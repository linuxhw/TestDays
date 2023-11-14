openSUSE - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for openSUSE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE/Desktop/README.md) and [notebooks](/Dist/openSUSE/Notebook/README.md).

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

Total: 3732

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f459ffa824](https://linux-hardware.org/?probe=f459ffa824) | Nov 06, 2023 |
| HP            | 82A2                        | Desktop     | [1d34952ece](https://linux-hardware.org/?probe=1d34952ece) | Nov 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [18053575fc](https://linux-hardware.org/?probe=18053575fc) | Nov 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [52781b1111](https://linux-hardware.org/?probe=52781b1111) | Nov 06, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [d40cc6e0a4](https://linux-hardware.org/?probe=d40cc6e0a4) | Nov 05, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [1c86a5a6de](https://linux-hardware.org/?probe=1c86a5a6de) | Nov 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9d79aa9486](https://linux-hardware.org/?probe=9d79aa9486) | Nov 05, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | Notebook    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Google        | Phaser360                   | Notebook    | [dbd0db9b7e](https://linux-hardware.org/?probe=dbd0db9b7e) | Nov 05, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [24e4446a67](https://linux-hardware.org/?probe=24e4446a67) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [263a417420](https://linux-hardware.org/?probe=263a417420) | Nov 05, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [a2b93486a9](https://linux-hardware.org/?probe=a2b93486a9) | Nov 05, 2023 |
| Notebook      | NL5xRU                      | Notebook    | [6dd04cca75](https://linux-hardware.org/?probe=6dd04cca75) | Nov 05, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [f8a30d78d3](https://linux-hardware.org/?probe=f8a30d78d3) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [ebf86ce161](https://linux-hardware.org/?probe=ebf86ce161) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [5eada91f48](https://linux-hardware.org/?probe=5eada91f48) | Nov 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [d1d65399a0](https://linux-hardware.org/?probe=d1d65399a0) | Nov 03, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [89e8c02e17](https://linux-hardware.org/?probe=89e8c02e17) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [e14eb66450](https://linux-hardware.org/?probe=e14eb66450) | Nov 03, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [1a0272a4ca](https://linux-hardware.org/?probe=1a0272a4ca) | Nov 02, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [8ce1afee32](https://linux-hardware.org/?probe=8ce1afee32) | Nov 02, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [98208c406a](https://linux-hardware.org/?probe=98208c406a) | Nov 02, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [54a7f5d1fa](https://linux-hardware.org/?probe=54a7f5d1fa) | Nov 02, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [175020104d](https://linux-hardware.org/?probe=175020104d) | Nov 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cdef3b5f1c](https://linux-hardware.org/?probe=cdef3b5f1c) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [137dba2261](https://linux-hardware.org/?probe=137dba2261) | Nov 02, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [1a9eef3748](https://linux-hardware.org/?probe=1a9eef3748) | Nov 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f72ba9e16b](https://linux-hardware.org/?probe=f72ba9e16b) | Nov 01, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [9893d57e1b](https://linux-hardware.org/?probe=9893d57e1b) | Nov 01, 2023 |
| ASUSTek       | M5A87                       | Desktop     | [b254c30981](https://linux-hardware.org/?probe=b254c30981) | Nov 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DDS0... | Notebook    | [ce44ee3f62](https://linux-hardware.org/?probe=ce44ee3f62) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d1e473a77b](https://linux-hardware.org/?probe=d1e473a77b) | Oct 31, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [c8ba0de51d](https://linux-hardware.org/?probe=c8ba0de51d) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2eaf76ce92](https://linux-hardware.org/?probe=2eaf76ce92) | Oct 31, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [1bdd8f14ad](https://linux-hardware.org/?probe=1bdd8f14ad) | Oct 31, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [4d6c2166c8](https://linux-hardware.org/?probe=4d6c2166c8) | Oct 30, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d5debf7011](https://linux-hardware.org/?probe=d5debf7011) | Oct 30, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [4b6c792eeb](https://linux-hardware.org/?probe=4b6c792eeb) | Oct 30, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [d16f2b19b0](https://linux-hardware.org/?probe=d16f2b19b0) | Oct 30, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [b5615554ee](https://linux-hardware.org/?probe=b5615554ee) | Oct 30, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [7d5dc09b04](https://linux-hardware.org/?probe=7d5dc09b04) | Oct 30, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [fa410ee23c](https://linux-hardware.org/?probe=fa410ee23c) | Oct 29, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [16417bdac2](https://linux-hardware.org/?probe=16417bdac2) | Oct 29, 2023 |
| Samsung       | Galaxy Book Go 5G           | Notebook    | [8f202d5648](https://linux-hardware.org/?probe=8f202d5648) | Oct 29, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [04e2b9cf4d](https://linux-hardware.org/?probe=04e2b9cf4d) | Oct 28, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [33d021b931](https://linux-hardware.org/?probe=33d021b931) | Oct 28, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [8b0a272a4e](https://linux-hardware.org/?probe=8b0a272a4e) | Oct 28, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [6aa696ac55](https://linux-hardware.org/?probe=6aa696ac55) | Oct 28, 2023 |
| Orange Pi     | 5 Plus                      | Soc         | [45f5ee6292](https://linux-hardware.org/?probe=45f5ee6292) | Oct 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [ae8894002e](https://linux-hardware.org/?probe=ae8894002e) | Oct 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [71ba004156](https://linux-hardware.org/?probe=71ba004156) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a8e35b3846](https://linux-hardware.org/?probe=a8e35b3846) | Oct 27, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [0990fc4382](https://linux-hardware.org/?probe=0990fc4382) | Oct 26, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [1b5677de0e](https://linux-hardware.org/?probe=1b5677de0e) | Oct 26, 2023 |
| Medion        | MS-7848                     | Desktop     | [ab89c9cc22](https://linux-hardware.org/?probe=ab89c9cc22) | Oct 26, 2023 |
| Intel         | NUC5i5RYB H40999-505        | Mini pc     | [78f407215c](https://linux-hardware.org/?probe=78f407215c) | Oct 26, 2023 |
| Intel         | NUC5i5RYB H40999-505        | Mini pc     | [f87489f8a3](https://linux-hardware.org/?probe=f87489f8a3) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX434FL             | Notebook    | [139d1a74ed](https://linux-hardware.org/?probe=139d1a74ed) | Oct 25, 2023 |
| Dell          | Precision M4700             | Notebook    | [0b95109eba](https://linux-hardware.org/?probe=0b95109eba) | Oct 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [39e846913d](https://linux-hardware.org/?probe=39e846913d) | Oct 25, 2023 |
| Lenovo        | ThinkPad P52 20MAS0WG00     | Notebook    | [e7e16a6ac8](https://linux-hardware.org/?probe=e7e16a6ac8) | Oct 25, 2023 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [99c1b311f1](https://linux-hardware.org/?probe=99c1b311f1) | Oct 25, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [926619798d](https://linux-hardware.org/?probe=926619798d) | Oct 25, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [504b1a1994](https://linux-hardware.org/?probe=504b1a1994) | Oct 25, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [0abcd8d89e](https://linux-hardware.org/?probe=0abcd8d89e) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [fb6910c3c6](https://linux-hardware.org/?probe=fb6910c3c6) | Oct 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [819d596b2e](https://linux-hardware.org/?probe=819d596b2e) | Oct 24, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a6d732c859](https://linux-hardware.org/?probe=a6d732c859) | Oct 24, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [1be0a39692](https://linux-hardware.org/?probe=1be0a39692) | Oct 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [48d2114a2e](https://linux-hardware.org/?probe=48d2114a2e) | Oct 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [8681ebe19c](https://linux-hardware.org/?probe=8681ebe19c) | Oct 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [b615345fa6](https://linux-hardware.org/?probe=b615345fa6) | Oct 21, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [edf8acb455](https://linux-hardware.org/?probe=edf8acb455) | Oct 21, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [75f2f0b411](https://linux-hardware.org/?probe=75f2f0b411) | Oct 21, 2023 |
| Samsung       | Galaxy Book Go 5G           | Notebook    | [db58c6b2e8](https://linux-hardware.org/?probe=db58c6b2e8) | Oct 21, 2023 |
| MSI           | Crosshair 15 B12UEZ         | Notebook    | [746189a3d8](https://linux-hardware.org/?probe=746189a3d8) | Oct 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [6a5182fc9c](https://linux-hardware.org/?probe=6a5182fc9c) | Oct 20, 2023 |
| ASRock        | Z270 Gaming K4              | Desktop     | [7de6bcb3b6](https://linux-hardware.org/?probe=7de6bcb3b6) | Oct 19, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [572daeb059](https://linux-hardware.org/?probe=572daeb059) | Oct 19, 2023 |
| Dell          | Latitude 5440               | Notebook    | [fa85c56dcb](https://linux-hardware.org/?probe=fa85c56dcb) | Oct 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d63ed71e40](https://linux-hardware.org/?probe=d63ed71e40) | Oct 17, 2023 |
| Lenovo        | ThinkPad P52 20MAS0WG00     | Notebook    | [edfeee597d](https://linux-hardware.org/?probe=edfeee597d) | Oct 17, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [a7f97ffc51](https://linux-hardware.org/?probe=a7f97ffc51) | Oct 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [81b0ac96b9](https://linux-hardware.org/?probe=81b0ac96b9) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [43d12d01b7](https://linux-hardware.org/?probe=43d12d01b7) | Oct 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [07b00a195f](https://linux-hardware.org/?probe=07b00a195f) | Oct 16, 2023 |
| HP            | ProBook 6560b               | Notebook    | [3567f55849](https://linux-hardware.org/?probe=3567f55849) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [dc34e61e94](https://linux-hardware.org/?probe=dc34e61e94) | Oct 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [d8cc0d7855](https://linux-hardware.org/?probe=d8cc0d7855) | Oct 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6e4a6a34cd](https://linux-hardware.org/?probe=6e4a6a34cd) | Oct 15, 2023 |
| Unknown       | V00                         | Mini pc     | [dc88db7cd5](https://linux-hardware.org/?probe=dc88db7cd5) | Oct 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [5586f17a5a](https://linux-hardware.org/?probe=5586f17a5a) | Oct 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [398445f93d](https://linux-hardware.org/?probe=398445f93d) | Oct 14, 2023 |
| HP            | ProBook 4535s               | Notebook    | [e52e92c95b](https://linux-hardware.org/?probe=e52e92c95b) | Oct 14, 2023 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [62688a7965](https://linux-hardware.org/?probe=62688a7965) | Oct 14, 2023 |
| Cube          | i18-BL                      | Notebook    | [0f2e9b2870](https://linux-hardware.org/?probe=0f2e9b2870) | Oct 14, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | Desktop     | [e550587c85](https://linux-hardware.org/?probe=e550587c85) | Oct 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [729234c285](https://linux-hardware.org/?probe=729234c285) | Oct 14, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [72fe96c3ea](https://linux-hardware.org/?probe=72fe96c3ea) | Oct 14, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [551ff39482](https://linux-hardware.org/?probe=551ff39482) | Oct 14, 2023 |
| HP            | Laptop 15s-du4xxx           | Notebook    | [8bec0ea3db](https://linux-hardware.org/?probe=8bec0ea3db) | Oct 14, 2023 |
| HP            | EliteBook 830 13 inch G1... | Notebook    | [e9ced529e2](https://linux-hardware.org/?probe=e9ced529e2) | Oct 14, 2023 |
| HP            | 2B4B                        | Desktop     | [8dc275b21d](https://linux-hardware.org/?probe=8dc275b21d) | Oct 13, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [56b055ab70](https://linux-hardware.org/?probe=56b055ab70) | Oct 12, 2023 |
| HP            | 3048h                       | Desktop     | [79350e657a](https://linux-hardware.org/?probe=79350e657a) | Oct 12, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [f33ca79691](https://linux-hardware.org/?probe=f33ca79691) | Oct 12, 2023 |
| Lenovo        | ThinkPad T400 27658JG       | Notebook    | [3b3b7832c9](https://linux-hardware.org/?probe=3b3b7832c9) | Oct 11, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [5e8749954f](https://linux-hardware.org/?probe=5e8749954f) | Oct 11, 2023 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [110e9a1566](https://linux-hardware.org/?probe=110e9a1566) | Oct 11, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [8b9a5127c0](https://linux-hardware.org/?probe=8b9a5127c0) | Oct 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [9ff3f35842](https://linux-hardware.org/?probe=9ff3f35842) | Oct 11, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [4e83b42f8d](https://linux-hardware.org/?probe=4e83b42f8d) | Oct 11, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6f2e3097a3](https://linux-hardware.org/?probe=6f2e3097a3) | Oct 10, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4c0b8f71c3](https://linux-hardware.org/?probe=4c0b8f71c3) | Oct 10, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [541d9a0542](https://linux-hardware.org/?probe=541d9a0542) | Oct 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [07a7cb2287](https://linux-hardware.org/?probe=07a7cb2287) | Oct 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [c98952b2ee](https://linux-hardware.org/?probe=c98952b2ee) | Oct 10, 2023 |
| Toshiba       | dynabook B452/22F           | Notebook    | [61777cd92a](https://linux-hardware.org/?probe=61777cd92a) | Oct 10, 2023 |
| ASRock        | Z270 Gaming K4              | Desktop     | [450e9268be](https://linux-hardware.org/?probe=450e9268be) | Oct 10, 2023 |
| Acer          | Aspire one                  | Notebook    | [302dc95903](https://linux-hardware.org/?probe=302dc95903) | Oct 09, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [814f6c5c52](https://linux-hardware.org/?probe=814f6c5c52) | Oct 09, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [954eecec42](https://linux-hardware.org/?probe=954eecec42) | Oct 09, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [1106658f2c](https://linux-hardware.org/?probe=1106658f2c) | Oct 09, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [a5d3c4e894](https://linux-hardware.org/?probe=a5d3c4e894) | Oct 09, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [d773c4faf0](https://linux-hardware.org/?probe=d773c4faf0) | Oct 09, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [5d51aca6b2](https://linux-hardware.org/?probe=5d51aca6b2) | Oct 08, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [9beb6f3b26](https://linux-hardware.org/?probe=9beb6f3b26) | Oct 08, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [e9b2c833e0](https://linux-hardware.org/?probe=e9b2c833e0) | Oct 08, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [4f2f37c5ba](https://linux-hardware.org/?probe=4f2f37c5ba) | Oct 08, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [61ffd24590](https://linux-hardware.org/?probe=61ffd24590) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [7b6ad19193](https://linux-hardware.org/?probe=7b6ad19193) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d8e06a9bf](https://linux-hardware.org/?probe=9d8e06a9bf) | Oct 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [bf5a7962a8](https://linux-hardware.org/?probe=bf5a7962a8) | Oct 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [da40fe16d9](https://linux-hardware.org/?probe=da40fe16d9) | Oct 07, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [f6fc0aee5b](https://linux-hardware.org/?probe=f6fc0aee5b) | Oct 07, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [c0c10b1767](https://linux-hardware.org/?probe=c0c10b1767) | Oct 07, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7d321bffa1](https://linux-hardware.org/?probe=7d321bffa1) | Oct 07, 2023 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [f542691a6b](https://linux-hardware.org/?probe=f542691a6b) | Oct 07, 2023 |
| ASUSTek       | Q550LF                      | Notebook    | [f666ae77d0](https://linux-hardware.org/?probe=f666ae77d0) | Oct 06, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [523e4c1ed6](https://linux-hardware.org/?probe=523e4c1ed6) | Oct 05, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [2070a1032e](https://linux-hardware.org/?probe=2070a1032e) | Oct 05, 2023 |
| Dell          | Precision M6500             | Notebook    | [18605f38d4](https://linux-hardware.org/?probe=18605f38d4) | Oct 05, 2023 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [274ebab6c4](https://linux-hardware.org/?probe=274ebab6c4) | Oct 04, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [2dd3582507](https://linux-hardware.org/?probe=2dd3582507) | Oct 04, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [d4ef6588b3](https://linux-hardware.org/?probe=d4ef6588b3) | Oct 04, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ab02b2a3e7](https://linux-hardware.org/?probe=ab02b2a3e7) | Oct 04, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [06d30a9c8d](https://linux-hardware.org/?probe=06d30a9c8d) | Oct 03, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [5b95d4de2f](https://linux-hardware.org/?probe=5b95d4de2f) | Oct 03, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [4817937b18](https://linux-hardware.org/?probe=4817937b18) | Oct 03, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9ea02c2b87](https://linux-hardware.org/?probe=9ea02c2b87) | Oct 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [001368f3a9](https://linux-hardware.org/?probe=001368f3a9) | Oct 03, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | Notebook    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [efd92c3198](https://linux-hardware.org/?probe=efd92c3198) | Oct 02, 2023 |
| ASUSTek       | VM40B                       | Desktop     | [461b7d03fb](https://linux-hardware.org/?probe=461b7d03fb) | Oct 02, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [d6c281a706](https://linux-hardware.org/?probe=d6c281a706) | Oct 01, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [411e8279da](https://linux-hardware.org/?probe=411e8279da) | Oct 01, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [bb5a34d03f](https://linux-hardware.org/?probe=bb5a34d03f) | Oct 01, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c8a525522f](https://linux-hardware.org/?probe=c8a525522f) | Sep 30, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [e2175cc32b](https://linux-hardware.org/?probe=e2175cc32b) | Sep 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a8bea5ed82](https://linux-hardware.org/?probe=a8bea5ed82) | Sep 30, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [5d41b45d45](https://linux-hardware.org/?probe=5d41b45d45) | Sep 30, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [a343a1c573](https://linux-hardware.org/?probe=a343a1c573) | Sep 30, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [65643e78ef](https://linux-hardware.org/?probe=65643e78ef) | Sep 30, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| HP            | 198E                        | Desktop     | [a311728a5f](https://linux-hardware.org/?probe=a311728a5f) | Sep 29, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [17584cef15](https://linux-hardware.org/?probe=17584cef15) | Sep 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [49090587ce](https://linux-hardware.org/?probe=49090587ce) | Sep 28, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [013801fc61](https://linux-hardware.org/?probe=013801fc61) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6fc52a277a](https://linux-hardware.org/?probe=6fc52a277a) | Sep 28, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [ee02fff8df](https://linux-hardware.org/?probe=ee02fff8df) | Sep 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [c09e747a85](https://linux-hardware.org/?probe=c09e747a85) | Sep 27, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a1a8055117](https://linux-hardware.org/?probe=a1a8055117) | Sep 27, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [9a3f695f09](https://linux-hardware.org/?probe=9a3f695f09) | Sep 27, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [0f2958c5a1](https://linux-hardware.org/?probe=0f2958c5a1) | Sep 27, 2023 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [74ea1c8adf](https://linux-hardware.org/?probe=74ea1c8adf) | Sep 27, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [844b7f2a1c](https://linux-hardware.org/?probe=844b7f2a1c) | Sep 27, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [0b586071f1](https://linux-hardware.org/?probe=0b586071f1) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 3 2... | Notebook    | [1903f91b48](https://linux-hardware.org/?probe=1903f91b48) | Sep 25, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3887b15fd0](https://linux-hardware.org/?probe=3887b15fd0) | Sep 25, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [666b064064](https://linux-hardware.org/?probe=666b064064) | Sep 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [4b2b76bdb3](https://linux-hardware.org/?probe=4b2b76bdb3) | Sep 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [723a872112](https://linux-hardware.org/?probe=723a872112) | Sep 24, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [eb82ffb863](https://linux-hardware.org/?probe=eb82ffb863) | Sep 24, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [01109ec772](https://linux-hardware.org/?probe=01109ec772) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [092bb813b4](https://linux-hardware.org/?probe=092bb813b4) | Sep 24, 2023 |
| Intel         | S1200RP G62254-407          | Server      | [1d003db534](https://linux-hardware.org/?probe=1d003db534) | Sep 24, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [f5ed151e3e](https://linux-hardware.org/?probe=f5ed151e3e) | Sep 24, 2023 |
| Dell          | Latitude 5440               | Notebook    | [255072aece](https://linux-hardware.org/?probe=255072aece) | Sep 24, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [f94566dde6](https://linux-hardware.org/?probe=f94566dde6) | Sep 23, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [ddac5bba05](https://linux-hardware.org/?probe=ddac5bba05) | Sep 23, 2023 |
| HP            | 15                          | Notebook    | [6d6b8bd8e3](https://linux-hardware.org/?probe=6d6b8bd8e3) | Sep 23, 2023 |
| Alienware     | m15 R3                      | Notebook    | [d9628d131b](https://linux-hardware.org/?probe=d9628d131b) | Sep 22, 2023 |
| HP            | ENVY 17                     | Notebook    | [4f6463148f](https://linux-hardware.org/?probe=4f6463148f) | Sep 22, 2023 |
| Lenovo        | ThinkPad W500 40624DG       | Notebook    | [9bdd448e89](https://linux-hardware.org/?probe=9bdd448e89) | Sep 22, 2023 |
| Medion        | E6224                       | Notebook    | [a6087c2bdf](https://linux-hardware.org/?probe=a6087c2bdf) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [efafe71bd6](https://linux-hardware.org/?probe=efafe71bd6) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [a1356bddb2](https://linux-hardware.org/?probe=a1356bddb2) | Sep 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [2a477b71f7](https://linux-hardware.org/?probe=2a477b71f7) | Sep 20, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a7eae64ec7](https://linux-hardware.org/?probe=a7eae64ec7) | Sep 20, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5fac0d7732](https://linux-hardware.org/?probe=5fac0d7732) | Sep 20, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [0f12c482a1](https://linux-hardware.org/?probe=0f12c482a1) | Sep 20, 2023 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [358b39a74a](https://linux-hardware.org/?probe=358b39a74a) | Sep 19, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [b962cd9626](https://linux-hardware.org/?probe=b962cd9626) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4398558915](https://linux-hardware.org/?probe=4398558915) | Sep 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [1bd2a17c99](https://linux-hardware.org/?probe=1bd2a17c99) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [d68a92e72a](https://linux-hardware.org/?probe=d68a92e72a) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [8b335d6bb0](https://linux-hardware.org/?probe=8b335d6bb0) | Sep 19, 2023 |
| Dell          | Latitude 5414               | Notebook    | [83589aaff4](https://linux-hardware.org/?probe=83589aaff4) | Sep 19, 2023 |
| ASRock        | Z590M Pro4                  | Desktop     | [d63be526d2](https://linux-hardware.org/?probe=d63be526d2) | Sep 18, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [39a50dc7e8](https://linux-hardware.org/?probe=39a50dc7e8) | Sep 18, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [2b11e9d8f5](https://linux-hardware.org/?probe=2b11e9d8f5) | Sep 18, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [1630396f5b](https://linux-hardware.org/?probe=1630396f5b) | Sep 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [4126504e2a](https://linux-hardware.org/?probe=4126504e2a) | Sep 17, 2023 |
| ANGXUN        | X99 V1.0                    | Desktop     | [c6c6277bf3](https://linux-hardware.org/?probe=c6c6277bf3) | Sep 17, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [038434c6a8](https://linux-hardware.org/?probe=038434c6a8) | Sep 16, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [f74d2ae164](https://linux-hardware.org/?probe=f74d2ae164) | Sep 16, 2023 |
| Acer          | Predator G3-710             | Desktop     | [aa2ac7f07c](https://linux-hardware.org/?probe=aa2ac7f07c) | Sep 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [76ca0d67e1](https://linux-hardware.org/?probe=76ca0d67e1) | Sep 16, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [81a1d404e3](https://linux-hardware.org/?probe=81a1d404e3) | Sep 15, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [0379270fb2](https://linux-hardware.org/?probe=0379270fb2) | Sep 15, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [8e044378bd](https://linux-hardware.org/?probe=8e044378bd) | Sep 15, 2023 |
| Dell          | Latitude 5501               | Notebook    | [1608104990](https://linux-hardware.org/?probe=1608104990) | Sep 14, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [6cc800f5dc](https://linux-hardware.org/?probe=6cc800f5dc) | Sep 14, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ad9f253d50](https://linux-hardware.org/?probe=ad9f253d50) | Sep 14, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [f445d0e46b](https://linux-hardware.org/?probe=f445d0e46b) | Sep 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [79e6e5fc48](https://linux-hardware.org/?probe=79e6e5fc48) | Sep 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [4714deba45](https://linux-hardware.org/?probe=4714deba45) | Sep 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [bd161c3850](https://linux-hardware.org/?probe=bd161c3850) | Sep 14, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [483bbfcc92](https://linux-hardware.org/?probe=483bbfcc92) | Sep 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [de53daa0f8](https://linux-hardware.org/?probe=de53daa0f8) | Sep 12, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8fc40b8424](https://linux-hardware.org/?probe=8fc40b8424) | Sep 12, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [718a7467d0](https://linux-hardware.org/?probe=718a7467d0) | Sep 12, 2023 |
| Alienware     | x14                         | Notebook    | [4fc435cc67](https://linux-hardware.org/?probe=4fc435cc67) | Sep 12, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [23f34b6e50](https://linux-hardware.org/?probe=23f34b6e50) | Sep 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [895c1ebe1c](https://linux-hardware.org/?probe=895c1ebe1c) | Sep 11, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [4de6e83768](https://linux-hardware.org/?probe=4de6e83768) | Sep 11, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [4d658a922b](https://linux-hardware.org/?probe=4d658a922b) | Sep 10, 2023 |
| Dell          | Precision 7540              | Notebook    | [ced1086a24](https://linux-hardware.org/?probe=ced1086a24) | Sep 09, 2023 |
| Dell          | Latitude 5431               | Notebook    | [41e4734fc7](https://linux-hardware.org/?probe=41e4734fc7) | Sep 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e8567c4d41](https://linux-hardware.org/?probe=e8567c4d41) | Sep 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [fe8d238cd4](https://linux-hardware.org/?probe=fe8d238cd4) | Sep 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [97fc2d4d2c](https://linux-hardware.org/?probe=97fc2d4d2c) | Sep 09, 2023 |
| HP            | 15                          | Notebook    | [189b38b9ac](https://linux-hardware.org/?probe=189b38b9ac) | Sep 08, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [d6a8fc3557](https://linux-hardware.org/?probe=d6a8fc3557) | Sep 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [e006d88ce8](https://linux-hardware.org/?probe=e006d88ce8) | Sep 08, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [299baaff27](https://linux-hardware.org/?probe=299baaff27) | Sep 08, 2023 |
| SLIMBOOK      | ONE-AM5                     | Desktop     | [0c8c554ff5](https://linux-hardware.org/?probe=0c8c554ff5) | Sep 08, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [394dd17b98](https://linux-hardware.org/?probe=394dd17b98) | Sep 07, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [d34f211b22](https://linux-hardware.org/?probe=d34f211b22) | Sep 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [2eae1044fc](https://linux-hardware.org/?probe=2eae1044fc) | Sep 07, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [098294fb47](https://linux-hardware.org/?probe=098294fb47) | Sep 07, 2023 |
| Lenovo        | IdeaPad Y580 2099           | Notebook    | [d0db961274](https://linux-hardware.org/?probe=d0db961274) | Sep 07, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [1e743d0b2d](https://linux-hardware.org/?probe=1e743d0b2d) | Sep 06, 2023 |
| HP            | ProBook 4530s               | Notebook    | [782493cb7d](https://linux-hardware.org/?probe=782493cb7d) | Sep 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [be4077d1c0](https://linux-hardware.org/?probe=be4077d1c0) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | Notebook    | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [0d796a5d20](https://linux-hardware.org/?probe=0d796a5d20) | Sep 05, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [12ed8aee3f](https://linux-hardware.org/?probe=12ed8aee3f) | Sep 05, 2023 |
| Panasonic     | CF-C2CUGZXKM                | Notebook    | [fdcab89946](https://linux-hardware.org/?probe=fdcab89946) | Sep 05, 2023 |
| Samsung       | 750QUA                      | Convertible | [d409932f7d](https://linux-hardware.org/?probe=d409932f7d) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [8253da4d01](https://linux-hardware.org/?probe=8253da4d01) | Sep 04, 2023 |
| HP            | 2129                        | Desktop     | [d021b12b77](https://linux-hardware.org/?probe=d021b12b77) | Sep 04, 2023 |
| ASRock        | Z490 Phantom Gaming 4/ac    | Desktop     | [5fa23571c9](https://linux-hardware.org/?probe=5fa23571c9) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [a0e83b70f5](https://linux-hardware.org/?probe=a0e83b70f5) | Sep 03, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [91bc08d933](https://linux-hardware.org/?probe=91bc08d933) | Sep 03, 2023 |
| Alienware     | m15 R7                      | Notebook    | [3d070813ea](https://linux-hardware.org/?probe=3d070813ea) | Sep 03, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [8ed88aa6f1](https://linux-hardware.org/?probe=8ed88aa6f1) | Sep 03, 2023 |
| Medion        | S15449                      | Notebook    | [7e8cd1a434](https://linux-hardware.org/?probe=7e8cd1a434) | Sep 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [78037f5e38](https://linux-hardware.org/?probe=78037f5e38) | Sep 02, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [1521626729](https://linux-hardware.org/?probe=1521626729) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [315510322c](https://linux-hardware.org/?probe=315510322c) | Sep 02, 2023 |
| Dell          | Precision 7560              | Notebook    | [d9d73d82f2](https://linux-hardware.org/?probe=d9d73d82f2) | Sep 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [318dc8ce55](https://linux-hardware.org/?probe=318dc8ce55) | Sep 01, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [0a46c781fc](https://linux-hardware.org/?probe=0a46c781fc) | Sep 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [e7c4150ded](https://linux-hardware.org/?probe=e7c4150ded) | Sep 01, 2023 |
| Lenovo        | ThinkPad T420 42364A1       | Notebook    | [968cd5e999](https://linux-hardware.org/?probe=968cd5e999) | Aug 31, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [b68a6514c4](https://linux-hardware.org/?probe=b68a6514c4) | Aug 30, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [43e624c0b4](https://linux-hardware.org/?probe=43e624c0b4) | Aug 30, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ad844f1a8c](https://linux-hardware.org/?probe=ad844f1a8c) | Aug 30, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [0c279f8cf0](https://linux-hardware.org/?probe=0c279f8cf0) | Aug 30, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [75acf7c3bf](https://linux-hardware.org/?probe=75acf7c3bf) | Aug 30, 2023 |
| Dell          | 0K06NC A00                  | All in one  | [616c88aa53](https://linux-hardware.org/?probe=616c88aa53) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | Notebook    | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Huanan        | X99-ZD4 V2.1                | Desktop     | [2ab7a21e20](https://linux-hardware.org/?probe=2ab7a21e20) | Aug 29, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [a9cd91e3be](https://linux-hardware.org/?probe=a9cd91e3be) | Aug 28, 2023 |
| Dell          | 068CDY A01                  | Server      | [1debff900a](https://linux-hardware.org/?probe=1debff900a) | Aug 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [11d516749d](https://linux-hardware.org/?probe=11d516749d) | Aug 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [960039f680](https://linux-hardware.org/?probe=960039f680) | Aug 28, 2023 |
| Gigabyte      | B75M-D3P                    | Desktop     | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [b2ecdef159](https://linux-hardware.org/?probe=b2ecdef159) | Aug 27, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [08ec98196f](https://linux-hardware.org/?probe=08ec98196f) | Aug 27, 2023 |
| Biostar       | B550GTA                     | Desktop     | [218cce14a5](https://linux-hardware.org/?probe=218cce14a5) | Aug 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [821972776e](https://linux-hardware.org/?probe=821972776e) | Aug 26, 2023 |
| HP            | 2129                        | Desktop     | [7ebe21012d](https://linux-hardware.org/?probe=7ebe21012d) | Aug 26, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [c5b6554c6b](https://linux-hardware.org/?probe=c5b6554c6b) | Aug 26, 2023 |
| Dell          | Vostro 1450                 | Notebook    | [1aad0f5aa3](https://linux-hardware.org/?probe=1aad0f5aa3) | Aug 26, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b2f6ae2fdd](https://linux-hardware.org/?probe=b2f6ae2fdd) | Aug 26, 2023 |
| Dell          | Latitude E6440              | Notebook    | [1a9a8b3267](https://linux-hardware.org/?probe=1a9a8b3267) | Aug 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [adb5d31da7](https://linux-hardware.org/?probe=adb5d31da7) | Aug 25, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [083aa2f63c](https://linux-hardware.org/?probe=083aa2f63c) | Aug 25, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [825725cf8d](https://linux-hardware.org/?probe=825725cf8d) | Aug 25, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f5e13ec783](https://linux-hardware.org/?probe=f5e13ec783) | Aug 25, 2023 |
| Dell          | Latitude 3440               | Notebook    | [ec46985a7b](https://linux-hardware.org/?probe=ec46985a7b) | Aug 24, 2023 |
| ASUSTek       | Z9NA-D6                     | Server      | [4e4302c5f0](https://linux-hardware.org/?probe=4e4302c5f0) | Aug 24, 2023 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [58d50740e7](https://linux-hardware.org/?probe=58d50740e7) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [28c491dd90](https://linux-hardware.org/?probe=28c491dd90) | Aug 23, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [e5e47ca15c](https://linux-hardware.org/?probe=e5e47ca15c) | Aug 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6b9175d89e](https://linux-hardware.org/?probe=6b9175d89e) | Aug 22, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a89271bc7d](https://linux-hardware.org/?probe=a89271bc7d) | Aug 22, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [10345216a9](https://linux-hardware.org/?probe=10345216a9) | Aug 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [625ff7df38](https://linux-hardware.org/?probe=625ff7df38) | Aug 22, 2023 |
| Biostar       | TF570 SLI A2+               | Desktop     | [3d706eb2f3](https://linux-hardware.org/?probe=3d706eb2f3) | Aug 21, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [2e8b5e3b34](https://linux-hardware.org/?probe=2e8b5e3b34) | Aug 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | Notebook    | [1a86753f1c](https://linux-hardware.org/?probe=1a86753f1c) | Aug 20, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [99cdeba16c](https://linux-hardware.org/?probe=99cdeba16c) | Aug 20, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [58eff7a9fb](https://linux-hardware.org/?probe=58eff7a9fb) | Aug 20, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [857e3132c1](https://linux-hardware.org/?probe=857e3132c1) | Aug 19, 2023 |
| ASRock        | Z270 Pro4                   | Desktop     | [de0587ccf3](https://linux-hardware.org/?probe=de0587ccf3) | Aug 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [60545dcc97](https://linux-hardware.org/?probe=60545dcc97) | Aug 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [f59c0429a1](https://linux-hardware.org/?probe=f59c0429a1) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6249529a81](https://linux-hardware.org/?probe=6249529a81) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [a58174338d](https://linux-hardware.org/?probe=a58174338d) | Aug 18, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [2c42cc3ebb](https://linux-hardware.org/?probe=2c42cc3ebb) | Aug 18, 2023 |
| Dell          | Latitude 5414               | Notebook    | [0716b41629](https://linux-hardware.org/?probe=0716b41629) | Aug 18, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e21dbce888](https://linux-hardware.org/?probe=e21dbce888) | Aug 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [5a62fd8541](https://linux-hardware.org/?probe=5a62fd8541) | Aug 17, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [98629bd8c4](https://linux-hardware.org/?probe=98629bd8c4) | Aug 17, 2023 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [6fedf0eae5](https://linux-hardware.org/?probe=6fedf0eae5) | Aug 17, 2023 |
| Dell          | Latitude 7290               | Notebook    | [eb12e0d829](https://linux-hardware.org/?probe=eb12e0d829) | Aug 17, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [4c36ef643e](https://linux-hardware.org/?probe=4c36ef643e) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [d2b1d6e9ad](https://linux-hardware.org/?probe=d2b1d6e9ad) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [cf9cfddfa5](https://linux-hardware.org/?probe=cf9cfddfa5) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [6c3b1a6ddd](https://linux-hardware.org/?probe=6c3b1a6ddd) | Aug 16, 2023 |
| Dell          | Latitude 5414               | Notebook    | [74b8020613](https://linux-hardware.org/?probe=74b8020613) | Aug 16, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [0954ff78e7](https://linux-hardware.org/?probe=0954ff78e7) | Aug 16, 2023 |
| ASUSTek       | M4A77TD                     | Desktop     | [a2c6278e77](https://linux-hardware.org/?probe=a2c6278e77) | Aug 15, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [620d12291b](https://linux-hardware.org/?probe=620d12291b) | Aug 15, 2023 |
| Toshiba       | Satellite Pro C70-A         | Notebook    | [dbb00fe95b](https://linux-hardware.org/?probe=dbb00fe95b) | Aug 15, 2023 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [488d5ee081](https://linux-hardware.org/?probe=488d5ee081) | Aug 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4e79ef6905](https://linux-hardware.org/?probe=4e79ef6905) | Aug 15, 2023 |
| Dell          | Latitude 5414               | Notebook    | [de4295d568](https://linux-hardware.org/?probe=de4295d568) | Aug 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5432051007](https://linux-hardware.org/?probe=5432051007) | Aug 15, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cbd08a7649](https://linux-hardware.org/?probe=cbd08a7649) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b62ff7f358](https://linux-hardware.org/?probe=b62ff7f358) | Aug 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [ceebf749ba](https://linux-hardware.org/?probe=ceebf749ba) | Aug 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [f523831970](https://linux-hardware.org/?probe=f523831970) | Aug 14, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [53717914de](https://linux-hardware.org/?probe=53717914de) | Aug 14, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e2fadc37f2](https://linux-hardware.org/?probe=e2fadc37f2) | Aug 14, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [b0e10f6505](https://linux-hardware.org/?probe=b0e10f6505) | Aug 13, 2023 |
| Intel         | DX58OG AAG10926-205         | Desktop     | [cb3a9289f9](https://linux-hardware.org/?probe=cb3a9289f9) | Aug 13, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [66bcc74be2](https://linux-hardware.org/?probe=66bcc74be2) | Aug 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [f0f6b13bf3](https://linux-hardware.org/?probe=f0f6b13bf3) | Aug 13, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [d1fddefbb1](https://linux-hardware.org/?probe=d1fddefbb1) | Aug 13, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [cf6dfa50ef](https://linux-hardware.org/?probe=cf6dfa50ef) | Aug 12, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d3d3ef7119](https://linux-hardware.org/?probe=d3d3ef7119) | Aug 12, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [5d96610622](https://linux-hardware.org/?probe=5d96610622) | Aug 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [a737674e04](https://linux-hardware.org/?probe=a737674e04) | Aug 12, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e374cc3341](https://linux-hardware.org/?probe=e374cc3341) | Aug 12, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [9aa2cd7b81](https://linux-hardware.org/?probe=9aa2cd7b81) | Aug 12, 2023 |
| Dell          | G7 7790                     | Notebook    | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| HP            | 1589                        | Desktop     | [1a38154020](https://linux-hardware.org/?probe=1a38154020) | Aug 12, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8193c225e5](https://linux-hardware.org/?probe=8193c225e5) | Aug 11, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [8ad81394c8](https://linux-hardware.org/?probe=8ad81394c8) | Aug 11, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [1c2e98b598](https://linux-hardware.org/?probe=1c2e98b598) | Aug 11, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [cbd4a63b2e](https://linux-hardware.org/?probe=cbd4a63b2e) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [9ce8c0dd74](https://linux-hardware.org/?probe=9ce8c0dd74) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f4dd9cbbbd](https://linux-hardware.org/?probe=f4dd9cbbbd) | Aug 10, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c2b7b4e760](https://linux-hardware.org/?probe=c2b7b4e760) | Aug 10, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [45c782fc7e](https://linux-hardware.org/?probe=45c782fc7e) | Aug 10, 2023 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [0ca6c48c2f](https://linux-hardware.org/?probe=0ca6c48c2f) | Aug 09, 2023 |
| HP            | 8433 11                     | Desktop     | [eac08c7b54](https://linux-hardware.org/?probe=eac08c7b54) | Aug 09, 2023 |
| Dell          | 0272WF A00                  | Server      | [39abbc5ab8](https://linux-hardware.org/?probe=39abbc5ab8) | Aug 09, 2023 |
| Lenovo        | SDK0E50510 WIN 262508147... | Desktop     | [badd1c22ff](https://linux-hardware.org/?probe=badd1c22ff) | Aug 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [fdbe025351](https://linux-hardware.org/?probe=fdbe025351) | Aug 09, 2023 |
| Lenovo        | SDK0E50510 WIN 262508147... | Desktop     | [f74262edcd](https://linux-hardware.org/?probe=f74262edcd) | Aug 09, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7d1e95601c](https://linux-hardware.org/?probe=7d1e95601c) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| Dell          | Precision 7740              | Notebook    | [954d8472e5](https://linux-hardware.org/?probe=954d8472e5) | Aug 09, 2023 |
| Dell          | 0DT021 A00                  | Server      | [f472313f3a](https://linux-hardware.org/?probe=f472313f3a) | Aug 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [88c76f027a](https://linux-hardware.org/?probe=88c76f027a) | Aug 08, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [3fea8d650e](https://linux-hardware.org/?probe=3fea8d650e) | Aug 08, 2023 |
| AZW           | MINI S 10                   | Desktop     | [1de6b9a754](https://linux-hardware.org/?probe=1de6b9a754) | Aug 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [2fa2ae29cc](https://linux-hardware.org/?probe=2fa2ae29cc) | Aug 07, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [bb99f6f69e](https://linux-hardware.org/?probe=bb99f6f69e) | Aug 07, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [35e4fef6c6](https://linux-hardware.org/?probe=35e4fef6c6) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [37bf6e8191](https://linux-hardware.org/?probe=37bf6e8191) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b1d5aab527](https://linux-hardware.org/?probe=b1d5aab527) | Aug 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| HP            | 2B4B                        | Desktop     | [f85fada33f](https://linux-hardware.org/?probe=f85fada33f) | Aug 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [ee882ba789](https://linux-hardware.org/?probe=ee882ba789) | Aug 06, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea4d9240fb](https://linux-hardware.org/?probe=ea4d9240fb) | Aug 05, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f8f4442b09](https://linux-hardware.org/?probe=f8f4442b09) | Aug 05, 2023 |
| ASUSTek       | Z97-PRO/USB                 | Desktop     | [edd74878c3](https://linux-hardware.org/?probe=edd74878c3) | Aug 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [297a14921c](https://linux-hardware.org/?probe=297a14921c) | Aug 04, 2023 |
| HP            | 470 G7 Notebook PC          | Notebook    | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [420353bf79](https://linux-hardware.org/?probe=420353bf79) | Aug 04, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [a9072f3117](https://linux-hardware.org/?probe=a9072f3117) | Aug 04, 2023 |
| Dell          | 0DT021 A00                  | Server      | [354c40df4e](https://linux-hardware.org/?probe=354c40df4e) | Aug 04, 2023 |
| MSI           | H81M-E35 V2                 | Desktop     | [2e72dc6560](https://linux-hardware.org/?probe=2e72dc6560) | Aug 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [90aecb9ada](https://linux-hardware.org/?probe=90aecb9ada) | Aug 04, 2023 |
| Dell          | 0W13NR A06                  | Server      | [b1820a9229](https://linux-hardware.org/?probe=b1820a9229) | Aug 04, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b2004d5d59](https://linux-hardware.org/?probe=b2004d5d59) | Aug 04, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [46e96687a1](https://linux-hardware.org/?probe=46e96687a1) | Aug 04, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [1318f4d842](https://linux-hardware.org/?probe=1318f4d842) | Aug 03, 2023 |
| Dell          | 082WXT A03                  | Desktop     | [27a50c4491](https://linux-hardware.org/?probe=27a50c4491) | Aug 03, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [573e7f6ad0](https://linux-hardware.org/?probe=573e7f6ad0) | Aug 03, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e5649696d0](https://linux-hardware.org/?probe=e5649696d0) | Aug 03, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [b684b97e44](https://linux-hardware.org/?probe=b684b97e44) | Aug 02, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [aa4285c237](https://linux-hardware.org/?probe=aa4285c237) | Aug 02, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8fb651def8](https://linux-hardware.org/?probe=8fb651def8) | Aug 02, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [6a4cd21dbf](https://linux-hardware.org/?probe=6a4cd21dbf) | Aug 02, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [982148fe9c](https://linux-hardware.org/?probe=982148fe9c) | Aug 02, 2023 |
| Schenker      | XMG FOCUS (Mid 2021)        | Notebook    | [d7fa14789f](https://linux-hardware.org/?probe=d7fa14789f) | Aug 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [bc84705e8f](https://linux-hardware.org/?probe=bc84705e8f) | Aug 01, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [89bc7e5c48](https://linux-hardware.org/?probe=89bc7e5c48) | Aug 01, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | Notebook    | [f353e39414](https://linux-hardware.org/?probe=f353e39414) | Jul 31, 2023 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [8cb9cf099a](https://linux-hardware.org/?probe=8cb9cf099a) | Jul 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [940a0b000a](https://linux-hardware.org/?probe=940a0b000a) | Jul 31, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [356dae8360](https://linux-hardware.org/?probe=356dae8360) | Jul 30, 2023 |
| Lenovo        | ThinkPad T440p 20AN009FG... | Notebook    | [f2cc6379cc](https://linux-hardware.org/?probe=f2cc6379cc) | Jul 30, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9d93bef2df](https://linux-hardware.org/?probe=9d93bef2df) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [24c271e6fd](https://linux-hardware.org/?probe=24c271e6fd) | Jul 30, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [bb2245d195](https://linux-hardware.org/?probe=bb2245d195) | Jul 30, 2023 |
| Dell          | 0272WF A00                  | Server      | [ab789b12e1](https://linux-hardware.org/?probe=ab789b12e1) | Jul 30, 2023 |
| Biostar       | A320MH                      | Desktop     | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c098429c68](https://linux-hardware.org/?probe=c098429c68) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Dell          | 0272WF A00                  | Server      | [2867ef6d1f](https://linux-hardware.org/?probe=2867ef6d1f) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [3a81b2b0d9](https://linux-hardware.org/?probe=3a81b2b0d9) | Jul 29, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [4d6a620df3](https://linux-hardware.org/?probe=4d6a620df3) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [07feda799a](https://linux-hardware.org/?probe=07feda799a) | Jul 28, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [270ce3344c](https://linux-hardware.org/?probe=270ce3344c) | Jul 28, 2023 |
| HP            | 250 G3                      | Notebook    | [49b5a143cf](https://linux-hardware.org/?probe=49b5a143cf) | Jul 28, 2023 |
| Sony          | Unknown                     | Notebook    | [80613731cb](https://linux-hardware.org/?probe=80613731cb) | Jul 28, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [ba47e8e20f](https://linux-hardware.org/?probe=ba47e8e20f) | Jul 27, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [7e89496549](https://linux-hardware.org/?probe=7e89496549) | Jul 27, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [3652a64ac1](https://linux-hardware.org/?probe=3652a64ac1) | Jul 27, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [75dec2a4a4](https://linux-hardware.org/?probe=75dec2a4a4) | Jul 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0a79ddb19](https://linux-hardware.org/?probe=a0a79ddb19) | Jul 27, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [af1671633e](https://linux-hardware.org/?probe=af1671633e) | Jul 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ed591a913a](https://linux-hardware.org/?probe=ed591a913a) | Jul 26, 2023 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [0cb1602cad](https://linux-hardware.org/?probe=0cb1602cad) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [9d891afae0](https://linux-hardware.org/?probe=9d891afae0) | Jul 26, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [10db13c772](https://linux-hardware.org/?probe=10db13c772) | Jul 26, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [1568ba2843](https://linux-hardware.org/?probe=1568ba2843) | Jul 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [d23913a471](https://linux-hardware.org/?probe=d23913a471) | Jul 25, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [5300c80b7e](https://linux-hardware.org/?probe=5300c80b7e) | Jul 24, 2023 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [533c44b02e](https://linux-hardware.org/?probe=533c44b02e) | Jul 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3ba6058c7](https://linux-hardware.org/?probe=d3ba6058c7) | Jul 24, 2023 |
| HP            | 1589                        | Desktop     | [5c0bd1ec07](https://linux-hardware.org/?probe=5c0bd1ec07) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [fd2add1e0f](https://linux-hardware.org/?probe=fd2add1e0f) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [b7c7b058b7](https://linux-hardware.org/?probe=b7c7b058b7) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [405387be09](https://linux-hardware.org/?probe=405387be09) | Jul 23, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [447b84f067](https://linux-hardware.org/?probe=447b84f067) | Jul 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f0dcdf797e](https://linux-hardware.org/?probe=f0dcdf797e) | Jul 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [49fc9fb8ce](https://linux-hardware.org/?probe=49fc9fb8ce) | Jul 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [c741f10f18](https://linux-hardware.org/?probe=c741f10f18) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [83df4e51e4](https://linux-hardware.org/?probe=83df4e51e4) | Jul 22, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [47cf8f41db](https://linux-hardware.org/?probe=47cf8f41db) | Jul 22, 2023 |
| MSI           | X58 Pro-E                   | Desktop     | [01f822dec1](https://linux-hardware.org/?probe=01f822dec1) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cda75b5e7a](https://linux-hardware.org/?probe=cda75b5e7a) | Jul 22, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [b00e97471c](https://linux-hardware.org/?probe=b00e97471c) | Jul 22, 2023 |
| Medion        | E6224                       | Notebook    | [c33b8a1fb1](https://linux-hardware.org/?probe=c33b8a1fb1) | Jul 22, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [4c5a8d18b9](https://linux-hardware.org/?probe=4c5a8d18b9) | Jul 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| MSI           | GL72 6QF                    | Notebook    | [0484bc209c](https://linux-hardware.org/?probe=0484bc209c) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [7b6300dfc7](https://linux-hardware.org/?probe=7b6300dfc7) | Jul 20, 2023 |
| Sony          | Unknown                     | Notebook    | [427e52d6a6](https://linux-hardware.org/?probe=427e52d6a6) | Jul 20, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [65da6837ae](https://linux-hardware.org/?probe=65da6837ae) | Jul 20, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [a2779c6ac8](https://linux-hardware.org/?probe=a2779c6ac8) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [158ce24cd5](https://linux-hardware.org/?probe=158ce24cd5) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2f067394f6](https://linux-hardware.org/?probe=2f067394f6) | Jul 19, 2023 |
| Acer          | MCP7A                       | Desktop     | [06afe36113](https://linux-hardware.org/?probe=06afe36113) | Jul 18, 2023 |
| Dell          | XPS L501X                   | Notebook    | [0879ff6b9d](https://linux-hardware.org/?probe=0879ff6b9d) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [af9244e836](https://linux-hardware.org/?probe=af9244e836) | Jul 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b48286d288](https://linux-hardware.org/?probe=b48286d288) | Jul 18, 2023 |
| Lenovo        | ThinkPad E480 20KN005CRT    | Notebook    | [722170f1f3](https://linux-hardware.org/?probe=722170f1f3) | Jul 17, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [0236d26da7](https://linux-hardware.org/?probe=0236d26da7) | Jul 17, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [fe065234a9](https://linux-hardware.org/?probe=fe065234a9) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [7ca76c0d32](https://linux-hardware.org/?probe=7ca76c0d32) | Jul 17, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [52d550e878](https://linux-hardware.org/?probe=52d550e878) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [4c3185f447](https://linux-hardware.org/?probe=4c3185f447) | Jul 17, 2023 |
| Medion        | E6224                       | Notebook    | [4ffae87044](https://linux-hardware.org/?probe=4ffae87044) | Jul 17, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [81db5657d9](https://linux-hardware.org/?probe=81db5657d9) | Jul 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [553bd7c29e](https://linux-hardware.org/?probe=553bd7c29e) | Jul 16, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [d9270dc2df](https://linux-hardware.org/?probe=d9270dc2df) | Jul 16, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Irbis         | NB131                       | Convertible | [c7efdcc615](https://linux-hardware.org/?probe=c7efdcc615) | Jul 15, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [01b8ada2a7](https://linux-hardware.org/?probe=01b8ada2a7) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| Irbis         | NB131                       | Convertible | [b14dbb093f](https://linux-hardware.org/?probe=b14dbb093f) | Jul 15, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [d1aa3f2d70](https://linux-hardware.org/?probe=d1aa3f2d70) | Jul 15, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [1917d24a87](https://linux-hardware.org/?probe=1917d24a87) | Jul 15, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [34871aac58](https://linux-hardware.org/?probe=34871aac58) | Jul 15, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [a2bb315c61](https://linux-hardware.org/?probe=a2bb315c61) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [874f8b41a7](https://linux-hardware.org/?probe=874f8b41a7) | Jul 14, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [78f620581b](https://linux-hardware.org/?probe=78f620581b) | Jul 14, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [9760be79b1](https://linux-hardware.org/?probe=9760be79b1) | Jul 13, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [542d77f366](https://linux-hardware.org/?probe=542d77f366) | Jul 13, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [35373c9acf](https://linux-hardware.org/?probe=35373c9acf) | Jul 13, 2023 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [9b03d78d55](https://linux-hardware.org/?probe=9b03d78d55) | Jul 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [e56a404324](https://linux-hardware.org/?probe=e56a404324) | Jul 13, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [480fe73577](https://linux-hardware.org/?probe=480fe73577) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [bc78a01502](https://linux-hardware.org/?probe=bc78a01502) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [c01febb128](https://linux-hardware.org/?probe=c01febb128) | Jul 12, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1c7a630efb](https://linux-hardware.org/?probe=1c7a630efb) | Jul 12, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [458df6678a](https://linux-hardware.org/?probe=458df6678a) | Jul 12, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [93d94feca6](https://linux-hardware.org/?probe=93d94feca6) | Jul 11, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [7aac135bc0](https://linux-hardware.org/?probe=7aac135bc0) | Jul 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [becf9726c7](https://linux-hardware.org/?probe=becf9726c7) | Jul 11, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [90f5732595](https://linux-hardware.org/?probe=90f5732595) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a52e535dcb](https://linux-hardware.org/?probe=a52e535dcb) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e9a45b4e27](https://linux-hardware.org/?probe=e9a45b4e27) | Jul 11, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [1a540134de](https://linux-hardware.org/?probe=1a540134de) | Jul 11, 2023 |
| Dell          | Latitude E5410              | Notebook    | [8d980136c2](https://linux-hardware.org/?probe=8d980136c2) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [8c2add9768](https://linux-hardware.org/?probe=8c2add9768) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [2cc9f44232](https://linux-hardware.org/?probe=2cc9f44232) | Jul 10, 2023 |
| Medion        | Akoya P2214T                | Notebook    | [341fc04e6c](https://linux-hardware.org/?probe=341fc04e6c) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [36b6c49552](https://linux-hardware.org/?probe=36b6c49552) | Jul 09, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [6d96bf0f5b](https://linux-hardware.org/?probe=6d96bf0f5b) | Jul 09, 2023 |
| Lenovo        | Unknown                     | Convertible | [7c4ddbebf7](https://linux-hardware.org/?probe=7c4ddbebf7) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [ffa5984711](https://linux-hardware.org/?probe=ffa5984711) | Jul 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [5d91f63280](https://linux-hardware.org/?probe=5d91f63280) | Jul 09, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [c00debe968](https://linux-hardware.org/?probe=c00debe968) | Jul 08, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [a72d3eff75](https://linux-hardware.org/?probe=a72d3eff75) | Jul 08, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [8a5cbee239](https://linux-hardware.org/?probe=8a5cbee239) | Jul 08, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9fc07d1102](https://linux-hardware.org/?probe=9fc07d1102) | Jul 08, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [f94c183910](https://linux-hardware.org/?probe=f94c183910) | Jul 08, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [dde4874147](https://linux-hardware.org/?probe=dde4874147) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7cbaa33271](https://linux-hardware.org/?probe=7cbaa33271) | Jul 07, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [bb2f259ef6](https://linux-hardware.org/?probe=bb2f259ef6) | Jul 07, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [f32ffc678f](https://linux-hardware.org/?probe=f32ffc678f) | Jul 07, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [54262c3aeb](https://linux-hardware.org/?probe=54262c3aeb) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [79166ca12f](https://linux-hardware.org/?probe=79166ca12f) | Jul 07, 2023 |
| Medion        | Akoya P2214T                | Notebook    | [e2c31b421a](https://linux-hardware.org/?probe=e2c31b421a) | Jul 07, 2023 |
| Lenovo        | 20RD001FHV                  | Notebook    | [de3ed49995](https://linux-hardware.org/?probe=de3ed49995) | Jul 07, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [5ee0aa7d94](https://linux-hardware.org/?probe=5ee0aa7d94) | Jul 07, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [0d98ce8578](https://linux-hardware.org/?probe=0d98ce8578) | Jul 07, 2023 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f156a2bbfa](https://linux-hardware.org/?probe=f156a2bbfa) | Jul 06, 2023 |
| HP            | 8B3B A                      | Desktop     | [b003988978](https://linux-hardware.org/?probe=b003988978) | Jul 05, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [b3530f3e0e](https://linux-hardware.org/?probe=b3530f3e0e) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | Desktop     | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Acer          | Swift SF114-33              | Notebook    | [e3bd5bf60f](https://linux-hardware.org/?probe=e3bd5bf60f) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [40b7950cb2](https://linux-hardware.org/?probe=40b7950cb2) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [73435e5646](https://linux-hardware.org/?probe=73435e5646) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [eef5ee5c9a](https://linux-hardware.org/?probe=eef5ee5c9a) | Jul 05, 2023 |
| Teclast       | X4                          | Tablet      | [6aab5b6610](https://linux-hardware.org/?probe=6aab5b6610) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6b1beb7eeb](https://linux-hardware.org/?probe=6b1beb7eeb) | Jul 05, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [427fc931a0](https://linux-hardware.org/?probe=427fc931a0) | Jul 04, 2023 |
| Gigabyte      | Z690 AERO D                 | Desktop     | [f42140d294](https://linux-hardware.org/?probe=f42140d294) | Jul 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9561990119](https://linux-hardware.org/?probe=9561990119) | Jul 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [bc2c3c520a](https://linux-hardware.org/?probe=bc2c3c520a) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [57f5458dfa](https://linux-hardware.org/?probe=57f5458dfa) | Jul 02, 2023 |
| ASUSTek       | P5E Deluxe                  | Desktop     | [895759fa79](https://linux-hardware.org/?probe=895759fa79) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | Notebook    | [a1fc2e0020](https://linux-hardware.org/?probe=a1fc2e0020) | Jul 01, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [3702fd669f](https://linux-hardware.org/?probe=3702fd669f) | Jul 01, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [10dc1c07c8](https://linux-hardware.org/?probe=10dc1c07c8) | Jul 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d9b6645cae](https://linux-hardware.org/?probe=d9b6645cae) | Jul 01, 2023 |
| HP            | ProBook 455 G6              | Notebook    | [f4b853f43e](https://linux-hardware.org/?probe=f4b853f43e) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Gigabyte      | P67A-UD5-B3                 | Desktop     | [b763c860fa](https://linux-hardware.org/?probe=b763c860fa) | Jun 30, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [5e11bea093](https://linux-hardware.org/?probe=5e11bea093) | Jun 30, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [ef3b3cf51e](https://linux-hardware.org/?probe=ef3b3cf51e) | Jun 30, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [70ddebe460](https://linux-hardware.org/?probe=70ddebe460) | Jun 30, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [7ae106bfd6](https://linux-hardware.org/?probe=7ae106bfd6) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [70ce1e280f](https://linux-hardware.org/?probe=70ce1e280f) | Jun 30, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [b5e0044759](https://linux-hardware.org/?probe=b5e0044759) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [47536e2cde](https://linux-hardware.org/?probe=47536e2cde) | Jun 29, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [64e81a22a5](https://linux-hardware.org/?probe=64e81a22a5) | Jun 29, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6c7621fe04](https://linux-hardware.org/?probe=6c7621fe04) | Jun 29, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6cc649e9ba](https://linux-hardware.org/?probe=6cc649e9ba) | Jun 29, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2dd6be0ddc](https://linux-hardware.org/?probe=2dd6be0ddc) | Jun 29, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | Notebook    | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [9d4c4f5506](https://linux-hardware.org/?probe=9d4c4f5506) | Jun 29, 2023 |
| HP            | 1589                        | Desktop     | [dcb3289360](https://linux-hardware.org/?probe=dcb3289360) | Jun 29, 2023 |
| Dell          | 00X7CK A04                  | Server      | [c59e7b7f26](https://linux-hardware.org/?probe=c59e7b7f26) | Jun 28, 2023 |
| Intel         | DG965SS AAD41678-304        | Desktop     | [696cd9ce01](https://linux-hardware.org/?probe=696cd9ce01) | Jun 28, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1ef1762ac3](https://linux-hardware.org/?probe=1ef1762ac3) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6a29eda577](https://linux-hardware.org/?probe=6a29eda577) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bf4abd6e9e](https://linux-hardware.org/?probe=bf4abd6e9e) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [3ea9e41d03](https://linux-hardware.org/?probe=3ea9e41d03) | Jun 28, 2023 |
| Gigabyte      | EG45M-DS2H                  | Desktop     | [b9b25df5a3](https://linux-hardware.org/?probe=b9b25df5a3) | Jun 27, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [465cc8968f](https://linux-hardware.org/?probe=465cc8968f) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [fce3ec0379](https://linux-hardware.org/?probe=fce3ec0379) | Jun 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [97b1fc630a](https://linux-hardware.org/?probe=97b1fc630a) | Jun 25, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8c0f33ffe](https://linux-hardware.org/?probe=a8c0f33ffe) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [17c221fa68](https://linux-hardware.org/?probe=17c221fa68) | Jun 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6c015f633b](https://linux-hardware.org/?probe=6c015f633b) | Jun 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [31d19c3462](https://linux-hardware.org/?probe=31d19c3462) | Jun 24, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [71f17d4d74](https://linux-hardware.org/?probe=71f17d4d74) | Jun 24, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | Notebook    | [ebfe7d469a](https://linux-hardware.org/?probe=ebfe7d469a) | Jun 24, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [68b591e6d8](https://linux-hardware.org/?probe=68b591e6d8) | Jun 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [1d6a241c9e](https://linux-hardware.org/?probe=1d6a241c9e) | Jun 23, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fed92425f3](https://linux-hardware.org/?probe=fed92425f3) | Jun 23, 2023 |
| HP            | 8055                        | Desktop     | [21f11f538d](https://linux-hardware.org/?probe=21f11f538d) | Jun 23, 2023 |
| HP            | 8055                        | Desktop     | [54e0de7a72](https://linux-hardware.org/?probe=54e0de7a72) | Jun 23, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [55873c7a70](https://linux-hardware.org/?probe=55873c7a70) | Jun 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5fbfa89321](https://linux-hardware.org/?probe=5fbfa89321) | Jun 21, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [86ee4e619f](https://linux-hardware.org/?probe=86ee4e619f) | Jun 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5cbbd51d7f](https://linux-hardware.org/?probe=5cbbd51d7f) | Jun 20, 2023 |
| Pegatron      | JESSE                       | Desktop     | [fa09a247a7](https://linux-hardware.org/?probe=fa09a247a7) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [405e91f460](https://linux-hardware.org/?probe=405e91f460) | Jun 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [e3ded6b5e4](https://linux-hardware.org/?probe=e3ded6b5e4) | Jun 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1f1209bd20](https://linux-hardware.org/?probe=1f1209bd20) | Jun 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [34610e62fe](https://linux-hardware.org/?probe=34610e62fe) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [bd4abe1a68](https://linux-hardware.org/?probe=bd4abe1a68) | Jun 18, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6ff9be62b8](https://linux-hardware.org/?probe=6ff9be62b8) | Jun 18, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7c7742bf5a](https://linux-hardware.org/?probe=7c7742bf5a) | Jun 18, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [23b64edd39](https://linux-hardware.org/?probe=23b64edd39) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [269309f364](https://linux-hardware.org/?probe=269309f364) | Jun 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [da0a4b3bf0](https://linux-hardware.org/?probe=da0a4b3bf0) | Jun 16, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [940ab1af2a](https://linux-hardware.org/?probe=940ab1af2a) | Jun 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [4d81fc8320](https://linux-hardware.org/?probe=4d81fc8320) | Jun 15, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [df63208f37](https://linux-hardware.org/?probe=df63208f37) | Jun 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [f802893b92](https://linux-hardware.org/?probe=f802893b92) | Jun 15, 2023 |
| HP            | 3397                        | Desktop     | [e67824996f](https://linux-hardware.org/?probe=e67824996f) | Jun 14, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [cb6681d609](https://linux-hardware.org/?probe=cb6681d609) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [9b67ef406b](https://linux-hardware.org/?probe=9b67ef406b) | Jun 14, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [b972bb9890](https://linux-hardware.org/?probe=b972bb9890) | Jun 14, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [3715cf9513](https://linux-hardware.org/?probe=3715cf9513) | Jun 14, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
| MSI           | P67A-C45                    | Desktop     | [4f3aa2017f](https://linux-hardware.org/?probe=4f3aa2017f) | Jun 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [f4f10ca549](https://linux-hardware.org/?probe=f4f10ca549) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f3cbfd7fe](https://linux-hardware.org/?probe=3f3cbfd7fe) | Jun 12, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [ed8bd3839f](https://linux-hardware.org/?probe=ed8bd3839f) | Jun 12, 2023 |
| HP            | 18E4                        | Desktop     | [a0d8b92e3a](https://linux-hardware.org/?probe=a0d8b92e3a) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| HP            | 2B16                        | Desktop     | [0f2ea937e9](https://linux-hardware.org/?probe=0f2ea937e9) | Jun 12, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [effdc6a5a3](https://linux-hardware.org/?probe=effdc6a5a3) | Jun 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7221d4851c](https://linux-hardware.org/?probe=7221d4851c) | Jun 11, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [008148f553](https://linux-hardware.org/?probe=008148f553) | Jun 11, 2023 |
| HP            | 158A                        | Desktop     | [ce5c3c88d4](https://linux-hardware.org/?probe=ce5c3c88d4) | Jun 11, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [75285a62bd](https://linux-hardware.org/?probe=75285a62bd) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [74e0ea4d38](https://linux-hardware.org/?probe=74e0ea4d38) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | Notebook    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [c8e822d0d7](https://linux-hardware.org/?probe=c8e822d0d7) | Jun 10, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| HP            | 2B4B                        | Desktop     | [3ade78a07e](https://linux-hardware.org/?probe=3ade78a07e) | Jun 10, 2023 |
| HP            | 2B4B                        | Desktop     | [2da60252b5](https://linux-hardware.org/?probe=2da60252b5) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [758afab931](https://linux-hardware.org/?probe=758afab931) | Jun 10, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d9e9a51e48](https://linux-hardware.org/?probe=d9e9a51e48) | Jun 10, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [685ba556b4](https://linux-hardware.org/?probe=685ba556b4) | Jun 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [797dea9c96](https://linux-hardware.org/?probe=797dea9c96) | Jun 09, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bae25f67b](https://linux-hardware.org/?probe=1bae25f67b) | Jun 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [cc1f571000](https://linux-hardware.org/?probe=cc1f571000) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| Dell          | Precision 5540              | Notebook    | [0e925c8b3c](https://linux-hardware.org/?probe=0e925c8b3c) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [d5d7ffe9df](https://linux-hardware.org/?probe=d5d7ffe9df) | Jun 08, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [f6fddfcd65](https://linux-hardware.org/?probe=f6fddfcd65) | Jun 07, 2023 |
| MSI           | P67A-C45                    | Desktop     | [673f3774bc](https://linux-hardware.org/?probe=673f3774bc) | Jun 07, 2023 |
| MSI           | CreatorPro X17 A12UKS       | Notebook    | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [1d36e85f27](https://linux-hardware.org/?probe=1d36e85f27) | Jun 07, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [87bd8323b6](https://linux-hardware.org/?probe=87bd8323b6) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e45ed702a4](https://linux-hardware.org/?probe=e45ed702a4) | Jun 07, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [47c5d7587a](https://linux-hardware.org/?probe=47c5d7587a) | Jun 06, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [5fb7d63e80](https://linux-hardware.org/?probe=5fb7d63e80) | Jun 06, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [23b41d16db](https://linux-hardware.org/?probe=23b41d16db) | Jun 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2508cbfdd2](https://linux-hardware.org/?probe=2508cbfdd2) | Jun 06, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3d0f46c6ed](https://linux-hardware.org/?probe=3d0f46c6ed) | Jun 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [8d150fb2b0](https://linux-hardware.org/?probe=8d150fb2b0) | Jun 05, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [edbf91844a](https://linux-hardware.org/?probe=edbf91844a) | Jun 04, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e0a13cdd1](https://linux-hardware.org/?probe=8e0a13cdd1) | Jun 04, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [4d82d8bf8b](https://linux-hardware.org/?probe=4d82d8bf8b) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cdbebd8a7e](https://linux-hardware.org/?probe=cdbebd8a7e) | Jun 04, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [25ffe9ad37](https://linux-hardware.org/?probe=25ffe9ad37) | Jun 03, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [76cd01b045](https://linux-hardware.org/?probe=76cd01b045) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [e91c644324](https://linux-hardware.org/?probe=e91c644324) | Jun 02, 2023 |
| Dell          | G15 5520                    | Notebook    | [5880c98c54](https://linux-hardware.org/?probe=5880c98c54) | Jun 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Panasonic     | CF-SX2JDHYS                 | Notebook    | [2bcfc48199](https://linux-hardware.org/?probe=2bcfc48199) | Jun 02, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2cf19f7b32](https://linux-hardware.org/?probe=2cf19f7b32) | Jun 02, 2023 |
| Portwell      | RuggedBookJ10               | Tablet      | [828336f149](https://linux-hardware.org/?probe=828336f149) | Jun 01, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [71c2818f01](https://linux-hardware.org/?probe=71c2818f01) | Jun 01, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [976fcb80b0](https://linux-hardware.org/?probe=976fcb80b0) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [a313036ec2](https://linux-hardware.org/?probe=a313036ec2) | May 31, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [02f6d0b74b](https://linux-hardware.org/?probe=02f6d0b74b) | May 29, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [a9ff8334b4](https://linux-hardware.org/?probe=a9ff8334b4) | May 28, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [d3afe375cf](https://linux-hardware.org/?probe=d3afe375cf) | May 28, 2023 |
| ASUSTek       | Z87I-DELUXE                 | Desktop     | [5d683647ae](https://linux-hardware.org/?probe=5d683647ae) | May 28, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [a890415f0e](https://linux-hardware.org/?probe=a890415f0e) | May 28, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [eb9ee9f38e](https://linux-hardware.org/?probe=eb9ee9f38e) | May 27, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [aeb6fa2258](https://linux-hardware.org/?probe=aeb6fa2258) | May 26, 2023 |
| Dell          | Latitude 3440               | Notebook    | [1d32fe235f](https://linux-hardware.org/?probe=1d32fe235f) | May 26, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [f4de9c8a5f](https://linux-hardware.org/?probe=f4de9c8a5f) | May 26, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [1c272c65dc](https://linux-hardware.org/?probe=1c272c65dc) | May 26, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [5b0dffc2c3](https://linux-hardware.org/?probe=5b0dffc2c3) | May 26, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e0920f015d](https://linux-hardware.org/?probe=e0920f015d) | May 25, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [f3e564d17d](https://linux-hardware.org/?probe=f3e564d17d) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [776f5c2411](https://linux-hardware.org/?probe=776f5c2411) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [e2110ab5da](https://linux-hardware.org/?probe=e2110ab5da) | May 25, 2023 |
| ASRock        | 890GX Extreme3              | Desktop     | [016f2a8ada](https://linux-hardware.org/?probe=016f2a8ada) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f133543500](https://linux-hardware.org/?probe=f133543500) | May 23, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [56fba05f01](https://linux-hardware.org/?probe=56fba05f01) | May 22, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [926421c6be](https://linux-hardware.org/?probe=926421c6be) | May 22, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [c903e06758](https://linux-hardware.org/?probe=c903e06758) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [8b4b66a085](https://linux-hardware.org/?probe=8b4b66a085) | May 22, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [3fb6e257a6](https://linux-hardware.org/?probe=3fb6e257a6) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [a6e8e03e74](https://linux-hardware.org/?probe=a6e8e03e74) | May 21, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a69a8746ff](https://linux-hardware.org/?probe=a69a8746ff) | May 20, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [d5213cca3c](https://linux-hardware.org/?probe=d5213cca3c) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | Desktop     | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5352a94049](https://linux-hardware.org/?probe=5352a94049) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [12da248164](https://linux-hardware.org/?probe=12da248164) | May 19, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c571a25585](https://linux-hardware.org/?probe=c571a25585) | May 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8EG0... | Notebook    | [0735cab104](https://linux-hardware.org/?probe=0735cab104) | May 18, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [7087600ab6](https://linux-hardware.org/?probe=7087600ab6) | May 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [ad17e04f3b](https://linux-hardware.org/?probe=ad17e04f3b) | May 17, 2023 |
| Dell          | Inspiron 7573               | Convertible | [8f57130549](https://linux-hardware.org/?probe=8f57130549) | May 17, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [74c412b40a](https://linux-hardware.org/?probe=74c412b40a) | May 16, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Dell          | Inspiron 7573               | Convertible | [6f1d226305](https://linux-hardware.org/?probe=6f1d226305) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [443ee2bf3a](https://linux-hardware.org/?probe=443ee2bf3a) | May 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [61499d189f](https://linux-hardware.org/?probe=61499d189f) | May 15, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [1560f547ad](https://linux-hardware.org/?probe=1560f547ad) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2dc2bdd057](https://linux-hardware.org/?probe=2dc2bdd057) | May 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [6335ace28b](https://linux-hardware.org/?probe=6335ace28b) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ab7d27081e](https://linux-hardware.org/?probe=ab7d27081e) | May 13, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [4bc8e971f7](https://linux-hardware.org/?probe=4bc8e971f7) | May 13, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [be75daf81a](https://linux-hardware.org/?probe=be75daf81a) | May 13, 2023 |
| HP            | 339A                        | Desktop     | [2ba14f8397](https://linux-hardware.org/?probe=2ba14f8397) | May 12, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [30bda7d8cb](https://linux-hardware.org/?probe=30bda7d8cb) | May 12, 2023 |
| Lenovo        | ThinkPad L540 20AUS01H00    | Notebook    | [d39599a293](https://linux-hardware.org/?probe=d39599a293) | May 12, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3d43aab6fd](https://linux-hardware.org/?probe=3d43aab6fd) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [3293d10187](https://linux-hardware.org/?probe=3293d10187) | May 12, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [99ad79383e](https://linux-hardware.org/?probe=99ad79383e) | May 11, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [165d6e12b4](https://linux-hardware.org/?probe=165d6e12b4) | May 11, 2023 |
| Lenovo        | ThinkPad T530 23926CU       | Notebook    | [4e7cab81f3](https://linux-hardware.org/?probe=4e7cab81f3) | May 11, 2023 |
| Lenovo        | ThinkPad W541 20EF001UGE    | Notebook    | [29c8170a0e](https://linux-hardware.org/?probe=29c8170a0e) | May 10, 2023 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [cde6cec9c8](https://linux-hardware.org/?probe=cde6cec9c8) | May 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [49e9002825](https://linux-hardware.org/?probe=49e9002825) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0a3aa24894](https://linux-hardware.org/?probe=0a3aa24894) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [6fca1885fc](https://linux-hardware.org/?probe=6fca1885fc) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [5cd314b0af](https://linux-hardware.org/?probe=5cd314b0af) | May 10, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | Notebook    | [c0ad43f440](https://linux-hardware.org/?probe=c0ad43f440) | May 09, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | Notebook    | [f3572c500c](https://linux-hardware.org/?probe=f3572c500c) | May 09, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [9430b8c328](https://linux-hardware.org/?probe=9430b8c328) | May 08, 2023 |
| Lenovo        | ThinkPad T410 2522K3U       | Notebook    | [55756e1659](https://linux-hardware.org/?probe=55756e1659) | May 07, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eeb37c9c4f](https://linux-hardware.org/?probe=eeb37c9c4f) | May 07, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [05c9e752a5](https://linux-hardware.org/?probe=05c9e752a5) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b661127bb7](https://linux-hardware.org/?probe=b661127bb7) | May 06, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [aaad2fda16](https://linux-hardware.org/?probe=aaad2fda16) | May 06, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [c6b9cf8729](https://linux-hardware.org/?probe=c6b9cf8729) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 304Ah                       | Desktop     | [d9a160845c](https://linux-hardware.org/?probe=d9a160845c) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [f9a56b49f3](https://linux-hardware.org/?probe=f9a56b49f3) | May 05, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [0d4ad3c608](https://linux-hardware.org/?probe=0d4ad3c608) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab21408c4c](https://linux-hardware.org/?probe=ab21408c4c) | May 03, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9ff86ca1f1](https://linux-hardware.org/?probe=9ff86ca1f1) | May 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9bd630708](https://linux-hardware.org/?probe=e9bd630708) | May 01, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [82d7303d5c](https://linux-hardware.org/?probe=82d7303d5c) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [0cb8947c84](https://linux-hardware.org/?probe=0cb8947c84) | Apr 30, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9109b0a7ed](https://linux-hardware.org/?probe=9109b0a7ed) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9876205c45](https://linux-hardware.org/?probe=9876205c45) | Apr 30, 2023 |
| AMI           | INTEL                       | Convertible | [3a67944d4f](https://linux-hardware.org/?probe=3a67944d4f) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | 1998                        | Desktop     | [4ba5ef1211](https://linux-hardware.org/?probe=4ba5ef1211) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c880b8dcdd](https://linux-hardware.org/?probe=c880b8dcdd) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [a1584c31ec](https://linux-hardware.org/?probe=a1584c31ec) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5f191f449f](https://linux-hardware.org/?probe=5f191f449f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5c5fece872](https://linux-hardware.org/?probe=5c5fece872) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | Notebook    | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2ccfcd2b27](https://linux-hardware.org/?probe=2ccfcd2b27) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [19c145fab1](https://linux-hardware.org/?probe=19c145fab1) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [46a27a7551](https://linux-hardware.org/?probe=46a27a7551) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Google        | Kefka                       | Notebook    | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| ASUSTek       | GL703VM                     | Notebook    | [f3c76b5075](https://linux-hardware.org/?probe=f3c76b5075) | Apr 23, 2023 |
| HP            | 8433 11                     | Desktop     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [2aa36b9cfd](https://linux-hardware.org/?probe=2aa36b9cfd) | Apr 22, 2023 |
| Allview       | Allbook J                   | Notebook    | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [1a3ff160a7](https://linux-hardware.org/?probe=1a3ff160a7) | Apr 21, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Gateway       | NV55C                       | Notebook    | [e77192c3b1](https://linux-hardware.org/?probe=e77192c3b1) | Apr 20, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [50f90c0b1f](https://linux-hardware.org/?probe=50f90c0b1f) | Apr 20, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [e299a6ed8e](https://linux-hardware.org/?probe=e299a6ed8e) | Apr 20, 2023 |
| Dell          | Latitude 7410               | Notebook    | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [69b2b1c95f](https://linux-hardware.org/?probe=69b2b1c95f) | Apr 19, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [17eb54bee6](https://linux-hardware.org/?probe=17eb54bee6) | Apr 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Allview       | Allbook J                   | Notebook    | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [482a8c29cc](https://linux-hardware.org/?probe=482a8c29cc) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c5f2678609](https://linux-hardware.org/?probe=c5f2678609) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [76f2d6b30c](https://linux-hardware.org/?probe=76f2d6b30c) | Apr 13, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [3ac19a6abf](https://linux-hardware.org/?probe=3ac19a6abf) | Apr 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6e34f5a7b8](https://linux-hardware.org/?probe=6e34f5a7b8) | Apr 13, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [23371691ec](https://linux-hardware.org/?probe=23371691ec) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [ae048d3165](https://linux-hardware.org/?probe=ae048d3165) | Apr 12, 2023 |
| HP            | 8433 11                     | Desktop     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| MSI           | P67A-C45                    | Desktop     | [25a90d2595](https://linux-hardware.org/?probe=25a90d2595) | Apr 10, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [b67954cc59](https://linux-hardware.org/?probe=b67954cc59) | Apr 10, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [0f078152ca](https://linux-hardware.org/?probe=0f078152ca) | Apr 10, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [d938c02967](https://linux-hardware.org/?probe=d938c02967) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ab81a719b](https://linux-hardware.org/?probe=1ab81a719b) | Apr 08, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [840f96a7df](https://linux-hardware.org/?probe=840f96a7df) | Apr 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d85ac2917b](https://linux-hardware.org/?probe=d85ac2917b) | Apr 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [241572fcea](https://linux-hardware.org/?probe=241572fcea) | Apr 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a9882c4012](https://linux-hardware.org/?probe=a9882c4012) | Apr 06, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b949468335](https://linux-hardware.org/?probe=b949468335) | Apr 05, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [62debd585f](https://linux-hardware.org/?probe=62debd585f) | Apr 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dcf97ad331](https://linux-hardware.org/?probe=dcf97ad331) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f89b2c8b2a](https://linux-hardware.org/?probe=f89b2c8b2a) | Apr 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [9f251621b1](https://linux-hardware.org/?probe=9f251621b1) | Apr 04, 2023 |
| Dell          | Precision 5530              | Notebook    | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | Unknown                     | Notebook    | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [a03fbcf098](https://linux-hardware.org/?probe=a03fbcf098) | Apr 03, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [d447871547](https://linux-hardware.org/?probe=d447871547) | Apr 03, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [82a3b55b60](https://linux-hardware.org/?probe=82a3b55b60) | Apr 02, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [fabc275714](https://linux-hardware.org/?probe=fabc275714) | Apr 01, 2023 |
| MSI           | P67A-C43                    | Desktop     | [f3e7913310](https://linux-hardware.org/?probe=f3e7913310) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASRock        | Z87 Extreme11/ac            | Desktop     | [283593a105](https://linux-hardware.org/?probe=283593a105) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| MSI           | 2AE0                        | Desktop     | [29c86e9653](https://linux-hardware.org/?probe=29c86e9653) | Mar 29, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [872733b74c](https://linux-hardware.org/?probe=872733b74c) | Mar 29, 2023 |
| MSI           | 2AE0                        | Desktop     | [53e6254c56](https://linux-hardware.org/?probe=53e6254c56) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| ASUSTek       | A78M-A                      | Desktop     | [e2ee931df2](https://linux-hardware.org/?probe=e2ee931df2) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [42601709f3](https://linux-hardware.org/?probe=42601709f3) | Mar 27, 2023 |
| Gigabyte      | H110M-S2PV DDR3-CF          | Desktop     | [022acc16f7](https://linux-hardware.org/?probe=022acc16f7) | Mar 27, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [98df8e769b](https://linux-hardware.org/?probe=98df8e769b) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6c942c5a39](https://linux-hardware.org/?probe=6c942c5a39) | Mar 26, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [3c68ddf942](https://linux-hardware.org/?probe=3c68ddf942) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [6a03f43f29](https://linux-hardware.org/?probe=6a03f43f29) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | Notebook    | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [f2a2593a06](https://linux-hardware.org/?probe=f2a2593a06) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6a2a55ca61](https://linux-hardware.org/?probe=6a2a55ca61) | Mar 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [640a9ac505](https://linux-hardware.org/?probe=640a9ac505) | Mar 24, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [2f50a76b96](https://linux-hardware.org/?probe=2f50a76b96) | Mar 22, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [b618258a5c](https://linux-hardware.org/?probe=b618258a5c) | Mar 22, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [982f47fec3](https://linux-hardware.org/?probe=982f47fec3) | Mar 22, 2023 |
| Dell          | Latitude D530               | Notebook    | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7b772c82ca](https://linux-hardware.org/?probe=7b772c82ca) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd045deb23](https://linux-hardware.org/?probe=bd045deb23) | Mar 21, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [c87a678cf5](https://linux-hardware.org/?probe=c87a678cf5) | Mar 21, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c7c5415a8c](https://linux-hardware.org/?probe=c7c5415a8c) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [de1c89d1b0](https://linux-hardware.org/?probe=de1c89d1b0) | Mar 21, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [0c0bff4f29](https://linux-hardware.org/?probe=0c0bff4f29) | Mar 20, 2023 |
| HP            | 304Ah                       | Desktop     | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| Lenovo        | LEGION5PRO-16ACH6H 82JQ     | Notebook    | [4f3cbedf85](https://linux-hardware.org/?probe=4f3cbedf85) | Mar 20, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b7cf9d91ee](https://linux-hardware.org/?probe=b7cf9d91ee) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [729a1432a0](https://linux-hardware.org/?probe=729a1432a0) | Mar 19, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9cdd00c854](https://linux-hardware.org/?probe=9cdd00c854) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [f35715c399](https://linux-hardware.org/?probe=f35715c399) | Mar 18, 2023 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [9d5f79bbf4](https://linux-hardware.org/?probe=9d5f79bbf4) | Mar 18, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [92d818d184](https://linux-hardware.org/?probe=92d818d184) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [60114cc9c8](https://linux-hardware.org/?probe=60114cc9c8) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | Desktop     | [d03e035ed6](https://linux-hardware.org/?probe=d03e035ed6) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | Desktop     | [2b34503276](https://linux-hardware.org/?probe=2b34503276) | Mar 16, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4a47120f89](https://linux-hardware.org/?probe=4a47120f89) | Mar 15, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [a1e7a34896](https://linux-hardware.org/?probe=a1e7a34896) | Mar 14, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [6e2a63edaa](https://linux-hardware.org/?probe=6e2a63edaa) | Mar 14, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [bc12f3e2e4](https://linux-hardware.org/?probe=bc12f3e2e4) | Mar 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfd3b8546c](https://linux-hardware.org/?probe=dfd3b8546c) | Mar 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 1595      | 63.83%  |
| openSUSE Leap-15.2           | 211       | 8.44%   |
| openSUSE Leap-15.5           | 158       | 6.32%   |
| openSUSE Leap-15.4           | 136       | 5.44%   |
| openSUSE Leap-15.3           | 134       | 5.36%   |
| openSUSE Leap-15.1           | 123       | 4.92%   |
| openSUSE Microos-XXXXXXXX    | 76        | 3.04%   |
| openSUSE Leap-15.0           | 48        | 1.92%   |
| openSUSE 13.2                | 5         | 0.2%    |
| openSUSE Leap-42.2           | 3         | 0.12%   |
| openSUSE 42.3                | 3         | 0.12%   |
| openSUSE                     | 3         | 0.12%   |
| openSUSE Leap-42.3           | 2         | 0.08%   |
| openSUSE Leap-42.1           | 1         | 0.04%   |
| openSUSE 13.1                | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| openSUSE | 2424      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.21-150500.53-default    | 52        | 1.79%   |
| 5.17.4-1-default             | 49        | 1.68%   |
| 6.5.4-1-default              | 43        | 1.48%   |
| 4.12.14-lp151.28.44-default  | 43        | 1.48%   |
| 6.3.9-1-default              | 42        | 1.44%   |
| 5.14.21-150500.55.19-default | 41        | 1.41%   |
| 6.0.8-1-default              | 35        | 1.2%    |
| 5.6.0-1-default              | 31        | 1.06%   |
| 6.3.2-1-default              | 29        | 1%      |
| 6.2.12-1-default             | 29        | 1%      |
| 6.3.4-1-default              | 27        | 0.93%   |
| 6.4.11-1-default             | 26        | 0.89%   |
| 6.1.8-1-default              | 26        | 0.89%   |
| 6.0.12-1-default             | 26        | 0.89%   |
| 6.2.9-1-default              | 25        | 0.86%   |
| 6.1.12-1-default             | 25        | 0.86%   |
| 5.14.21-150400.22-default    | 25        | 0.86%   |
| 6.5.6-1-default              | 24        | 0.82%   |
| 6.4.6-1-default              | 24        | 0.82%   |
| 5.19.2-1-default             | 24        | 0.82%   |
| 6.0.10-1-default             | 23        | 0.79%   |
| 4.18.15-1-default            | 23        | 0.79%   |
| 6.5.9-1-default              | 22        | 0.76%   |
| 5.3.18-lp152.63-default      | 22        | 0.76%   |
| 6.4.9-1-default              | 21        | 0.72%   |
| 6.2.1-1-default              | 21        | 0.72%   |
| 6.1.10-1-default             | 21        | 0.72%   |
| 5.14.14-1-default            | 21        | 0.72%   |
| 6.5.3-1-default              | 20        | 0.69%   |
| 6.3.1-1-default              | 20        | 0.69%   |
| 6.2.6-1-default              | 20        | 0.69%   |
| 5.17.9-1-default             | 20        | 0.69%   |
| 5.16.11-1-default            | 20        | 0.69%   |
| 6.4.8-1-default              | 19        | 0.65%   |
| 6.4.3-1-default              | 19        | 0.65%   |
| 6.3.7-1-default              | 19        | 0.65%   |
| 5.6.2-1-default              | 19        | 0.65%   |
| 5.17.1-1-default             | 19        | 0.65%   |
| 5.3.18-lp152.57-default      | 18        | 0.62%   |
| 5.3.18-59.37-default         | 18        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 315       | 11.19%  |
| 5.14.21 | 282       | 10.01%  |
| 4.12.14 | 158       | 5.61%   |
| 5.17.4  | 49        | 1.74%   |
| 6.5.4   | 43        | 1.53%   |
| 6.3.9   | 42        | 1.49%   |
| 6.0.8   | 35        | 1.24%   |
| 5.6.0   | 33        | 1.17%   |
| 5.14.14 | 31        | 1.1%    |
| 6.3.1   | 30        | 1.07%   |
| 6.3.2   | 29        | 1.03%   |
| 6.2.12  | 29        | 1.03%   |
| 6.3.4   | 27        | 0.96%   |
| 6.0.12  | 27        | 0.96%   |
| 6.4.11  | 26        | 0.92%   |
| 6.2.9   | 26        | 0.92%   |
| 6.1.8   | 26        | 0.92%   |
| 6.5.6   | 25        | 0.89%   |
| 6.4.6   | 25        | 0.89%   |
| 6.1.12  | 25        | 0.89%   |
| 6.0.10  | 24        | 0.85%   |
| 5.19.2  | 24        | 0.85%   |
| 6.1.10  | 23        | 0.82%   |
| 4.18.15 | 23        | 0.82%   |
| 6.5.9   | 22        | 0.78%   |
| 6.4.9   | 21        | 0.75%   |
| 6.2.1   | 21        | 0.75%   |
| 5.6.2   | 21        | 0.75%   |
| 6.5.3   | 20        | 0.71%   |
| 6.2.6   | 20        | 0.71%   |
| 5.17.9  | 20        | 0.71%   |
| 5.17.1  | 20        | 0.71%   |
| 5.16.11 | 20        | 0.71%   |
| 6.4.8   | 19        | 0.67%   |
| 6.4.3   | 19        | 0.67%   |
| 6.3.7   | 19        | 0.67%   |
| 5.12.4  | 19        | 0.67%   |
| 5.11.6  | 19        | 0.67%   |
| 5.8.4   | 18        | 0.64%   |
| 5.14.6  | 18        | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 370       | 13.53%  |
| 5.3     | 336       | 12.29%  |
| 4.12    | 158       | 5.78%   |
| 6.3     | 156       | 5.71%   |
| 6.4     | 147       | 5.38%   |
| 6.0     | 144       | 5.27%   |
| 6.1     | 141       | 5.16%   |
| 6.2     | 132       | 4.83%   |
| 6.5     | 127       | 4.65%   |
| 5.17    | 114       | 4.17%   |
| 5.6     | 82        | 3%      |
| 5.16    | 77        | 2.82%   |
| 5.18    | 76        | 2.78%   |
| 5.12    | 72        | 2.63%   |
| 5.8     | 70        | 2.56%   |
| 5.10    | 68        | 2.49%   |
| 5.19    | 67        | 2.45%   |
| 5.11    | 59        | 2.16%   |
| 5.15    | 58        | 2.12%   |
| 5.13    | 49        | 1.79%   |
| 5.9     | 40        | 1.46%   |
| 5.7     | 36        | 1.32%   |
| 5.5     | 34        | 1.24%   |
| 4.18    | 27        | 0.99%   |
| 5.4     | 21        | 0.77%   |
| 5.0     | 14        | 0.51%   |
| 5.2     | 13        | 0.48%   |
| 4.17    | 11        | 0.4%    |
| 4.4     | 9         | 0.33%   |
| 5.1     | 5         | 0.18%   |
| 4.20    | 5         | 0.18%   |
| 4.3     | 4         | 0.15%   |
| 3.16    | 4         | 0.15%   |
| 4.19    | 3         | 0.11%   |
| 4.16    | 2         | 0.07%   |
| 4.7     | 1         | 0.04%   |
| 4.1     | 1         | 0.04%   |
| 3.12    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2399      | 98.93%  |
| i686    | 16        | 0.66%   |
| aarch64 | 9         | 0.37%   |
| armv7l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 1406      | 56.13%  |
| GNOME         | 485       | 19.36%  |
| KDE           | 214       | 8.54%   |
| Unknown       | 158       | 6.31%   |
| XFCE          | 117       | 4.67%   |
| MATE          | 22        | 0.88%   |
| X-Cinnamon    | 19        | 0.76%   |
| Cinnamon      | 14        | 0.56%   |
| LXQt          | 10        | 0.4%    |
| KDE4          | 9         | 0.36%   |
| ICEWM         | 9         | 0.36%   |
| LXDE          | 6         | 0.24%   |
| Budgie        | 6         | 0.24%   |
| sway          | 4         | 0.16%   |
| Deepin        | 4         | 0.16%   |
| i3            | 3         | 0.12%   |
| Hyprland      | 3         | 0.12%   |
| GNOME Classic | 3         | 0.12%   |
| WindowMaker   | 2         | 0.08%   |
| Pantheon      | 2         | 0.08%   |
| awesome       | 2         | 0.08%   |
| Trinity       | 1         | 0.04%   |
| plasma5       | 1         | 0.04%   |
| openbox       | 1         | 0.04%   |
| Herbstluftwm  | 1         | 0.04%   |
| fvwm2         | 1         | 0.04%   |
| default       | 1         | 0.04%   |
| custom        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1903      | 76.4%   |
| Wayland     | 500       | 20.07%  |
| Tty         | 45        | 1.81%   |
| Unknown     | 41        | 1.65%   |
| Unspecified | 2         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1122      | 45.1%   |
| LightDM | 614       | 24.68%  |
| SDDM    | 590       | 23.71%  |
| XDM     | 126       | 5.06%   |
| GDM     | 35        | 1.41%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 913       | 36.74%  |
| de_DE   | 332       | 13.36%  |
| POSIX   | 220       | 8.85%   |
| Unknown | 180       | 7.24%   |
| en_GB   | 154       | 6.2%    |
| pt_BR   | 110       | 4.43%   |
| ru_RU   | 89        | 3.58%   |
| es_ES   | 85        | 3.42%   |
| it_IT   | 59        | 2.37%   |
| fr_FR   | 55        | 2.21%   |
| pl_PL   | 34        | 1.37%   |
| nl_NL   | 24        | 0.97%   |
| pt_PT   | 20        | 0.8%    |
| cs_CZ   | 16        | 0.64%   |
| zh_CN   | 15        | 0.6%    |
| hu_HU   | 11        | 0.44%   |
| fi_FI   | 9         | 0.36%   |
| C       | 9         | 0.36%   |
| es_MX   | 7         | 0.28%   |
| sv_SE   | 6         | 0.24%   |
| nl_BE   | 6         | 0.24%   |
| nb_NO   | 6         | 0.24%   |
| es_AR   | 6         | 0.24%   |
| en_IN   | 6         | 0.24%   |
| en_IE   | 6         | 0.24%   |
| en_DK   | 6         | 0.24%   |
| en_DE   | 6         | 0.24%   |
| tr_TR   | 5         | 0.2%    |
| ja_JP   | 5         | 0.2%    |
| es_DO   | 5         | 0.2%    |
| en_AU   | 5         | 0.2%    |
| bg_BG   | 5         | 0.2%    |
| sk_SK   | 4         | 0.16%   |
| nn_NO   | 4         | 0.16%   |
| ro_RO   | 3         | 0.12%   |
| ko_KR   | 3         | 0.12%   |
| hr_HR   | 3         | 0.12%   |
| en_FI   | 3         | 0.12%   |
| en_CH   | 3         | 0.12%   |
| cv_RU   | 3         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1615      | 65.95%  |
| BIOS | 834       | 34.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Btrfs    | 1772      | 72.27%  |
| Ext4     | 494       | 20.15%  |
| Xfs      | 90        | 3.67%   |
| Unknown  | 61        | 2.49%   |
| Overlay  | 20        | 0.82%   |
| Tmpfs    | 7         | 0.29%   |
| Ext3     | 3         | 0.12%   |
| Ext2     | 2         | 0.08%   |
| Zfs      | 1         | 0.04%   |
| Reiserfs | 1         | 0.04%   |
| F2fs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1248      | 50.51%  |
| Unknown | 1037      | 41.97%  |
| MBR     | 186       | 7.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2123      | 85.92%  |
| Yes       | 348       | 14.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1854      | 75.43%  |
| Yes       | 604       | 24.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 393       | 16.21%  |
| Lenovo                  | 379       | 15.64%  |
| Hewlett-Packard         | 347       | 14.32%  |
| Dell                    | 279       | 11.51%  |
| Gigabyte Technology     | 192       | 7.92%   |
| MSI                     | 170       | 7.01%   |
| Acer                    | 120       | 4.95%   |
| ASRock                  | 114       | 4.7%    |
| Apple                   | 63        | 2.6%    |
| Fujitsu                 | 29        | 1.2%    |
| Toshiba                 | 26        | 1.07%   |
| Intel                   | 23        | 0.95%   |
| HUAWEI                  | 21        | 0.87%   |
| TUXEDO                  | 19        | 0.78%   |
| Samsung Electronics     | 17        | 0.7%    |
| Sony                    | 15        | 0.62%   |
| Medion                  | 12        | 0.5%    |
| Biostar                 | 12        | 0.5%    |
| Unknown                 | 12        | 0.5%    |
| Alienware               | 11        | 0.45%   |
| Supermicro              | 9         | 0.37%   |
| Notebook                | 8         | 0.33%   |
| Microsoft               | 8         | 0.33%   |
| Fujitsu Siemens         | 8         | 0.33%   |
| Pegatron                | 7         | 0.29%   |
| Google                  | 6         | 0.25%   |
| Foxconn                 | 5         | 0.21%   |
| Timi                    | 4         | 0.17%   |
| SLIMBOOK                | 4         | 0.17%   |
| Schenker                | 4         | 0.17%   |
| Raspberry Pi Foundation | 4         | 0.17%   |
| Positivo                | 4         | 0.17%   |
| Razer                   | 3         | 0.12%   |
| LG Electronics          | 3         | 0.12%   |
| Gateway                 | 3         | 0.12%   |
| Clevo                   | 3         | 0.12%   |
| BESSTAR Tech            | 3         | 0.12%   |
| Avell High Performance  | 3         | 0.12%   |
| Wortmann AG             | 2         | 0.08%   |
| TYAN Computer           | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 25        | 1.03%   |
| Unknown                              | 21        | 0.87%   |
| Dell OptiPlex 9020                   | 11        | 0.45%   |
| MSI MS-7B86                          | 9         | 0.37%   |
| HP Notebook                          | 9         | 0.37%   |
| Apple MacBookPro9,2                  | 9         | 0.37%   |
| ASUS TUF Gaming X570-PLUS            | 8         | 0.33%   |
| ASRock B450M Pro4                    | 7         | 0.29%   |
| MSI MS-7C37                          | 6         | 0.25%   |
| MSI MS-7B89                          | 6         | 0.25%   |
| HP Pavilion dv7                      | 6         | 0.25%   |
| Gigabyte B450M DS3H                  | 6         | 0.25%   |
| Gigabyte 970A-DS3P                   | 6         | 0.25%   |
| Dell Precision 5530                  | 6         | 0.25%   |
| MSI MS-7C02                          | 5         | 0.21%   |
| MSI MS-7A34                          | 5         | 0.21%   |
| HP Pavilion dv6                      | 5         | 0.21%   |
| HP Laptop 17-ca0xxx                  | 5         | 0.21%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 5         | 0.21%   |
| Gigabyte B450 AORUS M                | 5         | 0.21%   |
| Dell Latitude 7490                   | 5         | 0.21%   |
| ASUS PRIME A320M-K                   | 5         | 0.21%   |
| ASUS M5A97 R2.0                      | 5         | 0.21%   |
| ASRock X570 Steel Legend             | 5         | 0.21%   |
| TUXEDO Pulse 15 Gen1                 | 4         | 0.17%   |
| MSI MS-7C91                          | 4         | 0.17%   |
| MSI MS-7B79                          | 4         | 0.17%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 4         | 0.17%   |
| Lenovo G50-45 80E3                   | 4         | 0.17%   |
| HP Z620 Workstation                  | 4         | 0.17%   |
| HP Pavilion g6                       | 4         | 0.17%   |
| HP OMEN Laptop 15-en0xxx             | 4         | 0.17%   |
| HP OMEN by Laptop                    | 4         | 0.17%   |
| Gigabyte X570 AORUS MASTER           | 4         | 0.17%   |
| Dell XPS 8700                        | 4         | 0.17%   |
| Dell XPS 15 9560                     | 4         | 0.17%   |
| Dell Latitude E7470                  | 4         | 0.17%   |
| ASUS ROG STRIX B550-F GAMING         | 4         | 0.17%   |
| ASUS PRIME X370-PRO                  | 4         | 0.17%   |
| ASUS PRIME B550-PLUS                 | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 200       | 8.25%   |
| Acer Aspire        | 77        | 3.18%   |
| Dell Latitude      | 65        | 2.68%   |
| Dell Inspiron      | 63        | 2.6%    |
| Lenovo IdeaPad     | 60        | 2.48%   |
| ASUS PRIME         | 55        | 2.27%   |
| HP Pavilion        | 53        | 2.19%   |
| HP EliteBook       | 46        | 1.9%    |
| ASUS ROG           | 46        | 1.9%    |
| Dell XPS           | 37        | 1.53%   |
| HP Laptop          | 35        | 1.44%   |
| Dell OptiPlex      | 35        | 1.44%   |
| ASUS TUF           | 34        | 1.4%    |
| Dell Precision     | 33        | 1.36%   |
| HP ProBook         | 30        | 1.24%   |
| ASUS VivoBook      | 30        | 1.24%   |
| HP ENVY            | 27        | 1.11%   |
| ASUS All           | 25        | 1.03%   |
| Lenovo Yoga        | 23        | 0.95%   |
| Toshiba Satellite  | 21        | 0.87%   |
| HP Compaq          | 21        | 0.87%   |
| Unknown            | 21        | 0.87%   |
| Lenovo ThinkCentre | 19        | 0.78%   |
| HP ZBook           | 19        | 0.78%   |
| Dell PowerEdge     | 18        | 0.74%   |
| HP OMEN            | 17        | 0.7%    |
| Fujitsu LIFEBOOK   | 15        | 0.62%   |
| ASUS ZenBook       | 14        | 0.58%   |
| Gigabyte X570      | 13        | 0.54%   |
| Acer Swift         | 13        | 0.54%   |
| Dell Vostro        | 12        | 0.5%    |
| ASUS ASUS          | 12        | 0.5%    |
| ASRock B450M       | 11        | 0.45%   |
| Lenovo Legion      | 10        | 0.41%   |
| Gigabyte B550      | 10        | 0.41%   |
| MSI MS-7B86        | 9         | 0.37%   |
| HP Notebook        | 9         | 0.37%   |
| Gigabyte B450M     | 9         | 0.37%   |
| ASUS M5A78L-M      | 9         | 0.37%   |
| ASRock X570        | 9         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 280       | 11.55%  |
| 2018 | 240       | 9.9%    |
| 2019 | 229       | 9.45%   |
| 2021 | 227       | 9.36%   |
| 2017 | 184       | 7.59%   |
| 2012 | 174       | 7.18%   |
| 2013 | 171       | 7.05%   |
| 2015 | 134       | 5.53%   |
| 2022 | 131       | 5.4%    |
| 2011 | 125       | 5.16%   |
| 2014 | 123       | 5.07%   |
| 2016 | 104       | 4.29%   |
| 2010 | 98        | 4.04%   |
| 2009 | 66        | 2.72%   |
| 2008 | 58        | 2.39%   |
| 2023 | 38        | 1.57%   |
| 2007 | 23        | 0.95%   |
| 2006 | 11        | 0.45%   |
| 2005 | 5         | 0.21%   |
| 2004 | 2         | 0.08%   |
| 2000 | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1250      | 51.57%  |
| Desktop        | 968       | 39.93%  |
| Convertible    | 90        | 3.71%   |
| Mini pc        | 36        | 1.49%   |
| Server         | 35        | 1.44%   |
| All in one     | 23        | 0.95%   |
| Tablet         | 13        | 0.54%   |
| System on chip | 7         | 0.29%   |
| Other          | 1         | 0.04%   |
| Firewall       | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2081      | 84.63%  |
| Enabled  | 378       | 15.37%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2414      | 99.59%  |
| Yes  | 10        | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 622       | 25.32%  |
| 4.01-8.0        | 519       | 21.12%  |
| 8.01-16.0       | 485       | 19.74%  |
| 32.01-64.0      | 375       | 15.26%  |
| 3.01-4.0        | 210       | 8.55%   |
| 64.01-256.0     | 112       | 4.56%   |
| 24.01-32.0      | 62        | 2.52%   |
| 1.01-2.0        | 34        | 1.38%   |
| 2.01-3.0        | 13        | 0.53%   |
| Unknown         | 10        | 0.41%   |
| 0.51-1.0        | 7         | 0.28%   |
| More than 256.0 | 6         | 0.24%   |
| 0.01-0.5        | 2         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 702       | 26.43%  |
| 4.01-8.0   | 646       | 24.32%  |
| 1.01-2.0   | 537       | 20.22%  |
| 3.01-4.0   | 465       | 17.51%  |
| 8.01-16.0  | 171       | 6.44%   |
| 0.51-1.0   | 78        | 2.94%   |
| 16.01-24.0 | 22        | 0.83%   |
| 0.01-0.5   | 16        | 0.6%    |
| Unknown    | 10        | 0.38%   |
| 24.01-32.0 | 8         | 0.3%    |
| 32.01-64.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1260      | 50.5%   |
| 2       | 665       | 26.65%  |
| 3       | 248       | 9.94%   |
| 4       | 151       | 6.05%   |
| 5       | 81        | 3.25%   |
| 6       | 44        | 1.76%   |
| 7       | 22        | 0.88%   |
| 0       | 8         | 0.32%   |
| 8       | 5         | 0.2%    |
| 13      | 3         | 0.12%   |
| 10      | 3         | 0.12%   |
| 9       | 2         | 0.08%   |
| 35      | 1         | 0.04%   |
| 16      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1596      | 65.44%  |
| Yes       | 843       | 34.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2094      | 86.17%  |
| No        | 336       | 13.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1822      | 74.89%  |
| No        | 611       | 25.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1577      | 64.45%  |
| No        | 870       | 35.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 445       | 18.29%  |
| USA          | 443       | 18.21%  |
| Brazil       | 153       | 6.29%   |
| Russia       | 112       | 4.6%    |
| Italy        | 99        | 4.07%   |
| UK           | 84        | 3.45%   |
| France       | 82        | 3.37%   |
| Netherlands  | 72        | 2.96%   |
| Spain        | 63        | 2.59%   |
| Canada       | 58        | 2.38%   |
| Poland       | 54        | 2.22%   |
| Switzerland  | 52        | 2.14%   |
| Australia    | 37        | 1.52%   |
| Sweden       | 36        | 1.48%   |
| India        | 36        | 1.48%   |
| Belgium      | 33        | 1.36%   |
| Czechia      | 30        | 1.23%   |
| Mexico       | 29        | 1.19%   |
| China        | 28        | 1.15%   |
| Austria      | 28        | 1.15%   |
| Romania      | 23        | 0.95%   |
| Hungary      | 23        | 0.95%   |
| Norway       | 22        | 0.9%    |
| Finland      | 22        | 0.9%    |
| Portugal     | 21        | 0.86%   |
| Bulgaria     | 19        | 0.78%   |
| Ukraine      | 17        | 0.7%    |
| Turkey       | 17        | 0.7%    |
| Greece       | 17        | 0.7%    |
| Argentina    | 16        | 0.66%   |
| Serbia       | 14        | 0.58%   |
| Indonesia    | 13        | 0.53%   |
| Chile        | 13        | 0.53%   |
| South Africa | 10        | 0.41%   |
| Peru         | 10        | 0.41%   |
| Japan        | 10        | 0.41%   |
| Colombia     | 10        | 0.41%   |
| Vietnam      | 9         | 0.37%   |
| Croatia      | 9         | 0.37%   |
| Belarus      | 9         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 33        | 1.28%   |
| Moscow            | 31        | 1.21%   |
| Rio de Janeiro    | 20        | 0.78%   |
| Sao Paulo         | 18        | 0.7%    |
| Munich            | 17        | 0.66%   |
| Vienna            | 16        | 0.62%   |
| Prague            | 16        | 0.62%   |
| Zurich            | 15        | 0.58%   |
| Warsaw            | 15        | 0.58%   |
| St Petersburg     | 15        | 0.58%   |
| Milan             | 15        | 0.58%   |
| Sydney            | 14        | 0.54%   |
| Paris             | 14        | 0.54%   |
| Frankfurt am Main | 14        | 0.54%   |
| Budapest          | 14        | 0.54%   |
| Amsterdam         | 14        | 0.54%   |
| Los Angeles       | 12        | 0.47%   |
| Hamburg           | 12        | 0.47%   |
| Littleton         | 11        | 0.43%   |
| Stuttgart         | 10        | 0.39%   |
| Sofia             | 10        | 0.39%   |
| Rome              | 10        | 0.39%   |
| Madrid            | 10        | 0.39%   |
| Cologne           | 10        | 0.39%   |
| Neuchatel         | 9         | 0.35%   |
| Melbourne         | 9         | 0.35%   |
| Belgrade          | 9         | 0.35%   |
| Athens            | 9         | 0.35%   |
| Riverton          | 8         | 0.31%   |
| Gothenburg        | 8         | 0.31%   |
| Essen             | 8         | 0.31%   |
| Bucharest         | 8         | 0.31%   |
| Bengaluru         | 8         | 0.31%   |
| Stockholm         | 7         | 0.27%   |
| Santiago          | 7         | 0.27%   |
| Montreal          | 7         | 0.27%   |
| Mexico City       | 7         | 0.27%   |
| Istanbul          | 7         | 0.27%   |
| Houston           | 7         | 0.27%   |
| Barcelona         | 7         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 760       | 1198   | 19.15%  |
| Seagate                     | 563       | 986    | 14.18%  |
| WDC                         | 547       | 953    | 13.78%  |
| Toshiba                     | 243       | 313    | 6.12%   |
| Sandisk                     | 216       | 296    | 5.44%   |
| Kingston                    | 214       | 279    | 5.39%   |
| Crucial                     | 171       | 225    | 4.31%   |
| Intel                       | 108       | 138    | 2.72%   |
| SK hynix                    | 107       | 149    | 2.7%    |
| Unknown                     | 99        | 138    | 2.49%   |
| Hitachi                     | 77        | 91     | 1.94%   |
| Micron Technology           | 64        | 77     | 1.61%   |
| HGST                        | 57        | 79     | 1.44%   |
| A-DATA Technology           | 45        | 57     | 1.13%   |
| Phison Electronics          | 36        | 47     | 0.91%   |
| KIOXIA                      | 35        | 40     | 0.88%   |
| Silicon Motion              | 32        | 33     | 0.81%   |
| SPCC                        | 28        | 37     | 0.71%   |
| Apple                       | 28        | 33     | 0.71%   |
| PNY                         | 27        | 36     | 0.68%   |
| Intenso                     | 27        | 39     | 0.68%   |
| China                       | 27        | 29     | 0.68%   |
| Phison                      | 25        | 35     | 0.63%   |
| Micron/Crucial Technology   | 24        | 31     | 0.6%    |
| Kingston Technology Company | 22        | 23     | 0.55%   |
| Hewlett-Packard             | 16        | 30     | 0.4%    |
| Transcend                   | 14        | 16     | 0.35%   |
| Patriot                     | 13        | 15     | 0.33%   |
| LITEON                      | 13        | 14     | 0.33%   |
| Fujitsu                     | 13        | 16     | 0.33%   |
| OCZ                         | 12        | 17     | 0.3%    |
| Corsair                     | 12        | 13     | 0.3%    |
| JMicron Technology          | 10        | 10     | 0.25%   |
| Team                        | 9         | 12     | 0.23%   |
| Realtek Semiconductor       | 9         | 9      | 0.23%   |
| Maxtor                      | 9         | 9      | 0.23%   |
| MAXIO Technology (Hangzhou) | 9         | 10     | 0.23%   |
| GOODRAM                     | 9         | 9      | 0.23%   |
| ADATA Technology            | 9         | 11     | 0.23%   |
| XrayDisk                    | 7         | 7      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 71        | 1.57%   |
| Samsung SSD 860 EVO 500GB                           | 50        | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 48        | 1.06%   |
| Samsung SSD 850 EVO 250GB                           | 40        | 0.89%   |
| Samsung SSD 860 EVO 1TB                             | 36        | 0.8%    |
| Seagate ST2000DM008-2FR102 2TB                      | 35        | 0.78%   |
| Kingston SA400S37480G 480GB SSD                     | 33        | 0.73%   |
| Kingston SA400S37240G 240GB SSD                     | 31        | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 29        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                        | 28        | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB                      | 27        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                      | 26        | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 23        | 0.51%   |
| Samsung SSD 850 EVO 500GB                           | 23        | 0.51%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.49%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 21        | 0.47%   |
| Samsung SSD 840 EVO 250GB                           | 21        | 0.47%   |
| HGST HTS721010A9E630 1TB                            | 21        | 0.47%   |
| Seagate ST500DM002-1BD142 500GB                     | 20        | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB                      | 20        | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB                      | 20        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 19        | 0.42%   |
| Unknown SD/MMC/MS PRO 16GB                          | 19        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                        | 19        | 0.42%   |
| Toshiba MQ01ABD100 1TB                              | 18        | 0.4%    |
| Toshiba DT01ACA100 1TB                              | 18        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                        | 18        | 0.4%    |
| Toshiba MQ04ABF100 1TB                              | 17        | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 17        | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 16        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 16        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                         | 16        | 0.35%   |
| Seagate Expansion 1TB                               | 15        | 0.33%   |
| Samsung SSD 970 EVO 500GB                           | 15        | 0.33%   |
| Samsung SSD 850 PRO 256GB                           | 15        | 0.33%   |
| Intel SSD 660P Series 1024GB                        | 15        | 0.33%   |
| Seagate ST3500418AS 500GB                           | 14        | 0.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 14        | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB                      | 14        | 0.31%   |
| Samsung SSD 860 QVO 1TB                             | 14        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 552       | 956    | 37.76%  |
| WDC                 | 443       | 765    | 30.3%   |
| Toshiba             | 172       | 227    | 11.76%  |
| Hitachi             | 77        | 91     | 5.27%   |
| Samsung Electronics | 75        | 114    | 5.13%   |
| HGST                | 57        | 79     | 3.9%    |
| Unknown             | 20        | 23     | 1.37%   |
| Fujitsu             | 13        | 16     | 0.89%   |
| Apple               | 10        | 12     | 0.68%   |
| Maxtor              | 8         | 8      | 0.55%   |
| Hewlett-Packard     | 7         | 19     | 0.48%   |
| WD MediaMax         | 3         | 3      | 0.21%   |
| SSK                 | 3         | 4      | 0.21%   |
| Intenso             | 3         | 8      | 0.21%   |
| USB3.0              | 2         | 3      | 0.14%   |
| Synology            | 2         | 2      | 0.14%   |
| Pioneer             | 2         | 7      | 0.14%   |
| JMicron Technology  | 2         | 2      | 0.14%   |
| ASMT                | 2         | 4      | 0.14%   |
| USB                 | 1         | 1      | 0.07%   |
| UD0401              | 1         | 1      | 0.07%   |
| Maxone              | 1         | 1      | 0.07%   |
| MaxDigital          | 1         | 1      | 0.07%   |
| Magnetic Data       | 1         | 2      | 0.07%   |
| IBM-207x            | 1         | 8      | 0.07%   |
| IB-377U3            | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| DELLBOSS            | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 373       | 555    | 27.49%  |
| Kingston            | 162       | 212    | 11.94%  |
| Crucial             | 159       | 208    | 11.72%  |
| SanDisk             | 119       | 152    | 8.77%   |
| WDC                 | 91        | 124    | 6.71%   |
| A-DATA Technology   | 34        | 41     | 2.51%   |
| Intel               | 31        | 43     | 2.28%   |
| Toshiba             | 29        | 34     | 2.14%   |
| China               | 27        | 29     | 1.99%   |
| SPCC                | 22        | 31     | 1.62%   |
| SK hynix            | 22        | 33     | 1.62%   |
| PNY                 | 22        | 27     | 1.62%   |
| Intenso             | 21        | 26     | 1.55%   |
| Micron Technology   | 20        | 28     | 1.47%   |
| Apple               | 14        | 17     | 1.03%   |
| Patriot             | 13        | 15     | 0.96%   |
| LITEON              | 13        | 14     | 0.96%   |
| OCZ                 | 12        | 17     | 0.88%   |
| Transcend           | 11        | 13     | 0.81%   |
| Team                | 8         | 11     | 0.59%   |
| GOODRAM             | 8         | 8      | 0.59%   |
| Corsair             | 8         | 8      | 0.59%   |
| LITEONIT            | 7         | 7      | 0.52%   |
| Seagate             | 6         | 7      | 0.44%   |
| Hewlett-Packard     | 6         | 8      | 0.44%   |
| XrayDisk            | 5         | 5      | 0.37%   |
| SABRENT             | 5         | 6      | 0.37%   |
| Plextor             | 5         | 8      | 0.37%   |
| Mushkin             | 5         | 8      | 0.37%   |
| KingSpec            | 5         | 10     | 0.37%   |
| TO Exter            | 4         | 4      | 0.29%   |
| Leven               | 4         | 4      | 0.29%   |
| Gigabyte Technology | 4         | 7      | 0.29%   |
| Biostar             | 4         | 6      | 0.29%   |
| Apacer              | 4         | 7      | 0.29%   |
| Smartbuy            | 3         | 5      | 0.22%   |
| Netac               | 3         | 3      | 0.22%   |
| Fanxiang            | 3         | 6      | 0.22%   |
| ASMT                | 3         | 3      | 0.22%   |
| Unknown             | 3         | 3      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1152      | 2360   | 33.29%  |
| SSD     | 1148      | 1820   | 33.18%  |
| NVMe    | 1041      | 1517   | 30.09%  |
| MMC     | 71        | 96     | 2.05%   |
| Unknown | 48        | 60     | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1735      | 4000   | 57.72%  |
| NVMe | 1040      | 1507   | 34.6%   |
| SAS  | 160       | 250    | 5.32%   |
| MMC  | 71        | 96     | 2.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1239      | 2030   | 49.3%   |
| 0.51-1.0   | 763       | 1254   | 30.36%  |
| 1.01-2.0   | 282       | 488    | 11.22%  |
| 2.01-3.0   | 86        | 142    | 3.42%   |
| 3.01-4.0   | 80        | 152    | 3.18%   |
| 4.01-10.0  | 53        | 98     | 2.11%   |
| 10.01-20.0 | 10        | 16     | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 828       | 32.73%  |
| 1001-2000      | 546       | 21.58%  |
| 501-1000       | 365       | 14.43%  |
| 2001-3000      | 313       | 12.37%  |
| 251-500        | 229       | 9.05%   |
| 101-250        | 131       | 5.18%   |
| Unknown        | 45        | 1.78%   |
| 51-100         | 35        | 1.38%   |
| 1-20           | 20        | 0.79%   |
| 21-50          | 18        | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 531       | 20.16%  |
| 251-500        | 437       | 16.59%  |
| 51-100         | 417       | 15.83%  |
| 501-1000       | 344       | 13.06%  |
| 1001-2000      | 318       | 12.07%  |
| More than 3000 | 160       | 6.07%   |
| 1-20           | 144       | 5.47%   |
| 21-50          | 123       | 4.67%   |
| 2001-3000      | 114       | 4.33%   |
| Unknown        | 45        | 1.71%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7         | 10     | 2.37%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 5         | 5      | 1.69%   |
| Samsung Electronics SSD 840 EVO 120GB | 5         | 6      | 1.69%   |
| Seagate ST2000DM001-1ER164 2TB        | 4         | 4      | 1.36%   |
| Seagate ST2000DM001-1CH164 2TB        | 4         | 5      | 1.36%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.36%   |
| WDC WD10JFCX-68N6GN0 1TB              | 3         | 4      | 1.02%   |
| Toshiba MQ01ABD100 1TB                | 3         | 3      | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 1.02%   |
| Seagate ST1000DM003-1SB102 1TB        | 3         | 4      | 1.02%   |
| Samsung Electronics HD501LJ 500GB     | 3         | 4      | 1.02%   |
| WDC WD6400AAKS-22A7B2 640GB           | 2         | 2      | 0.68%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2         | 3      | 0.68%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 2      | 0.68%   |
| WD MediaMax WL5000GSA12872B 5TB       | 2         | 2      | 0.68%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.68%   |
| Toshiba MK5055GSX 500GB               | 2         | 4      | 0.68%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.68%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 0.68%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.68%   |
| Seagate ST31000528AS 1TB              | 2         | 5      | 0.68%   |
| Seagate ST1000DM003-1ER162 1TB        | 2         | 2      | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 0.68%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 2         | 2      | 0.68%   |
| Samsung Electronics SSD 870 EVO 1TB   | 2         | 2      | 0.68%   |
| Samsung Electronics HN-M500MBB 500GB  | 2         | 2      | 0.68%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 0.68%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 3      | 0.68%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 3      | 0.68%   |
| Kingston SMS200S3240G 240GB SSD       | 2         | 2      | 0.68%   |
| Kingston SHFS37A120G 120GB SSD        | 2         | 2      | 0.68%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.68%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 0.68%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.68%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 0.68%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 0.34%   |
| XPG GAMMIX S41 256GB                  | 1         | 1      | 0.34%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 79        | 98     | 27.53%  |
| WDC                      | 53        | 62     | 18.47%  |
| Samsung Electronics      | 34        | 43     | 11.85%  |
| Toshiba                  | 27        | 37     | 9.41%   |
| Hitachi                  | 14        | 16     | 4.88%   |
| Kingston                 | 10        | 17     | 3.48%   |
| Crucial                  | 10        | 11     | 3.48%   |
| Intel                    | 7         | 8      | 2.44%   |
| HGST                     | 7         | 7      | 2.44%   |
| SanDisk                  | 6         | 6      | 2.09%   |
| Maxtor                   | 4         | 4      | 1.39%   |
| LITEONIT                 | 3         | 3      | 1.05%   |
| WD MediaMax              | 2         | 2      | 0.7%    |
| Transcend                | 2         | 3      | 0.7%    |
| SK hynix                 | 2         | 2      | 0.7%    |
| Patriot                  | 2         | 2      | 0.7%    |
| OCZ                      | 2         | 2      | 0.7%    |
| Micron Technology        | 2         | 2      | 0.7%    |
| Fujitsu                  | 2         | 3      | 0.7%    |
| Corsair                  | 2         | 2      | 0.7%    |
| XrayDisk                 | 1         | 1      | 0.35%   |
| XPG                      | 1         | 1      | 0.35%   |
| SuperTalent              | 1         | 1      | 0.35%   |
| SSSTC                    | 1         | 1      | 0.35%   |
| SPCC                     | 1         | 1      | 0.35%   |
| Silicon Motion           | 1         | 1      | 0.35%   |
| Phison                   | 1         | 1      | 0.35%   |
| Netac                    | 1         | 1      | 0.35%   |
| LEQIXIANG                | 1         | 1      | 0.35%   |
| KingFast                 | 1         | 1      | 0.35%   |
| Intenso                  | 1         | 1      | 0.35%   |
| Hewlett-Packard          | 1         | 1      | 0.35%   |
| GOODRAM                  | 1         | 1      | 0.35%   |
| EXRAM                    | 1         | 1      | 0.35%   |
| Biwin Storage Technology | 1         | 1      | 0.35%   |
| Apple                    | 1         | 1      | 0.35%   |
| A-DATA Technology        | 1         | 2      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 98     | 38.73%  |
| WDC                 | 51        | 60     | 25%     |
| Toshiba             | 26        | 36     | 12.75%  |
| Samsung Electronics | 17        | 23     | 8.33%   |
| Hitachi             | 14        | 16     | 6.86%   |
| HGST                | 7         | 7      | 3.43%   |
| Maxtor              | 4         | 4      | 1.96%   |
| WD MediaMax         | 2         | 2      | 0.98%   |
| Fujitsu             | 2         | 3      | 0.98%   |
| Hewlett-Packard     | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 184       | 251    | 69.43%  |
| SSD  | 66        | 82     | 24.91%  |
| NVMe | 15        | 15     | 5.66%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EADS-00R6B0 2TB           | 1         | 1      | 25%     |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 25%     |
| Samsung Electronics HD502HJ 500GB | 1         | 5      | 25%     |
| Hitachi HDS721025CLA382 250GB     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 6      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1326      | 2775   | 48.84%  |
| Detected | 1132      | 2722   | 41.69%  |
| Malfunc  | 253       | 348    | 9.32%   |
| Failed   | 4         | 8      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1432      | 42.45%  |
| AMD                                     | 634       | 18.8%   |
| Samsung Electronics                     | 386       | 11.44%  |
| SanDisk                                 | 150       | 4.45%   |
| SK hynix                                | 85        | 2.52%   |
| Kingston Technology Company             | 78        | 2.31%   |
| ASMedia Technology                      | 71        | 2.1%    |
| Phison Electronics                      | 69        | 2.05%   |
| Toshiba America Info Systems            | 48        | 1.42%   |
| Micron Technology                       | 45        | 1.33%   |
| Marvell Technology Group                | 39        | 1.16%   |
| Silicon Motion                          | 37        | 1.1%    |
| Micron/Crucial Technology               | 36        | 1.07%   |
| JMicron Technology                      | 34        | 1.01%   |
| KIOXIA                                  | 33        | 0.98%   |
| Nvidia                                  | 30        | 0.89%   |
| LSI Logic / Symbios Logic               | 20        | 0.59%   |
| ADATA Technology                        | 20        | 0.59%   |
| Broadcom / LSI                          | 17        | 0.5%    |
| Realtek Semiconductor                   | 15        | 0.44%   |
| Seagate Technology                      | 11        | 0.33%   |
| MAXIO Technology (Hangzhou)             | 10        | 0.3%    |
| Solid State Storage Technology          | 9         | 0.27%   |
| Union Memory (Shenzhen)                 | 7         | 0.21%   |
| Silicon Image                           | 6         | 0.18%   |
| Shenzhen Longsys Electronics            | 6         | 0.18%   |
| Adaptec                                 | 6         | 0.18%   |
| VIA Technologies                        | 5         | 0.15%   |
| Yangtze Memory Technologies             | 4         | 0.12%   |
| Apple                                   | 4         | 0.12%   |
| Lite-On Technology                      | 3         | 0.09%   |
| Lenovo                                  | 3         | 0.09%   |
| INNOGRIT                                | 3         | 0.09%   |
| Solidigm                                | 2         | 0.06%   |
| Promise Technology                      | 2         | 0.06%   |
| Hewlett-Packard                         | 2         | 0.06%   |
| Biwin Storage Technology                | 2         | 0.06%   |
| Tekram Technology                       | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 423       | 10.98%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 194       | 5.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 125       | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 122       | 3.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 93        | 2.41%   |
| AMD 400 Series Chipset SATA Controller                                         | 91        | 2.36%   |
| Intel Volume Management Device NVMe RAID Controller                            | 77        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 73        | 1.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 69        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 68        | 1.77%   |
| AMD 500 Series Chipset SATA Controller                                         | 68        | 1.77%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 65        | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 64        | 1.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 61        | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 60        | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 56        | 1.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 53        | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 43        | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 42        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 42        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 41        | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 41        | 1.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 39        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 39        | 1.01%   |
| Intel SSD 660P Series                                                          | 37        | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 37        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 35        | 0.91%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 34        | 0.88%   |
| Phison E12 NVMe Controller                                                     | 34        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 34        | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 32        | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                         | 32        | 0.83%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 30        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 30        | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 29        | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 26        | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 26        | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                            | 25        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 23        | 0.6%    |
| AMD FCH SATA Controller D                                                      | 23        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1808      | 54.07%  |
| NVMe | 1033      | 30.89%  |
| IDE  | 241       | 7.21%   |
| RAID | 227       | 6.79%   |
| SAS  | 21        | 0.63%   |
| SCSI | 14        | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 1625      | 67.04%  |
| AMD       | 789       | 32.55%  |
| ARM       | 8         | 0.33%   |
| Qualcomm  | 1         | 0.04%   |
| HISILICON | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 33        | 1.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 32        | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 26        | 1.07%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 1.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 22        | 0.91%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 21        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 19        | 0.78%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 19        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.74%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 18        | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 17        | 0.7%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 16        | 0.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 0.66%   |
| AMD FX-8350 Eight-Core Processor              | 16        | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 15        | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 14        | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 0.58%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 14        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.54%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 13        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 12        | 0.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 12        | 0.49%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 12        | 0.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 12        | 0.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 11        | 0.45%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 11        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 490       | 20.2%   |
| Intel Core i5           | 465       | 19.17%  |
| Other                   | 232       | 9.56%   |
| AMD Ryzen 5             | 226       | 9.32%   |
| AMD Ryzen 7             | 183       | 7.54%   |
| Intel Core i3           | 116       | 4.78%   |
| Intel Xeon              | 90        | 3.71%   |
| AMD Ryzen 9             | 74        | 3.05%   |
| Intel Core 2 Duo        | 59        | 2.43%   |
| Intel Celeron           | 53        | 2.18%   |
| AMD FX                  | 52        | 2.14%   |
| Intel Pentium           | 34        | 1.4%    |
| AMD Ryzen 3             | 31        | 1.28%   |
| Intel Core i9           | 21        | 0.87%   |
| AMD Ryzen 7 PRO         | 21        | 0.87%   |
| AMD Phenom II X4        | 18        | 0.74%   |
| AMD A8                  | 18        | 0.74%   |
| AMD A10                 | 18        | 0.74%   |
| Intel Atom              | 16        | 0.66%   |
| AMD A6                  | 16        | 0.66%   |
| Intel Pentium Dual-Core | 15        | 0.62%   |
| Intel Pentium Silver    | 14        | 0.58%   |
| Intel Core 2 Quad       | 14        | 0.58%   |
| AMD Athlon              | 14        | 0.58%   |
| AMD Ryzen 5 PRO         | 11        | 0.45%   |
| AMD Phenom II X6        | 11        | 0.45%   |
| AMD Ryzen Threadripper  | 9         | 0.37%   |
| AMD Athlon II X2        | 9         | 0.37%   |
| AMD A4                  | 9         | 0.37%   |
| AMD Opteron             | 7         | 0.29%   |
| Intel Core 2            | 6         | 0.25%   |
| AMD E2                  | 5         | 0.21%   |
| AMD Ryzen 3 PRO         | 4         | 0.16%   |
| AMD E                   | 4         | 0.16%   |
| Intel Pentium Dual      | 3         | 0.12%   |
| Intel Genuine           | 3         | 0.12%   |
| Intel Core m3           | 3         | 0.12%   |
| AMD EPYC                | 3         | 0.12%   |
| AMD E1                  | 3         | 0.12%   |
| AMD Athlon X2           | 3         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 872       | 35.88%  |
| 2       | 716       | 29.47%  |
| 6       | 315       | 12.96%  |
| 8       | 284       | 11.69%  |
| 12      | 69        | 2.84%   |
| 16      | 39        | 1.6%    |
| 1       | 36        | 1.48%   |
| 10      | 31        | 1.28%   |
| 3       | 18        | 0.74%   |
| 14      | 17        | 0.7%    |
| 24      | 11        | 0.45%   |
| 32      | 7         | 0.29%   |
| Unknown | 4         | 0.16%   |
| 40      | 3         | 0.12%   |
| 64      | 2         | 0.08%   |
| 20      | 2         | 0.08%   |
| 48      | 1         | 0.04%   |
| 44      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 18      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2379      | 98.1%   |
| 2       | 37        | 1.53%   |
| 4       | 6         | 0.25%   |
| Unknown | 3         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1847      | 76.01%  |
| 1       | 575       | 23.66%  |
| Unknown | 4         | 0.16%   |
| 8       | 3         | 0.12%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2362      | 97.2%   |
| Unknown        | 56        | 2.3%    |
| 32-bit         | 8         | 0.33%   |
| 64-bit         | 4         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 619       | 24.89%  |
| 0x306c3    | 103       | 4.14%   |
| 0x206a7    | 96        | 3.86%   |
| 0x306a9    | 94        | 3.78%   |
| 0x806c1    | 66        | 2.65%   |
| 0x906ea    | 61        | 2.45%   |
| 0x506e3    | 57        | 2.29%   |
| 0x08701021 | 53        | 2.13%   |
| 0x0a50000c | 52        | 2.09%   |
| 0x806ec    | 51        | 2.05%   |
| 0x406e3    | 50        | 2.01%   |
| 0x0800820d | 45        | 1.81%   |
| 0x906e9    | 44        | 1.77%   |
| 0x806ea    | 43        | 1.73%   |
| 0x08108109 | 43        | 1.73%   |
| 0x1067a    | 41        | 1.65%   |
| 0x806e9    | 39        | 1.57%   |
| 0x40651    | 37        | 1.49%   |
| 0x06000852 | 37        | 1.49%   |
| 0x08600106 | 36        | 1.45%   |
| 0x306d4    | 32        | 1.29%   |
| 0x08608103 | 28        | 1.13%   |
| 0x0a50000d | 25        | 1.01%   |
| 0x010000c8 | 25        | 1.01%   |
| 0x20655    | 22        | 0.88%   |
| 0x08108102 | 22        | 0.88%   |
| 0x08001138 | 21        | 0.84%   |
| 0x0a20120a | 20        | 0.8%    |
| 0x08600104 | 19        | 0.76%   |
| 0x906a3    | 18        | 0.72%   |
| 0x06001119 | 18        | 0.72%   |
| 0x0a404102 | 17        | 0.68%   |
| 0x0a201009 | 17        | 0.68%   |
| 0x08701013 | 17        | 0.68%   |
| 0x0810100b | 15        | 0.6%    |
| 0x906ed    | 14        | 0.56%   |
| 0x806eb    | 14        | 0.56%   |
| 0x08101016 | 14        | 0.56%   |
| 0x706a8    | 13        | 0.52%   |
| 0x08001137 | 13        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 366       | 15.08%  |
| Haswell          | 221       | 9.11%   |
| IvyBridge        | 158       | 6.51%   |
| Zen 2            | 152       | 6.26%   |
| Skylake          | 149       | 6.14%   |
| Zen 3            | 141       | 5.81%   |
| SandyBridge      | 137       | 5.64%   |
| Zen+             | 119       | 4.9%    |
| Unknown          | 103       | 4.24%   |
| TigerLake        | 94        | 3.87%   |
| Zen              | 83        | 3.42%   |
| Penryn           | 75        | 3.09%   |
| Alderlake Hybrid | 73        | 3.01%   |
| Piledriver       | 64        | 2.64%   |
| Westmere         | 53        | 2.18%   |
| K10              | 53        | 2.18%   |
| IceLake          | 51        | 2.1%    |
| Broadwell        | 48        | 1.98%   |
| CometLake        | 47        | 1.94%   |
| Core             | 35        | 1.44%   |
| Goldmont plus    | 34        | 1.4%    |
| Nehalem          | 28        | 1.15%   |
| Excavator        | 22        | 0.91%   |
| Steamroller      | 14        | 0.58%   |
| Silvermont       | 14        | 0.58%   |
| Puma             | 12        | 0.49%   |
| Bulldozer        | 11        | 0.45%   |
| Bonnell          | 10        | 0.41%   |
| Bobcat           | 10        | 0.41%   |
| K10 Llano        | 9         | 0.37%   |
| Jaguar           | 9         | 0.37%   |
| Goldmont         | 8         | 0.33%   |
| K8 Hammer        | 7         | 0.29%   |
| Tremont          | 5         | 0.21%   |
| K8 & K10 hybrid  | 4         | 0.16%   |
| P6               | 3         | 0.12%   |
| Gracemont        | 3         | 0.12%   |
| NetBurst         | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1226      | 42.55%  |
| Nvidia                     | 821       | 28.5%   |
| AMD                        | 806       | 27.98%  |
| Matrox Electronics Systems | 19        | 0.66%   |
| ASPEED Technology          | 6         | 0.21%   |
| S3 Graphics                | 2         | 0.07%   |
| VIA Technologies           | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 91        | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 85        | 2.85%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 82        | 2.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 71        | 2.38%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 70        | 2.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 69        | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 67        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 66        | 2.21%   |
| Intel UHD Graphics 620                                                      | 63        | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 54        | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 54        | 1.81%   |
| Intel HD Graphics 620                                                       | 53        | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 52        | 1.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 48        | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 46        | 1.54%   |
| Intel HD Graphics 530                                                       | 41        | 1.37%   |
| AMD Lucienne                                                                | 41        | 1.37%   |
| Intel HD Graphics 630                                                       | 36        | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                         | 33        | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 32        | 1.07%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 31        | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 30        | 1.01%   |
| Intel HD Graphics 5500                                                      | 29        | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 26        | 0.87%   |
| AMD Rembrandt [Radeon 680M]                                                 | 23        | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 22        | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 21        | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 20        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 18        | 0.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 18        | 0.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 18        | 0.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 18        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 17        | 0.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 17        | 0.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 17        | 0.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 16        | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 15        | 0.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 15        | 0.5%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 15        | 0.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 15        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 831       | 34.07%  |
| 1 x AMD            | 631       | 25.87%  |
| 1 x Nvidia         | 439       | 18%     |
| Intel + Nvidia     | 304       | 12.46%  |
| AMD + Nvidia       | 64        | 2.62%   |
| Intel + AMD        | 59        | 2.42%   |
| 2 x AMD            | 52        | 2.13%   |
| 1 x Matrox         | 15        | 0.62%   |
| Other              | 12        | 0.49%   |
| 2 x Nvidia         | 10        | 0.41%   |
| 2 x Intel          | 7         | 0.29%   |
| Nvidia + Matrox    | 3         | 0.12%   |
| Nvidia + ASPEED    | 3         | 0.12%   |
| 1 x ASPEED         | 3         | 0.12%   |
| 1 x S3 Graphics    | 2         | 0.08%   |
| 1 x VIA            | 1         | 0.04%   |
| Intel + 2 x Nvidia | 1         | 0.04%   |
| AMD + 2 x Nvidia   | 1         | 0.04%   |
| AMD + Matrox       | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1960      | 79.8%   |
| Proprietary | 445       | 18.12%  |
| Unknown     | 51        | 2.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1179      | 47.56%  |
| 1.01-2.0   | 303       | 12.22%  |
| 0.01-0.5   | 290       | 11.7%   |
| 3.01-4.0   | 202       | 8.15%   |
| 7.01-8.0   | 171       | 6.9%    |
| 0.51-1.0   | 168       | 6.78%   |
| 5.01-6.0   | 66        | 2.66%   |
| 8.01-16.0  | 65        | 2.62%   |
| 2.01-3.0   | 21        | 0.85%   |
| 16.01-24.0 | 12        | 0.48%   |
| 4.01-5.0   | 1         | 0.04%   |
| 24.01-32.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 333       | 11.84%  |
| AU Optronics            | 307       | 10.91%  |
| BOE                     | 236       | 8.39%   |
| Chimei Innolux          | 226       | 8.03%   |
| LG Display              | 203       | 7.22%   |
| Dell                    | 200       | 7.11%   |
| Goldstar                | 173       | 6.15%   |
| Hewlett-Packard         | 110       | 3.91%   |
| Acer                    | 96        | 3.41%   |
| Ancor Communications    | 82        | 2.92%   |
| BenQ                    | 81        | 2.88%   |
| AOC                     | 69        | 2.45%   |
| Philips                 | 60        | 2.13%   |
| Lenovo                  | 53        | 1.88%   |
| Sharp                   | 52        | 1.85%   |
| Apple                   | 52        | 1.85%   |
| ASUSTek Computer        | 29        | 1.03%   |
| InfoVision              | 28        | 1%      |
| PANDA                   | 27        | 0.96%   |
| Iiyama                  | 25        | 0.89%   |
| ViewSonic               | 24        | 0.85%   |
| Fujitsu Siemens         | 22        | 0.78%   |
| Chi Mei Optoelectronics | 22        | 0.78%   |
| Unknown                 | 20        | 0.71%   |
| Sony                    | 17        | 0.6%    |
| Eizo                    | 16        | 0.57%   |
| LG Electronics          | 14        | 0.5%    |
| CSO                     | 12        | 0.43%   |
| Panasonic               | 10        | 0.36%   |
| MSI                     | 10        | 0.36%   |
| Vizio                   | 9         | 0.32%   |
| Pixio                   | 9         | 0.32%   |
| NEC Computers           | 9         | 0.32%   |
| Sceptre Tech            | 8         | 0.28%   |
| LG Philips              | 8         | 0.28%   |
| Medion                  | 7         | 0.25%   |
| Gigabyte Technology     | 7         | 0.25%   |
| Insignia                | 6         | 0.21%   |
| HUAWEI                  | 6         | 0.21%   |
| Toshiba                 | 5         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 14        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 14        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 13        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 11        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 11        | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 11        | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 9         | 0.31%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 9         | 0.31%   |
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                   | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 8         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 8         | 0.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 7         | 0.24%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 7         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 7         | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7         | 0.24%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 7         | 0.24%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 7         | 0.24%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 6         | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 6         | 0.2%    |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch           | 6         | 0.2%    |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 6         | 0.2%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 6         | 0.2%    |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 6         | 0.2%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 5         | 0.17%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.17%   |
| Pixio U29I WAM2900 2560x1080 690x260mm 29.0-inch                      | 5         | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 5         | 0.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 5         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1289      | 47.78%  |
| 1366x768 (WXGA)    | 318       | 11.79%  |
| 2560x1440 (QHD)    | 185       | 6.86%   |
| 3840x2160 (4K)     | 181       | 6.71%   |
| 1920x1200 (WUXGA)  | 94        | 3.48%   |
| 1600x900 (HD+)     | 89        | 3.3%    |
| 1280x1024 (SXGA)   | 76        | 2.82%   |
| 1680x1050 (WSXGA+) | 67        | 2.48%   |
| 1440x900 (WXGA+)   | 47        | 1.74%   |
| 1280x800 (WXGA)    | 46        | 1.7%    |
| 2560x1080          | 45        | 1.67%   |
| 3440x1440          | 31        | 1.15%   |
| 2560x1600          | 30        | 1.11%   |
| Unknown            | 29        | 1.07%   |
| 3840x1080          | 19        | 0.7%    |
| 2880x1800          | 17        | 0.63%   |
| 1024x768 (XGA)     | 16        | 0.59%   |
| 1360x768           | 12        | 0.44%   |
| 1920x540           | 8         | 0.3%    |
| 2288x1287          | 7         | 0.26%   |
| 2160x1440          | 7         | 0.26%   |
| 3200x1800 (QHD+)   | 6         | 0.22%   |
| 1600x1200          | 6         | 0.22%   |
| 3840x2400          | 5         | 0.19%   |
| 3840x1600          | 5         | 0.19%   |
| 1024x600           | 5         | 0.19%   |
| 3840x1200          | 4         | 0.15%   |
| 2736x1824          | 3         | 0.11%   |
| 2520x1680          | 3         | 0.11%   |
| 2256x1504          | 3         | 0.11%   |
| 2240x1400          | 3         | 0.11%   |
| 1280x720 (HD)      | 3         | 0.11%   |
| 4480x1440          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |
| 2048x1536          | 2         | 0.07%   |
| 2048x1152          | 2         | 0.07%   |
| 1400x1050          | 2         | 0.07%   |
| 1280x960           | 2         | 0.07%   |
| 8960x2160          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 638       | 22.67%  |
| 27      | 280       | 9.95%   |
| 24      | 228       | 8.1%    |
| 13      | 222       | 7.89%   |
| 14      | 221       | 7.85%   |
| 21      | 178       | 6.33%   |
| 23      | 165       | 5.86%   |
| 17      | 155       | 5.51%   |
| Unknown | 96        | 3.41%   |
| 31      | 71        | 2.52%   |
| 19      | 71        | 2.52%   |
| 34      | 59        | 2.1%    |
| 12      | 54        | 1.92%   |
| 22      | 44        | 1.56%   |
| 18      | 41        | 1.46%   |
| 16      | 36        | 1.28%   |
| 20      | 31        | 1.1%    |
| 32      | 24        | 0.85%   |
| 84      | 21        | 0.75%   |
| 11      | 19        | 0.68%   |
| 25      | 16        | 0.57%   |
| 72      | 15        | 0.53%   |
| 54      | 13        | 0.46%   |
| 29      | 13        | 0.46%   |
| 40      | 12        | 0.43%   |
| 26      | 12        | 0.43%   |
| 28      | 8         | 0.28%   |
| 142     | 7         | 0.25%   |
| 37      | 7         | 0.25%   |
| 10      | 6         | 0.21%   |
| 49      | 5         | 0.18%   |
| 42      | 5         | 0.18%   |
| 33      | 5         | 0.18%   |
| 86      | 3         | 0.11%   |
| 74      | 3         | 0.11%   |
| 52      | 3         | 0.11%   |
| 48      | 3         | 0.11%   |
| 43      | 3         | 0.11%   |
| 35      | 3         | 0.11%   |
| 65      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 989       | 35.95%  |
| 501-600        | 621       | 22.57%  |
| 401-500        | 314       | 11.41%  |
| 201-300        | 201       | 7.31%   |
| 351-400        | 197       | 7.16%   |
| 601-700        | 127       | 4.62%   |
| Unknown        | 96        | 3.49%   |
| 701-800        | 88        | 3.2%    |
| 1501-2000      | 40        | 1.45%   |
| 1001-1500      | 34        | 1.24%   |
| 801-900        | 25        | 0.91%   |
| 901-1000       | 8         | 0.29%   |
| More than 2000 | 7         | 0.25%   |
| 101-200        | 3         | 0.11%   |
| 1-100          | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1889      | 75.35%  |
| 16/10   | 311       | 12.41%  |
| Unknown | 74        | 2.95%   |
| 21/9    | 69        | 2.75%   |
| 5/4     | 66        | 2.63%   |
| 4/3     | 37        | 1.48%   |
| 3/2     | 28        | 1.12%   |
| 6/5     | 7         | 0.28%   |
| 1.00    | 7         | 0.28%   |
| 32/9    | 6         | 0.24%   |
| 2.65    | 5         | 0.2%    |
| 0.56    | 3         | 0.12%   |
| 3.73    | 1         | 0.04%   |
| 3.40    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 641       | 23.06%  |
| 201-250        | 476       | 17.12%  |
| 81-90          | 347       | 12.48%  |
| 301-350        | 285       | 10.25%  |
| 351-500        | 176       | 6.33%   |
| 151-200        | 156       | 5.61%   |
| 121-130        | 117       | 4.21%   |
| 251-300        | 102       | 3.67%   |
| 71-80          | 98        | 3.53%   |
| Unknown        | 96        | 3.45%   |
| More than 1000 | 73        | 2.63%   |
| 141-150        | 55        | 1.98%   |
| 61-70          | 46        | 1.65%   |
| 501-1000       | 36        | 1.29%   |
| 111-120        | 25        | 0.9%    |
| 51-60          | 21        | 0.76%   |
| 131-140        | 16        | 0.58%   |
| 41-50          | 6         | 0.22%   |
| 91-100         | 5         | 0.18%   |
| 1-40           | 3         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 895       | 33.3%   |
| 121-160       | 751       | 27.94%  |
| 101-120       | 626       | 23.29%  |
| 161-240       | 196       | 7.29%   |
| Unknown       | 96        | 3.57%   |
| More than 240 | 67        | 2.49%   |
| 1-50          | 57        | 2.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1872      | 75.24%  |
| 2     | 492       | 19.77%  |
| 0     | 64        | 2.57%   |
| 3     | 54        | 2.17%   |
| 4     | 6         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1331      | 36.62%  |
| Intel                             | 1262      | 34.72%  |
| Qualcomm Atheros                  | 307       | 8.45%   |
| Broadcom                          | 200       | 5.5%    |
| MediaTek                          | 78        | 2.15%   |
| Broadcom Limited                  | 35        | 0.96%   |
| Ralink Technology                 | 34        | 0.94%   |
| TP-Link                           | 33        | 0.91%   |
| ASIX Electronics                  | 29        | 0.8%    |
| Ralink                            | 26        | 0.72%   |
| Nvidia                            | 25        | 0.69%   |
| Marvell Technology Group          | 24        | 0.66%   |
| Sierra Wireless                   | 15        | 0.41%   |
| DisplayLink                       | 13        | 0.36%   |
| Lenovo                            | 12        | 0.33%   |
| Dell                              | 12        | 0.33%   |
| Samsung Electronics               | 11        | 0.3%    |
| D-Link                            | 10        | 0.28%   |
| Aquantia                          | 10        | 0.28%   |
| NetGear                           | 8         | 0.22%   |
| Microsoft                         | 8         | 0.22%   |
| Ericsson Business Mobile Networks | 8         | 0.22%   |
| Edimax Technology                 | 8         | 0.22%   |
| Qualcomm                          | 7         | 0.19%   |
| Huawei Technologies               | 7         | 0.19%   |
| Linksys                           | 6         | 0.17%   |
| Hewlett-Packard                   | 6         | 0.17%   |
| D-Link System                     | 6         | 0.17%   |
| ASUSTek Computer                  | 6         | 0.17%   |
| Xiaomi                            | 5         | 0.14%   |
| U-Blox                            | 5         | 0.14%   |
| Cypress Semiconductor             | 5         | 0.14%   |
| AVM                               | 5         | 0.14%   |
| Qualcomm Atheros Communications   | 4         | 0.11%   |
| Belkin Components                 | 4         | 0.11%   |
| Motorola PCS                      | 3         | 0.08%   |
| Microchip Technology              | 3         | 0.08%   |
| Mellanox Technologies             | 3         | 0.08%   |
| JMicron Technology                | 3         | 0.08%   |
| ICS Advent                        | 3         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 961       | 22.22%  |
| Intel Wi-Fi 6 AX200                                               | 161       | 3.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 84        | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82        | 1.9%    |
| Intel Wireless 8265 / 8275                                        | 79        | 1.83%   |
| Intel I211 Gigabit Network Connection                             | 78        | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 76        | 1.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 75        | 1.73%   |
| Intel Wi-Fi 6 AX201                                               | 73        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 64        | 1.48%   |
| Intel Wireless 8260                                               | 61        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 54        | 1.25%   |
| Intel Wireless 7260                                               | 54        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 48        | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 45        | 1.04%   |
| Intel Wireless-AC 9260                                            | 44        | 1.02%   |
| Intel Wireless 7265                                               | 43        | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 40        | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 38        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 38        | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 35        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 33        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 33        | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32        | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 31        | 0.72%   |
| Intel Ethernet Controller I225-V                                  | 31        | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 30        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 26        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 23        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 22        | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 22        | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 22        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 21        | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 21        | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 21        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 964       | 50.1%   |
| Realtek Semiconductor                 | 301       | 15.64%  |
| Qualcomm Atheros                      | 242       | 12.58%  |
| Broadcom                              | 129       | 6.7%    |
| MediaTek                              | 73        | 3.79%   |
| Ralink Technology                     | 34        | 1.77%   |
| Ralink                                | 26        | 1.35%   |
| TP-Link                               | 24        | 1.25%   |
| Broadcom Limited                      | 21        | 1.09%   |
| Sierra Wireless                       | 15        | 0.78%   |
| D-Link                                | 10        | 0.52%   |
| NetGear                               | 8         | 0.42%   |
| Edimax Technology                     | 8         | 0.42%   |
| Dell                                  | 8         | 0.42%   |
| Qualcomm                              | 6         | 0.31%   |
| Microsoft                             | 6         | 0.31%   |
| Linksys                               | 6         | 0.31%   |
| ASUSTek Computer                      | 6         | 0.31%   |
| AVM                                   | 5         | 0.26%   |
| Qualcomm Atheros Communications       | 4         | 0.21%   |
| Marvell Technology Group              | 4         | 0.21%   |
| D-Link System                         | 4         | 0.21%   |
| Belkin Components                     | 4         | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.1%    |
| ZyXEL Communications                  | 1         | 0.05%   |
| Xiaomi                                | 1         | 0.05%   |
| Wacom                                 | 1         | 0.05%   |
| Samsung Electronics                   | 1         | 0.05%   |
| Realtek                               | 1         | 0.05%   |
| Quectel Wireless Solutions            | 1         | 0.05%   |
| Qualcomm Technologies                 | 1         | 0.05%   |
| Micro Star International              | 1         | 0.05%   |
| Intersil                              | 1         | 0.05%   |
| IMC Networks                          | 1         | 0.05%   |
| Hewlett-Packard                       | 1         | 0.05%   |
| Fibocom                               | 1         | 0.05%   |
| Ericsson Business Mobile Networks     | 1         | 0.05%   |
| BUFFALO                               | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 161       | 8.3%    |
| Intel Wireless 8265 / 8275                                     | 79        | 4.07%   |
| Intel Wi-Fi 6 AX201                                            | 73        | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 64        | 3.3%    |
| Intel Wireless 8260                                            | 61        | 3.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 54        | 2.78%   |
| Intel Wireless 7260                                            | 54        | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 48        | 2.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 45        | 2.32%   |
| Intel Wireless-AC 9260                                         | 44        | 2.27%   |
| Intel Wireless 7265                                            | 43        | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 40        | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 38        | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 35        | 1.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 33        | 1.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 33        | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 32        | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 31        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 30        | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 26        | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 23        | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 22        | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 22        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 21        | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 21        | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 21        | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                  | 18        | 0.93%   |
| Intel Centrino Ultimate-N 6300                                 | 17        | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 16        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.83%   |
| Intel Wireless 3165                                            | 16        | 0.83%   |
| Intel Wireless 3160                                            | 16        | 0.83%   |
| Realtek 802.11ac NIC                                           | 13        | 0.67%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.62%   |
| Ralink MT7601U Wireless Adapter                                | 12        | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1207      | 52.92%  |
| Intel                                  | 677       | 29.68%  |
| Broadcom                               | 104       | 4.56%   |
| Qualcomm Atheros                       | 89        | 3.9%    |
| ASIX Electronics                       | 29        | 1.27%   |
| Nvidia                                 | 25        | 1.1%    |
| Marvell Technology Group               | 20        | 0.88%   |
| Broadcom Limited                       | 14        | 0.61%   |
| DisplayLink                            | 13        | 0.57%   |
| Lenovo                                 | 12        | 0.53%   |
| Samsung Electronics                    | 10        | 0.44%   |
| Aquantia                               | 10        | 0.44%   |
| TP-Link                                | 9         | 0.39%   |
| Huawei Technologies                    | 6         | 0.26%   |
| MediaTek                               | 5         | 0.22%   |
| Cypress Semiconductor                  | 5         | 0.22%   |
| Xiaomi                                 | 4         | 0.18%   |
| Motorola PCS                           | 3         | 0.13%   |
| JMicron Technology                     | 3         | 0.13%   |
| ICS Advent                             | 3         | 0.13%   |
| Dell                                   | 3         | 0.13%   |
| VIA Technologies                       | 2         | 0.09%   |
| NetXen Incorporated                    | 2         | 0.09%   |
| Microsoft                              | 2         | 0.09%   |
| HMD Global                             | 2         | 0.09%   |
| D-Link System                          | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Solarflare Communications              | 1         | 0.04%   |
| Sitecom Europe                         | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| Qualcomm                               | 1         | 0.04%   |
| OPPO Electronics                       | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| MosChip Semiconductor                  | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| IBM                                    | 1         | 0.04%   |
| Hewlett-Packard                        | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 961       | 41.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 84        | 3.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82        | 3.5%    |
| Intel I211 Gigabit Network Connection                             | 78        | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 76        | 3.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 75        | 3.2%    |
| Intel Ethernet Connection I217-LM                                 | 39        | 1.67%   |
| Intel Ethernet Connection (2) I219-V                              | 38        | 1.62%   |
| Intel Ethernet Controller I225-V                                  | 31        | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 1.07%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.94%   |
| Intel I210 Gigabit Network Connection                             | 20        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 19        | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 18        | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.6%    |
| Nvidia MCP79 Ethernet                                             | 13        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 11        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.43%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 0.43%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 10        | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 10        | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 9         | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.38%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 8         | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2091      | 52.91%  |
| WiFi     | 1819      | 46.03%  |
| Modem    | 30        | 0.76%   |
| Unknown  | 12        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1357      | 52.6%   |
| Ethernet | 1222      | 47.36%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1320      | 54.32%  |
| 1     | 975       | 40.12%  |
| 3     | 77        | 3.17%   |
| 0     | 28        | 1.15%   |
| 4     | 21        | 0.86%   |
| 5     | 6         | 0.25%   |
| 6     | 2         | 0.08%   |
| 8     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1907      | 76.99%  |
| Yes  | 570       | 23.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 807       | 50.63%  |
| Realtek Semiconductor           | 157       | 9.85%   |
| Cambridge Silicon Radio         | 113       | 7.09%   |
| Qualcomm Atheros Communications | 96        | 6.02%   |
| Broadcom                        | 65        | 4.08%   |
| Apple                           | 62        | 3.89%   |
| Lite-On Technology              | 61        | 3.83%   |
| IMC Networks                    | 53        | 3.32%   |
| Foxconn / Hon Hai               | 52        | 3.26%   |
| ASUSTek Computer                | 30        | 1.88%   |
| MediaTek                        | 15        | 0.94%   |
| Hewlett-Packard                 | 13        | 0.82%   |
| Dell                            | 13        | 0.82%   |
| Realtek                         | 11        | 0.69%   |
| Toshiba                         | 6         | 0.38%   |
| Ralink                          | 5         | 0.31%   |
| TP-Link                         | 4         | 0.25%   |
| Marvell Semiconductor           | 4         | 0.25%   |
| Foxconn International           | 3         | 0.19%   |
| Belkin Components               | 3         | 0.19%   |
| USI                             | 2         | 0.13%   |
| Taiyo Yuden                     | 2         | 0.13%   |
| Smart Modular Technologies      | 2         | 0.13%   |
| Integrated System Solution      | 2         | 0.13%   |
| HTC (High Tech Computer)        | 2         | 0.13%   |
| Alps Electric                   | 2         | 0.13%   |
| Unknown                         | 1         | 0.06%   |
| SINO WEALTH                     | 1         | 0.06%   |
| Ralink Technology               | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Mobile Action Technology        | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Kensington                      | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 247       | 15.47%  |
| Intel AX200 Bluetooth                                                               | 153       | 9.58%   |
| Intel AX201 Bluetooth                                                               | 143       | 8.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 113       | 7.08%   |
| Realtek Bluetooth Radio                                                             | 104       | 6.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 87        | 5.45%   |
| Intel Bluetooth Device                                                              | 49        | 3.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 45        | 2.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 42        | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 38        | 2.38%   |
| Intel AX210 Bluetooth                                                               | 38        | 2.38%   |
| Apple Bluetooth Host Controller                                                     | 34        | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 30        | 1.88%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 23        | 1.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 22        | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 20        | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 19        | 1.19%   |
| IMC Networks Bluetooth Radio                                                        | 19        | 1.19%   |
| IMC Networks Wireless_Device                                                        | 17        | 1.06%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 1%      |
| MediaTek Wireless_Device                                                            | 15        | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 12        | 0.75%   |
| Lite-On Bluetooth Device                                                            | 12        | 0.75%   |
| Realtek Bluetooth Radio                                                             | 11        | 0.69%   |
| Lite-On Wireless_Device                                                             | 11        | 0.69%   |
| IMC Networks Bluetooth Device                                                       | 11        | 0.69%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 9         | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 9         | 0.56%   |
| ASUS ASUS USB-BT500                                                                 | 9         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 8         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 7         | 0.44%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.38%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 0.31%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 0.31%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.31%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1555      | 44.93%  |
| AMD                                          | 894       | 25.83%  |
| Nvidia                                       | 537       | 15.52%  |
| C-Media Electronics                          | 63        | 1.82%   |
| Logitech                                     | 34        | 0.98%   |
| Creative Labs                                | 29        | 0.84%   |
| Texas Instruments                            | 26        | 0.75%   |
| Realtek Semiconductor                        | 15        | 0.43%   |
| Razer USA                                    | 15        | 0.43%   |
| JMTek                                        | 15        | 0.43%   |
| Lenovo                                       | 14        | 0.4%    |
| ASUSTek Computer                             | 14        | 0.4%    |
| Creative Technology                          | 13        | 0.38%   |
| Kingston Technology                          | 12        | 0.35%   |
| GN Netcom                                    | 12        | 0.35%   |
| Generalplus Technology                       | 12        | 0.35%   |
| Plantronics                                  | 9         | 0.26%   |
| BEHRINGER International                      | 9         | 0.26%   |
| SteelSeries ApS                              | 8         | 0.23%   |
| RODE Microphones                             | 8         | 0.23%   |
| M-Audio                                      | 8         | 0.23%   |
| Sennheiser Communications                    | 7         | 0.2%    |
| Corsair                                      | 7         | 0.2%    |
| Yamaha                                       | 6         | 0.17%   |
| Micro Star International                     | 6         | 0.17%   |
| Focusrite-Novation                           | 6         | 0.17%   |
| VIA Technologies                             | 5         | 0.14%   |
| Hewlett-Packard                              | 5         | 0.14%   |
| FiiO Electronics Technology                  | 5         | 0.14%   |
| Samson Technologies                          | 4         | 0.12%   |
| Apple                                        | 4         | 0.12%   |
| SAVITECH                                     | 3         | 0.09%   |
| ONN                                          | 3         | 0.09%   |
| DSEA A/S                                     | 3         | 0.09%   |
| Dell                                         | 3         | 0.09%   |
| Conexant Systems                             | 3         | 0.09%   |
| Blue Microphones                             | 3         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.06%   |
| ZOOM                                         | 2         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 327       | 7.66%   |
| Intel Sunrise Point-LP HD Audio                                            | 191       | 4.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 178       | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 146       | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 132       | 3.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 132       | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 117       | 2.74%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 104       | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 95        | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 94        | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 93        | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 92        | 2.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 90        | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 78        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 76        | 1.78%   |
| AMD FCH Azalia Controller                                                  | 63        | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 58        | 1.36%   |
| Intel 8 Series HD Audio Controller                                         | 54        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 53        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 49        | 1.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 47        | 1.1%    |
| Intel 200 Series PCH HD Audio                                              | 42        | 0.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 41        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 40        | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 40        | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 40        | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 39        | 0.91%   |
| AMD Navi 10 HDMI Audio                                                     | 37        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 35        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 35        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 34        | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 34        | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 34        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 33        | 0.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 33        | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 32        | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 32        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 31        | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                              | 30        | 0.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 30        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 371       | 21.41%  |
| SK hynix                                | 293       | 16.91%  |
| Kingston                                | 205       | 11.83%  |
| Micron Technology                       | 184       | 10.62%  |
| Unknown                                 | 124       | 7.16%   |
| Crucial                                 | 118       | 6.81%   |
| Corsair                                 | 117       | 6.75%   |
| G.Skill                                 | 95        | 5.48%   |
| A-DATA Technology                       | 25        | 1.44%   |
| Ramaxel Technology                      | 22        | 1.27%   |
| Elpida                                  | 19        | 1.1%    |
| Patriot                                 | 17        | 0.98%   |
| Unknown (ABCD)                          | 16        | 0.92%   |
| Team                                    | 16        | 0.92%   |
| Smart                                   | 12        | 0.69%   |
| Nanya Technology                        | 12        | 0.69%   |
| Unknown                                 | 11        | 0.63%   |
| GOODRAM                                 | 8         | 0.46%   |
| Avant                                   | 8         | 0.46%   |
| Transcend                               | 7         | 0.4%    |
| AMD                                     | 4         | 0.23%   |
| Qimonda                                 | 3         | 0.17%   |
| PNY                                     | 3         | 0.17%   |
| Lexar                                   | 3         | 0.17%   |
| Teikon                                  | 2         | 0.12%   |
| Silicon Power Computer & Communications | 2         | 0.12%   |
| Kingmax                                 | 2         | 0.12%   |
| Exceleram                               | 2         | 0.12%   |
| ChangXin Memory                         | 2         | 0.12%   |
| ASint Technology                        | 2         | 0.12%   |
| Apacer                                  | 2         | 0.12%   |
| Unknown (0x02BA)                        | 1         | 0.06%   |
| Unknown (07FB)                          | 1         | 0.06%   |
| Unknown (000004B30000)                  | 1         | 0.06%   |
| Unifosa                                 | 1         | 0.06%   |
| Toshiba                                 | 1         | 0.06%   |
| Timetec                                 | 1         | 0.06%   |
| TakeMS                                  | 1         | 0.06%   |
| Super Talent                            | 1         | 0.06%   |
| Smart Modular                           | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 17        | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.76%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 11        | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.6%    |
| Unknown                                                          | 11        | 0.6%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.54%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.54%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 10        | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 9         | 0.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 9         | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.43%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 8         | 0.43%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 8         | 0.43%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 8         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 7         | 0.38%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.38%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.38%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.38%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 7         | 0.38%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 7         | 0.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 6         | 0.33%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.33%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 6         | 0.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 785       | 53.22%  |
| DDR3    | 429       | 29.08%  |
| LPDDR4  | 59        | 4%      |
| DDR2    | 46        | 3.12%   |
| Unknown | 40        | 2.71%   |
| LPDDR3  | 34        | 2.31%   |
| DDR5    | 32        | 2.17%   |
| SDRAM   | 23        | 1.56%   |
| LPDDR5  | 15        | 1.02%   |
| DDR     | 8         | 0.54%   |
| DRAM    | 4         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 808       | 54.34%  |
| DIMM         | 552       | 37.12%  |
| Row Of Chips | 108       | 7.26%   |
| Chip         | 14        | 0.94%   |
| RIMM         | 2         | 0.13%   |
| FB-DIMM      | 2         | 0.13%   |
| Unknown      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 682       | 41.84%  |
| 4096  | 399       | 24.48%  |
| 16384 | 289       | 17.73%  |
| 2048  | 139       | 8.53%   |
| 32768 | 79        | 4.85%   |
| 1024  | 38        | 2.33%   |
| 512   | 2         | 0.12%   |
| 49152 | 1         | 0.06%   |
| 128   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 284       | 17.56%  |
| 3200    | 283       | 17.5%   |
| 2667    | 240       | 14.84%  |
| 2400    | 118       | 7.3%    |
| 1333    | 107       | 6.62%   |
| 2133    | 93        | 5.75%   |
| 3600    | 49        | 3.03%   |
| 1334    | 43        | 2.66%   |
| 1867    | 29        | 1.79%   |
| 800     | 27        | 1.67%   |
| 4800    | 26        | 1.61%   |
| 667     | 23        | 1.42%   |
| 4267    | 22        | 1.36%   |
| 3266    | 18        | 1.11%   |
| 6400    | 16        | 0.99%   |
| 3400    | 16        | 0.99%   |
| 2933    | 14        | 0.87%   |
| 1067    | 13        | 0.8%    |
| Unknown | 13        | 0.8%    |
| 2666    | 12        | 0.74%   |
| 1066    | 12        | 0.74%   |
| 3800    | 11        | 0.68%   |
| 4266    | 10        | 0.62%   |
| 3733    | 10        | 0.62%   |
| 3000    | 10        | 0.62%   |
| 3533    | 9         | 0.56%   |
| 1866    | 9         | 0.56%   |
| 2048    | 8         | 0.49%   |
| 8400    | 7         | 0.43%   |
| 3666    | 6         | 0.37%   |
| 2800    | 6         | 0.37%   |
| 1800    | 6         | 0.37%   |
| 975     | 6         | 0.37%   |
| 533     | 6         | 0.37%   |
| 3866    | 5         | 0.31%   |
| 5600    | 4         | 0.25%   |
| 4199    | 4         | 0.25%   |
| 3933    | 4         | 0.25%   |
| 3466    | 4         | 0.25%   |
| 333     | 3         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 33        | 41.25%  |
| Seiko Epson         | 12        | 15%     |
| Brother Industries  | 11        | 13.75%  |
| Samsung Electronics | 10        | 12.5%   |
| Canon               | 7         | 8.75%   |
| Prolific Technology | 2         | 2.5%    |
| Pantum              | 2         | 2.5%    |
| Xerox               | 1         | 1.25%   |
| Star Micronics      | 1         | 1.25%   |
| Kyocera             | 1         | 1.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                      | 2         | 2.41%   |
| Samsung M267x 287x Series                       | 2         | 2.41%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 2.41%   |
| Prolific PL2305 Parallel Port                   | 2         | 2.41%   |
| HP Officejet 4500 G510g-m                       | 2         | 2.41%   |
| HP LaserJet 1320                                | 2         | 2.41%   |
| HP LaserJet 1018                                | 2         | 2.41%   |
| HP ENVY 4520 series                             | 2         | 2.41%   |
| HP Color LaserJet CP1215                        | 2         | 2.41%   |
| Canon LiDE 400                                  | 2         | 2.41%   |
| Brother Printer                                 | 2         | 2.41%   |
| Xerox WorkCentre 3220                           | 1         | 1.2%    |
| Star Micronics TSP100ECO/TSP100II               | 1         | 1.2%    |
| Seiko Epson XP-4200 Series                      | 1         | 1.2%    |
| Seiko Epson XP-4100 Series                      | 1         | 1.2%    |
| Seiko Epson XP-240 Series                       | 1         | 1.2%    |
| Seiko Epson XP-235 Series                       | 1         | 1.2%    |
| Seiko Epson WF-4830 Series                      | 1         | 1.2%    |
| Seiko Epson WF-2510 Series                      | 1         | 1.2%    |
| Seiko Epson L300 Series                         | 1         | 1.2%    |
| Seiko Epson L1300 Series                        | 1         | 1.2%    |
| Seiko Epson ET-3840 Series                      | 1         | 1.2%    |
| Seiko Epson ET-2820 Series                      | 1         | 1.2%    |
| Seiko Epson ET-2720 Series                      | 1         | 1.2%    |
| Samsung SCX-4200 series                         | 1         | 1.2%    |
| Samsung SCX-3400 Series                         | 1         | 1.2%    |
| Samsung Phaser 3121                             | 1         | 1.2%    |
| Samsung ML-191x/ML-252x Laser Printer           | 1         | 1.2%    |
| Samsung ML-1865                                 | 1         | 1.2%    |
| Samsung M2020 Series                            | 1         | 1.2%    |
| Pantum P2500W-series                            | 1         | 1.2%    |
| Pantum P2200-series                             | 1         | 1.2%    |
| Kyocera FS-1030D printer                        | 1         | 1.2%    |
| HP Smart Tank Plus 550 series                   | 1         | 1.2%    |
| HP Smart Install                                | 1         | 1.2%    |
| HP Officejet Pro 6230                           | 1         | 1.2%    |
| HP Officejet J4680                              | 1         | 1.2%    |
| HP Officejet 7110 series                        | 1         | 1.2%    |
| HP OfficeJet 5200 series                        | 1         | 1.2%    |
| HP Officejet 4620 series                        | 1         | 1.2%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 45.83%  |
| Seiko Epson     | 7         | 29.17%  |
| Hewlett-Packard | 3         | 12.5%   |
| AGFA-Gevaert NV | 2         | 8.33%   |
| Mustek Systems  | 1         | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                       | 5         | 20.83%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 2         | 8.33%   |
| Canon CanoScan LiDE 110                                       | 2         | 8.33%   |
| Seiko Epson Scanner                                           | 1         | 4.17%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]              | 1         | 4.17%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 4.17%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 4.17%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]           | 1         | 4.17%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 4.17%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                 | 1         | 4.17%   |
| Mustek Systems ScanExpress A3 USB                             | 1         | 4.17%   |
| HP Scanjet G2710                                              | 1         | 4.17%   |
| HP ScanJet 5300c/5370c                                        | 1         | 4.17%   |
| HP ScanJet 3970c                                              | 1         | 4.17%   |
| Canon CanoScan N1240U/LiDE 30                                 | 1         | 4.17%   |
| Canon CanoScan LiDE 220                                       | 1         | 4.17%   |
| AGFA-Gevaert NV SnapScan e20                                  | 1         | 4.17%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1         | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 323       | 22.18%  |
| IMC Networks                           | 143       | 9.82%   |
| Microdia                               | 126       | 8.65%   |
| Logitech                               | 115       | 7.9%    |
| Realtek Semiconductor                  | 105       | 7.21%   |
| Quanta                                 | 82        | 5.63%   |
| Bison Electronics                      | 76        | 5.22%   |
| Sunplus Innovation Technology          | 75        | 5.15%   |
| Apple                                  | 47        | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 43        | 2.95%   |
| Luxvisions Innotech Limited            | 38        | 2.61%   |
| Syntek                                 | 36        | 2.47%   |
| Lite-On Technology                     | 31        | 2.13%   |
| Acer                                   | 31        | 2.13%   |
| Suyin                                  | 27        | 1.85%   |
| Microsoft                              | 14        | 0.96%   |
| Silicon Motion                         | 12        | 0.82%   |
| Alcor Micro                            | 10        | 0.69%   |
| Sonix Technology                       | 9         | 0.62%   |
| Lenovo                                 | 9         | 0.62%   |
| Generalplus Technology                 | 8         | 0.55%   |
| Samsung Electronics                    | 6         | 0.41%   |
| Z-Star Microelectronics                | 5         | 0.34%   |
| Trust                                  | 4         | 0.27%   |
| Ricoh                                  | 4         | 0.27%   |
| Primax Electronics                     | 4         | 0.27%   |
| Creative Technology                    | 4         | 0.27%   |
| ARC International                      | 4         | 0.27%   |
| SunplusIT                              | 3         | 0.21%   |
| Hewlett-Packard                        | 3         | 0.21%   |
| HD 2MP WEBCAM                          | 3         | 0.21%   |
| Y Media                                | 2         | 0.14%   |
| Tobii Technology AB                    | 2         | 0.14%   |
| OmniVision Technologies                | 2         | 0.14%   |
| LG Electronics                         | 2         | 0.14%   |
| Intel                                  | 2         | 0.14%   |
| Importek                               | 2         | 0.14%   |
| DLTDC0A9II090N                         | 2         | 0.14%   |
| Cubeternet                             | 2         | 0.14%   |
| Arkmicro Technologies                  | 2         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 78        | 5.31%   |
| IMC Networks Integrated Camera                       | 56        | 3.81%   |
| Microdia Integrated_Webcam_HD                        | 51        | 3.47%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 41        | 2.79%   |
| Realtek Integrated_Webcam_HD                         | 40        | 2.72%   |
| Chicony HD WebCam                                    | 36        | 2.45%   |
| Logitech Webcam C270                                 | 32        | 2.18%   |
| Syntek Integrated Camera                             | 24        | 1.63%   |
| Sunplus Integrated_Webcam_HD                         | 22        | 1.5%    |
| Chicony HP HD Camera                                 | 20        | 1.36%   |
| Bison Integrated Camera                              | 17        | 1.16%   |
| Acer Integrated Camera                               | 17        | 1.16%   |
| Apple Built-in iSight                                | 15        | 1.02%   |
| Quanta HD User Facing                                | 13        | 0.89%   |
| Logitech HD Pro Webcam C920                          | 13        | 0.89%   |
| Chicony Integrated Camera (1280x720@30)              | 13        | 0.89%   |
| Apple FaceTime HD Camera                             | 13        | 0.89%   |
| Quanta HP HD Camera                                  | 12        | 0.82%   |
| Microdia USB 2.0 Camera                              | 12        | 0.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 12        | 0.82%   |
| Bison HD Webcam                                      | 12        | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 12        | 0.82%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 11        | 0.75%   |
| Lite-On Integrated Camera                            | 11        | 0.75%   |
| Chicony USB2.0 Camera                                | 11        | 0.75%   |
| Realtek Integrated Webcam HD                         | 10        | 0.68%   |
| Chicony HP HD Webcam                                 | 10        | 0.68%   |
| Chicony HD User Facing                               | 10        | 0.68%   |
| Sunplus HD WebCam                                    | 9         | 0.61%   |
| Quanta VGA WebCam                                    | 9         | 0.61%   |
| Quanta HP TrueVision HD Camera                       | 9         | 0.61%   |
| Microdia Integrated Webcam                           | 9         | 0.61%   |
| Realtek USB Camera                                   | 8         | 0.54%   |
| Microdia Webcam Vitade AF                            | 8         | 0.54%   |
| Luxvisions Innotech Limited HP HD Camera             | 8         | 0.54%   |
| Logitech HD Webcam C615                              | 8         | 0.54%   |
| Chicony FJ Camera                                    | 8         | 0.54%   |
| Luxvisions Innotech Limited Integrated Camera        | 7         | 0.48%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 7         | 0.48%   |
| Logitech C922 Pro Stream Webcam                      | 7         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 106       | 36.05%  |
| Validity Sensors           | 103       | 35.03%  |
| Shenzhen Goodix Technology | 42        | 14.29%  |
| Upek                       | 13        | 4.42%   |
| AuthenTec                  | 12        | 4.08%   |
| Elan Microelectronics      | 11        | 3.74%   |
| LighTuning Technology      | 3         | 1.02%   |
| STMicroelectronics         | 1         | 0.34%   |
| Samsung Electronics        | 1         | 0.34%   |
| Focal-systems.Corp         | 1         | 0.34%   |
| DigitalPersona             | 1         | 0.34%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 33        | 11.22%  |
| Shenzhen Goodix  Fingerprint Device                                        | 28        | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 8.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 5.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 4.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 4.08%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 4.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 4.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.4%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 2.72%   |
| Synaptics WBDI                                                             | 8         | 2.72%   |
| Synaptics UWP WBDI                                                         | 8         | 2.72%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 2.38%   |
| Elan ELAN:ARM-M4                                                           | 7         | 2.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.7%    |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.7%    |
| Validity Sensors VFS491                                                    | 4         | 1.36%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.36%   |
| Synaptics  WBDI                                                            | 4         | 1.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.36%   |
| Synaptics WBDI Device                                                      | 3         | 1.02%   |
| AuthenTec AES2810                                                          | 3         | 1.02%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.02%   |
| Unknown                                                                    | 3         | 1.02%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.68%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.68%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.68%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.68%   |
| Elan ELAN:Fingerprint                                                      | 2         | 0.68%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.68%   |
| AuthenTec AES1600                                                          | 2         | 0.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.34%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.34%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 48        | 40.34%  |
| Broadcom                   | 46        | 38.66%  |
| Gemalto (was Gemplus)      | 6         | 5.04%   |
| Upek                       | 5         | 4.2%    |
| O2 Micro                   | 3         | 2.52%   |
| Hewlett-Packard            | 3         | 2.52%   |
| Lenovo                     | 2         | 1.68%   |
| Yubico.com                 | 1         | 0.84%   |
| Watchdata                  | 1         | 0.84%   |
| SCM Microsystems           | 1         | 0.84%   |
| Clay Logic                 | 1         | 0.84%   |
| Castles Technology         | 1         | 0.84%   |
| Athena Smartcard Solutions | 1         | 0.84%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 46        | 38.66%  |
| Broadcom 5880                                                                | 16        | 13.45%  |
| Broadcom 58200                                                               | 16        | 13.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 6.72%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.2%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 4.2%    |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 4.2%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.52%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 3         | 2.52%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 1.68%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.84%   |
| Watchdata USB Key                                                            | 1         | 0.84%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.84%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.84%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.84%   |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 0.84%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.84%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.84%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.84%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.84%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1730      | 69.06%  |
| 1     | 618       | 24.67%  |
| 2     | 132       | 5.27%   |
| 3     | 20        | 0.8%    |
| 4     | 4         | 0.16%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 292       | 31.98%  |
| Graphics card            | 194       | 21.25%  |
| Chipcard                 | 109       | 11.94%  |
| Net/wireless             | 95        | 10.41%  |
| Multimedia controller    | 60        | 6.57%   |
| Sound                    | 35        | 3.83%   |
| Camera                   | 26        | 2.85%   |
| Unassigned class         | 25        | 2.74%   |
| Communication controller | 21        | 2.3%    |
| Card reader              | 15        | 1.64%   |
| Bluetooth                | 15        | 1.64%   |
| Storage                  | 9         | 0.99%   |
| Network                  | 5         | 0.55%   |
| Net/ethernet             | 4         | 0.44%   |
| Firewire controller      | 4         | 0.44%   |
| Modem                    | 2         | 0.22%   |
| Storage/raid             | 1         | 0.11%   |
| Flash memory             | 1         | 0.11%   |

