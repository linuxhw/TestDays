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

Total: 1759

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Acer          | Aspire X3400                | Desktop     | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [f9be94fa9b](https://linux-hardware.org/?probe=f9be94fa9b) | Mar 31, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [94beabac6e](https://linux-hardware.org/?probe=94beabac6e) | Mar 30, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [ea012026c5](https://linux-hardware.org/?probe=ea012026c5) | Mar 30, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [76ec39764b](https://linux-hardware.org/?probe=76ec39764b) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [eaaef17c19](https://linux-hardware.org/?probe=eaaef17c19) | Mar 25, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a68b0e55c](https://linux-hardware.org/?probe=0a68b0e55c) | Mar 24, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [b071309501](https://linux-hardware.org/?probe=b071309501) | Mar 23, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [eb934cc46a](https://linux-hardware.org/?probe=eb934cc46a) | Mar 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [6911af9ce1](https://linux-hardware.org/?probe=6911af9ce1) | Mar 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a52c137cf](https://linux-hardware.org/?probe=7a52c137cf) | Mar 18, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [f2fedaa3c3](https://linux-hardware.org/?probe=f2fedaa3c3) | Mar 18, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [56c1c58549](https://linux-hardware.org/?probe=56c1c58549) | Mar 15, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [ce34107bae](https://linux-hardware.org/?probe=ce34107bae) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [acef37559c](https://linux-hardware.org/?probe=acef37559c) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [884e853e6f](https://linux-hardware.org/?probe=884e853e6f) | Mar 14, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [14108beccf](https://linux-hardware.org/?probe=14108beccf) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [ee7f4f0b82](https://linux-hardware.org/?probe=ee7f4f0b82) | Mar 12, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d7fe091593](https://linux-hardware.org/?probe=d7fe091593) | Mar 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [0e4fb3e1fd](https://linux-hardware.org/?probe=0e4fb3e1fd) | Mar 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Dell          | Precision M6800             | Notebook    | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [3a9118e8bc](https://linux-hardware.org/?probe=3a9118e8bc) | Mar 07, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [5a711af850](https://linux-hardware.org/?probe=5a711af850) | Mar 07, 2022 |
| Lenovo        | ThinkPad T480 20L60033MX    | Notebook    | [fda7557aa0](https://linux-hardware.org/?probe=fda7557aa0) | Mar 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [54ae8c7668](https://linux-hardware.org/?probe=54ae8c7668) | Mar 01, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ad43671e4c](https://linux-hardware.org/?probe=ad43671e4c) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [9670ab829e](https://linux-hardware.org/?probe=9670ab829e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [d61754bba9](https://linux-hardware.org/?probe=d61754bba9) | Feb 26, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [290919912c](https://linux-hardware.org/?probe=290919912c) | Feb 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [c332efa9f8](https://linux-hardware.org/?probe=c332efa9f8) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [69896e5117](https://linux-hardware.org/?probe=69896e5117) | Feb 23, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [7bb148611f](https://linux-hardware.org/?probe=7bb148611f) | Feb 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| Lenovo        | ThinkPad T460s 20F9S1G20... | Notebook    | [6a6c0b0b39](https://linux-hardware.org/?probe=6a6c0b0b39) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| ASUSTek       | A4110                       | All in one  | [8fd1f10c40](https://linux-hardware.org/?probe=8fd1f10c40) | Feb 18, 2022 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [0337480978](https://linux-hardware.org/?probe=0337480978) | Feb 17, 2022 |
| ASUSTek       | A4110                       | All in one  | [ede6469471](https://linux-hardware.org/?probe=ede6469471) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| HP            | ProBook 4330s               | Notebook    | [3781146b1f](https://linux-hardware.org/?probe=3781146b1f) | Feb 14, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [a3709f6df1](https://linux-hardware.org/?probe=a3709f6df1) | Feb 12, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [2ad209abc4](https://linux-hardware.org/?probe=2ad209abc4) | Feb 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [68d863ab48](https://linux-hardware.org/?probe=68d863ab48) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | Notebook    | [ab580c3edd](https://linux-hardware.org/?probe=ab580c3edd) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | Notebook    | [c11f9d5c6d](https://linux-hardware.org/?probe=c11f9d5c6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0FJ0... | Notebook    | [6dc9215373](https://linux-hardware.org/?probe=6dc9215373) | Feb 07, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [ef92dfd4f1](https://linux-hardware.org/?probe=ef92dfd4f1) | Feb 03, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [9f7733e6ec](https://linux-hardware.org/?probe=9f7733e6ec) | Feb 03, 2022 |
| Dell          | Latitude E4200              | Notebook    | [35dbab3b2e](https://linux-hardware.org/?probe=35dbab3b2e) | Jan 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccd7847b28](https://linux-hardware.org/?probe=ccd7847b28) | Jan 30, 2022 |
| ASRock        | ION3D-HT                    | Desktop     | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| Unknown       | OnePlus 6                   | Soc         | [d9aedf2258](https://linux-hardware.org/?probe=d9aedf2258) | Jan 28, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [d6498c16bb](https://linux-hardware.org/?probe=d6498c16bb) | Jan 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8b6b3d70bf](https://linux-hardware.org/?probe=8b6b3d70bf) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | Notebook    | [698c80468a](https://linux-hardware.org/?probe=698c80468a) | Jan 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [29ce7637f6](https://linux-hardware.org/?probe=29ce7637f6) | Jan 23, 2022 |
| Intel         | NUC7i7DNB J83500-206        | Mini pc     | [65ae59d048](https://linux-hardware.org/?probe=65ae59d048) | Jan 23, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [cbf995ff80](https://linux-hardware.org/?probe=cbf995ff80) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [634d45ff9e](https://linux-hardware.org/?probe=634d45ff9e) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Dell          | Latitude 7280               | Notebook    | [6b9dcc88b7](https://linux-hardware.org/?probe=6b9dcc88b7) | Jan 21, 2022 |
| Dell          | Latitude 7280               | Notebook    | [beb9306791](https://linux-hardware.org/?probe=beb9306791) | Jan 21, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [e236263783](https://linux-hardware.org/?probe=e236263783) | Jan 19, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [c9587deb57](https://linux-hardware.org/?probe=c9587deb57) | Jan 19, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASRock        | Z87 Killer                  | Desktop     | [6931f1ca2f](https://linux-hardware.org/?probe=6931f1ca2f) | Jan 17, 2022 |
| MSI           | P67A-C45                    | Desktop     | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5a609ef492](https://linux-hardware.org/?probe=5a609ef492) | Jan 16, 2022 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7921e32637](https://linux-hardware.org/?probe=7921e32637) | Jan 14, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7b12fb3749](https://linux-hardware.org/?probe=7b12fb3749) | Jan 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [5cb4bc2ed8](https://linux-hardware.org/?probe=5cb4bc2ed8) | Jan 14, 2022 |
| Dell          | Precision 7560              | Notebook    | [a58a852902](https://linux-hardware.org/?probe=a58a852902) | Jan 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| Samsung       | 950QDB                      | Convertible | [d2f65665cd](https://linux-hardware.org/?probe=d2f65665cd) | Jan 12, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [831591fe79](https://linux-hardware.org/?probe=831591fe79) | Jan 11, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [a38abf3dd0](https://linux-hardware.org/?probe=a38abf3dd0) | Jan 10, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c572bd1eac](https://linux-hardware.org/?probe=c572bd1eac) | Jan 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [b5bd2eca7d](https://linux-hardware.org/?probe=b5bd2eca7d) | Jan 07, 2022 |
| HP            | Pavilion dv6000 (GH912EA... | Notebook    | [a41f8d2d74](https://linux-hardware.org/?probe=a41f8d2d74) | Jan 03, 2022 |
| Dell          | Latitude E7440              | Notebook    | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Acer          | Aspire X3400                | Desktop     | [6833137bc8](https://linux-hardware.org/?probe=6833137bc8) | Jan 02, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [de0e6691cd](https://linux-hardware.org/?probe=de0e6691cd) | Jan 02, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [a32495b8e4](https://linux-hardware.org/?probe=a32495b8e4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T410s 2924W79      | Notebook    | [43fe13f2a4](https://linux-hardware.org/?probe=43fe13f2a4) | Dec 30, 2021 |
| Dell          | Latitude 5480               | Notebook    | [e560c10eb8](https://linux-hardware.org/?probe=e560c10eb8) | Dec 29, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [ab9c63e097](https://linux-hardware.org/?probe=ab9c63e097) | Dec 28, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [04ebd359f1](https://linux-hardware.org/?probe=04ebd359f1) | Dec 28, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [63f4428f24](https://linux-hardware.org/?probe=63f4428f24) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [0f7bd5b933](https://linux-hardware.org/?probe=0f7bd5b933) | Dec 26, 2021 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [6246228e2d](https://linux-hardware.org/?probe=6246228e2d) | Dec 26, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| HP            | ZBook 15                    | Notebook    | [57cb28cc81](https://linux-hardware.org/?probe=57cb28cc81) | Dec 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [5c91ed91a8](https://linux-hardware.org/?probe=5c91ed91a8) | Dec 24, 2021 |
| Acer          | Aspire xxxx                 | Notebook    | [13b21c09d2](https://linux-hardware.org/?probe=13b21c09d2) | Dec 23, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [86789982ba](https://linux-hardware.org/?probe=86789982ba) | Dec 21, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [17fbd36a25](https://linux-hardware.org/?probe=17fbd36a25) | Dec 18, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | Notebook    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [3cd4b5c111](https://linux-hardware.org/?probe=3cd4b5c111) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [03115bdd2e](https://linux-hardware.org/?probe=03115bdd2e) | Dec 18, 2021 |
| Lenovo        | ThinkPad T410s 2924W79      | Notebook    | [f26b8b4f98](https://linux-hardware.org/?probe=f26b8b4f98) | Dec 17, 2021 |
| Acer          | Aspire xxxx                 | Notebook    | [dfa568d766](https://linux-hardware.org/?probe=dfa568d766) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [af2732b8a5](https://linux-hardware.org/?probe=af2732b8a5) | Dec 15, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [dd9fb384ea](https://linux-hardware.org/?probe=dd9fb384ea) | Dec 13, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [711aa97225](https://linux-hardware.org/?probe=711aa97225) | Dec 13, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| HP            | ZBook 15                    | Notebook    | [cb2487cb67](https://linux-hardware.org/?probe=cb2487cb67) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| HP            | ZBook 15                    | Notebook    | [c0d2e24505](https://linux-hardware.org/?probe=c0d2e24505) | Dec 10, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [696dd578ab](https://linux-hardware.org/?probe=696dd578ab) | Dec 08, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [b44117a400](https://linux-hardware.org/?probe=b44117a400) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | Notebook    | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [87b9d0f1e5](https://linux-hardware.org/?probe=87b9d0f1e5) | Dec 04, 2021 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [071e272398](https://linux-hardware.org/?probe=071e272398) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | Notebook    | [c579de06b5](https://linux-hardware.org/?probe=c579de06b5) | Dec 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | Notebook    | [e85a481d36](https://linux-hardware.org/?probe=e85a481d36) | Dec 02, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [4b1553b16a](https://linux-hardware.org/?probe=4b1553b16a) | Dec 01, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [64005f7018](https://linux-hardware.org/?probe=64005f7018) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [a380d2a0c8](https://linux-hardware.org/?probe=a380d2a0c8) | Nov 29, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c0f6b8395](https://linux-hardware.org/?probe=5c0f6b8395) | Nov 28, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [fb92bb54af](https://linux-hardware.org/?probe=fb92bb54af) | Nov 28, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [7c0e3a92a5](https://linux-hardware.org/?probe=7c0e3a92a5) | Nov 26, 2021 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [f3e1cfcdab](https://linux-hardware.org/?probe=f3e1cfcdab) | Nov 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [846877b55f](https://linux-hardware.org/?probe=846877b55f) | Nov 25, 2021 |
| MSI           | H170 GAMING M3              | Desktop     | [e9a754ed5c](https://linux-hardware.org/?probe=e9a754ed5c) | Nov 24, 2021 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [496b525711](https://linux-hardware.org/?probe=496b525711) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [969dde57b0](https://linux-hardware.org/?probe=969dde57b0) | Nov 22, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| ASUSTek       | ET2002G                     | All in one  | [a31ccc8a05](https://linux-hardware.org/?probe=a31ccc8a05) | Nov 21, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [756684e469](https://linux-hardware.org/?probe=756684e469) | Nov 20, 2021 |
| Acer          | EG43M                       | Desktop     | [03dc3c8d61](https://linux-hardware.org/?probe=03dc3c8d61) | Nov 20, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [1d12ea147a](https://linux-hardware.org/?probe=1d12ea147a) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [c6e0003dcb](https://linux-hardware.org/?probe=c6e0003dcb) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [6b485f4c9a](https://linux-hardware.org/?probe=6b485f4c9a) | Nov 20, 2021 |
| Acer          | Swift SF514-51              | Notebook    | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Lenovo        | ThinkPad T520 42433VG       | Notebook    | [529262c2e4](https://linux-hardware.org/?probe=529262c2e4) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [564ef15a99](https://linux-hardware.org/?probe=564ef15a99) | Nov 16, 2021 |
| HP            | 8056                        | Desktop     | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| HP            | ProBook 440 G4              | Notebook    | [f5d53e44ae](https://linux-hardware.org/?probe=f5d53e44ae) | Nov 15, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [b19a68b774](https://linux-hardware.org/?probe=b19a68b774) | Nov 13, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [4615791bf1](https://linux-hardware.org/?probe=4615791bf1) | Nov 04, 2021 |
| Lenovo        | ThinkPad W540 20BHS0NQ00    | Notebook    | [69f4b3d974](https://linux-hardware.org/?probe=69f4b3d974) | Nov 03, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [0b7ae3ebf5](https://linux-hardware.org/?probe=0b7ae3ebf5) | Nov 03, 2021 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [39c0680056](https://linux-hardware.org/?probe=39c0680056) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Acer          | Aspire 5739G                | Notebook    | [9366122bdb](https://linux-hardware.org/?probe=9366122bdb) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | Notebook    | [aaf8f33249](https://linux-hardware.org/?probe=aaf8f33249) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | Notebook    | [7979c29593](https://linux-hardware.org/?probe=7979c29593) | Oct 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [0cc8ca1a78](https://linux-hardware.org/?probe=0cc8ca1a78) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [688a36c9df](https://linux-hardware.org/?probe=688a36c9df) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ccce1ad4e4](https://linux-hardware.org/?probe=ccce1ad4e4) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [a96916c86f](https://linux-hardware.org/?probe=a96916c86f) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f4442e94e7](https://linux-hardware.org/?probe=f4442e94e7) | Oct 21, 2021 |
| HP            | 1998                        | Desktop     | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Pegatron      | 2AC3                        | Desktop     | [ae8b02d9cb](https://linux-hardware.org/?probe=ae8b02d9cb) | Oct 21, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | Notebook    | [df466b506d](https://linux-hardware.org/?probe=df466b506d) | Oct 20, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | Notebook    | [748d3e56a7](https://linux-hardware.org/?probe=748d3e56a7) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [26d1a4225d](https://linux-hardware.org/?probe=26d1a4225d) | Oct 17, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |

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
| Ubuntu 20.04                 | 127       | 12.15%  |
| Ubuntu 18.04                 | 61        | 5.84%   |
| Ubuntu 22.04                 | 44        | 4.21%   |
| Pop!_OS 22.04                | 41        | 3.92%   |
| Debian 11                    | 39        | 3.73%   |
| Zorin 16                     | 25        | 2.39%   |
| Arch Rolling                 | 25        | 2.39%   |
| Ubuntu 20.10                 | 20        | 1.91%   |
| OpenMandriva 4.2             | 20        | 1.91%   |
| Fedora 35                    | 20        | 1.91%   |
| OpenMandriva 4.3             | 18        | 1.72%   |
| Fedora 36                    | 17        | 1.63%   |
| ArcoLinux Rolling            | 17        | 1.63%   |
| Arch                         | 17        | 1.63%   |
| Pop!_OS 21.04                | 15        | 1.44%   |
| Pop!_OS 21.10                | 14        | 1.34%   |
| Manjaro                      | 14        | 1.34%   |
| KDE neon 20.04               | 14        | 1.34%   |
| Fedora 34                    | 14        | 1.34%   |
| Fedora 31                    | 14        | 1.34%   |
| Ubuntu 19.10                 | 13        | 1.24%   |
| Ubuntu 19.04                 | 13        | 1.24%   |
| Fedora 37                    | 13        | 1.24%   |
| Ubuntu 22.10                 | 12        | 1.15%   |
| Ubuntu 18.10                 | 12        | 1.15%   |
| Pop!_OS 20.10                | 12        | 1.15%   |
| Pop!_OS 20.04                | 12        | 1.15%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 1.15%   |
| Linux Mint 20.2              | 12        | 1.15%   |
| Linux Mint 20.3              | 10        | 0.96%   |
| Ubuntu 21.10                 | 9         | 0.86%   |
| Linux Mint 20.1              | 9         | 0.86%   |
| Linux Mint 19.3              | 9         | 0.86%   |
| Fedora 32                    | 9         | 0.86%   |
| Debian 10                    | 9         | 0.86%   |
| Zorin 15                     | 8         | 0.77%   |
| Xubuntu 20.04                | 8         | 0.77%   |
| Ubuntu 21.04                 | 8         | 0.77%   |
| OpenMandriva 23.01           | 8         | 0.77%   |
| Fedora 33                    | 8         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 314       | 31.65%  |
| Fedora        | 92        | 9.27%   |
| Pop!_OS       | 86        | 8.67%   |
| Linux Mint    | 60        | 6.05%   |
| Debian        | 59        | 5.95%   |
| OpenMandriva  | 55        | 5.54%   |
| Manjaro       | 45        | 4.54%   |
| Arch          | 42        | 4.23%   |
| Zorin         | 34        | 3.43%   |
| KDE neon      | 24        | 2.42%   |
| openSUSE      | 18        | 1.81%   |
| ArcoLinux     | 18        | 1.81%   |
| Xubuntu       | 16        | 1.61%   |
| Kubuntu       | 13        | 1.31%   |
| Gentoo        | 11        | 1.11%   |
| Elementary    | 11        | 1.11%   |
| Kali          | 10        | 1.01%   |
| Ubuntu MATE   | 9         | 0.91%   |
| Clear Linux   | 8         | 0.81%   |
| ROSA          | 7         | 0.71%   |
| RHEL          | 7         | 0.71%   |
| CentOS        | 7         | 0.71%   |
| Ubuntu Budgie | 6         | 0.6%    |
| EndeavourOS   | 5         | 0.5%    |
| Solus         | 4         | 0.4%    |
| Lubuntu       | 4         | 0.4%    |
| Ubuntu Unity  | 3         | 0.3%    |
| Nobara        | 3         | 0.3%    |
| Xero          | 2         | 0.2%    |
| Ubuntu Studio | 2         | 0.2%    |
| MX            | 2         | 0.2%    |
| LMDE          | 2         | 0.2%    |
| Garuda Linux  | 2         | 0.2%    |
| Alpine        | 2         | 0.2%    |
| Void Linux    | 1         | 0.1%    |
| Rocky Linux   | 1         | 0.1%    |
| PostmarketOS  | 1         | 0.1%    |
| Peppermint    | 1         | 0.1%    |
| Feren OS      | 1         | 0.1%    |
| Devuan        | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 19        | 1.63%   |
| 5.16.7-desktop-1omv4003     | 17        | 1.46%   |
| 5.4.0-42-generic            | 14        | 1.2%    |
| 5.19.0-76051900-generic     | 10        | 0.86%   |
| 5.15.0-46-generic           | 10        | 0.86%   |
| 5.4.0-58-generic            | 9         | 0.77%   |
| 5.3.0-46-generic            | 9         | 0.77%   |
| 4.18.0-16-generic           | 9         | 0.77%   |
| 3.10.0-1062.12.1.el7.x86_64 | 9         | 0.77%   |
| 6.1.1-desktop-1omv2290      | 8         | 0.69%   |
| 5.4.0-74-generic            | 8         | 0.69%   |
| 5.4.0-48-generic            | 8         | 0.69%   |
| 5.11.0-40-generic           | 8         | 0.69%   |
| 5.11.0-38-generic           | 8         | 0.69%   |
| 6.0.12-76060006-generic     | 7         | 0.6%    |
| 5.8.0-7630-generic          | 7         | 0.6%    |
| 5.8.0-44-generic            | 7         | 0.6%    |
| 5.8.0-43-generic            | 7         | 0.6%    |
| 5.4.0-91-generic            | 7         | 0.6%    |
| 5.4.0-26-generic            | 7         | 0.6%    |
| 5.3.0-40-generic            | 7         | 0.6%    |
| 5.15.0-58-generic           | 7         | 0.6%    |
| 5.15.0-56-generic           | 7         | 0.6%    |
| 5.15.0-48-generic           | 7         | 0.6%    |
| 5.11.0-7620-generic         | 7         | 0.6%    |
| 6.2.6-desktop-1omv2390      | 6         | 0.52%   |
| 6.2.6-76060206-generic      | 6         | 0.52%   |
| 5.4.0-47-generic            | 6         | 0.52%   |
| 5.4.0-45-generic            | 6         | 0.52%   |
| 5.4.0-29-generic            | 6         | 0.52%   |
| 5.3.0-28-generic            | 6         | 0.52%   |
| 5.15.0-60-generic           | 6         | 0.52%   |
| 5.15.0-41-generic           | 6         | 0.52%   |
| 5.11.0-27-generic           | 6         | 0.52%   |
| 5.10.0-8-amd64              | 6         | 0.52%   |
| 5.0.0-20-generic            | 6         | 0.52%   |
| 6.2.0-20-generic            | 5         | 0.43%   |
| 5.8.0-48-generic            | 5         | 0.43%   |
| 5.4.0-72-generic            | 5         | 0.43%   |
| 5.4.0-33-generic            | 5         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 164       | 14.92%  |
| 5.15.0  | 69        | 6.28%   |
| 5.11.0  | 55        | 5%      |
| 5.8.0   | 54        | 4.91%   |
| 5.3.0   | 42        | 3.82%   |
| 5.19.0  | 41        | 3.73%   |
| 5.13.0  | 39        | 3.55%   |
| 4.15.0  | 38        | 3.46%   |
| 5.10.0  | 37        | 3.37%   |
| 4.18.0  | 30        | 2.73%   |
| 5.0.0   | 25        | 2.27%   |
| 5.10.14 | 19        | 1.73%   |
| 5.16.7  | 17        | 1.55%   |
| 6.2.6   | 14        | 1.27%   |
| 3.10.0  | 10        | 0.91%   |
| 4.19.0  | 9         | 0.82%   |
| 6.2.0   | 8         | 0.73%   |
| 6.1.1   | 8         | 0.73%   |
| 5.17.5  | 8         | 0.73%   |
| 6.0.12  | 7         | 0.64%   |
| 5.16.0  | 7         | 0.64%   |
| 5.17.0  | 6         | 0.55%   |
| 5.16.11 | 6         | 0.55%   |
| 6.1.0   | 5         | 0.45%   |
| 5.9.16  | 5         | 0.45%   |
| 5.5.5   | 5         | 0.45%   |
| 5.18.10 | 5         | 0.45%   |
| 5.18.0  | 5         | 0.45%   |
| 5.12.4  | 5         | 0.45%   |
| 6.2.8   | 4         | 0.36%   |
| 6.1.11  | 4         | 0.36%   |
| 6.0.6   | 4         | 0.36%   |
| 6.0.2   | 4         | 0.36%   |
| 6.0.0   | 4         | 0.36%   |
| 5.17.15 | 4         | 0.36%   |
| 5.16.15 | 4         | 0.36%   |
| 5.15.8  | 4         | 0.36%   |
| 5.15.5  | 4         | 0.36%   |
| 5.15.4  | 4         | 0.36%   |
| 5.12.9  | 4         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 181       | 16.74%  |
| 5.15    | 109       | 10.08%  |
| 5.8     | 70        | 6.48%   |
| 5.10    | 69        | 6.38%   |
| 5.11    | 64        | 5.92%   |
| 5.13    | 61        | 5.64%   |
| 5.19    | 59        | 5.46%   |
| 5.3     | 51        | 4.72%   |
| 5.16    | 49        | 4.53%   |
| 4.15    | 38        | 3.52%   |
| 6.2     | 37        | 3.42%   |
| 4.18    | 33        | 3.05%   |
| 5.17    | 31        | 2.87%   |
| 6.1     | 27        | 2.5%    |
| 6.0     | 27        | 2.5%    |
| 5.0     | 27        | 2.5%    |
| 5.9     | 21        | 1.94%   |
| 5.14    | 21        | 1.94%   |
| 5.18    | 18        | 1.67%   |
| 5.12    | 15        | 1.39%   |
| 5.5     | 12        | 1.11%   |
| 5.7     | 11        | 1.02%   |
| 4.19    | 11        | 1.02%   |
| 3.10    | 10        | 0.93%   |
| 5.6     | 8         | 0.74%   |
| 6.3     | 6         | 0.56%   |
| 4.9     | 4         | 0.37%   |
| 5.1     | 3         | 0.28%   |
| 5.2     | 2         | 0.19%   |
| 4.4     | 2         | 0.19%   |
| 4.20    | 1         | 0.09%   |
| 4.12    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |
| 4.1     | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 938       | 97.51%  |
| i686    | 14        | 1.46%   |
| aarch64 | 8         | 0.83%   |
| armv7l  | 2         | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 466       | 46.74%  |
| KDE5              | 158       | 15.85%  |
| Unknown           | 142       | 14.24%  |
| XFCE              | 73        | 7.32%   |
| X-Cinnamon        | 40        | 4.01%   |
| KDE               | 24        | 2.41%   |
| MATE              | 19        | 1.91%   |
| i3                | 14        | 1.4%    |
| Cinnamon          | 11        | 1.1%    |
| Pantheon          | 9         | 0.9%    |
| Budgie            | 9         | 0.9%    |
| GNOME Flashback   | 6         | 0.6%    |
| LXDE              | 5         | 0.5%    |
| LXQt              | 4         | 0.4%    |
| Unity             | 3         | 0.3%    |
| KDE4              | 3         | 0.3%    |
| i3-with-shmlog    | 2         | 0.2%    |
| dwm               | 2         | 0.2%    |
| Yaru:ubuntu:GNOME | 1         | 0.1%    |
| xinit-compat      | 1         | 0.1%    |
| qtile             | 1         | 0.1%    |
| LeftWM            | 1         | 0.1%    |
| GNOME:Phosh       | 1         | 0.1%    |
| Deepin            | 1         | 0.1%    |
| bspwm             | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 731       | 73.62%  |
| Wayland | 159       | 16.01%  |
| Unknown | 71        | 7.15%   |
| Tty     | 32        | 3.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 510       | 50.75%  |
| GDM     | 135       | 13.43%  |
| SDDM    | 134       | 13.33%  |
| GDM3    | 105       | 10.45%  |
| LightDM | 86        | 8.56%   |
| TDM     | 28        | 2.79%   |
| KDM     | 4         | 0.4%    |
| XDM     | 2         | 0.2%    |
| Ly      | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 512       | 51.93%  |
| nb_NO       | 223       | 22.62%  |
| Unknown     | 108       | 10.95%  |
| en_GB       | 59        | 5.98%   |
| C           | 20        | 2.03%   |
| nn_NO       | 16        | 1.62%   |
| pl_PL       | 9         | 0.91%   |
| en_DK       | 9         | 0.91%   |
| de_DE       | 9         | 0.91%   |
| fr_FR       | 3         | 0.3%    |
| en_IE       | 3         | 0.3%    |
| ru_RU       | 2         | 0.2%    |
| pt_PT       | 2         | 0.2%    |
| POSIX       | 1         | 0.1%    |
| fi_FI       | 1         | 0.1%    |
| es_ES       | 1         | 0.1%    |
| en_US.utf-8 | 1         | 0.1%    |
| en_NZ       | 1         | 0.1%    |
| en_CA       | 1         | 0.1%    |
| en_AG       | 1         | 0.1%    |
| en_150      | 1         | 0.1%    |
| en_001      | 1         | 0.1%    |
| el_GR       | 1         | 0.1%    |
| da_DK       | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 526       | 53.73%  |
| BIOS | 453       | 46.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 745       | 76.33%  |
| Btrfs   | 104       | 10.66%  |
| Overlay | 60        | 6.15%   |
| Xfs     | 29        | 2.97%   |
| Unknown | 24        | 2.46%   |
| Zfs     | 7         | 0.72%   |
| Ext2    | 4         | 0.41%   |
| Tmpfs   | 2         | 0.2%    |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 508       | 51.68%  |
| GPT     | 395       | 40.18%  |
| MBR     | 80        | 8.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 840       | 85.71%  |
| Yes       | 140       | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 726       | 74.08%  |
| Yes       | 254       | 25.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 205       | 21.31%  |
| Lenovo                  | 191       | 19.85%  |
| Hewlett-Packard         | 143       | 14.86%  |
| Dell                    | 117       | 12.16%  |
| MSI                     | 57        | 5.93%   |
| Gigabyte Technology     | 47        | 4.89%   |
| Acer                    | 45        | 4.68%   |
| Apple                   | 31        | 3.22%   |
| ASRock                  | 24        | 2.49%   |
| HUAWEI                  | 13        | 1.35%   |
| Samsung Electronics     | 11        | 1.14%   |
| Intel                   | 9         | 0.94%   |
| Toshiba                 | 8         | 0.83%   |
| Raspberry Pi Foundation | 7         | 0.73%   |
| Packard Bell            | 7         | 0.73%   |
| Unknown                 | 7         | 0.73%   |
| Notebook                | 5         | 0.52%   |
| Clevo                   | 4         | 0.42%   |
| Pegatron                | 3         | 0.31%   |
| Microsoft               | 3         | 0.31%   |
| Google                  | 2         | 0.21%   |
| ZOTAC                   | 1         | 0.1%    |
| Xunlong                 | 1         | 0.1%    |
| Wibtek                  | 1         | 0.1%    |
| TYAN Computer           | 1         | 0.1%    |
| Teclast                 | 1         | 0.1%    |
| Supermicro              | 1         | 0.1%    |
| Sony                    | 1         | 0.1%    |
| Shuttle                 | 1         | 0.1%    |
| Razer                   | 1         | 0.1%    |
| Nokia                   | 1         | 0.1%    |
| Lenovo Product          | 1         | 0.1%    |
| LAMINA                  | 1         | 0.1%    |
| Intel Client Systems    | 1         | 0.1%    |
| GMKtec                  | 1         | 0.1%    |
| Getac                   | 1         | 0.1%    |
| Fujitsu Siemens         | 1         | 0.1%    |
| Fujitsu                 | 1         | 0.1%    |
| Cisco Systems           | 1         | 0.1%    |
| Cepter                  | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 14        | 1.46%   |
| Unknown                            | 8         | 0.83%   |
| Apple MacBookPro12,1               | 7         | 0.73%   |
| HUAWEI MACH-WX9                    | 6         | 0.62%   |
| Dell Precision 5530                | 6         | 0.62%   |
| ASUS KomplettPC                    | 6         | 0.62%   |
| Dell PowerEdge R230                | 5         | 0.52%   |
| ASUS ROG STRIX B360-F GAMING       | 5         | 0.52%   |
| HP ProBook 430 G2                  | 4         | 0.42%   |
| HP EliteBook 840 G6                | 4         | 0.42%   |
| Gigabyte GA-970A-UD3               | 4         | 0.42%   |
| Dell XPS 15 9570                   | 4         | 0.42%   |
| Dell Latitude E7240                | 4         | 0.42%   |
| ASUS ROG STRIX X570-F GAMING       | 4         | 0.42%   |
| ASUS M2R-FVM                       | 4         | 0.42%   |
| Samsung 950XCJ/951XCJ/950XCR       | 3         | 0.31%   |
| MSI MS-7885                        | 3         | 0.31%   |
| HUAWEI WRT-WX9                     | 3         | 0.31%   |
| HP OMEN by Laptop                  | 3         | 0.31%   |
| HP EliteBook 8470p                 | 3         | 0.31%   |
| HP EliteBook 840 G5                | 3         | 0.31%   |
| HP Compaq Elite 8300 SFF           | 3         | 0.31%   |
| Dell XPS 15 9500                   | 3         | 0.31%   |
| Dell XPS 13 9380                   | 3         | 0.31%   |
| Dell OptiPlex 9020                 | 3         | 0.31%   |
| Dell OptiPlex 7010                 | 3         | 0.31%   |
| Dell Latitude E5470                | 3         | 0.31%   |
| Dell Latitude 5480                 | 3         | 0.31%   |
| ASUS Z170 PRO GAMING               | 3         | 0.31%   |
| ASUS SABERTOOTH P67                | 3         | 0.31%   |
| ASUS ROG STRIX X470-F GAMING       | 3         | 0.31%   |
| ASUS ROG STRIX B550-I GAMING       | 3         | 0.31%   |
| ASUS ROG STRIX B450-F GAMING       | 3         | 0.31%   |
| ASUS ROG CROSSHAIR VIII HERO       | 3         | 0.31%   |
| ASUS PRIME X570-P                  | 3         | 0.31%   |
| ASUS P9X79 LE                      | 3         | 0.31%   |
| Acer Aspire V3-571G                | 3         | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 2         | 0.21%   |
| RPi Raspberry Pi                   | 2         | 0.21%   |
| MSI MS-7B86                        | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 123       | 12.79%  |
| HP EliteBook          | 42        | 4.37%   |
| ASUS ROG              | 42        | 4.37%   |
| Dell Latitude         | 39        | 4.05%   |
| Acer Aspire           | 30        | 3.12%   |
| HP ProBook            | 22        | 2.29%   |
| Dell XPS              | 21        | 2.18%   |
| Dell Precision        | 21        | 2.18%   |
| ASUS PRIME            | 21        | 2.18%   |
| Lenovo Yoga           | 17        | 1.77%   |
| Dell OptiPlex         | 16        | 1.66%   |
| ASUS All              | 14        | 1.46%   |
| HP Pavilion           | 13        | 1.35%   |
| Dell PowerEdge        | 12        | 1.25%   |
| Lenovo ThinkCentre    | 11        | 1.14%   |
| Lenovo IdeaPad        | 11        | 1.14%   |
| ASUS TUF              | 11        | 1.14%   |
| HP ZBook              | 10        | 1.04%   |
| ASUS VivoBook         | 10        | 1.04%   |
| HP EliteDesk          | 8         | 0.83%   |
| Unknown               | 8         | 0.83%   |
| RPi Raspberry         | 7         | 0.73%   |
| Apple MacBookPro12    | 7         | 0.73%   |
| Toshiba Satellite     | 6         | 0.62%   |
| HUAWEI MACH-WX9       | 6         | 0.62%   |
| HP Compaq             | 6         | 0.62%   |
| Gigabyte X570         | 6         | 0.62%   |
| Dell Inspiron         | 6         | 0.62%   |
| ASUS SABERTOOTH       | 6         | 0.62%   |
| ASUS KomplettPC       | 6         | 0.62%   |
| Packard Bell EasyNote | 5         | 0.52%   |
| Lenovo Legion         | 5         | 0.52%   |
| HP Spectre            | 5         | 0.52%   |
| HP OMEN               | 5         | 0.52%   |
| HP ENVY               | 5         | 0.52%   |
| Gigabyte B550         | 5         | 0.52%   |
| Gigabyte B450         | 5         | 0.52%   |
| Acer Swift            | 5         | 0.52%   |
| HP Laptop             | 4         | 0.42%   |
| Gigabyte GA-970A-UD3  | 4         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 110       | 11.43%  |
| 2019    | 106       | 11.02%  |
| 2020    | 94        | 9.77%   |
| 2015    | 77        | 8%      |
| 2012    | 75        | 7.8%    |
| 2017    | 74        | 7.69%   |
| 2016    | 63        | 6.55%   |
| 2013    | 60        | 6.24%   |
| 2011    | 58        | 6.03%   |
| 2014    | 56        | 5.82%   |
| 2021    | 53        | 5.51%   |
| 2010    | 38        | 3.95%   |
| 2022    | 27        | 2.81%   |
| 2009    | 25        | 2.6%    |
| 2008    | 12        | 1.25%   |
| 2007    | 12        | 1.25%   |
| Unknown | 8         | 0.83%   |
| 2006    | 7         | 0.73%   |
| 2005    | 4         | 0.42%   |
| 2023    | 2         | 0.21%   |
| 2001    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 532       | 55.3%   |
| Desktop        | 342       | 35.55%  |
| Convertible    | 29        | 3.01%   |
| Mini pc        | 16        | 1.66%   |
| Server         | 15        | 1.56%   |
| All in one     | 12        | 1.25%   |
| System on chip | 9         | 0.94%   |
| Tablet         | 7         | 0.73%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 874       | 90.38%  |
| Enabled  | 93        | 9.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 959       | 99.69%  |
| Yes  | 3         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 247       | 25.33%  |
| 4.01-8.0        | 219       | 22.46%  |
| 32.01-64.0      | 161       | 16.51%  |
| 8.01-16.0       | 147       | 15.08%  |
| 3.01-4.0        | 115       | 11.79%  |
| 64.01-256.0     | 41        | 4.21%   |
| 1.01-2.0        | 17        | 1.74%   |
| 24.01-32.0      | 15        | 1.54%   |
| 2.01-3.0        | 4         | 0.41%   |
| More than 256.0 | 3         | 0.31%   |
| 0.51-1.0        | 3         | 0.31%   |
| 0.01-0.5        | 3         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 298       | 27.54%  |
| 2.01-3.0    | 247       | 22.83%  |
| 4.01-8.0    | 219       | 20.24%  |
| 3.01-4.0    | 175       | 16.17%  |
| 8.01-16.0   | 62        | 5.73%   |
| 0.51-1.0    | 48        | 4.44%   |
| 0.01-0.5    | 13        | 1.2%    |
| 16.01-24.0  | 11        | 1.02%   |
| 32.01-64.0  | 4         | 0.37%   |
| 24.01-32.0  | 4         | 0.37%   |
| 64.01-256.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 596       | 60.32%  |
| 2      | 195       | 19.74%  |
| 3      | 81        | 8.2%    |
| 4      | 47        | 4.76%   |
| 5      | 22        | 2.23%   |
| 6      | 18        | 1.82%   |
| 0      | 13        | 1.32%   |
| 7      | 6         | 0.61%   |
| 8      | 4         | 0.4%    |
| 11     | 3         | 0.3%    |
| 9      | 3         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 703       | 72.55%  |
| Yes       | 266       | 27.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 822       | 85.27%  |
| No        | 142       | 14.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 759       | 78.57%  |
| No        | 207       | 21.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 629       | 64.45%  |
| No        | 347       | 35.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Norway  | 962       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Oslo                 | 280       | 27.24%  |
| Trondheim            | 69        | 6.71%   |
| Bergen               | 42        | 4.09%   |
| Kristiansand         | 30        | 2.92%   |
| Stavanger            | 27        | 2.63%   |
| Sandefjord           | 15        | 1.46%   |
| Tromsø              | 14        | 1.36%   |
| Skien                | 14        | 1.36%   |
| Ålesund             | 14        | 1.36%   |
| Drammen              | 12        | 1.17%   |
| Kongsberg            | 11        | 1.07%   |
| Asker                | 11        | 1.07%   |
| Fornebu              | 10        | 0.97%   |
| Røyken Municipality | 9         | 0.88%   |
| Nesttun              | 8         | 0.78%   |
| Sandnes              | 7         | 0.68%   |
| Lillehammer          | 7         | 0.68%   |
| Honefoss             | 7         | 0.68%   |
| Fredrikstad          | 7         | 0.68%   |
| Bodø                | 7         | 0.68%   |
| Arendal              | 7         | 0.68%   |
| Sarpsborg            | 6         | 0.58%   |
| Harstad              | 6         | 0.58%   |
| Fetsund              | 6         | 0.58%   |
| Voll                 | 5         | 0.49%   |
| Tønsberg            | 5         | 0.49%   |
| Notodden             | 5         | 0.49%   |
| Moss                 | 5         | 0.49%   |
| Mjondalen            | 5         | 0.49%   |
| Melhus               | 5         | 0.49%   |
| Haugesund            | 5         | 0.49%   |
| Hamar                | 5         | 0.49%   |
| Drobak               | 5         | 0.49%   |
| Bo                   | 5         | 0.49%   |
| Vennesla             | 4         | 0.39%   |
| Stjordal             | 4         | 0.39%   |
| Narvik               | 4         | 0.39%   |
| Mo i Rana            | 4         | 0.39%   |
| Kristiansund         | 4         | 0.39%   |
| Heimdal              | 4         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 345       | 533    | 24.26%  |
| Seagate                     | 179       | 332    | 12.59%  |
| WDC                         | 152       | 317    | 10.69%  |
| Kingston                    | 97        | 138    | 6.82%   |
| Toshiba                     | 85        | 104    | 5.98%   |
| SanDisk                     | 68        | 94     | 4.78%   |
| Intel                       | 55        | 73     | 3.87%   |
| Crucial                     | 50        | 80     | 3.52%   |
| SK hynix                    | 48        | 55     | 3.38%   |
| Unknown                     | 42        | 55     | 2.95%   |
| Hitachi                     | 38        | 53     | 2.67%   |
| Micron Technology           | 32        | 44     | 2.25%   |
| HGST                        | 30        | 38     | 2.11%   |
| Corsair                     | 24        | 36     | 1.69%   |
| Apple                       | 22        | 25     | 1.55%   |
| Phison                      | 18        | 23     | 1.27%   |
| OCZ                         | 15        | 18     | 1.05%   |
| LITEON                      | 15        | 19     | 1.05%   |
| PNY                         | 14        | 22     | 0.98%   |
| LITEONIT                    | 9         | 13     | 0.63%   |
| A-DATA Technology           | 9         | 12     | 0.63%   |
| KIOXIA                      | 8         | 16     | 0.56%   |
| Phison Electronics          | 5         | 11     | 0.35%   |
| Lenovo                      | 5         | 5      | 0.35%   |
| Intenso                     | 5         | 8      | 0.35%   |
| Kingston Technology Company | 4         | 5      | 0.28%   |
| Fujitsu                     | 4         | 4      | 0.28%   |
| China                       | 4         | 4      | 0.28%   |
| Unknown                     | 3         | 4      | 0.21%   |
| XPG                         | 2         | 2      | 0.14%   |
| Transcend                   | 2         | 2      | 0.14%   |
| Silicon Motion              | 2         | 3      | 0.14%   |
| Lexar                       | 2         | 2      | 0.14%   |
| JMicron Technology          | 2         | 1      | 0.14%   |
| GOODRAM                     | 2         | 2      | 0.14%   |
| ASMT                        | 2         | 3      | 0.14%   |
| Ugreen                      | 1         | 1      | 0.07%   |
| Teclast                     | 1         | 1      | 0.07%   |
| Team                        | 1         | 1      | 0.07%   |
| StoreJet                    | 1         | 1      | 0.07%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 256GB                        | 22        | 1.35%   |
| Samsung SSD 850 EVO 250GB                           | 18        | 1.11%   |
| Kingston SV300S37A120G 120GB SSD                    | 15        | 0.92%   |
| Samsung SSD 860 EVO 1TB                             | 14        | 0.86%   |
| Samsung SSD 850 EVO 500GB                           | 13        | 0.8%    |
| Samsung SSD 840 EVO 250GB                           | 13        | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 12        | 0.74%   |
| Samsung NVMe SSD Drive 500GB                        | 11        | 0.68%   |
| Samsung SSD 860 EVO 500GB                           | 10        | 0.61%   |
| Toshiba NVMe SSD Drive 256GB                        | 9         | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB                      | 9         | 0.55%   |
| Seagate Expansion 1TB                               | 9         | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB                        | 9         | 0.55%   |
| Samsung NVMe SSD Drive 512GB                        | 9         | 0.55%   |
| Samsung NVMe SSD Drive 1TB                          | 9         | 0.55%   |
| PNY ELITE PSSD 480GB                                | 9         | 0.55%   |
| HGST HTS721010A9E630 1TB                            | 9         | 0.55%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 8         | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 8         | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                      | 7         | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                      | 7         | 0.43%   |
| Samsung SSD 860 EVO 250GB                           | 7         | 0.43%   |
| Samsung SSD 840 EVO 120GB                           | 7         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 7         | 0.43%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD                | 7         | 0.43%   |
| Kingston SV300S37A240G 240GB SSD                    | 7         | 0.43%   |
| Kingston NVMe SSD Drive 1TB                         | 7         | 0.43%   |
| Apple SSD SM0128G 121GB                             | 7         | 0.43%   |
| Seagate ST1000DM010-2EP102 1TB                      | 6         | 0.37%   |
| Unknown MMC Card  64GB                              | 5         | 0.31%   |
| Unknown MMC Card  16GB                              | 5         | 0.31%   |
| Toshiba NVMe SSD Drive 512GB                        | 5         | 0.31%   |
| Toshiba MG04ACA100NY 1TB                            | 5         | 0.31%   |
| Seagate ST8000VN004-2M2101 8TB                      | 5         | 0.31%   |
| Seagate ST500DM002-1BD142 500GB                     | 5         | 0.31%   |
| Seagate ST4000VN008-2DR166 4TB                      | 5         | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5         | 0.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.31%   |
| Seagate Backup+ Hub BK 6TB                          | 5         | 0.31%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 5         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 174       | 325    | 39.82%  |
| WDC                 | 109       | 243    | 24.94%  |
| Toshiba             | 41        | 52     | 9.38%   |
| Hitachi             | 38        | 53     | 8.7%    |
| HGST                | 30        | 38     | 6.86%   |
| Samsung Electronics | 26        | 42     | 5.95%   |
| Apple               | 5         | 5      | 1.14%   |
| Fujitsu             | 4         | 4      | 0.92%   |
| Unknown             | 3         | 3      | 0.69%   |
| Intenso             | 3         | 6      | 0.69%   |
| LaCie               | 1         | 1      | 0.23%   |
| IET                 | 1         | 2      | 0.23%   |
| ASMT                | 1         | 2      | 0.23%   |
| Unknown             | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 190       | 266    | 35.19%  |
| Kingston            | 69        | 90     | 12.78%  |
| Crucial             | 44        | 74     | 8.15%   |
| SanDisk             | 35        | 45     | 6.48%   |
| Intel               | 33        | 47     | 6.11%   |
| WDC                 | 21        | 41     | 3.89%   |
| OCZ                 | 15        | 18     | 2.78%   |
| Micron Technology   | 15        | 21     | 2.78%   |
| Apple               | 15        | 18     | 2.78%   |
| PNY                 | 14        | 22     | 2.59%   |
| Corsair             | 14        | 18     | 2.59%   |
| SK hynix            | 13        | 14     | 2.41%   |
| LITEON              | 12        | 16     | 2.22%   |
| Toshiba             | 11        | 13     | 2.04%   |
| LITEONIT            | 9         | 13     | 1.67%   |
| A-DATA Technology   | 7         | 10     | 1.3%    |
| China               | 4         | 4      | 0.74%   |
| Transcend           | 2         | 2      | 0.37%   |
| Goodram             | 2         | 2      | 0.37%   |
| Teclast             | 1         | 1      | 0.19%   |
| Team                | 1         | 1      | 0.19%   |
| SPCC                | 1         | 1      | 0.19%   |
| Seagate             | 1         | 1      | 0.19%   |
| SandForce           | 1         | 2      | 0.19%   |
| Radeon              | 1         | 1      | 0.19%   |
| Phison              | 1         | 1      | 0.19%   |
| Patriot             | 1         | 1      | 0.19%   |
| LDLC                | 1         | 1      | 0.19%   |
| KingSpec            | 1         | 2      | 0.19%   |
| KingFast            | 1         | 1      | 0.19%   |
| Intenso             | 1         | 1      | 0.19%   |
| BIWIN               | 1         | 1      | 0.19%   |
| ASMT                | 1         | 1      | 0.19%   |
| Unknown             | 1         | 2      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 462       | 752    | 36.21%  |
| NVMe    | 395       | 582    | 30.96%  |
| HDD     | 363       | 777    | 28.45%  |
| MMC     | 40        | 53     | 3.13%   |
| Unknown | 16        | 18     | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 647       | 1440   | 56.36%  |
| NVMe | 395       | 582    | 34.41%  |
| SAS  | 66        | 107    | 5.75%   |
| MMC  | 40        | 53     | 3.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 517       | 836    | 57.25%  |
| 0.51-1.0   | 220       | 331    | 24.36%  |
| 1.01-2.0   | 61        | 108    | 6.76%   |
| 3.01-4.0   | 39        | 71     | 4.32%   |
| 4.01-10.0  | 33        | 99     | 3.65%   |
| 2.01-3.0   | 32        | 83     | 3.54%   |
| 10.01-20.0 | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 303       | 29.74%  |
| 251-500        | 217       | 21.3%   |
| 501-1000       | 136       | 13.35%  |
| 1001-2000      | 87        | 8.54%   |
| More than 3000 | 84        | 8.24%   |
| 1-20           | 70        | 6.87%   |
| 51-100         | 36        | 3.53%   |
| 2001-3000      | 34        | 3.34%   |
| Unknown        | 28        | 2.75%   |
| 21-50          | 24        | 2.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 383       | 35.9%   |
| 21-50          | 144       | 13.5%   |
| 101-250        | 141       | 13.21%  |
| 51-100         | 124       | 11.62%  |
| 251-500        | 87        | 8.15%   |
| 501-1000       | 62        | 5.81%   |
| 1001-2000      | 47        | 4.4%    |
| More than 3000 | 37        | 3.47%   |
| Unknown        | 28        | 2.62%   |
| 2001-3000      | 13        | 1.22%   |
| 0              | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-22JC3T0 752GB                | 2         | 2      | 2.56%   |
| WDC WD5000AAKS-00UU3A0 500GB                | 2         | 5      | 2.56%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 2         | 2      | 2.56%   |
| Seagate ST31000524AS 1TB                    | 2         | 2      | 2.56%   |
| Hitachi HTS543216L9SA00 160GB               | 2         | 2      | 2.56%   |
| WDC WD800JB-00CRA1 80GB                     | 1         | 1      | 1.28%   |
| WDC WD800BB-00CAA1 80GB                     | 1         | 1      | 1.28%   |
| WDC WD6400AAKS-75A7B0 640GB                 | 1         | 2      | 1.28%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1         | 1      | 1.28%   |
| WDC WD5000AAJS-00YFA0 500GB                 | 1         | 1      | 1.28%   |
| WDC WD40EFRX-68WT0N0 4TB                    | 1         | 4      | 1.28%   |
| WDC WD3200AAKS-00V1A0 320GB                 | 1         | 1      | 1.28%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 1.28%   |
| WDC WD10EALX-009BA0 1TB                     | 1         | 1      | 1.28%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 1      | 1.28%   |
| Toshiba MK5055GSX 500GB                     | 1         | 3      | 1.28%   |
| Toshiba HDWD110 1TB                         | 1         | 1      | 1.28%   |
| SK hynix SH920 2.5 7MM 128GB SSD            | 1         | 1      | 1.28%   |
| SK hynix SC210 2.5 7MM 256GB SSD            | 1         | 1      | 1.28%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1      | 1.28%   |
| Seagate ST9750420AS 752GB                   | 1         | 1      | 1.28%   |
| Seagate ST9250827AS 250GB                   | 1         | 1      | 1.28%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 1.28%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 1.28%   |
| Seagate ST500LM000-SSHD-8GB                 | 1         | 1      | 1.28%   |
| Seagate ST4000VN008-2DR166 4TB              | 1         | 1      | 1.28%   |
| Seagate ST4000LM024-2AN17V 4TB              | 1         | 1      | 1.28%   |
| Seagate ST3500418AS 500GB                   | 1         | 1      | 1.28%   |
| Seagate ST31000528AS 1TB                    | 1         | 1      | 1.28%   |
| Seagate ST3000DM008-2DM166 3TB              | 1         | 1      | 1.28%   |
| Seagate ST3000DM001-1CH166 3TB              | 1         | 17     | 1.28%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 1      | 1.28%   |
| Seagate ST2000DM001-1E6164 2TB              | 1         | 1      | 1.28%   |
| Seagate ST1000LM014-SSHD-8GB                | 1         | 1      | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB              | 1         | 1      | 1.28%   |
| Seagate ST1000DM003-1CH162 1TB              | 1         | 1      | 1.28%   |
| SanDisk SSD PLUS 1000GB                     | 1         | 1      | 1.28%   |
| SanDisk SD8TN8U-256G-1006 256GB SSD         | 1         | 1      | 1.28%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB | 1         | 1      | 1.28%   |
| Samsung Electronics SSD 970 EVO 500GB       | 1         | 1      | 1.28%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 34     | 22.37%  |
| WDC                 | 15        | 23     | 19.74%  |
| Hitachi             | 8         | 9      | 10.53%  |
| Intel               | 7         | 9      | 9.21%   |
| Samsung Electronics | 5         | 5      | 6.58%   |
| SK hynix            | 3         | 3      | 3.95%   |
| Micron Technology   | 3         | 6      | 3.95%   |
| Kingston            | 3         | 4      | 3.95%   |
| HGST                | 3         | 4      | 3.95%   |
| Toshiba             | 2         | 4      | 2.63%   |
| SanDisk             | 2         | 2      | 2.63%   |
| LITEON              | 2         | 2      | 2.63%   |
| Crucial             | 2         | 2      | 2.63%   |
| Corsair             | 2         | 2      | 2.63%   |
| OCZ                 | 1         | 1      | 1.32%   |
| Lenovo              | 1         | 1      | 1.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 34     | 36.17%  |
| WDC                 | 15        | 23     | 31.91%  |
| Hitachi             | 8         | 9      | 17.02%  |
| HGST                | 3         | 4      | 6.38%   |
| Toshiba             | 2         | 4      | 4.26%   |
| Samsung Electronics | 2         | 2      | 4.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 76     | 60.81%  |
| SSD  | 22        | 26     | 29.73%  |
| NVMe | 7         | 9      | 9.46%   |

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
| Detected | 576       | 1253   | 54.91%  |
| Works    | 397       | 814    | 37.85%  |
| Malfunc  | 72        | 111    | 6.86%   |
| Failed   | 4         | 4      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 609       | 47.36%  |
| AMD                              | 185       | 14.39%  |
| Samsung Electronics              | 177       | 13.76%  |
| SanDisk                          | 61        | 4.74%   |
| Kingston Technology Company      | 35        | 2.72%   |
| Toshiba America Info Systems     | 34        | 2.64%   |
| SK hynix                         | 34        | 2.64%   |
| Phison Electronics               | 30        | 2.33%   |
| ASMedia Technology               | 24        | 1.87%   |
| Micron Technology                | 17        | 1.32%   |
| Nvidia                           | 12        | 0.93%   |
| LSI Logic / Symbios Logic        | 12        | 0.93%   |
| Broadcom / LSI                   | 9         | 0.7%    |
| Micron/Crucial Technology        | 6         | 0.47%   |
| Marvell Technology Group         | 6         | 0.47%   |
| KIOXIA                           | 6         | 0.47%   |
| Lenovo                           | 5         | 0.39%   |
| JMicron Technology               | 5         | 0.39%   |
| Lite-On Technology               | 4         | 0.31%   |
| ADATA Technology                 | 4         | 0.31%   |
| Silicon Motion                   | 2         | 0.16%   |
| Seagate Technology               | 2         | 0.16%   |
| Solid State Storage Technology   | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| Silicon Image                    | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |
| Adaptec                          | 1         | 0.08%   |
| 3ware                            | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 124       | 8.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 87        | 6.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 56        | 3.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 52        | 3.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 44        | 3.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 38        | 2.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 36        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 33        | 2.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 32        | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 31        | 2.16%   |
| AMD 400 Series Chipset SATA Controller                                         | 26        | 1.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 1.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 1.6%    |
| Intel SATA Controller [RAID mode]                                              | 22        | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 22        | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 22        | 1.53%   |
| AMD 500 Series Chipset SATA Controller                                         | 22        | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 20        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 20        | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 19        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 19        | 1.32%   |
| Micron NVMe Storage Controller                                                 | 17        | 1.18%   |
| Kingston Company A2000 NVMe SSD                                                | 16        | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 16        | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 16        | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 15        | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 14        | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                               | 14        | 0.97%   |
| Intel SSD 660P Series                                                          | 14        | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 14        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 0.9%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 12        | 0.84%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 0.84%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 12        | 0.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 12        | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 11        | 0.77%   |
| Phison E12 NVMe Controller                                                     | 11        | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 707       | 55.54%  |
| NVMe | 395       | 31.03%  |
| RAID | 95        | 7.46%   |
| IDE  | 66        | 5.18%   |
| SAS  | 5         | 0.39%   |
| SCSI | 5         | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 729       | 75.78%  |
| AMD      | 223       | 23.18%  |
| ARM      | 9         | 0.94%   |
| QUALCOMM | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 19        | 1.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 1.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 14        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.35%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 12        | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 11        | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 1.04%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 10        | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 9         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 0.93%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 9         | 0.93%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 9         | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 8         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 8         | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 8         | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 8         | 0.83%   |
| AMD Ryzen 5 3600 6-Core Processor       | 8         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 7         | 0.73%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 7         | 0.73%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 7         | 0.73%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 7         | 0.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 0.73%   |
| ARM Processor                           | 7         | 0.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 0.62%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 0.62%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 6         | 0.62%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 6         | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 6         | 0.62%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 6         | 0.62%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 6         | 0.62%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 6         | 0.62%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz     | 5         | 0.52%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 5         | 0.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 5         | 0.52%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 5         | 0.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 0.52%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 5         | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 5         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 261       | 27.1%   |
| Intel Core i5           | 240       | 24.92%  |
| Other                   | 59        | 6.13%   |
| AMD Ryzen 7             | 56        | 5.82%   |
| AMD Ryzen 5             | 46        | 4.78%   |
| Intel Core i3           | 43        | 4.47%   |
| AMD Ryzen 9             | 33        | 3.43%   |
| Intel Xeon              | 26        | 2.7%    |
| Intel Celeron           | 24        | 2.49%   |
| Intel Core i9           | 18        | 1.87%   |
| Intel Core 2 Duo        | 16        | 1.66%   |
| Intel Pentium           | 14        | 1.45%   |
| AMD FX                  | 11        | 1.14%   |
| Intel Atom              | 10        | 1.04%   |
| AMD Athlon 64 X2        | 7         | 0.73%   |
| AMD A8                  | 7         | 0.73%   |
| Intel Core 2            | 6         | 0.62%   |
| AMD Ryzen 7 PRO         | 6         | 0.62%   |
| Intel Pentium Dual-Core | 5         | 0.52%   |
| AMD A6                  | 5         | 0.52%   |
| AMD A10                 | 5         | 0.52%   |
| Intel Genuine           | 4         | 0.42%   |
| AMD Ryzen 5 PRO         | 4         | 0.42%   |
| AMD Phenom II X4        | 4         | 0.42%   |
| Intel Xeon Silver       | 3         | 0.31%   |
| AMD Ryzen 3             | 3         | 0.31%   |
| AMD E2                  | 3         | 0.31%   |
| AMD E                   | 3         | 0.31%   |
| AMD Athlon              | 3         | 0.31%   |
| Intel Pentium Silver    | 2         | 0.21%   |
| Intel Core m7           | 2         | 0.21%   |
| AMD Turion 64 X2 Mobile | 2         | 0.21%   |
| AMD Ryzen Threadripper  | 2         | 0.21%   |
| AMD Phenom II           | 2         | 0.21%   |
| AMD E1                  | 2         | 0.21%   |
| AMD Dual Core Opteron   | 2         | 0.21%   |
| AMD Athlon II X4        | 2         | 0.21%   |
| AMD A4                  | 2         | 0.21%   |
| Intel Pentium III       | 1         | 0.1%    |
| Intel Pentium Gold      | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 347       | 35.96%  |
| 2      | 329       | 34.09%  |
| 6      | 116       | 12.02%  |
| 8      | 87        | 9.02%   |
| 12     | 29        | 3.01%   |
| 1      | 14        | 1.45%   |
| 16     | 13        | 1.35%   |
| 10     | 8         | 0.83%   |
| 3      | 7         | 0.73%   |
| 14     | 5         | 0.52%   |
| 20     | 4         | 0.41%   |
| 28     | 2         | 0.21%   |
| 40     | 1         | 0.1%    |
| 32     | 1         | 0.1%    |
| 24     | 1         | 0.1%    |
| 18     | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 946       | 98.34%  |
| 2      | 15        | 1.56%   |
| 4      | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 726       | 75.08%  |
| 1      | 240       | 24.82%  |
| 8      | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 936       | 97.2%   |
| Unknown        | 19        | 1.97%   |
| 32-bit         | 6         | 0.62%   |
| 64-bit         | 2         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 294       | 29.4%   |
| 0x306a9    | 46        | 4.6%    |
| 0x306c3    | 41        | 4.1%    |
| 0x206a7    | 39        | 3.9%    |
| 0x906ea    | 37        | 3.7%    |
| 0x506e3    | 33        | 3.3%    |
| 0x806ea    | 30        | 3%      |
| 0x406e3    | 27        | 2.7%    |
| 0x40651    | 26        | 2.6%    |
| 0x906e9    | 22        | 2.2%    |
| 0x806ec    | 22        | 2.2%    |
| 0x806e9    | 21        | 2.1%    |
| 0x08701021 | 20        | 2%      |
| 0x306d4    | 19        | 1.9%    |
| 0x1067a    | 15        | 1.5%    |
| 0x806c1    | 13        | 1.3%    |
| 0x20655    | 13        | 1.3%    |
| 0xa0652    | 11        | 1.1%    |
| 0x08600106 | 11        | 1.1%    |
| 0x906ed    | 8         | 0.8%    |
| 0x906a3    | 8         | 0.8%    |
| 0x806eb    | 8         | 0.8%    |
| 0x306f2    | 8         | 0.8%    |
| 0x0a201016 | 8         | 0.8%    |
| 0x08701013 | 8         | 0.8%    |
| 0x010000c8 | 8         | 0.8%    |
| 0x0800820d | 7         | 0.7%    |
| 0x806d1    | 6         | 0.6%    |
| 0x20652    | 6         | 0.6%    |
| 0x06001119 | 6         | 0.6%    |
| 0x06000852 | 6         | 0.6%    |
| 0x706e5    | 5         | 0.5%    |
| 0x0a601203 | 5         | 0.5%    |
| 0x0a50000c | 5         | 0.5%    |
| 0x0a201009 | 5         | 0.5%    |
| 0x08600104 | 5         | 0.5%    |
| 0x08600103 | 5         | 0.5%    |
| 0x6f6      | 4         | 0.4%    |
| 0x506c9    | 4         | 0.4%    |
| 0x406f1    | 4         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 196       | 20.31%  |
| Haswell          | 106       | 10.98%  |
| Skylake          | 92        | 9.53%   |
| IvyBridge        | 65        | 6.74%   |
| Zen 2            | 63        | 6.53%   |
| SandyBridge      | 55        | 5.7%    |
| Zen 3            | 38        | 3.94%   |
| Broadwell        | 36        | 3.73%   |
| Unknown          | 31        | 3.21%   |
| Zen+             | 26        | 2.69%   |
| Westmere         | 25        | 2.59%   |
| TigerLake        | 23        | 2.38%   |
| Penryn           | 22        | 2.28%   |
| CometLake        | 20        | 2.07%   |
| Zen              | 17        | 1.76%   |
| Piledriver       | 17        | 1.76%   |
| K8 Hammer        | 14        | 1.45%   |
| Silvermont       | 13        | 1.35%   |
| K10              | 13        | 1.35%   |
| IceLake          | 13        | 1.35%   |
| Alderlake Hybrid | 12        | 1.24%   |
| Core             | 11        | 1.14%   |
| Goldmont plus    | 8         | 0.83%   |
| Nehalem          | 7         | 0.73%   |
| Bonnell          | 7         | 0.73%   |
| Excavator        | 5         | 0.52%   |
| Bobcat           | 5         | 0.52%   |
| P6               | 4         | 0.41%   |
| Goldmont         | 4         | 0.41%   |
| Bulldozer        | 4         | 0.41%   |
| Steamroller      | 3         | 0.31%   |
| Puma             | 3         | 0.31%   |
| K10 Llano        | 3         | 0.31%   |
| Jaguar           | 2         | 0.21%   |
| Tremont          | 1         | 0.1%    |
| NetBurst         | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 551       | 48.5%   |
| Nvidia                     | 344       | 30.28%  |
| AMD                        | 226       | 19.89%  |
| Matrox Electronics Systems | 14        | 1.23%   |
| ASPEED Technology          | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 43        | 3.72%   |
| Intel UHD Graphics 620                                                                   | 38        | 3.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 36        | 3.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 32        | 2.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29        | 2.51%   |
| Intel HD Graphics 620                                                                    | 27        | 2.33%   |
| AMD Renoir                                                                               | 27        | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 25        | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24        | 2.07%   |
| Intel HD Graphics 530                                                                    | 24        | 2.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 1.82%   |
| Intel HD Graphics 5500                                                                   | 21        | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 19        | 1.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 15        | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 1.3%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 13        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 12        | 1.04%   |
| Intel HD Graphics 630                                                                    | 12        | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 0.95%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 11        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 0.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.78%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 9         | 0.78%   |
| Matrox Electronics Systems G200eR2                                                       | 8         | 0.69%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 8         | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 7         | 0.61%   |
| Intel Iris Graphics 6100                                                                 | 7         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.52%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6         | 0.52%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 6         | 0.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 387       | 39.9%   |
| 1 x Nvidia           | 189       | 19.48%  |
| 1 x AMD              | 183       | 18.87%  |
| Intel + Nvidia       | 137       | 14.12%  |
| Intel + AMD          | 20        | 2.06%   |
| 1 x Matrox           | 13        | 1.34%   |
| Other                | 12        | 1.24%   |
| AMD + Nvidia         | 12        | 1.24%   |
| 2 x AMD              | 11        | 1.13%   |
| 2 x Nvidia           | 3         | 0.31%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.1%    |
| Nvidia + Matrox      | 1         | 0.1%    |
| Nvidia + ASPEED      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 724       | 73.8%   |
| Proprietary | 212       | 21.61%  |
| Unknown     | 45        | 4.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 574       | 58.27%  |
| 1.01-2.0   | 102       | 10.36%  |
| 0.01-0.5   | 81        | 8.22%   |
| 7.01-8.0   | 66        | 6.7%    |
| 3.01-4.0   | 60        | 6.09%   |
| 0.51-1.0   | 40        | 4.06%   |
| 5.01-6.0   | 26        | 2.64%   |
| 8.01-16.0  | 19        | 1.93%   |
| 2.01-3.0   | 12        | 1.22%   |
| 16.01-24.0 | 3         | 0.3%    |
| 4.01-5.0   | 2         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 155       | 14.09%  |
| LG Display              | 112       | 10.18%  |
| AU Optronics            | 107       | 9.73%   |
| Chimei Innolux          | 82        | 7.45%   |
| Dell                    | 79        | 7.18%   |
| BOE                     | 65        | 5.91%   |
| AOC                     | 46        | 4.18%   |
| BenQ                    | 45        | 4.09%   |
| Acer                    | 40        | 3.64%   |
| Lenovo                  | 36        | 3.27%   |
| Ancor Communications    | 34        | 3.09%   |
| Sharp                   | 33        | 3%      |
| Hewlett-Packard         | 33        | 3%      |
| Philips                 | 31        | 2.82%   |
| Apple                   | 22        | 2%      |
| InfoVision              | 16        | 1.45%   |
| ASUSTek Computer        | 16        | 1.45%   |
| Goldstar                | 13        | 1.18%   |
| Chi Mei Optoelectronics | 11        | 1%      |
| NEC Computers           | 9         | 0.82%   |
| CSO                     | 8         | 0.73%   |
| JDI                     | 7         | 0.64%   |
| Sony                    | 6         | 0.55%   |
| PANDA                   | 6         | 0.55%   |
| Grundig                 | 6         | 0.55%   |
| Panasonic               | 5         | 0.45%   |
| Unknown                 | 4         | 0.36%   |
| LG Electronics          | 4         | 0.36%   |
| Fujitsu Siemens         | 4         | 0.36%   |
| Eizo                    | 4         | 0.36%   |
| VOXICON                 | 3         | 0.27%   |
| Vestel Elektronik       | 3         | 0.27%   |
| Iiyama                  | 3         | 0.27%   |
| HVR                     | 3         | 0.27%   |
| Gigabyte Technology     | 3         | 0.27%   |
| Denver                  | 3         | 0.27%   |
| AUS                     | 3         | 0.27%   |
| ViewSonic               | 2         | 0.18%   |
| Toshiba                 | 2         | 0.18%   |
| MSI                     | 2         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 7         | 0.61%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.52%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 6         | 0.52%   |
| Grundig WUXGA GRU4448 1920x1080                                       | 6         | 0.52%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 5         | 0.44%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch            | 5         | 0.44%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                    | 5         | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 5         | 0.44%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 5         | 0.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 5         | 0.44%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 5         | 0.44%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 5         | 0.44%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch  | 4         | 0.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 4         | 0.35%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.35%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 4         | 0.35%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                     | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 4         | 0.35%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.35%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 4         | 0.35%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 4         | 0.35%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 521x293mm 23.5-inch | 4         | 0.35%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 3         | 0.26%   |
| Sony TV SNYEE01 1920x1080                                             | 3         | 0.26%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.26%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.26%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch  | 3         | 0.26%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 3         | 0.26%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch             | 3         | 0.26%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 3         | 0.26%   |
| NEC Computers P403 NEC692B 1920x1080 886x498mm 40.0-inch              | 3         | 0.26%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 475       | 44.85%  |
| 1366x768 (WXGA)    | 112       | 10.58%  |
| 3840x2160 (4K)     | 109       | 10.29%  |
| 2560x1440 (QHD)    | 81        | 7.65%   |
| 1920x1200 (WUXGA)  | 49        | 4.63%   |
| 1600x900 (HD+)     | 35        | 3.31%   |
| 3440x1440          | 31        | 2.93%   |
| Unknown            | 15        | 1.42%   |
| 1280x800 (WXGA)    | 14        | 1.32%   |
| 1680x1050 (WSXGA+) | 13        | 1.23%   |
| 1280x1024 (SXGA)   | 12        | 1.13%   |
| 2560x1600          | 11        | 1.04%   |
| 3840x1080          | 10        | 0.94%   |
| 1440x900 (WXGA+)   | 8         | 0.76%   |
| 3840x1600          | 7         | 0.66%   |
| 3000x2000          | 7         | 0.66%   |
| 2880x1800          | 7         | 0.66%   |
| 1600x1200          | 7         | 0.66%   |
| 3840x2400          | 6         | 0.57%   |
| 2160x1440          | 6         | 0.57%   |
| 2560x1080          | 5         | 0.47%   |
| 1360x768           | 5         | 0.47%   |
| 1024x600           | 4         | 0.38%   |
| 2160x1200          | 3         | 0.28%   |
| 1920x540           | 3         | 0.28%   |
| 5120x1440          | 2         | 0.19%   |
| 4480x1440          | 2         | 0.19%   |
| 3200x1800 (QHD+)   | 2         | 0.19%   |
| 2288x1287          | 2         | 0.19%   |
| 1280x720 (HD)      | 2         | 0.19%   |
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
| 15      | 210       | 19.21%  |
| 27      | 135       | 12.35%  |
| 24      | 125       | 11.44%  |
| 13      | 124       | 11.34%  |
| 14      | 110       | 10.06%  |
| Unknown | 65        | 5.95%   |
| 17      | 42        | 3.84%   |
| 23      | 40        | 3.66%   |
| 12      | 36        | 3.29%   |
| 34      | 29        | 2.65%   |
| 31      | 24        | 2.2%    |
| 21      | 16        | 1.46%   |
| 84      | 15        | 1.37%   |
| 22      | 12        | 1.1%    |
| 19      | 9         | 0.82%   |
| 54      | 8         | 0.73%   |
| 48      | 8         | 0.73%   |
| 25      | 8         | 0.73%   |
| 37      | 7         | 0.64%   |
| 20      | 7         | 0.64%   |
| 40      | 6         | 0.55%   |
| 32      | 6         | 0.55%   |
| 72      | 5         | 0.46%   |
| 11      | 5         | 0.46%   |
| 43      | 4         | 0.37%   |
| 35      | 4         | 0.37%   |
| 26      | 3         | 0.27%   |
| 16      | 3         | 0.27%   |
| 10      | 3         | 0.27%   |
| 142     | 2         | 0.18%   |
| 65      | 2         | 0.18%   |
| 60      | 2         | 0.18%   |
| 55      | 2         | 0.18%   |
| 42      | 2         | 0.18%   |
| 39      | 2         | 0.18%   |
| 33      | 2         | 0.18%   |
| 18      | 2         | 0.18%   |
| 46      | 1         | 0.09%   |
| 44      | 1         | 0.09%   |
| 38      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 370       | 34.94%  |
| 501-600        | 264       | 24.93%  |
| 201-300        | 115       | 10.86%  |
| Unknown        | 65        | 6.14%   |
| 351-400        | 59        | 5.57%   |
| 601-700        | 44        | 4.15%   |
| 701-800        | 37        | 3.49%   |
| 401-500        | 33        | 3.12%   |
| 1001-1500      | 23        | 2.17%   |
| 801-900        | 21        | 1.98%   |
| 1501-2000      | 19        | 1.79%   |
| 901-1000       | 6         | 0.57%   |
| More than 2000 | 2         | 0.19%   |
| 101-200        | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 714       | 74.07%  |
| 16/10   | 108       | 11.2%   |
| Unknown | 51        | 5.29%   |
| 21/9    | 41        | 4.25%   |
| 3/2     | 19        | 1.97%   |
| 5/4     | 12        | 1.24%   |
| 32/9    | 8         | 0.83%   |
| 4/3     | 5         | 0.52%   |
| 1.00    | 2         | 0.21%   |
| 6/5     | 1         | 0.1%    |
| 3.76    | 1         | 0.1%    |
| 3.40    | 1         | 0.1%    |
| 0.80    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 206       | 19.09%  |
| 81-90          | 177       | 16.4%   |
| 201-250        | 138       | 12.79%  |
| 301-350        | 136       | 12.6%   |
| 351-500        | 68        | 6.3%    |
| Unknown        | 65        | 6.02%   |
| 71-80          | 58        | 5.38%   |
| 251-300        | 52        | 4.82%   |
| More than 1000 | 36        | 3.34%   |
| 121-130        | 35        | 3.24%   |
| 61-70          | 34        | 3.15%   |
| 501-1000       | 28        | 2.59%   |
| 151-200        | 21        | 1.95%   |
| 51-60          | 6         | 0.56%   |
| 131-140        | 6         | 0.56%   |
| 111-120        | 6         | 0.56%   |
| 41-50          | 3         | 0.28%   |
| 141-150        | 2         | 0.19%   |
| 1-40           | 1         | 0.09%   |
| 91-100         | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 332       | 31.44%  |
| 51-100        | 297       | 28.13%  |
| 101-120       | 216       | 20.45%  |
| 161-240       | 78        | 7.39%   |
| Unknown       | 65        | 6.16%   |
| More than 240 | 44        | 4.17%   |
| 1-50          | 24        | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 705       | 71.43%  |
| 2     | 196       | 19.86%  |
| 0     | 50        | 5.07%   |
| 3     | 34        | 3.44%   |
| 4     | 2         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 610       | 42.57%  |
| Realtek Semiconductor                  | 379       | 26.45%  |
| Qualcomm Atheros                       | 112       | 7.82%   |
| Broadcom                               | 89        | 6.21%   |
| Broadcom Limited                       | 21        | 1.47%   |
| Sierra Wireless                        | 17        | 1.19%   |
| Ericsson Business Mobile Networks      | 16        | 1.12%   |
| Ralink                                 | 14        | 0.98%   |
| NetGear                                | 14        | 0.98%   |
| Ralink Technology                      | 12        | 0.84%   |
| MediaTek                               | 12        | 0.84%   |
| Dell                                   | 12        | 0.84%   |
| Nvidia                                 | 11        | 0.77%   |
| ASUSTek Computer                       | 11        | 0.77%   |
| Lenovo                                 | 8         | 0.56%   |
| Hewlett-Packard                        | 8         | 0.56%   |
| TP-Link                                | 7         | 0.49%   |
| Marvell Technology Group               | 7         | 0.49%   |
| Samsung Electronics                    | 6         | 0.42%   |
| Microsoft                              | 6         | 0.42%   |
| Linksys                                | 5         | 0.35%   |
| DisplayLink                            | 5         | 0.35%   |
| Aquantia                               | 5         | 0.35%   |
| Motorola PCS                           | 4         | 0.28%   |
| Fibocom                                | 4         | 0.28%   |
| Qualcomm Atheros Communications        | 3         | 0.21%   |
| Qualcomm                               | 3         | 0.21%   |
| Microchip Technology                   | 3         | 0.21%   |
| Huawei Technologies                    | 3         | 0.21%   |
| Chu Yuen Enterprise                    | 3         | 0.21%   |
| ASIX Electronics                       | 3         | 0.21%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.14%   |
| Sigma Designs                          | 2         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.14%   |
| JMicron Technology                     | 2         | 0.14%   |
| Arduino SA                             | 2         | 0.14%   |
| Winbond Electronics                    | 1         | 0.07%   |
| Wacom                                  | 1         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.07%   |
| SEGGER                                 | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 256       | 14.5%   |
| Intel Wi-Fi 6 AX200                                               | 74        | 4.19%   |
| Intel Wireless 8265 / 8275                                        | 56        | 3.17%   |
| Intel I211 Gigabit Network Connection                             | 49        | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 49        | 2.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 39        | 2.21%   |
| Intel Wireless 7265                                               | 37        | 2.1%    |
| Intel Wireless 8260                                               | 33        | 1.87%   |
| Intel Wireless 7260                                               | 30        | 1.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 25        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 1.36%   |
| Intel Ethernet Controller I225-V                                  | 22        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 22        | 1.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 20        | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 19        | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 17        | 0.96%   |
| Intel Wireless-AC 9260                                            | 17        | 0.96%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 0.79%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14        | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.74%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 13        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 0.74%   |
| Intel Centrino Ultimate-N 6300                                    | 13        | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 13        | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 0.62%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 11        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.62%   |
| Sierra Wireless EM7455                                            | 10        | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 463       | 56.19%  |
| Qualcomm Atheros                | 88        | 10.68%  |
| Realtek Semiconductor           | 74        | 8.98%   |
| Broadcom                        | 61        | 7.4%    |
| Broadcom Limited                | 18        | 2.18%   |
| Sierra Wireless                 | 17        | 2.06%   |
| Ralink                          | 14        | 1.7%    |
| NetGear                         | 14        | 1.7%    |
| Ralink Technology               | 12        | 1.46%   |
| MediaTek                        | 12        | 1.46%   |
| ASUSTek Computer                | 11        | 1.33%   |
| TP-Link                         | 7         | 0.85%   |
| Dell                            | 7         | 0.85%   |
| Microsoft                       | 5         | 0.61%   |
| Linksys                         | 4         | 0.49%   |
| Fibocom                         | 4         | 0.49%   |
| Qualcomm Atheros Communications | 3         | 0.36%   |
| Qualcomm                        | 3         | 0.36%   |
| Hewlett-Packard                 | 3         | 0.36%   |
| Chu Yuen Enterprise             | 3         | 0.36%   |
| Wacom                           | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 74        | 8.97%   |
| Intel Wireless 8265 / 8275                                     | 56        | 6.79%   |
| Intel Wireless 7265                                            | 37        | 4.48%   |
| Intel Wireless 8260                                            | 33        | 4%      |
| Intel Wireless 7260                                            | 30        | 3.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 22        | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20        | 2.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 2.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 17        | 2.06%   |
| Intel Wireless-AC 9260                                         | 17        | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 1.7%    |
| Intel Wi-Fi 6 AX201                                            | 14        | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 1.58%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 1.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 13        | 1.58%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 1.33%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 11        | 1.33%   |
| Sierra Wireless EM7455                                         | 10        | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.09%   |
| Intel Wireless 3165                                            | 9         | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 9         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 1.09%   |
| Intel Centrino Advanced-N 6235                                 | 9         | 1.09%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 9         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 0.97%   |
| Intel WiFi Link 5100                                           | 8         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 0.97%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 8         | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 0.85%   |
| Intel Wireless 3160                                            | 7         | 0.85%   |
| Intel Centrino Wireless-N 2230                                 | 7         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 0.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.73%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 6         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 379       | 43.41%  |
| Realtek Semiconductor                  | 344       | 39.4%   |
| Broadcom                               | 44        | 5.04%   |
| Qualcomm Atheros                       | 41        | 4.7%    |
| Nvidia                                 | 11        | 1.26%   |
| Lenovo                                 | 8         | 0.92%   |
| Marvell Technology Group               | 7         | 0.8%    |
| Samsung Electronics                    | 5         | 0.57%   |
| DisplayLink                            | 5         | 0.57%   |
| Broadcom Limited                       | 5         | 0.57%   |
| Aquantia                               | 5         | 0.57%   |
| Huawei Technologies                    | 3         | 0.34%   |
| ASIX Electronics                       | 3         | 0.34%   |
| JMicron Technology                     | 2         | 0.23%   |
| T & A Mobile Phones                    | 1         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.11%   |
| NetXen Incorporated                    | 1         | 0.11%   |
| Microsoft                              | 1         | 0.11%   |
| Linksys                                | 1         | 0.11%   |
| Hewlett-Packard                        | 1         | 0.11%   |
| D-Link                                 | 1         | 0.11%   |
| Cisco Systems                          | 1         | 0.11%   |
| ATEN International                     | 1         | 0.11%   |
| 3Com                                   | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 256       | 28.48%  |
| Intel I211 Gigabit Network Connection                             | 49        | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 49        | 5.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 39        | 4.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 25        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 2.67%   |
| Intel Ethernet Controller I225-V                                  | 22        | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 2%      |
| Intel Ethernet Connection (4) I219-V                              | 15        | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 1.56%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 1.45%   |
| Intel Ethernet Connection (6) I219-V                              | 13        | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 1.45%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 1.22%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1%      |
| Intel I210 Gigabit Network Connection                             | 8         | 0.89%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                             | 6         | 0.67%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.56%   |
| Intel I350 Gigabit Network Connection                             | 5         | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.44%   |
| Intel Ethernet Connection (3) I218-V                              | 4         | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.44%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 816       | 50.46%  |
| WiFi     | 759       | 46.94%  |
| Modem    | 34        | 2.1%    |
| Unknown  | 8         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 591       | 59.4%   |
| Ethernet | 403       | 40.5%   |
| Unknown  | 1         | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 552       | 57.14%  |
| 1     | 356       | 36.85%  |
| 3     | 31        | 3.21%   |
| 0     | 20        | 2.07%   |
| 4     | 5         | 0.52%   |
| 6     | 2         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 861       | 87.23%  |
| Yes  | 126       | 12.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 364       | 57.5%   |
| Broadcom                        | 48        | 7.58%   |
| Realtek Semiconductor           | 31        | 4.9%    |
| Qualcomm Atheros Communications | 26        | 4.11%   |
| Cambridge Silicon Radio         | 26        | 4.11%   |
| Apple                           | 24        | 3.79%   |
| IMC Networks                    | 21        | 3.32%   |
| ASUSTek Computer                | 20        | 3.16%   |
| Lite-On Technology              | 16        | 2.53%   |
| Foxconn / Hon Hai               | 16        | 2.53%   |
| Hewlett-Packard                 | 11        | 1.74%   |
| Dell                            | 10        | 1.58%   |
| MediaTek                        | 5         | 0.79%   |
| Belkin Components               | 4         | 0.63%   |
| HTC (High Tech Computer)        | 3         | 0.47%   |
| Realtek                         | 2         | 0.32%   |
| Marvell Semiconductor           | 2         | 0.32%   |
| Ralink Technology               | 1         | 0.16%   |
| Ralink                          | 1         | 0.16%   |
| Integrated System Solution      | 1         | 0.16%   |
| Actions                         | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 156       | 24.57%  |
| Intel AX200 Bluetooth                                                | 67        | 10.55%  |
| Intel AX201 Bluetooth                                                | 47        | 7.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 36        | 5.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 26        | 4.09%   |
| Realtek Bluetooth Radio                                              | 24        | 3.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 17        | 2.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 13        | 2.05%   |
| Intel Bluetooth Device                                               | 13        | 2.05%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 13        | 2.05%   |
| Apple Bluetooth Host Controller                                      | 10        | 1.57%   |
| Intel AX210 Bluetooth                                                | 9         | 1.42%   |
| IMC Networks Bluetooth Radio                                         | 9         | 1.42%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9         | 1.42%   |
| Lite-On Bluetooth Device                                             | 8         | 1.26%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 8         | 1.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 8         | 1.26%   |
| Apple Bluetooth USB Host Controller                                  | 8         | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 7         | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 7         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                                   | 7         | 1.1%    |
| Qualcomm Atheros  Bluetooth Device                                   | 6         | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 6         | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5         | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4         | 0.63%   |
| MediaTek Wireless_Device                                             | 4         | 0.63%   |
| IMC Networks Bluetooth Device                                        | 4         | 0.63%   |
| Dell BCM20702A0 Bluetooth Module                                     | 4         | 0.63%   |
| Broadcom BCM20702A0                                                  | 4         | 0.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 4         | 0.63%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                                    | 3         | 0.47%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.47%   |
| Dell DW375 Bluetooth Module                                          | 3         | 0.47%   |
| Broadcom HP Portable SoftSailing                                     | 3         | 0.47%   |
| Broadcom BCM43142A0 Bluetooth Device                                 | 3         | 0.47%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 3         | 0.47%   |
| ASUS Bluetooth Radio                                                 | 3         | 0.47%   |
| Realtek RTL8821A Bluetooth                                           | 2         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 698       | 48.37%  |
| AMD                                          | 271       | 18.78%  |
| Nvidia                                       | 250       | 17.33%  |
| C-Media Electronics                          | 27        | 1.87%   |
| SteelSeries ApS                              | 18        | 1.25%   |
| Logitech                                     | 18        | 1.25%   |
| Realtek Semiconductor                        | 14        | 0.97%   |
| Kingston Technology                          | 13        | 0.9%    |
| Lenovo                                       | 11        | 0.76%   |
| Blue Microphones                             | 8         | 0.55%   |
| GN Netcom                                    | 7         | 0.49%   |
| Focusrite-Novation                           | 7         | 0.49%   |
| Creative Labs                                | 6         | 0.42%   |
| Corsair                                      | 6         | 0.42%   |
| ASUSTek Computer                             | 6         | 0.42%   |
| Texas Instruments                            | 5         | 0.35%   |
| SAVITECH                                     | 5         | 0.35%   |
| Razer USA                                    | 5         | 0.35%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.21%   |
| Sony                                         | 3         | 0.21%   |
| JMTek                                        | 3         | 0.21%   |
| Guangzhou FiiO Electronics                   | 3         | 0.21%   |
| Creative Technology                          | 3         | 0.21%   |
| Yamaha                                       | 2         | 0.14%   |
| XMOS                                         | 2         | 0.14%   |
| Roland                                       | 2         | 0.14%   |
| RODE Microphones                             | 2         | 0.14%   |
| ROCCAT                                       | 2         | 0.14%   |
| Plantronics                                  | 2         | 0.14%   |
| Musical Fidelity                             | 2         | 0.14%   |
| M-Audio                                      | 2         | 0.14%   |
| GYROCOM C&C                                  | 2         | 0.14%   |
| Elgato Systems                               | 2         | 0.14%   |
| DSEA A/S                                     | 2         | 0.14%   |
| Asahi Kasei Microsystems                     | 2         | 0.14%   |
| ZOOM                                         | 1         | 0.07%   |
| www.hirestech.com 2010 REV 1.4               | 1         | 0.07%   |
| Sonicstar                                    | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.07%   |
| Shenzhen Riitek Technology                   | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 105       | 6.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 66        | 3.89%   |
| AMD Family 17h/19h HD Audio Controller                                     | 64        | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 63        | 3.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 52        | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 49        | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 48        | 2.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 42        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41        | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 39        | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 37        | 2.18%   |
| Intel 8 Series HD Audio Controller                                         | 36        | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 31        | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 31        | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 30        | 1.77%   |
| Intel Broadwell-U Audio Controller                                         | 30        | 1.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 27        | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 27        | 1.59%   |
| Intel 200 Series PCH HD Audio                                              | 24        | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 24        | 1.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 23        | 1.36%   |
| AMD FCH Azalia Controller                                                  | 23        | 1.36%   |
| Nvidia GP106 High Definition Audio Controller                              | 21        | 1.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 20        | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19        | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                              | 18        | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 1%      |
| AMD Navi 10 HDMI Audio                                                     | 16        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 14        | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 0.77%   |
| Realtek Semiconductor USB Audio                                            | 12        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12        | 0.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 12        | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 11        | 0.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 0.65%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 10        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 147       | 24.71%  |
| SK hynix            | 128       | 21.51%  |
| Kingston            | 82        | 13.78%  |
| Micron Technology   | 56        | 9.41%   |
| Corsair             | 49        | 8.24%   |
| Crucial             | 38        | 6.39%   |
| Unknown             | 36        | 6.05%   |
| G.Skill             | 18        | 3.03%   |
| Elpida              | 10        | 1.68%   |
| Ramaxel Technology  | 7         | 1.18%   |
| A-DATA Technology   | 7         | 1.18%   |
| Team                | 2         | 0.34%   |
| Patriot             | 2         | 0.34%   |
| Nanya Technology    | 2         | 0.34%   |
| Unknown             | 2         | 0.34%   |
| Unknown (ABCD)      | 1         | 0.17%   |
| Transcend           | 1         | 0.17%   |
| Toshiba             | 1         | 0.17%   |
| SK_Hynix            | 1         | 0.17%   |
| Hewlett-Packard     | 1         | 0.17%   |
| GeIL                | 1         | 0.17%   |
| ASint Technology    | 1         | 0.17%   |
| Apacer              | 1         | 0.17%   |
| 48spaces            | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 7         | 1.12%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 7         | 1.12%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.96%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.96%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 5         | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 5         | 0.8%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.8%    |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 5         | 0.8%    |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                      | 5         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.8%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.8%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 5         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.64%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.64%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 4         | 0.64%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 4         | 0.64%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s             | 4         | 0.64%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 4         | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.48%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.48%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.48%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s             | 3         | 0.48%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.48%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.48%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 3         | 0.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.48%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.48%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.48%   |
| Samsung RAM M471A2G44AM0-CTD 16GB DDR4 2667MT/s                  | 3         | 0.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.48%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 272       | 52.11%  |
| DDR3    | 154       | 29.5%   |
| LPDDR3  | 31        | 5.94%   |
| LPDDR4  | 20        | 3.83%   |
| DDR2    | 15        | 2.87%   |
| SDRAM   | 7         | 1.34%   |
| LPDDR5  | 7         | 1.34%   |
| DDR5    | 7         | 1.34%   |
| Unknown | 7         | 1.34%   |
| DDR     | 2         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 270       | 51.33%  |
| DIMM         | 182       | 34.6%   |
| Row Of Chips | 58        | 11.03%  |
| Chip         | 11        | 2.09%   |
| Unknown      | 4         | 0.76%   |
| FB-DIMM      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 235       | 42.5%   |
| 4096  | 147       | 26.58%  |
| 16384 | 114       | 20.61%  |
| 2048  | 32        | 5.79%   |
| 32768 | 17        | 3.07%   |
| 1024  | 6         | 1.08%   |
| 512   | 1         | 0.18%   |
| 128   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 102       | 18.02%  |
| 2667    | 88        | 15.55%  |
| 3200    | 64        | 11.31%  |
| 2133    | 56        | 9.89%   |
| 2400    | 42        | 7.42%   |
| 1333    | 25        | 4.42%   |
| 1867    | 20        | 3.53%   |
| 3600    | 18        | 3.18%   |
| 3400    | 14        | 2.47%   |
| 1334    | 14        | 2.47%   |
| 667     | 13        | 2.3%    |
| 4267    | 9         | 1.59%   |
| 6400    | 8         | 1.41%   |
| 3733    | 6         | 1.06%   |
| 1800    | 6         | 1.06%   |
| 4800    | 5         | 0.88%   |
| 3533    | 5         | 0.88%   |
| 3466    | 5         | 0.88%   |
| 3000    | 5         | 0.88%   |
| 2666    | 5         | 0.88%   |
| 1067    | 5         | 0.88%   |
| 4199    | 4         | 0.71%   |
| 2800    | 4         | 0.71%   |
| 1066    | 4         | 0.71%   |
| 8400    | 3         | 0.53%   |
| 3866    | 3         | 0.53%   |
| 3266    | 3         | 0.53%   |
| 800     | 3         | 0.53%   |
| 6000    | 2         | 0.35%   |
| 4266    | 2         | 0.35%   |
| 4000    | 2         | 0.35%   |
| 3333    | 2         | 0.35%   |
| 3151    | 2         | 0.35%   |
| 3100    | 2         | 0.35%   |
| 2933    | 2         | 0.35%   |
| 2733    | 2         | 0.35%   |
| 2000    | 2         | 0.35%   |
| Unknown | 2         | 0.35%   |
| 3800    | 1         | 0.18%   |
| 2187    | 1         | 0.18%   |

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
| Chicony Electronics                    | 139       | 22.24%  |
| IMC Networks                           | 59        | 9.44%   |
| Logitech                               | 57        | 9.12%   |
| Microdia                               | 43        | 6.88%   |
| Sunplus Innovation Technology          | 37        | 5.92%   |
| Bison Electronics                      | 31        | 4.96%   |
| Realtek Semiconductor                  | 28        | 4.48%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 4.16%   |
| Acer                                   | 26        | 4.16%   |
| Apple                                  | 24        | 3.84%   |
| Quanta                                 | 21        | 3.36%   |
| Lite-On Technology                     | 20        | 3.2%    |
| Suyin                                  | 14        | 2.24%   |
| Microsoft                              | 11        | 1.76%   |
| Lenovo                                 | 11        | 1.76%   |
| Luxvisions Innotech Limited            | 8         | 1.28%   |
| Creative Technology                    | 7         | 1.12%   |
| Alcor Micro                            | 7         | 1.12%   |
| Samsung Electronics                    | 6         | 0.96%   |
| Silicon Motion                         | 5         | 0.8%    |
| Primax Electronics                     | 5         | 0.8%    |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.64%   |
| Razer USA                              | 3         | 0.48%   |
| Omnivision                             | 3         | 0.48%   |
| MacroSilicon                           | 3         | 0.48%   |
| Z-Star Microelectronics                | 2         | 0.32%   |
| Syntek                                 | 2         | 0.32%   |
| Sunplus Technology                     | 2         | 0.32%   |
| Sonix Technology                       | 2         | 0.32%   |
| Ricoh                                  | 2         | 0.32%   |
| Generalplus Technology                 | 2         | 0.32%   |
| Cubeternet                             | 2         | 0.32%   |
| ALi                                    | 2         | 0.32%   |
| Y Media                                | 1         | 0.16%   |
| Technologies                           | 1         | 0.16%   |
| TANDBERG                               | 1         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.16%   |
| Novatek Microelectronics               | 1         | 0.16%   |
| Mustek Systems                         | 1         | 0.16%   |
| Magewell                               | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 47        | 7.39%   |
| Microdia Integrated_Webcam_HD                       | 24        | 3.77%   |
| IMC Networks Integrated Camera                      | 21        | 3.3%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 18        | 2.83%   |
| Chicony HP HD Camera                                | 14        | 2.2%    |
| Logitech HD Pro Webcam C920                         | 13        | 2.04%   |
| Sunplus Integrated_Webcam_HD                        | 12        | 1.89%   |
| Realtek Integrated_Webcam_HD                        | 11        | 1.73%   |
| Chicony HP HD Webcam                                | 11        | 1.73%   |
| Lite-On Integrated Camera                           | 10        | 1.57%   |
| Chicony HD WebCam                                   | 10        | 1.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 10        | 1.57%   |
| Logitech C922 Pro Stream Webcam                     | 9         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 7         | 1.1%    |
| Bison Lenovo EasyCamera                             | 7         | 1.1%    |
| Samsung Galaxy series, misc. (MTP mode)             | 6         | 0.94%   |
| Logitech Webcam C270                                | 6         | 0.94%   |
| Lite-On HP HD Camera                                | 6         | 0.94%   |
| Lenovo Integrated Webcam [R5U877]                   | 6         | 0.94%   |
| Chicony Integrated HP HD Webcam                     | 6         | 0.94%   |
| Bison SunplusIT Integrated Camera                   | 6         | 0.94%   |
| Acer Integrated Camera                              | 6         | 0.94%   |
| Sunplus Laptop Integrated Webcam HD                 | 5         | 0.79%   |
| Sunplus HD WebCam                                   | 5         | 0.79%   |
| Quanta HD User Facing                               | 5         | 0.79%   |
| Microsoft LifeCam Cinema                            | 5         | 0.79%   |
| Microdia Integrated Webcam                          | 5         | 0.79%   |
| Chicony HP Wide Vision HD Camera                    | 5         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 0.79%   |
| Bison Integrated Camera                             | 5         | 0.79%   |
| Apple FaceTime HD Camera (Built-in)                 | 5         | 0.79%   |
| Sunplus Asus Webcam                                 | 4         | 0.63%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 4         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam                        | 4         | 0.63%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.63%   |
| Quanta HP HD Camera                                 | 4         | 0.63%   |
| Primax HP HD Webcam [Fixed]                         | 4         | 0.63%   |
| Luxvisions Innotech Limited HP HD Camera            | 4         | 0.63%   |
| Logitech Webcam C930e                               | 4         | 0.63%   |
| Logitech Webcam C925e                               | 4         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 67        | 42.68%  |
| Synaptics                  | 49        | 31.21%  |
| Upek                       | 15        | 9.55%   |
| Shenzhen Goodix Technology | 12        | 7.64%   |
| Elan Microelectronics      | 6         | 3.82%   |
| Samsung Electronics        | 3         | 1.91%   |
| AuthenTec                  | 3         | 1.91%   |
| LighTuning Technology      | 2         | 1.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 12.74%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 8.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 8.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 8.28%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 5.1%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 5.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 4.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 3.82%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 3.82%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.55%   |
| Validity Sensors VFS491                                                    | 4         | 2.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 2.55%   |
| Synaptics WBDI                                                             | 4         | 2.55%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 2.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.91%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.91%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 1.91%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.91%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 1.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.27%   |
| Synaptics UWP WBDI                                                         | 2         | 1.27%   |
| Synaptics  WBDI                                                            | 2         | 1.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.27%   |
| AuthenTec AES2810                                                          | 2         | 1.27%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.64%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.64%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.64%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.64%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.64%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.64%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.64%   |
| AuthenTec AES1600                                                          | 1         | 0.64%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 31        | 39.24%  |
| Broadcom              | 30        | 37.97%  |
| Upek                  | 8         | 10.13%  |
| Lenovo                | 5         | 6.33%   |
| OmniKey               | 2         | 2.53%   |
| Yubico.com            | 1         | 1.27%   |
| Hewlett-Packard       | 1         | 1.27%   |
| Gemalto (was Gemplus) | 1         | 1.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 31        | 39.24%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 12.66%  |
| Broadcom 5880                                                                | 9         | 11.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 10.13%  |
| Broadcom 58200                                                               | 7         | 8.86%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 6.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 5.06%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 2.53%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 1.27%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 620       | 63.01%  |
| 1     | 275       | 27.95%  |
| 2     | 69        | 7.01%   |
| 3     | 18        | 1.83%   |
| 7     | 1         | 0.1%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 157       | 34.97%  |
| Graphics card            | 74        | 16.48%  |
| Chipcard                 | 66        | 14.7%   |
| Net/wireless             | 53        | 11.8%   |
| Unassigned class         | 21        | 4.68%   |
| Multimedia controller    | 20        | 4.45%   |
| Camera                   | 14        | 3.12%   |
| Sound                    | 7         | 1.56%   |
| Communication controller | 7         | 1.56%   |
| Card reader              | 7         | 1.56%   |
| Bluetooth                | 6         | 1.34%   |
| Storage                  | 5         | 1.11%   |
| Net/ethernet             | 5         | 1.11%   |
| Wireless                 | 4         | 0.89%   |
| Storage/raid             | 1         | 0.22%   |
| Modem                    | 1         | 0.22%   |
| Dvb card                 | 1         | 0.22%   |

