Linux in Switzerland - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 3625

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [01e74da42d](https://linux-hardware.org/?probe=01e74da42d) | Nov 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [8efb96e5d7](https://linux-hardware.org/?probe=8efb96e5d7) | Nov 04, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [e6459bb42f](https://linux-hardware.org/?probe=e6459bb42f) | Nov 04, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [36646aca12](https://linux-hardware.org/?probe=36646aca12) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [05304710e4](https://linux-hardware.org/?probe=05304710e4) | Nov 03, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [62f85af4b5](https://linux-hardware.org/?probe=62f85af4b5) | Nov 03, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [792c22d04f](https://linux-hardware.org/?probe=792c22d04f) | Nov 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [7a6f17c843](https://linux-hardware.org/?probe=7a6f17c843) | Nov 03, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [ee12470303](https://linux-hardware.org/?probe=ee12470303) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d371b7299d](https://linux-hardware.org/?probe=d371b7299d) | Nov 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [04f3946d05](https://linux-hardware.org/?probe=04f3946d05) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [493dcbc1f8](https://linux-hardware.org/?probe=493dcbc1f8) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8c2a216d7b](https://linux-hardware.org/?probe=8c2a216d7b) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [6cce294b99](https://linux-hardware.org/?probe=6cce294b99) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [c985fdb0b7](https://linux-hardware.org/?probe=c985fdb0b7) | Nov 01, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [3479b99099](https://linux-hardware.org/?probe=3479b99099) | Nov 01, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [a0393f21c9](https://linux-hardware.org/?probe=a0393f21c9) | Nov 01, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [e9f8c192f1](https://linux-hardware.org/?probe=e9f8c192f1) | Nov 01, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df43f845a1](https://linux-hardware.org/?probe=df43f845a1) | Oct 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [924f7f81ce](https://linux-hardware.org/?probe=924f7f81ce) | Oct 30, 2023 |
| Biostar       | H61MHV2                     | Desktop     | [e8472e117d](https://linux-hardware.org/?probe=e8472e117d) | Oct 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [448c3ca446](https://linux-hardware.org/?probe=448c3ca446) | Oct 30, 2023 |
| HP            | ENVY 17                     | Notebook    | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| HP            | 8918                        | Desktop     | [12336ce9fe](https://linux-hardware.org/?probe=12336ce9fe) | Oct 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [53cddb0f34](https://linux-hardware.org/?probe=53cddb0f34) | Oct 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [effde383d8](https://linux-hardware.org/?probe=effde383d8) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [33d021b931](https://linux-hardware.org/?probe=33d021b931) | Oct 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| Notebook      | V1x0PNPx                    | Notebook    | [f1e27c662a](https://linux-hardware.org/?probe=f1e27c662a) | Oct 27, 2023 |
| System76      | Darter Pro                  | Notebook    | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [7ac5ac2ae2](https://linux-hardware.org/?probe=7ac5ac2ae2) | Oct 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [b90fafd403](https://linux-hardware.org/?probe=b90fafd403) | Oct 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e2f4e41023](https://linux-hardware.org/?probe=e2f4e41023) | Oct 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [39e846913d](https://linux-hardware.org/?probe=39e846913d) | Oct 25, 2023 |
| Unknown       | 1.1                         | Desktop     | [4a673ae7d0](https://linux-hardware.org/?probe=4a673ae7d0) | Oct 24, 2023 |
| Unknown       | 1.1                         | Desktop     | [c006e77646](https://linux-hardware.org/?probe=c006e77646) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [1406d2f4d5](https://linux-hardware.org/?probe=1406d2f4d5) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [56fa067caa](https://linux-hardware.org/?probe=56fa067caa) | Oct 24, 2023 |
| Dell          | Latitude 5520               | Notebook    | [0c8da2f95a](https://linux-hardware.org/?probe=0c8da2f95a) | Oct 24, 2023 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | Desktop     | [71fd7dde1d](https://linux-hardware.org/?probe=71fd7dde1d) | Oct 23, 2023 |
| HP            | 3397                        | Desktop     | [3f8e8810c1](https://linux-hardware.org/?probe=3f8e8810c1) | Oct 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6ef86fc1b9](https://linux-hardware.org/?probe=6ef86fc1b9) | Oct 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [557e6a2f27](https://linux-hardware.org/?probe=557e6a2f27) | Oct 21, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [20f6750372](https://linux-hardware.org/?probe=20f6750372) | Oct 21, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [2f7b2cf78e](https://linux-hardware.org/?probe=2f7b2cf78e) | Oct 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7e0b6aac3](https://linux-hardware.org/?probe=b7e0b6aac3) | Oct 19, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e3126b26df](https://linux-hardware.org/?probe=e3126b26df) | Oct 19, 2023 |
| HP            | 0A68h                       | Desktop     | [376c3156a9](https://linux-hardware.org/?probe=376c3156a9) | Oct 19, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [cf4c60a0a8](https://linux-hardware.org/?probe=cf4c60a0a8) | Oct 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [fc8b87bfe0](https://linux-hardware.org/?probe=fc8b87bfe0) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [cf522294f8](https://linux-hardware.org/?probe=cf522294f8) | Oct 18, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [b6b4b14ba1](https://linux-hardware.org/?probe=b6b4b14ba1) | Oct 18, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [5810a2ef0a](https://linux-hardware.org/?probe=5810a2ef0a) | Oct 17, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [ad07e33f54](https://linux-hardware.org/?probe=ad07e33f54) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [7f5a3b8e10](https://linux-hardware.org/?probe=7f5a3b8e10) | Oct 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2a5d18299e](https://linux-hardware.org/?probe=2a5d18299e) | Oct 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [b593a4511e](https://linux-hardware.org/?probe=b593a4511e) | Oct 13, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [df89a7b20b](https://linux-hardware.org/?probe=df89a7b20b) | Oct 12, 2023 |
| HP            | Unknown                     | Convertible | [8fe4fae90f](https://linux-hardware.org/?probe=8fe4fae90f) | Oct 12, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4bb651a7a6](https://linux-hardware.org/?probe=4bb651a7a6) | Oct 11, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [52bbb0243a](https://linux-hardware.org/?probe=52bbb0243a) | Oct 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [9ff3f35842](https://linux-hardware.org/?probe=9ff3f35842) | Oct 11, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [8ad88c7253](https://linux-hardware.org/?probe=8ad88c7253) | Oct 11, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [89748db0f1](https://linux-hardware.org/?probe=89748db0f1) | Oct 10, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [00f69fbe6c](https://linux-hardware.org/?probe=00f69fbe6c) | Oct 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [c98952b2ee](https://linux-hardware.org/?probe=c98952b2ee) | Oct 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [8dcc2d1ec2](https://linux-hardware.org/?probe=8dcc2d1ec2) | Oct 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [edd7c9e07a](https://linux-hardware.org/?probe=edd7c9e07a) | Oct 09, 2023 |
| HP            | 2187 A01                    | Desktop     | [8d63ab7986](https://linux-hardware.org/?probe=8d63ab7986) | Oct 09, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0c8f955052](https://linux-hardware.org/?probe=0c8f955052) | Oct 08, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [7eb13e7645](https://linux-hardware.org/?probe=7eb13e7645) | Oct 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [dae43772d4](https://linux-hardware.org/?probe=dae43772d4) | Oct 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [ade2b406fd](https://linux-hardware.org/?probe=ade2b406fd) | Oct 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [86f56798dc](https://linux-hardware.org/?probe=86f56798dc) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d8e06a9bf](https://linux-hardware.org/?probe=9d8e06a9bf) | Oct 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [0354977d6c](https://linux-hardware.org/?probe=0354977d6c) | Oct 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [faea5bdeba](https://linux-hardware.org/?probe=faea5bdeba) | Oct 07, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [27ce5f6a61](https://linux-hardware.org/?probe=27ce5f6a61) | Oct 06, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [6347be6a54](https://linux-hardware.org/?probe=6347be6a54) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a308ec4180](https://linux-hardware.org/?probe=a308ec4180) | Oct 06, 2023 |
| HP            | Unknown                     | Convertible | [46bfa371c4](https://linux-hardware.org/?probe=46bfa371c4) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6f6e394cdf](https://linux-hardware.org/?probe=6f6e394cdf) | Oct 05, 2023 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [34c7858d89](https://linux-hardware.org/?probe=34c7858d89) | Oct 04, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [8d69a9df41](https://linux-hardware.org/?probe=8d69a9df41) | Oct 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3fdbdfe773](https://linux-hardware.org/?probe=3fdbdfe773) | Oct 03, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [54231f7059](https://linux-hardware.org/?probe=54231f7059) | Oct 02, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [045606333c](https://linux-hardware.org/?probe=045606333c) | Oct 02, 2023 |
| Fujitsu       | STYLISTIC R726              | Notebook    | [a4c3a19501](https://linux-hardware.org/?probe=a4c3a19501) | Oct 02, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [c71241f73d](https://linux-hardware.org/?probe=c71241f73d) | Oct 01, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [b1af5494c8](https://linux-hardware.org/?probe=b1af5494c8) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [34e5bf82de](https://linux-hardware.org/?probe=34e5bf82de) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [d8c97108ad](https://linux-hardware.org/?probe=d8c97108ad) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [bcbf0e5bfd](https://linux-hardware.org/?probe=bcbf0e5bfd) | Sep 30, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [caa5ce0b99](https://linux-hardware.org/?probe=caa5ce0b99) | Sep 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [725f1e5b25](https://linux-hardware.org/?probe=725f1e5b25) | Sep 29, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [47a0a8627c](https://linux-hardware.org/?probe=47a0a8627c) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [af863ee3d6](https://linux-hardware.org/?probe=af863ee3d6) | Sep 27, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [5351027f5e](https://linux-hardware.org/?probe=5351027f5e) | Sep 25, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [f1721712f2](https://linux-hardware.org/?probe=f1721712f2) | Sep 22, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [16f768ab94](https://linux-hardware.org/?probe=16f768ab94) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [34d899f825](https://linux-hardware.org/?probe=34d899f825) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [8b39e51416](https://linux-hardware.org/?probe=8b39e51416) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [b1fd4a61ae](https://linux-hardware.org/?probe=b1fd4a61ae) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ae7455bac3](https://linux-hardware.org/?probe=ae7455bac3) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6337af2f4c](https://linux-hardware.org/?probe=6337af2f4c) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e04968b0ab](https://linux-hardware.org/?probe=e04968b0ab) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [16c09be7f2](https://linux-hardware.org/?probe=16c09be7f2) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [16f80f70a8](https://linux-hardware.org/?probe=16f80f70a8) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | Notebook    | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [49963f0f8a](https://linux-hardware.org/?probe=49963f0f8a) | Sep 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [06d67bab4a](https://linux-hardware.org/?probe=06d67bab4a) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0c21583146](https://linux-hardware.org/?probe=0c21583146) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | Notebook    | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1f152eb6fa](https://linux-hardware.org/?probe=1f152eb6fa) | Sep 17, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [38a985d781](https://linux-hardware.org/?probe=38a985d781) | Sep 16, 2023 |
| JINGSHA       | X99-D8I                     | Desktop     | [2865a9b1e6](https://linux-hardware.org/?probe=2865a9b1e6) | Sep 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [1b8a46fc57](https://linux-hardware.org/?probe=1b8a46fc57) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1400ef978f](https://linux-hardware.org/?probe=1400ef978f) | Sep 12, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [6b9804a536](https://linux-hardware.org/?probe=6b9804a536) | Sep 10, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [86f844f512](https://linux-hardware.org/?probe=86f844f512) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [0562141e37](https://linux-hardware.org/?probe=0562141e37) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [d824341957](https://linux-hardware.org/?probe=d824341957) | Sep 10, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | Notebook    | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [bb0f6ff00d](https://linux-hardware.org/?probe=bb0f6ff00d) | Sep 09, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [4a63a68d47](https://linux-hardware.org/?probe=4a63a68d47) | Sep 09, 2023 |
| Microsoft     | Surface Laptop 2            | Tablet      | [e74f5bd967](https://linux-hardware.org/?probe=e74f5bd967) | Sep 09, 2023 |
| HP            | 2B36                        | Desktop     | [20552523c6](https://linux-hardware.org/?probe=20552523c6) | Sep 08, 2023 |
| HP            | 2B36                        | Desktop     | [7697b6ff27](https://linux-hardware.org/?probe=7697b6ff27) | Sep 08, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [86ea72cfeb](https://linux-hardware.org/?probe=86ea72cfeb) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [0de4c341fa](https://linux-hardware.org/?probe=0de4c341fa) | Sep 07, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| HP            | 2B3C                        | Desktop     | [471f0f283b](https://linux-hardware.org/?probe=471f0f283b) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a28608cf93](https://linux-hardware.org/?probe=a28608cf93) | Sep 04, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [e446721809](https://linux-hardware.org/?probe=e446721809) | Sep 02, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [aab4c37d85](https://linux-hardware.org/?probe=aab4c37d85) | Sep 02, 2023 |
| HP            | Compaq 15                   | Notebook    | [2d0b51ccd5](https://linux-hardware.org/?probe=2d0b51ccd5) | Sep 01, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [25b3fed672](https://linux-hardware.org/?probe=25b3fed672) | Aug 31, 2023 |
| Lenovo        | ThinkPad X200 7458AL7       | Notebook    | [763d0f46f4](https://linux-hardware.org/?probe=763d0f46f4) | Aug 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [1c5a7bba51](https://linux-hardware.org/?probe=1c5a7bba51) | Aug 31, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [48fe841736](https://linux-hardware.org/?probe=48fe841736) | Aug 30, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3f2dec6262](https://linux-hardware.org/?probe=3f2dec6262) | Aug 30, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [176ad353fa](https://linux-hardware.org/?probe=176ad353fa) | Aug 29, 2023 |
| HP            | 8953                        | Desktop     | [7f0a271e35](https://linux-hardware.org/?probe=7f0a271e35) | Aug 29, 2023 |
| HP            | 82A2                        | Desktop     | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [fe9f235c26](https://linux-hardware.org/?probe=fe9f235c26) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [efc8be8369](https://linux-hardware.org/?probe=efc8be8369) | Aug 28, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d238cd036a](https://linux-hardware.org/?probe=d238cd036a) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [492a021411](https://linux-hardware.org/?probe=492a021411) | Aug 27, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [0f05e92358](https://linux-hardware.org/?probe=0f05e92358) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [248f2a9745](https://linux-hardware.org/?probe=248f2a9745) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [c1bea53459](https://linux-hardware.org/?probe=c1bea53459) | Aug 27, 2023 |
| ASUSTek       | M3N WS                      | Desktop     | [da41c8a755](https://linux-hardware.org/?probe=da41c8a755) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [14805d08fd](https://linux-hardware.org/?probe=14805d08fd) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f4af40c36f](https://linux-hardware.org/?probe=f4af40c36f) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [08efa3dcf3](https://linux-hardware.org/?probe=08efa3dcf3) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [131e36d487](https://linux-hardware.org/?probe=131e36d487) | Aug 22, 2023 |
| Gigabyte      | MZA2-CE0-00 02010201        | Server      | [853b026197](https://linux-hardware.org/?probe=853b026197) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [f280fd203e](https://linux-hardware.org/?probe=f280fd203e) | Aug 21, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7a5bd0f1a6](https://linux-hardware.org/?probe=7a5bd0f1a6) | Aug 19, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a75b18f36c](https://linux-hardware.org/?probe=a75b18f36c) | Aug 19, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [d3aac86eac](https://linux-hardware.org/?probe=d3aac86eac) | Aug 16, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [7032d8da96](https://linux-hardware.org/?probe=7032d8da96) | Aug 16, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [9f04bd8095](https://linux-hardware.org/?probe=9f04bd8095) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| ASRock        | EP2C602                     | Desktop     | [26c37b5dfa](https://linux-hardware.org/?probe=26c37b5dfa) | Aug 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9825a49641](https://linux-hardware.org/?probe=9825a49641) | Aug 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [25aaeea069](https://linux-hardware.org/?probe=25aaeea069) | Aug 15, 2023 |
| Alienware     | 0XJKKD A01                  | Desktop     | [1b0f880002](https://linux-hardware.org/?probe=1b0f880002) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| ASRock        | EP2C602                     | Desktop     | [c152c5a2f9](https://linux-hardware.org/?probe=c152c5a2f9) | Aug 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [fe5f1d5c1b](https://linux-hardware.org/?probe=fe5f1d5c1b) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bcda0258e5](https://linux-hardware.org/?probe=bcda0258e5) | Aug 12, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Intel         | D915GEV AAC63667-501        | Desktop     | [4d65f6d8fa](https://linux-hardware.org/?probe=4d65f6d8fa) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [92fda27219](https://linux-hardware.org/?probe=92fda27219) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [3bd085d1a5](https://linux-hardware.org/?probe=3bd085d1a5) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [eac08c7b54](https://linux-hardware.org/?probe=eac08c7b54) | Aug 09, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b97d54f6d8](https://linux-hardware.org/?probe=b97d54f6d8) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [11cf6b0c98](https://linux-hardware.org/?probe=11cf6b0c98) | Aug 09, 2023 |
| GPD           | P2 MAX                      | Notebook    | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [1e3f49e3a0](https://linux-hardware.org/?probe=1e3f49e3a0) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [2f32ca43ee](https://linux-hardware.org/?probe=2f32ca43ee) | Aug 09, 2023 |
| HP            | 894D                        | Desktop     | [e1c397df93](https://linux-hardware.org/?probe=e1c397df93) | Aug 09, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [62889fd683](https://linux-hardware.org/?probe=62889fd683) | Aug 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [cb5a99b4fb](https://linux-hardware.org/?probe=cb5a99b4fb) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6c24c9f7a9](https://linux-hardware.org/?probe=6c24c9f7a9) | Aug 05, 2023 |
| HP            | 87A4 10100                  | All in one  | [ac3d0deece](https://linux-hardware.org/?probe=ac3d0deece) | Aug 05, 2023 |
| HP            | 87A4 10100                  | All in one  | [1dac28eee7](https://linux-hardware.org/?probe=1dac28eee7) | Aug 05, 2023 |
| AZW           | GTR V02                     | Desktop     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Dell          | XPS 9320                    | Notebook    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| HP            | 87A4 10100                  | All in one  | [a62908af95](https://linux-hardware.org/?probe=a62908af95) | Aug 04, 2023 |
| HP            | 87A4 10100                  | All in one  | [eb7ae8bbb2](https://linux-hardware.org/?probe=eb7ae8bbb2) | Aug 04, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [0839bbc721](https://linux-hardware.org/?probe=0839bbc721) | Aug 03, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| HP            | 843E                        | Desktop     | [dbbfb83ae4](https://linux-hardware.org/?probe=dbbfb83ae4) | Aug 03, 2023 |
| HP            | 843E                        | Desktop     | [952db006c3](https://linux-hardware.org/?probe=952db006c3) | Aug 03, 2023 |
| Dell          | Latitude E6330              | Notebook    | [75d54a8988](https://linux-hardware.org/?probe=75d54a8988) | Aug 03, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [5bbbd1f3d4](https://linux-hardware.org/?probe=5bbbd1f3d4) | Aug 02, 2023 |
| Schenker      | XMG FOCUS (Mid 2021)        | Notebook    | [d7fa14789f](https://linux-hardware.org/?probe=d7fa14789f) | Aug 01, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3efa8549a5](https://linux-hardware.org/?probe=3efa8549a5) | Aug 01, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [b298625640](https://linux-hardware.org/?probe=b298625640) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [add6831dcd](https://linux-hardware.org/?probe=add6831dcd) | Jul 31, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [7cb3479a69](https://linux-hardware.org/?probe=7cb3479a69) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [5518dab193](https://linux-hardware.org/?probe=5518dab193) | Jul 29, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [aef96d4eb8](https://linux-hardware.org/?probe=aef96d4eb8) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| HP            | Elite Dragonfly             | Convertible | [a44424e066](https://linux-hardware.org/?probe=a44424e066) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [86d9ab8b73](https://linux-hardware.org/?probe=86d9ab8b73) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [6ea424234a](https://linux-hardware.org/?probe=6ea424234a) | Jul 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [9c8b9571d9](https://linux-hardware.org/?probe=9c8b9571d9) | Jul 27, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [03152e1c57](https://linux-hardware.org/?probe=03152e1c57) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [45e8471971](https://linux-hardware.org/?probe=45e8471971) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9fbb932f79](https://linux-hardware.org/?probe=9fbb932f79) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [a326770d26](https://linux-hardware.org/?probe=a326770d26) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [dc537ae22a](https://linux-hardware.org/?probe=dc537ae22a) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cff40caac1](https://linux-hardware.org/?probe=cff40caac1) | Jul 24, 2023 |
| Dell          | Latitude 7480               | Notebook    | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [988a5f870c](https://linux-hardware.org/?probe=988a5f870c) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | Notebook    | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a8f79a71f7](https://linux-hardware.org/?probe=a8f79a71f7) | Jul 20, 2023 |
| Acer          | Predator PH317-56           | Notebook    | [248af0e35c](https://linux-hardware.org/?probe=248af0e35c) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [b3d68108a2](https://linux-hardware.org/?probe=b3d68108a2) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [fbb58d4f7c](https://linux-hardware.org/?probe=fbb58d4f7c) | Jul 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [f62d1b0d14](https://linux-hardware.org/?probe=f62d1b0d14) | Jul 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [798ddca1c4](https://linux-hardware.org/?probe=798ddca1c4) | Jul 16, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [236c9f5565](https://linux-hardware.org/?probe=236c9f5565) | Jul 14, 2023 |
| HP            | Pavilion dm1                | Notebook    | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Dell          | 0WC7KF A00                  | All in one  | [71309341ec](https://linux-hardware.org/?probe=71309341ec) | Jul 13, 2023 |
| HP            | 83DD                        | Mini pc     | [38e991673e](https://linux-hardware.org/?probe=38e991673e) | Jul 12, 2023 |
| Dell          | XPS 12 9Q23                 | Notebook    | [5fb9db838e](https://linux-hardware.org/?probe=5fb9db838e) | Jul 12, 2023 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fdde43af89](https://linux-hardware.org/?probe=fdde43af89) | Jul 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [6d76fdbcd6](https://linux-hardware.org/?probe=6d76fdbcd6) | Jul 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [9fd763e236](https://linux-hardware.org/?probe=9fd763e236) | Jul 09, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [b44c0d94f4](https://linux-hardware.org/?probe=b44c0d94f4) | Jul 09, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [61da77f999](https://linux-hardware.org/?probe=61da77f999) | Jul 09, 2023 |
| Medion        | MS-7667                     | Desktop     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9b8d05afca](https://linux-hardware.org/?probe=9b8d05afca) | Jul 08, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e0e1896cc3](https://linux-hardware.org/?probe=e0e1896cc3) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [3908772779](https://linux-hardware.org/?probe=3908772779) | Jul 07, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [8da6cc6879](https://linux-hardware.org/?probe=8da6cc6879) | Jul 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Notebook    | [4ff583eb14](https://linux-hardware.org/?probe=4ff583eb14) | Jul 05, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [80ed1496a1](https://linux-hardware.org/?probe=80ed1496a1) | Jul 05, 2023 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [530d25db12](https://linux-hardware.org/?probe=530d25db12) | Jul 03, 2023 |
| TUXEDO        | InfinityBook 14 v2          | Notebook    | [9447ac0693](https://linux-hardware.org/?probe=9447ac0693) | Jul 02, 2023 |
| HP            | 8918                        | Desktop     | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d772da19a0](https://linux-hardware.org/?probe=d772da19a0) | Jun 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [566b883024](https://linux-hardware.org/?probe=566b883024) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3c1007547d](https://linux-hardware.org/?probe=3c1007547d) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1e33cadd37](https://linux-hardware.org/?probe=1e33cadd37) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ad91997e3e](https://linux-hardware.org/?probe=ad91997e3e) | Jun 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [7f5dfae0db](https://linux-hardware.org/?probe=7f5dfae0db) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| Unknown       | Unknown                     | Soc         | [baebeebbdb](https://linux-hardware.org/?probe=baebeebbdb) | Jun 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [a413031ef8](https://linux-hardware.org/?probe=a413031ef8) | Jun 25, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [66f2fbfdf4](https://linux-hardware.org/?probe=66f2fbfdf4) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire F5-571G              | Notebook    | [fb61026d60](https://linux-hardware.org/?probe=fb61026d60) | Jun 25, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [cb554fb8f8](https://linux-hardware.org/?probe=cb554fb8f8) | Jun 24, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [f8dee044e2](https://linux-hardware.org/?probe=f8dee044e2) | Jun 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [24db241d7a](https://linux-hardware.org/?probe=24db241d7a) | Jun 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [23ea485e5e](https://linux-hardware.org/?probe=23ea485e5e) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d607d3c598](https://linux-hardware.org/?probe=d607d3c598) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8518224d34](https://linux-hardware.org/?probe=8518224d34) | Jun 21, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [223c8d15d4](https://linux-hardware.org/?probe=223c8d15d4) | Jun 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [186a21a6f7](https://linux-hardware.org/?probe=186a21a6f7) | Jun 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f008d4c0db](https://linux-hardware.org/?probe=f008d4c0db) | Jun 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [953a81c579](https://linux-hardware.org/?probe=953a81c579) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | Notebook    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c45597704a](https://linux-hardware.org/?probe=c45597704a) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a312151081](https://linux-hardware.org/?probe=a312151081) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7d329c0bee](https://linux-hardware.org/?probe=7d329c0bee) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [acf5c5a440](https://linux-hardware.org/?probe=acf5c5a440) | Jun 14, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [467be092e4](https://linux-hardware.org/?probe=467be092e4) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8ea9d60a21](https://linux-hardware.org/?probe=8ea9d60a21) | Jun 12, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [794030a707](https://linux-hardware.org/?probe=794030a707) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | Notebook    | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [212ff65852](https://linux-hardware.org/?probe=212ff65852) | Jun 09, 2023 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | Notebook    | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5b7a78b32e](https://linux-hardware.org/?probe=5b7a78b32e) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [14f68da7a7](https://linux-hardware.org/?probe=14f68da7a7) | Jun 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [f077d744cb](https://linux-hardware.org/?probe=f077d744cb) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [4d24b9b7d5](https://linux-hardware.org/?probe=4d24b9b7d5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| HP            | 8918                        | Desktop     | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | Notebook    | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [e98b2555d7](https://linux-hardware.org/?probe=e98b2555d7) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| HP            | 2B36                        | Desktop     | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| GPD           | P2 MAX                      | Notebook    | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [2f3952dcfe](https://linux-hardware.org/?probe=2f3952dcfe) | May 27, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [246b95d20f](https://linux-hardware.org/?probe=246b95d20f) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Samsung       | 930QED                      | Convertible | [14f0193b6a](https://linux-hardware.org/?probe=14f0193b6a) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Intel         | S2600STB J17012-601         | Server      | [2fa80c021a](https://linux-hardware.org/?probe=2fa80c021a) | May 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [aa0bf32546](https://linux-hardware.org/?probe=aa0bf32546) | May 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [c956e9cbab](https://linux-hardware.org/?probe=c956e9cbab) | May 22, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| Dell          | Latitude E6530              | Notebook    | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [019a851aeb](https://linux-hardware.org/?probe=019a851aeb) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [5d4070956a](https://linux-hardware.org/?probe=5d4070956a) | May 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [f59c4fec2f](https://linux-hardware.org/?probe=f59c4fec2f) | May 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [b595a4a849](https://linux-hardware.org/?probe=b595a4a849) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [9f4a8a37c0](https://linux-hardware.org/?probe=9f4a8a37c0) | May 15, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| Dell          | Latitude 5520               | Notebook    | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [d71435c79a](https://linux-hardware.org/?probe=d71435c79a) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [62e7f77fdc](https://linux-hardware.org/?probe=62e7f77fdc) | May 12, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f6c8b6c33e](https://linux-hardware.org/?probe=f6c8b6c33e) | May 12, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [41d9417c57](https://linux-hardware.org/?probe=41d9417c57) | May 11, 2023 |
| Acer          | Aspire 5332                 | Notebook    | [e74870bf17](https://linux-hardware.org/?probe=e74870bf17) | May 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| HP            | Compaq 6910p                | Notebook    | [c17dc1abcf](https://linux-hardware.org/?probe=c17dc1abcf) | May 08, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [f0f22d5d3f](https://linux-hardware.org/?probe=f0f22d5d3f) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c95999b5ad](https://linux-hardware.org/?probe=c95999b5ad) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [670e910889](https://linux-hardware.org/?probe=670e910889) | May 08, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [7502ce9679](https://linux-hardware.org/?probe=7502ce9679) | May 08, 2023 |
| Medion        | MS-7797                     | Desktop     | [590e39bef4](https://linux-hardware.org/?probe=590e39bef4) | May 07, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6089dfdeab](https://linux-hardware.org/?probe=6089dfdeab) | May 07, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [df056ec6f1](https://linux-hardware.org/?probe=df056ec6f1) | May 07, 2023 |
| Medion        | MS-7797                     | Desktop     | [d7eb2caa26](https://linux-hardware.org/?probe=d7eb2caa26) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 212B                        | Desktop     | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [4b705b9dca](https://linux-hardware.org/?probe=4b705b9dca) | May 03, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [61873cde49](https://linux-hardware.org/?probe=61873cde49) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbd9496296](https://linux-hardware.org/?probe=bbd9496296) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [71ec2fc5ea](https://linux-hardware.org/?probe=71ec2fc5ea) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [6936dcf305](https://linux-hardware.org/?probe=6936dcf305) | May 03, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [7a44b651f4](https://linux-hardware.org/?probe=7a44b651f4) | May 03, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [7c5e0a3de1](https://linux-hardware.org/?probe=7c5e0a3de1) | May 02, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [a720d9d42e](https://linux-hardware.org/?probe=a720d9d42e) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f77b52547](https://linux-hardware.org/?probe=0f77b52547) | May 01, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [c8c9c1e591](https://linux-hardware.org/?probe=c8c9c1e591) | Apr 30, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [910d4a6ad8](https://linux-hardware.org/?probe=910d4a6ad8) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [00d8186404](https://linux-hardware.org/?probe=00d8186404) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [50e1b8e197](https://linux-hardware.org/?probe=50e1b8e197) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| Dell          | Latitude 5520               | Notebook    | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | Notebook    | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | Notebook    | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [7afd2012e8](https://linux-hardware.org/?probe=7afd2012e8) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [c7fdbbb95b](https://linux-hardware.org/?probe=c7fdbbb95b) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [363bb28966](https://linux-hardware.org/?probe=363bb28966) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| HP            | 8433 11                     | Desktop     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| AZW           | GTR V02                     | Desktop     | [104badc0d7](https://linux-hardware.org/?probe=104badc0d7) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [65c9942c32](https://linux-hardware.org/?probe=65c9942c32) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [607dbbf4d8](https://linux-hardware.org/?probe=607dbbf4d8) | Apr 21, 2023 |
| Gigabyte      | P55A-UD7                    | Desktop     | [59f8c4d262](https://linux-hardware.org/?probe=59f8c4d262) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [9bb50174ef](https://linux-hardware.org/?probe=9bb50174ef) | Apr 20, 2023 |
| Dell          | 0DPRKF A01                  | Server      | [51412400ba](https://linux-hardware.org/?probe=51412400ba) | Apr 20, 2023 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [f20338e169](https://linux-hardware.org/?probe=f20338e169) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2c6da4e91f](https://linux-hardware.org/?probe=2c6da4e91f) | Apr 20, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [472922fafd](https://linux-hardware.org/?probe=472922fafd) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [a1b9ea4fd9](https://linux-hardware.org/?probe=a1b9ea4fd9) | Apr 20, 2023 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [4e31c5af6b](https://linux-hardware.org/?probe=4e31c5af6b) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [27a629fd15](https://linux-hardware.org/?probe=27a629fd15) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f3a680d9bc](https://linux-hardware.org/?probe=f3a680d9bc) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [96d5a26185](https://linux-hardware.org/?probe=96d5a26185) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [b6306c2e97](https://linux-hardware.org/?probe=b6306c2e97) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [fbedbcb213](https://linux-hardware.org/?probe=fbedbcb213) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [6e77ac0ec9](https://linux-hardware.org/?probe=6e77ac0ec9) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c1b2a75484](https://linux-hardware.org/?probe=c1b2a75484) | Apr 20, 2023 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [756eccb961](https://linux-hardware.org/?probe=756eccb961) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ef04208d0f](https://linux-hardware.org/?probe=ef04208d0f) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c419c9200f](https://linux-hardware.org/?probe=c419c9200f) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [1be8dc273c](https://linux-hardware.org/?probe=1be8dc273c) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [d765a92052](https://linux-hardware.org/?probe=d765a92052) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [244222ae5c](https://linux-hardware.org/?probe=244222ae5c) | Apr 20, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [f77fe53c69](https://linux-hardware.org/?probe=f77fe53c69) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7d49aa5207](https://linux-hardware.org/?probe=7d49aa5207) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [d53ce13aa3](https://linux-hardware.org/?probe=d53ce13aa3) | Apr 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ec13e17577](https://linux-hardware.org/?probe=ec13e17577) | Apr 20, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9fde2b21fc](https://linux-hardware.org/?probe=9fde2b21fc) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [ddc7ba8ccb](https://linux-hardware.org/?probe=ddc7ba8ccb) | Apr 20, 2023 |
| Fujitsu       | D3348-A2 S26361-D3348-A2    | Desktop     | [3dbd4f731c](https://linux-hardware.org/?probe=3dbd4f731c) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d46e9b11d5](https://linux-hardware.org/?probe=d46e9b11d5) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [afbf28c15a](https://linux-hardware.org/?probe=afbf28c15a) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [f185782be2](https://linux-hardware.org/?probe=f185782be2) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [731671f1b8](https://linux-hardware.org/?probe=731671f1b8) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [463c62da83](https://linux-hardware.org/?probe=463c62da83) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [0356125777](https://linux-hardware.org/?probe=0356125777) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [0a45e9e9af](https://linux-hardware.org/?probe=0a45e9e9af) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ccf2e2bbc3](https://linux-hardware.org/?probe=ccf2e2bbc3) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3171099090](https://linux-hardware.org/?probe=3171099090) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [032f3a72c6](https://linux-hardware.org/?probe=032f3a72c6) | Apr 20, 2023 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [df7041b726](https://linux-hardware.org/?probe=df7041b726) | Apr 20, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [04e9cd2455](https://linux-hardware.org/?probe=04e9cd2455) | Apr 20, 2023 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [0dd9e12f5a](https://linux-hardware.org/?probe=0dd9e12f5a) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [ad6a3cc4d0](https://linux-hardware.org/?probe=ad6a3cc4d0) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [9e668ff813](https://linux-hardware.org/?probe=9e668ff813) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [5dc0cb1f28](https://linux-hardware.org/?probe=5dc0cb1f28) | Apr 20, 2023 |
| Medion        | GA-Z170X-Gaming 7           | Desktop     | [706cfb4c50](https://linux-hardware.org/?probe=706cfb4c50) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [b3b27e0fcf](https://linux-hardware.org/?probe=b3b27e0fcf) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [bdbd8d06e2](https://linux-hardware.org/?probe=bdbd8d06e2) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [ff10999142](https://linux-hardware.org/?probe=ff10999142) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [11da8c5d96](https://linux-hardware.org/?probe=11da8c5d96) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [128d16cf7f](https://linux-hardware.org/?probe=128d16cf7f) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c2de2809a0](https://linux-hardware.org/?probe=c2de2809a0) | Apr 20, 2023 |
| Intel         | S2600WFT H48104-860         | Server      | [f5848d1ba2](https://linux-hardware.org/?probe=f5848d1ba2) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c3a3c03c3f](https://linux-hardware.org/?probe=c3a3c03c3f) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [1ae9258a0d](https://linux-hardware.org/?probe=1ae9258a0d) | Apr 20, 2023 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [5fba63c085](https://linux-hardware.org/?probe=5fba63c085) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [ab89260502](https://linux-hardware.org/?probe=ab89260502) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3f99aeec69](https://linux-hardware.org/?probe=3f99aeec69) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [50f654b2a0](https://linux-hardware.org/?probe=50f654b2a0) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [9949a0748f](https://linux-hardware.org/?probe=9949a0748f) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [e3cfbf7435](https://linux-hardware.org/?probe=e3cfbf7435) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9817f90648](https://linux-hardware.org/?probe=9817f90648) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [cf4854d704](https://linux-hardware.org/?probe=cf4854d704) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [296676f929](https://linux-hardware.org/?probe=296676f929) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [2eeebec1ec](https://linux-hardware.org/?probe=2eeebec1ec) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [68ac671aab](https://linux-hardware.org/?probe=68ac671aab) | Apr 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a069d32b86](https://linux-hardware.org/?probe=a069d32b86) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [1b1a3da7b2](https://linux-hardware.org/?probe=1b1a3da7b2) | Apr 20, 2023 |
| Gigabyte      | MZ12-HD3-00 01010101        | Server      | [def4067c8e](https://linux-hardware.org/?probe=def4067c8e) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [2a1fcefe29](https://linux-hardware.org/?probe=2a1fcefe29) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5c54edc96d](https://linux-hardware.org/?probe=5c54edc96d) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [563e45a22a](https://linux-hardware.org/?probe=563e45a22a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0000720fb6](https://linux-hardware.org/?probe=0000720fb6) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fdda3d6276](https://linux-hardware.org/?probe=fdda3d6276) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ee95d83f31](https://linux-hardware.org/?probe=ee95d83f31) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1e49dc0f67](https://linux-hardware.org/?probe=1e49dc0f67) | Apr 20, 2023 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [3e6b182473](https://linux-hardware.org/?probe=3e6b182473) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | Desktop     | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [c4c1d8086c](https://linux-hardware.org/?probe=c4c1d8086c) | Apr 20, 2023 |
| ASRock        | B560M-HDV                   | Desktop     | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [882d6f625d](https://linux-hardware.org/?probe=882d6f625d) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f16bcad94](https://linux-hardware.org/?probe=8f16bcad94) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [848607e7f1](https://linux-hardware.org/?probe=848607e7f1) | Apr 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [b076a9a807](https://linux-hardware.org/?probe=b076a9a807) | Apr 18, 2023 |
| Dell          | 0D4VY1 A00                  | All in one  | [ddbd926522](https://linux-hardware.org/?probe=ddbd926522) | Apr 18, 2023 |
| Dell          | 0R4CNN A02                  | Server      | [237a3cd682](https://linux-hardware.org/?probe=237a3cd682) | Apr 18, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [79225bdfaf](https://linux-hardware.org/?probe=79225bdfaf) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [4d802fb610](https://linux-hardware.org/?probe=4d802fb610) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2b749e898e](https://linux-hardware.org/?probe=2b749e898e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [702377976d](https://linux-hardware.org/?probe=702377976d) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [32f7392dce](https://linux-hardware.org/?probe=32f7392dce) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b7f40b0d8e](https://linux-hardware.org/?probe=b7f40b0d8e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9602690aa2](https://linux-hardware.org/?probe=9602690aa2) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbf0a5108a](https://linux-hardware.org/?probe=bbf0a5108a) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [000ec3362e](https://linux-hardware.org/?probe=000ec3362e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [7d67899067](https://linux-hardware.org/?probe=7d67899067) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [256a2110b0](https://linux-hardware.org/?probe=256a2110b0) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9f69cc7127](https://linux-hardware.org/?probe=9f69cc7127) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [997c25143e](https://linux-hardware.org/?probe=997c25143e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [71822fdac9](https://linux-hardware.org/?probe=71822fdac9) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b3f9111b79](https://linux-hardware.org/?probe=b3f9111b79) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [df314b2a9c](https://linux-hardware.org/?probe=df314b2a9c) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [dc155ce308](https://linux-hardware.org/?probe=dc155ce308) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [aaff05d28f](https://linux-hardware.org/?probe=aaff05d28f) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | Notebook    | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [fc6c4adaa4](https://linux-hardware.org/?probe=fc6c4adaa4) | Apr 17, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [8dd4721bd1](https://linux-hardware.org/?probe=8dd4721bd1) | Apr 16, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [a0f5ba360c](https://linux-hardware.org/?probe=a0f5ba360c) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9c885fa5cf](https://linux-hardware.org/?probe=9c885fa5cf) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Dell          | Latitude 7530               | Notebook    | [133059c3d6](https://linux-hardware.org/?probe=133059c3d6) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [8fb4ed64eb](https://linux-hardware.org/?probe=8fb4ed64eb) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5943787304](https://linux-hardware.org/?probe=5943787304) | Apr 16, 2023 |
| ASUSTek       | X756UJ                      | Notebook    | [a374f8dd26](https://linux-hardware.org/?probe=a374f8dd26) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [a0247e45a6](https://linux-hardware.org/?probe=a0247e45a6) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [f205e700dc](https://linux-hardware.org/?probe=f205e700dc) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [817e4bb939](https://linux-hardware.org/?probe=817e4bb939) | Apr 13, 2023 |
| HP            | 8433 11                     | Desktop     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ec028424ea](https://linux-hardware.org/?probe=ec028424ea) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ccdf29023](https://linux-hardware.org/?probe=9ccdf29023) | Apr 08, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [a62766f42e](https://linux-hardware.org/?probe=a62766f42e) | Apr 08, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [6a8c52faa7](https://linux-hardware.org/?probe=6a8c52faa7) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [32f5d43e96](https://linux-hardware.org/?probe=32f5d43e96) | Apr 04, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| Sony          | VPCF22C5E                   | Notebook    | [9d122b8bdd](https://linux-hardware.org/?probe=9d122b8bdd) | Apr 03, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [36d245f86b](https://linux-hardware.org/?probe=36d245f86b) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6f3e488e2b](https://linux-hardware.org/?probe=6f3e488e2b) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [17fb0ed43a](https://linux-hardware.org/?probe=17fb0ed43a) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| HP            | Unknown                     | Notebook    | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [3494b0fdd9](https://linux-hardware.org/?probe=3494b0fdd9) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [c885b5da6c](https://linux-hardware.org/?probe=c885b5da6c) | Mar 30, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [452a3fa4a8](https://linux-hardware.org/?probe=452a3fa4a8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [e1d01990f4](https://linux-hardware.org/?probe=e1d01990f4) | Mar 27, 2023 |
| HP            | 844C                        | Desktop     | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [405ce5a9c8](https://linux-hardware.org/?probe=405ce5a9c8) | Mar 27, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [35e0a73e8f](https://linux-hardware.org/?probe=35e0a73e8f) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [03df3679d3](https://linux-hardware.org/?probe=03df3679d3) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [f7d3c52f58](https://linux-hardware.org/?probe=f7d3c52f58) | Mar 26, 2023 |
| Acer          | Predator G9-791             | Notebook    | [1f820516a3](https://linux-hardware.org/?probe=1f820516a3) | Mar 26, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | Notebook    | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [728f83932f](https://linux-hardware.org/?probe=728f83932f) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5a94081c24](https://linux-hardware.org/?probe=5a94081c24) | Mar 24, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [704fb36197](https://linux-hardware.org/?probe=704fb36197) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [74be0519cc](https://linux-hardware.org/?probe=74be0519cc) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [5074a23172](https://linux-hardware.org/?probe=5074a23172) | Mar 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9ba3333988](https://linux-hardware.org/?probe=9ba3333988) | Mar 20, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [0fb09c29cb](https://linux-hardware.org/?probe=0fb09c29cb) | Mar 20, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [6c83c2a089](https://linux-hardware.org/?probe=6c83c2a089) | Mar 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3c00ca015f](https://linux-hardware.org/?probe=3c00ca015f) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [d7acdc8bf3](https://linux-hardware.org/?probe=d7acdc8bf3) | Mar 18, 2023 |
| Google        | Lillipup                    | Notebook    | [3eca64113c](https://linux-hardware.org/?probe=3eca64113c) | Mar 18, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [4e6f4d1197](https://linux-hardware.org/?probe=4e6f4d1197) | Mar 17, 2023 |
| HP            | 2B36                        | Desktop     | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [bfdb73f825](https://linux-hardware.org/?probe=bfdb73f825) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [be76f3a0a3](https://linux-hardware.org/?probe=be76f3a0a3) | Mar 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [839899a14d](https://linux-hardware.org/?probe=839899a14d) | Mar 15, 2023 |
| ASUSTek       | UX32A                       | Notebook    | [05121bc6af](https://linux-hardware.org/?probe=05121bc6af) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f4926b859a](https://linux-hardware.org/?probe=f4926b859a) | Mar 15, 2023 |
| Dell          | Latitude E6440              | Notebook    | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Notebook      | NS50MU                      | Notebook    | [f5e64711f3](https://linux-hardware.org/?probe=f5e64711f3) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [31ac227c9f](https://linux-hardware.org/?probe=31ac227c9f) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [36bcd11bd3](https://linux-hardware.org/?probe=36bcd11bd3) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [aca12aa4c5](https://linux-hardware.org/?probe=aca12aa4c5) | Mar 13, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | Notebook    | [aa5eb19101](https://linux-hardware.org/?probe=aa5eb19101) | Mar 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [433c3d165a](https://linux-hardware.org/?probe=433c3d165a) | Mar 13, 2023 |
| HP            | 212B                        | Desktop     | [8d5ef71d93](https://linux-hardware.org/?probe=8d5ef71d93) | Mar 13, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [43c96b4e3e](https://linux-hardware.org/?probe=43c96b4e3e) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [99095e84f5](https://linux-hardware.org/?probe=99095e84f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [55fe24706a](https://linux-hardware.org/?probe=55fe24706a) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6c90dd73e7](https://linux-hardware.org/?probe=6c90dd73e7) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [c792b83b69](https://linux-hardware.org/?probe=c792b83b69) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | Notebook    | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d7535fd29e](https://linux-hardware.org/?probe=d7535fd29e) | Mar 10, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [0e1279e96d](https://linux-hardware.org/?probe=0e1279e96d) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5b8db1d628](https://linux-hardware.org/?probe=5b8db1d628) | Mar 10, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [b9e49da1f7](https://linux-hardware.org/?probe=b9e49da1f7) | Mar 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9946c1c6dc](https://linux-hardware.org/?probe=9946c1c6dc) | Mar 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3c5ca39c55](https://linux-hardware.org/?probe=3c5ca39c55) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [e280beba92](https://linux-hardware.org/?probe=e280beba92) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d52a175b61](https://linux-hardware.org/?probe=d52a175b61) | Mar 07, 2023 |
| AZW           | GTR V02                     | Desktop     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [971feb34e4](https://linux-hardware.org/?probe=971feb34e4) | Mar 07, 2023 |
| Fujitsu       | CELSIUS H780                | Notebook    | [7080d07525](https://linux-hardware.org/?probe=7080d07525) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [fd6cb5c68a](https://linux-hardware.org/?probe=fd6cb5c68a) | Mar 07, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [359903fe58](https://linux-hardware.org/?probe=359903fe58) | Mar 07, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [5656c3015d](https://linux-hardware.org/?probe=5656c3015d) | Mar 06, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| Lenovo        | ThinkPad E590 20NB000YMZ    | Notebook    | [fb05511be8](https://linux-hardware.org/?probe=fb05511be8) | Mar 05, 2023 |
| HP            | Compaq 15                   | Notebook    | [5c8a185273](https://linux-hardware.org/?probe=5c8a185273) | Mar 05, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e57a377381](https://linux-hardware.org/?probe=e57a377381) | Mar 05, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e45794963a](https://linux-hardware.org/?probe=e45794963a) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a987f40464](https://linux-hardware.org/?probe=a987f40464) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cd1e0a746](https://linux-hardware.org/?probe=6cd1e0a746) | Mar 04, 2023 |
| Timi          | TM1701                      | Notebook    | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [02df2ea534](https://linux-hardware.org/?probe=02df2ea534) | Mar 03, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [cacb713046](https://linux-hardware.org/?probe=cacb713046) | Mar 02, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [86ec7ef027](https://linux-hardware.org/?probe=86ec7ef027) | Mar 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [117d283b7a](https://linux-hardware.org/?probe=117d283b7a) | Mar 02, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [0780656106](https://linux-hardware.org/?probe=0780656106) | Mar 01, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fc8fee94a](https://linux-hardware.org/?probe=8fc8fee94a) | Feb 27, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [3f0d63ab15](https://linux-hardware.org/?probe=3f0d63ab15) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [0855d319b4](https://linux-hardware.org/?probe=0855d319b4) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cd4a13ce32](https://linux-hardware.org/?probe=cd4a13ce32) | Feb 25, 2023 |
| Dell          | Latitude 5580               | Notebook    | [79da5a8efd](https://linux-hardware.org/?probe=79da5a8efd) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [2b9ed74f9d](https://linux-hardware.org/?probe=2b9ed74f9d) | Feb 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [af87e6ea4c](https://linux-hardware.org/?probe=af87e6ea4c) | Feb 25, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9c0775a106](https://linux-hardware.org/?probe=9c0775a106) | Feb 25, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | Notebook    | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| Intel         | NUC7i3DNB J57625-510        | Mini pc     | [aedbb176f7](https://linux-hardware.org/?probe=aedbb176f7) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [576314ab03](https://linux-hardware.org/?probe=576314ab03) | Feb 20, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [f8dfa838b7](https://linux-hardware.org/?probe=f8dfa838b7) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [d773500fcb](https://linux-hardware.org/?probe=d773500fcb) | Feb 18, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [c8bc9e01fd](https://linux-hardware.org/?probe=c8bc9e01fd) | Feb 17, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b39c940cfd](https://linux-hardware.org/?probe=b39c940cfd) | Feb 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [92a61cd4ee](https://linux-hardware.org/?probe=92a61cd4ee) | Feb 16, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [ef74f90ec1](https://linux-hardware.org/?probe=ef74f90ec1) | Feb 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [e927a19203](https://linux-hardware.org/?probe=e927a19203) | Feb 16, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [826959e69e](https://linux-hardware.org/?probe=826959e69e) | Feb 13, 2023 |
| Samsung       | 930QED                      | Convertible | [9e03711ee7](https://linux-hardware.org/?probe=9e03711ee7) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [91657d5c1d](https://linux-hardware.org/?probe=91657d5c1d) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [db7a713397](https://linux-hardware.org/?probe=db7a713397) | Feb 12, 2023 |
| Lenovo        | ThinkPad P73 20QR002PMZ     | Notebook    | [458447fa93](https://linux-hardware.org/?probe=458447fa93) | Feb 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d2e867259](https://linux-hardware.org/?probe=2d2e867259) | Feb 10, 2023 |
| HP            | 8653 A                      | Desktop     | [5854a10eb0](https://linux-hardware.org/?probe=5854a10eb0) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [40c7c2e40b](https://linux-hardware.org/?probe=40c7c2e40b) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ddd47ed4b7](https://linux-hardware.org/?probe=ddd47ed4b7) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6d9840bb7c](https://linux-hardware.org/?probe=6d9840bb7c) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| HP            | ProBook 4720s               | Notebook    | [96ec8d979e](https://linux-hardware.org/?probe=96ec8d979e) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e7fd395c49](https://linux-hardware.org/?probe=e7fd395c49) | Feb 05, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [384a4f7da2](https://linux-hardware.org/?probe=384a4f7da2) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [9e7d0b79cf](https://linux-hardware.org/?probe=9e7d0b79cf) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | Notebook    | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5dbc22fda8](https://linux-hardware.org/?probe=5dbc22fda8) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7b6c27948](https://linux-hardware.org/?probe=e7b6c27948) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4626133ef2](https://linux-hardware.org/?probe=4626133ef2) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b08ab3c55c](https://linux-hardware.org/?probe=b08ab3c55c) | Feb 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [9968b839f2](https://linux-hardware.org/?probe=9968b839f2) | Feb 03, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a66e882be4](https://linux-hardware.org/?probe=a66e882be4) | Feb 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0ca0b99aa3](https://linux-hardware.org/?probe=0ca0b99aa3) | Feb 03, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b83c8fb5a1](https://linux-hardware.org/?probe=b83c8fb5a1) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [e04cbf47d6](https://linux-hardware.org/?probe=e04cbf47d6) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [163afb997a](https://linux-hardware.org/?probe=163afb997a) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | Notebook    | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bf7bab9d7c](https://linux-hardware.org/?probe=bf7bab9d7c) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [e05b7e7729](https://linux-hardware.org/?probe=e05b7e7729) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | Notebook    | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Medion        | MS-7728                     | Desktop     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| Acer          | Veriton M2110G              | Desktop     | [7097a3cf90](https://linux-hardware.org/?probe=7097a3cf90) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [80f8925010](https://linux-hardware.org/?probe=80f8925010) | Jan 17, 2023 |
| Acer          | Aspire M5910                | Desktop     | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | 212B                        | Desktop     | [00822b2263](https://linux-hardware.org/?probe=00822b2263) | Jan 16, 2023 |
| Medion        | MS-7728                     | Desktop     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| ELSKY         | QM10u                       | Desktop     | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [d014e736fc](https://linux-hardware.org/?probe=d014e736fc) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a7b0b9f2e](https://linux-hardware.org/?probe=9a7b0b9f2e) | Jan 10, 2023 |
| Medion        | MS-7728                     | Desktop     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| HP            | 3048h                       | Desktop     | [e13a2bdf6e](https://linux-hardware.org/?probe=e13a2bdf6e) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | Notebook    | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [97335b8723](https://linux-hardware.org/?probe=97335b8723) | Jan 07, 2023 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ac69fa3d31](https://linux-hardware.org/?probe=ac69fa3d31) | Jan 07, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [03524fa074](https://linux-hardware.org/?probe=03524fa074) | Jan 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [7281c172f4](https://linux-hardware.org/?probe=7281c172f4) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [8e49c8c0b1](https://linux-hardware.org/?probe=8e49c8c0b1) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [ca8adec17c](https://linux-hardware.org/?probe=ca8adec17c) | Jan 06, 2023 |
| Medion        | MS-7728                     | Desktop     | [4b3e96394b](https://linux-hardware.org/?probe=4b3e96394b) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | Notebook    | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| Acer          | Predator G9-591             | Notebook    | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0b9972387e](https://linux-hardware.org/?probe=0b9972387e) | Jan 05, 2023 |
| Medion        | MS-7728                     | Desktop     | [0ffef4911e](https://linux-hardware.org/?probe=0ffef4911e) | Jan 05, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| Medion        | MS-7728                     | Desktop     | [9c2439adf6](https://linux-hardware.org/?probe=9c2439adf6) | Jan 04, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [518b2272d4](https://linux-hardware.org/?probe=518b2272d4) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [b341980e6c](https://linux-hardware.org/?probe=b341980e6c) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d50cf83414](https://linux-hardware.org/?probe=d50cf83414) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | Notebook    | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [cc24dc6f72](https://linux-hardware.org/?probe=cc24dc6f72) | Dec 31, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [bf3922e95d](https://linux-hardware.org/?probe=bf3922e95d) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | Notebook    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [77ee14ad98](https://linux-hardware.org/?probe=77ee14ad98) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [1c022f7ff8](https://linux-hardware.org/?probe=1c022f7ff8) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b445490856](https://linux-hardware.org/?probe=b445490856) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [907ca44afe](https://linux-hardware.org/?probe=907ca44afe) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [47397487a7](https://linux-hardware.org/?probe=47397487a7) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e954c9ca37](https://linux-hardware.org/?probe=e954c9ca37) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| ASUSTek       | PN64                        | Mini pc     | [a5fdbdb0c8](https://linux-hardware.org/?probe=a5fdbdb0c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | Notebook    | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [9ed715edc4](https://linux-hardware.org/?probe=9ed715edc4) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3282a529f0](https://linux-hardware.org/?probe=3282a529f0) | Dec 11, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [6c26c9ff8c](https://linux-hardware.org/?probe=6c26c9ff8c) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [62986b3426](https://linux-hardware.org/?probe=62986b3426) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [439e89b31f](https://linux-hardware.org/?probe=439e89b31f) | Dec 07, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [f2ba8a7d55](https://linux-hardware.org/?probe=f2ba8a7d55) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [927991f54f](https://linux-hardware.org/?probe=927991f54f) | Dec 06, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [ee9c9e919b](https://linux-hardware.org/?probe=ee9c9e919b) | Dec 05, 2022 |
| HP            | ENVY dv7                    | Notebook    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [9a0718a60f](https://linux-hardware.org/?probe=9a0718a60f) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | Notebook    | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | Notebook    | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | Notebook    | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [13b2f864f8](https://linux-hardware.org/?probe=13b2f864f8) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | Notebook    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | Notebook    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [8d98938198](https://linux-hardware.org/?probe=8d98938198) | Nov 30, 2022 |
| Dell          | 0Y2G81 A01                  | Server      | [7ce42afb90](https://linux-hardware.org/?probe=7ce42afb90) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d233ee2114](https://linux-hardware.org/?probe=d233ee2114) | Nov 30, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [8d37e3e327](https://linux-hardware.org/?probe=8d37e3e327) | Nov 29, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [e41751f26a](https://linux-hardware.org/?probe=e41751f26a) | Nov 29, 2022 |
| Notebook      | L140PU                      | Notebook    | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Pegatron      | VIOLET                      | Desktop     | [f0f25e6854](https://linux-hardware.org/?probe=f0f25e6854) | Nov 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [3ba26453f1](https://linux-hardware.org/?probe=3ba26453f1) | Nov 24, 2022 |
| Nvidia        | Tegra                       | Soc         | [b565b4082e](https://linux-hardware.org/?probe=b565b4082e) | Nov 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [90f931841d](https://linux-hardware.org/?probe=90f931841d) | Nov 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [111f6a1fc2](https://linux-hardware.org/?probe=111f6a1fc2) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | Notebook    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b5ed1b189a](https://linux-hardware.org/?probe=b5ed1b189a) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [54f10b9d0b](https://linux-hardware.org/?probe=54f10b9d0b) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [576ca67a28](https://linux-hardware.org/?probe=576ca67a28) | Nov 21, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b25dd25478](https://linux-hardware.org/?probe=b25dd25478) | Nov 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| HP            | 212B                        | Desktop     | [574a94ad86](https://linux-hardware.org/?probe=574a94ad86) | Nov 18, 2022 |
| HP            | 212B                        | Desktop     | [3995268826](https://linux-hardware.org/?probe=3995268826) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | Notebook    | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | Notebook    | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | Notebook    | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | Notebook    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c6c7120833](https://linux-hardware.org/?probe=c6c7120833) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [2053688baa](https://linux-hardware.org/?probe=2053688baa) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [15f6c6a1aa](https://linux-hardware.org/?probe=15f6c6a1aa) | Nov 14, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [3726e23d23](https://linux-hardware.org/?probe=3726e23d23) | Nov 14, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [f320cc2659](https://linux-hardware.org/?probe=f320cc2659) | Nov 11, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [d2e25c9c4e](https://linux-hardware.org/?probe=d2e25c9c4e) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [33a4a1ea9a](https://linux-hardware.org/?probe=33a4a1ea9a) | Nov 09, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [ff7014b9b8](https://linux-hardware.org/?probe=ff7014b9b8) | Nov 06, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| HP            | 8458                        | Mini pc     | [4da864256d](https://linux-hardware.org/?probe=4da864256d) | Nov 03, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fd4d484f61](https://linux-hardware.org/?probe=fd4d484f61) | Nov 02, 2022 |
| Dell          | Precision 5520              | Notebook    | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | Notebook    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1e1f105579](https://linux-hardware.org/?probe=1e1f105579) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [19cddcf899](https://linux-hardware.org/?probe=19cddcf899) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | Notebook    | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 308       | 12%     |
| Ubuntu 18.04                 | 271       | 10.56%  |
| Ubuntu 22.04                 | 239       | 9.31%   |
| Debian 11                    | 95        | 3.7%    |
| Linux Mint 20.3              | 57        | 2.22%   |
| OpenMandriva 4.3             | 43        | 1.68%   |
| Debian 10                    | 41        | 1.6%    |
| Arch Rolling                 | 41        | 1.6%    |
| Ubuntu 21.10                 | 38        | 1.48%   |
| openSUSE Tumbleweed-XXXXXXXX | 38        | 1.48%   |
| Linux Mint 20.2              | 36        | 1.4%    |
| Linux Mint 20.1              | 36        | 1.4%    |
| KDE neon 20.04               | 36        | 1.4%    |
| Zorin 16                     | 35        | 1.36%   |
| Pop!_OS 22.04                | 34        | 1.33%   |
| OpenMandriva 4.2             | 31        | 1.21%   |
| Linux Mint 21.1              | 30        | 1.17%   |
| Fedora 38                    | 28        | 1.09%   |
| Arch                         | 28        | 1.09%   |
| Manjaro                      | 27        | 1.05%   |
| Ubuntu 20.10                 | 25        | 0.97%   |
| OpenMandriva 23.01           | 24        | 0.94%   |
| Fedora 32                    | 24        | 0.94%   |
| Ubuntu 22.10                 | 23        | 0.9%    |
| Fedora 37                    | 23        | 0.9%    |
| Ubuntu 21.04                 | 22        | 0.86%   |
| Fedora 34                    | 22        | 0.86%   |
| Ubuntu 23.04                 | 21        | 0.82%   |
| Ubuntu 19.10                 | 21        | 0.82%   |
| Pop!_OS 21.04                | 21        | 0.82%   |
| Pop!_OS 20.10                | 21        | 0.82%   |
| Pop!_OS 20.04                | 21        | 0.82%   |
| Fedora 33                    | 21        | 0.82%   |
| ArcoLinux Rolling            | 21        | 0.82%   |
| Ubuntu 19.04                 | 20        | 0.78%   |
| Fedora 35                    | 20        | 0.78%   |
| Linux Mint 19.3              | 19        | 0.74%   |
| Debian 12                    | 18        | 0.7%    |
| Linux Mint 21                | 17        | 0.66%   |
| OpenMandriva 23.03           | 16        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 904       | 38.47%  |
| Linux Mint    | 210       | 8.94%   |
| Debian        | 178       | 7.57%   |
| Fedora        | 157       | 6.68%   |
| OpenMandriva  | 132       | 5.62%   |
| Pop!_OS       | 96        | 4.09%   |
| Manjaro       | 73        | 3.11%   |
| Arch          | 68        | 2.89%   |
| openSUSE      | 52        | 2.21%   |
| Kubuntu       | 52        | 2.21%   |
| Zorin         | 50        | 2.13%   |
| KDE neon      | 43        | 1.83%   |
| Xubuntu       | 26        | 1.11%   |
| ROSA          | 26        | 1.11%   |
| ArcoLinux     | 24        | 1.02%   |
| Gentoo        | 20        | 0.85%   |
| Ubuntu MATE   | 18        | 0.77%   |
| Kali          | 18        | 0.77%   |
| Elementary    | 17        | 0.72%   |
| Lubuntu       | 15        | 0.64%   |
| EndeavourOS   | 12        | 0.51%   |
| CentOS        | 12        | 0.51%   |
| Ubuntu Budgie | 10        | 0.43%   |
| Feren OS      | 10        | 0.43%   |
| Clear Linux   | 9         | 0.38%   |
| Ubuntu Unity  | 7         | 0.3%    |
| MX            | 7         | 0.3%    |
| LMDE          | 7         | 0.3%    |
| Endless       | 7         | 0.3%    |
| BlackPanther  | 7         | 0.3%    |
| SteamOS       | 5         | 0.21%   |
| RHEL          | 5         | 0.21%   |
| NixOS         | 5         | 0.21%   |
| Artix         | 5         | 0.21%   |
| Void Linux    | 4         | 0.17%   |
| TUXEDO OS     | 4         | 0.17%   |
| Parrot        | 4         | 0.17%   |
| Garuda Linux  | 4         | 0.17%   |
| Xero          | 3         | 0.13%   |
| Virtuozzo     | 3         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.15.0-88-generic        | 44        | 1.53%   |
| 5.16.7-desktop-1omv4003  | 38        | 1.32%   |
| 5.15.0-67-generic        | 35        | 1.22%   |
| 5.15.0-58-generic        | 33        | 1.15%   |
| 5.4.0-42-generic         | 32        | 1.11%   |
| 5.15.0-56-generic        | 31        | 1.08%   |
| 5.15.0-69-generic        | 30        | 1.04%   |
| 5.10.14-desktop-1omv4002 | 30        | 1.04%   |
| 4.15.0-91-generic        | 27        | 0.94%   |
| 5.15.0-46-generic        | 25        | 0.87%   |
| 5.4.0-52-generic         | 22        | 0.77%   |
| 5.4.0-48-generic         | 22        | 0.77%   |
| 5.19.0-35-generic        | 22        | 0.77%   |
| 4.15.0-96-generic        | 22        | 0.77%   |
| 5.4.0-58-generic         | 21        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 20        | 0.7%    |
| 5.10.0-8-arm64           | 17        | 0.59%   |
| 6.2.6-desktop-1omv2390   | 16        | 0.56%   |
| 5.8.0-43-generic         | 15        | 0.52%   |
| 5.4.0-91-generic         | 15        | 0.52%   |
| 5.15.0-60-generic        | 15        | 0.52%   |
| 5.10.0-21-amd64          | 15        | 0.52%   |
| 5.13.0-35-generic        | 14        | 0.49%   |
| 5.4.0-80-generic         | 13        | 0.45%   |
| 5.4.0-26-generic         | 13        | 0.45%   |
| 5.15.0-52-generic        | 13        | 0.45%   |
| 5.11.0-43-generic        | 13        | 0.45%   |
| 5.11.0-27-generic        | 13        | 0.45%   |
| 5.4.0-81-generic         | 12        | 0.42%   |
| 5.4.0-47-generic         | 12        | 0.42%   |
| 5.15.0-48-generic        | 12        | 0.42%   |
| 5.15.0-43-generic        | 12        | 0.42%   |
| 5.13.0-39-generic        | 12        | 0.42%   |
| 5.13.0-30-generic        | 12        | 0.42%   |
| 5.10.0-8-amd64           | 12        | 0.42%   |
| 5.0.0-37-generic         | 12        | 0.42%   |
| 5.8.0-55-generic         | 11        | 0.38%   |
| 5.8.0-53-generic         | 11        | 0.38%   |
| 5.8.0-48-generic         | 11        | 0.38%   |
| 5.8.0-44-generic         | 11        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 381       | 14.23%  |
| 5.15.0  | 322       | 12.02%  |
| 4.15.0  | 207       | 7.73%   |
| 5.8.0   | 128       | 4.78%   |
| 5.11.0  | 117       | 4.37%   |
| 5.13.0  | 107       | 4%      |
| 5.10.0  | 98        | 3.66%   |
| 5.19.0  | 84        | 3.14%   |
| 5.3.0   | 72        | 2.69%   |
| 6.2.0   | 57        | 2.13%   |
| 5.0.0   | 50        | 1.87%   |
| 4.18.0  | 42        | 1.57%   |
| 5.16.7  | 39        | 1.46%   |
| 4.19.0  | 38        | 1.42%   |
| 5.10.14 | 31        | 1.16%   |
| 6.1.0   | 30        | 1.12%   |
| 6.1.1   | 24        | 0.9%    |
| 6.2.6   | 22        | 0.82%   |
| 5.14.0  | 16        | 0.6%    |
| 5.17.5  | 13        | 0.49%   |
| 6.0.0   | 12        | 0.45%   |
| 5.6.0   | 11        | 0.41%   |
| 6.5.0   | 10        | 0.37%   |
| 6.4.11  | 9         | 0.34%   |
| 5.7.0   | 9         | 0.34%   |
| 5.18.0  | 9         | 0.34%   |
| 5.16.13 | 8         | 0.3%    |
| 3.10.0  | 8         | 0.3%    |
| 6.0.12  | 7         | 0.26%   |
| 5.10.7  | 7         | 0.26%   |
| 4.9.60  | 7         | 0.26%   |
| 6.5.5   | 6         | 0.22%   |
| 6.3.5   | 6         | 0.22%   |
| 6.0.7   | 6         | 0.22%   |
| 6.0.15  | 6         | 0.22%   |
| 5.6.14  | 6         | 0.22%   |
| 5.3.18  | 6         | 0.22%   |
| 5.16.0  | 6         | 0.22%   |
| 5.14.21 | 6         | 0.22%   |
| 4.18.16 | 6         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 400       | 15.2%   |
| 5.15    | 376       | 14.29%  |
| 4.15    | 208       | 7.91%   |
| 5.10    | 169       | 6.42%   |
| 5.8     | 161       | 6.12%   |
| 5.11    | 146       | 5.55%   |
| 5.13    | 124       | 4.71%   |
| 6.2     | 102       | 3.88%   |
| 5.19    | 97        | 3.69%   |
| 6.1     | 87        | 3.31%   |
| 5.3     | 85        | 3.23%   |
| 5.16    | 75        | 2.85%   |
| 5.0     | 55        | 2.09%   |
| 6.0     | 50        | 1.9%    |
| 4.18    | 50        | 1.9%    |
| 4.19    | 45        | 1.71%   |
| 5.6     | 41        | 1.56%   |
| 5.14    | 41        | 1.56%   |
| 5.17    | 38        | 1.44%   |
| 6.5     | 34        | 1.29%   |
| 6.4     | 30        | 1.14%   |
| 5.9     | 29        | 1.1%    |
| 5.7     | 29        | 1.1%    |
| 5.18    | 28        | 1.06%   |
| 6.3     | 26        | 0.99%   |
| 5.12    | 25        | 0.95%   |
| 4.9     | 23        | 0.87%   |
| 5.5     | 11        | 0.42%   |
| 3.10    | 8         | 0.3%    |
| 4.4     | 5         | 0.19%   |
| 4.14    | 4         | 0.15%   |
| 5.2     | 3         | 0.11%   |
| 4.20    | 3         | 0.11%   |
| 4.13    | 3         | 0.11%   |
| 4.1     | 3         | 0.11%   |
| 2.6     | 3         | 0.11%   |
| 6.6     | 2         | 0.08%   |
| 4.10    | 2         | 0.08%   |
| 3.16    | 2         | 0.08%   |
| 5.1     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2193      | 96.69%  |
| aarch64 | 40        | 1.76%   |
| i686    | 33        | 1.46%   |
| armv8l  | 1         | 0.04%   |
| armv7l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 957       | 40.38%  |
| KDE5            | 359       | 15.15%  |
| Unknown         | 321       | 13.54%  |
| X-Cinnamon      | 169       | 7.13%   |
| GNUstep         | 153       | 6.46%   |
| XFCE            | 117       | 4.94%   |
| MATE            | 61        | 2.57%   |
| KDE             | 43        | 1.81%   |
| Cinnamon        | 35        | 1.48%   |
| LXQt            | 23        | 0.97%   |
| i3              | 19        | 0.8%    |
| Pantheon        | 18        | 0.76%   |
| KDE4            | 17        | 0.72%   |
| LXDE            | 16        | 0.68%   |
| GNOME Flashback | 15        | 0.63%   |
| Budgie          | 15        | 0.63%   |
| Unity           | 6         | 0.25%   |
| bspwm           | 5         | 0.21%   |
| qtile           | 4         | 0.17%   |
| Trinity         | 2         | 0.08%   |
| sway            | 2         | 0.08%   |
| Hyprland        | 2         | 0.08%   |
| GNOME Classic   | 2         | 0.08%   |
| DWM             | 2         | 0.08%   |
| xmonad          | 1         | 0.04%   |
| openbox         | 1         | 0.04%   |
| none+awesome    | 1         | 0.04%   |
| ICEWM           | 1         | 0.04%   |
| herbstluftwm    | 1         | 0.04%   |
| fluxbox         | 1         | 0.04%   |
| awesome         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1613      | 67.12%  |
| Wayland | 441       | 18.35%  |
| Unknown | 180       | 7.49%   |
| Tty     | 166       | 6.91%   |
| Web     | 3         | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 977       | 40.98%  |
| LightDM | 415       | 17.41%  |
| SDDM    | 315       | 13.21%  |
| GDM     | 289       | 12.12%  |
| GDM3    | 282       | 11.83%  |
| TDM     | 80        | 3.36%   |
| KDM     | 15        | 0.63%   |
| XDM     | 4         | 0.17%   |
| SLiM    | 4         | 0.17%   |
| NODM    | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 850       | 35.65%  |
| de_CH      | 535       | 22.44%  |
| Unknown    | 355       | 14.89%  |
| fr_CH      | 163       | 6.84%   |
| de_DE      | 158       | 6.63%   |
| en_GB      | 101       | 4.24%   |
| fr_FR      | 51        | 2.14%   |
| C          | 48        | 2.01%   |
| it_IT      | 19        | 0.8%    |
| it_CH      | 19        | 0.8%    |
| pt_PT      | 17        | 0.71%   |
| pl_PL      | 9         | 0.38%   |
| es_ES      | 9         | 0.38%   |
| ru_RU      | 7         | 0.29%   |
| en_CH      | 7         | 0.29%   |
| en_AU      | 5         | 0.21%   |
| de_AT      | 4         | 0.17%   |
| POSIX      | 3         | 0.13%   |
| en_IE      | 3         | 0.13%   |
| en_CA      | 2         | 0.08%   |
| en_AG      | 2         | 0.08%   |
| de_IT      | 2         | 0.08%   |
| tr_TR      | 1         | 0.04%   |
| sk_SK      | 1         | 0.04%   |
| ru_UA      | 1         | 0.04%   |
| pt_BR      | 1         | 0.04%   |
| nl_BE      | 1         | 0.04%   |
| hu_HU      | 1         | 0.04%   |
| hsb_DE     | 1         | 0.04%   |
| gsw_CH     | 1         | 0.04%   |
| fr_CA      | 1         | 0.04%   |
| fi_FI      | 1         | 0.04%   |
| de_LI      | 1         | 0.04%   |
| de_CH.UTF8 | 1         | 0.04%   |
| cs_CZ      | 1         | 0.04%   |
| ca_ES      | 1         | 0.04%   |
| C.UTF8     | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1307      | 56.29%  |
| BIOS | 1015      | 43.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1795      | 76.87%  |
| Btrfs   | 214       | 9.16%   |
| Overlay | 144       | 6.17%   |
| Unknown | 65        | 2.78%   |
| Tmpfs   | 43        | 1.84%   |
| Xfs     | 42        | 1.8%    |
| Zfs     | 14        | 0.6%    |
| Ext2    | 6         | 0.26%   |
| Ext3    | 5         | 0.21%   |
| F2fs    | 4         | 0.17%   |
| Jfs     | 1         | 0.04%   |
| ExX4    | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1108      | 47.59%  |
| Unknown | 974       | 41.84%  |
| MBR     | 246       | 10.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1971      | 84.92%  |
| Yes       | 350       | 15.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1736      | 75.12%  |
| Yes       | 575       | 24.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 427       | 18.84%  |
| Hewlett-Packard         | 378       | 16.68%  |
| Lenovo                  | 372       | 16.42%  |
| Dell                    | 183       | 8.08%   |
| Acer                    | 127       | 5.6%    |
| Gigabyte Technology     | 99        | 4.37%   |
| Apple                   | 91        | 4.02%   |
| MSI                     | 76        | 3.35%   |
| Intel                   | 69        | 3.05%   |
| ASRock                  | 68        | 3%      |
| Fujitsu                 | 42        | 1.85%   |
| Raspberry Pi Foundation | 34        | 1.5%    |
| Medion                  | 30        | 1.32%   |
| Supermicro              | 19        | 0.84%   |
| Microsoft               | 18        | 0.79%   |
| Toshiba                 | 17        | 0.75%   |
| Sony                    | 15        | 0.66%   |
| TUXEDO                  | 14        | 0.62%   |
| Notebook                | 13        | 0.57%   |
| Samsung Electronics     | 12        | 0.53%   |
| Unknown                 | 12        | 0.53%   |
| Shuttle                 | 9         | 0.4%    |
| HUAWEI                  | 9         | 0.4%    |
| ZOTAC                   | 8         | 0.35%   |
| TrekStor                | 7         | 0.31%   |
| Pegatron                | 7         | 0.31%   |
| PC Engines              | 7         | 0.31%   |
| Razer                   | 6         | 0.26%   |
| DALCO AG Switzerland    | 6         | 0.26%   |
| Alienware               | 6         | 0.26%   |
| Schenker                | 5         | 0.22%   |
| Packard Bell            | 5         | 0.22%   |
| Valve                   | 4         | 0.18%   |
| Biostar                 | 4         | 0.18%   |
| Timi                    | 3         | 0.13%   |
| System76                | 3         | 0.13%   |
| PC Specialist           | 3         | 0.13%   |
| GPD                     | 3         | 0.13%   |
| Fujitsu Siemens         | 3         | 0.13%   |
| Clevo                   | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 36        | 1.59%   |
| Unknown                                    | 20        | 0.88%   |
| ASUS PRIME Z590-P                          | 17        | 0.75%   |
| Fujitsu CELSIUS_W550                       | 12        | 0.53%   |
| ASUS PRIME X570-PRO                        | 12        | 0.53%   |
| ASUS ROG STRIX X570-E GAMING               | 11        | 0.49%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 10        | 0.44%   |
| ASUS PRIME B550M-A                         | 10        | 0.44%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 9         | 0.4%    |
| RPi Raspberry Pi 3 Model B Rev 1.2         | 8         | 0.35%   |
| MSI MS-7C02                                | 8         | 0.35%   |
| HP Pavilion dv7                            | 8         | 0.35%   |
| ASUS STRIX Z270F GAMING                    | 8         | 0.35%   |
| Dell Latitude 7490                         | 7         | 0.31%   |
| ASUS P9X79 WS                              | 7         | 0.31%   |
| ASUS P8Z77-V LX                            | 7         | 0.31%   |
| Microsoft Surface Pro 4                    | 6         | 0.26%   |
| DALCO AG Switzerland +41 44 908 38 38      | 6         | 0.26%   |
| Apple iMac12,2                             | 6         | 0.26%   |
| PC Engines APU2                            | 5         | 0.22%   |
| Intel S4600LH                              | 5         | 0.22%   |
| Intel DP67BA AAG10219-303                  | 5         | 0.22%   |
| HP Pavilion dv6                            | 5         | 0.22%   |
| HP Notebook                                | 5         | 0.22%   |
| HP ENVY 15                                 | 5         | 0.22%   |
| HP EliteDesk 800 G1 SFF                    | 5         | 0.22%   |
| Fujitsu CELSIUS W570                       | 5         | 0.22%   |
| Dell XPS 15 9570                           | 5         | 0.22%   |
| Dell OptiPlex 9020                         | 5         | 0.22%   |
| Dell OptiPlex 790                          | 5         | 0.22%   |
| Dell OptiPlex 7010                         | 5         | 0.22%   |
| Dell Latitude E7240                        | 5         | 0.22%   |
| ASUS ROG STRIX Z370-F GAMING               | 5         | 0.22%   |
| Apple MacBookPro9,2                        | 5         | 0.22%   |
| Apple MacBookPro8,1                        | 5         | 0.22%   |
| Apple iMac8,1                              | 5         | 0.22%   |
| Apple iMac13,1                             | 5         | 0.22%   |
| Valve Jupiter                              | 4         | 0.18%   |
| Supermicro X8DTN+-F                        | 4         | 0.18%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 233       | 10.28%  |
| ASUS ROG           | 79        | 3.49%   |
| ASUS PRIME         | 77        | 3.4%    |
| Acer Aspire        | 75        | 3.31%   |
| HP EliteBook       | 70        | 3.09%   |
| HP Pavilion        | 58        | 2.56%   |
| Dell XPS           | 55        | 2.43%   |
| Dell Latitude      | 54        | 2.38%   |
| HP ProBook         | 39        | 1.72%   |
| Lenovo Yoga        | 38        | 1.68%   |
| HP ENVY            | 36        | 1.59%   |
| ASUS All           | 36        | 1.59%   |
| RPi Raspberry      | 34        | 1.5%    |
| Dell OptiPlex      | 33        | 1.46%   |
| Fujitsu CELSIUS    | 28        | 1.24%   |
| HP Compaq          | 26        | 1.15%   |
| HP EliteDesk       | 23        | 1.02%   |
| Lenovo IdeaPad     | 22        | 0.97%   |
| ASUS TUF           | 22        | 0.97%   |
| ASUS VivoBook      | 20        | 0.88%   |
| Unknown            | 20        | 0.88%   |
| HP Laptop          | 19        | 0.84%   |
| Microsoft Surface  | 18        | 0.79%   |
| HP ZBook           | 15        | 0.66%   |
| Dell Inspiron      | 15        | 0.66%   |
| Acer Swift         | 15        | 0.66%   |
| Dell Precision     | 13        | 0.57%   |
| Lenovo IdeaPadFlex | 12        | 0.53%   |
| Toshiba Satellite  | 11        | 0.49%   |
| Lenovo ThinkCentre | 11        | 0.49%   |
| ASUS ZenBook       | 11        | 0.49%   |
| ASUS STRIX         | 10        | 0.44%   |
| Lenovo Legion      | 9         | 0.4%    |
| HP Spectre         | 9         | 0.4%    |
| HP ProLiant        | 9         | 0.4%    |
| HP ProDesk         | 9         | 0.4%    |
| HP OMEN            | 9         | 0.4%    |
| Gigabyte X570      | 9         | 0.4%    |
| ASUS P9X79         | 9         | 0.4%    |
| Apple iMac12       | 9         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 226       | 9.97%   |
| 2019    | 222       | 9.8%    |
| 2020    | 216       | 9.53%   |
| 2017    | 176       | 7.77%   |
| 2012    | 166       | 7.33%   |
| 2021    | 159       | 7.02%   |
| 2011    | 146       | 6.44%   |
| 2013    | 137       | 6.05%   |
| 2014    | 133       | 5.87%   |
| 2015    | 129       | 5.69%   |
| 2016    | 113       | 4.99%   |
| 2010    | 99        | 4.37%   |
| 2022    | 97        | 4.28%   |
| 2008    | 64        | 2.82%   |
| 2009    | 58        | 2.56%   |
| 2007    | 36        | 1.59%   |
| 2023    | 33        | 1.46%   |
| Unknown | 29        | 1.28%   |
| 2006    | 17        | 0.75%   |
| 2005    | 6         | 0.26%   |
| 2004    | 3         | 0.13%   |
| 2003    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1034      | 45.63%  |
| Desktop        | 867       | 38.26%  |
| Convertible    | 126       | 5.56%   |
| Mini pc        | 54        | 2.38%   |
| All in one     | 53        | 2.34%   |
| Server         | 51        | 2.25%   |
| System on chip | 39        | 1.72%   |
| Tablet         | 39        | 1.72%   |
| Phone          | 3         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2075      | 90.73%  |
| Enabled  | 212       | 9.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2250      | 99.29%  |
| Yes  | 16        | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 571       | 24.7%   |
| 32.01-64.0      | 382       | 16.52%  |
| 4.01-8.0        | 376       | 16.26%  |
| 8.01-16.0       | 364       | 15.74%  |
| 3.01-4.0        | 273       | 11.81%  |
| 64.01-256.0     | 162       | 7.01%   |
| 24.01-32.0      | 61        | 2.64%   |
| 1.01-2.0        | 57        | 2.47%   |
| More than 256.0 | 27        | 1.17%   |
| 0.51-1.0        | 22        | 0.95%   |
| 2.01-3.0        | 16        | 0.69%   |
| 0.01-0.5        | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 788       | 30.52%  |
| 2.01-3.0        | 577       | 22.35%  |
| 4.01-8.0        | 440       | 17.04%  |
| 3.01-4.0        | 312       | 12.08%  |
| 0.51-1.0        | 180       | 6.97%   |
| 8.01-16.0       | 173       | 6.7%    |
| 0.01-0.5        | 45        | 1.74%   |
| 16.01-24.0      | 32        | 1.24%   |
| 24.01-32.0      | 11        | 0.43%   |
| 32.01-64.0      | 10        | 0.39%   |
| 64.01-256.0     | 8         | 0.31%   |
| Unknown         | 4         | 0.15%   |
| More than 256.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1405      | 59.74%  |
| 2       | 555       | 23.6%   |
| 3       | 201       | 8.55%   |
| 4       | 77        | 3.27%   |
| 5       | 47        | 2%      |
| 6       | 22        | 0.94%   |
| 0       | 22        | 0.94%   |
| 7       | 17        | 0.72%   |
| 14      | 2         | 0.09%   |
| 11      | 1         | 0.04%   |
| 9       | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1511      | 65.92%  |
| Yes       | 781       | 34.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1941      | 85.02%  |
| No        | 342       | 14.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1633      | 71.69%  |
| No        | 645       | 28.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1371      | 59.74%  |
| No        | 924       | 40.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 2266      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 646       | 26.1%   |
| Bern                               | 115       | 4.65%   |
| Geneva                             | 91        | 3.68%   |
| Lucerne                            | 66        | 2.67%   |
| Lausanne                           | 45        | 1.82%   |
| Basel                              | 41        | 1.66%   |
| Winterthur                         | 36        | 1.45%   |
| Wiesendangen / Wiesendangen (Dorf) | 33        | 1.33%   |
| Neuchatel                          | 28        | 1.13%   |
| Thun                               | 26        | 1.05%   |
| Lugano                             | 21        | 0.85%   |
| Dietikon                           | 20        | 0.81%   |
| Lyss                               | 19        | 0.77%   |
| St. Gallen                         | 18        | 0.73%   |
| Wil                                | 17        | 0.69%   |
| Herrliberg                         | 15        | 0.61%   |
| Biel/Bienne                        | 13        | 0.53%   |
| Aarau                              | 13        | 0.53%   |
| Wettingen                          | 12        | 0.48%   |
| Sion                               | 12        | 0.48%   |
| Munchenstein                       | 12        | 0.48%   |
| Ittigen                            | 11        | 0.44%   |
| Dubendorf                          | 11        | 0.44%   |
| Onex                               | 10        | 0.4%    |
| Willisau                           | 9         | 0.36%   |
| Uster                              | 9         | 0.36%   |
| Solothurn                          | 9         | 0.36%   |
| Schaffhausen                       | 9         | 0.36%   |
| Oberwil-Lieli                      | 9         | 0.36%   |
| Kloten                             | 9         | 0.36%   |
| Glattbrugg                         | 9         | 0.36%   |
| Bulle                              | 9         | 0.36%   |
| Baden                              | 9         | 0.36%   |
| Aarburg                            | 9         | 0.36%   |
| Zollikofen                         | 8         | 0.32%   |
| Widnau                             | 8         | 0.32%   |
| Wetzikon                           | 8         | 0.32%   |
| Wallisellen                        | 8         | 0.32%   |
| St. Moritz                         | 8         | 0.32%   |
| Prilly                             | 8         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 850       | 1523   | 26.23%  |
| WDC                         | 447       | 729    | 13.8%   |
| Seagate                     | 372       | 541    | 11.48%  |
| Sandisk                     | 175       | 220    | 5.4%    |
| Toshiba                     | 158       | 220    | 4.88%   |
| Unknown                     | 146       | 221    | 4.51%   |
| Intel                       | 143       | 207    | 4.41%   |
| SK hynix                    | 106       | 129    | 3.27%   |
| Hitachi                     | 103       | 141    | 3.18%   |
| Kingston                    | 98        | 141    | 3.02%   |
| Crucial                     | 91        | 129    | 2.81%   |
| Micron Technology           | 60        | 76     | 1.85%   |
| Apple                       | 47        | 53     | 1.45%   |
| HGST                        | 37        | 47     | 1.14%   |
| Corsair                     | 27        | 32     | 0.83%   |
| OCZ                         | 25        | 30     | 0.77%   |
| A-DATA Technology           | 24        | 36     | 0.74%   |
| Intenso                     | 21        | 22     | 0.65%   |
| Phison                      | 19        | 30     | 0.59%   |
| LITEON                      | 19        | 25     | 0.59%   |
| Phison Electronics          | 16        | 27     | 0.49%   |
| KIOXIA                      | 15        | 23     | 0.46%   |
| LITEONIT                    | 14        | 16     | 0.43%   |
| China                       | 14        | 16     | 0.43%   |
| Transcend                   | 13        | 23     | 0.4%    |
| ASMT                        | 10        | 15     | 0.31%   |
| Hewlett-Packard             | 9         | 11     | 0.28%   |
| SPCC                        | 8         | 9      | 0.25%   |
| Silicon Motion              | 8         | 9      | 0.25%   |
| KingSpec                    | 8         | 13     | 0.25%   |
| Unknown                     | 8         | 9      | 0.25%   |
| Plextor                     | 7         | 8      | 0.22%   |
| Kingston Technology Company | 7         | 7      | 0.22%   |
| JMicron Technology          | 7         | 7      | 0.22%   |
| Fujitsu                     | 7         | 10     | 0.22%   |
| Patriot                     | 6         | 7      | 0.19%   |
| Micron/Crucial Technology   | 6         | 9      | 0.19%   |
| LaCie                       | 6         | 6      | 0.19%   |
| Maxtor                      | 5         | 7      | 0.15%   |
| HPE                         | 5         | 12     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                          | 43        | 1.18%   |
| Samsung SSD 850 EVO 250GB                          | 39        | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 36        | 0.99%   |
| Samsung SSD 860 EVO 1TB                            | 35        | 0.96%   |
| Samsung NVMe SSD Drive 1TB                         | 34        | 0.93%   |
| Samsung SSD 860 EVO 500GB                          | 30        | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 29        | 0.8%    |
| Samsung SSD 980 PRO 1TB                            | 27        | 0.74%   |
| Samsung SSD 860 EVO 250GB                          | 27        | 0.74%   |
| Samsung SSD 970 EVO Plus 1TB                       | 26        | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB                     | 25        | 0.69%   |
| Samsung NVMe SSD Drive 512GB                       | 24        | 0.66%   |
| Unknown MMC Card  32GB                             | 21        | 0.58%   |
| Samsung SSD 840 EVO 250GB                          | 21        | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB                     | 19        | 0.52%   |
| Samsung NVMe SSD Drive 500GB                       | 18        | 0.49%   |
| Unknown MMC Card  64GB                             | 17        | 0.47%   |
| Unknown MMC Card  128GB                            | 17        | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                     | 16        | 0.44%   |
| Samsung SSD 860 QVO 1TB                            | 16        | 0.44%   |
| Samsung SSD 850 EVO 1TB                            | 16        | 0.44%   |
| Seagate Expansion 1TB                              | 15        | 0.41%   |
| SanDisk NVMe SSD Drive 1TB                         | 15        | 0.41%   |
| HGST HTS721010A9E630 1TB                           | 15        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                       | 14        | 0.38%   |
| Samsung NVMe SSD Drive 1024GB                      | 14        | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                     | 13        | 0.36%   |
| SK hynix NVMe SSD Drive 512GB                      | 13        | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                     | 13        | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB                     | 13        | 0.36%   |
| Samsung SSD 850 PRO 256GB                          | 13        | 0.36%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 13        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB                        | 13        | 0.36%   |
| Toshiba DT01ACA100 1TB                             | 12        | 0.33%   |
| Samsung SSD 970 EVO 1TB                            | 12        | 0.33%   |
| Samsung SSD 870 EVO 500GB                          | 12        | 0.33%   |
| Samsung SSD 840 PRO Series 256GB                   | 12        | 0.33%   |
| Unknown SD/MMC/MS PRO 16GB                         | 11        | 0.3%    |
| Samsung SSD 970 EVO Plus 2TB                       | 11        | 0.3%    |
| Samsung SSD 850 PRO 512GB                          | 11        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 361       | 519    | 35.32%  |
| WDC                 | 337       | 565    | 32.97%  |
| Hitachi             | 103       | 141    | 10.08%  |
| Toshiba             | 83        | 108    | 8.12%   |
| Samsung Electronics | 41        | 62     | 4.01%   |
| HGST                | 37        | 47     | 3.62%   |
| Unknown             | 12        | 13     | 1.17%   |
| Apple               | 12        | 12     | 1.17%   |
| Fujitsu             | 7         | 10     | 0.68%   |
| Maxtor              | 5         | 7      | 0.49%   |
| Intenso             | 4         | 4      | 0.39%   |
| ASMT                | 3         | 4      | 0.29%   |
| Initio              | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 4      | 0.2%    |
| External            | 2         | 2      | 0.2%    |
| USB3.0              | 1         | 2      | 0.1%    |
| USB                 | 1         | 2      | 0.1%    |
| Unknown (CF)        | 1         | 1      | 0.1%    |
| MARVELL             | 1         | 1      | 0.1%    |
| IET                 | 1         | 1      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| HPE                 | 1         | 6      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 2      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 456       | 783    | 39.58%  |
| SanDisk             | 99        | 123    | 8.59%   |
| Crucial             | 82        | 119    | 7.12%   |
| Kingston            | 71        | 107    | 6.16%   |
| Intel               | 67        | 86     | 5.82%   |
| WDC                 | 64        | 84     | 5.56%   |
| Micron Technology   | 31        | 42     | 2.69%   |
| Toshiba             | 27        | 40     | 2.34%   |
| Apple               | 27        | 29     | 2.34%   |
| OCZ                 | 25        | 30     | 2.17%   |
| SK hynix            | 19        | 23     | 1.65%   |
| LITEON              | 18        | 24     | 1.56%   |
| Intenso             | 15        | 16     | 1.3%    |
| A-DATA Technology   | 15        | 24     | 1.3%    |
| LITEONIT            | 14        | 16     | 1.22%   |
| China               | 14        | 16     | 1.22%   |
| Corsair             | 13        | 14     | 1.13%   |
| Transcend           | 12        | 22     | 1.04%   |
| KingSpec            | 8         | 13     | 0.69%   |
| SPCC                | 7         | 8      | 0.61%   |
| Plextor             | 7         | 8      | 0.61%   |
| Patriot             | 6         | 7      | 0.52%   |
| ASMT                | 6         | 10     | 0.52%   |
| KIOXIA-EXCERIA      | 4         | 5      | 0.35%   |
| Seagate             | 3         | 3      | 0.26%   |
| HPE                 | 3         | 4      | 0.26%   |
| Hewlett-Packard     | 3         | 4      | 0.26%   |
| PNY                 | 2         | 3      | 0.17%   |
| OWC                 | 2         | 2      | 0.17%   |
| Mushkin             | 2         | 2      | 0.17%   |
| Dogfish             | 2         | 3      | 0.17%   |
| Adaptec             | 2         | 2      | 0.17%   |
| XSTAR               | 1         | 1      | 0.09%   |
| WDC WDS             | 1         | 1      | 0.09%   |
| WALRAM              | 1         | 1      | 0.09%   |
| VERICO              | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| SABRENT             | 1         | 1      | 0.09%   |
| S3+                 | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1011      | 1704   | 34.03%  |
| NVMe    | 919       | 1422   | 30.93%  |
| HDD     | 864       | 1519   | 29.08%  |
| MMC     | 142       | 212    | 4.78%   |
| Unknown | 35        | 53     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1483      | 3107   | 55.54%  |
| NVMe | 913       | 1414   | 34.19%  |
| MMC  | 142       | 212    | 5.32%   |
| SAS  | 132       | 177    | 4.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1004      | 1612   | 49.83%  |
| 0.51-1.0   | 569       | 911    | 28.24%  |
| 1.01-2.0   | 237       | 392    | 11.76%  |
| 3.01-4.0   | 85        | 138    | 4.22%   |
| 2.01-3.0   | 56        | 82     | 2.78%   |
| 4.01-10.0  | 45        | 60     | 2.23%   |
| 10.01-20.0 | 19        | 28     | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 557       | 22.79%  |
| 251-500        | 453       | 18.54%  |
| 501-1000       | 383       | 15.67%  |
| 1001-2000      | 261       | 10.68%  |
| More than 3000 | 181       | 7.41%   |
| 1-20           | 174       | 7.12%   |
| 2001-3000      | 118       | 4.83%   |
| 51-100         | 118       | 4.83%   |
| Unknown        | 118       | 4.83%   |
| 21-50          | 81        | 3.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 854       | 33.61%  |
| 21-50          | 328       | 12.91%  |
| 101-250        | 322       | 12.67%  |
| 51-100         | 279       | 10.98%  |
| 251-500        | 232       | 9.13%   |
| 501-1000       | 189       | 7.44%   |
| Unknown        | 118       | 4.64%   |
| 1001-2000      | 111       | 4.37%   |
| More than 3000 | 75        | 2.95%   |
| 2001-3000      | 33        | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB         | 2         | 2      | 1.29%   |
| WDC WD20EARS-00J99B0 2TB             | 2         | 2      | 1.29%   |
| WDC WD10EARS-00Y5B1 1TB              | 2         | 2      | 1.29%   |
| WDC WD10EADS-00L5B1 1TB              | 2         | 2      | 1.29%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 1.29%   |
| Seagate ST3250310AS 250GB            | 2         | 2      | 1.29%   |
| Seagate ST31500341AS 1TB             | 2         | 5      | 1.29%   |
| Samsung Electronics SSD 850 EVO 1TB  | 2         | 2      | 1.29%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 3      | 1.29%   |
| Initio 3639S 1TB                     | 2         | 2      | 1.29%   |
| Hitachi HUA722020ALA330 2TB          | 2         | 2      | 1.29%   |
| Hitachi HTS545050B9SA00 500GB        | 2         | 2      | 1.29%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 2      | 1.29%   |
| XSTAR SSD 128GB                      | 1         | 1      | 0.65%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 0.65%   |
| WDC WD5000AAKS-65A7B0 500GB          | 1         | 1      | 0.65%   |
| WDC WD5000AAKS-00TMA0 500GB          | 1         | 2      | 0.65%   |
| WDC WD5000AAKS-00E4A0 500GB          | 1         | 1      | 0.65%   |
| WDC WD40PURX-64GVNY0 4TB             | 1         | 1      | 0.65%   |
| WDC WD40EZRZ-00WN9B0 4TB             | 1         | 1      | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 2      | 0.65%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1         | 2      | 0.65%   |
| WDC WD3200AAKS-00B3A0 320GB          | 1         | 1      | 0.65%   |
| WDC WD3200AAJS-40VWA1 320GB          | 1         | 1      | 0.65%   |
| WDC WD30EZRX-00D8PB0 3TB             | 1         | 1      | 0.65%   |
| WDC WD2502ABYS-01B7A0 256GB          | 1         | 1      | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 1      | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 2      | 0.65%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 1      | 0.65%   |
| WDC WD20EARS-00J2GB0 2TB             | 1         | 1      | 0.65%   |
| WDC WD1600BEKT-60A25T1 160GB         | 1         | 1      | 0.65%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1      | 0.65%   |
| WDC WD10EADS-22M2B0 1TB              | 1         | 1      | 0.65%   |
| WDC WD10EADS-11M2B3 1TB              | 1         | 1      | 0.65%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1         | 1      | 0.65%   |
| WDC WD1001FALS-403AA0 1TB            | 1         | 1      | 0.65%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 1      | 0.65%   |
| Toshiba THNSN5256GPUK 256GB          | 1         | 1      | 0.65%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 0.65%   |
| Toshiba MQ01ABF050 500GB             | 1         | 2      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 35     | 19.61%  |
| Seagate             | 22        | 33     | 14.38%  |
| Samsung Electronics | 19        | 22     | 12.42%  |
| Hitachi             | 15        | 16     | 9.8%    |
| Toshiba             | 10        | 13     | 6.54%   |
| SK hynix            | 9         | 10     | 5.88%   |
| Intel               | 8         | 9      | 5.23%   |
| Kingston            | 6         | 7      | 3.92%   |
| SanDisk             | 5         | 6      | 3.27%   |
| Micron Technology   | 5         | 6      | 3.27%   |
| HGST                | 5         | 5      | 3.27%   |
| OCZ                 | 3         | 4      | 1.96%   |
| A-DATA Technology   | 3         | 5      | 1.96%   |
| Initio              | 2         | 2      | 1.31%   |
| Crucial             | 2         | 2      | 1.31%   |
| XSTAR               | 1         | 1      | 0.65%   |
| Patriot             | 1         | 2      | 0.65%   |
| Maxtor              | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| Intenso             | 1         | 1      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |
| China               | 1         | 1      | 0.65%   |
| ASMedia             | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 33     | 31.11%  |
| Seagate             | 22        | 33     | 24.44%  |
| Hitachi             | 15        | 16     | 16.67%  |
| Toshiba             | 9         | 12     | 10%     |
| Samsung Electronics | 5         | 6      | 5.56%   |
| HGST                | 5         | 5      | 5.56%   |
| Initio              | 2         | 2      | 2.22%   |
| Maxtor              | 1         | 1      | 1.11%   |
| Fujitsu             | 1         | 1      | 1.11%   |
| ASMedia             | 1         | 1      | 1.11%   |
| Apple               | 1         | 1      | 1.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 111    | 56.55%  |
| SSD  | 52        | 62     | 35.86%  |
| NVMe | 11        | 12     | 7.59%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750528AS 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1261      | 2611   | 50.83%  |
| Works    | 1082      | 2113   | 43.61%  |
| Malfunc  | 137       | 185    | 5.52%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1470      | 49.38%  |
| Samsung Electronics            | 452       | 15.18%  |
| AMD                            | 345       | 11.59%  |
| SanDisk                        | 126       | 4.23%   |
| SK hynix                       | 79        | 2.65%   |
| ASMedia Technology             | 65        | 2.18%   |
| Marvell Technology Group       | 60        | 2.02%   |
| Toshiba America Info Systems   | 53        | 1.78%   |
| Phison Electronics             | 48        | 1.61%   |
| Kingston Technology Company    | 36        | 1.21%   |
| JMicron Technology             | 35        | 1.18%   |
| Nvidia                         | 30        | 1.01%   |
| Micron Technology              | 30        | 1.01%   |
| LSI Logic / Symbios Logic      | 16        | 0.54%   |
| KIOXIA                         | 14        | 0.47%   |
| Silicon Motion                 | 13        | 0.44%   |
| Micron/Crucial Technology      | 13        | 0.44%   |
| Areca Technology               | 13        | 0.44%   |
| Seagate Technology             | 11        | 0.37%   |
| ADATA Technology               | 11        | 0.37%   |
| Hewlett-Packard                | 8         | 0.27%   |
| Broadcom / LSI                 | 8         | 0.27%   |
| Solid State Storage Technology | 6         | 0.2%    |
| Apple                          | 6         | 0.2%    |
| Union Memory (Shenzhen)        | 4         | 0.13%   |
| Realtek Semiconductor          | 4         | 0.13%   |
| Lite-On Technology             | 4         | 0.13%   |
| Lenovo                         | 4         | 0.13%   |
| Adaptec                        | 4         | 0.13%   |
| VIA Technologies               | 3         | 0.1%    |
| Silicon Image                  | 2         | 0.07%   |
| Transcend                      | 1         | 0.03%   |
| Tekram Technology              | 1         | 0.03%   |
| Shenzhen Longsys Electronics   | 1         | 0.03%   |
| Biwin Storage Technology       | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 234       | 6.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 228       | 6.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 112       | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 98        | 2.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 95        | 2.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 92        | 2.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 70        | 2.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 63        | 1.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 61        | 1.81%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 61        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 58        | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 56        | 1.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 56        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 53        | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 51        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 51        | 1.51%   |
| AMD 400 Series Chipset SATA Controller                                         | 45        | 1.34%   |
| Intel SATA Controller [RAID mode]                                              | 43        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 41        | 1.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 39        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 38        | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 36        | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 35        | 1.04%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 34        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 34        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 32        | 0.95%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 31        | 0.92%   |
| Intel SSD 660P Series                                                          | 31        | 0.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 29        | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 27        | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 25        | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 24        | 0.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 23        | 0.68%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 23        | 0.68%   |
| Phison E12 NVMe Controller                                                     | 23        | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 23        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 23        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 22        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1557      | 52.98%  |
| NVMe | 918       | 31.24%  |
| RAID | 220       | 7.49%   |
| IDE  | 216       | 7.35%   |
| SAS  | 27        | 0.92%   |
| SCSI | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1766      | 77.93%  |
| AMD          | 455       | 20.08%  |
| ARM          | 39        | 1.72%   |
| QUALCOMM     | 2         | 0.09%   |
| CentaurHauls | 2         | 0.09%   |
| Unknown      | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 48        | 2.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 45        | 1.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 43        | 1.9%    |
| ARM Processor                              | 38        | 1.68%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 23        | 1.01%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 23        | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 21        | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 21        | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 21        | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 21        | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 21        | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 20        | 0.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 19        | 0.84%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 17        | 0.75%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 17        | 0.75%   |
| AMD Ryzen 5 3600 6-Core Processor          | 17        | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 16        | 0.71%   |
| Intel 11th Gen Core i9-11900F @ 2.50GHz    | 16        | 0.71%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 15        | 0.66%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 15        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 15        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 15        | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 14        | 0.62%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 0.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 14        | 0.62%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 13        | 0.57%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 13        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 13        | 0.57%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 13        | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 12        | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 12        | 0.53%   |
| Intel 12th Gen Core i7-1260P               | 12        | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 11        | 0.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 11        | 0.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 11        | 0.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 11        | 0.49%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 10        | 0.44%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 10        | 0.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 10        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 712       | 31.41%  |
| Intel Core i5           | 435       | 19.19%  |
| Other                   | 233       | 10.28%  |
| AMD Ryzen 7             | 124       | 5.47%   |
| Intel Xeon              | 90        | 3.97%   |
| AMD Ryzen 5             | 90        | 3.97%   |
| Intel Core 2 Duo        | 72        | 3.18%   |
| AMD Ryzen 9             | 60        | 2.65%   |
| Intel Core i3           | 58        | 2.56%   |
| Intel Celeron           | 54        | 2.38%   |
| Intel Atom              | 33        | 1.46%   |
| Intel Pentium           | 29        | 1.28%   |
| AMD Ryzen 7 PRO         | 27        | 1.19%   |
| Intel Core i9           | 21        | 0.93%   |
| AMD FX                  | 20        | 0.88%   |
| AMD Ryzen Threadripper  | 16        | 0.71%   |
| Intel Core 2            | 15        | 0.66%   |
| Intel Pentium Dual-Core | 14        | 0.62%   |
| Intel Core 2 Quad       | 13        | 0.57%   |
| AMD Ryzen 3             | 10        | 0.44%   |
| AMD GX                  | 9         | 0.4%    |
| AMD A8                  | 9         | 0.4%    |
| AMD Quad-Core Opteron   | 8         | 0.35%   |
| AMD EPYC                | 8         | 0.35%   |
| Intel Xeon Gold         | 7         | 0.31%   |
| AMD E                   | 6         | 0.26%   |
| Intel Pentium 4         | 5         | 0.22%   |
| AMD Phenom II X4        | 5         | 0.22%   |
| AMD Opteron             | 5         | 0.22%   |
| AMD Athlon              | 5         | 0.22%   |
| Intel Pentium Silver    | 4         | 0.18%   |
| Intel Genuine           | 4         | 0.18%   |
| AMD Phenom II X6        | 4         | 0.18%   |
| AMD A10                 | 4         | 0.18%   |
| Intel Pentium M         | 3         | 0.13%   |
| Intel Core M            | 3         | 0.13%   |
| AMD Ryzen 5 PRO         | 3         | 0.13%   |
| AMD Phenom              | 3         | 0.13%   |
| AMD E2                  | 3         | 0.13%   |
| AMD E1                  | 3         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 937       | 41.3%   |
| 2       | 610       | 26.88%  |
| 8       | 267       | 11.77%  |
| 6       | 230       | 10.14%  |
| 12      | 71        | 3.13%   |
| 16      | 38        | 1.67%   |
| 1       | 21        | 0.93%   |
| 14      | 20        | 0.88%   |
| 10      | 20        | 0.88%   |
| 24      | 13        | 0.57%   |
| 32      | 11        | 0.48%   |
| 3       | 8         | 0.35%   |
| Unknown | 6         | 0.26%   |
| 40      | 5         | 0.22%   |
| 128     | 3         | 0.13%   |
| 48      | 3         | 0.13%   |
| 64      | 2         | 0.09%   |
| 18      | 2         | 0.09%   |
| 22      | 1         | 0.04%   |
| 20      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2202      | 97.13%  |
| 2       | 49        | 2.16%   |
| 4       | 11        | 0.49%   |
| Unknown | 4         | 0.18%   |
| 3       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1681      | 73.89%  |
| 1       | 588       | 25.85%  |
| Unknown | 6         | 0.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2228      | 98.02%  |
| Unknown        | 32        | 1.41%   |
| 32-bit         | 12        | 0.53%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 600       | 25.48%  |
| 0x306a9    | 130       | 5.52%   |
| 0x206a7    | 108       | 4.59%   |
| 0x306c3    | 101       | 4.29%   |
| 0x806ea    | 80        | 3.4%    |
| 0x506e3    | 65        | 2.76%   |
| 0x906ea    | 62        | 2.63%   |
| 0x806ec    | 56        | 2.38%   |
| 0x40651    | 55        | 2.34%   |
| 0x806c1    | 54        | 2.29%   |
| 0x1067a    | 54        | 2.29%   |
| 0x806e9    | 53        | 2.25%   |
| 0x906e9    | 38        | 1.61%   |
| 0x306d4    | 33        | 1.4%    |
| 0x08701021 | 32        | 1.36%   |
| 0x406e3    | 29        | 1.23%   |
| 0x20655    | 25        | 1.06%   |
| 0x30678    | 22        | 0.93%   |
| 0xa0671    | 20        | 0.85%   |
| 0xa0655    | 19        | 0.81%   |
| 0x706e5    | 19        | 0.81%   |
| 0x0a50000c | 19        | 0.81%   |
| 0x0800820d | 19        | 0.81%   |
| 0x10676    | 18        | 0.76%   |
| 0x806eb    | 17        | 0.72%   |
| 0x0a404102 | 17        | 0.72%   |
| 0x906a3    | 15        | 0.64%   |
| 0x406c4    | 15        | 0.64%   |
| 0x306f2    | 15        | 0.64%   |
| 0x206d7    | 15        | 0.64%   |
| 0x106e5    | 15        | 0.64%   |
| 0x0a201016 | 15        | 0.64%   |
| 0xa0652    | 14        | 0.59%   |
| 0x906ed    | 14        | 0.59%   |
| 0x50654    | 14        | 0.59%   |
| 0x306e4    | 14        | 0.59%   |
| 0x20652    | 14        | 0.59%   |
| 0x08701013 | 13        | 0.55%   |
| 0x206c2    | 12        | 0.51%   |
| 0x08600106 | 12        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 431       | 18.95%  |
| Haswell          | 219       | 9.63%   |
| IvyBridge        | 174       | 7.65%   |
| SandyBridge      | 156       | 6.86%   |
| Unknown          | 150       | 6.59%   |
| Skylake          | 149       | 6.55%   |
| Zen 2            | 114       | 5.01%   |
| Zen 3            | 90        | 3.96%   |
| Penryn           | 85        | 3.74%   |
| TigerLake        | 74        | 3.25%   |
| Westmere         | 60        | 2.64%   |
| CometLake        | 54        | 2.37%   |
| Silvermont       | 52        | 2.29%   |
| Broadwell        | 52        | 2.29%   |
| Icelake          | 50        | 2.2%    |
| Alderlake Hybrid | 48        | 2.11%   |
| Zen+             | 45        | 1.98%   |
| Core             | 38        | 1.67%   |
| Nehalem          | 37        | 1.63%   |
| Zen              | 36        | 1.58%   |
| K10              | 30        | 1.32%   |
| Piledriver       | 23        | 1.01%   |
| Goldmont plus    | 20        | 0.88%   |
| Bobcat           | 13        | 0.57%   |
| Goldmont         | 12        | 0.53%   |
| Puma             | 10        | 0.44%   |
| Jaguar           | 10        | 0.44%   |
| K8 Hammer        | 9         | 0.4%    |
| P6               | 6         | 0.26%   |
| NetBurst         | 5         | 0.22%   |
| Excavator        | 5         | 0.22%   |
| Bulldozer        | 5         | 0.22%   |
| Bonnell          | 5         | 0.22%   |
| K10 Llano        | 4         | 0.18%   |
| Tremont          | 2         | 0.09%   |
| Steamroller      | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1238      | 47.58%  |
| Nvidia                                       | 812       | 31.21%  |
| AMD                                          | 490       | 18.83%  |
| Matrox Electronics Systems                   | 35        | 1.35%   |
| ASPEED Technology                            | 16        | 0.61%   |
| XGI Technology (eXtreme Graphics Innovation) | 9         | 0.35%   |
| VIA Technologies                             | 2         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 91        | 3.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 91        | 3.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 88        | 3.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 70        | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 66        | 2.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 64        | 2.41%   |
| Intel HD Graphics 620                                                                    | 56        | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 49        | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 44        | 1.66%   |
| Intel HD Graphics 530                                                                    | 42        | 1.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 42        | 1.58%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 40        | 1.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 36        | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.32%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 1.09%   |
| Intel HD Graphics 630                                                                    | 27        | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 27        | 1.02%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 26        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 0.87%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 21        | 0.79%   |
| AMD Rembrandt [Radeon 680M]                                                              | 21        | 0.79%   |
| Nvidia GP107GL [Quadro P400]                                                             | 20        | 0.75%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                           | 20        | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 19        | 0.72%   |
| AMD Lucienne                                                                             | 18        | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.6%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 16        | 0.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 0.6%    |
| Nvidia GK107GL [Quadro K420]                                                             | 15        | 0.57%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 15        | 0.57%   |
| Intel Iris Plus Graphics G7                                                              | 15        | 0.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 14        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 899       | 39.38%  |
| 1 x Nvidia               | 508       | 22.25%  |
| 1 x AMD                  | 404       | 17.7%   |
| Intel + Nvidia           | 263       | 11.52%  |
| Other                    | 52        | 2.28%   |
| Intel + AMD              | 42        | 1.84%   |
| 1 x Matrox               | 32        | 1.4%    |
| AMD + Nvidia             | 29        | 1.27%   |
| 2 x AMD                  | 15        | 0.66%   |
| 1 x ASPEED               | 10        | 0.44%   |
| 1 x XGI                  | 9         | 0.39%   |
| 2 x Nvidia               | 5         | 0.22%   |
| Nvidia + ASPEED          | 5         | 0.22%   |
| 2 x Intel                | 3         | 0.13%   |
| 1 x VIA                  | 2         | 0.09%   |
| Nvidia + Matrox          | 2         | 0.09%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1677      | 73.14%  |
| Proprietary | 487       | 21.24%  |
| Unknown     | 129       | 5.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1254      | 53.89%  |
| 1.01-2.0   | 278       | 11.95%  |
| 0.01-0.5   | 213       | 9.15%   |
| 3.01-4.0   | 158       | 6.79%   |
| 0.51-1.0   | 151       | 6.49%   |
| 7.01-8.0   | 125       | 5.37%   |
| 8.01-16.0  | 74        | 3.18%   |
| 5.01-6.0   | 42        | 1.8%    |
| 2.01-3.0   | 15        | 0.64%   |
| 16.01-24.0 | 15        | 0.64%   |
| 4.01-5.0   | 2         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 336       | 13.69%  |
| AU Optronics            | 275       | 11.21%  |
| LG Display              | 224       | 9.13%   |
| Dell                    | 177       | 7.21%   |
| Chimei Innolux          | 140       | 5.7%    |
| BOE                     | 129       | 5.26%   |
| Hewlett-Packard         | 115       | 4.69%   |
| Acer                    | 104       | 4.24%   |
| Philips                 | 100       | 4.07%   |
| Apple                   | 93        | 3.79%   |
| BenQ                    | 76        | 3.1%    |
| Ancor Communications    | 68        | 2.77%   |
| Sharp                   | 66        | 2.69%   |
| Lenovo                  | 59        | 2.4%    |
| AOC                     | 56        | 2.28%   |
| Goldstar                | 54        | 2.2%    |
| Eizo                    | 43        | 1.75%   |
| ASUSTek Computer        | 27        | 1.1%    |
| Unknown                 | 25        | 1.02%   |
| InfoVision              | 24        | 0.98%   |
| Chi Mei Optoelectronics | 23        | 0.94%   |
| Sony                    | 21        | 0.86%   |
| CSO                     | 21        | 0.86%   |
| NEC Computers           | 15        | 0.61%   |
| Iiyama                  | 15        | 0.61%   |
| Panasonic               | 12        | 0.49%   |
| PANDA                   | 10        | 0.41%   |
| Toshiba                 | 8         | 0.33%   |
| Vestel Elektronik       | 7         | 0.29%   |
| Medion                  | 7         | 0.29%   |
| Fujitsu Siemens         | 6         | 0.24%   |
| ViewSonic               | 5         | 0.2%    |
| MSI                     | 5         | 0.2%    |
| LG Philips              | 5         | 0.2%    |
| LG Electronics          | 5         | 0.2%    |
| Gigabyte Technology     | 5         | 0.2%    |
| AUS                     | 5         | 0.2%    |
| Valve                   | 4         | 0.16%   |
| LGD                     | 4         | 0.16%   |
| JDI                     | 4         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                   | 15        | 0.58%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 12        | 0.46%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 12        | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                  | 11        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 9         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.35%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                   | 9         | 0.35%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 8         | 0.31%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 7         | 0.27%   |
| Philips LCD Monitor PHL 272S4L 2560x1440                              | 7         | 0.27%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.27%   |
| Dell LCD Monitor P2719H 3840x1080                                     | 7         | 0.27%   |
| Dell LCD Monitor P2719H                                               | 7         | 0.27%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                      | 7         | 0.27%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 7         | 0.27%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 6         | 0.23%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 6         | 0.23%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch   | 6         | 0.23%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 6         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 6         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 6         | 0.23%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                      | 6         | 0.23%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 5         | 0.19%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 5         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.19%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 5         | 0.19%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 5         | 0.19%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 5         | 0.19%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.19%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.19%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 5         | 0.19%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch           | 5         | 0.19%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 5         | 0.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 987       | 41.4%   |
| 3840x2160 (4K)     | 221       | 9.27%   |
| 2560x1440 (QHD)    | 178       | 7.47%   |
| 1366x768 (WXGA)    | 167       | 7.01%   |
| 1920x1200 (WUXGA)  | 126       | 5.29%   |
| 1600x900 (HD+)     | 89        | 3.73%   |
| 1680x1050 (WSXGA+) | 81        | 3.4%    |
| 1280x1024 (SXGA)   | 67        | 2.81%   |
| Unknown            | 66        | 2.77%   |
| 3440x1440          | 49        | 2.06%   |
| 2560x1600          | 39        | 1.64%   |
| 1280x800 (WXGA)    | 37        | 1.55%   |
| 1440x900 (WXGA+)   | 34        | 1.43%   |
| 3840x1080          | 31        | 1.3%    |
| 1600x1200          | 26        | 1.09%   |
| 2880x1800          | 18        | 0.76%   |
| 3840x2400          | 14        | 0.59%   |
| 2560x1080          | 13        | 0.55%   |
| 3200x1800 (QHD+)   | 12        | 0.5%    |
| 2736x1824          | 11        | 0.46%   |
| 3840x1200          | 10        | 0.42%   |
| 3840x1600          | 7         | 0.29%   |
| 1360x768           | 7         | 0.29%   |
| 1024x768 (XGA)     | 7         | 0.29%   |
| 4480x1440          | 6         | 0.25%   |
| 3000x2000          | 6         | 0.25%   |
| 1920x540           | 6         | 0.25%   |
| 2160x1440          | 5         | 0.21%   |
| 1024x600           | 5         | 0.21%   |
| 800x1280           | 4         | 0.17%   |
| 3520x1200          | 4         | 0.17%   |
| 3456x2160          | 4         | 0.17%   |
| 7680x2160          | 3         | 0.13%   |
| 5120x1440          | 3         | 0.13%   |
| 3360x1050          | 3         | 0.13%   |
| 2048x1152          | 3         | 0.13%   |
| 6400x1440          | 2         | 0.08%   |
| 3840x1100          | 2         | 0.08%   |
| 3200x1080          | 2         | 0.08%   |
| 3072x1920          | 2         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 435       | 17.86%  |
| 27      | 258       | 10.6%   |
| 13      | 221       | 9.08%   |
| Unknown | 217       | 8.91%   |
| 14      | 205       | 8.42%   |
| 24      | 196       | 8.05%   |
| 17      | 148       | 6.08%   |
| 23      | 122       | 5.01%   |
| 21      | 97        | 3.98%   |
| 31      | 64        | 2.63%   |
| 12      | 61        | 2.51%   |
| 34      | 49        | 2.01%   |
| 20      | 40        | 1.64%   |
| 22      | 39        | 1.6%    |
| 19      | 39        | 1.6%    |
| 16      | 29        | 1.19%   |
| 32      | 19        | 0.78%   |
| 84      | 18        | 0.74%   |
| 40      | 15        | 0.62%   |
| 11      | 15        | 0.62%   |
| 72      | 14        | 0.57%   |
| 25      | 14        | 0.57%   |
| 33      | 11        | 0.45%   |
| 46      | 10        | 0.41%   |
| 37      | 10        | 0.41%   |
| 18      | 10        | 0.41%   |
| 29      | 9         | 0.37%   |
| 48      | 8         | 0.33%   |
| 54      | 7         | 0.29%   |
| 28      | 7         | 0.29%   |
| 10      | 7         | 0.29%   |
| 49      | 6         | 0.25%   |
| 35      | 4         | 0.16%   |
| 26      | 4         | 0.16%   |
| 7       | 4         | 0.16%   |
| 65      | 3         | 0.12%   |
| 55      | 3         | 0.12%   |
| 142     | 2         | 0.08%   |
| 60      | 2         | 0.08%   |
| 43      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 748       | 31.19%  |
| 501-600        | 529       | 22.06%  |
| 201-300        | 228       | 9.51%   |
| Unknown        | 217       | 9.05%   |
| 401-500        | 187       | 7.8%    |
| 351-400        | 180       | 7.51%   |
| 601-700        | 112       | 4.67%   |
| 701-800        | 79        | 3.29%   |
| 1001-1500      | 44        | 1.83%   |
| 1501-2000      | 33        | 1.38%   |
| 801-900        | 31        | 1.29%   |
| 1-100          | 4         | 0.17%   |
| 901-1000       | 3         | 0.13%   |
| More than 2000 | 2         | 0.08%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1456      | 66%     |
| 16/10   | 337       | 15.28%  |
| Unknown | 202       | 9.16%   |
| 21/9    | 62        | 2.81%   |
| 5/4     | 59        | 2.67%   |
| 3/2     | 32        | 1.45%   |
| 4/3     | 29        | 1.31%   |
| 32/9    | 12        | 0.54%   |
| 6/5     | 4         | 0.18%   |
| 0.67    | 4         | 0.18%   |
| 1.00    | 3         | 0.14%   |
| 3.40    | 2         | 0.09%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 2.50    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 433       | 17.93%  |
| 201-250        | 327       | 13.54%  |
| 81-90          | 295       | 12.22%  |
| 301-350        | 261       | 10.81%  |
| Unknown        | 217       | 8.99%   |
| 351-500        | 161       | 6.67%   |
| 71-80          | 128       | 5.3%    |
| 121-130        | 114       | 4.72%   |
| 251-300        | 109       | 4.51%   |
| 151-200        | 106       | 4.39%   |
| More than 1000 | 57        | 2.36%   |
| 61-70          | 57        | 2.36%   |
| 501-1000       | 49        | 2.03%   |
| 111-120        | 27        | 1.12%   |
| 141-150        | 23        | 0.95%   |
| 51-60          | 18        | 0.75%   |
| 131-140        | 16        | 0.66%   |
| 41-50          | 6         | 0.25%   |
| 91-100         | 6         | 0.25%   |
| 1-40           | 5         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 675       | 28.87%  |
| 121-160       | 626       | 26.78%  |
| 101-120       | 447       | 19.12%  |
| Unknown       | 217       | 9.28%   |
| 161-240       | 201       | 8.6%    |
| More than 240 | 118       | 5.05%   |
| 1-50          | 54        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1695      | 72.13%  |
| 2     | 421       | 17.91%  |
| 0     | 170       | 7.23%   |
| 3     | 60        | 2.55%   |
| 4     | 4         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1367      | 40.98%  |
| Realtek Semiconductor             | 935       | 28.03%  |
| Qualcomm Atheros                  | 243       | 7.28%   |
| Broadcom                          | 191       | 5.73%   |
| MediaTek                          | 53        | 1.59%   |
| Broadcom Limited                  | 50        | 1.5%    |
| Marvell Technology Group          | 44        | 1.32%   |
| Aquantia                          | 33        | 0.99%   |
| Ralink                            | 32        | 0.96%   |
| ASIX Electronics                  | 32        | 0.96%   |
| Lenovo                            | 24        | 0.72%   |
| Nvidia                            | 23        | 0.69%   |
| Sierra Wireless                   | 21        | 0.63%   |
| Ralink Technology                 | 21        | 0.63%   |
| TP-Link                           | 20        | 0.6%    |
| DisplayLink                       | 16        | 0.48%   |
| Dell                              | 16        | 0.48%   |
| Hewlett-Packard                   | 15        | 0.45%   |
| Qualcomm                          | 14        | 0.42%   |
| Huawei Technologies               | 14        | 0.42%   |
| Ericsson Business Mobile Networks | 13        | 0.39%   |
| Edimax Technology                 | 13        | 0.39%   |
| Samsung Electronics               | 12        | 0.36%   |
| NetGear                           | 12        | 0.36%   |
| Microchip Technology              | 10        | 0.3%    |
| D-Link                            | 10        | 0.3%    |
| ASUSTek Computer                  | 10        | 0.3%    |
| Microsoft                         | 9         | 0.27%   |
| Xiaomi                            | 8         | 0.24%   |
| IMC Networks                      | 5         | 0.15%   |
| Fibocom                           | 5         | 0.15%   |
| AVM                               | 5         | 0.15%   |
| NetXen Incorporated               | 4         | 0.12%   |
| Linksys                           | 4         | 0.12%   |
| ICS Advent                        | 4         | 0.12%   |
| D-Link System                     | 4         | 0.12%   |
| Wilocity                          | 3         | 0.09%   |
| Qualcomm Atheros Communications   | 3         | 0.09%   |
| Mellanox Technologies             | 3         | 0.09%   |
| Arduino SA                        | 3         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 638       | 16.03%  |
| Intel Wi-Fi 6 AX200                                               | 136       | 3.42%   |
| Intel Wireless 8265 / 8275                                        | 108       | 2.71%   |
| Intel I211 Gigabit Network Connection                             | 96        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 95        | 2.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 2.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 78        | 1.96%   |
| Intel Wi-Fi 6 AX201                                               | 60        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                              | 59        | 1.48%   |
| Intel Wireless 7260                                               | 53        | 1.33%   |
| Intel Wireless 7265                                               | 48        | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 42        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 40        | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 0.98%   |
| Intel Wireless 8260                                               | 39        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 39        | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 37        | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 34        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 30        | 0.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 30        | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 28        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 28        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27        | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 26        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 26        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 25        | 0.63%   |
| Intel Wireless 3165                                               | 25        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                    | 25        | 0.63%   |
| Intel Wireless-AC 9260                                            | 24        | 0.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 24        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 941       | 54.39%  |
| Qualcomm Atheros                      | 201       | 11.62%  |
| Realtek Semiconductor                 | 180       | 10.4%   |
| Broadcom                              | 107       | 6.18%   |
| MediaTek                              | 50        | 2.89%   |
| Broadcom Limited                      | 34        | 1.97%   |
| Ralink                                | 32        | 1.85%   |
| Sierra Wireless                       | 21        | 1.21%   |
| Ralink Technology                     | 21        | 1.21%   |
| TP-Link                               | 15        | 0.87%   |
| Edimax Technology                     | 13        | 0.75%   |
| Qualcomm                              | 12        | 0.69%   |
| Marvell Technology Group              | 12        | 0.69%   |
| NetGear                               | 11        | 0.64%   |
| ASUSTek Computer                      | 10        | 0.58%   |
| Dell                                  | 9         | 0.52%   |
| D-Link                                | 9         | 0.52%   |
| Hewlett-Packard                       | 7         | 0.4%    |
| Microsoft                             | 6         | 0.35%   |
| IMC Networks                          | 5         | 0.29%   |
| Fibocom                               | 5         | 0.29%   |
| AVM                                   | 5         | 0.29%   |
| Wilocity                              | 3         | 0.17%   |
| Qualcomm Atheros Communications       | 3         | 0.17%   |
| D-Link System                         | 3         | 0.17%   |
| Micro Star International              | 2         | 0.12%   |
| Ericsson Business Mobile Networks     | 2         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.12%   |
| ZyXEL Communications                  | 1         | 0.06%   |
| Quectel Wireless Solutions            | 1         | 0.06%   |
| Philips (or NXP)                      | 1         | 0.06%   |
| Netopia                               | 1         | 0.06%   |
| Linksys                               | 1         | 0.06%   |
| Gemtek                                | 1         | 0.06%   |
| CyberTAN Technology                   | 1         | 0.06%   |
| Belkin Components                     | 1         | 0.06%   |
| Arduino SA                            | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 136       | 7.82%   |
| Intel Wireless 8265 / 8275                                     | 108       | 6.21%   |
| Intel Wi-Fi 6 AX201                                            | 60        | 3.45%   |
| Intel Wireless 7260                                            | 53        | 3.05%   |
| Intel Wireless 7265                                            | 48        | 2.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 42        | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 40        | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 39        | 2.24%   |
| Intel Wireless 8260                                            | 39        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 39        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 33        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 30        | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 30        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 26        | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 26        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 25        | 1.44%   |
| Intel Wireless 3165                                            | 25        | 1.44%   |
| Intel Centrino Ultimate-N 6300                                 | 25        | 1.44%   |
| Intel Wireless-AC 9260                                         | 24        | 1.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 22        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 20        | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 19        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 18        | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 17        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 16        | 0.92%   |
| Intel Centrino Advanced-N 6235                                 | 16        | 0.92%   |
| Intel Wireless 3160                                            | 15        | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 13        | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 12        | 0.69%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 12        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 0.69%   |
| Sierra Wireless EM7455                                         | 11        | 0.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 11        | 0.63%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 11        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 857       | 40.54%  |
| Intel                         | 827       | 39.12%  |
| Broadcom                      | 110       | 5.2%    |
| Qualcomm Atheros              | 69        | 3.26%   |
| Aquantia                      | 33        | 1.56%   |
| Marvell Technology Group      | 32        | 1.51%   |
| ASIX Electronics              | 32        | 1.51%   |
| Nvidia                        | 23        | 1.09%   |
| Lenovo                        | 23        | 1.09%   |
| DisplayLink                   | 16        | 0.76%   |
| Broadcom Limited              | 16        | 0.76%   |
| Samsung Electronics           | 12        | 0.57%   |
| Xiaomi                        | 8         | 0.38%   |
| Microchip Technology          | 8         | 0.38%   |
| Huawei Technologies           | 8         | 0.38%   |
| TP-Link                       | 5         | 0.24%   |
| NetXen Incorporated           | 4         | 0.19%   |
| ICS Advent                    | 4         | 0.19%   |
| MediaTek                      | 3         | 0.14%   |
| Linksys                       | 3         | 0.14%   |
| Qualcomm                      | 2         | 0.09%   |
| Microsoft                     | 2         | 0.09%   |
| Mellanox Technologies         | 2         | 0.09%   |
| Standard Microsystems         | 1         | 0.05%   |
| QNAP System                   | 1         | 0.05%   |
| OnePlus Technology (Shenzhen) | 1         | 0.05%   |
| NetGear                       | 1         | 0.05%   |
| Netchip Technology            | 1         | 0.05%   |
| MosChip Semiconductor         | 1         | 0.05%   |
| JMicron Technology            | 1         | 0.05%   |
| HMD Global                    | 1         | 0.05%   |
| Hewlett-Packard               | 1         | 0.05%   |
| Google                        | 1         | 0.05%   |
| D-Link System                 | 1         | 0.05%   |
| D-Link                        | 1         | 0.05%   |
| Cypress Semiconductor         | 1         | 0.05%   |
| Apple                         | 1         | 0.05%   |
| ADMtek                        | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 638       | 29.16%  |
| Intel I211 Gigabit Network Connection                             | 96        | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 95        | 4.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 4.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 78        | 3.56%   |
| Intel Ethernet Connection (2) I219-V                              | 59        | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 46        | 2.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 1.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 1.83%   |
| Intel 82579V Gigabit Network Connection                           | 37        | 1.69%   |
| Intel 82574L Gigabit Network Connection                           | 34        | 1.55%   |
| Intel Ethernet Controller I225-V                                  | 28        | 1.28%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 1.14%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 24        | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 1.05%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 1.05%   |
| Intel I210 Gigabit Network Connection                             | 21        | 0.96%   |
| Intel I350 Gigabit Network Connection                             | 20        | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 19        | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 18        | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 18        | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.73%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 16        | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.55%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 9         | 0.41%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 0.41%   |
| Intel Ethernet Connection (11) I219-LM                            | 9         | 0.41%   |
| Intel 82576 Gigabit Network Connection                            | 9         | 0.41%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 8         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 8         | 0.37%   |
| Lenovo ThinkPad Lan                                               | 8         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1932      | 53.49%  |
| WiFi     | 1629      | 45.1%   |
| Modem    | 47        | 1.3%    |
| Unknown  | 4         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1163      | 50.7%   |
| Ethernet | 1131      | 49.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1151      | 50.5%   |
| 1     | 913       | 40.06%  |
| 3     | 101       | 4.43%   |
| 0     | 70        | 3.07%   |
| 4     | 28        | 1.23%   |
| 6     | 8         | 0.35%   |
| 5     | 4         | 0.18%   |
| 8     | 2         | 0.09%   |
| 10    | 1         | 0.04%   |
| 7     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1816      | 77.91%  |
| Yes  | 515       | 22.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 758       | 54.77%  |
| Realtek Semiconductor           | 89        | 6.43%   |
| Apple                           | 83        | 6%      |
| Broadcom                        | 72        | 5.2%    |
| Cambridge Silicon Radio         | 62        | 4.48%   |
| Qualcomm Atheros Communications | 58        | 4.19%   |
| Foxconn / Hon Hai               | 54        | 3.9%    |
| IMC Networks                    | 45        | 3.25%   |
| Lite-On Technology              | 35        | 2.53%   |
| ASUSTek Computer                | 33        | 2.38%   |
| Hewlett-Packard                 | 16        | 1.16%   |
| Dell                            | 15        | 1.08%   |
| MediaTek                        | 11        | 0.79%   |
| Marvell Semiconductor           | 10        | 0.72%   |
| Ralink                          | 9         | 0.65%   |
| USI                             | 8         | 0.58%   |
| Alps Electric                   | 4         | 0.29%   |
| Toshiba                         | 3         | 0.22%   |
| Realtek                         | 3         | 0.22%   |
| Micro Star International        | 3         | 0.22%   |
| Ralink Technology               | 2         | 0.14%   |
| Edimax Technology               | 2         | 0.14%   |
| Chicony Electronics             | 2         | 0.14%   |
| TP-Link                         | 1         | 0.07%   |
| Taiyo Yuden                     | 1         | 0.07%   |
| Logitech                        | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Foxconn International           | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 280       | 20.2%   |
| Intel AX201 Bluetooth                               | 138       | 9.96%   |
| Intel AX200 Bluetooth                               | 129       | 9.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 79        | 5.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 62        | 4.47%   |
| Realtek Bluetooth Radio                             | 61        | 4.4%    |
| Intel Bluetooth Device                              | 48        | 3.46%   |
| Apple Bluetooth USB Host Controller                 | 25        | 1.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 24        | 1.73%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 1.73%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 24        | 1.73%   |
| Apple Bluetooth Host Controller                     | 24        | 1.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 1.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 1.44%   |
| IMC Networks Bluetooth Radio                        | 20        | 1.44%   |
| Intel AX210 Bluetooth                               | 16        | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 1.08%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 1.01%   |
| IMC Networks Wireless_Device                        | 14        | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.87%   |
| MediaTek Wireless_Device                            | 11        | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 10        | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.72%   |
| Apple Bluetooth HCI                                 | 10        | 0.72%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.65%   |
| ASUS ASUS USB-BT500                                 | 9         | 0.65%   |
| USI Bluetooth Device                                | 8         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.58%   |
| Marvell Bluetooth and Wireless LAN Composite        | 7         | 0.51%   |
| Lite-On Bluetooth Device                            | 7         | 0.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.51%   |
| IMC Networks Bluetooth Device                       | 6         | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                        | 6         | 0.43%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 6         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 1673      | 52.63%  |
| Nvidia                    | 623       | 19.6%   |
| AMD                       | 533       | 16.77%  |
| GN Netcom                 | 39        | 1.23%   |
| Logitech                  | 37        | 1.16%   |
| C-Media Electronics       | 33        | 1.04%   |
| ASUSTek Computer          | 19        | 0.6%    |
| Lenovo                    | 18        | 0.57%   |
| Plantronics               | 14        | 0.44%   |
| Realtek Semiconductor     | 11        | 0.35%   |
| Hewlett-Packard           | 11        | 0.35%   |
| Creative Labs             | 10        | 0.31%   |
| SteelSeries ApS           | 9         | 0.28%   |
| RODE Microphones          | 9         | 0.28%   |
| Kingston Technology       | 9         | 0.28%   |
| Razer USA                 | 6         | 0.19%   |
| Generalplus Technology    | 6         | 0.19%   |
| BEHRINGER International   | 6         | 0.19%   |
| Apple                     | 6         | 0.19%   |
| Texas Instruments         | 5         | 0.16%   |
| Tenx Technology           | 5         | 0.16%   |
| Creative Technology       | 5         | 0.16%   |
| Samson Technologies       | 4         | 0.13%   |
| JMTek                     | 4         | 0.13%   |
| Corsair                   | 4         | 0.13%   |
| Conexant Systems          | 4         | 0.13%   |
| Sony                      | 3         | 0.09%   |
| Sennheiser Communications | 3         | 0.09%   |
| ROCCAT                    | 3         | 0.09%   |
| Micro Star International  | 3         | 0.09%   |
| Focusrite-Novation        | 3         | 0.09%   |
| Yamaha                    | 2         | 0.06%   |
| XMOS                      | 2         | 0.06%   |
| VIA Technologies          | 2         | 0.06%   |
| TerraTec Electronic       | 2         | 0.06%   |
| Roland                    | 2         | 0.06%   |
| Other World Computing     | 2         | 0.06%   |
| Magic Control Technology  | 2         | 0.06%   |
| HiFiBerry                 | 2         | 0.06%   |
| GYROCOM C&C               | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 213       | 5.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 163       | 4.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 155       | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 127       | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 117       | 3.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 106       | 2.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 88        | 2.39%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 88        | 2.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 83        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 79        | 2.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 74        | 2.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 74        | 2.01%   |
| Intel Haswell-ULT HD Audio Controller                                      | 65        | 1.76%   |
| Intel 8 Series HD Audio Controller                                         | 65        | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 65        | 1.76%   |
| Intel 200 Series PCH HD Audio                                              | 60        | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 54        | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 1.36%   |
| Nvidia GK107 HDMI Audio Controller                                         | 49        | 1.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 47        | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 44        | 1.19%   |
| Nvidia GA104 High Definition Audio Controller                              | 42        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 42        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 42        | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 42        | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 41        | 1.11%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 37        | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 36        | 0.98%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 36        | 0.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 34        | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 33        | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 33        | 0.9%    |
| Nvidia GP102 HDMI Audio Controller                                         | 30        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 30        | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                              | 29        | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                         | 28        | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 28        | 0.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 0.76%   |
| AMD FCH Azalia Controller                                                  | 28        | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 368       | 23.74%  |
| SK hynix                                | 295       | 19.03%  |
| Kingston                                | 258       | 16.65%  |
| Micron Technology                       | 174       | 11.23%  |
| Corsair                                 | 155       | 10%     |
| Unknown                                 | 100       | 6.45%   |
| Crucial                                 | 54        | 3.48%   |
| G.Skill                                 | 42        | 2.71%   |
| Elpida                                  | 21        | 1.35%   |
| Ramaxel Technology                      | 14        | 0.9%    |
| A-DATA Technology                       | 13        | 0.84%   |
| Nanya Technology                        | 9         | 0.58%   |
| Unknown                                 | 7         | 0.45%   |
| Patriot                                 | 5         | 0.32%   |
| Unknown (ABCD)                          | 3         | 0.19%   |
| Hewlett-Packard                         | 3         | 0.19%   |
| Avant                                   | 3         | 0.19%   |
| Unknown (0x9801)                        | 2         | 0.13%   |
| Team                                    | 2         | 0.13%   |
| ASint Technology                        | 2         | 0.13%   |
| Apacer                                  | 2         | 0.13%   |
| Unknown (0x198)                         | 1         | 0.06%   |
| Unknown (08AE)                          | 1         | 0.06%   |
| Unifosa                                 | 1         | 0.06%   |
| Smart                                   | 1         | 0.06%   |
| Silicon Power Computer & Communications | 1         | 0.06%   |
| Princeton                               | 1         | 0.06%   |
| Patriot Memory                          | 1         | 0.06%   |
| OnBoard                                 | 1         | 0.06%   |
| OCZ                                     | 1         | 0.06%   |
| Melco                                   | 1         | 0.06%   |
| Kingmax                                 | 1         | 0.06%   |
| KANMEIQi                                | 1         | 0.06%   |
| HPE                                     | 1         | 0.06%   |
| GOODRAM                                 | 1         | 0.06%   |
| G-Alantic                               | 1         | 0.06%   |
| Advantech                               | 1         | 0.06%   |
| A-DA                                    | 1         | 0.06%   |
| 48spaces                                | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 16        | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 16        | 0.95%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s          | 13        | 0.77%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 13        | 0.77%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 12        | 0.72%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 12        | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 10        | 0.6%    |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s          | 9         | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 8         | 0.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8         | 0.48%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 8         | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 8         | 0.48%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s         | 8         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 7         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 7         | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 7         | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 7         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 7         | 0.42%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 7         | 0.42%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 7         | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 7         | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 7         | 0.42%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 7         | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 7         | 0.42%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s       | 7         | 0.42%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 7         | 0.42%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s         | 7         | 0.42%   |
| Unknown                                                        | 7         | 0.42%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 6         | 0.36%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 6         | 0.36%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 6         | 0.36%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 6         | 0.36%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 6         | 0.36%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 6         | 0.36%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s  | 6         | 0.36%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 6         | 0.36%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 6         | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 5         | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 5         | 0.3%    |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 5         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 702       | 49.96%  |
| DDR3    | 451       | 32.1%   |
| LPDDR3  | 62        | 4.41%   |
| LPDDR4  | 49        | 3.49%   |
| DDR2    | 42        | 2.99%   |
| DDR5    | 34        | 2.42%   |
| Unknown | 23        | 1.64%   |
| LPDDR5  | 19        | 1.35%   |
| SDRAM   | 18        | 1.28%   |
| DDR     | 5         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 694       | 49.57%  |
| DIMM         | 567       | 40.5%   |
| Row Of Chips | 120       | 8.57%   |
| Chip         | 9         | 0.64%   |
| RIMM         | 6         | 0.43%   |
| Unknown      | 3         | 0.21%   |
| FB-DIMM      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 604       | 40.29%  |
| 16384 | 339       | 22.62%  |
| 4096  | 308       | 20.55%  |
| 2048  | 128       | 8.54%   |
| 32768 | 81        | 5.4%    |
| 1024  | 32        | 2.13%   |
| 65536 | 5         | 0.33%   |
| 49152 | 1         | 0.07%   |
| 512   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 279       | 18.62%  |
| 3200    | 243       | 16.22%  |
| 2667    | 195       | 13.02%  |
| 2133    | 111       | 7.41%   |
| 1333    | 99        | 6.61%   |
| 2400    | 92        | 6.14%   |
| 1334    | 51        | 3.4%    |
| 1867    | 29        | 1.94%   |
| 3600    | 28        | 1.87%   |
| 3000    | 27        | 1.8%    |
| 4800    | 26        | 1.74%   |
| 4267    | 26        | 1.74%   |
| 2666    | 26        | 1.74%   |
| 800     | 26        | 1.74%   |
| 667     | 20        | 1.34%   |
| 3400    | 19        | 1.27%   |
| 6400    | 18        | 1.2%    |
| 1067    | 16        | 1.07%   |
| 3266    | 13        | 0.87%   |
| 3733    | 12        | 0.8%    |
| Unknown | 12        | 0.8%    |
| 1066    | 10        | 0.67%   |
| 2933    | 9         | 0.6%    |
| 3800    | 7         | 0.47%   |
| 8400    | 6         | 0.4%    |
| 2000    | 6         | 0.4%    |
| 1866    | 6         | 0.4%    |
| 1800    | 6         | 0.4%    |
| 5808    | 5         | 0.33%   |
| 4266    | 5         | 0.33%   |
| 3533    | 5         | 0.33%   |
| 3100    | 5         | 0.33%   |
| 4199    | 4         | 0.27%   |
| 3933    | 4         | 0.27%   |
| 3666    | 4         | 0.27%   |
| 2465    | 4         | 0.27%   |
| 2048    | 4         | 0.27%   |
| 6000    | 3         | 0.2%    |
| 3500    | 3         | 0.2%    |
| 333     | 3         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 27        | 42.86%  |
| Brother Industries       | 16        | 25.4%   |
| Samsung Electronics      | 5         | 7.94%   |
| Canon                    | 4         | 6.35%   |
| STMicroelectronics       | 3         | 4.76%   |
| Seiko Epson              | 2         | 3.17%   |
| Oki Data                 | 2         | 3.17%   |
| Zhuhai Poskey Technology | 1         | 1.59%   |
| Prolific Technology      | 1         | 1.59%   |
| Konica Minolta           | 1         | 1.59%   |
| Dymo-CoStar              | 1         | 1.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 3         | 4.76%   |
| Samsung M337x 387x 407x Series                             | 2         | 3.17%   |
| Oki Data USB Device                                        | 2         | 3.17%   |
| HP OfficeJet Pro 7730 series                               | 2         | 3.17%   |
| HP OfficeJet 6950                                          | 2         | 3.17%   |
| HP LaserJet Pro M148f-M149f                                | 2         | 3.17%   |
| HP LaserJet P1102                                          | 2         | 3.17%   |
| HP ENVY 5540 series                                        | 2         | 3.17%   |
| HP Deskjet 2540 series                                     | 2         | 3.17%   |
| Brother Printer                                            | 2         | 3.17%   |
| Brother MFC Composite Device                               | 2         | 3.17%   |
| Zhuhai Poskey Printer                                      | 1         | 1.59%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.59%   |
| Seiko Epson ET-2820 Series                                 | 1         | 1.59%   |
| Samsung M332x 382x 402x Series                             | 1         | 1.59%   |
| Samsung C48x Series                                        | 1         | 1.59%   |
| Samsung C1860 Series                                       | 1         | 1.59%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.59%   |
| Konica Minolta Printer                                     | 1         | 1.59%   |
| HP Smart Tank Plus 550 series                              | 1         | 1.59%   |
| HP Smart Tank 7000 series                                  | 1         | 1.59%   |
| HP Officejet 4630 series                                   | 1         | 1.59%   |
| HP LaserJet P3010 Series                                   | 1         | 1.59%   |
| HP LaserJet P2055 series                                   | 1         | 1.59%   |
| HP Laserjet P1505                                          | 1         | 1.59%   |
| HP LaserJet 3050                                           | 1         | 1.59%   |
| HP LaserJet 3020                                           | 1         | 1.59%   |
| HP LaserJet 1320                                           | 1         | 1.59%   |
| HP LaserJet 1020                                           | 1         | 1.59%   |
| HP Laser 107a                                              | 1         | 1.59%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.59%   |
| HP ENVY 6400 series                                        | 1         | 1.59%   |
| HP ENVY 4520 series                                        | 1         | 1.59%   |
| HP DeskJet F2100 Printer series                            | 1         | 1.59%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.59%   |
| Canon TS3300 series                                        | 1         | 1.59%   |
| Canon PIXMA TS6250                                         | 1         | 1.59%   |
| Canon PIXMA MX450 Series                                   | 1         | 1.59%   |
| Canon iP7200 series                                        | 1         | 1.59%   |
| Brother MFC-9320CW                                         | 1         | 1.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Canon             | 7         | 46.67%  |
| Seiko Epson       | 4         | 26.67%  |
| Hewlett-Packard   | 2         | 13.33%  |
| Fujitsu           | 1         | 6.67%   |
| Canon Electronics | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 2         | 13.33%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                   | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 6.67%   |
| HP ScanJet 4070 PhotoSmart                                    | 1         | 6.67%   |
| HP ScanJet 2400c                                              | 1         | 6.67%   |
| Fujitsu ScanSnap SV600                                        | 1         | 6.67%   |
| Canon P-150 Scanner                                           | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 1         | 6.67%   |
| Canon CanoScan N650U/N656U                                    | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                        | 1         | 6.67%   |
| Canon CanoScan LiDE 200                                       | 1         | 6.67%   |
| Canon CanoScan LiDE 100                                       | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 347       | 26.96%  |
| IMC Networks                           | 101       | 7.85%   |
| Logitech                               | 95        | 7.38%   |
| Apple                                  | 82        | 6.37%   |
| Microdia                               | 79        | 6.14%   |
| Bison Electronics                      | 74        | 5.75%   |
| Realtek Semiconductor                  | 65        | 5.05%   |
| Quanta                                 | 61        | 4.74%   |
| Sunplus Innovation Technology          | 53        | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 48        | 3.73%   |
| Lite-On Technology                     | 35        | 2.72%   |
| Suyin                                  | 32        | 2.49%   |
| Acer                                   | 22        | 1.71%   |
| Syntek                                 | 21        | 1.63%   |
| Luxvisions Innotech Limited            | 19        | 1.48%   |
| Lenovo                                 | 17        | 1.32%   |
| Ricoh                                  | 14        | 1.09%   |
| Microsoft                              | 14        | 1.09%   |
| Alcor Micro                            | 14        | 1.09%   |
| Samsung Electronics                    | 12        | 0.93%   |
| Sonix Technology                       | 8         | 0.62%   |
| Silicon Motion                         | 7         | 0.54%   |
| Z-Star Microelectronics                | 5         | 0.39%   |
| Primax Electronics                     | 5         | 0.39%   |
| Generalplus Technology                 | 5         | 0.39%   |
| ALi                                    | 5         | 0.39%   |
| Xiaomi                                 | 2         | 0.16%   |
| Tripath Technology                     | 2         | 0.16%   |
| ShineTech                              | 2         | 0.16%   |
| OmniVision Technologies                | 2         | 0.16%   |
| MacroSilicon                           | 2         | 0.16%   |
| KYE Systems (Mouse Systems)            | 2         | 0.16%   |
| Intel                                  | 2         | 0.16%   |
| Genesys Logic                          | 2         | 0.16%   |
| DLTDC0A9II090N                         | 2         | 0.16%   |
| DigiTech                               | 2         | 0.16%   |
| Creative Technology                    | 2         | 0.16%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.16%   |
| YGTek                                  | 1         | 0.08%   |
| WCM_USB                                | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 93        | 7.1%    |
| IMC Networks Integrated Camera          | 48        | 3.67%   |
| Microdia Integrated_Webcam_HD           | 40        | 3.06%   |
| Chicony HD WebCam                       | 34        | 2.6%    |
| Apple FaceTime HD Camera (Built-in)     | 27        | 2.06%   |
| Chicony HP HD Camera                    | 26        | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam       | 23        | 1.76%   |
| Bison Integrated Camera                 | 23        | 1.76%   |
| Apple Built-in iSight                   | 23        | 1.76%   |
| Realtek Integrated_Webcam_HD            | 21        | 1.6%    |
| Logitech Webcam C270                    | 17        | 1.3%    |
| Quanta HP HD Camera                     | 16        | 1.22%   |
| Logitech HD Pro Webcam C920             | 16        | 1.22%   |
| Lite-On Integrated Camera               | 16        | 1.22%   |
| Chicony USB2.0 Camera                   | 16        | 1.22%   |
| Chicony HP Wide Vision HD Camera        | 14        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 14        | 1.07%   |
| Sunplus HD WebCam                       | 13        | 0.99%   |
| Syntek Integrated Camera                | 12        | 0.92%   |
| Samsung Galaxy series, misc. (MTP mode) | 12        | 0.92%   |
| Microdia Integrated Webcam              | 11        | 0.84%   |
| Chicony Integrated Camera (1280x720@30) | 11        | 0.84%   |
| Chicony HP Truevision HD                | 11        | 0.84%   |
| Sunplus Integrated_Webcam_HD            | 10        | 0.76%   |
| Lite-On HP HD Camera                    | 10        | 0.76%   |
| Apple FaceTime HD Camera                | 10        | 0.76%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 9         | 0.69%   |
| Chicony HD User Facing                  | 9         | 0.69%   |
| Suyin HP Truevision HD                  | 8         | 0.61%   |
| Chicony HP HD Webcam                    | 8         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam            | 7         | 0.53%   |
| Quanta HD User Facing                   | 7         | 0.53%   |
| Logitech StreamCam                      | 7         | 0.53%   |
| Logitech HD Webcam C615                 | 7         | 0.53%   |
| Lenovo Integrated Webcam                | 7         | 0.53%   |
| Chicony VGA WebCam                      | 7         | 0.53%   |
| Chicony Integrated IR Camera            | 7         | 0.53%   |
| Bison SunplusIT Integrated Camera       | 7         | 0.53%   |
| Bison Lenovo EasyCamera                 | 7         | 0.53%   |
| Bison BisonCam,NB Pro                   | 7         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 142       | 37.08%  |
| Validity Sensors                   | 140       | 36.55%  |
| Shenzhen Goodix Technology         | 32        | 8.36%   |
| Upek                               | 20        | 5.22%   |
| Elan Microelectronics              | 20        | 5.22%   |
| AuthenTec                          | 14        | 3.66%   |
| LighTuning Technology              | 11        | 2.87%   |
| STMicroelectronics                 | 3         | 0.78%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 51        | 13.32%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 8.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 5.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 4.18%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 4.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 4.18%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 14        | 3.66%   |
| Elan ELAN:ARM-M4                                                           | 14        | 3.66%   |
| Synaptics  WBDI                                                            | 13        | 3.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 3.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 2.87%   |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 2.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 2.61%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 2.35%   |
| Synaptics UWP WBDI                                                         | 9         | 2.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.35%   |
| Validity Sensors VFS491                                                    | 8         | 2.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 1.83%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 1.83%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.57%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.31%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.31%   |
| AuthenTec AES2810                                                          | 5         | 1.31%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.31%   |
| Synaptics WBDI                                                             | 4         | 1.04%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.78%   |
| Unknown                                                                    | 3         | 0.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.52%   |
| Synaptics TouchPad                                                         | 2         | 0.52%   |
| Synaptics Fingerprint scanner                                              | 2         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 56        | 43.41%  |
| Broadcom                  | 41        | 31.78%  |
| Upek                      | 12        | 9.3%    |
| Yubico.com                | 5         | 3.88%   |
| O2 Micro                  | 5         | 3.88%   |
| Lenovo                    | 3         | 2.33%   |
| Clay Logic                | 2         | 1.55%   |
| OmniKey                   | 1         | 0.78%   |
| Gemalto (was Gemplus)     | 1         | 0.78%   |
| Bit4id                    | 1         | 0.78%   |
| Aladdin Knowledge Systems | 1         | 0.78%   |
| Advanced Card Systems     | 1         | 0.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 56        | 43.41%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 10.08%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 9.3%    |
| Broadcom 5880                                                                | 12        | 9.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 6.2%    |
| Broadcom 58200                                                               | 8         | 6.2%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 3.88%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 2.33%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.33%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 0.78%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.78%   |
| OmniKey CardMan 4321                                                         | 1         | 0.78%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.78%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.78%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.78%   |
| Bit4id miniLector-s                                                          | 1         | 0.78%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.78%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1509      | 64.6%   |
| 1     | 640       | 27.4%   |
| 2     | 144       | 6.16%   |
| 3     | 26        | 1.11%   |
| 4     | 11        | 0.47%   |
| 7     | 2         | 0.09%   |
| 6     | 2         | 0.09%   |
| 5     | 2         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 378       | 36.63%  |
| Graphics card            | 170       | 16.47%  |
| Chipcard                 | 108       | 10.47%  |
| Net/wireless             | 106       | 10.27%  |
| Multimedia controller    | 58        | 5.62%   |
| Communication controller | 51        | 4.94%   |
| Unassigned class         | 39        | 3.78%   |
| Camera                   | 29        | 2.81%   |
| Bluetooth                | 22        | 2.13%   |
| Sound                    | 14        | 1.36%   |
| Net/ethernet             | 12        | 1.16%   |
| Card reader              | 12        | 1.16%   |
| Storage                  | 8         | 0.78%   |
| Network                  | 6         | 0.58%   |
| Storage/raid             | 5         | 0.48%   |
| Modem                    | 5         | 0.48%   |
| Dvb card                 | 3         | 0.29%   |
| Storage/nvme             | 2         | 0.19%   |
| Wireless                 | 1         | 0.1%    |
| Storage/ata              | 1         | 0.1%    |
| Flash memory             | 1         | 0.1%    |
| Firewire controller      | 1         | 0.1%    |

