Linux in Norway - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Norway/Desktop/README.md) and [notebooks](/Location/Norway/Notebook/README.md).

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

Total: 1959

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | X99A RAIDER                 | Desktop     | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | Notebook    | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [a5e7296c29](https://linux-hardware.org/?probe=a5e7296c29) | Sep 28, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [ab332c2dcb](https://linux-hardware.org/?probe=ab332c2dcb) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [45c1c156af](https://linux-hardware.org/?probe=45c1c156af) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [908d74fdc8](https://linux-hardware.org/?probe=908d74fdc8) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [987e4c193b](https://linux-hardware.org/?probe=987e4c193b) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [1180346586](https://linux-hardware.org/?probe=1180346586) | Sep 19, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [96a6758726](https://linux-hardware.org/?probe=96a6758726) | Sep 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | Notebook    | [2c90700f4f](https://linux-hardware.org/?probe=2c90700f4f) | Sep 16, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [13e8645c6c](https://linux-hardware.org/?probe=13e8645c6c) | Sep 16, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [183adfb8b6](https://linux-hardware.org/?probe=183adfb8b6) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [de94d54f00](https://linux-hardware.org/?probe=de94d54f00) | Sep 15, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [d1ef9fa580](https://linux-hardware.org/?probe=d1ef9fa580) | Sep 15, 2023 |
| Lenovo        | ThinkPad E14 20RA005MMX     | Notebook    | [d9d0c012b3](https://linux-hardware.org/?probe=d9d0c012b3) | Sep 13, 2023 |
| Lenovo        | ThinkPad X260 20F5S7QT00    | Notebook    | [8475dc74df](https://linux-hardware.org/?probe=8475dc74df) | Sep 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [83b997b3ab](https://linux-hardware.org/?probe=83b997b3ab) | Sep 09, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c936953cf7](https://linux-hardware.org/?probe=c936953cf7) | Sep 08, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [f4ddf6b6ec](https://linux-hardware.org/?probe=f4ddf6b6ec) | Sep 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [362b2dadfc](https://linux-hardware.org/?probe=362b2dadfc) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7a0e6bd16c](https://linux-hardware.org/?probe=7a0e6bd16c) | Sep 07, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [bedbf331b0](https://linux-hardware.org/?probe=bedbf331b0) | Sep 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [0434d08b59](https://linux-hardware.org/?probe=0434d08b59) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [96d3b5db5c](https://linux-hardware.org/?probe=96d3b5db5c) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8c22ca23f2](https://linux-hardware.org/?probe=8c22ca23f2) | Sep 07, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [7e7c32364d](https://linux-hardware.org/?probe=7e7c32364d) | Sep 06, 2023 |
| Panasonic     | CF-191HACHFN                | Notebook    | [2c3ca0bdcf](https://linux-hardware.org/?probe=2c3ca0bdcf) | Sep 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c06fdd0648](https://linux-hardware.org/?probe=c06fdd0648) | Sep 05, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [59b20fdfab](https://linux-hardware.org/?probe=59b20fdfab) | Sep 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [6bf9db20f8](https://linux-hardware.org/?probe=6bf9db20f8) | Sep 04, 2023 |
| Star Labs     | StarBook                    | Notebook    | [ac568bfcd4](https://linux-hardware.org/?probe=ac568bfcd4) | Sep 03, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [499d13e212](https://linux-hardware.org/?probe=499d13e212) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9607f36921](https://linux-hardware.org/?probe=9607f36921) | Sep 03, 2023 |
| Dell          | Latitude 3540               | Notebook    | [e7d1d4f160](https://linux-hardware.org/?probe=e7d1d4f160) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [72c5c271b6](https://linux-hardware.org/?probe=72c5c271b6) | Sep 03, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [19e076e3e1](https://linux-hardware.org/?probe=19e076e3e1) | Sep 01, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [ef4c22cc94](https://linux-hardware.org/?probe=ef4c22cc94) | Sep 01, 2023 |
| Google        | Galtic                      | Notebook    | [e9ccd3a286](https://linux-hardware.org/?probe=e9ccd3a286) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [7f9db7db99](https://linux-hardware.org/?probe=7f9db7db99) | Sep 01, 2023 |
| MSI           | X299 SLI PLUS               | Desktop     | [572982299a](https://linux-hardware.org/?probe=572982299a) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [44e98cb157](https://linux-hardware.org/?probe=44e98cb157) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [771adfa310](https://linux-hardware.org/?probe=771adfa310) | Aug 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [68c01672c3](https://linux-hardware.org/?probe=68c01672c3) | Aug 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [5a388c766a](https://linux-hardware.org/?probe=5a388c766a) | Aug 23, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [10345216a9](https://linux-hardware.org/?probe=10345216a9) | Aug 22, 2023 |
| Dell          | Precision M4700             | Notebook    | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| eMachines     | E520 V1.06                  | Notebook    | [bd63874856](https://linux-hardware.org/?probe=bd63874856) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | Notebook    | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | Notebook    | [10b7d76c38](https://linux-hardware.org/?probe=10b7d76c38) | Aug 20, 2023 |
| Lenovo        | V320-17ISK 81B6             | Notebook    | [cc96bcc8d9](https://linux-hardware.org/?probe=cc96bcc8d9) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [41b00dc8b3](https://linux-hardware.org/?probe=41b00dc8b3) | Aug 18, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [e0a9b4c86f](https://linux-hardware.org/?probe=e0a9b4c86f) | Aug 18, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b80142953c](https://linux-hardware.org/?probe=b80142953c) | Aug 17, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [1ba4da3bec](https://linux-hardware.org/?probe=1ba4da3bec) | Aug 17, 2023 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [6ed8f5fce9](https://linux-hardware.org/?probe=6ed8f5fce9) | Aug 16, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [b2377a274f](https://linux-hardware.org/?probe=b2377a274f) | Aug 16, 2023 |
| Intel         | X99                         | Desktop     | [64c64eec64](https://linux-hardware.org/?probe=64c64eec64) | Aug 16, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [2412623eac](https://linux-hardware.org/?probe=2412623eac) | Aug 15, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [48ae062db8](https://linux-hardware.org/?probe=48ae062db8) | Aug 15, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [88056b62e3](https://linux-hardware.org/?probe=88056b62e3) | Aug 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0c0df32662](https://linux-hardware.org/?probe=0c0df32662) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| ASUSTek       | ROG STRIX Z590-I GAMING ... | Desktop     | [8903899ce9](https://linux-hardware.org/?probe=8903899ce9) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [cec1060cd6](https://linux-hardware.org/?probe=cec1060cd6) | Aug 10, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [01dc3bfc4b](https://linux-hardware.org/?probe=01dc3bfc4b) | Aug 09, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [33beb40ea6](https://linux-hardware.org/?probe=33beb40ea6) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [9f230de889](https://linux-hardware.org/?probe=9f230de889) | Aug 07, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [24dc4f34a2](https://linux-hardware.org/?probe=24dc4f34a2) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f7354ee466](https://linux-hardware.org/?probe=f7354ee466) | Aug 04, 2023 |
| HP            | 8620                        | Mini pc     | [3203f90412](https://linux-hardware.org/?probe=3203f90412) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [ab8efe91ea](https://linux-hardware.org/?probe=ab8efe91ea) | Jul 30, 2023 |
| ASUSTek       | UX461UN                     | Convertible | [8f48f3562c](https://linux-hardware.org/?probe=8f48f3562c) | Jul 30, 2023 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [30784ff697](https://linux-hardware.org/?probe=30784ff697) | Jul 30, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [1b0bb754bc](https://linux-hardware.org/?probe=1b0bb754bc) | Jul 28, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [54684f905d](https://linux-hardware.org/?probe=54684f905d) | Jul 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [aac37c9ed6](https://linux-hardware.org/?probe=aac37c9ed6) | Jul 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f3cc428da8](https://linux-hardware.org/?probe=f3cc428da8) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6c03bf1d0d](https://linux-hardware.org/?probe=6c03bf1d0d) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [405387be09](https://linux-hardware.org/?probe=405387be09) | Jul 23, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [62efe51727](https://linux-hardware.org/?probe=62efe51727) | Jul 23, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ecce500445](https://linux-hardware.org/?probe=ecce500445) | Jul 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [f4e52f14b5](https://linux-hardware.org/?probe=f4e52f14b5) | Jul 22, 2023 |
| MSI           | GL72 6QF                    | Notebook    | [0484bc209c](https://linux-hardware.org/?probe=0484bc209c) | Jul 21, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [c81d7372fb](https://linux-hardware.org/?probe=c81d7372fb) | Jul 21, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [a05f11a6b4](https://linux-hardware.org/?probe=a05f11a6b4) | Jul 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [2e18524ef0](https://linux-hardware.org/?probe=2e18524ef0) | Jul 20, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [e0303e4012](https://linux-hardware.org/?probe=e0303e4012) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [abf1be3307](https://linux-hardware.org/?probe=abf1be3307) | Jul 16, 2023 |
| Supermicro    | X9DRT                       | Server      | [b95f28343e](https://linux-hardware.org/?probe=b95f28343e) | Jul 14, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [e7898eacb6](https://linux-hardware.org/?probe=e7898eacb6) | Jul 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e241cdbe45](https://linux-hardware.org/?probe=e241cdbe45) | Jul 12, 2023 |
| Lenovo        | ThinkPad 8 20BN001RMN       | Tablet      | [6801265f9f](https://linux-hardware.org/?probe=6801265f9f) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f99bab3454](https://linux-hardware.org/?probe=f99bab3454) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [333813fa10](https://linux-hardware.org/?probe=333813fa10) | Jul 11, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [66fb93438f](https://linux-hardware.org/?probe=66fb93438f) | Jul 11, 2023 |
| Dell          | Precision 5680              | Notebook    | [e1363522ee](https://linux-hardware.org/?probe=e1363522ee) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [0fbc8ca097](https://linux-hardware.org/?probe=0fbc8ca097) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fddbab0cf6](https://linux-hardware.org/?probe=fddbab0cf6) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [d47bb47c61](https://linux-hardware.org/?probe=d47bb47c61) | Jul 10, 2023 |
| MSI           | GL72 6QF                    | Notebook    | [487fd6cc0e](https://linux-hardware.org/?probe=487fd6cc0e) | Jul 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [30658f7ab7](https://linux-hardware.org/?probe=30658f7ab7) | Jul 09, 2023 |
| Acer          | Swift SF514-51              | Notebook    | [74c43ecd5c](https://linux-hardware.org/?probe=74c43ecd5c) | Jul 08, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [220629a068](https://linux-hardware.org/?probe=220629a068) | Jul 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f86f946540](https://linux-hardware.org/?probe=f86f946540) | Jul 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | Notebook    | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Dell          | Latitude 7480               | Notebook    | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [2fa3986e67](https://linux-hardware.org/?probe=2fa3986e67) | Jul 05, 2023 |
| ASUSTek       | X556UR                      | Notebook    | [79d8c96e3c](https://linux-hardware.org/?probe=79d8c96e3c) | Jul 05, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [155825a56a](https://linux-hardware.org/?probe=155825a56a) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [205dfa0056](https://linux-hardware.org/?probe=205dfa0056) | Jul 03, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [40ca2e97cc](https://linux-hardware.org/?probe=40ca2e97cc) | Jul 03, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [6b9216eef4](https://linux-hardware.org/?probe=6b9216eef4) | Jul 02, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [8f6145f929](https://linux-hardware.org/?probe=8f6145f929) | Jul 02, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [dba19e3fa3](https://linux-hardware.org/?probe=dba19e3fa3) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [556867d0f2](https://linux-hardware.org/?probe=556867d0f2) | Jul 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [b36612c9e4](https://linux-hardware.org/?probe=b36612c9e4) | Jul 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c2b529a2ee](https://linux-hardware.org/?probe=c2b529a2ee) | Jul 02, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ef05796af7](https://linux-hardware.org/?probe=ef05796af7) | Jul 01, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ea8982e574](https://linux-hardware.org/?probe=ea8982e574) | Jul 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d7efa66a54](https://linux-hardware.org/?probe=d7efa66a54) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| MSI           | Katana GF66 11UG            | Notebook    | [e9f98cc102](https://linux-hardware.org/?probe=e9f98cc102) | Jun 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bb8a8eac46](https://linux-hardware.org/?probe=bb8a8eac46) | Jun 30, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [c44fba1fa2](https://linux-hardware.org/?probe=c44fba1fa2) | Jun 29, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [fee1e04033](https://linux-hardware.org/?probe=fee1e04033) | Jun 28, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [0294ef5e1f](https://linux-hardware.org/?probe=0294ef5e1f) | Jun 28, 2023 |
| Supermicro    | X9DRT                       | Server      | [807e745cb1](https://linux-hardware.org/?probe=807e745cb1) | Jun 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [31fc00f1ac](https://linux-hardware.org/?probe=31fc00f1ac) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [684000f2c5](https://linux-hardware.org/?probe=684000f2c5) | Jun 25, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [6cb0af7fea](https://linux-hardware.org/?probe=6cb0af7fea) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [7ce8bcbc26](https://linux-hardware.org/?probe=7ce8bcbc26) | Jun 23, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fed92425f3](https://linux-hardware.org/?probe=fed92425f3) | Jun 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [8d35565fd3](https://linux-hardware.org/?probe=8d35565fd3) | Jun 20, 2023 |
| Supermicro    | X9DRT                       | Server      | [5b25db1cae](https://linux-hardware.org/?probe=5b25db1cae) | Jun 20, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | Notebook    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [058b2ea405](https://linux-hardware.org/?probe=058b2ea405) | Jun 20, 2023 |
| MSI           | X299 TOMAHAWK               | Desktop     | [aa2a65c324](https://linux-hardware.org/?probe=aa2a65c324) | Jun 19, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [00e6086d35](https://linux-hardware.org/?probe=00e6086d35) | Jun 19, 2023 |
| Supermicro    | X9DRT                       | Server      | [7efb88b5d7](https://linux-hardware.org/?probe=7efb88b5d7) | Jun 19, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [50d54b5967](https://linux-hardware.org/?probe=50d54b5967) | Jun 18, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [3dc796f9d3](https://linux-hardware.org/?probe=3dc796f9d3) | Jun 18, 2023 |
| Multicom N... | Multicom Talisa U235        | Tablet      | [cb5806fefc](https://linux-hardware.org/?probe=cb5806fefc) | Jun 18, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [b61d1afa3c](https://linux-hardware.org/?probe=b61d1afa3c) | Jun 17, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [1bb6017aaa](https://linux-hardware.org/?probe=1bb6017aaa) | Jun 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87cd6547ad](https://linux-hardware.org/?probe=87cd6547ad) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4fac659113](https://linux-hardware.org/?probe=4fac659113) | Jun 13, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [785b0849fd](https://linux-hardware.org/?probe=785b0849fd) | Jun 13, 2023 |
| MSI           | P67A-C45                    | Desktop     | [4f3aa2017f](https://linux-hardware.org/?probe=4f3aa2017f) | Jun 13, 2023 |
| Lenovo        | G565 4385                   | Notebook    | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| ASUSTek       | GX501VIK                    | Notebook    | [e54a895262](https://linux-hardware.org/?probe=e54a895262) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1fd265b6d8](https://linux-hardware.org/?probe=1fd265b6d8) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1c5e1b092a](https://linux-hardware.org/?probe=1c5e1b092a) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [4ab556e4b8](https://linux-hardware.org/?probe=4ab556e4b8) | Jun 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [212c44c43f](https://linux-hardware.org/?probe=212c44c43f) | Jun 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| MSI           | P67A-C45                    | Desktop     | [673f3774bc](https://linux-hardware.org/?probe=673f3774bc) | Jun 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d70fe31101](https://linux-hardware.org/?probe=d70fe31101) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3c3708dcec](https://linux-hardware.org/?probe=3c3708dcec) | Jun 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [0763f751ac](https://linux-hardware.org/?probe=0763f751ac) | Jun 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [79b80daf83](https://linux-hardware.org/?probe=79b80daf83) | Jun 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [36173d5a42](https://linux-hardware.org/?probe=36173d5a42) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a39c2e8d55](https://linux-hardware.org/?probe=a39c2e8d55) | Jun 04, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [d09ba05086](https://linux-hardware.org/?probe=d09ba05086) | Jun 03, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [9f13a5184c](https://linux-hardware.org/?probe=9f13a5184c) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [58f688ebc5](https://linux-hardware.org/?probe=58f688ebc5) | Jun 02, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [02d5f4b511](https://linux-hardware.org/?probe=02d5f4b511) | Jun 01, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [835a44b010](https://linux-hardware.org/?probe=835a44b010) | Jun 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b951e6223c](https://linux-hardware.org/?probe=b951e6223c) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [df9086deb4](https://linux-hardware.org/?probe=df9086deb4) | Jun 01, 2023 |
| Sony          | SVT1121B2EW                 | Notebook    | [67819a243c](https://linux-hardware.org/?probe=67819a243c) | May 31, 2023 |
| ASUSTek       | ROG Strix G513RS_G513RS     | Notebook    | [69b1782cce](https://linux-hardware.org/?probe=69b1782cce) | May 31, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3404cb6c67](https://linux-hardware.org/?probe=3404cb6c67) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a908da319](https://linux-hardware.org/?probe=4a908da319) | May 31, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b4b6bfda0c](https://linux-hardware.org/?probe=b4b6bfda0c) | May 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8b96413dfd](https://linux-hardware.org/?probe=8b96413dfd) | May 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ffe895debc](https://linux-hardware.org/?probe=ffe895debc) | May 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [0b7f7fb99a](https://linux-hardware.org/?probe=0b7f7fb99a) | May 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [38936854c8](https://linux-hardware.org/?probe=38936854c8) | May 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [f7fddb36e8](https://linux-hardware.org/?probe=f7fddb36e8) | May 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [362ad8bcaf](https://linux-hardware.org/?probe=362ad8bcaf) | May 23, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [cc966f1ede](https://linux-hardware.org/?probe=cc966f1ede) | May 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ec7d8d12e1](https://linux-hardware.org/?probe=ec7d8d12e1) | May 23, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1b7089a58b](https://linux-hardware.org/?probe=1b7089a58b) | May 23, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1fd2d41164](https://linux-hardware.org/?probe=1fd2d41164) | May 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ecc77ee7a9](https://linux-hardware.org/?probe=ecc77ee7a9) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [3f5a6968d4](https://linux-hardware.org/?probe=3f5a6968d4) | May 21, 2023 |
| Dell          | Latitude 7370               | Notebook    | [756455c062](https://linux-hardware.org/?probe=756455c062) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [9b29aafd95](https://linux-hardware.org/?probe=9b29aafd95) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d4344603b6](https://linux-hardware.org/?probe=d4344603b6) | May 15, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [14928b0276](https://linux-hardware.org/?probe=14928b0276) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [36f918cce7](https://linux-hardware.org/?probe=36f918cce7) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [1ba0adc2ba](https://linux-hardware.org/?probe=1ba0adc2ba) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [903ece310a](https://linux-hardware.org/?probe=903ece310a) | May 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2d942e3436](https://linux-hardware.org/?probe=2d942e3436) | May 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6bfe747b4d](https://linux-hardware.org/?probe=6bfe747b4d) | May 13, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [a15b90ff4b](https://linux-hardware.org/?probe=a15b90ff4b) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2e2b57870b](https://linux-hardware.org/?probe=2e2b57870b) | May 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4243b6a57b](https://linux-hardware.org/?probe=4243b6a57b) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | Notebook    | [795e44d159](https://linux-hardware.org/?probe=795e44d159) | May 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [08adc44b64](https://linux-hardware.org/?probe=08adc44b64) | May 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e985d1beac](https://linux-hardware.org/?probe=e985d1beac) | May 12, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [184f099d28](https://linux-hardware.org/?probe=184f099d28) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [727163d7b9](https://linux-hardware.org/?probe=727163d7b9) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [96d3be3118](https://linux-hardware.org/?probe=96d3be3118) | May 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [dfdc7713b6](https://linux-hardware.org/?probe=dfdc7713b6) | May 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e2bbbffe45](https://linux-hardware.org/?probe=e2bbbffe45) | May 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bc30b63ce3](https://linux-hardware.org/?probe=bc30b63ce3) | May 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [53c03d6942](https://linux-hardware.org/?probe=53c03d6942) | May 08, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | Desktop     | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [98008481eb](https://linux-hardware.org/?probe=98008481eb) | May 07, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| MSI           | X299 SLI PLUS               | Desktop     | [db983da641](https://linux-hardware.org/?probe=db983da641) | May 04, 2023 |
| Lenovo        | ThinkPad X230 23252CG       | Notebook    | [00ff147a9a](https://linux-hardware.org/?probe=00ff147a9a) | May 03, 2023 |
| Dell          | Precision 7510              | Notebook    | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| MSI           | MS-7025                     | Desktop     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [513f1e9efb](https://linux-hardware.org/?probe=513f1e9efb) | May 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [51c2405640](https://linux-hardware.org/?probe=51c2405640) | May 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f2c73a1fbb](https://linux-hardware.org/?probe=f2c73a1fbb) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [be8b69e1b4](https://linux-hardware.org/?probe=be8b69e1b4) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c33288abe2](https://linux-hardware.org/?probe=c33288abe2) | Apr 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [606b173cab](https://linux-hardware.org/?probe=606b173cab) | Apr 30, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | Notebook    | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [44b55b4721](https://linux-hardware.org/?probe=44b55b4721) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [853016bfe3](https://linux-hardware.org/?probe=853016bfe3) | Apr 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6bf052a2f](https://linux-hardware.org/?probe=d6bf052a2f) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e14205d01a](https://linux-hardware.org/?probe=e14205d01a) | Apr 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [909ad37ab0](https://linux-hardware.org/?probe=909ad37ab0) | Apr 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [71983d0574](https://linux-hardware.org/?probe=71983d0574) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [1d6082efe8](https://linux-hardware.org/?probe=1d6082efe8) | Apr 25, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [d86639089a](https://linux-hardware.org/?probe=d86639089a) | Apr 25, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a8b5c5c3ad](https://linux-hardware.org/?probe=a8b5c5c3ad) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [620334c0fc](https://linux-hardware.org/?probe=620334c0fc) | Apr 23, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [2aa36b9cfd](https://linux-hardware.org/?probe=2aa36b9cfd) | Apr 22, 2023 |
| Dell          | Latitude 7420               | Notebook    | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| Xunlong       | Orange Pi One               | Soc         | [5542de4f04](https://linux-hardware.org/?probe=5542de4f04) | Apr 19, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [79029817b8](https://linux-hardware.org/?probe=79029817b8) | Apr 17, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Mini 210-1000               | Notebook    | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [0f678c5ded](https://linux-hardware.org/?probe=0f678c5ded) | Apr 15, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ee48e89e45](https://linux-hardware.org/?probe=ee48e89e45) | Apr 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [57cc389eff](https://linux-hardware.org/?probe=57cc389eff) | Apr 14, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [0d0a704eae](https://linux-hardware.org/?probe=0d0a704eae) | Apr 12, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [6d04c51285](https://linux-hardware.org/?probe=6d04c51285) | Apr 11, 2023 |
| MSI           | P67A-C45                    | Desktop     | [25a90d2595](https://linux-hardware.org/?probe=25a90d2595) | Apr 10, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [35d855a901](https://linux-hardware.org/?probe=35d855a901) | Apr 10, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6fe9dfd9a6](https://linux-hardware.org/?probe=6fe9dfd9a6) | Apr 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [332f3ed32f](https://linux-hardware.org/?probe=332f3ed32f) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [d6cbe10f95](https://linux-hardware.org/?probe=d6cbe10f95) | Apr 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3f8d1c6a26](https://linux-hardware.org/?probe=3f8d1c6a26) | Apr 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87f9a72b18](https://linux-hardware.org/?probe=87f9a72b18) | Apr 09, 2023 |
| HP            | 83E9                        | Desktop     | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | Desktop     | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [7f55348e8b](https://linux-hardware.org/?probe=7f55348e8b) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [94df0605ae](https://linux-hardware.org/?probe=94df0605ae) | Apr 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6f7c92fc7](https://linux-hardware.org/?probe=d6f7c92fc7) | Apr 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [50e745e72a](https://linux-hardware.org/?probe=50e745e72a) | Apr 01, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [8bc61e0fcd](https://linux-hardware.org/?probe=8bc61e0fcd) | Mar 31, 2023 |
| ASRock        | Z87 Extreme11/ac            | Desktop     | [283593a105](https://linux-hardware.org/?probe=283593a105) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [0f26b74917](https://linux-hardware.org/?probe=0f26b74917) | Mar 30, 2023 |
| HP            | ProBook 6360b               | Notebook    | [cf027e03de](https://linux-hardware.org/?probe=cf027e03de) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [455ce69724](https://linux-hardware.org/?probe=455ce69724) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [493cabf3f8](https://linux-hardware.org/?probe=493cabf3f8) | Mar 29, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [aebe1aa0af](https://linux-hardware.org/?probe=aebe1aa0af) | Mar 29, 2023 |
| Acer          | Predator G3-605             | Desktop     | [8a1a55a1da](https://linux-hardware.org/?probe=8a1a55a1da) | Mar 29, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [0bc21ff162](https://linux-hardware.org/?probe=0bc21ff162) | Mar 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [df27b06a95](https://linux-hardware.org/?probe=df27b06a95) | Mar 28, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [761f7d71db](https://linux-hardware.org/?probe=761f7d71db) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [0730a39a3a](https://linux-hardware.org/?probe=0730a39a3a) | Mar 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [dd6b3f7e44](https://linux-hardware.org/?probe=dd6b3f7e44) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [d1eea40764](https://linux-hardware.org/?probe=d1eea40764) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [640a9ac505](https://linux-hardware.org/?probe=640a9ac505) | Mar 24, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | Notebook    | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8892fdfdf9](https://linux-hardware.org/?probe=8892fdfdf9) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f842840cc9](https://linux-hardware.org/?probe=f842840cc9) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ac3bb4cdf4](https://linux-hardware.org/?probe=ac3bb4cdf4) | Mar 18, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [c20318c7c0](https://linux-hardware.org/?probe=c20318c7c0) | Mar 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [2d722aa2b5](https://linux-hardware.org/?probe=2d722aa2b5) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c919e2da37](https://linux-hardware.org/?probe=c919e2da37) | Mar 12, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [089cafb799](https://linux-hardware.org/?probe=089cafb799) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| HP            | Presario CQ57               | Notebook    | [87bbd773ac](https://linux-hardware.org/?probe=87bbd773ac) | Mar 09, 2023 |
| HP            | Presario CQ57               | Notebook    | [ffa117dde1](https://linux-hardware.org/?probe=ffa117dde1) | Mar 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [c5c1815bc8](https://linux-hardware.org/?probe=c5c1815bc8) | Mar 08, 2023 |
| MSI           | P67A-C45                    | Desktop     | [52e013338c](https://linux-hardware.org/?probe=52e013338c) | Mar 07, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [c3476001d3](https://linux-hardware.org/?probe=c3476001d3) | Mar 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2246ef48c8](https://linux-hardware.org/?probe=2246ef48c8) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [73a3777352](https://linux-hardware.org/?probe=73a3777352) | Mar 06, 2023 |
| Dell          | Latitude 3510               | Notebook    | [983c57e386](https://linux-hardware.org/?probe=983c57e386) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [46d39caf5c](https://linux-hardware.org/?probe=46d39caf5c) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b20cfbdfa1](https://linux-hardware.org/?probe=b20cfbdfa1) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [2ac4801793](https://linux-hardware.org/?probe=2ac4801793) | Mar 03, 2023 |
| Unknown       | Rev.00                      | Desktop     | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [989eed6d5f](https://linux-hardware.org/?probe=989eed6d5f) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| GMKtec        | NucBox5                     | Notebook    | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ba4afa4d3b](https://linux-hardware.org/?probe=ba4afa4d3b) | Mar 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [7b7df086e0](https://linux-hardware.org/?probe=7b7df086e0) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f27314deb8](https://linux-hardware.org/?probe=f27314deb8) | Feb 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [97192c0aef](https://linux-hardware.org/?probe=97192c0aef) | Feb 26, 2023 |
| HP            | 3397                        | Desktop     | [a1840ee53d](https://linux-hardware.org/?probe=a1840ee53d) | Feb 26, 2023 |
| MSI           | B85M-E45                    | Desktop     | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6c6778bb7](https://linux-hardware.org/?probe=d6c6778bb7) | Feb 25, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7b4981d722](https://linux-hardware.org/?probe=7b4981d722) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [142a12ded0](https://linux-hardware.org/?probe=142a12ded0) | Feb 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [06138e952c](https://linux-hardware.org/?probe=06138e952c) | Feb 22, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [48817e62c6](https://linux-hardware.org/?probe=48817e62c6) | Feb 21, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [31d92eed57](https://linux-hardware.org/?probe=31d92eed57) | Feb 21, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [b5aebe4c92](https://linux-hardware.org/?probe=b5aebe4c92) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5b33608a35](https://linux-hardware.org/?probe=5b33608a35) | Feb 20, 2023 |
| HP            | 0AECh D                     | Desktop     | [e844a614ec](https://linux-hardware.org/?probe=e844a614ec) | Feb 19, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [22fdba9212](https://linux-hardware.org/?probe=22fdba9212) | Feb 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8dabbaa31c](https://linux-hardware.org/?probe=8dabbaa31c) | Feb 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243W83       | Notebook    | [e6abb63f33](https://linux-hardware.org/?probe=e6abb63f33) | Feb 17, 2023 |
| Acer          | Aspire XC-230               | Desktop     | [e01d812902](https://linux-hardware.org/?probe=e01d812902) | Feb 17, 2023 |
| Acer          | Aspire XC-230               | Desktop     | [52b4d00a5a](https://linux-hardware.org/?probe=52b4d00a5a) | Feb 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [991b8b4361](https://linux-hardware.org/?probe=991b8b4361) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [387ec47efe](https://linux-hardware.org/?probe=387ec47efe) | Feb 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [b96dc1b089](https://linux-hardware.org/?probe=b96dc1b089) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [dcb244db8e](https://linux-hardware.org/?probe=dcb244db8e) | Feb 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [30db5b00f4](https://linux-hardware.org/?probe=30db5b00f4) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e9fac81aa1](https://linux-hardware.org/?probe=e9fac81aa1) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0e4bbcc317](https://linux-hardware.org/?probe=0e4bbcc317) | Feb 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| HP            | 3397                        | Desktop     | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a096de92f6](https://linux-hardware.org/?probe=a096de92f6) | Feb 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| Dell          | Latitude E7240              | Notebook    | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c91d5b265b](https://linux-hardware.org/?probe=c91d5b265b) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| Dell          | Precision 5530              | Notebook    | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d8de82d8c4](https://linux-hardware.org/?probe=d8de82d8c4) | Jan 29, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e5abc7fae4](https://linux-hardware.org/?probe=e5abc7fae4) | Jan 28, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [293a308d86](https://linux-hardware.org/?probe=293a308d86) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| HP            | 8597                        | Desktop     | [8cc851783e](https://linux-hardware.org/?probe=8cc851783e) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [a9b7912b52](https://linux-hardware.org/?probe=a9b7912b52) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R500... | Convertible | [7f5181d202](https://linux-hardware.org/?probe=7f5181d202) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| HP            | Notebook                    | Notebook    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [8c4a855d8e](https://linux-hardware.org/?probe=8c4a855d8e) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [0ea26f4af6](https://linux-hardware.org/?probe=0ea26f4af6) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [859d3c1b58](https://linux-hardware.org/?probe=859d3c1b58) | Jan 18, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [5b8deec807](https://linux-hardware.org/?probe=5b8deec807) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [cc16045ed3](https://linux-hardware.org/?probe=cc16045ed3) | Jan 16, 2023 |
| Dell          | Latitude E7240              | Notebook    | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [79eb90321f](https://linux-hardware.org/?probe=79eb90321f) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Latitude 3350               | Notebook    | [d7ca8710c2](https://linux-hardware.org/?probe=d7ca8710c2) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| MSI           | P67A-C45                    | Desktop     | [625a573f22](https://linux-hardware.org/?probe=625a573f22) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| HP            | 8299                        | Desktop     | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| Dell          | Latitude E7240              | Notebook    | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [1dba72668b](https://linux-hardware.org/?probe=1dba72668b) | Jan 10, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [e6d3982bc0](https://linux-hardware.org/?probe=e6d3982bc0) | Jan 10, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [e14b3158f3](https://linux-hardware.org/?probe=e14b3158f3) | Jan 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ec34483710](https://linux-hardware.org/?probe=ec34483710) | Jan 09, 2023 |
| Dell          | Latitude 7490               | Notebook    | [0780580a38](https://linux-hardware.org/?probe=0780580a38) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [69b46423cb](https://linux-hardware.org/?probe=69b46423cb) | Jan 08, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e43de3e94e](https://linux-hardware.org/?probe=e43de3e94e) | Jan 08, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [2b8c216e1a](https://linux-hardware.org/?probe=2b8c216e1a) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| Cepter        | N530-01                     | Notebook    | [2b5d455bfd](https://linux-hardware.org/?probe=2b5d455bfd) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [5187413460](https://linux-hardware.org/?probe=5187413460) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Dell          | Latitude 9330               | Convertible | [66c7c42eea](https://linux-hardware.org/?probe=66c7c42eea) | Jan 04, 2023 |
| Dell          | Latitude 9330               | Convertible | [fad0f6ab61](https://linux-hardware.org/?probe=fad0f6ab61) | Jan 04, 2023 |
| Dell          | Latitude E5520              | Notebook    | [fd30377f05](https://linux-hardware.org/?probe=fd30377f05) | Jan 04, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [854bee8efb](https://linux-hardware.org/?probe=854bee8efb) | Jan 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | Notebook    | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [ea9aef1e8d](https://linux-hardware.org/?probe=ea9aef1e8d) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [728793a92a](https://linux-hardware.org/?probe=728793a92a) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [90bb379f4e](https://linux-hardware.org/?probe=90bb379f4e) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [23f2e15649](https://linux-hardware.org/?probe=23f2e15649) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [17630a4351](https://linux-hardware.org/?probe=17630a4351) | Dec 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [30eb665688](https://linux-hardware.org/?probe=30eb665688) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6a731c5c9b](https://linux-hardware.org/?probe=6a731c5c9b) | Dec 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [cc8dd14279](https://linux-hardware.org/?probe=cc8dd14279) | Dec 19, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [24affad285](https://linux-hardware.org/?probe=24affad285) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| Google        | Cyan                        | Notebook    | [df6e213ea7](https://linux-hardware.org/?probe=df6e213ea7) | Dec 17, 2022 |
| Google        | Cyan                        | Notebook    | [b0872d0327](https://linux-hardware.org/?probe=b0872d0327) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [226bab8281](https://linux-hardware.org/?probe=226bab8281) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [3326c90617](https://linux-hardware.org/?probe=3326c90617) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [7924d2f347](https://linux-hardware.org/?probe=7924d2f347) | Dec 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [37b8d2824f](https://linux-hardware.org/?probe=37b8d2824f) | Dec 11, 2022 |
| Dell          | 0KG317                      | Desktop     | [cf7f697a0a](https://linux-hardware.org/?probe=cf7f697a0a) | Dec 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [7a6c67f095](https://linux-hardware.org/?probe=7a6c67f095) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [6bb486dbb5](https://linux-hardware.org/?probe=6bb486dbb5) | Dec 07, 2022 |
| MSI           | P67A-C45                    | Desktop     | [44c8da681d](https://linux-hardware.org/?probe=44c8da681d) | Dec 07, 2022 |
| ASRock        | AB350M                      | Desktop     | [95a14fd558](https://linux-hardware.org/?probe=95a14fd558) | Dec 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d655b34178](https://linux-hardware.org/?probe=d655b34178) | Dec 07, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [68fa42c5f5](https://linux-hardware.org/?probe=68fa42c5f5) | Dec 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3caa213ecf](https://linux-hardware.org/?probe=3caa213ecf) | Dec 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [b2b1b1649a](https://linux-hardware.org/?probe=b2b1b1649a) | Dec 03, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| Dell          | Latitude E7240              | Notebook    | [831ec54e18](https://linux-hardware.org/?probe=831ec54e18) | Nov 26, 2022 |
| HP            | Presario CQ56               | Notebook    | [919fad0653](https://linux-hardware.org/?probe=919fad0653) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [7917cbbd8c](https://linux-hardware.org/?probe=7917cbbd8c) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [50c2b71615](https://linux-hardware.org/?probe=50c2b71615) | Nov 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [71c464a407](https://linux-hardware.org/?probe=71c464a407) | Nov 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d3412020ec](https://linux-hardware.org/?probe=d3412020ec) | Nov 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4c86f7c670](https://linux-hardware.org/?probe=4c86f7c670) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2eb90688b5](https://linux-hardware.org/?probe=2eb90688b5) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [dffde21ad4](https://linux-hardware.org/?probe=dffde21ad4) | Nov 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5006a2d188](https://linux-hardware.org/?probe=5006a2d188) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d6644079ac](https://linux-hardware.org/?probe=d6644079ac) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a311d2c018](https://linux-hardware.org/?probe=a311d2c018) | Nov 11, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b7d21d229b](https://linux-hardware.org/?probe=b7d21d229b) | Nov 11, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d6fd1a5ecd](https://linux-hardware.org/?probe=d6fd1a5ecd) | Nov 10, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [5264f28363](https://linux-hardware.org/?probe=5264f28363) | Nov 07, 2022 |
| HP            | Pavilion dv6                | Notebook    | [f715c6e15c](https://linux-hardware.org/?probe=f715c6e15c) | Nov 07, 2022 |
| Dell          | Latitude 3340               | Notebook    | [2c6380f259](https://linux-hardware.org/?probe=2c6380f259) | Nov 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [95fb6a845e](https://linux-hardware.org/?probe=95fb6a845e) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [36e78b1c17](https://linux-hardware.org/?probe=36e78b1c17) | Nov 05, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b3eefc89d6](https://linux-hardware.org/?probe=b3eefc89d6) | Nov 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [653a03dee6](https://linux-hardware.org/?probe=653a03dee6) | Nov 04, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [34c050ed44](https://linux-hardware.org/?probe=34c050ed44) | Nov 03, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [ada830a489](https://linux-hardware.org/?probe=ada830a489) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9bdccc90c4](https://linux-hardware.org/?probe=9bdccc90c4) | Nov 03, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0036848bf2](https://linux-hardware.org/?probe=0036848bf2) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| Dell          | Latitude E7240              | Notebook    | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [f845ed2866](https://linux-hardware.org/?probe=f845ed2866) | Oct 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [e2a6e0f610](https://linux-hardware.org/?probe=e2a6e0f610) | Oct 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | Desktop     | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| Dell          | Latitude 5480               | Notebook    | [0b8576ce3b](https://linux-hardware.org/?probe=0b8576ce3b) | Oct 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5eeed3a9f0](https://linux-hardware.org/?probe=5eeed3a9f0) | Oct 24, 2022 |
| HP            | 828A                        | Desktop     | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [9c484b6d22](https://linux-hardware.org/?probe=9c484b6d22) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | Notebook    | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| Lenovo        | ThinkPad T510 43495KG       | Notebook    | [4668319862](https://linux-hardware.org/?probe=4668319862) | Oct 16, 2022 |
| Getac         | V110G3                      | Notebook    | [09cd83f0ec](https://linux-hardware.org/?probe=09cd83f0ec) | Oct 14, 2022 |
| Lenovo        | ThinkPad T510 43495KG       | Notebook    | [dbe29306f4](https://linux-hardware.org/?probe=dbe29306f4) | Oct 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| MSI           | GL62 6QD                    | Notebook    | [d97ad417e9](https://linux-hardware.org/?probe=d97ad417e9) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [f8d3a419e6](https://linux-hardware.org/?probe=f8d3a419e6) | Oct 07, 2022 |
| Dell          | Latitude 5400               | Notebook    | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [a085d5e42c](https://linux-hardware.org/?probe=a085d5e42c) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| Dell          | Latitude 5400               | Notebook    | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [25077cf5e8](https://linux-hardware.org/?probe=25077cf5e8) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5037913bd4](https://linux-hardware.org/?probe=5037913bd4) | Oct 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [80a70e8f6e](https://linux-hardware.org/?probe=80a70e8f6e) | Oct 03, 2022 |
| ASRock        | Z97 Pro4                    | Desktop     | [d0465080bf](https://linux-hardware.org/?probe=d0465080bf) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fca2e4409a](https://linux-hardware.org/?probe=fca2e4409a) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [54bc787611](https://linux-hardware.org/?probe=54bc787611) | Sep 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [23142407b0](https://linux-hardware.org/?probe=23142407b0) | Sep 28, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [3553d42d14](https://linux-hardware.org/?probe=3553d42d14) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [1095e2f7f0](https://linux-hardware.org/?probe=1095e2f7f0) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| HP            | Presario CQ56               | Notebook    | [ed937514cf](https://linux-hardware.org/?probe=ed937514cf) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [38fa0eaf03](https://linux-hardware.org/?probe=38fa0eaf03) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [72c53fd3c8](https://linux-hardware.org/?probe=72c53fd3c8) | Sep 15, 2022 |
| HP            | 805D                        | Desktop     | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [cb054f2964](https://linux-hardware.org/?probe=cb054f2964) | Sep 12, 2022 |
| MSI           | Z97M-G43                    | Desktop     | [706804a4e2](https://linux-hardware.org/?probe=706804a4e2) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [fe1d0da2fc](https://linux-hardware.org/?probe=fe1d0da2fc) | Sep 10, 2022 |
| ASUSTek       | P9D-M Series                | Server      | [209be79723](https://linux-hardware.org/?probe=209be79723) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| MSI           | P67A-C45                    | Desktop     | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| ASUSTek       | P9D-M Series                | Server      | [04faeec9ab](https://linux-hardware.org/?probe=04faeec9ab) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0df0bba932](https://linux-hardware.org/?probe=0df0bba932) | Sep 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [9438d3a4fe](https://linux-hardware.org/?probe=9438d3a4fe) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [5344528fa4](https://linux-hardware.org/?probe=5344528fa4) | Sep 03, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [9bc39724f8](https://linux-hardware.org/?probe=9bc39724f8) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [446e2d292a](https://linux-hardware.org/?probe=446e2d292a) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [689c3aa34d](https://linux-hardware.org/?probe=689c3aa34d) | Sep 01, 2022 |
| Acer          | Aspire X3400                | Desktop     | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [df96c4acaf](https://linux-hardware.org/?probe=df96c4acaf) | Aug 31, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d4de10030b](https://linux-hardware.org/?probe=d4de10030b) | Aug 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [eba231b7db](https://linux-hardware.org/?probe=eba231b7db) | Aug 30, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | Notebook    | [1ffe55389e](https://linux-hardware.org/?probe=1ffe55389e) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | Notebook    | [46b40c3c67](https://linux-hardware.org/?probe=46b40c3c67) | Aug 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ff55a7dbf1](https://linux-hardware.org/?probe=ff55a7dbf1) | Aug 26, 2022 |
| Acer          | Aspire X3400                | Desktop     | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f80abd07f3](https://linux-hardware.org/?probe=f80abd07f3) | Aug 25, 2022 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [17260bd4fb](https://linux-hardware.org/?probe=17260bd4fb) | Aug 24, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [3df60311dc](https://linux-hardware.org/?probe=3df60311dc) | Aug 24, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [d287893b82](https://linux-hardware.org/?probe=d287893b82) | Aug 22, 2022 |
| Lenovo        | B570e 476022G               | Notebook    | [ad4a4c25d5](https://linux-hardware.org/?probe=ad4a4c25d5) | Aug 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [4adf6ab444](https://linux-hardware.org/?probe=4adf6ab444) | Aug 22, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [e663637449](https://linux-hardware.org/?probe=e663637449) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [da2ae510f9](https://linux-hardware.org/?probe=da2ae510f9) | Aug 17, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2b746c613f](https://linux-hardware.org/?probe=2b746c613f) | Aug 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3f83c9e402](https://linux-hardware.org/?probe=3f83c9e402) | Aug 16, 2022 |
| Dell          | 0H21J3 A04                  | Server      | [14f7add408](https://linux-hardware.org/?probe=14f7add408) | Aug 16, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1298facab1](https://linux-hardware.org/?probe=1298facab1) | Aug 15, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [c0ba049caf](https://linux-hardware.org/?probe=c0ba049caf) | Aug 14, 2022 |
| HP            | 829A                        | Mini pc     | [0e36f81a7b](https://linux-hardware.org/?probe=0e36f81a7b) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [91a2943c51](https://linux-hardware.org/?probe=91a2943c51) | Aug 09, 2022 |
| Dell          | Latitude E5470              | Notebook    | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [244025d59e](https://linux-hardware.org/?probe=244025d59e) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9320816ca5](https://linux-hardware.org/?probe=9320816ca5) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [48606f92a6](https://linux-hardware.org/?probe=48606f92a6) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [c55f1b0a46](https://linux-hardware.org/?probe=c55f1b0a46) | Aug 05, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b224ef1b8d](https://linux-hardware.org/?probe=b224ef1b8d) | Aug 04, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [49ba856687](https://linux-hardware.org/?probe=49ba856687) | Aug 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [015ec264f5](https://linux-hardware.org/?probe=015ec264f5) | Aug 02, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8ea1e0f22c](https://linux-hardware.org/?probe=8ea1e0f22c) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9dd9d17e79](https://linux-hardware.org/?probe=9dd9d17e79) | Jul 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9a7de8cc64](https://linux-hardware.org/?probe=9a7de8cc64) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | Desktop     | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c0ce536184](https://linux-hardware.org/?probe=c0ce536184) | Jul 29, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [ca0d4b7108](https://linux-hardware.org/?probe=ca0d4b7108) | Jul 28, 2022 |
| ASUSTek       | VC65                        | Desktop     | [b43ad009f1](https://linux-hardware.org/?probe=b43ad009f1) | Jul 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a9c3256946](https://linux-hardware.org/?probe=a9c3256946) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [78a53c9be0](https://linux-hardware.org/?probe=78a53c9be0) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [8c749dd7e6](https://linux-hardware.org/?probe=8c749dd7e6) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [aef89fc83f](https://linux-hardware.org/?probe=aef89fc83f) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [137d7c8701](https://linux-hardware.org/?probe=137d7c8701) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76bd6feebe](https://linux-hardware.org/?probe=76bd6feebe) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [3e2f9e1e86](https://linux-hardware.org/?probe=3e2f9e1e86) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2632256ed7](https://linux-hardware.org/?probe=2632256ed7) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8bb191bc8f](https://linux-hardware.org/?probe=8bb191bc8f) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9c1f5f7a4e](https://linux-hardware.org/?probe=9c1f5f7a4e) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d758abd21c](https://linux-hardware.org/?probe=d758abd21c) | Jul 22, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b54cb1f930](https://linux-hardware.org/?probe=b54cb1f930) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8cae76caea](https://linux-hardware.org/?probe=8cae76caea) | Jul 20, 2022 |
| MSI           | MS-B090                     | All in one  | [b5df4140d1](https://linux-hardware.org/?probe=b5df4140d1) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ce2e8f2a2a](https://linux-hardware.org/?probe=ce2e8f2a2a) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [84f993f04d](https://linux-hardware.org/?probe=84f993f04d) | Jul 11, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [ae0184c434](https://linux-hardware.org/?probe=ae0184c434) | Jul 10, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [42158587b1](https://linux-hardware.org/?probe=42158587b1) | Jul 10, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Latitude D531               | Notebook    | [008236dd11](https://linux-hardware.org/?probe=008236dd11) | Jul 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [fec0786471](https://linux-hardware.org/?probe=fec0786471) | Jul 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1bec4af414](https://linux-hardware.org/?probe=1bec4af414) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a658ebf5e9](https://linux-hardware.org/?probe=a658ebf5e9) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [163a5c29e6](https://linux-hardware.org/?probe=163a5c29e6) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [66b8ec6b28](https://linux-hardware.org/?probe=66b8ec6b28) | Jun 29, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4801136187](https://linux-hardware.org/?probe=4801136187) | Jun 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [550772184f](https://linux-hardware.org/?probe=550772184f) | Jun 18, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [680bf4c033](https://linux-hardware.org/?probe=680bf4c033) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [fd2fb2f646](https://linux-hardware.org/?probe=fd2fb2f646) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7990c32699](https://linux-hardware.org/?probe=7990c32699) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dcd3256961](https://linux-hardware.org/?probe=dcd3256961) | Jun 13, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| HP            | Mini 210-1000               | Notebook    | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5a835b2aa6](https://linux-hardware.org/?probe=5a835b2aa6) | Jun 07, 2022 |
| ASUSTek       | X55U                        | Notebook    | [66e1c7ed1d](https://linux-hardware.org/?probe=66e1c7ed1d) | Jun 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [838e0b8e42](https://linux-hardware.org/?probe=838e0b8e42) | Jun 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cb07ae6e24](https://linux-hardware.org/?probe=cb07ae6e24) | Jun 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dd51d706e3](https://linux-hardware.org/?probe=dd51d706e3) | Jun 01, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [6f6f16ee08](https://linux-hardware.org/?probe=6f6f16ee08) | May 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| Notebook      | Multicom Xishan NL50        | Notebook    | [9ffa89c7a9](https://linux-hardware.org/?probe=9ffa89c7a9) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [85a456dd94](https://linux-hardware.org/?probe=85a456dd94) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| Notebook      | Multicom Xishan NL50        | Notebook    | [0c45263f11](https://linux-hardware.org/?probe=0c45263f11) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ff73ff1ea6](https://linux-hardware.org/?probe=ff73ff1ea6) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3487c76d47](https://linux-hardware.org/?probe=3487c76d47) | May 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [db4eade79e](https://linux-hardware.org/?probe=db4eade79e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8226c07ba6](https://linux-hardware.org/?probe=8226c07ba6) | May 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [1fa6bb2d62](https://linux-hardware.org/?probe=1fa6bb2d62) | May 26, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [a07fb7cbcd](https://linux-hardware.org/?probe=a07fb7cbcd) | May 25, 2022 |
| Lenovo        | ThinkPad T490s 20NX0077M... | Notebook    | [cea81a1d63](https://linux-hardware.org/?probe=cea81a1d63) | May 24, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [428631aa4a](https://linux-hardware.org/?probe=428631aa4a) | May 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [19d23eb25f](https://linux-hardware.org/?probe=19d23eb25f) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5ea71aeb2](https://linux-hardware.org/?probe=f5ea71aeb2) | May 21, 2022 |
| Notebook      | N8xEJEK                     | Notebook    | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [79682a20fa](https://linux-hardware.org/?probe=79682a20fa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [c195f80f3c](https://linux-hardware.org/?probe=c195f80f3c) | May 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [47b730f9bd](https://linux-hardware.org/?probe=47b730f9bd) | May 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [afac7f7fb3](https://linux-hardware.org/?probe=afac7f7fb3) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2075bfcc02](https://linux-hardware.org/?probe=2075bfcc02) | May 05, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [71f8f45765](https://linux-hardware.org/?probe=71f8f45765) | May 05, 2022 |
| HP            | ProBook 4330s               | Notebook    | [7cad0acb2c](https://linux-hardware.org/?probe=7cad0acb2c) | May 04, 2022 |
| HP            | ProBook 4330s               | Notebook    | [ca6474fbfc](https://linux-hardware.org/?probe=ca6474fbfc) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d9a2b425f](https://linux-hardware.org/?probe=7d9a2b425f) | May 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [01de94a143](https://linux-hardware.org/?probe=01de94a143) | May 02, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [743177a467](https://linux-hardware.org/?probe=743177a467) | Apr 24, 2022 |
| Acer          | Swift SF514-51              | Notebook    | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| Acer          | Predator G3610              | Desktop     | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91bbf4068b](https://linux-hardware.org/?probe=91bbf4068b) | Apr 20, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [e595903b64](https://linux-hardware.org/?probe=e595903b64) | Apr 18, 2022 |
| Google        | Cave                        | Notebook    | [c762019e08](https://linux-hardware.org/?probe=c762019e08) | Apr 18, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b2fe9a09fd](https://linux-hardware.org/?probe=b2fe9a09fd) | Apr 17, 2022 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [19299bc16d](https://linux-hardware.org/?probe=19299bc16d) | Apr 14, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [29124147fe](https://linux-hardware.org/?probe=29124147fe) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490s 20NX003UM... | Notebook    | [60dca75a93](https://linux-hardware.org/?probe=60dca75a93) | Apr 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [7f83d03bf3](https://linux-hardware.org/?probe=7f83d03bf3) | Apr 13, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [2d44f4a10b](https://linux-hardware.org/?probe=2d44f4a10b) | Apr 13, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [bbcb05781f](https://linux-hardware.org/?probe=bbcb05781f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T460s 20F90044M... | Notebook    | [47498ed4aa](https://linux-hardware.org/?probe=47498ed4aa) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| HP            | 87F9 A00                    | All in one  | [a5081405c2](https://linux-hardware.org/?probe=a5081405c2) | Apr 11, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [cf2e65caf4](https://linux-hardware.org/?probe=cf2e65caf4) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [c344a9c7b9](https://linux-hardware.org/?probe=c344a9c7b9) | Apr 10, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [dd511f4bf0](https://linux-hardware.org/?probe=dd511f4bf0) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [5328fde624](https://linux-hardware.org/?probe=5328fde624) | Apr 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [abc7562fb9](https://linux-hardware.org/?probe=abc7562fb9) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | Notebook    | [79c6231f19](https://linux-hardware.org/?probe=79c6231f19) | Apr 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Norway/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 131       | 11.37%  |
| Ubuntu 18.04                 | 61        | 5.3%    |
| Ubuntu 22.04                 | 55        | 4.77%   |
| Pop!_OS 22.04                | 43        | 3.73%   |
| Debian 11                    | 41        | 3.56%   |
| Zorin 16                     | 28        | 2.43%   |
| Arch Rolling                 | 27        | 2.34%   |
| ArcoLinux Rolling            | 21        | 1.82%   |
| Ubuntu 20.10                 | 20        | 1.74%   |
| OpenMandriva 4.2             | 20        | 1.74%   |
| Fedora 35                    | 20        | 1.74%   |
| OpenMandriva 4.3             | 19        | 1.65%   |
| Fedora 38                    | 19        | 1.65%   |
| Ubuntu 23.04                 | 17        | 1.48%   |
| Fedora 36                    | 17        | 1.48%   |
| Arch                         | 17        | 1.48%   |
| Pop!_OS 21.04                | 15        | 1.3%    |
| openSUSE Tumbleweed-XXXXXXXX | 15        | 1.3%    |
| Manjaro                      | 15        | 1.3%    |
| Pop!_OS 21.10                | 14        | 1.22%   |
| KDE neon 20.04               | 14        | 1.22%   |
| Fedora 37                    | 14        | 1.22%   |
| Fedora 34                    | 14        | 1.22%   |
| Fedora 31                    | 14        | 1.22%   |
| Ubuntu 19.10                 | 13        | 1.13%   |
| Ubuntu 19.04                 | 13        | 1.13%   |
| Ubuntu 22.10                 | 12        | 1.04%   |
| Ubuntu 18.10                 | 12        | 1.04%   |
| Pop!_OS 20.10                | 12        | 1.04%   |
| Pop!_OS 20.04                | 12        | 1.04%   |
| Linux Mint 20.2              | 12        | 1.04%   |
| Linux Mint 21.1              | 11        | 0.95%   |
| OpenMandriva 23.03           | 10        | 0.87%   |
| Linux Mint 20.3              | 10        | 0.87%   |
| Ubuntu 21.10                 | 9         | 0.78%   |
| Linux Mint 20.1              | 9         | 0.78%   |
| Linux Mint 19.3              | 9         | 0.78%   |
| Fedora 32                    | 9         | 0.78%   |
| Debian 12                    | 9         | 0.78%   |
| Debian 10                    | 9         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 337       | 30.89%  |
| Fedora        | 105       | 9.62%   |
| Pop!_OS       | 88        | 8.07%   |
| Debian        | 68        | 6.23%   |
| Linux Mint    | 67        | 6.14%   |
| OpenMandriva  | 66        | 6.05%   |
| Manjaro       | 48        | 4.4%    |
| Arch          | 44        | 4.03%   |
| Zorin         | 37        | 3.39%   |
| KDE neon      | 25        | 2.29%   |
| ArcoLinux     | 22        | 2.02%   |
| openSUSE      | 21        | 1.92%   |
| Xubuntu       | 17        | 1.56%   |
| Kubuntu       | 15        | 1.37%   |
| Kali          | 12        | 1.1%    |
| Elementary    | 12        | 1.1%    |
| Gentoo        | 11        | 1.01%   |
| Ubuntu MATE   | 9         | 0.82%   |
| Clear Linux   | 8         | 0.73%   |
| ROSA          | 7         | 0.64%   |
| RHEL          | 7         | 0.64%   |
| CentOS        | 7         | 0.64%   |
| Ubuntu Budgie | 6         | 0.55%   |
| EndeavourOS   | 5         | 0.46%   |
| Xero          | 4         | 0.37%   |
| Solus         | 4         | 0.37%   |
| NixOS         | 4         | 0.37%   |
| Lubuntu       | 4         | 0.37%   |
| Ubuntu Unity  | 3         | 0.27%   |
| Nobara        | 3         | 0.27%   |
| Garuda Linux  | 3         | 0.27%   |
| Ubuntu Studio | 2         | 0.18%   |
| Rocky Linux   | 2         | 0.18%   |
| MX            | 2         | 0.18%   |
| LMDE          | 2         | 0.18%   |
| Alpine        | 2         | 0.18%   |
| Void Linux    | 1         | 0.09%   |
| Raspbian      | 1         | 0.09%   |
| PostmarketOS  | 1         | 0.09%   |
| Peppermint    | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 19        | 1.48%   |
| 5.16.7-desktop-1omv4003     | 18        | 1.4%    |
| 5.4.0-42-generic            | 14        | 1.09%   |
| 6.2.6-desktop-1omv2390      | 10        | 0.78%   |
| 5.19.0-76051900-generic     | 10        | 0.78%   |
| 5.15.0-46-generic           | 10        | 0.78%   |
| 5.4.0-58-generic            | 9         | 0.7%    |
| 5.3.0-46-generic            | 9         | 0.7%    |
| 5.15.0-76-generic           | 9         | 0.7%    |
| 4.18.0-16-generic           | 9         | 0.7%    |
| 3.10.0-1062.12.1.el7.x86_64 | 9         | 0.7%    |
| 6.1.1-desktop-1omv2290      | 8         | 0.62%   |
| 5.4.0-74-generic            | 8         | 0.62%   |
| 5.4.0-48-generic            | 8         | 0.62%   |
| 5.11.0-40-generic           | 8         | 0.62%   |
| 5.11.0-38-generic           | 8         | 0.62%   |
| 6.2.6-76060206-generic      | 7         | 0.54%   |
| 6.2.0-20-generic            | 7         | 0.54%   |
| 6.0.12-76060006-generic     | 7         | 0.54%   |
| 5.8.0-7630-generic          | 7         | 0.54%   |
| 5.8.0-44-generic            | 7         | 0.54%   |
| 5.8.0-43-generic            | 7         | 0.54%   |
| 5.4.0-91-generic            | 7         | 0.54%   |
| 5.4.0-26-generic            | 7         | 0.54%   |
| 5.3.0-40-generic            | 7         | 0.54%   |
| 5.15.0-58-generic           | 7         | 0.54%   |
| 5.15.0-56-generic           | 7         | 0.54%   |
| 5.15.0-48-generic           | 7         | 0.54%   |
| 5.11.0-7620-generic         | 7         | 0.54%   |
| 6.2.0-26-generic            | 6         | 0.47%   |
| 5.4.0-47-generic            | 6         | 0.47%   |
| 5.4.0-45-generic            | 6         | 0.47%   |
| 5.4.0-29-generic            | 6         | 0.47%   |
| 5.3.0-28-generic            | 6         | 0.47%   |
| 5.15.0-60-generic           | 6         | 0.47%   |
| 5.15.0-41-generic           | 6         | 0.47%   |
| 5.11.0-27-generic           | 6         | 0.47%   |
| 5.10.0-8-amd64              | 6         | 0.47%   |
| 5.0.0-20-generic            | 6         | 0.47%   |
| 5.8.0-48-generic            | 5         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 164       | 13.51%  |
| 5.15.0  | 84        | 6.92%   |
| 5.11.0  | 55        | 4.53%   |
| 5.8.0   | 54        | 4.45%   |
| 5.19.0  | 49        | 4.04%   |
| 5.3.0   | 42        | 3.46%   |
| 5.13.0  | 39        | 3.21%   |
| 4.15.0  | 38        | 3.13%   |
| 5.10.0  | 37        | 3.05%   |
| 4.18.0  | 30        | 2.47%   |
| 6.2.0   | 25        | 2.06%   |
| 5.0.0   | 25        | 2.06%   |
| 6.2.6   | 19        | 1.57%   |
| 5.10.14 | 19        | 1.57%   |
| 5.16.7  | 18        | 1.48%   |
| 6.1.0   | 12        | 0.99%   |
| 3.10.0  | 10        | 0.82%   |
| 4.19.0  | 9         | 0.74%   |
| 6.1.1   | 8         | 0.66%   |
| 5.17.5  | 8         | 0.66%   |
| 6.0.12  | 7         | 0.58%   |
| 5.16.0  | 7         | 0.58%   |
| 6.4.12  | 6         | 0.49%   |
| 6.0.0   | 6         | 0.49%   |
| 5.17.0  | 6         | 0.49%   |
| 5.16.11 | 6         | 0.49%   |
| 6.4.0   | 5         | 0.41%   |
| 5.9.16  | 5         | 0.41%   |
| 5.5.5   | 5         | 0.41%   |
| 5.18.10 | 5         | 0.41%   |
| 5.18.0  | 5         | 0.41%   |
| 5.12.4  | 5         | 0.41%   |
| 6.4.8   | 4         | 0.33%   |
| 6.4.6   | 4         | 0.33%   |
| 6.3.9   | 4         | 0.33%   |
| 6.2.9   | 4         | 0.33%   |
| 6.2.8   | 4         | 0.33%   |
| 6.1.11  | 4         | 0.33%   |
| 6.0.6   | 4         | 0.33%   |
| 6.0.2   | 4         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 181       | 15.16%  |
| 5.15    | 124       | 10.39%  |
| 5.8     | 70        | 5.86%   |
| 5.10    | 69        | 5.78%   |
| 5.19    | 68        | 5.7%    |
| 5.11    | 64        | 5.36%   |
| 5.13    | 61        | 5.11%   |
| 6.2     | 60        | 5.03%   |
| 5.3     | 51        | 4.27%   |
| 5.16    | 50        | 4.19%   |
| 6.1     | 43        | 3.6%    |
| 4.15    | 38        | 3.18%   |
| 4.18    | 33        | 2.76%   |
| 6.4     | 31        | 2.6%    |
| 5.17    | 31        | 2.6%    |
| 6.0     | 29        | 2.43%   |
| 5.0     | 27        | 2.26%   |
| 5.14    | 22        | 1.84%   |
| 5.9     | 21        | 1.76%   |
| 6.3     | 19        | 1.59%   |
| 5.18    | 18        | 1.51%   |
| 5.12    | 15        | 1.26%   |
| 5.5     | 12        | 1.01%   |
| 5.7     | 11        | 0.92%   |
| 4.19    | 11        | 0.92%   |
| 3.10    | 10        | 0.84%   |
| 5.6     | 8         | 0.67%   |
| 4.9     | 4         | 0.34%   |
| 5.1     | 3         | 0.25%   |
| 6.5     | 2         | 0.17%   |
| 5.2     | 2         | 0.17%   |
| 4.4     | 2         | 0.17%   |
| 4.20    | 1         | 0.08%   |
| 4.12    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |
| 4.1     | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1029      | 97.63%  |
| i686    | 14        | 1.33%   |
| aarch64 | 8         | 0.76%   |
| armv7l  | 2         | 0.19%   |
| armv6l  | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 504       | 46.07%  |
| KDE5              | 181       | 16.54%  |
| Unknown           | 148       | 13.53%  |
| XFCE              | 84        | 7.68%   |
| X-Cinnamon        | 50        | 4.57%   |
| KDE               | 25        | 2.29%   |
| MATE              | 21        | 1.92%   |
| i3                | 14        | 1.28%   |
| Cinnamon          | 11        | 1.01%   |
| Pantheon          | 10        | 0.91%   |
| Budgie            | 10        | 0.91%   |
| GNOME Flashback   | 8         | 0.73%   |
| LXDE              | 5         | 0.46%   |
| LXQt              | 4         | 0.37%   |
| Unity             | 3         | 0.27%   |
| KDE4              | 3         | 0.27%   |
| i3-with-shmlog    | 2         | 0.18%   |
| Hyprland          | 2         | 0.18%   |
| dwm               | 2         | 0.18%   |
| Yaru:ubuntu:GNOME | 1         | 0.09%   |
| xinit-compat      | 1         | 0.09%   |
| qtile             | 1         | 0.09%   |
| LeftWM            | 1         | 0.09%   |
| GNOME:Phosh       | 1         | 0.09%   |
| Deepin            | 1         | 0.09%   |
| bspwm             | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 776       | 71%     |
| Wayland | 202       | 18.48%  |
| Unknown | 75        | 6.86%   |
| Tty     | 40        | 3.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 541       | 49%     |
| SDDM    | 157       | 14.22%  |
| GDM     | 141       | 12.77%  |
| GDM3    | 129       | 11.68%  |
| LightDM | 101       | 9.15%   |
| TDM     | 28        | 2.54%   |
| KDM     | 4         | 0.36%   |
| XDM     | 2         | 0.18%   |
| Ly      | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 572       | 52.91%  |
| nb_NO       | 240       | 22.2%   |
| Unknown     | 108       | 9.99%   |
| en_GB       | 68        | 6.29%   |
| C           | 22        | 2.04%   |
| nn_NO       | 18        | 1.67%   |
| pl_PL       | 11        | 1.02%   |
| en_DK       | 10        | 0.93%   |
| de_DE       | 9         | 0.83%   |
| fr_FR       | 3         | 0.28%   |
| en_IE       | 3         | 0.28%   |
| ru_RU       | 2         | 0.19%   |
| pt_PT       | 2         | 0.19%   |
| POSIX       | 2         | 0.19%   |
| it_IT       | 1         | 0.09%   |
| fi_FI       | 1         | 0.09%   |
| es_ES       | 1         | 0.09%   |
| en_US.utf-8 | 1         | 0.09%   |
| en_NZ       | 1         | 0.09%   |
| en_CA       | 1         | 0.09%   |
| en_AG       | 1         | 0.09%   |
| en_150      | 1         | 0.09%   |
| en_001      | 1         | 0.09%   |
| el_GR       | 1         | 0.09%   |
| da_DK       | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 595       | 55.3%   |
| BIOS | 481       | 44.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 796       | 73.98%  |
| Btrfs   | 123       | 11.43%  |
| Overlay | 66        | 6.13%   |
| Xfs     | 33        | 3.07%   |
| Unknown | 24        | 2.23%   |
| Tmpfs   | 20        | 1.86%   |
| Zfs     | 8         | 0.74%   |
| Ext2    | 4         | 0.37%   |
| F2fs    | 1         | 0.09%   |
| Ext3    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 532       | 49.26%  |
| GPT     | 465       | 43.06%  |
| MBR     | 83        | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 918       | 85.32%  |
| Yes       | 158       | 14.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 795       | 73.95%  |
| Yes       | 280       | 26.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 224       | 21.25%  |
| Lenovo                  | 213       | 20.21%  |
| Hewlett-Packard         | 153       | 14.52%  |
| Dell                    | 130       | 12.33%  |
| MSI                     | 65        | 6.17%   |
| Gigabyte Technology     | 50        | 4.74%   |
| Acer                    | 47        | 4.46%   |
| Apple                   | 34        | 3.23%   |
| ASRock                  | 25        | 2.37%   |
| HUAWEI                  | 13        | 1.23%   |
| Samsung Electronics     | 12        | 1.14%   |
| Intel                   | 11        | 1.04%   |
| Toshiba                 | 8         | 0.76%   |
| Raspberry Pi Foundation | 8         | 0.76%   |
| Unknown                 | 8         | 0.76%   |
| Packard Bell            | 7         | 0.66%   |
| Notebook                | 5         | 0.47%   |
| Clevo                   | 4         | 0.38%   |
| Pegatron                | 3         | 0.28%   |
| Microsoft               | 3         | 0.28%   |
| Google                  | 3         | 0.28%   |
| Supermicro              | 2         | 0.19%   |
| ZOTAC                   | 1         | 0.09%   |
| Xunlong                 | 1         | 0.09%   |
| Wibtek                  | 1         | 0.09%   |
| TYAN Computer           | 1         | 0.09%   |
| Teclast                 | 1         | 0.09%   |
| Star Labs               | 1         | 0.09%   |
| Sony                    | 1         | 0.09%   |
| Shuttle                 | 1         | 0.09%   |
| Razer                   | 1         | 0.09%   |
| Panasonic               | 1         | 0.09%   |
| Nokia                   | 1         | 0.09%   |
| Multicom Norge AS       | 1         | 0.09%   |
| Lenovo Product          | 1         | 0.09%   |
| LAMINA                  | 1         | 0.09%   |
| Intel Client Systems    | 1         | 0.09%   |
| GMKtec                  | 1         | 0.09%   |
| Getac                   | 1         | 0.09%   |
| Fujitsu Siemens         | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ASUS All Series                         | 14        | 1.33%   |
| Unknown                                 | 9         | 0.85%   |
| ASUS KomplettPC                         | 7         | 0.66%   |
| Apple MacBookPro12,1                    | 7         | 0.66%   |
| HUAWEI MACH-WX9                         | 6         | 0.57%   |
| HP EliteBook 840 G6                     | 6         | 0.57%   |
| Dell Precision 5530                     | 6         | 0.57%   |
| Dell PowerEdge R230                     | 5         | 0.47%   |
| ASUS ROG STRIX B360-F GAMING            | 5         | 0.47%   |
| MSI MS-7885                             | 4         | 0.38%   |
| HP ProBook 430 G2                       | 4         | 0.38%   |
| Gigabyte GA-970A-UD3                    | 4         | 0.38%   |
| Dell XPS 15 9570                        | 4         | 0.38%   |
| Dell OptiPlex 9020                      | 4         | 0.38%   |
| Dell Latitude E7240                     | 4         | 0.38%   |
| ASUS ROG STRIX X570-F GAMING            | 4         | 0.38%   |
| ASUS ROG STRIX B550-E GAMING            | 4         | 0.38%   |
| ASUS ROG CROSSHAIR VIII HERO            | 4         | 0.38%   |
| ASUS M2R-FVM                            | 4         | 0.38%   |
| Samsung 950XCJ/951XCJ/950XCR            | 3         | 0.28%   |
| MSI MS-7B86                             | 3         | 0.28%   |
| Lenovo Yoga Slim 7 Carbon 14ACN6 82L0   | 3         | 0.28%   |
| HUAWEI WRT-WX9                          | 3         | 0.28%   |
| HP OMEN by Laptop                       | 3         | 0.28%   |
| HP EliteBook 8470p                      | 3         | 0.28%   |
| HP EliteBook 840 G5                     | 3         | 0.28%   |
| HP Compaq Elite 8300 SFF                | 3         | 0.28%   |
| Dell XPS 15 9500                        | 3         | 0.28%   |
| Dell XPS 13 9380                        | 3         | 0.28%   |
| Dell OptiPlex 7010                      | 3         | 0.28%   |
| Dell Latitude E5470                     | 3         | 0.28%   |
| Dell Latitude 5480                      | 3         | 0.28%   |
| ASUS Z170 PRO GAMING                    | 3         | 0.28%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA | 3         | 0.28%   |
| ASUS SABERTOOTH P67                     | 3         | 0.28%   |
| ASUS ROG STRIX X470-F GAMING            | 3         | 0.28%   |
| ASUS ROG STRIX B550-I GAMING            | 3         | 0.28%   |
| ASUS ROG STRIX B450-F GAMING            | 3         | 0.28%   |
| ASUS PRIME X570-P                       | 3         | 0.28%   |
| ASUS P9X79 LE                           | 3         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 132       | 12.52%  |
| ASUS ROG              | 49        | 4.65%   |
| HP EliteBook          | 46        | 4.36%   |
| Dell Latitude         | 43        | 4.08%   |
| Acer Aspire           | 30        | 2.85%   |
| Dell Precision        | 25        | 2.37%   |
| Dell XPS              | 24        | 2.28%   |
| HP ProBook            | 23        | 2.18%   |
| ASUS PRIME            | 23        | 2.18%   |
| Lenovo Yoga           | 19        | 1.8%    |
| Dell OptiPlex         | 17        | 1.61%   |
| Lenovo IdeaPad        | 16        | 1.52%   |
| HP Pavilion           | 14        | 1.33%   |
| ASUS All              | 14        | 1.33%   |
| Dell PowerEdge        | 13        | 1.23%   |
| ASUS TUF              | 13        | 1.23%   |
| ASUS VivoBook         | 12        | 1.14%   |
| Lenovo ThinkCentre    | 11        | 1.04%   |
| HP ZBook              | 11        | 1.04%   |
| Unknown               | 9         | 0.85%   |
| RPi Raspberry         | 8         | 0.76%   |
| HP EliteDesk          | 8         | 0.76%   |
| Gigabyte X570         | 8         | 0.76%   |
| Lenovo Legion         | 7         | 0.66%   |
| ASUS KomplettPC       | 7         | 0.66%   |
| Apple MacBookPro12    | 7         | 0.66%   |
| Toshiba Satellite     | 6         | 0.57%   |
| HUAWEI MACH-WX9       | 6         | 0.57%   |
| HP Compaq             | 6         | 0.57%   |
| Dell Inspiron         | 6         | 0.57%   |
| ASUS SABERTOOTH       | 6         | 0.57%   |
| Acer Swift            | 6         | 0.57%   |
| Packard Bell EasyNote | 5         | 0.47%   |
| HP Spectre            | 5         | 0.47%   |
| HP OMEN               | 5         | 0.47%   |
| HP Laptop             | 5         | 0.47%   |
| HP ENVY               | 5         | 0.47%   |
| Gigabyte B550         | 5         | 0.47%   |
| Gigabyte B450         | 5         | 0.47%   |
| MSI MS-7885           | 4         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 120       | 11.39%  |
| 2018    | 119       | 11.29%  |
| 2020    | 99        | 9.39%   |
| 2017    | 83        | 7.87%   |
| 2012    | 81        | 7.69%   |
| 2015    | 74        | 7.02%   |
| 2021    | 68        | 6.45%   |
| 2016    | 66        | 6.26%   |
| 2014    | 64        | 6.07%   |
| 2013    | 63        | 5.98%   |
| 2011    | 62        | 5.88%   |
| 2010    | 39        | 3.7%    |
| 2022    | 35        | 3.32%   |
| 2009    | 26        | 2.47%   |
| 2008    | 13        | 1.23%   |
| 2007    | 12        | 1.14%   |
| 2023    | 9         | 0.85%   |
| Unknown | 9         | 0.85%   |
| 2006    | 7         | 0.66%   |
| 2005    | 4         | 0.38%   |
| 2001    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 587       | 55.69%  |
| Desktop        | 370       | 35.1%   |
| Convertible    | 31        | 2.94%   |
| Mini pc        | 17        | 1.61%   |
| Server         | 17        | 1.61%   |
| All in one     | 13        | 1.23%   |
| System on chip | 10        | 0.95%   |
| Tablet         | 9         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 960       | 90.48%  |
| Enabled  | 101       | 9.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1049      | 99.53%  |
| Yes  | 5         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 271       | 25.28%  |
| 4.01-8.0        | 237       | 22.11%  |
| 32.01-64.0      | 174       | 16.23%  |
| 8.01-16.0       | 157       | 14.65%  |
| 3.01-4.0        | 126       | 11.75%  |
| 64.01-256.0     | 54        | 5.04%   |
| 24.01-32.0      | 20        | 1.87%   |
| 1.01-2.0        | 19        | 1.77%   |
| 2.01-3.0        | 4         | 0.37%   |
| 0.01-0.5        | 4         | 0.37%   |
| More than 256.0 | 3         | 0.28%   |
| 0.51-1.0        | 3         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 322       | 26.95%  |
| 2.01-3.0    | 276       | 23.1%   |
| 4.01-8.0    | 248       | 20.75%  |
| 3.01-4.0    | 191       | 15.98%  |
| 8.01-16.0   | 67        | 5.61%   |
| 0.51-1.0    | 53        | 4.44%   |
| 0.01-0.5    | 15        | 1.26%   |
| 16.01-24.0  | 14        | 1.17%   |
| 32.01-64.0  | 4         | 0.33%   |
| 24.01-32.0  | 4         | 0.33%   |
| 64.01-256.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 655       | 60.04%  |
| 2      | 213       | 19.52%  |
| 3      | 90        | 8.25%   |
| 4      | 54        | 4.95%   |
| 5      | 27        | 2.47%   |
| 6      | 20        | 1.83%   |
| 0      | 13        | 1.19%   |
| 7      | 7         | 0.64%   |
| 11     | 4         | 0.37%   |
| 8      | 4         | 0.37%   |
| 9      | 3         | 0.27%   |
| 10     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 780       | 73.52%  |
| Yes       | 281       | 26.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 894       | 84.58%  |
| No        | 163       | 15.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 837       | 79.11%  |
| No        | 221       | 20.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 700       | 65.54%  |
| No        | 368       | 34.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Norway  | 1054      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Oslo                 | 306       | 27.1%   |
| Trondheim            | 73        | 6.47%   |
| Bergen               | 44        | 3.9%    |
| Stavanger            | 32        | 2.83%   |
| Kristiansand         | 31        | 2.75%   |
| Ålesund             | 19        | 1.68%   |
| Skien                | 17        | 1.51%   |
| Sandefjord           | 16        | 1.42%   |
| Tromsø              | 14        | 1.24%   |
| Drammen              | 13        | 1.15%   |
| Kongsberg            | 12        | 1.06%   |
| Asker                | 11        | 0.97%   |
| Fornebu              | 10        | 0.89%   |
| Røyken Municipality | 9         | 0.8%    |
| Lillehammer          | 9         | 0.8%    |
| Arendal              | 9         | 0.8%    |
| Sandnes              | 8         | 0.71%   |
| Nesttun              | 8         | 0.71%   |
| Fredrikstad          | 8         | 0.71%   |
| Sarpsborg            | 7         | 0.62%   |
| Moss                 | 7         | 0.62%   |
| Honefoss             | 7         | 0.62%   |
| Bodø                | 7         | 0.62%   |
| Stjordal             | 6         | 0.53%   |
| Porsgrunn            | 6         | 0.53%   |
| Haugesund            | 6         | 0.53%   |
| Harstad              | 6         | 0.53%   |
| Fetsund              | 6         | 0.53%   |
| Drobak               | 6         | 0.53%   |
| Voll                 | 5         | 0.44%   |
| Tønsberg            | 5         | 0.44%   |
| Notodden             | 5         | 0.44%   |
| Mjondalen            | 5         | 0.44%   |
| Melhus               | 5         | 0.44%   |
| Langhus              | 5         | 0.44%   |
| Kristiansund         | 5         | 0.44%   |
| Hamar                | 5         | 0.44%   |
| Egersund             | 5         | 0.44%   |
| Bo                   | 5         | 0.44%   |
| Vennesla             | 4         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 374       | 601    | 23.91%  |
| Seagate                        | 196       | 365    | 12.53%  |
| WDC                            | 165       | 351    | 10.55%  |
| Kingston                       | 110       | 159    | 7.03%   |
| Toshiba                        | 91        | 131    | 5.82%   |
| SanDisk                        | 79        | 107    | 5.05%   |
| Intel                          | 61        | 84     | 3.9%    |
| SK hynix                       | 56        | 67     | 3.58%   |
| Crucial                        | 51        | 83     | 3.26%   |
| Unknown                        | 47        | 60     | 3.01%   |
| Hitachi                        | 42        | 58     | 2.69%   |
| Micron Technology              | 37        | 49     | 2.37%   |
| HGST                           | 30        | 39     | 1.92%   |
| Corsair                        | 26        | 39     | 1.66%   |
| Apple                          | 24        | 28     | 1.53%   |
| Phison                         | 18        | 23     | 1.15%   |
| LITEON                         | 16        | 20     | 1.02%   |
| PNY                            | 15        | 23     | 0.96%   |
| OCZ                            | 15        | 18     | 0.96%   |
| LITEONIT                       | 10        | 15     | 0.64%   |
| KIOXIA                         | 10        | 18     | 0.64%   |
| A-DATA Technology              | 9         | 12     | 0.58%   |
| Phison Electronics             | 8         | 15     | 0.51%   |
| Kingston Technology Company    | 7         | 10     | 0.45%   |
| Lenovo                         | 5         | 5      | 0.32%   |
| Intenso                        | 5         | 8      | 0.32%   |
| China                          | 5         | 6      | 0.32%   |
| JMicron Technology             | 4         | 4      | 0.26%   |
| Fujitsu                        | 4         | 4      | 0.26%   |
| Unknown                        | 3         | 4      | 0.19%   |
| XPG                            | 2         | 2      | 0.13%   |
| Transcend                      | 2         | 2      | 0.13%   |
| Solid State Storage Technology | 2         | 2      | 0.13%   |
| Silicon Motion                 | 2         | 3      | 0.13%   |
| Patriot                        | 2         | 2      | 0.13%   |
| Lexar                          | 2         | 2      | 0.13%   |
| Goodram                        | 2         | 2      | 0.13%   |
| ASMT                           | 2         | 3      | 0.13%   |
| Union Memory                   | 1         | 1      | 0.06%   |
| UMIS                           | 1         | 1      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 22        | 1.23%   |
| Samsung SSD 850 EVO 250GB                           | 18        | 1%      |
| Samsung SSD 860 EVO 1TB                             | 15        | 0.84%   |
| Kingston SV300S37A120G 120GB SSD                    | 15        | 0.84%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 13        | 0.72%   |
| Samsung SSD 850 EVO 500GB                           | 13        | 0.72%   |
| Samsung SSD 840 EVO 250GB                           | 13        | 0.72%   |
| Samsung SSD 860 EVO 500GB                           | 12        | 0.67%   |
| Samsung NVMe SSD Drive 500GB                        | 11        | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 11        | 0.61%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10        | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 10        | 0.56%   |
| PNY ELITE PSSD 480GB                                | 10        | 0.56%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 9         | 0.5%    |
| Seagate Expansion 1TB                               | 9         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB                        | 9         | 0.5%    |
| Samsung NVMe SSD Drive 512GB                        | 9         | 0.5%    |
| Samsung NVMe SSD Drive 1TB                          | 9         | 0.5%    |
| HGST HTS721010A9E630 1TB                            | 9         | 0.5%    |
| WDC WD30EFRX-68EUZN0 3TB                            | 8         | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB                      | 8         | 0.45%   |
| Samsung SSD 860 EVO 250GB                           | 8         | 0.45%   |
| Samsung SSD 840 EVO 120GB                           | 8         | 0.45%   |
| Kingston SA400S37240G 240GB SSD                     | 8         | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB                      | 7         | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB                      | 7         | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 7         | 0.39%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                | 7         | 0.39%   |
| Kingston SV300S37A240G 240GB SSD                    | 7         | 0.39%   |
| Kingston NVMe SSD Drive 1TB                         | 7         | 0.39%   |
| Apple SSD SM0128G 121GB                             | 7         | 0.39%   |
| Unknown MMC Card  64GB                              | 6         | 0.33%   |
| Seagate ST500DM002-1BD142 500GB                     | 6         | 0.33%   |
| Seagate ST4000VN008-2DR166 4TB                      | 6         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                      | 6         | 0.33%   |
| Seagate Backup+ Hub BK 8TB                          | 6         | 0.33%   |
| SanDisk NVMe SSD Drive 1TB                          | 6         | 0.33%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.33%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 5         | 0.28%   |
| Unknown MMC Card  16GB                              | 5         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 191       | 357    | 40.64%  |
| WDC                 | 114       | 264    | 24.26%  |
| Toshiba             | 45        | 75     | 9.57%   |
| Hitachi             | 42        | 58     | 8.94%   |
| HGST                | 30        | 39     | 6.38%   |
| Samsung Electronics | 28        | 48     | 5.96%   |
| Apple               | 6         | 7      | 1.28%   |
| Fujitsu             | 4         | 4      | 0.85%   |
| Unknown             | 3         | 3      | 0.64%   |
| Intenso             | 3         | 6      | 0.64%   |
| LaCie               | 1         | 1      | 0.21%   |
| IET                 | 1         | 2      | 0.21%   |
| ASMT                | 1         | 2      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 203       | 291    | 34.82%  |
| Kingston            | 75        | 100    | 12.86%  |
| Crucial             | 45        | 77     | 7.72%   |
| SanDisk             | 40        | 50     | 6.86%   |
| Intel               | 34        | 48     | 5.83%   |
| WDC                 | 26        | 51     | 4.46%   |
| Micron Technology   | 17        | 23     | 2.92%   |
| Apple               | 16        | 19     | 2.74%   |
| SK hynix            | 15        | 17     | 2.57%   |
| PNY                 | 15        | 23     | 2.57%   |
| OCZ                 | 15        | 18     | 2.57%   |
| Corsair             | 15        | 20     | 2.57%   |
| LITEON              | 13        | 17     | 2.23%   |
| Toshiba             | 11        | 14     | 1.89%   |
| LITEONIT            | 10        | 15     | 1.72%   |
| A-DATA Technology   | 7         | 10     | 1.2%    |
| China               | 5         | 6      | 0.86%   |
| Transcend           | 2         | 2      | 0.34%   |
| Patriot             | 2         | 2      | 0.34%   |
| GOODRAM             | 2         | 2      | 0.34%   |
| Teclast             | 1         | 1      | 0.17%   |
| Team                | 1         | 1      | 0.17%   |
| SPCC                | 1         | 1      | 0.17%   |
| Seagate             | 1         | 1      | 0.17%   |
| SandForce           | 1         | 2      | 0.17%   |
| Radeon              | 1         | 1      | 0.17%   |
| Phison              | 1         | 1      | 0.17%   |
| LDLC                | 1         | 1      | 0.17%   |
| KingSpec            | 1         | 2      | 0.17%   |
| KingFast            | 1         | 1      | 0.17%   |
| JMicron Technology  | 1         | 2      | 0.17%   |
| Intenso             | 1         | 1      | 0.17%   |
| BIWIN               | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |
| Unknown             | 1         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 499       | 824    | 35.59%  |
| NVMe    | 452       | 684    | 32.24%  |
| HDD     | 389       | 867    | 27.75%  |
| MMC     | 45        | 58     | 3.21%   |
| Unknown | 17        | 19     | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 693       | 1589   | 54.74%  |
| NVMe | 451       | 682    | 35.62%  |
| SAS  | 77        | 123    | 6.08%   |
| MMC  | 45        | 58     | 3.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 549       | 905    | 56.6%   |
| 0.51-1.0   | 234       | 353    | 24.12%  |
| 1.01-2.0   | 74        | 150    | 7.63%   |
| 3.01-4.0   | 42        | 76     | 4.33%   |
| 2.01-3.0   | 34        | 90     | 3.51%   |
| 4.01-10.0  | 32        | 111    | 3.3%    |
| 10.01-20.0 | 5         | 6      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 326       | 29.08%  |
| 251-500        | 231       | 20.61%  |
| 501-1000       | 147       | 13.11%  |
| 1001-2000      | 96        | 8.56%   |
| More than 3000 | 93        | 8.3%    |
| 1-20           | 83        | 7.4%    |
| 51-100         | 47        | 4.19%   |
| 2001-3000      | 40        | 3.57%   |
| Unknown        | 30        | 2.68%   |
| 21-50          | 28        | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 423       | 35.91%  |
| 21-50          | 168       | 14.26%  |
| 101-250        | 150       | 12.73%  |
| 51-100         | 136       | 11.54%  |
| 251-500        | 93        | 7.89%   |
| 501-1000       | 69        | 5.86%   |
| 1001-2000      | 51        | 4.33%   |
| More than 3000 | 43        | 3.65%   |
| Unknown        | 30        | 2.55%   |
| 2001-3000      | 14        | 1.19%   |
| 0              | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 2.27%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 2         | 5      | 2.27%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 2      | 2.27%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 2.27%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 2.27%   |
| Hitachi HTS543216L9SA00 160GB         | 2         | 2      | 2.27%   |
| Hitachi HDS722020ALA330 2TB           | 2         | 2      | 2.27%   |
| WDC WD800JB-00CRA1 80GB               | 1         | 1      | 1.14%   |
| WDC WD800BB-00CAA1 80GB               | 1         | 1      | 1.14%   |
| WDC WD6400AAKS-75A7B0 640GB           | 1         | 2      | 1.14%   |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 1.14%   |
| WDC WD5000AAJS-00YFA0 500GB           | 1         | 1      | 1.14%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 4      | 1.14%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1         | 1      | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.14%   |
| WDC WD10EALX-009BA0 1TB               | 1         | 1      | 1.14%   |
| WDC WD10EADS-114BB1 1TB               | 1         | 1      | 1.14%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 1.14%   |
| WDC WD Blue SA510 M.2 2280 1000GB SSD | 1         | 1      | 1.14%   |
| Toshiba MK5055GSX 500GB               | 1         | 3      | 1.14%   |
| Toshiba HDWD110 1TB                   | 1         | 1      | 1.14%   |
| SK hynix SH920 2.5 7MM 128GB SSD      | 1         | 1      | 1.14%   |
| SK hynix SC210 2.5 7MM 256GB SSD      | 1         | 1      | 1.14%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 1.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.14%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 1.14%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.14%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 1.14%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.14%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 1.14%   |
| Seagate ST4000VN008-2DR166 4TB        | 1         | 1      | 1.14%   |
| Seagate ST4000LM024-2AN17V 4TB        | 1         | 1      | 1.14%   |
| Seagate ST3500630AS 500GB             | 1         | 1      | 1.14%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.14%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.14%   |
| Seagate ST3000DM008-2DM166 3TB        | 1         | 1      | 1.14%   |
| Seagate ST3000DM001-1CH166 3TB        | 1         | 18     | 1.14%   |
| Seagate ST2000DX002-2DV164 2TB        | 1         | 2      | 1.14%   |
| Seagate ST2000DM001-1E6164 2TB        | 1         | 1      | 1.14%   |
| Seagate ST1000LM014-SSHD-8GB          | 1         | 1      | 1.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 40     | 24.42%  |
| WDC                 | 17        | 25     | 19.77%  |
| Hitachi             | 9         | 10     | 10.47%  |
| Intel               | 7         | 9      | 8.14%   |
| Samsung Electronics | 5         | 5      | 5.81%   |
| SK hynix            | 4         | 4      | 4.65%   |
| Micron Technology   | 3         | 6      | 3.49%   |
| LITEON              | 3         | 3      | 3.49%   |
| Kingston            | 3         | 4      | 3.49%   |
| HGST                | 3         | 4      | 3.49%   |
| Toshiba             | 2         | 4      | 2.33%   |
| SanDisk             | 2         | 2      | 2.33%   |
| Crucial             | 2         | 2      | 2.33%   |
| Corsair             | 2         | 3      | 2.33%   |
| OCZ                 | 1         | 1      | 1.16%   |
| Lenovo              | 1         | 1      | 1.16%   |
| Apple               | 1         | 1      | 1.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 40     | 39.62%  |
| WDC                 | 16        | 24     | 30.19%  |
| Hitachi             | 9         | 10     | 16.98%  |
| HGST                | 3         | 4      | 5.66%   |
| Toshiba             | 2         | 4      | 3.77%   |
| Samsung Electronics | 2         | 2      | 3.77%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 84     | 60.24%  |
| SSD  | 26        | 31     | 31.33%  |
| NVMe | 7         | 9      | 8.43%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB    | 3         | 3      | 75%     |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Apple    | 3         | 3      | 75%     |
| Kingston | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 624       | 1366   | 53.93%  |
| Works    | 448       | 958    | 38.72%  |
| Malfunc  | 81        | 124    | 7%      |
| Failed   | 4         | 4      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 657       | 46.3%   |
| AMD                              | 207       | 14.59%  |
| Samsung Electronics              | 196       | 13.81%  |
| SanDisk                          | 70        | 4.93%   |
| Kingston Technology Company      | 45        | 3.17%   |
| SK hynix                         | 40        | 2.82%   |
| Toshiba America Info Systems     | 36        | 2.54%   |
| Phison Electronics               | 34        | 2.4%    |
| ASMedia Technology               | 24        | 1.69%   |
| Micron Technology                | 20        | 1.41%   |
| Nvidia                           | 12        | 0.85%   |
| LSI Logic / Symbios Logic        | 12        | 0.85%   |
| Broadcom / LSI                   | 10        | 0.7%    |
| KIOXIA                           | 8         | 0.56%   |
| Marvell Technology Group         | 7         | 0.49%   |
| Micron/Crucial Technology        | 6         | 0.42%   |
| JMicron Technology               | 6         | 0.42%   |
| Lenovo                           | 5         | 0.35%   |
| ADATA Technology                 | 5         | 0.35%   |
| Lite-On Technology               | 4         | 0.28%   |
| Seagate Technology               | 3         | 0.21%   |
| Union Memory (Shenzhen)          | 2         | 0.14%   |
| Solid State Storage Technology   | 2         | 0.14%   |
| Silicon Motion                   | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Silicon Image                    | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |
| 3ware                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 140       | 8.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 91        | 5.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 61        | 3.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 59        | 3.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 44        | 2.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 40        | 2.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 40        | 2.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 36        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 35        | 2.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 32        | 2.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 30        | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 29        | 1.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 25        | 1.58%   |
| Intel SATA Controller [RAID mode]                                              | 24        | 1.51%   |
| AMD 500 Series Chipset SATA Controller                                         | 24        | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 23        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 22        | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 21        | 1.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 20        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 20        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 20        | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 17        | 1.07%   |
| Kingston Company A2000 NVMe SSD                                                | 17        | 1.07%   |
| Intel SSD 660P Series                                                          | 17        | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 17        | 1.07%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 16        | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 16        | 1.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 15        | 0.95%   |
| Phison E12 NVMe Controller                                                     | 15        | 0.95%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 15        | 0.95%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 15        | 0.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 0.95%   |
| Samsung NVMe SSD Controller 980                                                | 14        | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                               | 14        | 0.88%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 12        | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 12        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 12        | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12        | 0.76%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 11        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 765       | 54.53%  |
| NVMe | 450       | 32.07%  |
| RAID | 108       | 7.7%    |
| IDE  | 69        | 4.92%   |
| SAS  | 6         | 0.43%   |
| SCSI | 5         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 791       | 75.05%  |
| AMD      | 252       | 23.91%  |
| ARM      | 10        | 0.95%   |
| QUALCOMM | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 1.98%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 1.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 14        | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.23%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 13        | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 12        | 1.13%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 12        | 1.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 10        | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 0.95%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 10        | 0.95%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 0.85%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 9         | 0.85%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 9         | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor       | 9         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 8         | 0.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 8         | 0.76%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 8         | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 8         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.66%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 7         | 0.66%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 7         | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 0.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 0.66%   |
| ARM Processor                           | 7         | 0.66%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 7         | 0.66%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 7         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 0.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 6         | 0.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 6         | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 6         | 0.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 6         | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 6         | 0.57%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 6         | 0.57%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 6         | 0.57%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz     | 5         | 0.47%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 5         | 0.47%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 5         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 279       | 26.42%  |
| Intel Core i5           | 253       | 23.96%  |
| Other                   | 74        | 7.01%   |
| AMD Ryzen 7             | 64        | 6.06%   |
| AMD Ryzen 5             | 55        | 5.21%   |
| Intel Core i3           | 48        | 4.55%   |
| AMD Ryzen 9             | 37        | 3.5%    |
| Intel Xeon              | 30        | 2.84%   |
| Intel Celeron           | 27        | 2.56%   |
| Intel Core i9           | 18        | 1.7%    |
| Intel Pentium           | 16        | 1.52%   |
| Intel Core 2 Duo        | 16        | 1.52%   |
| Intel Atom              | 11        | 1.04%   |
| AMD FX                  | 11        | 1.04%   |
| AMD Ryzen 3             | 7         | 0.66%   |
| AMD Athlon 64 X2        | 7         | 0.66%   |
| AMD A8                  | 7         | 0.66%   |
| Intel Core 2            | 6         | 0.57%   |
| AMD Ryzen 7 PRO         | 6         | 0.57%   |
| AMD A10                 | 6         | 0.57%   |
| Intel Pentium Dual-Core | 5         | 0.47%   |
| Intel Genuine           | 5         | 0.47%   |
| AMD A6                  | 5         | 0.47%   |
| AMD Ryzen 5 PRO         | 4         | 0.38%   |
| AMD Phenom II X4        | 4         | 0.38%   |
| Intel Xeon Silver       | 3         | 0.28%   |
| AMD Ryzen Threadripper  | 3         | 0.28%   |
| AMD E2                  | 3         | 0.28%   |
| AMD E                   | 3         | 0.28%   |
| AMD Athlon              | 3         | 0.28%   |
| AMD A4                  | 3         | 0.28%   |
| Intel Pentium Silver    | 2         | 0.19%   |
| Intel Core m7           | 2         | 0.19%   |
| AMD Turion 64 X2 Mobile | 2         | 0.19%   |
| AMD Ryzen 3 PRO         | 2         | 0.19%   |
| AMD Phenom II           | 2         | 0.19%   |
| AMD E1                  | 2         | 0.19%   |
| AMD Dual Core Opteron   | 2         | 0.19%   |
| AMD Athlon II X4        | 2         | 0.19%   |
| AMD Athlon II           | 2         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 367       | 34.62%  |
| 2      | 354       | 33.4%   |
| 6      | 134       | 12.64%  |
| 8      | 100       | 9.43%   |
| 12     | 34        | 3.21%   |
| 16     | 17        | 1.6%    |
| 1      | 17        | 1.6%    |
| 10     | 11        | 1.04%   |
| 14     | 7         | 0.66%   |
| 3      | 7         | 0.66%   |
| 20     | 4         | 0.38%   |
| 28     | 3         | 0.28%   |
| 32     | 2         | 0.19%   |
| 40     | 1         | 0.09%   |
| 24     | 1         | 0.09%   |
| 18     | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1036      | 98.2%   |
| 2      | 18        | 1.71%   |
| 4      | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 801       | 75.42%  |
| 1      | 259       | 24.39%  |
| 8      | 2         | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1027      | 97.35%  |
| Unknown        | 20        | 1.9%    |
| 32-bit         | 6         | 0.57%   |
| 64-bit         | 2         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 346       | 31.31%  |
| 0x306a9    | 47        | 4.25%   |
| 0x306c3    | 41        | 3.71%   |
| 0x206a7    | 41        | 3.71%   |
| 0x906ea    | 37        | 3.35%   |
| 0x506e3    | 33        | 2.99%   |
| 0x806ea    | 32        | 2.9%    |
| 0x406e3    | 29        | 2.62%   |
| 0x40651    | 26        | 2.35%   |
| 0x806ec    | 23        | 2.08%   |
| 0x906e9    | 22        | 1.99%   |
| 0x806e9    | 22        | 1.99%   |
| 0x08701021 | 21        | 1.9%    |
| 0x306d4    | 20        | 1.81%   |
| 0x1067a    | 15        | 1.36%   |
| 0x806c1    | 14        | 1.27%   |
| 0x20655    | 13        | 1.18%   |
| 0x08600106 | 12        | 1.09%   |
| 0xa0652    | 11        | 1%      |
| 0x906a3    | 10        | 0.9%    |
| 0x306f2    | 10        | 0.9%    |
| 0x08701013 | 9         | 0.81%   |
| 0x010000c8 | 9         | 0.81%   |
| 0x906ed    | 8         | 0.72%   |
| 0x806eb    | 8         | 0.72%   |
| 0x0a601203 | 8         | 0.72%   |
| 0x0a201016 | 8         | 0.72%   |
| 0x806d1    | 7         | 0.63%   |
| 0x0a50000c | 7         | 0.63%   |
| 0x0800820d | 7         | 0.63%   |
| 0x20652    | 6         | 0.54%   |
| 0x0a201009 | 6         | 0.54%   |
| 0x06001119 | 6         | 0.54%   |
| 0x06000852 | 6         | 0.54%   |
| 0x706e5    | 5         | 0.45%   |
| 0x406f1    | 5         | 0.45%   |
| 0x206d7    | 5         | 0.45%   |
| 0x0a20120a | 5         | 0.45%   |
| 0x0a201204 | 5         | 0.45%   |
| 0x08600104 | 5         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 212       | 20.02%  |
| Haswell          | 110       | 10.39%  |
| Skylake          | 99        | 9.35%   |
| IvyBridge        | 69        | 6.52%   |
| Zen 2            | 67        | 6.33%   |
| SandyBridge      | 59        | 5.57%   |
| Zen 3            | 48        | 4.53%   |
| Unknown          | 40        | 3.78%   |
| Broadwell        | 39        | 3.68%   |
| Zen+             | 28        | 2.64%   |
| Westmere         | 27        | 2.55%   |
| TigerLake        | 23        | 2.17%   |
| Alderlake Hybrid | 23        | 2.17%   |
| Penryn           | 22        | 2.08%   |
| Zen              | 21        | 1.98%   |
| CometLake        | 21        | 1.98%   |
| Piledriver       | 18        | 1.7%    |
| Icelake          | 17        | 1.61%   |
| Silvermont       | 14        | 1.32%   |
| K8 Hammer        | 14        | 1.32%   |
| K10              | 14        | 1.32%   |
| Core             | 12        | 1.13%   |
| Goldmont plus    | 10        | 0.94%   |
| Nehalem          | 7         | 0.66%   |
| Bonnell          | 7         | 0.66%   |
| Excavator        | 6         | 0.57%   |
| Goldmont         | 5         | 0.47%   |
| Bobcat           | 5         | 0.47%   |
| P6               | 4         | 0.38%   |
| Bulldozer        | 4         | 0.38%   |
| Steamroller      | 3         | 0.28%   |
| Puma             | 3         | 0.28%   |
| K10 Llano        | 3         | 0.28%   |
| Tremont          | 2         | 0.19%   |
| Jaguar           | 2         | 0.19%   |
| NetBurst         | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 602       | 48.39%  |
| Nvidia                     | 371       | 29.82%  |
| AMD                        | 254       | 20.42%  |
| Matrox Electronics Systems | 16        | 1.29%   |
| ASPEED Technology          | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 46        | 3.63%   |
| Intel UHD Graphics 620                                                      | 41        | 3.24%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 40        | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 37        | 2.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 34        | 2.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 32        | 2.53%   |
| Intel HD Graphics 620                                                       | 30        | 2.37%   |
| AMD Renoir                                                                  | 28        | 2.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 27        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 24        | 1.89%   |
| Intel HD Graphics 530                                                       | 24        | 1.89%   |
| Intel HD Graphics 5500                                                      | 22        | 1.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 21        | 1.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20        | 1.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 19        | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                         | 16        | 1.26%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 15        | 1.18%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 14        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 14        | 1.1%    |
| Intel HD Graphics 630                                                       | 13        | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 13        | 1.03%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 13        | 1.03%   |
| Nvidia GP108M [GeForce MX150]                                               | 12        | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12        | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 12        | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 12        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 9         | 0.71%   |
| Matrox Electronics Systems G200eR2                                          | 9         | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9         | 0.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 9         | 0.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9         | 0.71%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9         | 0.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 8         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8         | 0.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 7         | 0.55%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7         | 0.55%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 7         | 0.55%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 424       | 39.92%  |
| 1 x AMD              | 204       | 19.21%  |
| 1 x Nvidia           | 200       | 18.83%  |
| Intel + Nvidia       | 150       | 14.12%  |
| Intel + AMD          | 21        | 1.98%   |
| 1 x Matrox           | 15        | 1.41%   |
| AMD + Nvidia         | 15        | 1.41%   |
| 2 x AMD              | 14        | 1.32%   |
| Other                | 13        | 1.22%   |
| 2 x Nvidia           | 3         | 0.28%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.09%   |
| Nvidia + Matrox      | 1         | 0.09%   |
| Nvidia + ASPEED      | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 798       | 74.23%  |
| Proprietary | 230       | 21.4%   |
| Unknown     | 47        | 4.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 635       | 58.85%  |
| 1.01-2.0   | 114       | 10.57%  |
| 0.01-0.5   | 88        | 8.16%   |
| 7.01-8.0   | 68        | 6.3%    |
| 3.01-4.0   | 63        | 5.84%   |
| 0.51-1.0   | 41        | 3.8%    |
| 5.01-6.0   | 26        | 2.41%   |
| 8.01-16.0  | 26        | 2.41%   |
| 2.01-3.0   | 12        | 1.11%   |
| 16.01-24.0 | 4         | 0.37%   |
| 4.01-5.0   | 2         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 172       | 14.17%  |
| AU Optronics            | 126       | 10.38%  |
| LG Display              | 118       | 9.72%   |
| Chimei Innolux          | 91        | 7.5%    |
| Dell                    | 83        | 6.84%   |
| BOE                     | 74        | 6.1%    |
| BenQ                    | 52        | 4.28%   |
| AOC                     | 52        | 4.28%   |
| Acer                    | 43        | 3.54%   |
| Lenovo                  | 37        | 3.05%   |
| Hewlett-Packard         | 36        | 2.97%   |
| Ancor Communications    | 36        | 2.97%   |
| Sharp                   | 35        | 2.88%   |
| Philips                 | 35        | 2.88%   |
| Apple                   | 25        | 2.06%   |
| ASUSTek Computer        | 19        | 1.57%   |
| InfoVision              | 18        | 1.48%   |
| Goldstar                | 18        | 1.48%   |
| Chi Mei Optoelectronics | 11        | 0.91%   |
| NEC Computers           | 10        | 0.82%   |
| CSO                     | 8         | 0.66%   |
| JDI                     | 7         | 0.58%   |
| Sony                    | 6         | 0.49%   |
| PANDA                   | 6         | 0.49%   |
| Panasonic               | 6         | 0.49%   |
| Grundig                 | 6         | 0.49%   |
| Unknown                 | 5         | 0.41%   |
| Eizo                    | 5         | 0.41%   |
| LG Electronics          | 4         | 0.33%   |
| Iiyama                  | 4         | 0.33%   |
| HVR                     | 4         | 0.33%   |
| Fujitsu Siemens         | 4         | 0.33%   |
| VOXICON                 | 3         | 0.25%   |
| ViewSonic               | 3         | 0.25%   |
| Vestel Elektronik       | 3         | 0.25%   |
| Gigabyte Technology     | 3         | 0.25%   |
| Denver                  | 3         | 0.25%   |
| AUS                     | 3         | 0.25%   |
| Toshiba                 | 2         | 0.16%   |
| MSI                     | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 7         | 0.55%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.47%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 6         | 0.47%   |
| Grundig WXGA GRU4448 1600x1200                                        | 6         | 0.47%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 6         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 6         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.47%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 6         | 0.47%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 5         | 0.39%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 5         | 0.39%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch            | 5         | 0.39%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                    | 5         | 0.39%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 5         | 0.39%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 5         | 0.39%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch  | 4         | 0.32%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 4         | 0.32%   |
| NEC Computers P403 NEC692B 1920x1080 886x498mm 40.0-inch              | 4         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 4         | 0.32%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.32%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 4         | 0.32%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 4         | 0.32%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                     | 4         | 0.32%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                 | 4         | 0.32%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 4         | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.32%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 4         | 0.32%   |
| AOC 2475W AOC2475 1920x1080 527x296mm 23.8-inch                       | 4         | 0.32%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 4         | 0.32%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch | 4         | 0.32%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 3         | 0.24%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.24%   |
| Sony TV SNYEE01 1920x1080                                             | 3         | 0.24%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.24%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.24%   |
| Samsung Electronics SyncMaster SAM043F 1920x1200 518x324mm 24.1-inch  | 3         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 529       | 45.37%  |
| 3840x2160 (4K)     | 122       | 10.46%  |
| 1366x768 (WXGA)    | 118       | 10.12%  |
| 2560x1440 (QHD)    | 88        | 7.55%   |
| 1920x1200 (WUXGA)  | 55        | 4.72%   |
| 1600x900 (HD+)     | 35        | 3%      |
| 3440x1440          | 32        | 2.74%   |
| 1280x800 (WXGA)    | 16        | 1.37%   |
| 1680x1050 (WSXGA+) | 15        | 1.29%   |
| Unknown            | 15        | 1.29%   |
| 3840x1080          | 13        | 1.11%   |
| 2560x1600          | 13        | 1.11%   |
| 1280x1024 (SXGA)   | 13        | 1.11%   |
| 2880x1800          | 11        | 0.94%   |
| 1440x900 (WXGA+)   | 8         | 0.69%   |
| 3840x2400          | 7         | 0.6%    |
| 3840x1600          | 7         | 0.6%    |
| 3000x2000          | 7         | 0.6%    |
| 1600x1200          | 7         | 0.6%    |
| 2560x1080          | 6         | 0.51%   |
| 2160x1440          | 6         | 0.51%   |
| 1360x768           | 5         | 0.43%   |
| 2160x1200          | 4         | 0.34%   |
| 1024x600           | 4         | 0.34%   |
| 2288x1287          | 3         | 0.26%   |
| 1920x540           | 3         | 0.26%   |
| 5120x1440          | 2         | 0.17%   |
| 4480x1440          | 2         | 0.17%   |
| 3200x1800 (QHD+)   | 2         | 0.17%   |
| 1280x720 (HD)      | 2         | 0.17%   |
| 9600x2160          | 1         | 0.09%   |
| 7680x1440          | 1         | 0.09%   |
| 7680x1080          | 1         | 0.09%   |
| 6880x1440          | 1         | 0.09%   |
| 5760x2160          | 1         | 0.09%   |
| 5520x1080          | 1         | 0.09%   |
| 5360x1440          | 1         | 0.09%   |
| 3840x1200          | 1         | 0.09%   |
| 3840x1100          | 1         | 0.09%   |
| 3840x1024          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 229       | 18.96%  |
| 27      | 147       | 12.17%  |
| 24      | 141       | 11.67%  |
| 13      | 137       | 11.34%  |
| 14      | 126       | 10.43%  |
| Unknown | 67        | 5.55%   |
| 23      | 47        | 3.89%   |
| 17      | 46        | 3.81%   |
| 12      | 38        | 3.15%   |
| 34      | 32        | 2.65%   |
| 31      | 27        | 2.24%   |
| 21      | 16        | 1.32%   |
| 84      | 15        | 1.24%   |
| 22      | 13        | 1.08%   |
| 48      | 10        | 0.83%   |
| 19      | 10        | 0.83%   |
| 54      | 9         | 0.75%   |
| 25      | 9         | 0.75%   |
| 40      | 7         | 0.58%   |
| 37      | 7         | 0.58%   |
| 32      | 7         | 0.58%   |
| 20      | 7         | 0.58%   |
| 72      | 6         | 0.5%    |
| 16      | 6         | 0.5%    |
| 11      | 5         | 0.41%   |
| 43      | 4         | 0.33%   |
| 35      | 4         | 0.33%   |
| 142     | 3         | 0.25%   |
| 39      | 3         | 0.25%   |
| 26      | 3         | 0.25%   |
| 18      | 3         | 0.25%   |
| 10      | 3         | 0.25%   |
| 65      | 2         | 0.17%   |
| 60      | 2         | 0.17%   |
| 55      | 2         | 0.17%   |
| 46      | 2         | 0.17%   |
| 42      | 2         | 0.17%   |
| 36      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |
| 49      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 415       | 35.44%  |
| 501-600        | 294       | 25.11%  |
| 201-300        | 122       | 10.42%  |
| Unknown        | 67        | 5.72%   |
| 351-400        | 65        | 5.55%   |
| 601-700        | 49        | 4.18%   |
| 701-800        | 42        | 3.59%   |
| 401-500        | 36        | 3.07%   |
| 1001-1500      | 28        | 2.39%   |
| 801-900        | 23        | 1.96%   |
| 1501-2000      | 20        | 1.71%   |
| 901-1000       | 6         | 0.51%   |
| More than 2000 | 3         | 0.26%   |
| 101-200        | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 786       | 73.8%   |
| 16/10   | 127       | 11.92%  |
| Unknown | 52        | 4.88%   |
| 21/9    | 44        | 4.13%   |
| 3/2     | 20        | 1.88%   |
| 5/4     | 13        | 1.22%   |
| 32/9    | 11        | 1.03%   |
| 4/3     | 5         | 0.47%   |
| 1.00    | 3         | 0.28%   |
| 6/5     | 1         | 0.09%   |
| 3.76    | 1         | 0.09%   |
| 3.40    | 1         | 0.09%   |
| 0.80    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 225       | 18.88%  |
| 81-90          | 202       | 16.95%  |
| 201-250        | 154       | 12.92%  |
| 301-350        | 148       | 12.42%  |
| 351-500        | 75        | 6.29%   |
| Unknown        | 67        | 5.62%   |
| 71-80          | 62        | 5.2%    |
| 251-300        | 59        | 4.95%   |
| More than 1000 | 39        | 3.27%   |
| 121-130        | 38        | 3.19%   |
| 61-70          | 36        | 3.02%   |
| 501-1000       | 35        | 2.94%   |
| 151-200        | 22        | 1.85%   |
| 111-120        | 9         | 0.76%   |
| 131-140        | 7         | 0.59%   |
| 51-60          | 6         | 0.5%    |
| 41-50          | 3         | 0.25%   |
| 141-150        | 3         | 0.25%   |
| 1-40           | 1         | 0.08%   |
| 91-100         | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 367       | 31.39%  |
| 51-100        | 335       | 28.66%  |
| 101-120       | 233       | 19.93%  |
| 161-240       | 89        | 7.61%   |
| Unknown       | 67        | 5.73%   |
| More than 240 | 51        | 4.36%   |
| 1-50          | 27        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 774       | 71.14%  |
| 2     | 217       | 19.94%  |
| 0     | 55        | 5.06%   |
| 3     | 38        | 3.49%   |
| 4     | 4         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 667       | 42.24%  |
| Realtek Semiconductor                  | 424       | 26.85%  |
| Qualcomm Atheros                       | 118       | 7.47%   |
| Broadcom                               | 96        | 6.08%   |
| Broadcom Limited                       | 23        | 1.46%   |
| Sierra Wireless                        | 18        | 1.14%   |
| MediaTek                               | 17        | 1.08%   |
| Ericsson Business Mobile Networks      | 17        | 1.08%   |
| Ralink Technology                      | 15        | 0.95%   |
| NetGear                                | 15        | 0.95%   |
| Ralink                                 | 14        | 0.89%   |
| Dell                                   | 14        | 0.89%   |
| Nvidia                                 | 11        | 0.7%    |
| ASUSTek Computer                       | 11        | 0.7%    |
| Hewlett-Packard                        | 9         | 0.57%   |
| Lenovo                                 | 8         | 0.51%   |
| TP-Link                                | 7         | 0.44%   |
| Microsoft                              | 7         | 0.44%   |
| Marvell Technology Group               | 7         | 0.44%   |
| Aquantia                               | 7         | 0.44%   |
| Samsung Electronics                    | 6         | 0.38%   |
| DisplayLink                            | 6         | 0.38%   |
| Linksys                                | 5         | 0.32%   |
| Qualcomm Atheros Communications        | 4         | 0.25%   |
| Motorola PCS                           | 4         | 0.25%   |
| Microchip Technology                   | 4         | 0.25%   |
| Fibocom                                | 4         | 0.25%   |
| D-Link                                 | 4         | 0.25%   |
| Qualcomm                               | 3         | 0.19%   |
| Huawei Technologies                    | 3         | 0.19%   |
| Chu Yuen Enterprise                    | 3         | 0.19%   |
| ASIX Electronics                       | 3         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.13%   |
| Sigma Designs                          | 2         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.13%   |
| Mellanox Technologies                  | 2         | 0.13%   |
| JMicron Technology                     | 2         | 0.13%   |
| Arduino SA                             | 2         | 0.13%   |
| Winbond Electronics                    | 1         | 0.06%   |
| Wilocity                               | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 281       | 14.46%  |
| Intel Wi-Fi 6 AX200                                               | 80        | 4.12%   |
| Intel Wireless 8265 / 8275                                        | 64        | 3.29%   |
| Intel I211 Gigabit Network Connection                             | 53        | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 52        | 2.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 2.52%   |
| Intel Wireless 7265                                               | 38        | 1.96%   |
| Intel Wireless 8260                                               | 36        | 1.85%   |
| Intel Wireless 7260                                               | 30        | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 29        | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 23        | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 1.03%   |
| Intel Wireless-AC 9260                                            | 20        | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 0.98%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 17        | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 16        | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 16        | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.77%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 0.72%   |
| Intel Centrino Ultimate-N 6300                                    | 14        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.67%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.62%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 12        | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 12        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.62%   |
| Sierra Wireless EM7455                                            | 11        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 510       | 56.11%  |
| Qualcomm Atheros                | 92        | 10.12%  |
| Realtek Semiconductor           | 85        | 9.35%   |
| Broadcom                        | 66        | 7.26%   |
| Broadcom Limited                | 19        | 2.09%   |
| Sierra Wireless                 | 18        | 1.98%   |
| MediaTek                        | 17        | 1.87%   |
| Ralink Technology               | 15        | 1.65%   |
| NetGear                         | 15        | 1.65%   |
| Ralink                          | 14        | 1.54%   |
| ASUSTek Computer                | 11        | 1.21%   |
| Dell                            | 8         | 0.88%   |
| TP-Link                         | 7         | 0.77%   |
| Microsoft                       | 6         | 0.66%   |
| Qualcomm Atheros Communications | 4         | 0.44%   |
| Linksys                         | 4         | 0.44%   |
| Fibocom                         | 4         | 0.44%   |
| Qualcomm                        | 3         | 0.33%   |
| Hewlett-Packard                 | 3         | 0.33%   |
| D-Link                          | 3         | 0.33%   |
| Chu Yuen Enterprise             | 3         | 0.33%   |
| Wilocity                        | 1         | 0.11%   |
| Wacom                           | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 80        | 8.79%   |
| Intel Wireless 8265 / 8275                                     | 64        | 7.03%   |
| Intel Wireless 7265                                            | 38        | 4.18%   |
| Intel Wireless 8260                                            | 36        | 3.96%   |
| Intel Wireless 7260                                            | 30        | 3.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 2.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 21        | 2.31%   |
| Intel Wireless-AC 9260                                         | 20        | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 17        | 1.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 1.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 16        | 1.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 16        | 1.76%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 1.54%   |
| Intel Centrino Ultimate-N 6300                                 | 14        | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 1.32%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 12        | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12        | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1.32%   |
| Sierra Wireless EM7455                                         | 11        | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.1%    |
| Intel Wireless 3165                                            | 10        | 1.1%    |
| Intel Centrino Advanced-N 6235                                 | 10        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 9         | 0.99%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 9         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 0.88%   |
| Intel Wireless 3160                                            | 8         | 0.88%   |
| Intel WiFi Link 5100                                           | 8         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 7         | 0.77%   |
| Intel Centrino Wireless-N 2230                                 | 7         | 0.77%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 0.66%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 410       | 42.71%  |
| Realtek Semiconductor                  | 382       | 39.79%  |
| Broadcom                               | 48        | 5%      |
| Qualcomm Atheros                       | 43        | 4.48%   |
| Nvidia                                 | 11        | 1.15%   |
| Lenovo                                 | 8         | 0.83%   |
| Marvell Technology Group               | 7         | 0.73%   |
| Aquantia                               | 7         | 0.73%   |
| Samsung Electronics                    | 6         | 0.63%   |
| DisplayLink                            | 6         | 0.63%   |
| Broadcom Limited                       | 6         | 0.63%   |
| Huawei Technologies                    | 3         | 0.31%   |
| ASIX Electronics                       | 3         | 0.31%   |
| Mellanox Technologies                  | 2         | 0.21%   |
| JMicron Technology                     | 2         | 0.21%   |
| T & A Mobile Phones                    | 1         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| OPPO Electronics                       | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)          | 1         | 0.1%    |
| NetXen Incorporated                    | 1         | 0.1%    |
| Microsoft                              | 1         | 0.1%    |
| Microchip Technology                   | 1         | 0.1%    |
| Linksys                                | 1         | 0.1%    |
| Hewlett-Packard                        | 1         | 0.1%    |
| Google                                 | 1         | 0.1%    |
| Dell                                   | 1         | 0.1%    |
| D-Link                                 | 1         | 0.1%    |
| Cisco Systems                          | 1         | 0.1%    |
| ATEN International                     | 1         | 0.1%    |
| Apple                                  | 1         | 0.1%    |
| 3Com                                   | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 281       | 28.38%  |
| Intel I211 Gigabit Network Connection                             | 53        | 5.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 52        | 5.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 4.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 2.93%   |
| Intel Ethernet Controller I225-V                                  | 29        | 2.93%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 2.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.92%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 1.62%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.31%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 1.31%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.21%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 1.21%   |
| Intel Ethernet Connection I219-V                                  | 11        | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 0.91%   |
| Intel I210 Gigabit Network Connection                             | 8         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.71%   |
| Intel I350 Gigabit Network Connection                             | 6         | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                             | 6         | 0.61%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.51%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 889       | 50.23%  |
| WiFi     | 837       | 47.29%  |
| Modem    | 34        | 1.92%   |
| Unknown  | 10        | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 653       | 59.74%  |
| Ethernet | 439       | 40.16%  |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 600       | 56.66%  |
| 1     | 393       | 37.11%  |
| 3     | 35        | 3.31%   |
| 0     | 23        | 2.17%   |
| 4     | 5         | 0.47%   |
| 6     | 3         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 940       | 86.8%   |
| Yes  | 143       | 13.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 407       | 57.73%  |
| Broadcom                        | 49        | 6.95%   |
| Realtek Semiconductor           | 40        | 5.67%   |
| Qualcomm Atheros Communications | 29        | 4.11%   |
| Cambridge Silicon Radio         | 29        | 4.11%   |
| Apple                           | 27        | 3.83%   |
| IMC Networks                    | 23        | 3.26%   |
| ASUSTek Computer                | 21        | 2.98%   |
| Foxconn / Hon Hai               | 19        | 2.7%    |
| Lite-On Technology              | 17        | 2.41%   |
| Hewlett-Packard                 | 11        | 1.56%   |
| Dell                            | 10        | 1.42%   |
| MediaTek                        | 6         | 0.85%   |
| HTC (High Tech Computer)        | 4         | 0.57%   |
| Belkin Components               | 4         | 0.57%   |
| Realtek                         | 2         | 0.28%   |
| Marvell Semiconductor           | 2         | 0.28%   |
| Integrated System Solution      | 2         | 0.28%   |
| Ralink Technology               | 1         | 0.14%   |
| Ralink                          | 1         | 0.14%   |
| Actions                         | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 168       | 23.76%  |
| Intel AX200 Bluetooth                                                | 73        | 10.33%  |
| Intel AX201 Bluetooth                                                | 55        | 7.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 39        | 5.52%   |
| Realtek Bluetooth Radio                                              | 32        | 4.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 29        | 4.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 20        | 2.83%   |
| Intel Bluetooth Device                                               | 18        | 2.55%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 14        | 1.98%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 13        | 1.84%   |
| Intel AX210 Bluetooth                                                | 12        | 1.7%    |
| Apple Bluetooth Host Controller                                      | 12        | 1.7%    |
| IMC Networks Bluetooth Radio                                         | 10        | 1.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 10        | 1.41%   |
| Qualcomm Atheros  Bluetooth Device                                   | 9         | 1.27%   |
| Lite-On Bluetooth Device                                             | 9         | 1.27%   |
| Apple Bluetooth USB Host Controller                                  | 9         | 1.27%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 8         | 1.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 8         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 7         | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 7         | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 7         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 6         | 0.85%   |
| MediaTek Wireless_Device                                             | 5         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.71%   |
| IMC Networks Bluetooth Device                                        | 5         | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                                    | 5         | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5         | 0.71%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 0.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4         | 0.57%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                                     | 4         | 0.57%   |
| Broadcom BCM20702A0                                                  | 4         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 4         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth                                    | 3         | 0.42%   |
| Dell DW375 Bluetooth Module                                          | 3         | 0.42%   |
| Broadcom HP Portable SoftSailing                                     | 3         | 0.42%   |
| Broadcom BCM43142A0 Bluetooth Device                                 | 3         | 0.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 0.42%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 3         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 758       | 47.88%  |
| AMD                                          | 305       | 19.27%  |
| Nvidia                                       | 272       | 17.18%  |
| C-Media Electronics                          | 30        | 1.9%    |
| SteelSeries ApS                              | 19        | 1.2%    |
| Logitech                                     | 19        | 1.2%    |
| Realtek Semiconductor                        | 16        | 1.01%   |
| Kingston Technology                          | 15        | 0.95%   |
| Lenovo                                       | 12        | 0.76%   |
| GN Netcom                                    | 10        | 0.63%   |
| Blue Microphones                             | 9         | 0.57%   |
| Corsair                                      | 8         | 0.51%   |
| ASUSTek Computer                             | 8         | 0.51%   |
| Focusrite-Novation                           | 7         | 0.44%   |
| SAVITECH                                     | 6         | 0.38%   |
| Razer USA                                    | 6         | 0.38%   |
| Creative Labs                                | 6         | 0.38%   |
| Texas Instruments                            | 5         | 0.32%   |
| FiiO Electronics Technology                  | 4         | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.19%   |
| XMOS                                         | 3         | 0.19%   |
| Sony                                         | 3         | 0.19%   |
| JMTek                                        | 3         | 0.19%   |
| DCMT Technology                              | 3         | 0.19%   |
| Creative Technology                          | 3         | 0.19%   |
| Yamaha                                       | 2         | 0.13%   |
| Roland                                       | 2         | 0.13%   |
| RODE Microphones                             | 2         | 0.13%   |
| ROCCAT                                       | 2         | 0.13%   |
| Plantronics                                  | 2         | 0.13%   |
| Musical Fidelity                             | 2         | 0.13%   |
| Micro Star International                     | 2         | 0.13%   |
| M-Audio                                      | 2         | 0.13%   |
| GYROCOM C&C                                  | 2         | 0.13%   |
| Elgato Systems                               | 2         | 0.13%   |
| DSEA A/S                                     | 2         | 0.13%   |
| Asahi Kasei Microsystems                     | 2         | 0.13%   |
| ZOOM                                         | 1         | 0.06%   |
| www.hirestech.com 2012 REV 1.8               | 1         | 0.06%   |
| Sonicstar                                    | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 117       | 6.29%   |
| AMD Family 17h/19h HD Audio Controller                                     | 79        | 4.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 72        | 3.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 70        | 3.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 55        | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 51        | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 51        | 2.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 43        | 2.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 43        | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41        | 2.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 37        | 1.99%   |
| Intel 8 Series HD Audio Controller                                         | 36        | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 34        | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 32        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 31        | 1.67%   |
| Intel Broadwell-U Audio Controller                                         | 31        | 1.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 28        | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 28        | 1.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 26        | 1.4%    |
| Intel 200 Series PCH HD Audio                                              | 25        | 1.34%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 25        | 1.34%   |
| AMD FCH Azalia Controller                                                  | 24        | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 23        | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 22        | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 20        | 1.08%   |
| Nvidia GA104 High Definition Audio Controller                              | 19        | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 18        | 0.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 18        | 0.97%   |
| AMD Navi 10 HDMI Audio                                                     | 17        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 0.86%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 15        | 0.81%   |
| Realtek Semiconductor USB Audio                                            | 14        | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 14        | 0.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 0.7%    |
| Intel CM238 HD Audio Controller                                            | 13        | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 159       | 24.02%  |
| SK hynix            | 141       | 21.3%   |
| Kingston            | 95        | 14.35%  |
| Micron Technology   | 66        | 9.97%   |
| Corsair             | 57        | 8.61%   |
| Crucial             | 39        | 5.89%   |
| Unknown             | 37        | 5.59%   |
| G.Skill             | 21        | 3.17%   |
| Elpida              | 11        | 1.66%   |
| Ramaxel Technology  | 9         | 1.36%   |
| A-DATA Technology   | 8         | 1.21%   |
| Unknown (ABCD)      | 2         | 0.3%    |
| Team                | 2         | 0.3%    |
| Patriot             | 2         | 0.3%    |
| Nanya Technology    | 2         | 0.3%    |
| Unknown             | 2         | 0.3%    |
| Transcend           | 1         | 0.15%   |
| Toshiba             | 1         | 0.15%   |
| SK_Hynix            | 1         | 0.15%   |
| Hewlett-Packard     | 1         | 0.15%   |
| GSkill              | 1         | 0.15%   |
| GeIL                | 1         | 0.15%   |
| ASint Technology    | 1         | 0.15%   |
| Apacer              | 1         | 0.15%   |
| 48spaces            | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 9         | 1.29%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 7         | 1.01%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 6         | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.86%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.86%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.86%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 5         | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 5         | 0.72%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 5         | 0.72%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                      | 5         | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.72%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.72%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 5         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.58%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.58%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 4         | 0.58%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 4         | 0.58%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 4         | 0.58%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 4         | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.43%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.43%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.43%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.43%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s             | 3         | 0.43%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s             | 3         | 0.43%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.43%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 3         | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 311       | 53.25%  |
| DDR3    | 162       | 27.74%  |
| LPDDR3  | 33        | 5.65%   |
| LPDDR4  | 24        | 4.11%   |
| DDR2    | 16        | 2.74%   |
| DDR5    | 14        | 2.4%    |
| SDRAM   | 7         | 1.2%    |
| LPDDR5  | 7         | 1.2%    |
| Unknown | 7         | 1.2%    |
| DDR     | 2         | 0.34%   |
| DRAM    | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 306       | 51.95%  |
| DIMM         | 203       | 34.47%  |
| Row Of Chips | 64        | 10.87%  |
| Chip         | 11        | 1.87%   |
| Unknown      | 4         | 0.68%   |
| FB-DIMM      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 274       | 44.12%  |
| 4096  | 151       | 24.32%  |
| 16384 | 133       | 21.42%  |
| 2048  | 33        | 5.31%   |
| 32768 | 22        | 3.54%   |
| 1024  | 6         | 0.97%   |
| 512   | 1         | 0.16%   |
| 128   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 107       | 16.88%  |
| 2667    | 97        | 15.3%   |
| 3200    | 77        | 12.15%  |
| 2133    | 61        | 9.62%   |
| 2400    | 51        | 8.04%   |
| 1333    | 26        | 4.1%    |
| 3600    | 24        | 3.79%   |
| 1867    | 20        | 3.15%   |
| 3400    | 16        | 2.52%   |
| 1334    | 14        | 2.21%   |
| 667     | 14        | 2.21%   |
| 4267    | 10        | 1.58%   |
| 6400    | 9         | 1.42%   |
| 3000    | 8         | 1.26%   |
| 1800    | 8         | 1.26%   |
| 4800    | 6         | 0.95%   |
| 3733    | 6         | 0.95%   |
| 1067    | 6         | 0.95%   |
| 3466    | 5         | 0.79%   |
| 2666    | 5         | 0.79%   |
| 4199    | 4         | 0.63%   |
| 3533    | 4         | 0.63%   |
| 2933    | 4         | 0.63%   |
| 2800    | 4         | 0.63%   |
| 1066    | 4         | 0.63%   |
| 800     | 4         | 0.63%   |
| 8400    | 3         | 0.47%   |
| 6000    | 3         | 0.47%   |
| 3866    | 3         | 0.47%   |
| 3266    | 3         | 0.47%   |
| 3100    | 3         | 0.47%   |
| 5900    | 2         | 0.32%   |
| 5600    | 2         | 0.32%   |
| 4266    | 2         | 0.32%   |
| 4000    | 2         | 0.32%   |
| 3333    | 2         | 0.32%   |
| 3151    | 2         | 0.32%   |
| 2733    | 2         | 0.32%   |
| 2000    | 2         | 0.32%   |
| Unknown | 2         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 42.86%  |
| Brother Industries  | 5         | 35.71%  |
| Samsung Electronics | 1         | 7.14%   |
| Pantum              | 1         | 7.14%   |
| Canon               | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series            | 2         | 14.29%  |
| Samsung M2020 Series                 | 1         | 7.14%   |
| Pantum P2500W series                 | 1         | 7.14%   |
| HP Printing Support                  | 1         | 7.14%   |
| HP LaserJet Professional P 1102w     | 1         | 7.14%   |
| HP DeskJet F300 series               | 1         | 7.14%   |
| HP Deskjet 2540 series               | 1         | 7.14%   |
| Canon PIXMA MX530 Series             | 1         | 7.14%   |
| Brother QL-800 P-touch Label Printer | 1         | 7.14%   |
| Brother QL-550 printer               | 1         | 7.14%   |
| Brother PT-2450DX                    | 1         | 7.14%   |
| Brother HL-1210W series              | 1         | 7.14%   |
| Brother DCP-8085DN                   | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Canon CanoScan 9000F Mark II | 2         | 50%     |
| Canon CanoScan LiDE 200      | 1         | 25%     |
| Canon CanoScan LiDE 110      | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 151       | 21.92%  |
| IMC Networks                           | 65        | 9.43%   |
| Logitech                               | 63        | 9.14%   |
| Bison Electronics                      | 48        | 6.97%   |
| Microdia                               | 47        | 6.82%   |
| Sunplus Innovation Technology          | 40        | 5.81%   |
| Realtek Semiconductor                  | 33        | 4.79%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 3.92%   |
| Apple                                  | 27        | 3.92%   |
| Quanta                                 | 23        | 3.34%   |
| Lite-On Technology                     | 23        | 3.34%   |
| Acer                                   | 18        | 2.61%   |
| Suyin                                  | 15        | 2.18%   |
| Luxvisions Innotech Limited            | 12        | 1.74%   |
| Microsoft                              | 11        | 1.6%    |
| Lenovo                                 | 11        | 1.6%    |
| Creative Technology                    | 8         | 1.16%   |
| Alcor Micro                            | 8         | 1.16%   |
| Samsung Electronics                    | 7         | 1.02%   |
| Silicon Motion                         | 6         | 0.87%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.58%   |
| Primax Electronics                     | 4         | 0.58%   |
| Syntek                                 | 3         | 0.44%   |
| Razer USA                              | 3         | 0.44%   |
| Omnivision                             | 3         | 0.44%   |
| MacroSilicon                           | 3         | 0.44%   |
| Z-Star Microelectronics                | 2         | 0.29%   |
| Sunplus Technology                     | 2         | 0.29%   |
| Sonix Technology                       | 2         | 0.29%   |
| Ricoh                                  | 2         | 0.29%   |
| Generalplus Technology                 | 2         | 0.29%   |
| Cubeternet                             | 2         | 0.29%   |
| ALi                                    | 2         | 0.29%   |
| Y Media                                | 1         | 0.15%   |
| Technologies                           | 1         | 0.15%   |
| TANDBERG                               | 1         | 0.15%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.15%   |
| Novatek Microelectronics               | 1         | 0.15%   |
| Mustek Systems                         | 1         | 0.15%   |
| Magewell                               | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 52        | 7.41%   |
| Microdia Integrated_Webcam_HD                       | 26        | 3.7%    |
| IMC Networks Integrated Camera                      | 22        | 3.13%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 21        | 2.99%   |
| Chicony HP HD Camera                                | 15        | 2.14%   |
| Logitech HD Pro Webcam C920                         | 14        | 1.99%   |
| Sunplus Integrated_Webcam_HD                        | 13        | 1.85%   |
| Realtek Integrated_Webcam_HD                        | 12        | 1.71%   |
| Lite-On Integrated Camera                           | 11        | 1.57%   |
| Chicony HP HD Webcam                                | 11        | 1.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 11        | 1.57%   |
| Logitech C922 Pro Stream Webcam                     | 10        | 1.42%   |
| Chicony HD WebCam                                   | 10        | 1.42%   |
| Bison Integrated Camera                             | 8         | 1.14%   |
| Bison BisonCam, NB Pro                              | 8         | 1.14%   |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 1%      |
| Logitech Webcam C270                                | 7         | 1%      |
| Lite-On HP HD Camera                                | 7         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 7         | 1%      |
| Bison SunplusIT Integrated Camera                   | 7         | 1%      |
| Acer Integrated Camera                              | 7         | 1%      |
| Lenovo Integrated Webcam [R5U877]                   | 6         | 0.85%   |
| Chicony Integrated HP HD Webcam                     | 6         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 6         | 0.85%   |
| Bison HD Webcam                                     | 6         | 0.85%   |
| Apple FaceTime HD Camera (Built-in)                 | 6         | 0.85%   |
| Sunplus Laptop Integrated Webcam HD                 | 5         | 0.71%   |
| Sunplus HD WebCam                                   | 5         | 0.71%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.71%   |
| Quanta HP TrueVision HD Camera                      | 5         | 0.71%   |
| Quanta HP HD Camera                                 | 5         | 0.71%   |
| Quanta HD User Facing                               | 5         | 0.71%   |
| Microsoft LifeCam Cinema                            | 5         | 0.71%   |
| Microdia Integrated Webcam                          | 5         | 0.71%   |
| Chicony HP Wide Vision HD Camera                    | 5         | 0.71%   |
| Chicony EasyCamera                                  | 5         | 0.71%   |
| Bison Lenovo Integrated Webcam                      | 5         | 0.71%   |
| Sunplus Asus Webcam                                 | 4         | 0.57%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 4         | 0.57%   |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 71        | 42.26%  |
| Synaptics                          | 53        | 31.55%  |
| Upek                               | 15        | 8.93%   |
| Shenzhen Goodix Technology         | 13        | 7.74%   |
| Elan Microelectronics              | 6         | 3.57%   |
| Samsung Electronics                | 3         | 1.79%   |
| LighTuning Technology              | 3         | 1.79%   |
| AuthenTec                          | 3         | 1.79%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.6%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 11.9%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 8.93%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 8.33%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 5.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 4.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 3.57%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 3.57%   |
| Validity Sensors VFS491                                                    | 5         | 2.98%   |
| Synaptics WBDI                                                             | 5         | 2.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 2.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 2.38%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.79%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.79%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 1.79%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.19%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.19%   |
| Synaptics UWP WBDI                                                         | 2         | 1.19%   |
| Synaptics  WBDI                                                            | 2         | 1.19%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.19%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.19%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 1.19%   |
| AuthenTec AES2810                                                          | 2         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.6%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.6%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.6%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.6%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.6%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.6%    |
| AuthenTec AES1600                                                          | 1         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 33        | 39.29%  |
| Alcor Micro           | 33        | 39.29%  |
| Upek                  | 8         | 9.52%   |
| Lenovo                | 5         | 5.95%   |
| OmniKey               | 2         | 2.38%   |
| Yubico.com            | 1         | 1.19%   |
| Hewlett-Packard       | 1         | 1.19%   |
| Gemalto (was Gemplus) | 1         | 1.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 39.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 11.9%   |
| Broadcom 5880                                                                | 10        | 11.9%   |
| Broadcom 58200                                                               | 9         | 10.71%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 9.52%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.95%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.76%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 2.38%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 1.19%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.19%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 686       | 63.4%   |
| 1     | 297       | 27.45%  |
| 2     | 79        | 7.3%    |
| 3     | 18        | 1.66%   |
| 7     | 1         | 0.09%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 167       | 34.08%  |
| Graphics card            | 85        | 17.35%  |
| Chipcard                 | 70        | 14.29%  |
| Net/wireless             | 59        | 12.04%  |
| Unassigned class         | 24        | 4.9%    |
| Multimedia controller    | 22        | 4.49%   |
| Camera                   | 15        | 3.06%   |
| Communication controller | 9         | 1.84%   |
| Sound                    | 7         | 1.43%   |
| Card reader              | 7         | 1.43%   |
| Bluetooth                | 7         | 1.43%   |
| Storage                  | 5         | 1.02%   |
| Net/ethernet             | 5         | 1.02%   |
| Wireless                 | 4         | 0.82%   |
| Modem                    | 2         | 0.41%   |
| Storage/raid             | 1         | 0.2%    |
| Dvb card                 | 1         | 0.2%    |

