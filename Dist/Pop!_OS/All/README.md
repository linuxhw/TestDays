Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 14992

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| System76      | Oryx Pro                    | Notebook    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Unknown       | X99H                        | Desktop     | [61c57cb006](https://linux-hardware.org/?probe=61c57cb006) | Jan 01, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| ASUSTek       | P6T                         | Desktop     | [7b5a14566d](https://linux-hardware.org/?probe=7b5a14566d) | Jan 01, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [58557ae7c7](https://linux-hardware.org/?probe=58557ae7c7) | Jan 01, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [eb47ce9900](https://linux-hardware.org/?probe=eb47ce9900) | Jan 01, 2024 |
| ASUSTek       | M4N72-E                     | Desktop     | [7d21517ee3](https://linux-hardware.org/?probe=7d21517ee3) | Dec 31, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa478c5226](https://linux-hardware.org/?probe=fa478c5226) | Dec 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | Notebook    | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| Google        | Delbin                      | Notebook    | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [63fd2a4477](https://linux-hardware.org/?probe=63fd2a4477) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [faf34bf75f](https://linux-hardware.org/?probe=faf34bf75f) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | Notebook    | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b1b1057a4b](https://linux-hardware.org/?probe=b1b1057a4b) | Dec 30, 2023 |
| Acer          | SF314-71-50E8               | Notebook    | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| HP            | 802E                        | Desktop     | [a519d89c9e](https://linux-hardware.org/?probe=a519d89c9e) | Dec 29, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [e0e92720cb](https://linux-hardware.org/?probe=e0e92720cb) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | Notebook    | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | Notebook    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94b90795bb](https://linux-hardware.org/?probe=94b90795bb) | Dec 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [2e6989112a](https://linux-hardware.org/?probe=2e6989112a) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2d2449e5d7](https://linux-hardware.org/?probe=2d2449e5d7) | Dec 28, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [f52a281bd2](https://linux-hardware.org/?probe=f52a281bd2) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [42460d0cd3](https://linux-hardware.org/?probe=42460d0cd3) | Dec 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [61116b6285](https://linux-hardware.org/?probe=61116b6285) | Dec 27, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [0927068d89](https://linux-hardware.org/?probe=0927068d89) | Dec 27, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [77d5e43585](https://linux-hardware.org/?probe=77d5e43585) | Dec 26, 2023 |
| SZMZ          | X99-S3                      | Desktop     | [85c9abf0f3](https://linux-hardware.org/?probe=85c9abf0f3) | Dec 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [e63c96ff95](https://linux-hardware.org/?probe=e63c96ff95) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [96aa7493e0](https://linux-hardware.org/?probe=96aa7493e0) | Dec 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [634e14ff4c](https://linux-hardware.org/?probe=634e14ff4c) | Dec 25, 2023 |
| MicroByte     | ezbook                      | Notebook    | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f385a26e94](https://linux-hardware.org/?probe=f385a26e94) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [744adae48d](https://linux-hardware.org/?probe=744adae48d) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [325376d316](https://linux-hardware.org/?probe=325376d316) | Dec 25, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0620... | Notebook    | [5cceadde0c](https://linux-hardware.org/?probe=5cceadde0c) | Dec 25, 2023 |
| PC Special... | N150CU                      | Notebook    | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f9cf1edcee](https://linux-hardware.org/?probe=f9cf1edcee) | Dec 24, 2023 |
| PC Special... | GK7NP5R                     | Notebook    | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8decde512f](https://linux-hardware.org/?probe=8decde512f) | Dec 23, 2023 |
| System76      | Serval WS                   | Notebook    | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| System76      | Gazelle                     | Notebook    | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [00781519db](https://linux-hardware.org/?probe=00781519db) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [de502eec48](https://linux-hardware.org/?probe=de502eec48) | Dec 22, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [ec6847b7f2](https://linux-hardware.org/?probe=ec6847b7f2) | Dec 22, 2023 |
| Gigabyte      | H610M S2H                   | Desktop     | [6c554a9668](https://linux-hardware.org/?probe=6c554a9668) | Dec 22, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [bf0861748d](https://linux-hardware.org/?probe=bf0861748d) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9515cb0c90](https://linux-hardware.org/?probe=9515cb0c90) | Dec 22, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [b49d16daf5](https://linux-hardware.org/?probe=b49d16daf5) | Dec 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1b8100314e](https://linux-hardware.org/?probe=1b8100314e) | Dec 21, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ecefa48588](https://linux-hardware.org/?probe=ecefa48588) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| DEXP          | Atlas M15-I3W302            | Notebook    | [176dd6f77a](https://linux-hardware.org/?probe=176dd6f77a) | Dec 20, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [67098aebca](https://linux-hardware.org/?probe=67098aebca) | Dec 20, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9a3cef62bc](https://linux-hardware.org/?probe=9a3cef62bc) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [d2ed93003e](https://linux-hardware.org/?probe=d2ed93003e) | Dec 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Dell          | Latitude E5270              | Notebook    | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| System76      | Pangolin                    | Notebook    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [86b686b3cf](https://linux-hardware.org/?probe=86b686b3cf) | Dec 19, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [047feb8e76](https://linux-hardware.org/?probe=047feb8e76) | Dec 19, 2023 |
| Biostar       | A320MH                      | Desktop     | [9ec714a02b](https://linux-hardware.org/?probe=9ec714a02b) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [29169b6700](https://linux-hardware.org/?probe=29169b6700) | Dec 19, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [1375b869d1](https://linux-hardware.org/?probe=1375b869d1) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [0759f6c04f](https://linux-hardware.org/?probe=0759f6c04f) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [939c3a4be6](https://linux-hardware.org/?probe=939c3a4be6) | Dec 19, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [92531d60e9](https://linux-hardware.org/?probe=92531d60e9) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [8efe53adcb](https://linux-hardware.org/?probe=8efe53adcb) | Dec 18, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [f051e1ba58](https://linux-hardware.org/?probe=f051e1ba58) | Dec 18, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [2e837d2a52](https://linux-hardware.org/?probe=2e837d2a52) | Dec 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [85358f7505](https://linux-hardware.org/?probe=85358f7505) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [825b7230bc](https://linux-hardware.org/?probe=825b7230bc) | Dec 18, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [2d78f7257c](https://linux-hardware.org/?probe=2d78f7257c) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |
| HP            | ProBook 4535s               | Notebook    | [80aa5bd12b](https://linux-hardware.org/?probe=80aa5bd12b) | Dec 17, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3a10e23529](https://linux-hardware.org/?probe=3a10e23529) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [801f62b573](https://linux-hardware.org/?probe=801f62b573) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [d16bd87505](https://linux-hardware.org/?probe=d16bd87505) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [7f32922e8f](https://linux-hardware.org/?probe=7f32922e8f) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [b9029b0475](https://linux-hardware.org/?probe=b9029b0475) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0baa198f9f](https://linux-hardware.org/?probe=0baa198f9f) | Dec 17, 2023 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | Desktop     | [47bc0a39bf](https://linux-hardware.org/?probe=47bc0a39bf) | Dec 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [b90524a691](https://linux-hardware.org/?probe=b90524a691) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [ef0c78ce49](https://linux-hardware.org/?probe=ef0c78ce49) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d227968843](https://linux-hardware.org/?probe=d227968843) | Dec 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [95deb85c40](https://linux-hardware.org/?probe=95deb85c40) | Dec 16, 2023 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [8717000b31](https://linux-hardware.org/?probe=8717000b31) | Dec 16, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [4f6031c3b2](https://linux-hardware.org/?probe=4f6031c3b2) | Dec 16, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [51a1a58859](https://linux-hardware.org/?probe=51a1a58859) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [976a5e3ec2](https://linux-hardware.org/?probe=976a5e3ec2) | Dec 16, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [7da400b028](https://linux-hardware.org/?probe=7da400b028) | Dec 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [10f1017f04](https://linux-hardware.org/?probe=10f1017f04) | Dec 16, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [fb32a1a82e](https://linux-hardware.org/?probe=fb32a1a82e) | Dec 15, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [17fcc16842](https://linux-hardware.org/?probe=17fcc16842) | Dec 14, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9d6455339e](https://linux-hardware.org/?probe=9d6455339e) | Dec 14, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3280eaaea1](https://linux-hardware.org/?probe=3280eaaea1) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4919d10355](https://linux-hardware.org/?probe=4919d10355) | Dec 14, 2023 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b7bef0ec08](https://linux-hardware.org/?probe=b7bef0ec08) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [c132a249e4](https://linux-hardware.org/?probe=c132a249e4) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [913708c3f0](https://linux-hardware.org/?probe=913708c3f0) | Dec 13, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3f2ed65cf0](https://linux-hardware.org/?probe=3f2ed65cf0) | Dec 13, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | Notebook    | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [25a03e3488](https://linux-hardware.org/?probe=25a03e3488) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e33caa2659](https://linux-hardware.org/?probe=e33caa2659) | Dec 12, 2023 |
| AZW           | SER                         | Mini pc     | [35001d9cec](https://linux-hardware.org/?probe=35001d9cec) | Dec 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ca9ceaf4a0](https://linux-hardware.org/?probe=ca9ceaf4a0) | Dec 11, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [076e19b0aa](https://linux-hardware.org/?probe=076e19b0aa) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [efba53721c](https://linux-hardware.org/?probe=efba53721c) | Dec 11, 2023 |
| MSI           | H610M BOMBER DDR4           | Desktop     | [7ea9e34c4c](https://linux-hardware.org/?probe=7ea9e34c4c) | Dec 11, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [7b2a48d751](https://linux-hardware.org/?probe=7b2a48d751) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [90fce6c777](https://linux-hardware.org/?probe=90fce6c777) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [6c83c2bec6](https://linux-hardware.org/?probe=6c83c2bec6) | Dec 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [539d1d09fe](https://linux-hardware.org/?probe=539d1d09fe) | Dec 11, 2023 |
| System76      | Lemur Pro                   | Notebook    | [05062ae2dd](https://linux-hardware.org/?probe=05062ae2dd) | Dec 10, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [0c0de57a07](https://linux-hardware.org/?probe=0c0de57a07) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [832dd09409](https://linux-hardware.org/?probe=832dd09409) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [b17b809ccf](https://linux-hardware.org/?probe=b17b809ccf) | Dec 10, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [ad9ec5bc5b](https://linux-hardware.org/?probe=ad9ec5bc5b) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| HP            | 2AF7                        | Desktop     | [e7a6fd7a82](https://linux-hardware.org/?probe=e7a6fd7a82) | Dec 10, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [3e42bedcd3](https://linux-hardware.org/?probe=3e42bedcd3) | Dec 10, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [ef47cf6d30](https://linux-hardware.org/?probe=ef47cf6d30) | Dec 10, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [06e9cf1c8d](https://linux-hardware.org/?probe=06e9cf1c8d) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296e90c442](https://linux-hardware.org/?probe=296e90c442) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [cea0431bcb](https://linux-hardware.org/?probe=cea0431bcb) | Dec 09, 2023 |
| Razer         | Blade                       | Notebook    | [bf9ad5f7df](https://linux-hardware.org/?probe=bf9ad5f7df) | Dec 09, 2023 |
| Gigabyte      | MU92-TU0-00 01010101        | Server      | [fa219aabb0](https://linux-hardware.org/?probe=fa219aabb0) | Dec 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [f499be5e26](https://linux-hardware.org/?probe=f499be5e26) | Dec 09, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [e7d15edec4](https://linux-hardware.org/?probe=e7d15edec4) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [981334c448](https://linux-hardware.org/?probe=981334c448) | Dec 08, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [944218c6ec](https://linux-hardware.org/?probe=944218c6ec) | Dec 08, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [8c7f7f9b91](https://linux-hardware.org/?probe=8c7f7f9b91) | Dec 08, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [2499101d89](https://linux-hardware.org/?probe=2499101d89) | Dec 08, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [182fbc1464](https://linux-hardware.org/?probe=182fbc1464) | Dec 08, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [68bd979ae6](https://linux-hardware.org/?probe=68bd979ae6) | Dec 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | Notebook    | [87477ed836](https://linux-hardware.org/?probe=87477ed836) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [13080ba71b](https://linux-hardware.org/?probe=13080ba71b) | Dec 07, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [895b027832](https://linux-hardware.org/?probe=895b027832) | Dec 07, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [18c7fcf897](https://linux-hardware.org/?probe=18c7fcf897) | Dec 06, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [49e317cfc8](https://linux-hardware.org/?probe=49e317cfc8) | Dec 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [0d809d54ad](https://linux-hardware.org/?probe=0d809d54ad) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eeb3db62db](https://linux-hardware.org/?probe=eeb3db62db) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5160cc41b9](https://linux-hardware.org/?probe=5160cc41b9) | Dec 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be8fd86ad0](https://linux-hardware.org/?probe=be8fd86ad0) | Dec 05, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [4ae43e0af1](https://linux-hardware.org/?probe=4ae43e0af1) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [973530edc6](https://linux-hardware.org/?probe=973530edc6) | Dec 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [67d1badc93](https://linux-hardware.org/?probe=67d1badc93) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [1f66aaf874](https://linux-hardware.org/?probe=1f66aaf874) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [419da197bb](https://linux-hardware.org/?probe=419da197bb) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [745d537d97](https://linux-hardware.org/?probe=745d537d97) | Dec 05, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [474cae9549](https://linux-hardware.org/?probe=474cae9549) | Dec 05, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [48a8d668d9](https://linux-hardware.org/?probe=48a8d668d9) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2ace6b74e5](https://linux-hardware.org/?probe=2ace6b74e5) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b55a2ed6be](https://linux-hardware.org/?probe=b55a2ed6be) | Dec 03, 2023 |
| Acer          | Aspire A515-44G             | Notebook    | [7e41d52591](https://linux-hardware.org/?probe=7e41d52591) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c5bdb91907](https://linux-hardware.org/?probe=c5bdb91907) | Dec 03, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [1b6b67ba62](https://linux-hardware.org/?probe=1b6b67ba62) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [98567fb8e0](https://linux-hardware.org/?probe=98567fb8e0) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [00da9d31bd](https://linux-hardware.org/?probe=00da9d31bd) | Dec 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c7a7d555a6](https://linux-hardware.org/?probe=c7a7d555a6) | Dec 02, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [5568b58564](https://linux-hardware.org/?probe=5568b58564) | Dec 02, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [0714d912db](https://linux-hardware.org/?probe=0714d912db) | Dec 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [7488b95d21](https://linux-hardware.org/?probe=7488b95d21) | Dec 02, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [31ac2917e3](https://linux-hardware.org/?probe=31ac2917e3) | Dec 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [eb3b0a6afb](https://linux-hardware.org/?probe=eb3b0a6afb) | Dec 01, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [613d0fb4a0](https://linux-hardware.org/?probe=613d0fb4a0) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [53bc6eba90](https://linux-hardware.org/?probe=53bc6eba90) | Dec 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [ea481bfb9d](https://linux-hardware.org/?probe=ea481bfb9d) | Dec 01, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [b431f0a398](https://linux-hardware.org/?probe=b431f0a398) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [863d4d2b8f](https://linux-hardware.org/?probe=863d4d2b8f) | Nov 30, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | Notebook    | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [11e0af1d39](https://linux-hardware.org/?probe=11e0af1d39) | Nov 30, 2023 |
| HP            | 8299                        | Desktop     | [7d01726c17](https://linux-hardware.org/?probe=7d01726c17) | Nov 30, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e43b293d0e](https://linux-hardware.org/?probe=e43b293d0e) | Nov 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [43e0c71549](https://linux-hardware.org/?probe=43e0c71549) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [707797695c](https://linux-hardware.org/?probe=707797695c) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a05b28f5b1](https://linux-hardware.org/?probe=a05b28f5b1) | Nov 29, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| HP            | 0B40h                       | Desktop     | [9875f70785](https://linux-hardware.org/?probe=9875f70785) | Nov 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [56ad64e87a](https://linux-hardware.org/?probe=56ad64e87a) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [977a25b18b](https://linux-hardware.org/?probe=977a25b18b) | Nov 29, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [07dd4aaf53](https://linux-hardware.org/?probe=07dd4aaf53) | Nov 29, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [a193c9a207](https://linux-hardware.org/?probe=a193c9a207) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | Notebook    | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| Dell          | Precision 3550              | Notebook    | [935b0dba56](https://linux-hardware.org/?probe=935b0dba56) | Nov 28, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f502294656](https://linux-hardware.org/?probe=f502294656) | Nov 28, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [1f793dc2d3](https://linux-hardware.org/?probe=1f793dc2d3) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Dell          | Precision M4700             | Notebook    | [e63ddd94ec](https://linux-hardware.org/?probe=e63ddd94ec) | Nov 27, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [abbb97fea2](https://linux-hardware.org/?probe=abbb97fea2) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [0bc55c4101](https://linux-hardware.org/?probe=0bc55c4101) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [d6f36dff1d](https://linux-hardware.org/?probe=d6f36dff1d) | Nov 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [4fd4ea2869](https://linux-hardware.org/?probe=4fd4ea2869) | Nov 26, 2023 |
| Dell          | 0RY206                      | Desktop     | [7115b05660](https://linux-hardware.org/?probe=7115b05660) | Nov 25, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6007599bc5](https://linux-hardware.org/?probe=6007599bc5) | Nov 25, 2023 |
| MSI           | Z87-S02                     | Desktop     | [2d40c55867](https://linux-hardware.org/?probe=2d40c55867) | Nov 25, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [c6955988fb](https://linux-hardware.org/?probe=c6955988fb) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ab26a80bc5](https://linux-hardware.org/?probe=ab26a80bc5) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [6f3cf47d7d](https://linux-hardware.org/?probe=6f3cf47d7d) | Nov 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [1065af244c](https://linux-hardware.org/?probe=1065af244c) | Nov 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [904f3a4c07](https://linux-hardware.org/?probe=904f3a4c07) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4e7c1f967f](https://linux-hardware.org/?probe=4e7c1f967f) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a886bd351a](https://linux-hardware.org/?probe=a886bd351a) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [386171f14d](https://linux-hardware.org/?probe=386171f14d) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ac1dfd9609](https://linux-hardware.org/?probe=ac1dfd9609) | Nov 24, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [98b666cd95](https://linux-hardware.org/?probe=98b666cd95) | Nov 24, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [9e25aa3d8f](https://linux-hardware.org/?probe=9e25aa3d8f) | Nov 24, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [d12afced10](https://linux-hardware.org/?probe=d12afced10) | Nov 24, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3730101bfb](https://linux-hardware.org/?probe=3730101bfb) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [c3d0a3a34c](https://linux-hardware.org/?probe=c3d0a3a34c) | Nov 24, 2023 |
| HP            | 85A2                        | All in one  | [80b79f2bed](https://linux-hardware.org/?probe=80b79f2bed) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [4d256b493c](https://linux-hardware.org/?probe=4d256b493c) | Nov 23, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| HP            | 2AF7                        | Desktop     | [5594c88f44](https://linux-hardware.org/?probe=5594c88f44) | Nov 23, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [bc09939521](https://linux-hardware.org/?probe=bc09939521) | Nov 23, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [7b6e215012](https://linux-hardware.org/?probe=7b6e215012) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b6e4999e4f](https://linux-hardware.org/?probe=b6e4999e4f) | Nov 22, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [b8a0ad5987](https://linux-hardware.org/?probe=b8a0ad5987) | Nov 22, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [2720b6f6d4](https://linux-hardware.org/?probe=2720b6f6d4) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [21257dcbad](https://linux-hardware.org/?probe=21257dcbad) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [b69760e673](https://linux-hardware.org/?probe=b69760e673) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [00c164e154](https://linux-hardware.org/?probe=00c164e154) | Nov 21, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [be7c395cc7](https://linux-hardware.org/?probe=be7c395cc7) | Nov 21, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [96172d652b](https://linux-hardware.org/?probe=96172d652b) | Nov 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [03d7d46dd0](https://linux-hardware.org/?probe=03d7d46dd0) | Nov 21, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [348094cd98](https://linux-hardware.org/?probe=348094cd98) | Nov 21, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [a166dbb3cf](https://linux-hardware.org/?probe=a166dbb3cf) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [ece8c390b1](https://linux-hardware.org/?probe=ece8c390b1) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [55dac497f4](https://linux-hardware.org/?probe=55dac497f4) | Nov 20, 2023 |
| Lenovo        | ThinkPad Helix 3701CTO      | Notebook    | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f58ea2a820](https://linux-hardware.org/?probe=f58ea2a820) | Nov 20, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a4f7b1d9d3](https://linux-hardware.org/?probe=a4f7b1d9d3) | Nov 20, 2023 |
| HP            | 8054                        | Desktop     | [2ccc2c67f2](https://linux-hardware.org/?probe=2ccc2c67f2) | Nov 20, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [56cd0716d9](https://linux-hardware.org/?probe=56cd0716d9) | Nov 19, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [792754cbe2](https://linux-hardware.org/?probe=792754cbe2) | Nov 19, 2023 |
| Lenovo        | ThinkPad E520 11437UG       | Notebook    | [422931d9a6](https://linux-hardware.org/?probe=422931d9a6) | Nov 19, 2023 |
| Dell          | Latitude E6330              | Notebook    | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [354af02ac9](https://linux-hardware.org/?probe=354af02ac9) | Nov 19, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [75065dda24](https://linux-hardware.org/?probe=75065dda24) | Nov 19, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| MSI           | GE76 Raider 11UE            | Notebook    | [9d0a216d82](https://linux-hardware.org/?probe=9d0a216d82) | Nov 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a7d065988a](https://linux-hardware.org/?probe=a7d065988a) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [fca337aea5](https://linux-hardware.org/?probe=fca337aea5) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [7c45a9b620](https://linux-hardware.org/?probe=7c45a9b620) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [91f7d584f3](https://linux-hardware.org/?probe=91f7d584f3) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ef77e621d0](https://linux-hardware.org/?probe=ef77e621d0) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d086db0563](https://linux-hardware.org/?probe=d086db0563) | Nov 18, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ae962a2552](https://linux-hardware.org/?probe=ae962a2552) | Nov 18, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [4735287055](https://linux-hardware.org/?probe=4735287055) | Nov 18, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [0619c3b255](https://linux-hardware.org/?probe=0619c3b255) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [d402c27e5c](https://linux-hardware.org/?probe=d402c27e5c) | Nov 17, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| HP            | 83E8                        | Desktop     | [393ca40cd9](https://linux-hardware.org/?probe=393ca40cd9) | Nov 16, 2023 |
| Dell          | Precision 5680              | Notebook    | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [9b4ca9cc96](https://linux-hardware.org/?probe=9b4ca9cc96) | Nov 16, 2023 |
| Dell          | Precision 5680              | Notebook    | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | Notebook    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fade86e55e](https://linux-hardware.org/?probe=fade86e55e) | Nov 16, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [e4ac0f919f](https://linux-hardware.org/?probe=e4ac0f919f) | Nov 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [14799f850b](https://linux-hardware.org/?probe=14799f850b) | Nov 15, 2023 |
| HP            | ProBook 4540s               | Notebook    | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| Dell          | XPS 9320                    | Notebook    | [f0435ea4b7](https://linux-hardware.org/?probe=f0435ea4b7) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6a6b0096bb](https://linux-hardware.org/?probe=6a6b0096bb) | Nov 15, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [c3c068a998](https://linux-hardware.org/?probe=c3c068a998) | Nov 14, 2023 |
| Acer          | Aspire V3-471G              | Notebook    | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [7b17ba0f7f](https://linux-hardware.org/?probe=7b17ba0f7f) | Nov 14, 2023 |
| HP            | 2AF7                        | Desktop     | [dd8d87a916](https://linux-hardware.org/?probe=dd8d87a916) | Nov 14, 2023 |
| HP            | ProBook 4540s               | Notebook    | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [73ef67d393](https://linux-hardware.org/?probe=73ef67d393) | Nov 13, 2023 |
| System76      | Adder WS                    | Notebook    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| ASUSTek       | X55U                        | Notebook    | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [1f358e68ee](https://linux-hardware.org/?probe=1f358e68ee) | Nov 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [facdc5c2a4](https://linux-hardware.org/?probe=facdc5c2a4) | Nov 13, 2023 |
| MSI           | GT70                        | Notebook    | [e2c0bb5bfe](https://linux-hardware.org/?probe=e2c0bb5bfe) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| AMI           | Intel                       | Desktop     | [7c96434a18](https://linux-hardware.org/?probe=7c96434a18) | Nov 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [cac951f39c](https://linux-hardware.org/?probe=cac951f39c) | Nov 13, 2023 |
| System76      | Lemur Pro                   | Notebook    | [35e6e1214c](https://linux-hardware.org/?probe=35e6e1214c) | Nov 12, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [a6083e5df9](https://linux-hardware.org/?probe=a6083e5df9) | Nov 12, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [4162e8afa8](https://linux-hardware.org/?probe=4162e8afa8) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f3b49f17b1](https://linux-hardware.org/?probe=f3b49f17b1) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [61994e2e2e](https://linux-hardware.org/?probe=61994e2e2e) | Nov 12, 2023 |
| Google        | Edgar                       | Notebook    | [838bd73737](https://linux-hardware.org/?probe=838bd73737) | Nov 12, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [0e6185c9db](https://linux-hardware.org/?probe=0e6185c9db) | Nov 11, 2023 |
| Google        | Edgar                       | Notebook    | [42f8059f62](https://linux-hardware.org/?probe=42f8059f62) | Nov 11, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [1946d2a10c](https://linux-hardware.org/?probe=1946d2a10c) | Nov 11, 2023 |
| HP            | G42                         | Notebook    | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [75735f5b69](https://linux-hardware.org/?probe=75735f5b69) | Nov 11, 2023 |
| Dell          | Latitude E5420              | Notebook    | [ac31e56717](https://linux-hardware.org/?probe=ac31e56717) | Nov 11, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [f22d74d5eb](https://linux-hardware.org/?probe=f22d74d5eb) | Nov 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [080772c4d8](https://linux-hardware.org/?probe=080772c4d8) | Nov 11, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [9c77400bbf](https://linux-hardware.org/?probe=9c77400bbf) | Nov 11, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [ecc5d08bd8](https://linux-hardware.org/?probe=ecc5d08bd8) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [93d7b2bcdc](https://linux-hardware.org/?probe=93d7b2bcdc) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1473413ce2](https://linux-hardware.org/?probe=1473413ce2) | Nov 09, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [03b4295585](https://linux-hardware.org/?probe=03b4295585) | Nov 09, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| Dell          | 015YTG A02                  | All in one  | [d151271204](https://linux-hardware.org/?probe=d151271204) | Nov 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [c048c3b791](https://linux-hardware.org/?probe=c048c3b791) | Nov 09, 2023 |
| HP            | G42                         | Notebook    | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Precision 5520              | Notebook    | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Dell          | Latitude E7270              | Notebook    | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [d2ce7f8ca6](https://linux-hardware.org/?probe=d2ce7f8ca6) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [e4f3bd771d](https://linux-hardware.org/?probe=e4f3bd771d) | Nov 08, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [8ca7abbf03](https://linux-hardware.org/?probe=8ca7abbf03) | Nov 08, 2023 |
| Acer          | Aspire A517-51              | Notebook    | [9b0700130f](https://linux-hardware.org/?probe=9b0700130f) | Nov 08, 2023 |
| System76      | Lemur Pro                   | Notebook    | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c28217d1ed](https://linux-hardware.org/?probe=c28217d1ed) | Nov 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [a675ce6c08](https://linux-hardware.org/?probe=a675ce6c08) | Nov 07, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [4075eda03c](https://linux-hardware.org/?probe=4075eda03c) | Nov 07, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [c88dde8f18](https://linux-hardware.org/?probe=c88dde8f18) | Nov 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c2ae66ef2b](https://linux-hardware.org/?probe=c2ae66ef2b) | Nov 06, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [7f057ebed2](https://linux-hardware.org/?probe=7f057ebed2) | Nov 06, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [2716ef5f71](https://linux-hardware.org/?probe=2716ef5f71) | Nov 06, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [697278adb7](https://linux-hardware.org/?probe=697278adb7) | Nov 06, 2023 |
| HP            | 89E9 0100                   | All in one  | [5e98ad51b6](https://linux-hardware.org/?probe=5e98ad51b6) | Nov 06, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Google        | Taeko                       | Notebook    | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [6f11758faa](https://linux-hardware.org/?probe=6f11758faa) | Nov 04, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [8bbce8a378](https://linux-hardware.org/?probe=8bbce8a378) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| HP            | 655                         | Notebook    | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [f27bded4c1](https://linux-hardware.org/?probe=f27bded4c1) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26aff1917e](https://linux-hardware.org/?probe=26aff1917e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Intel         | X79 V1.0                    | Desktop     | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [d35fc5aa78](https://linux-hardware.org/?probe=d35fc5aa78) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | Notebook    | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| HP            | ProBook 6450b               | Notebook    | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9a5c45e54b](https://linux-hardware.org/?probe=9a5c45e54b) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [fc0052213d](https://linux-hardware.org/?probe=fc0052213d) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [7812f09d39](https://linux-hardware.org/?probe=7812f09d39) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [b45e25ec01](https://linux-hardware.org/?probe=b45e25ec01) | Nov 02, 2023 |
| HP            | 2AF7                        | Desktop     | [65ac8348d7](https://linux-hardware.org/?probe=65ac8348d7) | Nov 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [04f3946d05](https://linux-hardware.org/?probe=04f3946d05) | Nov 02, 2023 |
| Supermicro    | X9DRE-TF+/X9DR7-TF+         | Server      | [1274766930](https://linux-hardware.org/?probe=1274766930) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cd018c7ab7](https://linux-hardware.org/?probe=cd018c7ab7) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [523fd59139](https://linux-hardware.org/?probe=523fd59139) | Nov 01, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [d85d5f59c2](https://linux-hardware.org/?probe=d85d5f59c2) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [dba91e5612](https://linux-hardware.org/?probe=dba91e5612) | Nov 01, 2023 |
| HP            | ENVY 15                     | Notebook    | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [39f8a7c959](https://linux-hardware.org/?probe=39f8a7c959) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [c1e44a55c8](https://linux-hardware.org/?probe=c1e44a55c8) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [84ca0a285d](https://linux-hardware.org/?probe=84ca0a285d) | Nov 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [38d664802f](https://linux-hardware.org/?probe=38d664802f) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [0ec8ac4d00](https://linux-hardware.org/?probe=0ec8ac4d00) | Nov 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ea7f00b4e](https://linux-hardware.org/?probe=0ea7f00b4e) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7d5fd28d41](https://linux-hardware.org/?probe=7d5fd28d41) | Nov 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| HP            | 829A                        | Mini pc     | [d6ef1b58ed](https://linux-hardware.org/?probe=d6ef1b58ed) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [e9f8c192f1](https://linux-hardware.org/?probe=e9f8c192f1) | Nov 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [f08e4e21a0](https://linux-hardware.org/?probe=f08e4e21a0) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d58a78a617](https://linux-hardware.org/?probe=d58a78a617) | Oct 31, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| ASRockRack    | X570D4U-2L2T/BCM            | Server      | [66607ff17c](https://linux-hardware.org/?probe=66607ff17c) | Oct 31, 2023 |
| eMachines     | EL1352G                     | Desktop     | [e133fecf3e](https://linux-hardware.org/?probe=e133fecf3e) | Oct 31, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [a63d934992](https://linux-hardware.org/?probe=a63d934992) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [cb013304f5](https://linux-hardware.org/?probe=cb013304f5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [d6ac483e43](https://linux-hardware.org/?probe=d6ac483e43) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ee528fce07](https://linux-hardware.org/?probe=ee528fce07) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4e0042e20c](https://linux-hardware.org/?probe=4e0042e20c) | Oct 31, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [7c76f143a4](https://linux-hardware.org/?probe=7c76f143a4) | Oct 31, 2023 |
| HP            | 8299                        | Desktop     | [e45f46df9d](https://linux-hardware.org/?probe=e45f46df9d) | Oct 30, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [d5ace42b13](https://linux-hardware.org/?probe=d5ace42b13) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d51c491524](https://linux-hardware.org/?probe=d51c491524) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e231035f6e](https://linux-hardware.org/?probe=e231035f6e) | Oct 30, 2023 |
| System76      | Adder WS                    | Notebook    | [57478f4561](https://linux-hardware.org/?probe=57478f4561) | Oct 30, 2023 |
| System76      | Adder WS                    | Notebook    | [a10fcac3f4](https://linux-hardware.org/?probe=a10fcac3f4) | Oct 30, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b62cfa508b](https://linux-hardware.org/?probe=b62cfa508b) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [48040bae06](https://linux-hardware.org/?probe=48040bae06) | Oct 29, 2023 |
| HP            | 2AF7                        | Desktop     | [1960b3a243](https://linux-hardware.org/?probe=1960b3a243) | Oct 29, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2815a5477f](https://linux-hardware.org/?probe=2815a5477f) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [c1785bec94](https://linux-hardware.org/?probe=c1785bec94) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d621a72336](https://linux-hardware.org/?probe=d621a72336) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [57e3abc23d](https://linux-hardware.org/?probe=57e3abc23d) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| Samsung       | DM700A4K-KN27 SGL8559A1A... | All in one  | [e6c0db51c1](https://linux-hardware.org/?probe=e6c0db51c1) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6b8560a943](https://linux-hardware.org/?probe=6b8560a943) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9a6fdf5543](https://linux-hardware.org/?probe=9a6fdf5543) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [85b2c39c93](https://linux-hardware.org/?probe=85b2c39c93) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | Desktop     | [fdb96441a0](https://linux-hardware.org/?probe=fdb96441a0) | Oct 27, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | Desktop     | [dde83d5de1](https://linux-hardware.org/?probe=dde83d5de1) | Oct 27, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [2e5ee0032d](https://linux-hardware.org/?probe=2e5ee0032d) | Oct 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [880bf38f49](https://linux-hardware.org/?probe=880bf38f49) | Oct 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [fc29a80949](https://linux-hardware.org/?probe=fc29a80949) | Oct 27, 2023 |
| System76      | Darter Pro                  | Notebook    | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | OMEN LAPTOP - 15-EK0013D... | Notebook    | [0c582fd597](https://linux-hardware.org/?probe=0c582fd597) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [4938c66cd8](https://linux-hardware.org/?probe=4938c66cd8) | Oct 27, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [815b0a4bc4](https://linux-hardware.org/?probe=815b0a4bc4) | Oct 27, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [61bdfadaa0](https://linux-hardware.org/?probe=61bdfadaa0) | Oct 26, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f0641b8822](https://linux-hardware.org/?probe=f0641b8822) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Dell          | Latitude E6530              | Notebook    | [ec57b86fe6](https://linux-hardware.org/?probe=ec57b86fe6) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| Panasonic     | CF-31SBM08DM                | Notebook    | [820f042ba6](https://linux-hardware.org/?probe=820f042ba6) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [13ad3bb316](https://linux-hardware.org/?probe=13ad3bb316) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [a8d850eef8](https://linux-hardware.org/?probe=a8d850eef8) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [023bd4d497](https://linux-hardware.org/?probe=023bd4d497) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [638386d33c](https://linux-hardware.org/?probe=638386d33c) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [dab53e45c9](https://linux-hardware.org/?probe=dab53e45c9) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b7447f21b5](https://linux-hardware.org/?probe=b7447f21b5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [85fac54d6a](https://linux-hardware.org/?probe=85fac54d6a) | Oct 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Danuri        | B550M-PX                    | Desktop     | [e24df1ad61](https://linux-hardware.org/?probe=e24df1ad61) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Intel         | H61 V124                    | Desktop     | [034689793f](https://linux-hardware.org/?probe=034689793f) | Oct 24, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b1f52f8dc1](https://linux-hardware.org/?probe=b1f52f8dc1) | Oct 23, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9af589ace](https://linux-hardware.org/?probe=a9af589ace) | Oct 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47fdb21256](https://linux-hardware.org/?probe=47fdb21256) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7e9d761b35](https://linux-hardware.org/?probe=7e9d761b35) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cf347b4567](https://linux-hardware.org/?probe=cf347b4567) | Oct 23, 2023 |
| MSI           | Sword 15 A11UD              | Notebook    | [d07a7c777c](https://linux-hardware.org/?probe=d07a7c777c) | Oct 23, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [ce5ff412d1](https://linux-hardware.org/?probe=ce5ff412d1) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [73c1b49eab](https://linux-hardware.org/?probe=73c1b49eab) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [b6169d3a96](https://linux-hardware.org/?probe=b6169d3a96) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e0f48fec00](https://linux-hardware.org/?probe=e0f48fec00) | Oct 22, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [f5664b02d2](https://linux-hardware.org/?probe=f5664b02d2) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | Notebook    | [010dd78352](https://linux-hardware.org/?probe=010dd78352) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [6468bd6335](https://linux-hardware.org/?probe=6468bd6335) | Oct 21, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [85894d27fe](https://linux-hardware.org/?probe=85894d27fe) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| Dell          | 06FW8P A01                  | Desktop     | [356c2f38aa](https://linux-hardware.org/?probe=356c2f38aa) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [ca61a8649a](https://linux-hardware.org/?probe=ca61a8649a) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [6108985945](https://linux-hardware.org/?probe=6108985945) | Oct 21, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e7cd525d35](https://linux-hardware.org/?probe=e7cd525d35) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [e51b067a88](https://linux-hardware.org/?probe=e51b067a88) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [6ee41b351a](https://linux-hardware.org/?probe=6ee41b351a) | Oct 20, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | Latitude 5520               | Notebook    | [281fdb7e86](https://linux-hardware.org/?probe=281fdb7e86) | Oct 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [7148bf6db9](https://linux-hardware.org/?probe=7148bf6db9) | Oct 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9cbbb0364b](https://linux-hardware.org/?probe=9cbbb0364b) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [81f32f2ac2](https://linux-hardware.org/?probe=81f32f2ac2) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | Notebook    | [b2cba37968](https://linux-hardware.org/?probe=b2cba37968) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ed3ce7aaa6](https://linux-hardware.org/?probe=ed3ce7aaa6) | Oct 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Dell          | 0JYF1T A03                  | Server      | [93ada2329e](https://linux-hardware.org/?probe=93ada2329e) | Oct 18, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [b6b4b14ba1](https://linux-hardware.org/?probe=b6b4b14ba1) | Oct 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| HP            | 85A2                        | All in one  | [67234a41ca](https://linux-hardware.org/?probe=67234a41ca) | Oct 18, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [e275cfc499](https://linux-hardware.org/?probe=e275cfc499) | Oct 18, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [d652b15856](https://linux-hardware.org/?probe=d652b15856) | Oct 17, 2023 |
| System76      | Gazelle                     | Notebook    | [061012cdb0](https://linux-hardware.org/?probe=061012cdb0) | Oct 17, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | Desktop     | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [464e218144](https://linux-hardware.org/?probe=464e218144) | Oct 17, 2023 |
| Gigabyte      | Z590 VISION D               | Desktop     | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [0ebd0d4ce6](https://linux-hardware.org/?probe=0ebd0d4ce6) | Oct 16, 2023 |
| HP            | 250 G4                      | Notebook    | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| HP            | Laptop 15-dw4xxx            | Notebook    | [44ba7f4015](https://linux-hardware.org/?probe=44ba7f4015) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | Notebook    | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [5631fc0230](https://linux-hardware.org/?probe=5631fc0230) | Oct 16, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| HP            | ProBook 4730s               | Notebook    | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [98224c65b6](https://linux-hardware.org/?probe=98224c65b6) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [47788537bf](https://linux-hardware.org/?probe=47788537bf) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [30723700f1](https://linux-hardware.org/?probe=30723700f1) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [e4dc0eeb72](https://linux-hardware.org/?probe=e4dc0eeb72) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [abc6dc18ab](https://linux-hardware.org/?probe=abc6dc18ab) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| HP            | 212B                        | Desktop     | [c0b9765d6e](https://linux-hardware.org/?probe=c0b9765d6e) | Oct 15, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [5bbd5682e8](https://linux-hardware.org/?probe=5bbd5682e8) | Oct 15, 2023 |
| System76      | Lemur Pro                   | Notebook    | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [5a1df4c4df](https://linux-hardware.org/?probe=5a1df4c4df) | Oct 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a8e7e9b968](https://linux-hardware.org/?probe=a8e7e9b968) | Oct 14, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [725929fa07](https://linux-hardware.org/?probe=725929fa07) | Oct 14, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [7df48c5c5d](https://linux-hardware.org/?probe=7df48c5c5d) | Oct 14, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [142bc36a3f](https://linux-hardware.org/?probe=142bc36a3f) | Oct 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [0594aaa28b](https://linux-hardware.org/?probe=0594aaa28b) | Oct 13, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [596e3973bc](https://linux-hardware.org/?probe=596e3973bc) | Oct 13, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4d6379353d](https://linux-hardware.org/?probe=4d6379353d) | Oct 13, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [52fdfb249e](https://linux-hardware.org/?probe=52fdfb249e) | Oct 12, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d7d6c5206f](https://linux-hardware.org/?probe=d7d6c5206f) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Biostar       | B550GTQ                     | Desktop     | [63f1b39dd4](https://linux-hardware.org/?probe=63f1b39dd4) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| HP            | Unknown                     | Convertible | [8fe4fae90f](https://linux-hardware.org/?probe=8fe4fae90f) | Oct 12, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [df15a4cce8](https://linux-hardware.org/?probe=df15a4cce8) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [5e2f8bdc4d](https://linux-hardware.org/?probe=5e2f8bdc4d) | Oct 12, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [ee849775df](https://linux-hardware.org/?probe=ee849775df) | Oct 12, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| System76      | Thelio Mega thelio-mega-... | Desktop     | [abb07364c1](https://linux-hardware.org/?probe=abb07364c1) | Oct 11, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| Gateway       | NE570                       | Notebook    | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | Notebook    | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4ce0d26e3c](https://linux-hardware.org/?probe=4ce0d26e3c) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [835f369588](https://linux-hardware.org/?probe=835f369588) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [9acd34e892](https://linux-hardware.org/?probe=9acd34e892) | Oct 11, 2023 |
| HP            | ProLiant SE1220             | Server      | [da67ae4335](https://linux-hardware.org/?probe=da67ae4335) | Oct 11, 2023 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [ee15914a37](https://linux-hardware.org/?probe=ee15914a37) | Oct 10, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Lenovo        | ThinkPad P1 20MES05502      | Notebook    | [869264ad64](https://linux-hardware.org/?probe=869264ad64) | Oct 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3d02079672](https://linux-hardware.org/?probe=3d02079672) | Oct 10, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b09f4a3a8a](https://linux-hardware.org/?probe=b09f4a3a8a) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6591296a12](https://linux-hardware.org/?probe=6591296a12) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [c39ce018d6](https://linux-hardware.org/?probe=c39ce018d6) | Oct 10, 2023 |
| Gigabyte      | AORUS 17H BXF               | Notebook    | [4fcbae7a75](https://linux-hardware.org/?probe=4fcbae7a75) | Oct 10, 2023 |
| System76      | Darter Pro                  | Notebook    | [71e1a67b2a](https://linux-hardware.org/?probe=71e1a67b2a) | Oct 10, 2023 |
| Razer         | Blade                       | Notebook    | [22de5dfe50](https://linux-hardware.org/?probe=22de5dfe50) | Oct 09, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2d033cba6c](https://linux-hardware.org/?probe=2d033cba6c) | Oct 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d510e53b4](https://linux-hardware.org/?probe=3d510e53b4) | Oct 08, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [3b54f5530b](https://linux-hardware.org/?probe=3b54f5530b) | Oct 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3ac34a911c](https://linux-hardware.org/?probe=3ac34a911c) | Oct 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a3190a6c6d](https://linux-hardware.org/?probe=a3190a6c6d) | Oct 07, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [e223a799bc](https://linux-hardware.org/?probe=e223a799bc) | Oct 07, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [36d48fe6f7](https://linux-hardware.org/?probe=36d48fe6f7) | Oct 07, 2023 |
| HP            | 8058                        | All in one  | [1e3047c572](https://linux-hardware.org/?probe=1e3047c572) | Oct 07, 2023 |
| System76      | Serval WS                   | Notebook    | [509cc872ee](https://linux-hardware.org/?probe=509cc872ee) | Oct 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [17cdd65d6b](https://linux-hardware.org/?probe=17cdd65d6b) | Oct 07, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [f773c3004e](https://linux-hardware.org/?probe=f773c3004e) | Oct 07, 2023 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [9477d90e51](https://linux-hardware.org/?probe=9477d90e51) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| MSI           | GE62 2QF                    | Notebook    | [cd73adb01d](https://linux-hardware.org/?probe=cd73adb01d) | Oct 07, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [5ec4f81683](https://linux-hardware.org/?probe=5ec4f81683) | Oct 06, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [687a37a00f](https://linux-hardware.org/?probe=687a37a00f) | Oct 06, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [95d81c3bb1](https://linux-hardware.org/?probe=95d81c3bb1) | Oct 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [6507df947b](https://linux-hardware.org/?probe=6507df947b) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| System76      | Serval WS                   | Notebook    | [f8e3cd9fd0](https://linux-hardware.org/?probe=f8e3cd9fd0) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a308ec4180](https://linux-hardware.org/?probe=a308ec4180) | Oct 06, 2023 |
| HP            | Unknown                     | Convertible | [46bfa371c4](https://linux-hardware.org/?probe=46bfa371c4) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [b6caf35101](https://linux-hardware.org/?probe=b6caf35101) | Oct 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [ebbd23f352](https://linux-hardware.org/?probe=ebbd23f352) | Oct 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3e6f44ce5c](https://linux-hardware.org/?probe=3e6f44ce5c) | Oct 05, 2023 |
| Google        | Morphius                    | Notebook    | [735ed70d9c](https://linux-hardware.org/?probe=735ed70d9c) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [34ff66e3a9](https://linux-hardware.org/?probe=34ff66e3a9) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [314a6f2edf](https://linux-hardware.org/?probe=314a6f2edf) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [3f779c87f6](https://linux-hardware.org/?probe=3f779c87f6) | Oct 05, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [234f939987](https://linux-hardware.org/?probe=234f939987) | Oct 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [1dcdef2d17](https://linux-hardware.org/?probe=1dcdef2d17) | Oct 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [eb2aacccb0](https://linux-hardware.org/?probe=eb2aacccb0) | Oct 03, 2023 |
| HP            | 0AA4h                       | Desktop     | [8e4a645689](https://linux-hardware.org/?probe=8e4a645689) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5932daaa4e](https://linux-hardware.org/?probe=5932daaa4e) | Oct 03, 2023 |
| Dell          | Latitude 7400               | Notebook    | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| ASRock        | Z790 PG Riptide             | Desktop     | [82630a534f](https://linux-hardware.org/?probe=82630a534f) | Oct 03, 2023 |
| Kllisre       | X79 V1.2                    | Desktop     | [fb9b29c804](https://linux-hardware.org/?probe=fb9b29c804) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b5965220de](https://linux-hardware.org/?probe=b5965220de) | Oct 03, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [bc03d7f758](https://linux-hardware.org/?probe=bc03d7f758) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [2435f20a18](https://linux-hardware.org/?probe=2435f20a18) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [2e57173dd9](https://linux-hardware.org/?probe=2e57173dd9) | Oct 02, 2023 |
| System76      | Lemur Pro                   | Notebook    | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [57ddb0f758](https://linux-hardware.org/?probe=57ddb0f758) | Oct 01, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [3bb0e0c792](https://linux-hardware.org/?probe=3bb0e0c792) | Oct 01, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [d16a64a7e1](https://linux-hardware.org/?probe=d16a64a7e1) | Oct 01, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| HP            | 250 G4                      | Notebook    | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [691c015f6f](https://linux-hardware.org/?probe=691c015f6f) | Oct 01, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8e74ff2f99](https://linux-hardware.org/?probe=8e74ff2f99) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| HP            | 8054                        | Desktop     | [20f337b1e7](https://linux-hardware.org/?probe=20f337b1e7) | Sep 29, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | Notebook    | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| AZW           | SER V1                      | Desktop     | [10660522cb](https://linux-hardware.org/?probe=10660522cb) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [d19f334f02](https://linux-hardware.org/?probe=d19f334f02) | Sep 28, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2ede90f6eb](https://linux-hardware.org/?probe=2ede90f6eb) | Sep 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | Notebook    | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [9d86e194aa](https://linux-hardware.org/?probe=9d86e194aa) | Sep 27, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [240ff7b72a](https://linux-hardware.org/?probe=240ff7b72a) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f11867f0b7](https://linux-hardware.org/?probe=f11867f0b7) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5a73611f4d](https://linux-hardware.org/?probe=5a73611f4d) | Sep 26, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [0a5cc18946](https://linux-hardware.org/?probe=0a5cc18946) | Sep 26, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [4259a21921](https://linux-hardware.org/?probe=4259a21921) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [2fe436c443](https://linux-hardware.org/?probe=2fe436c443) | Sep 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a58111d9ae](https://linux-hardware.org/?probe=a58111d9ae) | Sep 25, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9de1c7395f](https://linux-hardware.org/?probe=9de1c7395f) | Sep 25, 2023 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [ac151127e1](https://linux-hardware.org/?probe=ac151127e1) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a7eb798aed](https://linux-hardware.org/?probe=a7eb798aed) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ac45698051](https://linux-hardware.org/?probe=ac45698051) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | Notebook    | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3346cccd71](https://linux-hardware.org/?probe=3346cccd71) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7119229a1b](https://linux-hardware.org/?probe=7119229a1b) | Sep 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a3e2e5f3c0](https://linux-hardware.org/?probe=a3e2e5f3c0) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [f4a96c9156](https://linux-hardware.org/?probe=f4a96c9156) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | Notebook    | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9be7572b83](https://linux-hardware.org/?probe=9be7572b83) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [b063963175](https://linux-hardware.org/?probe=b063963175) | Sep 23, 2023 |
| HP            | 250 G4                      | Notebook    | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | Notebook    | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| MSI           | X399 SLI PLUS               | Desktop     | [1c755bb49f](https://linux-hardware.org/?probe=1c755bb49f) | Sep 23, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | Desktop     | [32b162a364](https://linux-hardware.org/?probe=32b162a364) | Sep 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [6656c28ec7](https://linux-hardware.org/?probe=6656c28ec7) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [9867cb03bb](https://linux-hardware.org/?probe=9867cb03bb) | Sep 23, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d344d1e396](https://linux-hardware.org/?probe=d344d1e396) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [31fc587bda](https://linux-hardware.org/?probe=31fc587bda) | Sep 22, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | Notebook    | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| HP            | EliteBook 725 G4            | Notebook    | [1ef194c5fd](https://linux-hardware.org/?probe=1ef194c5fd) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | Notebook    | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [19d1333b4f](https://linux-hardware.org/?probe=19d1333b4f) | Sep 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [5e45e8b196](https://linux-hardware.org/?probe=5e45e8b196) | Sep 21, 2023 |
| System76      | Darter Pro                  | Notebook    | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | Notebook    | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e1805d26c3](https://linux-hardware.org/?probe=e1805d26c3) | Sep 17, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| ASRockRack    | Z490D4U-2L2T                | Desktop     | [0d43dbb11d](https://linux-hardware.org/?probe=0d43dbb11d) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e0371fc03e](https://linux-hardware.org/?probe=e0371fc03e) | Sep 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [43bf92a01b](https://linux-hardware.org/?probe=43bf92a01b) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [5c77a043ae](https://linux-hardware.org/?probe=5c77a043ae) | Sep 15, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | Notebook    | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | Notebook    | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [ebac37bdbd](https://linux-hardware.org/?probe=ebac37bdbd) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | Notebook    | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | Notebook    | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | Notebook    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [49aca37979](https://linux-hardware.org/?probe=49aca37979) | Sep 13, 2023 |
| Lenovo        | 3717 NO DPK                 | Desktop     | [13870a17b4](https://linux-hardware.org/?probe=13870a17b4) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [97909e20b1](https://linux-hardware.org/?probe=97909e20b1) | Sep 12, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [36991ac5a6](https://linux-hardware.org/?probe=36991ac5a6) | Sep 11, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | Notebook    | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [6fdfbcc425](https://linux-hardware.org/?probe=6fdfbcc425) | Sep 10, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca89a07b9e](https://linux-hardware.org/?probe=ca89a07b9e) | Sep 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [56bef39b59](https://linux-hardware.org/?probe=56bef39b59) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [a812c1659b](https://linux-hardware.org/?probe=a812c1659b) | Sep 09, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [375f82dc0c](https://linux-hardware.org/?probe=375f82dc0c) | Sep 09, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [de7d9282cd](https://linux-hardware.org/?probe=de7d9282cd) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | Notebook    | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| MSI           | MAG B560M BAZOOKA           | Desktop     | [c3ba2033e2](https://linux-hardware.org/?probe=c3ba2033e2) | Sep 09, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [1c45c834fe](https://linux-hardware.org/?probe=1c45c834fe) | Sep 09, 2023 |
| HP            | 1495                        | Desktop     | [b56f622d7a](https://linux-hardware.org/?probe=b56f622d7a) | Sep 09, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [8442c861ed](https://linux-hardware.org/?probe=8442c861ed) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | Notebook    | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [bad7c8bf82](https://linux-hardware.org/?probe=bad7c8bf82) | Sep 08, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [57b82728d8](https://linux-hardware.org/?probe=57b82728d8) | Sep 08, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [05d61b5c23](https://linux-hardware.org/?probe=05d61b5c23) | Sep 08, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Dell          | 0WN7Y6 A02                  | Desktop     | [aaf64e4624](https://linux-hardware.org/?probe=aaf64e4624) | Sep 07, 2023 |
| Biostar       | A58MD                       | Desktop     | [40f078fcfc](https://linux-hardware.org/?probe=40f078fcfc) | Sep 06, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [613e4acc75](https://linux-hardware.org/?probe=613e4acc75) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [a33ec74b50](https://linux-hardware.org/?probe=a33ec74b50) | Sep 05, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [d5cd8916d0](https://linux-hardware.org/?probe=d5cd8916d0) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | Notebook    | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [e9faf4759d](https://linux-hardware.org/?probe=e9faf4759d) | Sep 03, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ffc201e884](https://linux-hardware.org/?probe=ffc201e884) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [1c82c8d8b5](https://linux-hardware.org/?probe=1c82c8d8b5) | Sep 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b4907a6220](https://linux-hardware.org/?probe=b4907a6220) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| MSI           | A320M-A PRO M2              | Desktop     | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [6ddc9b767d](https://linux-hardware.org/?probe=6ddc9b767d) | Sep 01, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [76b83d4e93](https://linux-hardware.org/?probe=76b83d4e93) | Sep 01, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [d0cdea5d23](https://linux-hardware.org/?probe=d0cdea5d23) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | Notebook    | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ba11958a48](https://linux-hardware.org/?probe=ba11958a48) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [158ed240bf](https://linux-hardware.org/?probe=158ed240bf) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [085b3d4330](https://linux-hardware.org/?probe=085b3d4330) | Aug 31, 2023 |
| Google        | Kefka                       | Notebook    | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [98b18bb67a](https://linux-hardware.org/?probe=98b18bb67a) | Aug 31, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [45f86c066d](https://linux-hardware.org/?probe=45f86c066d) | Aug 30, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [84f61e2225](https://linux-hardware.org/?probe=84f61e2225) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | Notebook    | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | Notebook    | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [ebebe5ddf7](https://linux-hardware.org/?probe=ebebe5ddf7) | Aug 29, 2023 |
| Dell          | Latitude 5330               | Notebook    | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4cdf174574](https://linux-hardware.org/?probe=4cdf174574) | Aug 29, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6d2186fdd9](https://linux-hardware.org/?probe=6d2186fdd9) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | Notebook    | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | Notebook    | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | Notebook    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | Notebook    | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Unknown       | V00                         | Mini pc     | [b63adaac28](https://linux-hardware.org/?probe=b63adaac28) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [e3a47f55c9](https://linux-hardware.org/?probe=e3a47f55c9) | Aug 26, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [f3874bf2fc](https://linux-hardware.org/?probe=f3874bf2fc) | Aug 26, 2023 |
| HP            | ProBook 4730s               | Notebook    | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | Notebook    | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | Notebook    | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [8d952e28e1](https://linux-hardware.org/?probe=8d952e28e1) | Aug 25, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51d4eefbc9](https://linux-hardware.org/?probe=51d4eefbc9) | Aug 25, 2023 |
| System76      | Thelio Major thelio-majo... | Desktop     | [e5caa63b77](https://linux-hardware.org/?probe=e5caa63b77) | Aug 25, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [958521d2be](https://linux-hardware.org/?probe=958521d2be) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [254f8aee40](https://linux-hardware.org/?probe=254f8aee40) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [6f72852248](https://linux-hardware.org/?probe=6f72852248) | Aug 25, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [acc5fdd0f3](https://linux-hardware.org/?probe=acc5fdd0f3) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [c0bf920a5b](https://linux-hardware.org/?probe=c0bf920a5b) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [40660610aa](https://linux-hardware.org/?probe=40660610aa) | Aug 24, 2023 |
| Dell          | Latitude 7430               | Notebook    | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82be53cac0](https://linux-hardware.org/?probe=82be53cac0) | Aug 23, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [2970428ad3](https://linux-hardware.org/?probe=2970428ad3) | Aug 23, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5abce3a991](https://linux-hardware.org/?probe=5abce3a991) | Aug 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| HP            | 18E7                        | Desktop     | [a78496c36e](https://linux-hardware.org/?probe=a78496c36e) | Aug 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 3856      | 36.27%  |
| Pop!_OS 20.04 | 2131      | 20.05%  |
| Pop!_OS 21.04 | 1803      | 16.96%  |
| Pop!_OS 20.10 | 1652      | 15.54%  |
| Pop!_OS 21.10 | 1113      | 10.47%  |
| Pop!_OS 19.10 | 47        | 0.44%   |
| Pop!_OS 19.04 | 12        | 0.11%   |
| Pop!_OS 18.04 | 11        | 0.1%    |
| Pop!_OS 18.10 | 5         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 10094     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 839       | 7.28%   |
| 6.2.6-76060206-generic   | 832       | 7.22%   |
| 5.8.0-7630-generic       | 741       | 6.43%   |
| 5.4.0-7634-generic       | 667       | 5.79%   |
| 5.13.0-7614-generic      | 496       | 4.3%    |
| 5.8.0-7642-generic       | 482       | 4.18%   |
| 6.0.12-76060006-generic  | 477       | 4.14%   |
| 5.4.0-7642-generic       | 465       | 4.04%   |
| 5.17.5-76051705-generic  | 462       | 4.01%   |
| 5.19.0-76051900-generic  | 449       | 3.9%    |
| 5.11.0-7614-generic      | 439       | 3.81%   |
| 5.13.0-7620-generic      | 413       | 3.58%   |
| 6.0.6-76060006-generic   | 302       | 2.62%   |
| 6.5.6-76060506-generic   | 297       | 2.58%   |
| 6.4.6-76060406-generic   | 293       | 2.54%   |
| 5.15.15-76051515-generic | 280       | 2.43%   |
| 5.16.11-76051611-generic | 264       | 2.29%   |
| 5.15.5-76051505-generic  | 237       | 2.06%   |
| 5.11.0-7612-generic      | 227       | 1.97%   |
| 5.18.10-76051810-generic | 214       | 1.86%   |
| 5.8.0-7625-generic       | 196       | 1.7%    |
| 5.17.15-76051715-generic | 190       | 1.65%   |
| 5.16.19-76051619-generic | 181       | 1.57%   |
| 5.11.0-7633-generic      | 180       | 1.56%   |
| 5.15.8-76051508-generic  | 171       | 1.48%   |
| 5.16.15-76051615-generic | 151       | 1.31%   |
| 5.4.0-7626-generic       | 144       | 1.25%   |
| 6.5.4-76060504-generic   | 129       | 1.12%   |
| 6.2.0-76060200-generic   | 122       | 1.06%   |
| 5.15.11-76051511-generic | 115       | 1%      |
| 6.0.2-76060002-generic   | 92        | 0.8%    |
| 6.1.11-76060111-generic  | 91        | 0.79%   |
| 5.15.23-76051523-generic | 91        | 0.79%   |
| 6.6.6-76060606-generic   | 82        | 0.71%   |
| 5.4.0-7625-generic       | 74        | 0.64%   |
| 5.4.0-7629-generic       | 62        | 0.54%   |
| 5.19.16-76051916-generic | 43        | 0.37%   |
| 6.0.3-76060003-generic   | 40        | 0.35%   |
| 5.3.0-7625-generic       | 16        | 0.14%   |
| 6.0.12-76060012-generic  | 10        | 0.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1629      | 14.4%   |
| 5.4.0   | 1371      | 12.12%  |
| 5.8.0   | 1359      | 12.01%  |
| 5.13.0  | 911       | 8.05%   |
| 6.2.6   | 833       | 7.36%   |
| 6.0.12  | 488       | 4.31%   |
| 5.17.5  | 465       | 4.11%   |
| 5.19.0  | 453       | 4%      |
| 6.0.6   | 303       | 2.68%   |
| 6.5.6   | 297       | 2.62%   |
| 6.4.6   | 293       | 2.59%   |
| 5.15.15 | 281       | 2.48%   |
| 5.16.11 | 264       | 2.33%   |
| 5.15.5  | 237       | 2.09%   |
| 5.18.10 | 214       | 1.89%   |
| 5.17.15 | 190       | 1.68%   |
| 5.16.19 | 181       | 1.6%    |
| 5.15.8  | 171       | 1.51%   |
| 5.16.15 | 151       | 1.33%   |
| 6.5.4   | 129       | 1.14%   |
| 6.2.0   | 122       | 1.08%   |
| 5.15.11 | 115       | 1.02%   |
| 6.0.2   | 95        | 0.84%   |
| 6.1.11  | 92        | 0.81%   |
| 5.15.23 | 91        | 0.8%    |
| 6.6.6   | 82        | 0.72%   |
| 5.3.0   | 51        | 0.45%   |
| 5.19.16 | 43        | 0.38%   |
| 6.0.3   | 40        | 0.35%   |
| 5.15.0  | 14        | 0.12%   |
| 5.0.0   | 12        | 0.11%   |
| 5.8.5   | 8         | 0.07%   |
| 5.7.0   | 8         | 0.07%   |
| 5.8.12  | 7         | 0.06%   |
| 4.18.0  | 7         | 0.06%   |
| 6.1.0   | 6         | 0.05%   |
| 5.13.12 | 6         | 0.05%   |
| 5.10.0  | 6         | 0.05%   |
| 6.3.7   | 5         | 0.04%   |
| 5.8.6   | 5         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1638      | 14.63%  |
| 5.8     | 1396      | 12.47%  |
| 5.4     | 1375      | 12.28%  |
| 6.2     | 954       | 8.52%   |
| 5.13    | 930       | 8.31%   |
| 5.15    | 905       | 8.08%   |
| 6.0     | 904       | 8.07%   |
| 5.17    | 655       | 5.85%   |
| 5.16    | 585       | 5.23%   |
| 5.19    | 498       | 4.45%   |
| 6.5     | 432       | 3.86%   |
| 6.4     | 300       | 2.68%   |
| 5.18    | 221       | 1.97%   |
| 6.1     | 109       | 0.97%   |
| 6.6     | 82        | 0.73%   |
| 5.3     | 51        | 0.46%   |
| 5.10    | 28        | 0.25%   |
| 5.7     | 27        | 0.24%   |
| 5.12    | 18        | 0.16%   |
| 6.3     | 17        | 0.15%   |
| 5.14    | 16        | 0.14%   |
| 5.9     | 15        | 0.13%   |
| 5.6     | 15        | 0.13%   |
| 5.0     | 12        | 0.11%   |
| 4.18    | 8         | 0.07%   |
| 4.15    | 3         | 0.03%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 10074     | 99.8%   |
| aarch64 | 20        | 0.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 9775      | 96.31%  |
| KDE5            | 94        | 0.93%   |
| Unknown         | 69        | 0.68%   |
| KDE             | 59        | 0.58%   |
| X-Cinnamon      | 43        | 0.42%   |
| MATE            | 20        | 0.2%    |
| GNOME Flashback | 20        | 0.2%    |
| XFCE            | 17        | 0.17%   |
| Cinnamon        | 14        | 0.14%   |
| LXQt            | 12        | 0.12%   |
| Unity           | 9         | 0.09%   |
| i3              | 6         | 0.06%   |
| Budgie          | 6         | 0.06%   |
| awesome         | 2         | 0.02%   |
| UKUI            | 1         | 0.01%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 9792      | 96.45%  |
| Wayland | 312       | 3.07%   |
| Unknown | 33        | 0.33%   |
| Tty     | 15        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7964      | 78.06%  |
| GDM     | 1205      | 11.81%  |
| GDM3    | 1002      | 9.82%   |
| SDDM    | 19        | 0.19%   |
| TDM     | 8         | 0.08%   |
| LightDM | 4         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 5815      | 57.11%  |
| en_GB   | 741       | 7.28%   |
| pt_BR   | 692       | 6.8%    |
| de_DE   | 496       | 4.87%   |
| C       | 332       | 3.26%   |
| en_AU   | 257       | 2.52%   |
| en_CA   | 221       | 2.17%   |
| fr_FR   | 202       | 1.98%   |
| it_IT   | 175       | 1.72%   |
| es_ES   | 158       | 1.55%   |
| ru_RU   | 131       | 1.29%   |
| pl_PL   | 92        | 0.9%    |
| Unknown | 85        | 0.83%   |
| pt_PT   | 65        | 0.64%   |
| sv_SE   | 63        | 0.62%   |
| nl_NL   | 58        | 0.57%   |
| en_IN   | 45        | 0.44%   |
| fi_FI   | 36        | 0.35%   |
| nb_NO   | 33        | 0.32%   |
| en_ZA   | 29        | 0.28%   |
| es_MX   | 28        | 0.27%   |
| en_NZ   | 27        | 0.27%   |
| tr_TR   | 26        | 0.26%   |
| fr_CA   | 25        | 0.25%   |
| es_AR   | 24        | 0.24%   |
| en_DK   | 23        | 0.23%   |
| da_DK   | 21        | 0.21%   |
| es_CL   | 19        | 0.19%   |
| cs_CZ   | 17        | 0.17%   |
| de_CH   | 16        | 0.16%   |
| ja_JP   | 15        | 0.15%   |
| hu_HU   | 15        | 0.15%   |
| en_IE   | 14        | 0.14%   |
| sk_SK   | 13        | 0.13%   |
| nl_BE   | 13        | 0.13%   |
| de_AT   | 13        | 0.13%   |
| zh_TW   | 12        | 0.12%   |
| hr_HR   | 12        | 0.12%   |
| zh_CN   | 10        | 0.1%    |
| ro_RO   | 9         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7516      | 73.45%  |
| EFI  | 2717      | 26.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 9675      | 95.45%  |
| Btrfs   | 228       | 2.25%   |
| Overlay | 178       | 1.76%   |
| Xfs     | 31        | 0.31%   |
| Unknown | 13        | 0.13%   |
| Zfs     | 9         | 0.09%   |
| Tmpfs   | 1         | 0.01%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7910      | 77.69%  |
| GPT     | 2064      | 20.27%  |
| MBR     | 207       | 2.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9836      | 97.06%  |
| Yes       | 298       | 2.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9191      | 90.57%  |
| Yes       | 957       | 9.43%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1772      | 17.55%  |
| Lenovo                  | 1361      | 13.48%  |
| Dell                    | 1315      | 13.03%  |
| Hewlett-Packard         | 1090      | 10.8%   |
| MSI                     | 766       | 7.59%   |
| Gigabyte Technology     | 754       | 7.47%   |
| Acer                    | 472       | 4.68%   |
| Apple                   | 453       | 4.49%   |
| ASRock                  | 377       | 3.73%   |
| System76                | 240       | 2.38%   |
| Intel                   | 137       | 1.36%   |
| Toshiba                 | 108       | 1.07%   |
| Samsung Electronics     | 106       | 1.05%   |
| HUAWEI                  | 69        | 0.68%   |
| Alienware               | 62        | 0.61%   |
| Notebook                | 54        | 0.53%   |
| Sony                    | 51        | 0.51%   |
| Microsoft               | 51        | 0.51%   |
| Google                  | 48        | 0.48%   |
| Fujitsu                 | 48        | 0.48%   |
| Unknown                 | 45        | 0.45%   |
| Positivo                | 43        | 0.43%   |
| Pegatron                | 28        | 0.28%   |
| Razer                   | 27        | 0.27%   |
| Medion                  | 22        | 0.22%   |
| Biostar                 | 22        | 0.22%   |
| Supermicro              | 20        | 0.2%    |
| Raspberry Pi Foundation | 20        | 0.2%    |
| Timi                    | 19        | 0.19%   |
| PC Specialist           | 18        | 0.18%   |
| Foxconn                 | 18        | 0.18%   |
| LG Electronics          | 16        | 0.16%   |
| Framework               | 15        | 0.15%   |
| ECS                     | 15        | 0.15%   |
| TUXEDO                  | 14        | 0.14%   |
| Packard Bell            | 14        | 0.14%   |
| Gateway                 | 14        | 0.14%   |
| AZW                     | 14        | 0.14%   |
| Huanan                  | 13        | 0.13%   |
| GPU Company             | 13        | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 94        | 0.93%   |
| Unknown                        | 62        | 0.61%   |
| System76 Oryx Pro              | 48        | 0.48%   |
| ASUS TUF Gaming X570-PLUS      | 44        | 0.44%   |
| System76 Lemur Pro             | 41        | 0.41%   |
| Gigabyte B450M DS3H            | 34        | 0.34%   |
| Dell XPS 15 7590               | 34        | 0.34%   |
| MSI MS-7C02                    | 32        | 0.32%   |
| ASUS ROG STRIX B550-F GAMING   | 32        | 0.32%   |
| ASUS ROG STRIX B450-F GAMING   | 31        | 0.31%   |
| MSI MS-7C37                    | 30        | 0.3%    |
| System76 Gazelle               | 29        | 0.29%   |
| MSI MS-7B86                    | 29        | 0.29%   |
| Apple MacBookPro9,2            | 27        | 0.27%   |
| Apple MacBookPro8,1            | 26        | 0.26%   |
| Dell OptiPlex 9020             | 25        | 0.25%   |
| ASUS PRIME B450M-A             | 24        | 0.24%   |
| System76 Galago Pro            | 23        | 0.23%   |
| Apple MacBookPro12,1           | 23        | 0.23%   |
| Dell XPS 15 9500               | 22        | 0.22%   |
| Apple MacBookAir7,2            | 22        | 0.22%   |
| System76 Thelio                | 21        | 0.21%   |
| System76 Darter Pro            | 21        | 0.21%   |
| Gigabyte X570 AORUS ELITE      | 21        | 0.21%   |
| HP Pavilion Notebook           | 20        | 0.2%    |
| HP Notebook                    | 20        | 0.2%    |
| Gigabyte A320M-S2H             | 19        | 0.19%   |
| Apple MacBookAir6,2            | 19        | 0.19%   |
| HP Pavilion 15                 | 18        | 0.18%   |
| Dell OptiPlex 7010             | 18        | 0.18%   |
| MSI MS-7C91                    | 17        | 0.17%   |
| ASRock B450M Pro4              | 17        | 0.17%   |
| HP Pavilion dv6                | 16        | 0.16%   |
| Dell XPS 15 9560               | 16        | 0.16%   |
| ASRock B450M Steel Legend      | 16        | 0.16%   |
| Apple MacBookPro7,1            | 16        | 0.16%   |
| RPi Raspberry Pi               | 15        | 0.15%   |
| Dell XPS 15 9570               | 15        | 0.15%   |
| Dell Latitude E6420            | 15        | 0.15%   |
| Lenovo IdeaPad S145-15API 81V7 | 14        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 564       | 5.59%   |
| Dell Inspiron      | 362       | 3.59%   |
| ASUS ROG           | 362       | 3.59%   |
| Lenovo IdeaPad     | 319       | 3.16%   |
| Acer Aspire        | 315       | 3.12%   |
| Dell Latitude      | 256       | 2.54%   |
| Dell XPS           | 235       | 2.33%   |
| ASUS PRIME         | 208       | 2.06%   |
| HP Pavilion        | 203       | 2.01%   |
| ASUS TUF           | 174       | 1.72%   |
| Dell OptiPlex      | 161       | 1.6%    |
| HP EliteBook       | 127       | 1.26%   |
| Dell Precision     | 122       | 1.21%   |
| ASUS VivoBook      | 115       | 1.14%   |
| HP Laptop          | 112       | 1.11%   |
| ASUS All           | 94        | 0.93%   |
| Toshiba Satellite  | 92        | 0.91%   |
| Lenovo Legion      | 92        | 0.91%   |
| HP ProBook         | 88        | 0.87%   |
| HP ENVY            | 82        | 0.81%   |
| Lenovo Yoga        | 80        | 0.79%   |
| HP Compaq          | 78        | 0.77%   |
| Gigabyte X570      | 78        | 0.77%   |
| Dell Vostro        | 64        | 0.63%   |
| Unknown            | 62        | 0.61%   |
| Lenovo ThinkCentre | 61        | 0.6%    |
| ASUS ASUS          | 58        | 0.57%   |
| Acer Nitro         | 55        | 0.54%   |
| Gigabyte B450      | 54        | 0.53%   |
| Microsoft Surface  | 51        | 0.51%   |
| Gigabyte B450M     | 49        | 0.49%   |
| System76 Oryx      | 48        | 0.48%   |
| ASUS ZenBook       | 47        | 0.47%   |
| HP OMEN            | 45        | 0.45%   |
| System76 Lemur     | 44        | 0.44%   |
| Apple MacBookPro11 | 43        | 0.43%   |
| Acer Swift         | 42        | 0.42%   |
| ASRock B450M       | 40        | 0.4%    |
| ASRock X570        | 38        | 0.38%   |
| System76 Thelio    | 36        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1224      | 12.13%  |
| 2020    | 1184      | 11.73%  |
| 2018    | 1161      | 11.5%   |
| 2021    | 871       | 8.63%   |
| 2012    | 711       | 7.04%   |
| 2017    | 676       | 6.7%    |
| 2013    | 628       | 6.22%   |
| 2011    | 574       | 5.69%   |
| 2014    | 531       | 5.26%   |
| 2015    | 508       | 5.03%   |
| 2016    | 482       | 4.78%   |
| 2022    | 436       | 4.32%   |
| 2010    | 355       | 3.52%   |
| 2009    | 268       | 2.66%   |
| 2008    | 197       | 1.95%   |
| 2007    | 123       | 1.22%   |
| 2023    | 118       | 1.17%   |
| 2006    | 22        | 0.22%   |
| Unknown | 22        | 0.22%   |
| 2005    | 2         | 0.02%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5565      | 55.13%  |
| Desktop        | 3808      | 37.73%  |
| Convertible    | 278       | 2.75%   |
| Mini pc        | 138       | 1.37%   |
| All in one     | 131       | 1.3%    |
| Tablet         | 116       | 1.15%   |
| Server         | 36        | 0.36%   |
| System on chip | 21        | 0.21%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 10088     | 99.92%  |
| Enabled  | 8         | 0.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9914      | 98.22%  |
| Yes  | 180       | 1.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2649      | 25.88%  |
| 4.01-8.0        | 2197      | 21.47%  |
| 8.01-16.0       | 1883      | 18.4%   |
| 32.01-64.0      | 1473      | 14.39%  |
| 3.01-4.0        | 1194      | 11.67%  |
| 64.01-256.0     | 429       | 4.19%   |
| 24.01-32.0      | 230       | 2.25%   |
| 1.01-2.0        | 120       | 1.17%   |
| 2.01-3.0        | 48        | 0.47%   |
| More than 256.0 | 10        | 0.1%    |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 3125      | 28.21%  |
| 4.01-8.0    | 2584      | 23.33%  |
| 1.01-2.0    | 2432      | 21.95%  |
| 3.01-4.0    | 2058      | 18.58%  |
| 8.01-16.0   | 709       | 6.4%    |
| 16.01-24.0  | 94        | 0.85%   |
| 24.01-32.0  | 31        | 0.28%   |
| 0.51-1.0    | 22        | 0.2%    |
| 32.01-64.0  | 18        | 0.16%   |
| 64.01-256.0 | 4         | 0.04%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5776      | 55.82%  |
| 2      | 2784      | 26.91%  |
| 3      | 922       | 8.91%   |
| 4      | 457       | 4.42%   |
| 5      | 191       | 1.85%   |
| 6      | 82        | 0.79%   |
| 0      | 58        | 0.56%   |
| 7      | 36        | 0.35%   |
| 8      | 13        | 0.13%   |
| 11     | 9         | 0.09%   |
| 9      | 9         | 0.09%   |
| 10     | 3         | 0.03%   |
| 26     | 1         | 0.01%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7311      | 72.06%  |
| Yes       | 2835      | 27.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8551      | 84.35%  |
| No        | 1587      | 15.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8213      | 81.02%  |
| No        | 1924      | 18.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6901      | 67.72%  |
| No        | 3290      | 32.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 3065      | 30.21%  |
| Brazil       | 938       | 9.25%   |
| Germany      | 695       | 6.85%   |
| UK           | 501       | 4.94%   |
| Canada       | 440       | 4.34%   |
| Australia    | 303       | 2.99%   |
| Italy        | 288       | 2.84%   |
| India        | 286       | 2.82%   |
| France       | 261       | 2.57%   |
| Netherlands  | 220       | 2.17%   |
| Russia       | 176       | 1.74%   |
| Sweden       | 175       | 1.73%   |
| Poland       | 160       | 1.58%   |
| Spain        | 143       | 1.41%   |
| Mexico       | 116       | 1.14%   |
| Portugal     | 115       | 1.13%   |
| Switzerland  | 99        | 0.98%   |
| Norway       | 99        | 0.98%   |
| South Africa | 93        | 0.92%   |
| Finland      | 92        | 0.91%   |
| Romania      | 90        | 0.89%   |
| Austria      | 77        | 0.76%   |
| New Zealand  | 72        | 0.71%   |
| Denmark      | 72        | 0.71%   |
| Belgium      | 71        | 0.7%    |
| Philippines  | 69        | 0.68%   |
| Turkey       | 68        | 0.67%   |
| Greece       | 67        | 0.66%   |
| Argentina    | 67        | 0.66%   |
| Indonesia    | 61        | 0.6%    |
| Czechia      | 59        | 0.58%   |
| Chile        | 50        | 0.49%   |
| Japan        | 48        | 0.47%   |
| Hungary      | 45        | 0.44%   |
| Bulgaria     | 45        | 0.44%   |
| Ireland      | 42        | 0.41%   |
| Malaysia     | 39        | 0.38%   |
| Serbia       | 38        | 0.37%   |
| Croatia      | 37        | 0.36%   |
| Ukraine      | 35        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 111       | 1.05%   |
| Sydney         | 82        | 0.77%   |
| Melbourne      | 61        | 0.58%   |
| Berlin         | 58        | 0.55%   |
| Rio de Janeiro | 57        | 0.54%   |
| Brisbane       | 54        | 0.51%   |
| Milan          | 51        | 0.48%   |
| Helsinki       | 50        | 0.47%   |
| Vienna         | 48        | 0.45%   |
| Warsaw         | 45        | 0.42%   |
| Moscow         | 44        | 0.41%   |
| London         | 42        | 0.4%    |
| New York       | 41        | 0.39%   |
| Dallas         | 41        | 0.39%   |
| Chicago        | 41        | 0.39%   |
| Bengaluru      | 41        | 0.39%   |
| Amsterdam      | 37        | 0.35%   |
| Denver         | 36        | 0.34%   |
| Toronto        | 35        | 0.33%   |
| Paris          | 35        | 0.33%   |
| Madrid         | 35        | 0.33%   |
| Seattle        | 34        | 0.32%   |
| Auckland       | 34        | 0.32%   |
| Athens         | 34        | 0.32%   |
| Rome           | 33        | 0.31%   |
| Bucharest      | 32        | 0.3%    |
| Sofia          | 31        | 0.29%   |
| Montreal       | 31        | 0.29%   |
| Los Angeles    | 31        | 0.29%   |
| Zurich         | 30        | 0.28%   |
| Stockholm      | 30        | 0.28%   |
| Istanbul       | 30        | 0.28%   |
| Edmonton       | 30        | 0.28%   |
| Miami          | 29        | 0.27%   |
| Lisbon         | 29        | 0.27%   |
| Johannesburg   | 29        | 0.27%   |
| Calgary        | 29        | 0.27%   |
| Oslo           | 28        | 0.26%   |
| Brasília      | 28        | 0.26%   |
| Hamburg        | 27        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2836      | 4345   | 18.23%  |
| Seagate                     | 2005      | 2888   | 12.89%  |
| WDC                         | 1993      | 2786   | 12.81%  |
| Sandisk                     | 1057      | 1407   | 6.79%   |
| Kingston                    | 868       | 1091   | 5.58%   |
| Toshiba                     | 793       | 981    | 5.1%    |
| Crucial                     | 624       | 821    | 4.01%   |
| Unknown                     | 484       | 621    | 3.11%   |
| SK hynix                    | 451       | 576    | 2.9%    |
| Intel                       | 433       | 583    | 2.78%   |
| Hitachi                     | 301       | 393    | 1.93%   |
| Micron Technology           | 275       | 327    | 1.77%   |
| HGST                        | 259       | 313    | 1.66%   |
| Phison                      | 241       | 333    | 1.55%   |
| A-DATA Technology           | 229       | 283    | 1.47%   |
| Apple                       | 222       | 258    | 1.43%   |
| China                       | 152       | 204    | 0.98%   |
| Micron/Crucial Technology   | 151       | 205    | 0.97%   |
| PNY                         | 144       | 180    | 0.93%   |
| Silicon Motion              | 137       | 182    | 0.88%   |
| Phison Electronics          | 97        | 134    | 0.62%   |
| KIOXIA                      | 96        | 111    | 0.62%   |
| SPCC                        | 68        | 92     | 0.44%   |
| OCZ                         | 63        | 82     | 0.4%    |
| LITEON                      | 62        | 73     | 0.4%    |
| Team                        | 57        | 68     | 0.37%   |
| Transcend                   | 55        | 63     | 0.35%   |
| Kingston Technology Company | 52        | 62     | 0.33%   |
| XPG                         | 51        | 66     | 0.33%   |
| Realtek Semiconductor       | 50        | 56     | 0.32%   |
| Patriot                     | 50        | 67     | 0.32%   |
| Corsair                     | 47        | 62     | 0.3%    |
| JMicron Technology          | 44        | 63     | 0.28%   |
| LITEONIT                    | 42        | 60     | 0.27%   |
| ADATA Technology            | 42        | 54     | 0.27%   |
| Intenso                     | 40        | 52     | 0.26%   |
| Netac                       | 35        | 39     | 0.22%   |
| Maxtor                      | 35        | 36     | 0.22%   |
| KingSpec                    | 35        | 41     | 0.22%   |
| Unknown                     | 35        | 40     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 222       | 1.29%   |
| Samsung NVMe SSD Drive 1TB                          | 197       | 1.14%   |
| Samsung NVMe SSD Drive 500GB                        | 178       | 1.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 157       | 0.91%   |
| Samsung SSD 850 EVO 250GB                           | 138       | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                      | 137       | 0.8%    |
| Samsung SSD 860 EVO 500GB                           | 124       | 0.72%   |
| Samsung SSD 850 EVO 500GB                           | 122       | 0.71%   |
| SanDisk NVMe SSD Drive 1TB                          | 119       | 0.69%   |
| Samsung NVMe SSD Drive 512GB                        | 118       | 0.69%   |
| Samsung SSD 860 EVO 1TB                             | 115       | 0.67%   |
| Unknown MMC Card  64GB                              | 111       | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 110       | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                      | 103       | 0.6%    |
| Kingston SA400S37120G 120GB SSD                     | 102       | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 100       | 0.58%   |
| Kingston SA400S37480G 480GB SSD                     | 98        | 0.57%   |
| SanDisk NVMe SSD Drive 500GB                        | 97        | 0.56%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 91        | 0.53%   |
| HGST HTS721010A9E630 1TB                            | 88        | 0.51%   |
| Seagate ST500DM002-1BD142 500GB                     | 86        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                         | 86        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 84        | 0.49%   |
| Toshiba MQ01ABD100 1TB                              | 83        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                        | 82        | 0.48%   |
| Unknown MMC Card  32GB                              | 78        | 0.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 74        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 73        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 72        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                        | 72        | 0.42%   |
| Intel NVMe SSD Drive 512GB                          | 69        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                        | 65        | 0.38%   |
| SK hynix NVMe SSD Drive 512GB                       | 61        | 0.35%   |
| Seagate Expansion 2TB                               | 60        | 0.35%   |
| Samsung NVMe SSD Drive 2TB                          | 59        | 0.34%   |
| Unknown MMC Card  128GB                             | 58        | 0.34%   |
| Samsung NVMe SSD Drive 1024GB                       | 58        | 0.34%   |
| Toshiba MQ04ABF100 1TB                              | 57        | 0.33%   |
| Samsung SSD 860 EVO 250GB                           | 56        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 56        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1939      | 2741   | 38.79%  |
| WDC                 | 1509      | 2108   | 30.19%  |
| Toshiba             | 565       | 683    | 11.3%   |
| Hitachi             | 301       | 393    | 6.02%   |
| HGST                | 259       | 313    | 5.18%   |
| Samsung Electronics | 157       | 184    | 3.14%   |
| Unknown             | 59        | 71     | 1.18%   |
| Apple               | 57        | 70     | 1.14%   |
| Maxtor              | 27        | 28     | 0.54%   |
| Fujitsu             | 25        | 30     | 0.5%    |
| SABRENT             | 23        | 28     | 0.46%   |
| TO Exter            | 13        | 16     | 0.26%   |
| External            | 8         | 8      | 0.16%   |
| ASMT                | 8         | 10     | 0.16%   |
| JMicron Technology  | 6         | 17     | 0.12%   |
| USB                 | 3         | 4      | 0.06%   |
| StoreJet            | 3         | 3      | 0.06%   |
| Intenso             | 3         | 7      | 0.06%   |
| Hewlett-Packard     | 3         | 5      | 0.06%   |
| ExcelStor           | 3         | 3      | 0.06%   |
| RSH-339             | 2         | 2      | 0.04%   |
| MaxDigital          | 2         | 2      | 0.04%   |
| Magnetic Data       | 2         | 2      | 0.04%   |
| LaCie               | 2         | 3      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| Unknown             | 2         | 3      | 0.04%   |
| XrayDisk            | 1         | 1      | 0.02%   |
| WD MediaMax         | 1         | 2      | 0.02%   |
| USB3.0              | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| ASMT109x            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1301      | 1915   | 24.27%  |
| Kingston            | 692       | 852    | 12.91%  |
| Crucial             | 566       | 742    | 10.56%  |
| SanDisk             | 484       | 618    | 9.03%   |
| WDC                 | 347       | 437    | 6.47%   |
| A-DATA Technology   | 179       | 221    | 3.34%   |
| China               | 151       | 203    | 2.82%   |
| PNY                 | 140       | 176    | 2.61%   |
| Apple               | 140       | 152    | 2.61%   |
| Intel               | 118       | 149    | 2.2%    |
| SK hynix            | 100       | 125    | 1.87%   |
| Micron Technology   | 91        | 101    | 1.7%    |
| Toshiba             | 77        | 90     | 1.44%   |
| OCZ                 | 62        | 78     | 1.16%   |
| SPCC                | 61        | 77     | 1.14%   |
| LITEON              | 56        | 67     | 1.04%   |
| Transcend           | 52        | 60     | 0.97%   |
| Patriot             | 49        | 66     | 0.91%   |
| Team                | 46        | 56     | 0.86%   |
| LITEONIT            | 42        | 60     | 0.78%   |
| Corsair             | 36        | 44     | 0.67%   |
| KingSpec            | 35        | 41     | 0.65%   |
| Seagate             | 34        | 50     | 0.63%   |
| Netac               | 29        | 33     | 0.54%   |
| Lexar               | 27        | 31     | 0.5%    |
| Intenso             | 27        | 34     | 0.5%    |
| Hewlett-Packard     | 24        | 32     | 0.45%   |
| JMicron Technology  | 23        | 26     | 0.43%   |
| Apacer              | 22        | 31     | 0.41%   |
| Gigabyte Technology | 17        | 19     | 0.32%   |
| GOODRAM             | 16        | 18     | 0.3%    |
| KingDian            | 15        | 24     | 0.28%   |
| Plextor             | 13        | 17     | 0.24%   |
| Mushkin             | 13        | 16     | 0.24%   |
| Dogfish             | 12        | 17     | 0.22%   |
| ASMT                | 12        | 18     | 0.22%   |
| OWC                 | 9         | 18     | 0.17%   |
| Maxtor              | 8         | 8      | 0.15%   |
| KIOXIA-EXCERIA      | 8         | 9      | 0.15%   |
| Unknown             | 7         | 7      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 4632      | 7001   | 33.39%  |
| NVMe    | 4370      | 6568   | 31.5%   |
| HDD     | 4248      | 6758   | 30.62%  |
| MMC     | 374       | 463    | 2.7%    |
| Unknown | 248       | 368    | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 7032      | 13189  | 56.79%  |
| NVMe | 4365      | 6548   | 35.25%  |
| SAS  | 611       | 958    | 4.93%   |
| MMC  | 374       | 463    | 3.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 5017      | 7512   | 53.87%  |
| 0.51-1.0        | 2842      | 3990   | 30.52%  |
| 1.01-2.0        | 872       | 1253   | 9.36%   |
| 3.01-4.0        | 246       | 413    | 2.64%   |
| 4.01-10.0       | 164       | 312    | 1.76%   |
| 2.01-3.0        | 148       | 225    | 1.59%   |
| 10.01-20.0      | 23        | 53     | 0.25%   |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3057      | 29.05%  |
| 251-500        | 2612      | 24.82%  |
| 501-1000       | 2012      | 19.12%  |
| 1001-2000      | 987       | 9.38%   |
| More than 3000 | 520       | 4.94%   |
| 51-100         | 463       | 4.4%    |
| 2001-3000      | 337       | 3.2%    |
| 1-20           | 251       | 2.39%   |
| 21-50          | 215       | 2.04%   |
| Unknown        | 68        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3914      | 35.49%  |
| 21-50          | 2255      | 20.45%  |
| 101-250        | 1411      | 12.79%  |
| 51-100         | 1317      | 11.94%  |
| 251-500        | 865       | 7.84%   |
| 501-1000       | 568       | 5.15%   |
| 1001-2000      | 329       | 2.98%   |
| More than 3000 | 190       | 1.72%   |
| 2001-3000      | 112       | 1.02%   |
| Unknown        | 68        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 7         | 7      | 2.23%   |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1.91%   |
| Seagate ST1000LM035-1RK172 1TB           | 5         | 5      | 1.59%   |
| HGST HTS721010A9E630 1TB                 | 5         | 5      | 1.59%   |
| Seagate ST500LT012-9WS142 500GB          | 4         | 5      | 1.27%   |
| Seagate ST500DM002-1BD142 500GB          | 4         | 4      | 1.27%   |
| Seagate ST1000LX015-1U7172 1TB           | 4         | 4      | 1.27%   |
| HGST HTS541010A9E680 1TB                 | 4         | 4      | 1.27%   |
| Crucial CT525MX300SSD1 528GB             | 4         | 4      | 1.27%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 3         | 3      | 0.96%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB    | 3         | 3      | 0.96%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 0.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 3         | 3      | 0.96%   |
| Seagate ST1500DL003-9VT16L 1TB           | 3         | 4      | 0.96%   |
| Seagate ST1000DM003-9YN162 1TB           | 3         | 3      | 0.96%   |
| Samsung Electronics HD502HI 500GB        | 3         | 4      | 0.96%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 5      | 0.96%   |
| Kingston SA400S37120G 120GB SSD          | 3         | 5      | 0.96%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 0.96%   |
| Crucial CT1000P1SSD8 1TB                 | 3         | 3      | 0.96%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2         | 2      | 0.64%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 2         | 2      | 0.64%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 2         | 2      | 0.64%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 2         | 3      | 0.64%   |
| WDC WD1002FAEX-00Z3A0 1TB                | 2         | 2      | 0.64%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 2      | 0.64%   |
| Toshiba MK7559GSXP 752GB                 | 2         | 2      | 0.64%   |
| Toshiba HDWD110 1TB                      | 2         | 2      | 0.64%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 2         | 2      | 0.64%   |
| Seagate ST9750420AS 752GB                | 2         | 2      | 0.64%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 0.64%   |
| Seagate ST9320325AS 320GB                | 2         | 2      | 0.64%   |
| Seagate ST3250310AS 250GB                | 2         | 4      | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB           | 2         | 2      | 0.64%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 0.64%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 0.64%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 2         | 2      | 0.64%   |
| Samsung Electronics SSD 850 EVO 500GB    | 2         | 2      | 0.64%   |
| Samsung Electronics SSD 850 EVO 250GB    | 2         | 2      | 0.64%   |
| Samsung Electronics HD103SJ 1TB          | 2         | 2      | 0.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 75        | 86     | 24.43%  |
| WDC                         | 66        | 78     | 21.5%   |
| Samsung Electronics         | 32        | 39     | 10.42%  |
| Toshiba                     | 20        | 21     | 6.51%   |
| HGST                        | 20        | 23     | 6.51%   |
| Kingston                    | 13        | 17     | 4.23%   |
| Hitachi                     | 13        | 16     | 4.23%   |
| SK hynix                    | 11        | 13     | 3.58%   |
| Crucial                     | 10        | 10     | 3.26%   |
| Intel                       | 8         | 8      | 2.61%   |
| A-DATA Technology           | 7         | 7      | 2.28%   |
| Micron Technology           | 6         | 8      | 1.95%   |
| SanDisk                     | 4         | 4      | 1.3%    |
| China                       | 3         | 3      | 0.98%   |
| Team                        | 2         | 2      | 0.65%   |
| LITEON                      | 2         | 2      | 0.65%   |
| Apple                       | 2         | 2      | 0.65%   |
| SPCC                        | 1         | 1      | 0.33%   |
| Silicon Motion              | 1         | 1      | 0.33%   |
| SABRENT                     | 1         | 1      | 0.33%   |
| S3+                         | 1         | 1      | 0.33%   |
| Plextor                     | 1         | 1      | 0.33%   |
| Maxtor                      | 1         | 1      | 0.33%   |
| Lexar                       | 1         | 1      | 0.33%   |
| Leven                       | 1         | 1      | 0.33%   |
| Kingston Technology Company | 1         | 1      | 0.33%   |
| Intenso                     | 1         | 1      | 0.33%   |
| Flashwar                    | 1         | 1      | 0.33%   |
| BAITITON                    | 1         | 1      | 0.33%   |
| ASMT                        | 1         | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 86     | 37.13%  |
| WDC                 | 62        | 74     | 30.69%  |
| HGST                | 20        | 23     | 9.9%    |
| Toshiba             | 17        | 17     | 8.42%   |
| Hitachi             | 13        | 16     | 6.44%   |
| Samsung Electronics | 11        | 12     | 5.45%   |
| Apple               | 2         | 2      | 0.99%   |
| SABRENT             | 1         | 1      | 0.5%    |
| Maxtor              | 1         | 1      | 0.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 189       | 232    | 64.07%  |
| SSD  | 75        | 87     | 25.42%  |
| NVMe | 31        | 33     | 10.51%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 16.67%  |
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 16.67%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 16.67%  |
| Patriot Pyro SSD 120GB            | 1         | 2      | 16.67%  |
| KingDian S400 120GB               | 1         | 2      | 16.67%  |
| Intenso JAJP600M1TB               | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Patriot             | 1         | 2      | 16.67%  |
| KingDian            | 1         | 2      | 16.67%  |
| Intenso             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8074      | 17069  | 76.13%  |
| Works    | 2239      | 3728   | 21.11%  |
| Malfunc  | 286       | 352    | 2.7%    |
| Failed   | 6         | 8      | 0.06%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6087      | 43.63%  |
| AMD                              | 2477      | 17.76%  |
| Samsung Electronics              | 1733      | 12.42%  |
| SanDisk                          | 751       | 5.38%   |
| Phison Electronics               | 352       | 2.52%   |
| SK hynix                         | 351       | 2.52%   |
| ASMedia Technology               | 232       | 1.66%   |
| Kingston Technology Company      | 231       | 1.66%   |
| Micron/Crucial Technology        | 204       | 1.46%   |
| Micron Technology                | 187       | 1.34%   |
| Toshiba America Info Systems     | 171       | 1.23%   |
| Nvidia                           | 170       | 1.22%   |
| Silicon Motion                   | 156       | 1.12%   |
| Marvell Technology Group         | 125       | 0.9%    |
| ADATA Technology                 | 125       | 0.9%    |
| KIOXIA                           | 98        | 0.7%    |
| JMicron Technology               | 91        | 0.65%   |
| Realtek Semiconductor            | 69        | 0.49%   |
| Solid State Storage Technology   | 48        | 0.34%   |
| Union Memory (Shenzhen)          | 41        | 0.29%   |
| Seagate Technology               | 31        | 0.22%   |
| Broadcom / LSI                   | 31        | 0.22%   |
| Apple                            | 27        | 0.19%   |
| LSI Logic / Symbios Logic        | 22        | 0.16%   |
| Lite-On Technology               | 19        | 0.14%   |
| Shenzhen Longsys Electronics     | 17        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 14        | 0.1%    |
| VIA Technologies                 | 12        | 0.09%   |
| Silicon Integrated Systems [SiS] | 10        | 0.07%   |
| INNOGRIT                         | 9         | 0.06%   |
| Hewlett-Packard                  | 8         | 0.06%   |
| Solidigm                         | 7         | 0.05%   |
| Silicon Image                    | 7         | 0.05%   |
| Lenovo                           | 7         | 0.05%   |
| Adaptec                          | 6         | 0.04%   |
| Yangtze Memory Technologies      | 3         | 0.02%   |
| Transcend                        | 3         | 0.02%   |
| Netac Technology                 | 3         | 0.02%   |
| HighPoint Technologies           | 3         | 0.02%   |
| OCZ Technology Group             | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1837      | 11.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 924       | 5.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 489       | 3.12%   |
| AMD 400 Series Chipset SATA Controller                                         | 481       | 3.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 417       | 2.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 385       | 2.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 360       | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 316       | 2.02%   |
| AMD 500 Series Chipset SATA Controller                                         | 278       | 1.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 264       | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 258       | 1.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 246       | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 240       | 1.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 237       | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 224       | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 219       | 1.4%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 196       | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 193       | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 187       | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 185       | 1.18%   |
| Intel SATA Controller [RAID mode]                                              | 181       | 1.15%   |
| Phison E12 NVMe Controller                                                     | 171       | 1.09%   |
| Intel SSD 660P Series                                                          | 162       | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 160       | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 160       | 1.02%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 157       | 1%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 152       | 0.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 147       | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 146       | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 130       | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 126       | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 124       | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 123       | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 122       | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 104       | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 102       | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 101       | 0.64%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 98        | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 89        | 0.57%   |
| AMD 300 Series Chipset SATA Controller                                         | 88        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 7491      | 55%     |
| NVMe | 4363      | 32.03%  |
| RAID | 912       | 6.7%    |
| IDE  | 795       | 5.84%   |
| SAS  | 43        | 0.32%   |
| SCSI | 16        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 7088      | 70.22%  |
| AMD    | 2986      | 29.58%  |
| ARM    | 20        | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 158       | 1.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 138       | 1.36%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 124       | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 117       | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 115       | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 108       | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 105       | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 99        | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 91        | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 90        | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 82        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 82        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 80        | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 79        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 78        | 0.77%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 75        | 0.74%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 74        | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 73        | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 68        | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 64        | 0.63%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 64        | 0.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 62        | 0.61%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 62        | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 60        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 59        | 0.58%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 57        | 0.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 56        | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 55        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 54        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 54        | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 51        | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 49        | 0.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 49        | 0.48%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 48        | 0.47%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 47        | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 0.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 46        | 0.45%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 46        | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 45        | 0.44%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 45        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2353      | 23.27%  |
| Intel Core i5           | 2183      | 21.59%  |
| AMD Ryzen 5             | 967       | 9.56%   |
| AMD Ryzen 7             | 779       | 7.7%    |
| Other                   | 743       | 7.35%   |
| Intel Core i3           | 547       | 5.41%   |
| AMD Ryzen 9             | 306       | 3.03%   |
| Intel Core 2 Duo        | 273       | 2.7%    |
| Intel Celeron           | 254       | 2.51%   |
| Intel Xeon              | 223       | 2.21%   |
| AMD FX                  | 139       | 1.37%   |
| AMD Ryzen 3             | 135       | 1.34%   |
| Intel Pentium           | 119       | 1.18%   |
| Intel Core i9           | 117       | 1.16%   |
| AMD A6                  | 69        | 0.68%   |
| AMD A8                  | 67        | 0.66%   |
| Intel Pentium Dual-Core | 64        | 0.63%   |
| Intel Atom              | 64        | 0.63%   |
| AMD A10                 | 63        | 0.62%   |
| AMD Ryzen 7 PRO         | 53        | 0.52%   |
| AMD Ryzen Threadripper  | 52        | 0.51%   |
| Intel Core 2 Quad       | 51        | 0.5%    |
| AMD A4                  | 39        | 0.39%   |
| AMD Phenom II X4        | 35        | 0.35%   |
| Intel Core 2            | 34        | 0.34%   |
| AMD Athlon              | 32        | 0.32%   |
| AMD Athlon II X2        | 26        | 0.26%   |
| AMD Ryzen 5 PRO         | 24        | 0.24%   |
| Intel Pentium Dual      | 22        | 0.22%   |
| Intel Genuine           | 17        | 0.17%   |
| AMD Athlon II X4        | 17        | 0.17%   |
| Intel Core m3           | 16        | 0.16%   |
| AMD E1                  | 16        | 0.16%   |
| AMD E                   | 16        | 0.16%   |
| Intel Pentium Silver    | 15        | 0.15%   |
| AMD Phenom II X6        | 14        | 0.14%   |
| AMD Athlon 64 X2        | 13        | 0.13%   |
| AMD E2                  | 12        | 0.12%   |
| Intel Pentium Gold      | 11        | 0.11%   |
| Intel Core m5           | 10        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3671      | 36.3%   |
| 2       | 3041      | 30.07%  |
| 6       | 1452      | 14.36%  |
| 8       | 1189      | 11.76%  |
| 12      | 246       | 2.43%   |
| 16      | 139       | 1.37%   |
| 14      | 96        | 0.95%   |
| 10      | 91        | 0.9%    |
| 1       | 60        | 0.59%   |
| 3       | 56        | 0.55%   |
| 24      | 31        | 0.31%   |
| 32      | 16        | 0.16%   |
| Unknown | 9         | 0.09%   |
| 64      | 4         | 0.04%   |
| 40      | 2         | 0.02%   |
| 36      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 48      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10027     | 99.33%  |
| 2       | 59        | 0.58%   |
| Unknown | 9         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7837      | 77.52%  |
| 1       | 2263      | 22.39%  |
| Unknown | 9         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10067     | 99.73%  |
| 64-bit         | 16        | 0.16%   |
| Unknown        | 11        | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7169      | 69.35%  |
| 0x906ea    | 193       | 1.87%   |
| 0x306a9    | 168       | 1.63%   |
| 0x206a7    | 147       | 1.42%   |
| 0x306c3    | 135       | 1.31%   |
| 0x806ea    | 126       | 1.22%   |
| 0x806ec    | 124       | 1.2%    |
| 0x806c1    | 118       | 1.14%   |
| 0x08701021 | 110       | 1.06%   |
| 0x406e3    | 95        | 0.92%   |
| 0x906e9    | 88        | 0.85%   |
| 0x40651    | 86        | 0.83%   |
| 0x806e9    | 81        | 0.78%   |
| 0x506e3    | 79        | 0.76%   |
| 0x0800820d | 78        | 0.75%   |
| 0x08701013 | 77        | 0.74%   |
| 0xa0652    | 75        | 0.73%   |
| 0x0a50000c | 67        | 0.65%   |
| 0x1067a    | 63        | 0.61%   |
| 0x08108109 | 57        | 0.55%   |
| 0x08600106 | 53        | 0.51%   |
| 0x08108102 | 51        | 0.49%   |
| 0x906ed    | 44        | 0.43%   |
| 0x306d4    | 44        | 0.43%   |
| 0x806d1    | 38        | 0.37%   |
| 0x806eb    | 37        | 0.36%   |
| 0x08608103 | 34        | 0.33%   |
| 0x20655    | 30        | 0.29%   |
| 0x08001138 | 28        | 0.27%   |
| 0x706e5    | 27        | 0.26%   |
| 0x08600104 | 27        | 0.26%   |
| 0x906a3    | 26        | 0.25%   |
| 0x406c4    | 26        | 0.25%   |
| 0x0a201016 | 26        | 0.25%   |
| 0x0810100b | 25        | 0.24%   |
| 0x06000852 | 25        | 0.24%   |
| 0x0a601203 | 22        | 0.21%   |
| 0x0a50000d | 22        | 0.21%   |
| 0x08600103 | 21        | 0.2%    |
| 0x06001119 | 20        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1805      | 17.84%  |
| Haswell          | 937       | 9.26%   |
| Zen 2            | 772       | 7.63%   |
| SandyBridge      | 661       | 6.53%   |
| IvyBridge        | 657       | 6.49%   |
| Skylake          | 560       | 5.54%   |
| Zen 3            | 550       | 5.44%   |
| Unknown          | 535       | 5.29%   |
| Zen+             | 518       | 5.12%   |
| Penryn           | 340       | 3.36%   |
| CometLake        | 336       | 3.32%   |
| TigerLake        | 304       | 3%      |
| Zen              | 255       | 2.52%   |
| Broadwell        | 226       | 2.23%   |
| Westmere         | 222       | 2.19%   |
| Piledriver       | 194       | 1.92%   |
| Silvermont       | 153       | 1.51%   |
| Core             | 144       | 1.42%   |
| Icelake          | 135       | 1.33%   |
| K10              | 125       | 1.24%   |
| Alderlake Hybrid | 112       | 1.11%   |
| Nehalem          | 105       | 1.04%   |
| Excavator        | 95        | 0.94%   |
| Goldmont plus    | 90        | 0.89%   |
| Puma             | 48        | 0.47%   |
| Steamroller      | 43        | 0.43%   |
| Goldmont         | 37        | 0.37%   |
| Bobcat           | 34        | 0.34%   |
| K8 Hammer        | 31        | 0.31%   |
| K10 Llano        | 28        | 0.28%   |
| Jaguar           | 22        | 0.22%   |
| Bulldozer        | 16        | 0.16%   |
| NetBurst         | 9         | 0.09%   |
| K8 & K10 hybrid  | 8         | 0.08%   |
| Bonnell          | 6         | 0.06%   |
| Tremont          | 4         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5285      | 42.73%  |
| Nvidia                           | 4118      | 33.3%   |
| AMD                              | 2932      | 23.71%  |
| Matrox Electronics Systems       | 15        | 0.12%   |
| Silicon Integrated Systems [SiS] | 8         | 0.06%   |
| ASPEED Technology                | 8         | 0.06%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 461       | 3.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 356       | 2.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 356       | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 295       | 2.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 290       | 2.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 290       | 2.28%   |
| Intel UHD Graphics 620                                                                   | 285       | 2.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 281       | 2.21%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 239       | 1.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 219       | 1.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 218       | 1.72%   |
| Intel HD Graphics 620                                                                    | 196       | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 189       | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 184       | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 178       | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 174       | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 167       | 1.32%   |
| Intel HD Graphics 630                                                                    | 160       | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 148       | 1.17%   |
| Intel HD Graphics 5500                                                                   | 145       | 1.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 136       | 1.07%   |
| Intel HD Graphics 530                                                                    | 135       | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 131       | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 115       | 0.91%   |
| AMD Lucienne                                                                             | 112       | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 99        | 0.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 98        | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 96        | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 92        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 91        | 0.72%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 91        | 0.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 89        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 86        | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 84        | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 80        | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 75        | 0.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 72        | 0.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 71        | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 70        | 0.55%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 68        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 3437      | 33.68%  |
| 1 x Nvidia              | 2238      | 21.93%  |
| 1 x AMD                 | 2191      | 21.47%  |
| Intel + Nvidia          | 1484      | 14.54%  |
| AMD + Nvidia            | 320       | 3.14%   |
| Intel + AMD             | 241       | 2.36%   |
| 2 x AMD                 | 182       | 1.78%   |
| 2 x Nvidia              | 47        | 0.46%   |
| Other                   | 24        | 0.24%   |
| 1 x SiS                 | 8         | 0.08%   |
| 1 x Matrox              | 8         | 0.08%   |
| Nvidia + Matrox         | 4         | 0.04%   |
| Nvidia + ASPEED         | 4         | 0.04%   |
| Intel + 2 x Nvidia      | 4         | 0.04%   |
| AMD + ASPEED            | 3         | 0.03%   |
| AMD + Matrox            | 2         | 0.02%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x Intel               | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| 1 x ASPEED              | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6520      | 63.78%  |
| Proprietary | 3302      | 32.3%   |
| Unknown     | 401       | 3.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7118      | 69.08%  |
| 1.01-2.0   | 685       | 6.65%   |
| 3.01-4.0   | 634       | 6.15%   |
| 7.01-8.0   | 600       | 5.82%   |
| 5.01-6.0   | 439       | 4.26%   |
| 0.01-0.5   | 326       | 3.16%   |
| 0.51-1.0   | 195       | 1.89%   |
| 8.01-16.0  | 190       | 1.84%   |
| 2.01-3.0   | 84        | 0.82%   |
| 16.01-24.0 | 28        | 0.27%   |
| 4.01-5.0   | 3         | 0.03%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1359      | 11.87%  |
| AU Optronics            | 1230      | 10.75%  |
| Chimei Innolux          | 998       | 8.72%   |
| LG Display              | 944       | 8.25%   |
| BOE                     | 929       | 8.12%   |
| Goldstar                | 723       | 6.32%   |
| Dell                    | 708       | 6.19%   |
| Acer                    | 461       | 4.03%   |
| Apple                   | 351       | 3.07%   |
| Hewlett-Packard         | 347       | 3.03%   |
| AOC                     | 326       | 2.85%   |
| Sharp                   | 275       | 2.4%    |
| BenQ                    | 249       | 2.18%   |
| Ancor Communications    | 245       | 2.14%   |
| Philips                 | 187       | 1.63%   |
| ASUSTek Computer        | 185       | 1.62%   |
| Lenovo                  | 169       | 1.48%   |
| PANDA                   | 156       | 1.36%   |
| ViewSonic               | 103       | 0.9%    |
| Chi Mei Optoelectronics | 101       | 0.88%   |
| Iiyama                  | 90        | 0.79%   |
| InfoVision              | 79        | 0.69%   |
| Sony                    | 73        | 0.64%   |
| MSI                     | 71        | 0.62%   |
| Sceptre Tech            | 56        | 0.49%   |
| Vizio                   | 48        | 0.42%   |
| Panasonic               | 47        | 0.41%   |
| CSO                     | 41        | 0.36%   |
| Gigabyte Technology     | 37        | 0.32%   |
| Toshiba                 | 36        | 0.31%   |
| NEC Computers           | 27        | 0.24%   |
| Unknown                 | 26        | 0.23%   |
| Eizo                    | 25        | 0.22%   |
| Insignia                | 23        | 0.2%    |
| Fujitsu Siemens         | 22        | 0.19%   |
| Hitachi                 | 20        | 0.17%   |
| Vestel Elektronik       | 19        | 0.17%   |
| LG Electronics          | 18        | 0.16%   |
| TMX                     | 17        | 0.15%   |
| MStar                   | 16        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 75        | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 75        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 58        | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 54        | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 52        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 51        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 50        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 45        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 41        | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 39        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 35        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 33        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 33        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 32        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 30        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 30        | 0.25%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 29        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 27        | 0.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 26        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 26        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 25        | 0.21%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 25        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 25        | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 24        | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 23        | 0.19%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 23        | 0.19%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 23        | 0.19%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 23        | 0.19%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 22        | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 22        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 22        | 0.19%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 22        | 0.19%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch               | 21        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 21        | 0.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 21        | 0.18%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 20        | 0.17%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 20        | 0.17%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 19        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 19        | 0.16%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 19        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 5074      | 46.9%   |
| 1366x768 (WXGA)    | 1644      | 15.2%   |
| 3840x2160 (4K)     | 961       | 8.88%   |
| 2560x1440 (QHD)    | 687       | 6.35%   |
| 1600x900 (HD+)     | 335       | 3.1%    |
| 1920x1200 (WUXGA)  | 252       | 2.33%   |
| 3440x1440          | 212       | 1.96%   |
| 1680x1050 (WSXGA+) | 205       | 1.89%   |
| 1440x900 (WXGA+)   | 201       | 1.86%   |
| 2560x1080          | 195       | 1.8%    |
| 1280x1024 (SXGA)   | 169       | 1.56%   |
| 1280x800 (WXGA)    | 145       | 1.34%   |
| 2560x1600          | 116       | 1.07%   |
| 2880x1800          | 84        | 0.78%   |
| 1360x768           | 68        | 0.63%   |
| 3840x1080          | 51        | 0.47%   |
| 1920x540           | 48        | 0.44%   |
| 3840x2400          | 44        | 0.41%   |
| Unknown            | 36        | 0.33%   |
| 2160x1440          | 34        | 0.31%   |
| 2736x1824          | 22        | 0.2%    |
| 3200x1800 (QHD+)   | 19        | 0.18%   |
| 3840x1600          | 18        | 0.17%   |
| 2256x1504          | 18        | 0.17%   |
| 1024x768 (XGA)     | 16        | 0.15%   |
| 3072x1920          | 14        | 0.13%   |
| 3000x2000          | 14        | 0.13%   |
| 1600x1200          | 14        | 0.13%   |
| 1280x720 (HD)      | 14        | 0.13%   |
| 1920x1280          | 12        | 0.11%   |
| 3456x2160          | 7         | 0.06%   |
| 3200x2000          | 7         | 0.06%   |
| 2048x1152          | 6         | 0.06%   |
| 4480x1440          | 4         | 0.04%   |
| 3840x1200          | 4         | 0.04%   |
| 3840x1100          | 4         | 0.04%   |
| 2880x1620          | 4         | 0.04%   |
| 2288x1287          | 4         | 0.04%   |
| 2240x1400          | 4         | 0.04%   |
| 5120x1440          | 3         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2844      | 24.86%  |
| 13      | 1109      | 9.69%   |
| 27      | 1045      | 9.13%   |
| 24      | 890       | 7.78%   |
| 14      | 822       | 7.19%   |
| 23      | 702       | 6.14%   |
| 21      | 577       | 5.04%   |
| 17      | 560       | 4.9%    |
| 31      | 392       | 3.43%   |
| 34      | 344       | 3.01%   |
| 19      | 206       | 1.8%    |
| Unknown | 190       | 1.66%   |
| 12      | 175       | 1.53%   |
| 18      | 170       | 1.49%   |
| 22      | 142       | 1.24%   |
| 16      | 139       | 1.22%   |
| 20      | 126       | 1.1%    |
| 84      | 118       | 1.03%   |
| 32      | 100       | 0.87%   |
| 11      | 91        | 0.8%    |
| 72      | 82        | 0.72%   |
| 40      | 74        | 0.65%   |
| 54      | 60        | 0.52%   |
| 48      | 46        | 0.4%    |
| 26      | 44        | 0.38%   |
| 25      | 41        | 0.36%   |
| 28      | 35        | 0.31%   |
| 35      | 29        | 0.25%   |
| 52      | 28        | 0.24%   |
| 65      | 23        | 0.2%    |
| 49      | 22        | 0.19%   |
| 37      | 22        | 0.19%   |
| 29      | 21        | 0.18%   |
| 46      | 19        | 0.17%   |
| 36      | 16        | 0.14%   |
| 33      | 16        | 0.14%   |
| 42      | 13        | 0.11%   |
| 74      | 9         | 0.08%   |
| 43      | 9         | 0.08%   |
| 55      | 8         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 4308      | 38.47%  |
| 501-600        | 2379      | 21.25%  |
| 401-500        | 1103      | 9.85%   |
| 201-300        | 850       | 7.59%   |
| 351-400        | 683       | 6.1%    |
| 601-700        | 584       | 5.22%   |
| 701-800        | 464       | 4.14%   |
| 1001-1500      | 237       | 2.12%   |
| 1501-2000      | 219       | 1.96%   |
| Unknown        | 190       | 1.7%    |
| 801-900        | 145       | 1.29%   |
| 901-1000       | 28        | 0.25%   |
| 101-200        | 3         | 0.03%   |
| More than 2000 | 2         | 0.02%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7975      | 79.25%  |
| 16/10   | 1145      | 11.38%  |
| 21/9    | 415       | 4.12%   |
| 5/4     | 167       | 1.66%   |
| 3/2     | 113       | 1.12%   |
| Unknown | 107       | 1.06%   |
| 32/9    | 57        | 0.57%   |
| 4/3     | 53        | 0.53%   |
| 6/5     | 10        | 0.1%    |
| 1.96    | 5         | 0.05%   |
| 3.40    | 4         | 0.04%   |
| 3.20    | 3         | 0.03%   |
| 3.73    | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 1.00    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2828      | 25.01%  |
| 201-250        | 1829      | 16.18%  |
| 81-90          | 1511      | 13.36%  |
| 301-350        | 1076      | 9.52%   |
| 351-500        | 890       | 7.87%   |
| 151-200        | 492       | 4.35%   |
| 121-130        | 452       | 4%      |
| 71-80          | 429       | 3.79%   |
| More than 1000 | 377       | 3.33%   |
| 251-300        | 326       | 2.88%   |
| 501-1000       | 233       | 2.06%   |
| 141-150        | 220       | 1.95%   |
| Unknown        | 190       | 1.68%   |
| 61-70          | 146       | 1.29%   |
| 111-120        | 131       | 1.16%   |
| 51-60          | 95        | 0.84%   |
| 131-140        | 46        | 0.41%   |
| 91-100         | 23        | 0.2%    |
| 41-50          | 8         | 0.07%   |
| 1-40           | 5         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3423      | 31.42%  |
| 121-160       | 3222      | 29.58%  |
| 101-120       | 2675      | 24.55%  |
| 161-240       | 734       | 6.74%   |
| More than 240 | 352       | 3.23%   |
| 1-50          | 298       | 2.74%   |
| Unknown       | 190       | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7731      | 74.76%  |
| 2     | 1885      | 18.23%  |
| 0     | 473       | 4.57%   |
| 3     | 230       | 2.22%   |
| 4     | 20        | 0.19%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5488      | 35.32%  |
| Intel                             | 5212      | 33.54%  |
| Qualcomm Atheros                  | 1583      | 10.19%  |
| Broadcom                          | 905       | 5.82%   |
| MediaTek                          | 265       | 1.71%   |
| Broadcom Limited                  | 209       | 1.34%   |
| TP-Link                           | 172       | 1.11%   |
| Ralink Technology                 | 157       | 1.01%   |
| Marvell Technology Group          | 143       | 0.92%   |
| Nvidia                            | 128       | 0.82%   |
| Ralink                            | 115       | 0.74%   |
| Samsung Electronics               | 94        | 0.6%    |
| ASIX Electronics                  | 88        | 0.57%   |
| Microsoft                         | 82        | 0.53%   |
| NetGear                           | 58        | 0.37%   |
| Xiaomi                            | 50        | 0.32%   |
| Aquantia                          | 45        | 0.29%   |
| Qualcomm Atheros Communications   | 43        | 0.28%   |
| Google                            | 43        | 0.28%   |
| DisplayLink                       | 43        | 0.28%   |
| InterBiometrics                   | 38        | 0.24%   |
| Dell                              | 36        | 0.23%   |
| ASUSTek Computer                  | 35        | 0.23%   |
| Lenovo                            | 32        | 0.21%   |
| Sierra Wireless                   | 31        | 0.2%    |
| Qualcomm                          | 30        | 0.19%   |
| D-Link                            | 30        | 0.19%   |
| Huawei Technologies               | 29        | 0.19%   |
| Linksys                           | 27        | 0.17%   |
| Ericsson Business Mobile Networks | 23        | 0.15%   |
| JMicron Technology                | 21        | 0.14%   |
| OnePlus Technology (Shenzhen)     | 20        | 0.13%   |
| OPPO Electronics                  | 19        | 0.12%   |
| Edimax Technology                 | 18        | 0.12%   |
| Motorola PCS                      | 17        | 0.11%   |
| Hewlett-Packard                   | 17        | 0.11%   |
| D-Link System                     | 14        | 0.09%   |
| Belkin Components                 | 10        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.06%   |
| Fibocom                           | 9         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3741      | 20.48%  |
| Intel Wi-Fi 6 AX200                                               | 779       | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 507       | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 442       | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 339       | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 326       | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 325       | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 321       | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 301       | 1.65%   |
| Intel Wi-Fi 6 AX201                                               | 239       | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 226       | 1.24%   |
| Intel Wireless 7265                                               | 213       | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 208       | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 205       | 1.12%   |
| Intel Wireless 7260                                               | 204       | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 195       | 1.07%   |
| Intel Ethernet Controller I225-V                                  | 191       | 1.05%   |
| Intel Wireless 8260                                               | 183       | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 183       | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 176       | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 169       | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 166       | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 165       | 0.9%    |
| Intel Wireless-AC 9260                                            | 165       | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 160       | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 145       | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 126       | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 124       | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 124       | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 121       | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 120       | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 118       | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 112       | 0.61%   |
| Intel Wireless 3165                                               | 108       | 0.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 100       | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                     | 93        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 90        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 90        | 0.49%   |
| Realtek 802.11ac NIC                                              | 89        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 85        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4117      | 47.28%  |
| Realtek Semiconductor                 | 1321      | 15.17%  |
| Qualcomm Atheros                      | 1232      | 14.15%  |
| Broadcom                              | 695       | 7.98%   |
| MediaTek                              | 256       | 2.94%   |
| Broadcom Limited                      | 166       | 1.91%   |
| TP-Link                               | 157       | 1.8%    |
| Ralink Technology                     | 157       | 1.8%    |
| Ralink                                | 115       | 1.32%   |
| Microsoft                             | 77        | 0.88%   |
| NetGear                               | 56        | 0.64%   |
| Qualcomm Atheros Communications       | 43        | 0.49%   |
| Marvell Technology Group              | 40        | 0.46%   |
| Dell                                  | 32        | 0.37%   |
| ASUSTek Computer                      | 32        | 0.37%   |
| Sierra Wireless                       | 31        | 0.36%   |
| D-Link                                | 29        | 0.33%   |
| Qualcomm                              | 23        | 0.26%   |
| Linksys                               | 23        | 0.26%   |
| Edimax Technology                     | 14        | 0.16%   |
| D-Link System                         | 10        | 0.11%   |
| Belkin Components                     | 10        | 0.11%   |
| Fibocom                               | 9         | 0.1%    |
| AVM                                   | 8         | 0.09%   |
| Hewlett-Packard                       | 7         | 0.08%   |
| Sitecom Europe                        | 6         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 6         | 0.07%   |
| Gemtek                                | 5         | 0.06%   |
| Mercucys                              | 4         | 0.05%   |
| IMC Networks                          | 3         | 0.03%   |
| Ericsson Business Mobile Networks     | 3         | 0.03%   |
| Accton Technology                     | 3         | 0.03%   |
| ZyDAS                                 | 2         | 0.02%   |
| Wilocity                              | 2         | 0.02%   |
| Wacom                                 | 2         | 0.02%   |
| Samsung Electronics                   | 2         | 0.02%   |
| Ovislink                              | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| TRENDnet                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 779       | 8.88%   |
| Intel Wireless 8265 / 8275                                           | 321       | 3.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 301       | 3.43%   |
| Intel Wi-Fi 6 AX201                                                  | 239       | 2.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 226       | 2.58%   |
| Intel Wireless 7265                                                  | 213       | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 208       | 2.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 205       | 2.34%   |
| Intel Wireless 7260                                                  | 204       | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 195       | 2.22%   |
| Intel Wireless 8260                                                  | 183       | 2.09%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 183       | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 176       | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 166       | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 165       | 1.88%   |
| Intel Wireless-AC 9260                                               | 165       | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 160       | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 126       | 1.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 124       | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 124       | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 121       | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 120       | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 112       | 1.28%   |
| Intel Wireless 3165                                                  | 108       | 1.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 100       | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 93        | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 90        | 1.03%   |
| Realtek 802.11ac NIC                                                 | 89        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 85        | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 85        | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 81        | 0.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 76        | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 74        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 74        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 71        | 0.81%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 71        | 0.81%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 70        | 0.8%    |
| Intel Wireless 3160                                                  | 67        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 66        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                      | 61        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4953      | 54.22%  |
| Intel                            | 2470      | 27.04%  |
| Qualcomm Atheros                 | 482       | 5.28%   |
| Broadcom                         | 382       | 4.18%   |
| Nvidia                           | 128       | 1.4%    |
| Marvell Technology Group         | 103       | 1.13%   |
| ASIX Electronics                 | 88        | 0.96%   |
| Samsung Electronics              | 54        | 0.59%   |
| Xiaomi                           | 50        | 0.55%   |
| Broadcom Limited                 | 47        | 0.51%   |
| Aquantia                         | 45        | 0.49%   |
| Google                           | 43        | 0.47%   |
| DisplayLink                      | 43        | 0.47%   |
| Lenovo                           | 32        | 0.35%   |
| Huawei Technologies              | 26        | 0.28%   |
| JMicron Technology               | 21        | 0.23%   |
| OPPO Electronics                 | 19        | 0.21%   |
| OnePlus Technology (Shenzhen)    | 16        | 0.18%   |
| TP-Link                          | 15        | 0.16%   |
| Motorola PCS                     | 12        | 0.13%   |
| Silicon Integrated Systems [SiS] | 9         | 0.1%    |
| MediaTek                         | 8         | 0.09%   |
| Qualcomm                         | 7         | 0.08%   |
| ICS Advent                       | 7         | 0.08%   |
| Apple                            | 6         | 0.07%   |
| VIA Technologies                 | 5         | 0.05%   |
| Microsoft                        | 5         | 0.05%   |
| Mellanox Technologies            | 4         | 0.04%   |
| Linksys                          | 4         | 0.04%   |
| Hewlett-Packard                  | 4         | 0.04%   |
| Edimax Technology                | 4         | 0.04%   |
| D-Link System                    | 4         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.03%   |
| T & A Mobile Phones              | 3         | 0.03%   |
| LG Electronics                   | 3         | 0.03%   |
| ASUSTek Computer                 | 3         | 0.03%   |
| NetGear                          | 2         | 0.02%   |
| LSI                              | 2         | 0.02%   |
| American Megatrends              | 2         | 0.02%   |
| 3Com                             | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3741      | 40.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 507       | 5.44%   |
| Intel I211 Gigabit Network Connection                             | 442       | 4.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 339       | 3.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 326       | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 325       | 3.49%   |
| Intel Ethernet Controller I225-V                                  | 191       | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 169       | 1.81%   |
| Intel Ethernet Connection I217-LM                                 | 145       | 1.56%   |
| Intel Ethernet Connection (7) I219-V                              | 118       | 1.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 90        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 83        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 77        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 77        | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 71        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 67        | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 64        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 63        | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 63        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 61        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 61        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 59        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 56        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 54        | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 54        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                              | 52        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 50        | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 44        | 0.47%   |
| Intel Ethernet Connection (4) I219-V                              | 44        | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 43        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 43        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 40        | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 40        | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 38        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 37        | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 37        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 36        | 0.39%   |
| Intel 82577LM Gigabit Network Connection                          | 34        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 32        | 0.34%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 32        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8536      | 50.44%  |
| WiFi     | 8216      | 48.55%  |
| Modem    | 140       | 0.83%   |
| Unknown  | 31        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 6379      | 59.53%  |
| Ethernet | 4329      | 40.4%   |
| Modem    | 4         | 0.04%   |
| Unknown  | 3         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 5654      | 55.85%  |
| 1     | 4052      | 40.02%  |
| 3     | 246       | 2.43%   |
| 0     | 124       | 1.22%   |
| 4     | 36        | 0.36%   |
| 5     | 8         | 0.08%   |
| 10    | 2         | 0.02%   |
| 6     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7932      | 77.21%  |
| Yes  | 2341      | 22.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3588      | 51.37%  |
| Realtek Semiconductor           | 591       | 8.46%   |
| Qualcomm Atheros Communications | 525       | 7.52%   |
| Apple                           | 425       | 6.08%   |
| Cambridge Silicon Radio         | 366       | 5.24%   |
| IMC Networks                    | 286       | 4.09%   |
| Broadcom                        | 277       | 3.97%   |
| Lite-On Technology              | 220       | 3.15%   |
| Foxconn / Hon Hai               | 185       | 2.65%   |
| ASUSTek Computer                | 108       | 1.55%   |
| Dell                            | 74        | 1.06%   |
| MediaTek                        | 52        | 0.74%   |
| Marvell Semiconductor           | 42        | 0.6%    |
| Realtek                         | 37        | 0.53%   |
| Ralink                          | 36        | 0.52%   |
| Toshiba                         | 32        | 0.46%   |
| Hewlett-Packard                 | 32        | 0.46%   |
| TP-Link                         | 18        | 0.26%   |
| Foxconn International           | 12        | 0.17%   |
| Dynex                           | 9         | 0.13%   |
| Ralink Technology               | 8         | 0.11%   |
| Alps Electric                   | 7         | 0.1%    |
| Integrated System Solution      | 5         | 0.07%   |
| Actions                         | 5         | 0.07%   |
| USI                             | 4         | 0.06%   |
| Smart Modular Technologies      | 4         | 0.06%   |
| HTC (High Tech Computer)        | 4         | 0.06%   |
| Askey Computer                  | 4         | 0.06%   |
| Taiyo Yuden                     | 3         | 0.04%   |
| SINO WEALTH                     | 3         | 0.04%   |
| Qcom                            | 3         | 0.04%   |
| Opticis                         | 3         | 0.04%   |
| Micro Star International        | 3         | 0.04%   |
| Creative Technology             | 3         | 0.04%   |
| Logitech                        | 2         | 0.03%   |
| Fujitsu                         | 2         | 0.03%   |
| Edimax Technology               | 2         | 0.03%   |
| Conwise Technology              | 2         | 0.03%   |
| Belkin Components               | 2         | 0.03%   |
| Primax Electronics              | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1053      | 15.06%  |
| Intel Bluetooth Device                              | 772       | 11.04%  |
| Intel AX200 Bluetooth                               | 744       | 10.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 476       | 6.81%   |
| Realtek Bluetooth Radio                             | 380       | 5.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 366       | 5.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 289       | 4.13%   |
| Apple Bluetooth Host Controller                     | 179       | 2.56%   |
| Apple Bluetooth USB Host Controller                 | 158       | 2.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 157       | 2.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 152       | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 141       | 2.02%   |
| Intel AX210 Bluetooth                               | 117       | 1.67%   |
| IMC Networks Bluetooth Radio                        | 89        | 1.27%   |
| IMC Networks Wireless_Device                        | 85        | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 78        | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 77        | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 67        | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 65        | 0.93%   |
| IMC Networks Bluetooth Device                       | 57        | 0.82%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 56        | 0.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 53        | 0.76%   |
| MediaTek Wireless_Device                            | 52        | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 51        | 0.73%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 50        | 0.72%   |
| Lite-On Bluetooth Device                            | 50        | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 45        | 0.64%   |
| Realtek Bluetooth Radio                             | 37        | 0.53%   |
| Ralink RT3290 Bluetooth                             | 36        | 0.51%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 36        | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 35        | 0.5%    |
| Apple Bluetooth HCI                                 | 35        | 0.5%    |
| Marvell Bluetooth and Wireless LAN Composite        | 29        | 0.41%   |
| Dell DW375 Bluetooth Module                         | 27        | 0.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 25        | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.36%   |
| ASUS Bluetooth Radio                                | 25        | 0.36%   |
| Realtek RTL8821A Bluetooth                          | 22        | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 6810      | 43.84%  |
| AMD                                             | 3473      | 22.36%  |
| Nvidia                                          | 3286      | 21.16%  |
| C-Media Electronics                             | 280       | 1.8%    |
| Logitech                                        | 158       | 1.02%   |
| Kingston Technology                             | 83        | 0.53%   |
| JMTek                                           | 80        | 0.52%   |
| Creative Labs                                   | 79        | 0.51%   |
| Razer USA                                       | 76        | 0.49%   |
| Corsair                                         | 69        | 0.44%   |
| Texas Instruments                               | 61        | 0.39%   |
| SteelSeries ApS                                 | 60        | 0.39%   |
| Realtek Semiconductor                           | 60        | 0.39%   |
| Focusrite-Novation                              | 56        | 0.36%   |
| ASUSTek Computer                                | 53        | 0.34%   |
| Generalplus Technology                          | 47        | 0.3%    |
| GN Netcom                                       | 44        | 0.28%   |
| Creative Technology                             | 40        | 0.26%   |
| Lenovo                                          | 35        | 0.23%   |
| Blue Microphones                                | 33        | 0.21%   |
| Micro Star International                        | 29        | 0.19%   |
| Sony                                            | 28        | 0.18%   |
| Plantronics                                     | 28        | 0.18%   |
| Apple                                           | 24        | 0.15%   |
| DSEA A/S                                        | 21        | 0.14%   |
| Giga-Byte Technology                            | 19        | 0.12%   |
| Astro Gaming                                    | 19        | 0.12%   |
| Samson Technologies                             | 16        | 0.1%    |
| Hewlett-Packard                                 | 16        | 0.1%    |
| Tenx Technology                                 | 15        | 0.1%    |
| Yamaha                                          | 14        | 0.09%   |
| FiiO Electronics Technology                     | 14        | 0.09%   |
| Valve Software                                  | 13        | 0.08%   |
| Turtle Beach                                    | 13        | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 13        | 0.08%   |
| SAVITECH                                        | 12        | 0.08%   |
| M-Audio                                         | 12        | 0.08%   |
| Silicon Integrated Systems [SiS]                | 10        | 0.06%   |
| Licensed by Sony Computer Entertainment America | 10        | 0.06%   |
| Dell                                            | 10        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1175      | 6.34%   |
| AMD Starship/Matisse HD Audio Controller                                   | 778       | 4.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 768       | 4.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 628       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 607       | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 534       | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 530       | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 506       | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 363       | 1.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 331       | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 317       | 1.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 304       | 1.64%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 297       | 1.6%    |
| Intel 8 Series HD Audio Controller                                         | 293       | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 290       | 1.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 289       | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 259       | 1.4%    |
| Nvidia GP107GL High Definition Audio Controller                            | 250       | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 242       | 1.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 237       | 1.28%   |
| AMD FCH Azalia Controller                                                  | 234       | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 230       | 1.24%   |
| Nvidia GP104 High Definition Audio Controller                              | 227       | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 215       | 1.16%   |
| Intel Broadwell-U Audio Controller                                         | 215       | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 211       | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 209       | 1.13%   |
| Nvidia GP106 High Definition Audio Controller                              | 208       | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 207       | 1.12%   |
| Intel 200 Series PCH HD Audio                                              | 207       | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                              | 206       | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 205       | 1.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 185       | 1%      |
| AMD Navi 10 HDMI Audio                                                     | 175       | 0.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 154       | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                              | 150       | 0.81%   |
| Nvidia TU104 HD Audio Controller                                           | 149       | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 149       | 0.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 147       | 0.79%   |
| Nvidia Audio device                                                        | 137       | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 655       | 22.88%  |
| SK hynix            | 521       | 18.2%   |
| Micron Technology   | 324       | 11.32%  |
| Kingston            | 296       | 10.34%  |
| Corsair             | 208       | 7.27%   |
| Crucial             | 190       | 6.64%   |
| G.Skill             | 137       | 4.79%   |
| Unknown             | 121       | 4.23%   |
| A-DATA Technology   | 64        | 2.24%   |
| Team                | 42        | 1.47%   |
| Smart               | 37        | 1.29%   |
| Ramaxel Technology  | 35        | 1.22%   |
| Elpida              | 27        | 0.94%   |
| Goldkey             | 24        | 0.84%   |
| Unknown             | 23        | 0.8%    |
| Neo Forza           | 22        | 0.77%   |
| Unknown (ABCD)      | 18        | 0.63%   |
| Patriot             | 15        | 0.52%   |
| Smart Brazil        | 10        | 0.35%   |
| Teikon              | 8         | 0.28%   |
| Nanya Technology    | 8         | 0.28%   |
| Apacer              | 7         | 0.24%   |
| Transcend           | 5         | 0.17%   |
| Avant               | 5         | 0.17%   |
| PNY                 | 4         | 0.14%   |
| Timetec             | 3         | 0.1%    |
| Silicon Power       | 3         | 0.1%    |
| High Bridge         | 3         | 0.1%    |
| GSkill              | 3         | 0.1%    |
| GOODRAM             | 3         | 0.1%    |
| CSX                 | 3         | 0.1%    |
| ChangXin Memory     | 3         | 0.1%    |
| Patriot Memory      | 2         | 0.07%   |
| OLOY                | 2         | 0.07%   |
| Gold Key            | 2         | 0.07%   |
| AMD                 | 2         | 0.07%   |
| Wilk                | 1         | 0.03%   |
| Unknown (8A02)      | 1         | 0.03%   |
| Unknown (898F)      | 1         | 0.03%   |
| Unknown (0x0CAB)    | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 51        | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 36        | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 32        | 1.06%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 27        | 0.9%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.83%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 23        | 0.76%   |
| Unknown                                                          | 23        | 0.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.73%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 20        | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 20        | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 19        | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.6%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 16        | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.5%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.5%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 15        | 0.5%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 14        | 0.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.47%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 14        | 0.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.4%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 12        | 0.4%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 11        | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 11        | 0.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 11        | 0.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.37%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1637      | 66.09%  |
| DDR3    | 459       | 18.53%  |
| LPDDR4  | 105       | 4.24%   |
| DDR5    | 89        | 3.59%   |
| LPDDR3  | 81        | 3.27%   |
| LPDDR5  | 45        | 1.82%   |
| DDR2    | 27        | 1.09%   |
| Unknown | 20        | 0.81%   |
| SDRAM   | 12        | 0.48%   |
| DDR     | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1527      | 61.01%  |
| DIMM         | 688       | 27.49%  |
| Row Of Chips | 269       | 10.75%  |
| Chip         | 14        | 0.56%   |
| Unknown      | 4         | 0.16%   |
| RIMM         | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1202      | 44.93%  |
| 16384 | 591       | 22.09%  |
| 4096  | 558       | 20.86%  |
| 32768 | 173       | 6.47%   |
| 2048  | 127       | 4.75%   |
| 1024  | 22        | 0.82%   |
| 512   | 2         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 577       | 21.51%  |
| 2667    | 545       | 20.32%  |
| 1600    | 327       | 12.19%  |
| 2400    | 208       | 7.76%   |
| 2133    | 137       | 5.11%   |
| 3600    | 129       | 4.81%   |
| 1333    | 75        | 2.8%    |
| 4800    | 60        | 2.24%   |
| 4267    | 56        | 2.09%   |
| 1867    | 51        | 1.9%    |
| 6400    | 46        | 1.72%   |
| 3733    | 35        | 1.3%    |
| 3266    | 35        | 1.3%    |
| 1334    | 32        | 1.19%   |
| 3000    | 28        | 1.04%   |
| 3800    | 26        | 0.97%   |
| 3400    | 25        | 0.93%   |
| 800     | 22        | 0.82%   |
| 8400    | 20        | 0.75%   |
| 2933    | 19        | 0.71%   |
| 3866    | 16        | 0.6%    |
| 4266    | 15        | 0.56%   |
| 3533    | 15        | 0.56%   |
| 5600    | 14        | 0.52%   |
| 1866    | 14        | 0.52%   |
| 1067    | 14        | 0.52%   |
| 667     | 13        | 0.48%   |
| 2666    | 11        | 0.41%   |
| 2800    | 10        | 0.37%   |
| 3534    | 9         | 0.34%   |
| 3466    | 8         | 0.3%    |
| 1800    | 8         | 0.3%    |
| Unknown | 8         | 0.3%    |
| 6000    | 7         | 0.26%   |
| 4000    | 6         | 0.22%   |
| 5200    | 5         | 0.19%   |
| 4400    | 5         | 0.19%   |
| 3666    | 5         | 0.19%   |
| 3333    | 4         | 0.15%   |
| 1066    | 4         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 63        | 32.47%  |
| Brother Industries    | 35        | 18.04%  |
| Canon                 | 29        | 14.95%  |
| Samsung Electronics   | 22        | 11.34%  |
| Seiko Epson           | 21        | 10.82%  |
| Dymo-CoStar           | 6         | 3.09%   |
| STMicroelectronics    | 3         | 1.55%   |
| Fuji Xerox            | 3         | 1.55%   |
| Xerox                 | 2         | 1.03%   |
| QinHeng Electronics   | 2         | 1.03%   |
| Prolific Technology   | 1         | 0.52%   |
| Oki Data              | 1         | 0.52%   |
| MIIIW                 | 1         | 0.52%   |
| Lexmark International | 1         | 0.52%   |
| Kyocera               | 1         | 0.52%   |
| ICS Advent            | 1         | 0.52%   |
| Dell                  | 1         | 0.52%   |
| Apple                 | 1         | 0.52%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                               | 5         | 2.56%   |
| Samsung M2020 Series                                      | 4         | 2.05%   |
| Canon PIXMA MX920 Series                                  | 4         | 2.05%   |
| Seiko Epson ET-2700 Series                                | 3         | 1.54%   |
| Samsung SCX-3400 Series                                   | 3         | 1.54%   |
| Samsung ML-1640 Series Laser Printer                      | 3         | 1.54%   |
| HP LaserJet Professional P 1102w                          | 3         | 1.54%   |
| Dymo-CoStar LabelWriter 450                               | 3         | 1.54%   |
| Brother Printer                                           | 3         | 1.54%   |
| Brother HL-2270DW Laser Printer                           | 3         | 1.54%   |
| Brother HL-2130 series                                    | 3         | 1.54%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.03%   |
| Seiko Epson WF-4830 Series                                | 2         | 1.03%   |
| Seiko Epson WF-3520 Series                                | 2         | 1.03%   |
| Seiko Epson L355 Series                                   | 2         | 1.03%   |
| Seiko Epson L3110 Series                                  | 2         | 1.03%   |
| Seiko Epson ET-2600 Series                                | 2         | 1.03%   |
| Samsung M2070 Series                                      | 2         | 1.03%   |
| QinHeng CH340S                                            | 2         | 1.03%   |
| HP OfficeJet 3830 series                                  | 2         | 1.03%   |
| HP ENVY Pro 6400 series                                   | 2         | 1.03%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.03%   |
| HP ENVY 4520 series                                       | 2         | 1.03%   |
| HP ENVY 4500 series                                       | 2         | 1.03%   |
| HP DeskJet F4100 Printer series                           | 2         | 1.03%   |
| HP Deskjet F2280 series                                   | 2         | 1.03%   |
| HP DeskJet 2600 series                                    | 2         | 1.03%   |
| HP Deskjet 2540 series                                    | 2         | 1.03%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.03%   |
| Fuji Xerox DocuPrint CM315/318 z                          | 2         | 1.03%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 2         | 1.03%   |
| Canon PIXMA MG2500 Series                                 | 2         | 1.03%   |
| Brother HL-L3230CDW series                                | 2         | 1.03%   |
| Brother HL-1110 series                                    | 2         | 1.03%   |
| Xerox Phaser 6000B                                        | 1         | 0.51%   |
| Xerox B215                                                | 1         | 0.51%   |
| STMicroelectronics USB Printer P                          | 1         | 0.51%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.51%   |
| Seiko Epson L6160 Series                                  | 1         | 0.51%   |
| Seiko Epson L382 Series                                   | 1         | 0.51%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 47.83%  |
| Seiko Epson     | 7         | 30.43%  |
| Hewlett-Packard | 4         | 17.39%  |
| Mustek Systems  | 1         | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson Scanner                                     | 2         | 8.7%    |
| Canon CanoScan N1240U/LiDE 30                           | 2         | 8.7%    |
| Canon CanoScan LiDE 210                                 | 2         | 8.7%    |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 4.35%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4.35%   |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1         | 4.35%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 4.35%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 4.35%   |
| HP Scanjet G2710                                        | 1         | 4.35%   |
| HP ScanJet 82x0C                                        | 1         | 4.35%   |
| HP Scanjet 300                                          | 1         | 4.35%   |
| HP ScanJet 2400c                                        | 1         | 4.35%   |
| Canon CanoScan N650U/N656U                              | 1         | 4.35%   |
| Canon CanoScan LiDE 60                                  | 1         | 4.35%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 4.35%   |
| Canon CanoScan LiDE 220                                 | 1         | 4.35%   |
| Canon CanoScan LiDE 200                                 | 1         | 4.35%   |
| Canon CanoScan LiDE 110                                 | 1         | 4.35%   |
| Canon CanoScan 9000F Mark II                            | 1         | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1259      | 20.38%  |
| IMC Networks                           | 587       | 9.5%    |
| Microdia                               | 574       | 9.29%   |
| Realtek Semiconductor                  | 448       | 7.25%   |
| Logitech                               | 407       | 6.59%   |
| Bison Electronics                      | 384       | 6.22%   |
| Apple                                  | 328       | 5.31%   |
| Sunplus Innovation Technology          | 315       | 5.1%    |
| Quanta                                 | 284       | 4.6%    |
| Cheng Uei Precision Industry (Foxlink) | 184       | 2.98%   |
| Acer                                   | 174       | 2.82%   |
| Syntek                                 | 147       | 2.38%   |
| Suyin                                  | 133       | 2.15%   |
| Lite-On Technology                     | 114       | 1.85%   |
| Luxvisions Innotech Limited            | 102       | 1.65%   |
| Silicon Motion                         | 72        | 1.17%   |
| Microsoft                              | 71        | 1.15%   |
| Samsung Electronics                    | 50        | 0.81%   |
| Ricoh                                  | 39        | 0.63%   |
| Alcor Micro                            | 39        | 0.63%   |
| Sonix Technology                       | 33        | 0.53%   |
| Generalplus Technology                 | 27        | 0.44%   |
| Z-Star Microelectronics                | 22        | 0.36%   |
| SunplusIT                              | 20        | 0.32%   |
| Razer USA                              | 18        | 0.29%   |
| ARC International                      | 17        | 0.28%   |
| ALi                                    | 15        | 0.24%   |
| MacroSilicon                           | 14        | 0.23%   |
| Primax Electronics                     | 13        | 0.21%   |
| Valve Software                         | 12        | 0.19%   |
| Lenovo                                 | 12        | 0.19%   |
| Jieli Technology                       | 12        | 0.19%   |
| Intel                                  | 11        | 0.18%   |
| Importek                               | 11        | 0.18%   |
| Creative Technology                    | 11        | 0.18%   |
| OmniVision Technologies                | 10        | 0.16%   |
| KYE Systems (Mouse Systems)            | 10        | 0.16%   |
| DigiTech                               | 10        | 0.16%   |
| AVerMedia Technologies                 | 10        | 0.16%   |
| Hewlett-Packard                        | 8         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 274       | 4.39%   |
| Chicony Integrated Camera                           | 252       | 4.04%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 191       | 3.06%   |
| Realtek Integrated_Webcam_HD                        | 175       | 2.81%   |
| IMC Networks Integrated Camera                      | 169       | 2.71%   |
| Chicony HD Webcam                                   | 147       | 2.36%   |
| Bison Integrated Camera                             | 112       | 1.8%    |
| Acer BisonCam,NB Pro                                | 108       | 1.73%   |
| Chicony USB2.0 Camera                               | 102       | 1.64%   |
| Apple Built-in iSight                               | 100       | 1.6%    |
| Syntek Integrated Camera                            | 96        | 1.54%   |
| Sunplus Integrated_Webcam_HD                        | 96        | 1.54%   |
| Logitech HD Pro Webcam C920                         | 85        | 1.36%   |
| Logitech Webcam C270                                | 75        | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE                           | 75        | 1.2%    |
| Apple FaceTime HD Camera                            | 70        | 1.12%   |
| Apple FaceTime HD Camera (Built-in)                 | 68        | 1.09%   |
| Bison HD Webcam                                     | 65        | 1.04%   |
| Quanta HD User Facing                               | 58        | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 57        | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)             | 47        | 0.75%   |
| Realtek USB camera                                  | 47        | 0.75%   |
| Lite-On Integrated Camera                           | 45        | 0.72%   |
| Chicony USB 2.0 Camera                              | 44        | 0.71%   |
| Chicony HP HD Camera                                | 43        | 0.69%   |
| Chicony HP Wide Vision HD Camera                    | 40        | 0.64%   |
| Microdia Webcam Vitade AF                           | 39        | 0.63%   |
| Chicony HD User Facing                              | 38        | 0.61%   |
| Microdia Integrated Webcam                          | 37        | 0.59%   |
| Chicony Integrated Camera (1280x720@30)             | 36        | 0.58%   |
| Quanta HD Webcam                                    | 35        | 0.56%   |
| Logitech C922 Pro Stream Webcam                     | 35        | 0.56%   |
| Bison SunplusIT Integrated Camera                   | 35        | 0.56%   |
| Chicony TOSHIBA Web Camera - HD                     | 34        | 0.55%   |
| Sunplus HD WebCam                                   | 33        | 0.53%   |
| Chicony USB2.0 HD UVC WebCam                        | 33        | 0.53%   |
| Quanta HP TrueVision HD Camera                      | 32        | 0.51%   |
| Microdia Laptop_Integrated_Webcam_HD                | 31        | 0.5%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 31        | 0.5%    |
| Realtek Integrated Webcam                           | 29        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 375       | 33.72%  |
| Validity Sensors                   | 313       | 28.15%  |
| Shenzhen Goodix Technology         | 209       | 18.79%  |
| Elan Microelectronics              | 65        | 5.85%   |
| Upek                               | 53        | 4.77%   |
| LighTuning Technology              | 43        | 3.87%   |
| AuthenTec                          | 30        | 2.7%    |
| STMicroelectronics                 | 7         | 0.63%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 0.45%   |
| Focal-systems.Corp                 | 5         | 0.45%   |
| HOLTEK                             | 3         | 0.27%   |
| Samsung Electronics                | 2         | 0.18%   |
| DigitalPersona                     | 2         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 92        | 8.27%   |
| Shenzhen Goodix  Fingerprint Device                                        | 85        | 7.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 74        | 6.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 67        | 6.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 60        | 5.4%    |
| Shenzhen Goodix FingerPrint                                                | 50        | 4.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 48        | 4.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 43        | 3.87%   |
| Elan ELAN:Fingerprint                                                      | 43        | 3.87%   |
| Synaptics  WBDI                                                            | 28        | 2.52%   |
| Synaptics TouchPad                                                         | 27        | 2.43%   |
| Validity Sensors Synaptics WBDI                                            | 26        | 2.34%   |
| Synaptics WBDI                                                             | 24        | 2.16%   |
| Synaptics WBDI Device                                                      | 23        | 2.07%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 1.98%   |
| Synaptics UWP WBDI                                                         | 22        | 1.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 21        | 1.89%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 1.89%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 1.89%   |
| Validity Sensors VFS491                                                    | 20        | 1.8%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 1.8%    |
| Elan ELAN:ARM-M4                                                           | 20        | 1.8%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 1.62%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 18        | 1.62%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 1.53%   |
| Unknown                                                                    | 17        | 1.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 1.35%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 1.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 1.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.08%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 1.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 9         | 0.81%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 0.81%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.72%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.63%   |
| AuthenTec AES2810                                                          | 7         | 0.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.63%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.54%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 181       | 46.65%  |
| Alcor Micro               | 107       | 27.58%  |
| Upek                      | 29        | 7.47%   |
| O2 Micro                  | 27        | 6.96%   |
| Lenovo                    | 20        | 5.15%   |
| SCM Microsystems          | 7         | 1.8%    |
| OmniKey                   | 5         | 1.29%   |
| Realtek Semiconductor     | 3         | 0.77%   |
| Gemalto (was Gemplus)     | 2         | 0.52%   |
| Aladdin Knowledge Systems | 2         | 0.52%   |
| Advanced Card Systems     | 2         | 0.52%   |
| Giesecke & Devrient       | 1         | 0.26%   |
| Clay Logic                | 1         | 0.26%   |
| Chicony Electronics       | 1         | 0.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 105       | 27.06%  |
| Broadcom BCM5880 Secure Applications Processor                               | 50        | 12.89%  |
| Broadcom 5880                                                                | 50        | 12.89%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 10.82%  |
| Broadcom 58200                                                               | 36        | 9.28%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 7.47%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 5.93%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.15%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.29%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.03%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.77%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.52%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.52%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.52%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.26%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.26%   |
| OmniKey CardMan 4321                                                         | 1         | 0.26%   |
| OmniKey CardMan 1021                                                         | 1         | 0.26%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.26%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.26%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.26%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.26%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.26%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.26%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7054      | 68.47%  |
| 1     | 2657      | 25.79%  |
| 2     | 505       | 4.9%    |
| 3     | 70        | 0.68%   |
| 4     | 12        | 0.12%   |
| 5     | 3         | 0.03%   |
| 7     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1089      | 28.58%  |
| Net/wireless             | 650       | 17.06%  |
| Graphics card            | 635       | 16.67%  |
| Multimedia controller    | 453       | 11.89%  |
| Chipcard                 | 374       | 9.82%   |
| Bluetooth                | 128       | 3.36%   |
| Camera                   | 84        | 2.2%    |
| Communication controller | 67        | 1.76%   |
| Unassigned class         | 64        | 1.68%   |
| Sound                    | 62        | 1.63%   |
| Net/ethernet             | 51        | 1.34%   |
| Storage                  | 43        | 1.13%   |
| Network                  | 26        | 0.68%   |
| Card reader              | 26        | 0.68%   |
| Storage/raid             | 18        | 0.47%   |
| Modem                    | 13        | 0.34%   |
| Storage/ide              | 11        | 0.29%   |
| Storage/nvme             | 6         | 0.16%   |
| Firewire controller      | 4         | 0.1%    |
| Flash memory             | 2         | 0.05%   |
| Dvb card                 | 2         | 0.05%   |
| Wireless                 | 1         | 0.03%   |
| Unclassified device      | 1         | 0.03%   |

