Linux in Chile - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Chile/Desktop/README.md) and [notebooks](/Location/Chile/Notebook/README.md).

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

Total: 1569

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 240 G8 Notebook PC          | Notebook    | [d4c61a6527](https://linux-hardware.org/?probe=d4c61a6527) | Feb 01, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d743247f69](https://linux-hardware.org/?probe=d743247f69) | Jan 31, 2024 |
| ASUSTek       | X556UQK                     | Notebook    | [970dc5b87d](https://linux-hardware.org/?probe=970dc5b87d) | Jan 31, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [02a1844f63](https://linux-hardware.org/?probe=02a1844f63) | Jan 31, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [202a9720c4](https://linux-hardware.org/?probe=202a9720c4) | Jan 30, 2024 |
| Lenovo        | ThinkPad T495 20NKS1EP00    | Notebook    | [addeb3711c](https://linux-hardware.org/?probe=addeb3711c) | Jan 30, 2024 |
| Lenovo        | ThinkPad T490 20N3S8DK00    | Notebook    | [4e9cad214e](https://linux-hardware.org/?probe=4e9cad214e) | Jan 28, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [68364930e7](https://linux-hardware.org/?probe=68364930e7) | Jan 27, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [1d4943457c](https://linux-hardware.org/?probe=1d4943457c) | Jan 26, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [75379edae7](https://linux-hardware.org/?probe=75379edae7) | Jan 26, 2024 |
| HP            | 304Ah                       | Desktop     | [5e40a8acee](https://linux-hardware.org/?probe=5e40a8acee) | Jan 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3bc0546f62](https://linux-hardware.org/?probe=3bc0546f62) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [95692e9f04](https://linux-hardware.org/?probe=95692e9f04) | Jan 23, 2024 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [efa155f365](https://linux-hardware.org/?probe=efa155f365) | Jan 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [2c5947d48c](https://linux-hardware.org/?probe=2c5947d48c) | Jan 22, 2024 |
| HP            | Pavilion g4                 | Notebook    | [ecddd3e100](https://linux-hardware.org/?probe=ecddd3e100) | Jan 21, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [de30e068d6](https://linux-hardware.org/?probe=de30e068d6) | Jan 21, 2024 |
| Lenovo        | ThinkPad X280 20KEA03YCL    | Notebook    | [6d4961e126](https://linux-hardware.org/?probe=6d4961e126) | Jan 21, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [1ad08b8198](https://linux-hardware.org/?probe=1ad08b8198) | Jan 21, 2024 |
| Acer          | Nitro AN517-54              | Notebook    | [e736d57544](https://linux-hardware.org/?probe=e736d57544) | Jan 18, 2024 |
| Sony          | VPCF120FL                   | Notebook    | [6ada0707e6](https://linux-hardware.org/?probe=6ada0707e6) | Jan 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [5a872c599e](https://linux-hardware.org/?probe=5a872c599e) | Jan 15, 2024 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [2d802ba751](https://linux-hardware.org/?probe=2d802ba751) | Jan 13, 2024 |
| ECS           | G31T-M7                     | Desktop     | [254ece65d1](https://linux-hardware.org/?probe=254ece65d1) | Jan 12, 2024 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [13fd289ac7](https://linux-hardware.org/?probe=13fd289ac7) | Jan 11, 2024 |
| ASUSTek       | X542UQ                      | Notebook    | [80e9791b86](https://linux-hardware.org/?probe=80e9791b86) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [68a601314f](https://linux-hardware.org/?probe=68a601314f) | Jan 10, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [d7c1f42897](https://linux-hardware.org/?probe=d7c1f42897) | Jan 10, 2024 |
| Shenzhen M... | F7BSC                       | Desktop     | [80d405caee](https://linux-hardware.org/?probe=80d405caee) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | Notebook    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| ASUSTek       | X542UA                      | Notebook    | [028b7c4d83](https://linux-hardware.org/?probe=028b7c4d83) | Jan 08, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [2ed16f6a80](https://linux-hardware.org/?probe=2ed16f6a80) | Jan 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4285b072d7](https://linux-hardware.org/?probe=4285b072d7) | Jan 05, 2024 |
| HP            | EliteBook 6930p             | Notebook    | [868c32afaa](https://linux-hardware.org/?probe=868c32afaa) | Jan 05, 2024 |
| ASUSTek       | X542UA                      | Notebook    | [5d7b076a1c](https://linux-hardware.org/?probe=5d7b076a1c) | Jan 05, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [65ef79e8a1](https://linux-hardware.org/?probe=65ef79e8a1) | Jan 04, 2024 |
| HP            | Notebook                    | Notebook    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [04753e77e0](https://linux-hardware.org/?probe=04753e77e0) | Jan 02, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [63fd2a4477](https://linux-hardware.org/?probe=63fd2a4477) | Dec 31, 2023 |
| ANGXUN        | X79 (INTEL Xeon E5/Corei... | Desktop     | [92d3ce2ee5](https://linux-hardware.org/?probe=92d3ce2ee5) | Dec 30, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [12339778af](https://linux-hardware.org/?probe=12339778af) | Dec 30, 2023 |
| Dell          | Latitude 7390               | Notebook    | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [da4285cce4](https://linux-hardware.org/?probe=da4285cce4) | Dec 26, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [029b043cec](https://linux-hardware.org/?probe=029b043cec) | Dec 25, 2023 |
| eMachines     | EMCP61M                     | Desktop     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| Dell          | Latitude 7280               | Notebook    | [5397e7633e](https://linux-hardware.org/?probe=5397e7633e) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [ae01ab2ebe](https://linux-hardware.org/?probe=ae01ab2ebe) | Dec 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dbbab5f96b](https://linux-hardware.org/?probe=dbbab5f96b) | Dec 19, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [f6f623f0d8](https://linux-hardware.org/?probe=f6f623f0d8) | Dec 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e8847d53ec](https://linux-hardware.org/?probe=e8847d53ec) | Dec 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5223e586fd](https://linux-hardware.org/?probe=5223e586fd) | Dec 15, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [165e16505d](https://linux-hardware.org/?probe=165e16505d) | Dec 14, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1d510c91de](https://linux-hardware.org/?probe=1d510c91de) | Dec 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2eeac061b2](https://linux-hardware.org/?probe=2eeac061b2) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [53ee047174](https://linux-hardware.org/?probe=53ee047174) | Dec 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [af38b45c59](https://linux-hardware.org/?probe=af38b45c59) | Dec 12, 2023 |
| Acer          | V5-171                      | Notebook    | [79abc82869](https://linux-hardware.org/?probe=79abc82869) | Dec 11, 2023 |
| SK hynix      | HyBook                      | Notebook    | [cf29911599](https://linux-hardware.org/?probe=cf29911599) | Dec 11, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [5121b6a20c](https://linux-hardware.org/?probe=5121b6a20c) | Dec 09, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [f6ed574e0d](https://linux-hardware.org/?probe=f6ed574e0d) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [8198e47786](https://linux-hardware.org/?probe=8198e47786) | Dec 08, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2a593d9294](https://linux-hardware.org/?probe=2a593d9294) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9b6c1bfbf2](https://linux-hardware.org/?probe=9b6c1bfbf2) | Dec 06, 2023 |
| HP            | 245 G5 Notebook PC          | Notebook    | [f3abc9d11d](https://linux-hardware.org/?probe=f3abc9d11d) | Dec 05, 2023 |
| HP            | Notebook                    | Notebook    | [8d58f80f77](https://linux-hardware.org/?probe=8d58f80f77) | Dec 03, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [707fd0c687](https://linux-hardware.org/?probe=707fd0c687) | Dec 02, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [80be39f0d4](https://linux-hardware.org/?probe=80be39f0d4) | Dec 01, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [bb2313602b](https://linux-hardware.org/?probe=bb2313602b) | Nov 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [933ce1aa7d](https://linux-hardware.org/?probe=933ce1aa7d) | Nov 27, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6005ac3fdd](https://linux-hardware.org/?probe=6005ac3fdd) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [5b41f73363](https://linux-hardware.org/?probe=5b41f73363) | Nov 25, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [4f1442fcc4](https://linux-hardware.org/?probe=4f1442fcc4) | Nov 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f17333cca3](https://linux-hardware.org/?probe=f17333cca3) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f3956e461c](https://linux-hardware.org/?probe=f3956e461c) | Nov 23, 2023 |
| ASUSTek       | X456UV                      | Notebook    | [f38105228e](https://linux-hardware.org/?probe=f38105228e) | Nov 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f8778aa9e9](https://linux-hardware.org/?probe=f8778aa9e9) | Nov 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [94962a7ceb](https://linux-hardware.org/?probe=94962a7ceb) | Nov 19, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [b05c08e4ab](https://linux-hardware.org/?probe=b05c08e4ab) | Nov 17, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5077cde917](https://linux-hardware.org/?probe=5077cde917) | Nov 16, 2023 |
| ECS           | H77H2-EM                    | Desktop     | [20c68c0667](https://linux-hardware.org/?probe=20c68c0667) | Nov 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4c653190f6](https://linux-hardware.org/?probe=4c653190f6) | Nov 14, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [707f319e17](https://linux-hardware.org/?probe=707f319e17) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | Notebook    | [4bf49cfb42](https://linux-hardware.org/?probe=4bf49cfb42) | Nov 11, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [3f794fd46d](https://linux-hardware.org/?probe=3f794fd46d) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2c921ede59](https://linux-hardware.org/?probe=2c921ede59) | Nov 08, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [54d6d39995](https://linux-hardware.org/?probe=54d6d39995) | Nov 07, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [7971055e99](https://linux-hardware.org/?probe=7971055e99) | Nov 06, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [fc242f51bf](https://linux-hardware.org/?probe=fc242f51bf) | Nov 05, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [70a66852db](https://linux-hardware.org/?probe=70a66852db) | Nov 05, 2023 |
| HP            | ENVY 15                     | Notebook    | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Dell          | Latitude 7290               | Notebook    | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [98c2ece6fd](https://linux-hardware.org/?probe=98c2ece6fd) | Oct 28, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [8c6cbf3608](https://linux-hardware.org/?probe=8c6cbf3608) | Oct 27, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [354a804750](https://linux-hardware.org/?probe=354a804750) | Oct 27, 2023 |
| Foxconn       | P35A01                      | Desktop     | [e63e8acdaa](https://linux-hardware.org/?probe=e63e8acdaa) | Oct 27, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [e0534a1c2a](https://linux-hardware.org/?probe=e0534a1c2a) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c4b4502472](https://linux-hardware.org/?probe=c4b4502472) | Oct 20, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [464e218144](https://linux-hardware.org/?probe=464e218144) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [19d60d452f](https://linux-hardware.org/?probe=19d60d452f) | Oct 17, 2023 |
| Lenovo        | E41-50 82HW                 | Notebook    | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [1014c56a70](https://linux-hardware.org/?probe=1014c56a70) | Oct 10, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| MSI           | MS-7392                     | Desktop     | [5107ce50a1](https://linux-hardware.org/?probe=5107ce50a1) | Oct 09, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [8c4bcd5155](https://linux-hardware.org/?probe=8c4bcd5155) | Oct 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [26247d8807](https://linux-hardware.org/?probe=26247d8807) | Oct 05, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [965f7580d3](https://linux-hardware.org/?probe=965f7580d3) | Oct 05, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [06c1e095a7](https://linux-hardware.org/?probe=06c1e095a7) | Oct 03, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [0babc8185b](https://linux-hardware.org/?probe=0babc8185b) | Oct 03, 2023 |
| Toshiba       | Satellite C845D             | Notebook    | [92651c9e51](https://linux-hardware.org/?probe=92651c9e51) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e7fb14ee98](https://linux-hardware.org/?probe=e7fb14ee98) | Sep 28, 2023 |
| HP            | 2ADE                        | Desktop     | [b701a5c589](https://linux-hardware.org/?probe=b701a5c589) | Sep 27, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [91e89424ef](https://linux-hardware.org/?probe=91e89424ef) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| Lenovo        | ThinkPad Edge E431 62778... | Notebook    | [31b0e8e9ce](https://linux-hardware.org/?probe=31b0e8e9ce) | Sep 24, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [f4a96c9156](https://linux-hardware.org/?probe=f4a96c9156) | Sep 24, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b61b5cb7e3](https://linux-hardware.org/?probe=b61b5cb7e3) | Sep 23, 2023 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [05ef373ef0](https://linux-hardware.org/?probe=05ef373ef0) | Sep 23, 2023 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [a57b236842](https://linux-hardware.org/?probe=a57b236842) | Sep 23, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [f4d4f80645](https://linux-hardware.org/?probe=f4d4f80645) | Sep 20, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [50023a1d3a](https://linux-hardware.org/?probe=50023a1d3a) | Sep 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [68c0d7834d](https://linux-hardware.org/?probe=68c0d7834d) | Sep 18, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [a44de9f197](https://linux-hardware.org/?probe=a44de9f197) | Sep 15, 2023 |
| HP            | 0A60h                       | Desktop     | [107f849e6b](https://linux-hardware.org/?probe=107f849e6b) | Sep 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [62375851b3](https://linux-hardware.org/?probe=62375851b3) | Sep 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [c87b0b463c](https://linux-hardware.org/?probe=c87b0b463c) | Sep 13, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [f1cff1b2ac](https://linux-hardware.org/?probe=f1cff1b2ac) | Sep 11, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [f7eae2e7c4](https://linux-hardware.org/?probe=f7eae2e7c4) | Sep 09, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [aa2d2a4c29](https://linux-hardware.org/?probe=aa2d2a4c29) | Sep 08, 2023 |
| HP            | 2ADE                        | Desktop     | [f7b01f93c4](https://linux-hardware.org/?probe=f7b01f93c4) | Sep 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d075cbe2e0](https://linux-hardware.org/?probe=d075cbe2e0) | Sep 04, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [2c90811519](https://linux-hardware.org/?probe=2c90811519) | Sep 03, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c0af84c629](https://linux-hardware.org/?probe=c0af84c629) | Sep 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ab39767c20](https://linux-hardware.org/?probe=ab39767c20) | Sep 02, 2023 |
| Lenovo        | ThinkPad X201 3680KS9       | Notebook    | [561d8c3891](https://linux-hardware.org/?probe=561d8c3891) | Sep 02, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [52e8a720ba](https://linux-hardware.org/?probe=52e8a720ba) | Sep 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e3433226b](https://linux-hardware.org/?probe=3e3433226b) | Sep 01, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0c46e2d419](https://linux-hardware.org/?probe=0c46e2d419) | Aug 26, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [6554eecc36](https://linux-hardware.org/?probe=6554eecc36) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [0b3afd5dce](https://linux-hardware.org/?probe=0b3afd5dce) | Aug 24, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [4d1d53f6d8](https://linux-hardware.org/?probe=4d1d53f6d8) | Aug 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [fa5d7d5547](https://linux-hardware.org/?probe=fa5d7d5547) | Aug 23, 2023 |
| ASUSTek       | ROG Strix G531GU_G531GU     | Notebook    | [627606b933](https://linux-hardware.org/?probe=627606b933) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1b985f59a1](https://linux-hardware.org/?probe=1b985f59a1) | Aug 21, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [272e3307fe](https://linux-hardware.org/?probe=272e3307fe) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [e84eba7c7d](https://linux-hardware.org/?probe=e84eba7c7d) | Aug 20, 2023 |
| Acer          | TravelMate P645-S           | Notebook    | [658d88e2a5](https://linux-hardware.org/?probe=658d88e2a5) | Aug 20, 2023 |
| HP            | Pavilion dv4                | Notebook    | [5f1e0c4484](https://linux-hardware.org/?probe=5f1e0c4484) | Aug 19, 2023 |
| HP            | 435                         | Notebook    | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [dbdb6ca163](https://linux-hardware.org/?probe=dbdb6ca163) | Aug 17, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [3151636f73](https://linux-hardware.org/?probe=3151636f73) | Aug 16, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [a9d7216b70](https://linux-hardware.org/?probe=a9d7216b70) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [c27b841a97](https://linux-hardware.org/?probe=c27b841a97) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [5c55416a18](https://linux-hardware.org/?probe=5c55416a18) | Aug 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4404dc3287](https://linux-hardware.org/?probe=4404dc3287) | Aug 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [b691f28c43](https://linux-hardware.org/?probe=b691f28c43) | Aug 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [84d6b99d2c](https://linux-hardware.org/?probe=84d6b99d2c) | Aug 10, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| Lenovo        | G460 20041                  | Notebook    | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| HP            | Compaq 15                   | Notebook    | [387a3b8af2](https://linux-hardware.org/?probe=387a3b8af2) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f8f4442b09](https://linux-hardware.org/?probe=f8f4442b09) | Aug 05, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [b8f1735d23](https://linux-hardware.org/?probe=b8f1735d23) | Aug 04, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [6a6f453881](https://linux-hardware.org/?probe=6a6f453881) | Aug 02, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [fda8d0a543](https://linux-hardware.org/?probe=fda8d0a543) | Aug 02, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [752821ae1a](https://linux-hardware.org/?probe=752821ae1a) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [b847ac4535](https://linux-hardware.org/?probe=b847ac4535) | Aug 01, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680KS9       | Notebook    | [968bd5d46b](https://linux-hardware.org/?probe=968bd5d46b) | Jul 30, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [d9c029afa4](https://linux-hardware.org/?probe=d9c029afa4) | Jul 28, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [ba47e8e20f](https://linux-hardware.org/?probe=ba47e8e20f) | Jul 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2ca3c71f4a](https://linux-hardware.org/?probe=2ca3c71f4a) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [19aa0d748d](https://linux-hardware.org/?probe=19aa0d748d) | Jul 24, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [5300c80b7e](https://linux-hardware.org/?probe=5300c80b7e) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [ec2be7713c](https://linux-hardware.org/?probe=ec2be7713c) | Jul 22, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [b754fb3410](https://linux-hardware.org/?probe=b754fb3410) | Jul 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [d163198c13](https://linux-hardware.org/?probe=d163198c13) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [35d1400354](https://linux-hardware.org/?probe=35d1400354) | Jul 20, 2023 |
| Dell          | Latitude E6410              | Notebook    | [2a09336b72](https://linux-hardware.org/?probe=2a09336b72) | Jul 20, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [64b51936ea](https://linux-hardware.org/?probe=64b51936ea) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [ab65cec6fe](https://linux-hardware.org/?probe=ab65cec6fe) | Jul 19, 2023 |
| Lenovo        | M490s 20215                 | Notebook    | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e056c22283](https://linux-hardware.org/?probe=e056c22283) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [48b3d62237](https://linux-hardware.org/?probe=48b3d62237) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [d477369e7e](https://linux-hardware.org/?probe=d477369e7e) | Jul 14, 2023 |
| HP            | 83EB                        | All in one  | [9a1012bd0d](https://linux-hardware.org/?probe=9a1012bd0d) | Jul 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6c541c67b9](https://linux-hardware.org/?probe=6c541c67b9) | Jul 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [110622383d](https://linux-hardware.org/?probe=110622383d) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [eb024b5188](https://linux-hardware.org/?probe=eb024b5188) | Jul 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [52fafabf05](https://linux-hardware.org/?probe=52fafabf05) | Jul 10, 2023 |
| MSI           | H81M-E33                    | Desktop     | [804d078deb](https://linux-hardware.org/?probe=804d078deb) | Jul 10, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [275acaaa00](https://linux-hardware.org/?probe=275acaaa00) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | Notebook    | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [48195d85f8](https://linux-hardware.org/?probe=48195d85f8) | Jul 02, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [189320a2cf](https://linux-hardware.org/?probe=189320a2cf) | Jul 01, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8a0d6c1825](https://linux-hardware.org/?probe=8a0d6c1825) | Jun 29, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f72fe64697](https://linux-hardware.org/?probe=f72fe64697) | Jun 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d2a1351f86](https://linux-hardware.org/?probe=d2a1351f86) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [7487f61ff1](https://linux-hardware.org/?probe=7487f61ff1) | Jun 26, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [dfeaf221e6](https://linux-hardware.org/?probe=dfeaf221e6) | Jun 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS02V0... | Notebook    | [bed60c3010](https://linux-hardware.org/?probe=bed60c3010) | Jun 21, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [b3ce37b2cb](https://linux-hardware.org/?probe=b3ce37b2cb) | Jun 21, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| HP            | Compaq 15                   | Notebook    | [d89a75cb42](https://linux-hardware.org/?probe=d89a75cb42) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [34610e62fe](https://linux-hardware.org/?probe=34610e62fe) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [bd4abe1a68](https://linux-hardware.org/?probe=bd4abe1a68) | Jun 18, 2023 |
| HP            | Compaq 15                   | Notebook    | [a60f50ade5](https://linux-hardware.org/?probe=a60f50ade5) | Jun 18, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7e8ae5cb7a](https://linux-hardware.org/?probe=7e8ae5cb7a) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [63ded73edb](https://linux-hardware.org/?probe=63ded73edb) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [fb57cc3ed4](https://linux-hardware.org/?probe=fb57cc3ed4) | Jun 13, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [b00b3b8570](https://linux-hardware.org/?probe=b00b3b8570) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eb6dc5143e](https://linux-hardware.org/?probe=eb6dc5143e) | Jun 12, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [90bcfaba60](https://linux-hardware.org/?probe=90bcfaba60) | Jun 12, 2023 |
| Unknown       | Unknown                     | Tablet      | [f9d086b77c](https://linux-hardware.org/?probe=f9d086b77c) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [758afab931](https://linux-hardware.org/?probe=758afab931) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [246facab73](https://linux-hardware.org/?probe=246facab73) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [233dac6c68](https://linux-hardware.org/?probe=233dac6c68) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [eda13b898c](https://linux-hardware.org/?probe=eda13b898c) | Jun 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [3776ac93b3](https://linux-hardware.org/?probe=3776ac93b3) | Jun 08, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9c9fb1b1a6](https://linux-hardware.org/?probe=9c9fb1b1a6) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [829839a3b3](https://linux-hardware.org/?probe=829839a3b3) | Jun 07, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [beb59fa1d1](https://linux-hardware.org/?probe=beb59fa1d1) | Jun 07, 2023 |
| ASRock        | Z590 Phantom Gaming 4       | Desktop     | [1e9eef0102](https://linux-hardware.org/?probe=1e9eef0102) | Jun 03, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [25ffe9ad37](https://linux-hardware.org/?probe=25ffe9ad37) | Jun 03, 2023 |
| SK hynix      | HyBook                      | Notebook    | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [f1e9073b3d](https://linux-hardware.org/?probe=f1e9073b3d) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [2f61fcf47d](https://linux-hardware.org/?probe=2f61fcf47d) | May 31, 2023 |
| HP            | 2B07                        | All in one  | [19be50fbca](https://linux-hardware.org/?probe=19be50fbca) | May 30, 2023 |
| HP            | 2B07                        | All in one  | [a9392cd6cf](https://linux-hardware.org/?probe=a9392cd6cf) | May 30, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [882f43330b](https://linux-hardware.org/?probe=882f43330b) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [46f455ce35](https://linux-hardware.org/?probe=46f455ce35) | May 30, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [5ee0afea25](https://linux-hardware.org/?probe=5ee0afea25) | May 25, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3cb0dd251d](https://linux-hardware.org/?probe=3cb0dd251d) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f69b95b887](https://linux-hardware.org/?probe=f69b95b887) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [8aaec63d14](https://linux-hardware.org/?probe=8aaec63d14) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [f3724cb7da](https://linux-hardware.org/?probe=f3724cb7da) | May 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ffa28e78e](https://linux-hardware.org/?probe=8ffa28e78e) | May 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33a9b42068](https://linux-hardware.org/?probe=33a9b42068) | May 15, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Intel         | H61                         | Desktop     | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | Desktop     | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Latitude 5480               | Notebook    | [eb671ee7d2](https://linux-hardware.org/?probe=eb671ee7d2) | May 11, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [76f23f434d](https://linux-hardware.org/?probe=76f23f434d) | May 10, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [ce0391bdee](https://linux-hardware.org/?probe=ce0391bdee) | May 09, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ce04ace3b3](https://linux-hardware.org/?probe=ce04ace3b3) | May 09, 2023 |
| SK hynix      | HyBook Plus                 | Notebook    | [817a46f154](https://linux-hardware.org/?probe=817a46f154) | May 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [d0eb83c0af](https://linux-hardware.org/?probe=d0eb83c0af) | May 07, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0BB0... | Notebook    | [881068ac47](https://linux-hardware.org/?probe=881068ac47) | May 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e3dd9f70f6](https://linux-hardware.org/?probe=e3dd9f70f6) | May 04, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [29f68ce8d7](https://linux-hardware.org/?probe=29f68ce8d7) | May 03, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [c8b7ffa6dc](https://linux-hardware.org/?probe=c8b7ffa6dc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8fea3db366](https://linux-hardware.org/?probe=8fea3db366) | May 02, 2023 |
| Toshiba       | Satellite L45               | Notebook    | [044db31897](https://linux-hardware.org/?probe=044db31897) | May 02, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [d44b4f12a5](https://linux-hardware.org/?probe=d44b4f12a5) | May 01, 2023 |
| Lenovo        | B490 20205                  | Notebook    | [c786307607](https://linux-hardware.org/?probe=c786307607) | May 01, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [611ed4a200](https://linux-hardware.org/?probe=611ed4a200) | May 01, 2023 |
| HP            | Compaq 15                   | Notebook    | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6A0LJCL    | Notebook    | [f67154866c](https://linux-hardware.org/?probe=f67154866c) | May 01, 2023 |
| Lenovo        | B490 20205                  | Notebook    | [bc1fdb2575](https://linux-hardware.org/?probe=bc1fdb2575) | May 01, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [bba2f8d1ad](https://linux-hardware.org/?probe=bba2f8d1ad) | Apr 30, 2023 |
| Toshiba       | PORTEGE R830                | Notebook    | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ed7c1abb38](https://linux-hardware.org/?probe=ed7c1abb38) | Apr 28, 2023 |
| HP            | ENVY 15                     | Notebook    | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1287b17594](https://linux-hardware.org/?probe=1287b17594) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [37f98c9450](https://linux-hardware.org/?probe=37f98c9450) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [ebe7f36c99](https://linux-hardware.org/?probe=ebe7f36c99) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4286A44       | Notebook    | [6b6e909d11](https://linux-hardware.org/?probe=6b6e909d11) | Apr 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e72f221b5b](https://linux-hardware.org/?probe=e72f221b5b) | Apr 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1950979b24](https://linux-hardware.org/?probe=1950979b24) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| HP            | Notebook                    | Notebook    | [31d24dfe38](https://linux-hardware.org/?probe=31d24dfe38) | Apr 21, 2023 |
| Dell          | G15 5510                    | Notebook    | [43d4ce3c37](https://linux-hardware.org/?probe=43d4ce3c37) | Apr 21, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [a7b05c2528](https://linux-hardware.org/?probe=a7b05c2528) | Apr 20, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [5262a186b5](https://linux-hardware.org/?probe=5262a186b5) | Apr 20, 2023 |
| WZA300S2R1... | SA300-D4                    | Desktop     | [e2a6ae91b9](https://linux-hardware.org/?probe=e2a6ae91b9) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Lenovo        | G405 20239                  | Notebook    | [e79c183bde](https://linux-hardware.org/?probe=e79c183bde) | Apr 17, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [19b858e5f8](https://linux-hardware.org/?probe=19b858e5f8) | Apr 16, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [eb800f7d1b](https://linux-hardware.org/?probe=eb800f7d1b) | Apr 14, 2023 |
| HP            | 8433 11                     | Desktop     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MS-7360                     | Desktop     | [48bee654fc](https://linux-hardware.org/?probe=48bee654fc) | Apr 13, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [22da370a63](https://linux-hardware.org/?probe=22da370a63) | Apr 08, 2023 |
| ASRock        | B360M/OEM                   | Desktop     | [d1feabb956](https://linux-hardware.org/?probe=d1feabb956) | Apr 07, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ff65115a04](https://linux-hardware.org/?probe=ff65115a04) | Apr 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [771f3d8665](https://linux-hardware.org/?probe=771f3d8665) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [712e78de35](https://linux-hardware.org/?probe=712e78de35) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [a7cb3cf668](https://linux-hardware.org/?probe=a7cb3cf668) | Apr 05, 2023 |
| Unknown       | X99-GT                      | Desktop     | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [16f81f8254](https://linux-hardware.org/?probe=16f81f8254) | Apr 05, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [ad6e45cead](https://linux-hardware.org/?probe=ad6e45cead) | Apr 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [4710939159](https://linux-hardware.org/?probe=4710939159) | Apr 05, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [4191279e7e](https://linux-hardware.org/?probe=4191279e7e) | Apr 01, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [27fbf62ba0](https://linux-hardware.org/?probe=27fbf62ba0) | Apr 01, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| HP            | 8433 11                     | Desktop     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [e9600e8bfe](https://linux-hardware.org/?probe=e9600e8bfe) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f7222bf293](https://linux-hardware.org/?probe=f7222bf293) | Mar 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [698b73783e](https://linux-hardware.org/?probe=698b73783e) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [036c2c771c](https://linux-hardware.org/?probe=036c2c771c) | Mar 23, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [2c25601c7c](https://linux-hardware.org/?probe=2c25601c7c) | Mar 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4cbcbc3025](https://linux-hardware.org/?probe=4cbcbc3025) | Mar 22, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| Dell          | G3 3590                     | Notebook    | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| HP            | 18E7                        | Desktop     | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [23c1be0005](https://linux-hardware.org/?probe=23c1be0005) | Mar 19, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| MSI           | MS-7360                     | Desktop     | [6c8cb5d98f](https://linux-hardware.org/?probe=6c8cb5d98f) | Mar 18, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [11b2e17886](https://linux-hardware.org/?probe=11b2e17886) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| Gear          | Geranium                    | Notebook    | [8567411d91](https://linux-hardware.org/?probe=8567411d91) | Mar 13, 2023 |
| Gear          | Geranium                    | Notebook    | [1303244018](https://linux-hardware.org/?probe=1303244018) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [322b5bf476](https://linux-hardware.org/?probe=322b5bf476) | Mar 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [87779bfdea](https://linux-hardware.org/?probe=87779bfdea) | Mar 11, 2023 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [9a61fd62b3](https://linux-hardware.org/?probe=9a61fd62b3) | Mar 05, 2023 |
| HP            | 339A                        | Desktop     | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Dell          | Latitude 5410               | Notebook    | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [76645fa513](https://linux-hardware.org/?probe=76645fa513) | Feb 28, 2023 |
| HP            | 240 G4 Notebook PC          | Notebook    | [02744836e7](https://linux-hardware.org/?probe=02744836e7) | Feb 28, 2023 |
| Dell          | G3 3590                     | Notebook    | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | System XPS L321X            | Notebook    | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| HP            | ProBook 4730s               | Notebook    | [6d563800a1](https://linux-hardware.org/?probe=6d563800a1) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| HP            | 15                          | Notebook    | [470b07302a](https://linux-hardware.org/?probe=470b07302a) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Samsung       | R430/P430                   | Notebook    | [3bbea19ca4](https://linux-hardware.org/?probe=3bbea19ca4) | Feb 21, 2023 |
| HP            | Pavilion x360 14 G1         | Convertible | [77d9445484](https://linux-hardware.org/?probe=77d9445484) | Feb 20, 2023 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [51a7f0e66d](https://linux-hardware.org/?probe=51a7f0e66d) | Feb 19, 2023 |
| HP            | 15                          | Notebook    | [60ecad0be7](https://linux-hardware.org/?probe=60ecad0be7) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [764c7eaffe](https://linux-hardware.org/?probe=764c7eaffe) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [6d64083839](https://linux-hardware.org/?probe=6d64083839) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [7857666504](https://linux-hardware.org/?probe=7857666504) | Feb 16, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e78a97227a](https://linux-hardware.org/?probe=e78a97227a) | Feb 15, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [45e719d7c0](https://linux-hardware.org/?probe=45e719d7c0) | Feb 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [247ab26b54](https://linux-hardware.org/?probe=247ab26b54) | Feb 14, 2023 |
| HP            | 14                          | Notebook    | [38554cf215](https://linux-hardware.org/?probe=38554cf215) | Feb 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [c3f554a4bf](https://linux-hardware.org/?probe=c3f554a4bf) | Feb 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [4ba93ea14d](https://linux-hardware.org/?probe=4ba93ea14d) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| HP            | 14                          | Notebook    | [610e26434d](https://linux-hardware.org/?probe=610e26434d) | Feb 12, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| HP            | 1850                        | Desktop     | [54f5b16151](https://linux-hardware.org/?probe=54f5b16151) | Feb 11, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3fce6d5f05](https://linux-hardware.org/?probe=3fce6d5f05) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [209a38d937](https://linux-hardware.org/?probe=209a38d937) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [1867884ede](https://linux-hardware.org/?probe=1867884ede) | Feb 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [104a086d29](https://linux-hardware.org/?probe=104a086d29) | Feb 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [578b166faa](https://linux-hardware.org/?probe=578b166faa) | Feb 05, 2023 |
| HP            | Presario CQ43               | Notebook    | [76bfeffd5f](https://linux-hardware.org/?probe=76bfeffd5f) | Feb 02, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [b3bb51473f](https://linux-hardware.org/?probe=b3bb51473f) | Feb 01, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | Desktop     | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| ViewSonic     | VOT132                      | Desktop     | [a8ecfadd53](https://linux-hardware.org/?probe=a8ecfadd53) | Jan 30, 2023 |
| HP            | Convertible x360 11-ab0X... | Convertible | [c56cc33809](https://linux-hardware.org/?probe=c56cc33809) | Jan 29, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Lenovo        | V14 G1 IML 82NA             | Notebook    | [c346600bdc](https://linux-hardware.org/?probe=c346600bdc) | Jan 25, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [cd487a22cd](https://linux-hardware.org/?probe=cd487a22cd) | Jan 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [30b373aafe](https://linux-hardware.org/?probe=30b373aafe) | Jan 25, 2023 |
| HP            | 2ADE                        | Desktop     | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Google        | Treeya                      | Notebook    | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [93db1bee75](https://linux-hardware.org/?probe=93db1bee75) | Jan 23, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| MSI           | H81M-E33                    | Desktop     | [ddb1be1cc6](https://linux-hardware.org/?probe=ddb1be1cc6) | Jan 18, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [a9cad4d873](https://linux-hardware.org/?probe=a9cad4d873) | Jan 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| ASUSTek       | Q325UA                      | Convertible | [1862534df3](https://linux-hardware.org/?probe=1862534df3) | Jan 13, 2023 |
| Acer          | Aspire 2920                 | Notebook    | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [1a68bed616](https://linux-hardware.org/?probe=1a68bed616) | Jan 12, 2023 |
| HP            | 83F2                        | Desktop     | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [247bb9fe04](https://linux-hardware.org/?probe=247bb9fe04) | Jan 10, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [6c7f37297d](https://linux-hardware.org/?probe=6c7f37297d) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [5729420a54](https://linux-hardware.org/?probe=5729420a54) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [3a3164f63f](https://linux-hardware.org/?probe=3a3164f63f) | Jan 04, 2023 |
| HP            | EliteBook 8740w (WH274UT... | Notebook    | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fdb827eff9](https://linux-hardware.org/?probe=fdb827eff9) | Dec 29, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [b593030fef](https://linux-hardware.org/?probe=b593030fef) | Dec 28, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [27e4ff648f](https://linux-hardware.org/?probe=27e4ff648f) | Dec 28, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [06d788f40a](https://linux-hardware.org/?probe=06d788f40a) | Dec 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6de981f1fc](https://linux-hardware.org/?probe=6de981f1fc) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [1397ed80b3](https://linux-hardware.org/?probe=1397ed80b3) | Dec 21, 2022 |
| HP            | 2B54 100                    | All in one  | [b47807a201](https://linux-hardware.org/?probe=b47807a201) | Dec 16, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Dell          | Inspiron 7380               | Notebook    | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [d41bef1f84](https://linux-hardware.org/?probe=d41bef1f84) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [9b714617c8](https://linux-hardware.org/?probe=9b714617c8) | Dec 04, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| ASUSTek       | K501UW                      | Notebook    | [1571941805](https://linux-hardware.org/?probe=1571941805) | Dec 03, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [aa9ad07031](https://linux-hardware.org/?probe=aa9ad07031) | Dec 01, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [703ef1c899](https://linux-hardware.org/?probe=703ef1c899) | Nov 30, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [f6745ce587](https://linux-hardware.org/?probe=f6745ce587) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [810ed5914a](https://linux-hardware.org/?probe=810ed5914a) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [509dfbf1a4](https://linux-hardware.org/?probe=509dfbf1a4) | Nov 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [68e1087fde](https://linux-hardware.org/?probe=68e1087fde) | Nov 25, 2022 |
| Alienware     | M17xR3                      | Notebook    | [438f3639aa](https://linux-hardware.org/?probe=438f3639aa) | Nov 24, 2022 |
| HP            | 8309                        | Desktop     | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [0627894c6b](https://linux-hardware.org/?probe=0627894c6b) | Nov 18, 2022 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [12073cb314](https://linux-hardware.org/?probe=12073cb314) | Nov 16, 2022 |
| Sony          | SVE1411EGXB                 | Notebook    | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| HP            | Pavilion g4                 | Notebook    | [44162d8878](https://linux-hardware.org/?probe=44162d8878) | Nov 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [7f498c5723](https://linux-hardware.org/?probe=7f498c5723) | Nov 08, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [ece385acfe](https://linux-hardware.org/?probe=ece385acfe) | Nov 05, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7a183bdeb7](https://linux-hardware.org/?probe=7a183bdeb7) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [3bd662e577](https://linux-hardware.org/?probe=3bd662e577) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [4a158afdfd](https://linux-hardware.org/?probe=4a158afdfd) | Nov 02, 2022 |
| Sony          | VAIO                        | All in one  | [cefad415d0](https://linux-hardware.org/?probe=cefad415d0) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [15690a2198](https://linux-hardware.org/?probe=15690a2198) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [2e4c04ada0](https://linux-hardware.org/?probe=2e4c04ada0) | Oct 27, 2022 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [cb31f9ab8b](https://linux-hardware.org/?probe=cb31f9ab8b) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [3d3ac2530c](https://linux-hardware.org/?probe=3d3ac2530c) | Oct 25, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| HP            | 225E                        | Desktop     | [7e246d254b](https://linux-hardware.org/?probe=7e246d254b) | Oct 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| Google        | Treeya                      | Notebook    | [1a93d190b0](https://linux-hardware.org/?probe=1a93d190b0) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20JNS01R01    | Notebook    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [c2f91318fe](https://linux-hardware.org/?probe=c2f91318fe) | Oct 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b3c91d2b0](https://linux-hardware.org/?probe=2b3c91d2b0) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [e3dcca8113](https://linux-hardware.org/?probe=e3dcca8113) | Oct 11, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [593d28a4cf](https://linux-hardware.org/?probe=593d28a4cf) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [04e29685a6](https://linux-hardware.org/?probe=04e29685a6) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [2a8fd02f04](https://linux-hardware.org/?probe=2a8fd02f04) | Oct 07, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [6680cedc5e](https://linux-hardware.org/?probe=6680cedc5e) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55f843ecf6](https://linux-hardware.org/?probe=55f843ecf6) | Oct 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3bbd57ceea](https://linux-hardware.org/?probe=3bbd57ceea) | Oct 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5283dee456](https://linux-hardware.org/?probe=5283dee456) | Oct 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9a2de7b77f](https://linux-hardware.org/?probe=9a2de7b77f) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | Notebook    | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [4684b672f6](https://linux-hardware.org/?probe=4684b672f6) | Sep 30, 2022 |
| SK hynix      | HyBook                      | Notebook    | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [ce2d41ee99](https://linux-hardware.org/?probe=ce2d41ee99) | Sep 30, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [09795617ab](https://linux-hardware.org/?probe=09795617ab) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1570daf698](https://linux-hardware.org/?probe=1570daf698) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [58caf99a77](https://linux-hardware.org/?probe=58caf99a77) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [bd2dea6653](https://linux-hardware.org/?probe=bd2dea6653) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [2d55b9b35e](https://linux-hardware.org/?probe=2d55b9b35e) | Sep 28, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [cf179c716e](https://linux-hardware.org/?probe=cf179c716e) | Sep 27, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [7dc3fbcf76](https://linux-hardware.org/?probe=7dc3fbcf76) | Sep 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Sony          | VAIO                        | All in one  | [0e3271f88f](https://linux-hardware.org/?probe=0e3271f88f) | Sep 19, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [277daa8d6d](https://linux-hardware.org/?probe=277daa8d6d) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [2ac6776181](https://linux-hardware.org/?probe=2ac6776181) | Sep 13, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [7ec64e9e08](https://linux-hardware.org/?probe=7ec64e9e08) | Sep 13, 2022 |
| Dell          | 060K5C A00                  | Desktop     | [a64a44387b](https://linux-hardware.org/?probe=a64a44387b) | Sep 13, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6f309073f2](https://linux-hardware.org/?probe=6f309073f2) | Sep 11, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [c1a16c7963](https://linux-hardware.org/?probe=c1a16c7963) | Sep 06, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [2ae4968612](https://linux-hardware.org/?probe=2ae4968612) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2176e4d70f](https://linux-hardware.org/?probe=2176e4d70f) | Sep 05, 2022 |
| ECS           | H61H-G11/7.0                | Desktop     | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | Notebook    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ec88b5b492](https://linux-hardware.org/?probe=ec88b5b492) | Sep 02, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8e1734f31a](https://linux-hardware.org/?probe=8e1734f31a) | Sep 01, 2022 |
| SZMZ          | X99M-G2                     | Desktop     | [eff1231310](https://linux-hardware.org/?probe=eff1231310) | Aug 31, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [93f28535f8](https://linux-hardware.org/?probe=93f28535f8) | Aug 23, 2022 |
| MSI           | H81M-E33                    | Desktop     | [56808775ee](https://linux-hardware.org/?probe=56808775ee) | Aug 23, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| HP            | Pavilion g4                 | Notebook    | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| Intel         | X79M-S                      | Desktop     | [b6746f7b8d](https://linux-hardware.org/?probe=b6746f7b8d) | Aug 18, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [9ee2e85959](https://linux-hardware.org/?probe=9ee2e85959) | Aug 14, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [51cc14cc1f](https://linux-hardware.org/?probe=51cc14cc1f) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3db0355713](https://linux-hardware.org/?probe=3db0355713) | Aug 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [818d0c73e8](https://linux-hardware.org/?probe=818d0c73e8) | Aug 12, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | Notebook    | [541d75d7ee](https://linux-hardware.org/?probe=541d75d7ee) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | Notebook    | [77b260c9f1](https://linux-hardware.org/?probe=77b260c9f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f9efd8697b](https://linux-hardware.org/?probe=f9efd8697b) | Aug 11, 2022 |
| HP            | 240 G3                      | Notebook    | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [832967e639](https://linux-hardware.org/?probe=832967e639) | Aug 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [18b6026d87](https://linux-hardware.org/?probe=18b6026d87) | Aug 09, 2022 |
| Google        | Treeya                      | Notebook    | [11f77c6171](https://linux-hardware.org/?probe=11f77c6171) | Aug 08, 2022 |
| Render        | NOTEBOOK Revision A         | Notebook    | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| MOTILE        | M141                        | Notebook    | [7cdc678c70](https://linux-hardware.org/?probe=7cdc678c70) | Aug 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Sony          | VPCEA45FL                   | Notebook    | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a58ae4eb60](https://linux-hardware.org/?probe=a58ae4eb60) | Jul 24, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Samsung       | 750XED                      | Notebook    | [546562ffbb](https://linux-hardware.org/?probe=546562ffbb) | Jul 21, 2022 |
| Olidata       | Unknown                     | Desktop     | [ac7a530d9d](https://linux-hardware.org/?probe=ac7a530d9d) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Dell          | MXG061                      | Notebook    | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [8a0a0ed167](https://linux-hardware.org/?probe=8a0a0ed167) | Jul 16, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [e94723280f](https://linux-hardware.org/?probe=e94723280f) | Jul 16, 2022 |
| Samsung       | 750XED                      | Notebook    | [eb7c27f7ff](https://linux-hardware.org/?probe=eb7c27f7ff) | Jul 15, 2022 |
| HP            | Pavilion g4                 | Notebook    | [40067cace0](https://linux-hardware.org/?probe=40067cace0) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | Notebook    | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| HP            | Notebook                    | Notebook    | [1358a12fdf](https://linux-hardware.org/?probe=1358a12fdf) | Jul 13, 2022 |
| HP            | Pavilion g4                 | Notebook    | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c96551a28](https://linux-hardware.org/?probe=0c96551a28) | Jul 09, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [f69a70c4b4](https://linux-hardware.org/?probe=f69a70c4b4) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | Notebook    | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [bcb40b4a21](https://linux-hardware.org/?probe=bcb40b4a21) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [de014d917d](https://linux-hardware.org/?probe=de014d917d) | Jul 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [03dd055ce5](https://linux-hardware.org/?probe=03dd055ce5) | Jun 30, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [5b8770aaf7](https://linux-hardware.org/?probe=5b8770aaf7) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [d80f5059d2](https://linux-hardware.org/?probe=d80f5059d2) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [89b9650228](https://linux-hardware.org/?probe=89b9650228) | Jun 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b56f69ff9c](https://linux-hardware.org/?probe=b56f69ff9c) | Jun 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Samsung       | 750XED                      | Notebook    | [49322b3456](https://linux-hardware.org/?probe=49322b3456) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Packard Be... | EasyNote MH36               | Notebook    | [ecd7a50e8e](https://linux-hardware.org/?probe=ecd7a50e8e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [234a9c1523](https://linux-hardware.org/?probe=234a9c1523) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [f5d7a0bba4](https://linux-hardware.org/?probe=f5d7a0bba4) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| Sony          | VPCM120AL                   | Notebook    | [9eb0e19bd0](https://linux-hardware.org/?probe=9eb0e19bd0) | Jun 13, 2022 |
| HP            | 240 G7                      | Notebook    | [2af5911cf8](https://linux-hardware.org/?probe=2af5911cf8) | Jun 12, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| HP            | 240 G7                      | Notebook    | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [576c9acdaa](https://linux-hardware.org/?probe=576c9acdaa) | Jun 08, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83b786e73a](https://linux-hardware.org/?probe=83b786e73a) | Jun 04, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [b1fe95fd93](https://linux-hardware.org/?probe=b1fe95fd93) | May 31, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [4ad762abcb](https://linux-hardware.org/?probe=4ad762abcb) | May 31, 2022 |
| ECS           | MCP61M-M3                   | Desktop     | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b7b419d941](https://linux-hardware.org/?probe=b7b419d941) | May 28, 2022 |
| HP            | 240 G7                      | Notebook    | [687546391a](https://linux-hardware.org/?probe=687546391a) | May 23, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [73bd0df4ae](https://linux-hardware.org/?probe=73bd0df4ae) | May 19, 2022 |
| Unknown       | Unknown                     | Notebook    | [834d86e9da](https://linux-hardware.org/?probe=834d86e9da) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [713dcb3d05](https://linux-hardware.org/?probe=713dcb3d05) | May 17, 2022 |
| HP            | 2ADE                        | Desktop     | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [be93982cf0](https://linux-hardware.org/?probe=be93982cf0) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [84ae0966e6](https://linux-hardware.org/?probe=84ae0966e6) | May 15, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f2f965ba56](https://linux-hardware.org/?probe=f2f965ba56) | May 13, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | Notebook    | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [207110a3d4](https://linux-hardware.org/?probe=207110a3d4) | May 07, 2022 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [21e4e874a2](https://linux-hardware.org/?probe=21e4e874a2) | May 06, 2022 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [37e77cbfe5](https://linux-hardware.org/?probe=37e77cbfe5) | May 06, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [cd1e81afae](https://linux-hardware.org/?probe=cd1e81afae) | May 03, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [bf6d6784ab](https://linux-hardware.org/?probe=bf6d6784ab) | May 03, 2022 |
| MSI           | B450M BAZOOKA               | Desktop     | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | Desktop     | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [0fa0b3d5f4](https://linux-hardware.org/?probe=0fa0b3d5f4) | May 01, 2022 |
| Lenovo        | ThinkPad T61 7659A39        | Notebook    | [e5c32846e2](https://linux-hardware.org/?probe=e5c32846e2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | Notebook    | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| HP            | Pavilion 14                 | Notebook    | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [f40f12b9be](https://linux-hardware.org/?probe=f40f12b9be) | Apr 27, 2022 |
| Intel         | Unknown                     | Notebook    | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [6dac014a49](https://linux-hardware.org/?probe=6dac014a49) | Apr 22, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [d103edc70e](https://linux-hardware.org/?probe=d103edc70e) | Apr 21, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [e5d8c4e246](https://linux-hardware.org/?probe=e5d8c4e246) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [cb4bc274b3](https://linux-hardware.org/?probe=cb4bc274b3) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [c83cb969dc](https://linux-hardware.org/?probe=c83cb969dc) | Apr 19, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [79eb10a5ef](https://linux-hardware.org/?probe=79eb10a5ef) | Apr 19, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d0cde0bcd](https://linux-hardware.org/?probe=7d0cde0bcd) | Apr 13, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| ASUSTek       | X405UQ                      | Notebook    | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [f531f62c1b](https://linux-hardware.org/?probe=f531f62c1b) | Apr 03, 2022 |
| Dell          | Vostro A860                 | Notebook    | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | 1998                        | Desktop     | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [e02f2032f1](https://linux-hardware.org/?probe=e02f2032f1) | Mar 28, 2022 |
| Dell          | Latitude E5450              | Notebook    | [776f0672a0](https://linux-hardware.org/?probe=776f0672a0) | Mar 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [fb7f18d5a2](https://linux-hardware.org/?probe=fb7f18d5a2) | Mar 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9183654349](https://linux-hardware.org/?probe=9183654349) | Mar 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [95acb8d0af](https://linux-hardware.org/?probe=95acb8d0af) | Mar 21, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [baae82b163](https://linux-hardware.org/?probe=baae82b163) | Mar 19, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [539ebb7dd9](https://linux-hardware.org/?probe=539ebb7dd9) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [82cfb46909](https://linux-hardware.org/?probe=82cfb46909) | Mar 13, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [671a3fc70b](https://linux-hardware.org/?probe=671a3fc70b) | Mar 12, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [379733b3e7](https://linux-hardware.org/?probe=379733b3e7) | Mar 07, 2022 |
| Elife         | series                      | Notebook    | [dddf04aa69](https://linux-hardware.org/?probe=dddf04aa69) | Mar 05, 2022 |
| Elife         | series                      | Notebook    | [979e43c05a](https://linux-hardware.org/?probe=979e43c05a) | Mar 05, 2022 |
| HP            | 2140                        | Notebook    | [6956607bfd](https://linux-hardware.org/?probe=6956607bfd) | Mar 02, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [332a3f936b](https://linux-hardware.org/?probe=332a3f936b) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2f1bb56767](https://linux-hardware.org/?probe=2f1bb56767) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | Notebook    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Sony          | VAIO                        | All in one  | [4d477a343a](https://linux-hardware.org/?probe=4d477a343a) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [8dfdb07f98](https://linux-hardware.org/?probe=8dfdb07f98) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | Notebook    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| Google        | Barla                       | Notebook    | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [16e608fb6b](https://linux-hardware.org/?probe=16e608fb6b) | Feb 22, 2022 |
| HP            | ENVY 15                     | Notebook    | [9758bb9b66](https://linux-hardware.org/?probe=9758bb9b66) | Feb 20, 2022 |
| Dell          | 0CT017                      | Desktop     | [27a31fcb1b](https://linux-hardware.org/?probe=27a31fcb1b) | Feb 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [46021e669f](https://linux-hardware.org/?probe=46021e669f) | Feb 17, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4de3659979](https://linux-hardware.org/?probe=4de3659979) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [309f440466](https://linux-hardware.org/?probe=309f440466) | Feb 15, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [81f2a365be](https://linux-hardware.org/?probe=81f2a365be) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [18fa19a4f0](https://linux-hardware.org/?probe=18fa19a4f0) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [824518037a](https://linux-hardware.org/?probe=824518037a) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [3c0ad9ce1b](https://linux-hardware.org/?probe=3c0ad9ce1b) | Feb 08, 2022 |
| MSI           | H310M GAMING ARCTIC         | Desktop     | [842ee88335](https://linux-hardware.org/?probe=842ee88335) | Jan 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| Lenovo        | G400 20235                  | Notebook    | [cba5cda239](https://linux-hardware.org/?probe=cba5cda239) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [c00dd7c570](https://linux-hardware.org/?probe=c00dd7c570) | Jan 18, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [ca729da91f](https://linux-hardware.org/?probe=ca729da91f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | Notebook    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Acer          | AOD255E                     | Notebook    | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [edc40344ef](https://linux-hardware.org/?probe=edc40344ef) | Jan 08, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [979f80197d](https://linux-hardware.org/?probe=979f80197d) | Jan 07, 2022 |
| MSI           | B85M-E33 V2                 | Desktop     | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| Google        | Barla                       | Notebook    | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Google        | Barla                       | Notebook    | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| Samsung       | R510/P510                   | Notebook    | [37a9793570](https://linux-hardware.org/?probe=37a9793570) | Dec 08, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Samsung       | R510/P510                   | Notebook    | [f55c0c88cc](https://linux-hardware.org/?probe=f55c0c88cc) | Dec 07, 2021 |
| Lenovo        | ThinkPad T460 20FMA03MCL    | Notebook    | [aecb392c83](https://linux-hardware.org/?probe=aecb392c83) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [18da52385a](https://linux-hardware.org/?probe=18da52385a) | Dec 04, 2021 |
| MSI           | 3664h                       | Desktop     | [c4bc6c8049](https://linux-hardware.org/?probe=c4bc6c8049) | Nov 29, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [6490a6beba](https://linux-hardware.org/?probe=6490a6beba) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | Notebook    | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [489679b294](https://linux-hardware.org/?probe=489679b294) | Nov 27, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [e9b3a62560](https://linux-hardware.org/?probe=e9b3a62560) | Nov 26, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [93b6cabcb6](https://linux-hardware.org/?probe=93b6cabcb6) | Nov 25, 2021 |
| HP            | 245 G6                      | Notebook    | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| Acer          | Aspire V5-471P              | Notebook    | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [befb5b9afe](https://linux-hardware.org/?probe=befb5b9afe) | Nov 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [787fc2d581](https://linux-hardware.org/?probe=787fc2d581) | Nov 18, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d26e2fac89](https://linux-hardware.org/?probe=d26e2fac89) | Nov 17, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2bca77430e](https://linux-hardware.org/?probe=2bca77430e) | Nov 14, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | Notebook    | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [a61385548e](https://linux-hardware.org/?probe=a61385548e) | Nov 13, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [8b26cea464](https://linux-hardware.org/?probe=8b26cea464) | Nov 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [835c948f68](https://linux-hardware.org/?probe=835c948f68) | Nov 13, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| HP            | 2215                        | Desktop     | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c0671f26c9](https://linux-hardware.org/?probe=c0671f26c9) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1dd0c3ba0a](https://linux-hardware.org/?probe=1dd0c3ba0a) | Nov 05, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d6eff141a3](https://linux-hardware.org/?probe=d6eff141a3) | Nov 04, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e53f2b7fd5](https://linux-hardware.org/?probe=e53f2b7fd5) | Nov 03, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [922c058537](https://linux-hardware.org/?probe=922c058537) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [befb41472e](https://linux-hardware.org/?probe=befb41472e) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3f67c7622c](https://linux-hardware.org/?probe=3f67c7622c) | Oct 22, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| Nvidia        | NF-MCP61                    | Desktop     | [666f204c08](https://linux-hardware.org/?probe=666f204c08) | Oct 18, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7076268ecc](https://linux-hardware.org/?probe=7076268ecc) | Oct 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7524634b9](https://linux-hardware.org/?probe=f7524634b9) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [e51cebc629](https://linux-hardware.org/?probe=e51cebc629) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [18a1e9d294](https://linux-hardware.org/?probe=18a1e9d294) | Oct 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [8f7c7a493b](https://linux-hardware.org/?probe=8f7c7a493b) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [06b7518f72](https://linux-hardware.org/?probe=06b7518f72) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [a0e3e93f48](https://linux-hardware.org/?probe=a0e3e93f48) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [ad35db71c7](https://linux-hardware.org/?probe=ad35db71c7) | Oct 12, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | Notebook    | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | Notebook    | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Alienware     | M17xR3                      | Notebook    | [740de1796c](https://linux-hardware.org/?probe=740de1796c) | Oct 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8ea6adfced](https://linux-hardware.org/?probe=8ea6adfced) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [3af223c792](https://linux-hardware.org/?probe=3af223c792) | Sep 30, 2021 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| Gigabyte      | A520M DS3H                  | Desktop     | [228b36fb26](https://linux-hardware.org/?probe=228b36fb26) | Sep 28, 2021 |
| Dell          | G3 3590                     | Notebook    | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | Notebook    | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99773cf00e](https://linux-hardware.org/?probe=99773cf00e) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [079bf76915](https://linux-hardware.org/?probe=079bf76915) | Sep 18, 2021 |
| ASRock        | Z490 Phantom Gaming 4G      | Desktop     | [7857ce2ffa](https://linux-hardware.org/?probe=7857ce2ffa) | Sep 16, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [ef87caa5ba](https://linux-hardware.org/?probe=ef87caa5ba) | Sep 12, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [27a6448b5e](https://linux-hardware.org/?probe=27a6448b5e) | Sep 12, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [e2df45f5f6](https://linux-hardware.org/?probe=e2df45f5f6) | Sep 12, 2021 |
| Intel         | X79M-S                      | Desktop     | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [feea6f3fec](https://linux-hardware.org/?probe=feea6f3fec) | Sep 11, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [36685ad5ea](https://linux-hardware.org/?probe=36685ad5ea) | Sep 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [890790d388](https://linux-hardware.org/?probe=890790d388) | Sep 07, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [341d88eae9](https://linux-hardware.org/?probe=341d88eae9) | Sep 07, 2021 |
| HP            | 339A                        | Desktop     | [ae80063e20](https://linux-hardware.org/?probe=ae80063e20) | Sep 07, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [14536c9a37](https://linux-hardware.org/?probe=14536c9a37) | Sep 06, 2021 |
| Intel         | X79M-S                      | Desktop     | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| HP            | 339A                        | Desktop     | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [3697a37403](https://linux-hardware.org/?probe=3697a37403) | Sep 04, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [e4d2306204](https://linux-hardware.org/?probe=e4d2306204) | Sep 04, 2021 |
| HP            | 339A                        | Desktop     | [2c96fd74fb](https://linux-hardware.org/?probe=2c96fd74fb) | Sep 04, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [f6df33267b](https://linux-hardware.org/?probe=f6df33267b) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | Notebook    | [436287e7dc](https://linux-hardware.org/?probe=436287e7dc) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | Notebook    | [a89f3e4acf](https://linux-hardware.org/?probe=a89f3e4acf) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [93a7aa0485](https://linux-hardware.org/?probe=93a7aa0485) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [190ef257e8](https://linux-hardware.org/?probe=190ef257e8) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | Notebook    | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a2afd00e64](https://linux-hardware.org/?probe=a2afd00e64) | Aug 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | Notebook    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| Sony          | VGN-NW215T                  | Notebook    | [3b59710f01](https://linux-hardware.org/?probe=3b59710f01) | Aug 25, 2021 |
| Supermicro    | H8DG6/H8DGi                 | Server      | [1fe97b31a1](https://linux-hardware.org/?probe=1fe97b31a1) | Aug 24, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [207f0c8966](https://linux-hardware.org/?probe=207f0c8966) | Aug 24, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [849c1fe7e3](https://linux-hardware.org/?probe=849c1fe7e3) | Aug 22, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [80aa412668](https://linux-hardware.org/?probe=80aa412668) | Aug 22, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [2a0bf4d1a9](https://linux-hardware.org/?probe=2a0bf4d1a9) | Aug 21, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [28d8feb60d](https://linux-hardware.org/?probe=28d8feb60d) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [f207dc8e9a](https://linux-hardware.org/?probe=f207dc8e9a) | Aug 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [ab27a12603](https://linux-hardware.org/?probe=ab27a12603) | Aug 18, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0eb2abca1d](https://linux-hardware.org/?probe=0eb2abca1d) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [9c25f25e8f](https://linux-hardware.org/?probe=9c25f25e8f) | Aug 16, 2021 |
| Pegatron      | 2ADC                        | Desktop     | [48cc7f548e](https://linux-hardware.org/?probe=48cc7f548e) | Aug 13, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [b99b48660a](https://linux-hardware.org/?probe=b99b48660a) | Aug 08, 2021 |
| Sony          | SVE14A27CLS                 | Notebook    | [53a5965063](https://linux-hardware.org/?probe=53a5965063) | Aug 07, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Dell          | G3 3590                     | Notebook    | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | Notebook    | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [482c64a9c9](https://linux-hardware.org/?probe=482c64a9c9) | Aug 03, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [e053c132dc](https://linux-hardware.org/?probe=e053c132dc) | Aug 02, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [acc597c748](https://linux-hardware.org/?probe=acc597c748) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60b58b4557](https://linux-hardware.org/?probe=60b58b4557) | Jul 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2e753f12ce](https://linux-hardware.org/?probe=2e753f12ce) | Jul 28, 2021 |
| Medion        | Unknown                     | Notebook    | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Medion        | Unknown                     | Notebook    | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [cae2419e98](https://linux-hardware.org/?probe=cae2419e98) | Jul 25, 2021 |
| MSI           | 3664h                       | Desktop     | [491117f46c](https://linux-hardware.org/?probe=491117f46c) | Jul 25, 2021 |
| MSI           | 3664h                       | Desktop     | [c9f3c48709](https://linux-hardware.org/?probe=c9f3c48709) | Jul 24, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [f8812e14cb](https://linux-hardware.org/?probe=f8812e14cb) | Jul 23, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [f56f54e2fa](https://linux-hardware.org/?probe=f56f54e2fa) | Jul 18, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [783a5cafc2](https://linux-hardware.org/?probe=783a5cafc2) | Jul 18, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2a3149a9a](https://linux-hardware.org/?probe=d2a3149a9a) | Jul 17, 2021 |
| eMachines     | EL1352                      | Desktop     | [83c494c15a](https://linux-hardware.org/?probe=83c494c15a) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| R-StyleCom... | ALICON AI2S-A21 00.69       | Desktop     | [85a8017eaf](https://linux-hardware.org/?probe=85a8017eaf) | Jul 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5320824c78](https://linux-hardware.org/?probe=5320824c78) | Jul 11, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [efc4c63ac7](https://linux-hardware.org/?probe=efc4c63ac7) | Jul 09, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9f7d75d241](https://linux-hardware.org/?probe=9f7d75d241) | Jul 09, 2021 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [ef9a6d3444](https://linux-hardware.org/?probe=ef9a6d3444) | Jul 08, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e3ea65a467](https://linux-hardware.org/?probe=e3ea65a467) | Jul 07, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1888baa539](https://linux-hardware.org/?probe=1888baa539) | Jul 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a87404851f](https://linux-hardware.org/?probe=a87404851f) | Jul 01, 2021 |
| MSI           | A75MA-G55                   | Desktop     | [3611191f22](https://linux-hardware.org/?probe=3611191f22) | Jun 30, 2021 |
| HP            | Notebook                    | Notebook    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [771f0fed2a](https://linux-hardware.org/?probe=771f0fed2a) | Jun 27, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [48a1dddc38](https://linux-hardware.org/?probe=48a1dddc38) | Jun 27, 2021 |
| Intel         | X79 V2.72B                  | Desktop     | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| ASUSTek       | N551JX                      | Notebook    | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [22f31e0de1](https://linux-hardware.org/?probe=22f31e0de1) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aa0efa1872](https://linux-hardware.org/?probe=aa0efa1872) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| Unknown       | Intel X79                   | Desktop     | [5be1e4c74c](https://linux-hardware.org/?probe=5be1e4c74c) | Jun 18, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [82a162c683](https://linux-hardware.org/?probe=82a162c683) | Jun 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [033cd8c9eb](https://linux-hardware.org/?probe=033cd8c9eb) | Jun 17, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [d37cfc0abc](https://linux-hardware.org/?probe=d37cfc0abc) | Jun 13, 2021 |
| HP            | Notebook                    | Notebook    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| MSI           | 970A-G46                    | Desktop     | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [6529cc537c](https://linux-hardware.org/?probe=6529cc537c) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [2aa173f32b](https://linux-hardware.org/?probe=2aa173f32b) | Jun 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Samsung       | 670Z5E                      | Notebook    | [252e20c152](https://linux-hardware.org/?probe=252e20c152) | Jun 11, 2021 |
| Intel         | DZ77GA-70K AAG39009-401     | Desktop     | [a88c5c7685](https://linux-hardware.org/?probe=a88c5c7685) | Jun 09, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [0ffe39ef8d](https://linux-hardware.org/?probe=0ffe39ef8d) | Jun 09, 2021 |
| Sony          | SVE14113ELW                 | Notebook    | [738c72c21c](https://linux-hardware.org/?probe=738c72c21c) | Jun 09, 2021 |
| HP            | ENVY 15                     | Notebook    | [8d7a772e05](https://linux-hardware.org/?probe=8d7a772e05) | Jun 07, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| Dell          | Precision 5520              | Notebook    | [199dec46c7](https://linux-hardware.org/?probe=199dec46c7) | Jun 01, 2021 |
| HP            | 1000                        | Notebook    | [21fb6389e7](https://linux-hardware.org/?probe=21fb6389e7) | Jun 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b1500a1319](https://linux-hardware.org/?probe=b1500a1319) | May 28, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [abc55fc46d](https://linux-hardware.org/?probe=abc55fc46d) | May 28, 2021 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [1761317692](https://linux-hardware.org/?probe=1761317692) | May 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9654da138c](https://linux-hardware.org/?probe=9654da138c) | May 28, 2021 |
| Personal C... | Iris                        | Notebook    | [835df5c61e](https://linux-hardware.org/?probe=835df5c61e) | May 27, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [afd83c5750](https://linux-hardware.org/?probe=afd83c5750) | May 25, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [66e4f1aeff](https://linux-hardware.org/?probe=66e4f1aeff) | May 23, 2021 |
| ASUSTek       | P5K3 Deluxe                 | Desktop     | [458525ba70](https://linux-hardware.org/?probe=458525ba70) | May 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5287ceef8d](https://linux-hardware.org/?probe=5287ceef8d) | May 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [0be7d156c5](https://linux-hardware.org/?probe=0be7d156c5) | May 17, 2021 |
| Toshiba       | Satellite L45-B             | Notebook    | [544d468137](https://linux-hardware.org/?probe=544d468137) | May 16, 2021 |
| HP            | 435                         | Notebook    | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | Notebook    | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [493edc40c4](https://linux-hardware.org/?probe=493edc40c4) | May 15, 2021 |
| Dell          | 0CN7X8 A04                  | Server      | [e4dee6faf7](https://linux-hardware.org/?probe=e4dee6faf7) | May 15, 2021 |
| Dell          | 0CN7X8 A04                  | Server      | [aa08de711d](https://linux-hardware.org/?probe=aa08de711d) | May 15, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [a98d93888d](https://linux-hardware.org/?probe=a98d93888d) | May 14, 2021 |
| Intel         | YL-3160L2                   | Desktop     | [c282d94246](https://linux-hardware.org/?probe=c282d94246) | May 13, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Lenovo        | ThinkCentre M55 8808E19     | Desktop     | [a53c13a5c9](https://linux-hardware.org/?probe=a53c13a5c9) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [1fba25dbcf](https://linux-hardware.org/?probe=1fba25dbcf) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c71715672c](https://linux-hardware.org/?probe=c71715672c) | May 12, 2021 |
| Samsung       | RF712                       | Notebook    | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | Notebook    | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [2e4262cb53](https://linux-hardware.org/?probe=2e4262cb53) | May 11, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [aacf9438d2](https://linux-hardware.org/?probe=aacf9438d2) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| Olidata       | Unknown                     | Desktop     | [1dc7094a4d](https://linux-hardware.org/?probe=1dc7094a4d) | May 09, 2021 |
| HP            | 339A                        | Desktop     | [c103096e94](https://linux-hardware.org/?probe=c103096e94) | May 09, 2021 |
| HP            | 339A                        | Desktop     | [1b94801e8b](https://linux-hardware.org/?probe=1b94801e8b) | May 09, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| Olidata       | Unknown                     | Desktop     | [0c2f6b27a9](https://linux-hardware.org/?probe=0c2f6b27a9) | May 08, 2021 |
| HP            | 1000                        | Notebook    | [4205750e24](https://linux-hardware.org/?probe=4205750e24) | May 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ce41256b96](https://linux-hardware.org/?probe=ce41256b96) | May 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [566133628f](https://linux-hardware.org/?probe=566133628f) | May 07, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [50baa8508f](https://linux-hardware.org/?probe=50baa8508f) | May 05, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Chile/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 103       | 9.23%   |
| Ubuntu 18.04                 | 74        | 6.63%   |
| Ubuntu 22.04                 | 52        | 4.66%   |
| Fedora 38                    | 31        | 2.78%   |
| Arch Rolling                 | 30        | 2.69%   |
| Pop!_OS 22.04                | 26        | 2.33%   |
| Manjaro                      | 25        | 2.24%   |
| Zorin 16                     | 23        | 2.06%   |
| OpenMandriva 4.3             | 23        | 2.06%   |
| Arch                         | 23        | 2.06%   |
| Ubuntu 19.04                 | 22        | 1.97%   |
| OpenMandriva 4.2             | 22        | 1.97%   |
| Debian 11                    | 19        | 1.7%    |
| Debian 10                    | 17        | 1.52%   |
| Fedora 37                    | 16        | 1.43%   |
| Fedora 34                    | 16        | 1.43%   |
| Linux Mint 21.1              | 15        | 1.34%   |
| Linux Mint 20.1              | 15        | 1.34%   |
| KDE neon 20.04               | 15        | 1.34%   |
| Fedora 35                    | 15        | 1.34%   |
| Zorin 15                     | 14        | 1.25%   |
| OpenMandriva 23.01           | 14        | 1.25%   |
| Debian 12                    | 14        | 1.25%   |
| Pop!_OS 20.04                | 13        | 1.16%   |
| Ubuntu 22.10                 | 12        | 1.08%   |
| Ubuntu 19.10                 | 12        | 1.08%   |
| Ubuntu 23.04                 | 11        | 0.99%   |
| Ubuntu 21.10                 | 11        | 0.99%   |
| Ubuntu 20.10                 | 11        | 0.99%   |
| Linux Mint 21.2              | 11        | 0.99%   |
| KDE neon 22.04               | 11        | 0.99%   |
| Fedora 32                    | 11        | 0.99%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.9%    |
| Fedora 36                    | 10        | 0.9%    |
| Fedora 33                    | 10        | 0.9%    |
| Debian Testing               | 10        | 0.9%    |
| Ubuntu 21.04                 | 9         | 0.81%   |
| ArcoLinux Rolling            | 9         | 0.81%   |
| Pop!_OS 20.10                | 8         | 0.72%   |
| OpenMandriva 23.08           | 8         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 320       | 30.16%  |
| Fedora        | 106       | 9.99%   |
| Linux Mint    | 82        | 7.73%   |
| OpenMandriva  | 77        | 7.26%   |
| Debian        | 60        | 5.66%   |
| Pop!_OS       | 52        | 4.9%    |
| Arch          | 50        | 4.71%   |
| Zorin         | 39        | 3.68%   |
| Manjaro       | 35        | 3.3%    |
| KDE neon      | 31        | 2.92%   |
| Kubuntu       | 18        | 1.7%    |
| ROSA          | 15        | 1.41%   |
| openSUSE      | 14        | 1.32%   |
| Elementary    | 14        | 1.32%   |
| Xubuntu       | 13        | 1.23%   |
| ArcoLinux     | 9         | 0.85%   |
| Ubuntu MATE   | 8         | 0.75%   |
| Nobara        | 8         | 0.75%   |
| Lubuntu       | 8         | 0.75%   |
| Endless       | 7         | 0.66%   |
| SteamOS       | 6         | 0.57%   |
| Kali          | 6         | 0.57%   |
| EndeavourOS   | 6         | 0.57%   |
| Xero          | 5         | 0.47%   |
| Ubuntu Budgie | 5         | 0.47%   |
| Loc OS        | 5         | 0.47%   |
| LMDE          | 5         | 0.47%   |
| Clear Linux   | 5         | 0.47%   |
| MX            | 4         | 0.38%   |
| Gentoo        | 4         | 0.38%   |
| Deepin        | 4         | 0.38%   |
| Ubuntu Unity  | 3         | 0.28%   |
| Solus         | 3         | 0.28%   |
| RHEL          | 3         | 0.28%   |
| Parrot        | 3         | 0.28%   |
| Ultramarine   | 2         | 0.19%   |
| Slackware     | 2         | 0.19%   |
| LinuxFX       | 2         | 0.19%   |
| Linux Lite    | 2         | 0.19%   |
| GNOME OS      | 2         | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 23        | 1.87%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.63%   |
| 6.1.1-desktop-1omv2290   | 13        | 1.06%   |
| 5.4.0-42-generic         | 13        | 1.06%   |
| 5.4.0-26-generic         | 9         | 0.73%   |
| 5.15.0-56-generic        | 9         | 0.73%   |
| 5.0.0-13-generic         | 9         | 0.73%   |
| 5.8.0-50-generic         | 8         | 0.65%   |
| 5.8.0-48-generic         | 8         | 0.65%   |
| 5.4.0-58-generic         | 8         | 0.65%   |
| 5.15.0-58-generic        | 8         | 0.65%   |
| 6.2.6-desktop-1omv2390   | 7         | 0.57%   |
| 5.4.0-48-generic         | 7         | 0.57%   |
| 5.4.0-47-generic         | 7         | 0.57%   |
| 5.15.0-60-generic        | 7         | 0.57%   |
| 5.15.0-52-generic        | 7         | 0.57%   |
| 5.15.0-48-generic        | 7         | 0.57%   |
| 5.11.0-27-generic        | 7         | 0.57%   |
| 5.0.0-23-generic         | 7         | 0.57%   |
| 4.18.0-15-generic        | 7         | 0.57%   |
| 6.4.11-desktop-1omv2390  | 6         | 0.49%   |
| 6.2.6-76060206-generic   | 6         | 0.49%   |
| 6.2.0-39-generic         | 6         | 0.49%   |
| 6.2.0-20-generic         | 6         | 0.49%   |
| 5.4.0-56-generic         | 6         | 0.49%   |
| 5.4.0-52-generic         | 6         | 0.49%   |
| 5.4.0-29-generic         | 6         | 0.49%   |
| 5.19.0-38-generic        | 6         | 0.49%   |
| 5.19.0-35-generic        | 6         | 0.49%   |
| 5.15.0-41-generic        | 6         | 0.49%   |
| 5.11.0-37-generic        | 6         | 0.49%   |
| 5.4.0-77-generic         | 5         | 0.41%   |
| 5.4.0-72-generic         | 5         | 0.41%   |
| 5.4.0-37-generic         | 5         | 0.41%   |
| 5.4.0-33-generic         | 5         | 0.41%   |
| 5.3.0-53-generic         | 5         | 0.41%   |
| 5.3.0-46-generic         | 5         | 0.41%   |
| 5.3.0-42-generic         | 5         | 0.41%   |
| 5.19.0-46-generic        | 5         | 0.41%   |
| 5.15.0-46-generic        | 5         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 151       | 12.91%  |
| 5.15.0  | 97        | 8.29%   |
| 5.8.0   | 49        | 4.19%   |
| 5.11.0  | 49        | 4.19%   |
| 5.0.0   | 45        | 3.85%   |
| 5.19.0  | 41        | 3.5%    |
| 4.15.0  | 41        | 3.5%    |
| 5.3.0   | 38        | 3.25%   |
| 6.2.0   | 35        | 2.99%   |
| 5.13.0  | 32        | 2.74%   |
| 4.18.0  | 28        | 2.39%   |
| 5.16.7  | 23        | 1.97%   |
| 5.10.0  | 21        | 1.79%   |
| 5.10.14 | 20        | 1.71%   |
| 6.1.1   | 16        | 1.37%   |
| 6.1.0   | 15        | 1.28%   |
| 6.2.6   | 14        | 1.2%    |
| 4.19.0  | 13        | 1.11%   |
| 5.14.0  | 12        | 1.03%   |
| 6.0.0   | 9         | 0.77%   |
| 6.4.11  | 7         | 0.6%    |
| 6.5.0   | 6         | 0.51%   |
| 6.4.8   | 6         | 0.51%   |
| 6.2.9   | 6         | 0.51%   |
| 5.9.16  | 6         | 0.51%   |
| 4.9.60  | 6         | 0.51%   |
| 6.6.6   | 5         | 0.43%   |
| 6.3.8   | 5         | 0.43%   |
| 5.17.5  | 5         | 0.43%   |
| 6.6.8   | 4         | 0.34%   |
| 6.6.2   | 4         | 0.34%   |
| 6.5.6   | 4         | 0.34%   |
| 6.2.14  | 4         | 0.34%   |
| 6.0.12  | 4         | 0.34%   |
| 5.8.12  | 4         | 0.34%   |
| 5.18.10 | 4         | 0.34%   |
| 5.16.11 | 4         | 0.34%   |
| 5.13.13 | 4         | 0.34%   |
| 5.12.0  | 4         | 0.34%   |
| 6.7.0   | 3         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 157       | 13.66%  |
| 5.15    | 108       | 9.4%    |
| 6.2     | 70        | 6.09%   |
| 5.10    | 67        | 5.83%   |
| 5.11    | 66        | 5.74%   |
| 5.19    | 61        | 5.31%   |
| 6.1     | 60        | 5.22%   |
| 5.8     | 54        | 4.7%    |
| 5.13    | 48        | 4.18%   |
| 5.0     | 48        | 4.18%   |
| 4.15    | 41        | 3.57%   |
| 5.3     | 40        | 3.48%   |
| 5.16    | 37        | 3.22%   |
| 6.4     | 32        | 2.79%   |
| 4.18    | 29        | 2.52%   |
| 6.5     | 24        | 2.09%   |
| 6.0     | 23        | 2%      |
| 6.3     | 22        | 1.91%   |
| 6.6     | 21        | 1.83%   |
| 5.17    | 21        | 1.83%   |
| 5.14    | 20        | 1.74%   |
| 5.9     | 16        | 1.39%   |
| 5.12    | 16        | 1.39%   |
| 4.19    | 14        | 1.22%   |
| 5.18    | 13        | 1.13%   |
| 4.9     | 10        | 0.87%   |
| 5.6     | 7         | 0.61%   |
| 5.5     | 6         | 0.52%   |
| 6.7     | 4         | 0.35%   |
| 5.7     | 4         | 0.35%   |
| 4.4     | 4         | 0.35%   |
| 5.1     | 3         | 0.26%   |
| 4.13    | 1         | 0.09%   |
| 3.10    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 997       | 97.75%  |
| i686    | 21        | 2.06%   |
| aarch64 | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 470       | 44.3%   |
| KDE5             | 203       | 19.13%  |
| Unknown          | 113       | 10.65%  |
| XFCE             | 71        | 6.69%   |
| X-Cinnamon       | 65        | 6.13%   |
| KDE              | 29        | 2.73%   |
| MATE             | 19        | 1.79%   |
| Pantheon         | 14        | 1.32%   |
| LXDE             | 11        | 1.04%   |
| KDE4             | 10        | 0.94%   |
| Budgie           | 10        | 0.94%   |
| i3               | 9         | 0.85%   |
| LXQt             | 7         | 0.66%   |
| Cinnamon         | 7         | 0.66%   |
| Deepin           | 6         | 0.57%   |
| Unity            | 3         | 0.28%   |
| GNOME Flashback  | 3         | 0.28%   |
| awesome          | 3         | 0.28%   |
| xmonad           | 2         | 0.19%   |
| qtile            | 2         | 0.19%   |
| Trinity          | 1         | 0.09%   |
| lightdm-xsession | 1         | 0.09%   |
| icewm            | 1         | 0.09%   |
| bspwm            | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 756       | 71.59%  |
| Wayland | 221       | 20.93%  |
| Unknown | 69        | 6.53%   |
| Tty     | 10        | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 594       | 55.72%  |
| SDDM    | 149       | 13.98%  |
| GDM     | 112       | 10.51%  |
| GDM3    | 93        | 8.72%   |
| LightDM | 74        | 6.94%   |
| TDM     | 26        | 2.44%   |
| KDM     | 10        | 0.94%   |
| XDM     | 4         | 0.38%   |
| LXDM    | 2         | 0.19%   |
| SLIMSKI | 1         | 0.09%   |
| LY-DM   | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_CL      | 552       | 52.52%  |
| en_US      | 230       | 21.88%  |
| Unknown    | 113       | 10.75%  |
| es_ES      | 71        | 6.76%   |
| es_MX      | 28        | 2.66%   |
| en_GB      | 17        | 1.62%   |
| C          | 13        | 1.24%   |
| es_AR      | 7         | 0.67%   |
| fr_FR      | 2         | 0.19%   |
| es_VE      | 2         | 0.19%   |
| es_UY      | 2         | 0.19%   |
| es_BO      | 2         | 0.19%   |
| en_CA      | 2         | 0.19%   |
| de_DE      | 2         | 0.19%   |
| ru_RU      | 1         | 0.1%    |
| pt_BR      | 1         | 0.1%    |
| nl_NL      | 1         | 0.1%    |
| latam_IT   | 1         | 0.1%    |
| es_CO      | 1         | 0.1%    |
| es_CL.UTF8 | 1         | 0.1%    |
| en_AG      | 1         | 0.1%    |
| arn_CL     | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 539       | 51.83%  |
| BIOS | 501       | 48.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 761       | 72.06%  |
| Btrfs   | 139       | 13.16%  |
| Overlay | 67        | 6.34%   |
| Unknown | 40        | 3.79%   |
| Tmpfs   | 28        | 2.65%   |
| Xfs     | 12        | 1.14%   |
| Ext2    | 4         | 0.38%   |
| Zfs     | 3         | 0.28%   |
| Jfs     | 1         | 0.09%   |
| Ext3    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 612       | 57.84%  |
| GPT     | 365       | 34.5%   |
| MBR     | 81        | 7.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 930       | 89.17%  |
| Yes       | 113       | 10.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 759       | 72.49%  |
| Yes       | 288       | 27.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 229       | 22.47%  |
| ASUSTek Computer                     | 167       | 16.39%  |
| Lenovo                               | 153       | 15.01%  |
| Dell                                 | 83        | 8.15%   |
| Acer                                 | 69        | 6.77%   |
| MSI                                  | 52        | 5.1%    |
| Samsung Electronics                  | 27        | 2.65%   |
| Gigabyte Technology                  | 26        | 2.55%   |
| Intel                                | 22        | 2.16%   |
| Toshiba                              | 21        | 2.06%   |
| Apple                                | 20        | 1.96%   |
| Sony                                 | 15        | 1.47%   |
| Unknown                              | 15        | 1.47%   |
| ECS                                  | 14        | 1.37%   |
| HUAWEI                               | 11        | 1.08%   |
| ASRock                               | 9         | 0.88%   |
| Packard Bell                         | 8         | 0.79%   |
| Valve                                | 6         | 0.59%   |
| Huanan                               | 5         | 0.49%   |
| SK hynix                             | 4         | 0.39%   |
| Pegatron                             | 4         | 0.39%   |
| Google                               | 4         | 0.39%   |
| Chuwi                                | 4         | 0.39%   |
| AMI                                  | 3         | 0.29%   |
| TPV-INVENTA                          | 2         | 0.2%    |
| MACHINIST                            | 2         | 0.2%    |
| HONOR                                | 2         | 0.2%    |
| HC                                   | 2         | 0.2%    |
| Foxconn                              | 2         | 0.2%    |
| eMachines                            | 2         | 0.2%    |
| ZOTAC                                | 1         | 0.1%    |
| WZA300S2R120                         | 1         | 0.1%    |
| ViewSonic                            | 1         | 0.1%    |
| TAGTech                              | 1         | 0.1%    |
| SZMZ                                 | 1         | 0.1%    |
| Supermicro                           | 1         | 0.1%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.1%    |
| Render                               | 1         | 0.1%    |
| Raspberry Pi Foundation              | 1         | 0.1%    |
| R-StyleComputers                     | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 20        | 1.96%   |
| HP Notebook                           | 12        | 1.18%   |
| HP 240 G6 Notebook PC                 | 11        | 1.08%   |
| HP Pavilion Notebook                  | 7         | 0.69%   |
| Valve Jupiter                         | 6         | 0.59%   |
| MSI MS-7817                           | 6         | 0.59%   |
| HP ENVY 15                            | 6         | 0.59%   |
| ASUS All Series                       | 6         | 0.59%   |
| HP Pavilion Laptop 15-cw1xxx          | 5         | 0.49%   |
| HP Pavilion 15                        | 5         | 0.49%   |
| ASUS ZenBook UX325EA_UX325EA          | 5         | 0.49%   |
| ASUS PRIME B450M-A                    | 5         | 0.49%   |
| ASUS PRIME A320M-K                    | 5         | 0.49%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 4         | 0.39%   |
| HUAWEI BOHK-WAX9X                     | 4         | 0.39%   |
| HP Pavilion Laptop 15-eh0xxx          | 4         | 0.39%   |
| HP Pavilion g4                        | 4         | 0.39%   |
| HP 250 G6 Notebook PC                 | 4         | 0.39%   |
| HP 14                                 | 4         | 0.39%   |
| Dell Inspiron 3501                    | 4         | 0.39%   |
| Acer Aspire ES1-111M                  | 4         | 0.39%   |
| SK hynix HyBook                       | 3         | 0.29%   |
| Samsung RF511/RF411/RF711             | 3         | 0.29%   |
| MSI MS-7A34                           | 3         | 0.29%   |
| MSI MS-7788                           | 3         | 0.29%   |
| Lenovo Y520-15IKBN 80WK               | 3         | 0.29%   |
| Lenovo Legion Y530-15ICH 81FV         | 3         | 0.29%   |
| Lenovo IdeaPad 330S-15ARR 81FB        | 3         | 0.29%   |
| HP ProBook 440 G3                     | 3         | 0.29%   |
| HP Pavilion Laptop 15-cw0xxx          | 3         | 0.29%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 3         | 0.29%   |
| HP Pavilion Gaming Laptop 15-dk0xxx   | 3         | 0.29%   |
| HP Pavilion dv4                       | 3         | 0.29%   |
| HP ENVY x360 Convertible 13-ag0xxx    | 3         | 0.29%   |
| HP EliteBook 840 G6                   | 3         | 0.29%   |
| HP EliteBook 2560p                    | 3         | 0.29%   |
| HP Compaq Pro 4300 SFF PC             | 3         | 0.29%   |
| HP 15                                 | 3         | 0.29%   |
| HP 1000                               | 3         | 0.29%   |
| Google Treeya                         | 3         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 63        | 6.18%   |
| HP Pavilion           | 57        | 5.59%   |
| Acer Aspire           | 51        | 5%      |
| Lenovo IdeaPad        | 46        | 4.51%   |
| Dell Inspiron         | 31        | 3.04%   |
| ASUS VivoBook         | 23        | 2.26%   |
| Dell Latitude         | 22        | 2.16%   |
| ASUS TUF              | 22        | 2.16%   |
| ASUS PRIME            | 22        | 2.16%   |
| Unknown               | 20        | 1.96%   |
| HP EliteBook          | 19        | 1.86%   |
| HP 240                | 18        | 1.77%   |
| HP ENVY               | 17        | 1.67%   |
| HP Laptop             | 16        | 1.57%   |
| Toshiba Satellite     | 15        | 1.47%   |
| HP ProBook            | 15        | 1.47%   |
| HP Compaq             | 13        | 1.28%   |
| HP Notebook           | 12        | 1.18%   |
| ASUS ZenBook          | 12        | 1.18%   |
| ASUS ROG              | 10        | 0.98%   |
| Lenovo ThinkCentre    | 8         | 0.79%   |
| ASUS ASUS             | 8         | 0.79%   |
| Acer Swift            | 8         | 0.79%   |
| HP 250                | 7         | 0.69%   |
| HP 245                | 7         | 0.69%   |
| Dell Precision        | 7         | 0.69%   |
| Valve Jupiter         | 6         | 0.59%   |
| Packard Bell EasyNote | 6         | 0.59%   |
| MSI MS-7817           | 6         | 0.59%   |
| Lenovo Legion         | 6         | 0.59%   |
| Dell Vostro           | 6         | 0.59%   |
| ASUS All              | 6         | 0.59%   |
| Dell OptiPlex         | 5         | 0.49%   |
| Toshiba PORTEGE       | 4         | 0.39%   |
| SK hynix HyBook       | 4         | 0.39%   |
| HUAWEI BOHK-WAX9X     | 4         | 0.39%   |
| HP ProDesk            | 4         | 0.39%   |
| HP Presario           | 4         | 0.39%   |
| HP OMEN               | 4         | 0.39%   |
| HP 14                 | 4         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 111       | 10.89%  |
| 2017    | 99        | 9.72%   |
| 2019    | 91        | 8.93%   |
| 2018    | 91        | 8.93%   |
| 2013    | 72        | 7.07%   |
| 2021    | 71        | 6.97%   |
| 2012    | 71        | 6.97%   |
| 2011    | 68        | 6.67%   |
| 2016    | 61        | 5.99%   |
| 2014    | 59        | 5.79%   |
| 2015    | 44        | 4.32%   |
| 2010    | 43        | 4.22%   |
| 2022    | 32        | 3.14%   |
| 2007    | 32        | 3.14%   |
| 2008    | 31        | 3.04%   |
| 2009    | 27        | 2.65%   |
| 2023    | 10        | 0.98%   |
| 2006    | 4         | 0.39%   |
| 2005    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 690       | 67.71%  |
| Desktop        | 271       | 26.59%  |
| Convertible    | 19        | 1.86%   |
| All in one     | 15        | 1.47%   |
| Mini pc        | 13        | 1.28%   |
| Tablet         | 7         | 0.69%   |
| Server         | 3         | 0.29%   |
| System on chip | 1         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 933       | 90.58%  |
| Enabled  | 97        | 9.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1015      | 99.61%  |
| Yes  | 4         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 282       | 27.25%  |
| 3.01-4.0    | 212       | 20.48%  |
| 8.01-16.0   | 209       | 20.19%  |
| 16.01-24.0  | 166       | 16.04%  |
| 32.01-64.0  | 72        | 6.96%   |
| 1.01-2.0    | 45        | 4.35%   |
| 24.01-32.0  | 19        | 1.84%   |
| 2.01-3.0    | 17        | 1.64%   |
| 64.01-256.0 | 10        | 0.97%   |
| 0.51-1.0    | 2         | 0.19%   |
| Unknown     | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 369       | 32.63%  |
| 2.01-3.0   | 287       | 25.38%  |
| 3.01-4.0   | 191       | 16.89%  |
| 4.01-8.0   | 179       | 15.83%  |
| 0.51-1.0   | 53        | 4.69%   |
| 8.01-16.0  | 43        | 3.8%    |
| 0.01-0.5   | 5         | 0.44%   |
| 16.01-24.0 | 2         | 0.18%   |
| 24.01-32.0 | 1         | 0.09%   |
| Unknown    | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 684       | 65.33%  |
| 2      | 254       | 24.26%  |
| 3      | 58        | 5.54%   |
| 4      | 30        | 2.87%   |
| 5      | 11        | 1.05%   |
| 0      | 7         | 0.67%   |
| 7      | 2         | 0.19%   |
| 6      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 720       | 69.97%  |
| Yes       | 309       | 30.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 865       | 84.72%  |
| No        | 156       | 15.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 860       | 84.15%  |
| No        | 162       | 15.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 698       | 67.64%  |
| No        | 334       | 32.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Chile   | 1019      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Santiago            | 371       | 34.13%  |
| Concepción         | 52        | 4.78%   |
| Viña del Mar       | 48        | 4.42%   |
| Las Condes          | 36        | 3.31%   |
| Maipu               | 32        | 2.94%   |
| Puente Alto         | 30        | 2.76%   |
| Temuco              | 26        | 2.39%   |
| Valdivia            | 22        | 2.02%   |
| Nunoa               | 22        | 2.02%   |
| La Florida          | 22        | 2.02%   |
| Providencia         | 19        | 1.75%   |
| Antofagasta         | 19        | 1.75%   |
| San Miguel          | 16        | 1.47%   |
| La Serena           | 16        | 1.47%   |
| Port Montt          | 15        | 1.38%   |
| Valparaíso         | 13        | 1.2%    |
| Rancagua            | 11        | 1.01%   |
| Coronel             | 11        | 1.01%   |
| Quilpué            | 10        | 0.92%   |
| Iquique             | 10        | 0.92%   |
| Los Ángeles        | 9         | 0.83%   |
| Coquimbo            | 9         | 0.83%   |
| Talcahuano          | 8         | 0.74%   |
| Osorno              | 8         | 0.74%   |
| San Pedro de la Paz | 7         | 0.64%   |
| Melipilla           | 7         | 0.64%   |
| Curicó             | 7         | 0.64%   |
| Colina              | 7         | 0.64%   |
| Chillan             | 7         | 0.64%   |
| San Bernardo        | 6         | 0.55%   |
| Quillota            | 6         | 0.55%   |
| Penalolen           | 6         | 0.55%   |
| Macul               | 6         | 0.55%   |
| Hualpen             | 6         | 0.55%   |
| Central             | 6         | 0.55%   |
| Vitacura            | 5         | 0.46%   |
| Villa Alemana       | 5         | 0.46%   |
| Talca               | 5         | 0.46%   |
| Quilicura           | 5         | 0.46%   |
| Punta Arenas        | 5         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 261       | 380    | 18.54%  |
| Seagate                     | 180       | 245    | 12.78%  |
| Toshiba                     | 128       | 153    | 9.09%   |
| Kingston                    | 124       | 180    | 8.81%   |
| Samsung Electronics         | 112       | 161    | 7.95%   |
| Crucial                     | 85        | 105    | 6.04%   |
| SanDisk                     | 68        | 84     | 4.83%   |
| Unknown                     | 61        | 85     | 4.33%   |
| Hitachi                     | 46        | 54     | 3.27%   |
| HGST                        | 37        | 41     | 2.63%   |
| SK hynix                    | 36        | 45     | 2.56%   |
| Intel                       | 33        | 50     | 2.34%   |
| China                       | 23        | 28     | 1.63%   |
| Micron Technology           | 17        | 25     | 1.21%   |
| Silicon Motion              | 15        | 15     | 1.07%   |
| Apple                       | 14        | 14     | 0.99%   |
| Kingston Technology Company | 13        | 16     | 0.92%   |
| Micron/Crucial Technology   | 11        | 15     | 0.78%   |
| KingSpec                    | 11        | 20     | 0.78%   |
| KIOXIA                      | 10        | 14     | 0.71%   |
| Lexar                       | 7         | 14     | 0.5%    |
| JMicron Technology          | 7         | 7      | 0.5%    |
| A-DATA Technology           | 7         | 9      | 0.5%    |
| XPG                         | 6         | 16     | 0.43%   |
| Corsair                     | 6         | 11     | 0.43%   |
| Maxtor                      | 5         | 7      | 0.36%   |
| XrayDisk                    | 4         | 4      | 0.28%   |
| Realtek Semiconductor       | 4         | 4      | 0.28%   |
| LITEON                      | 4         | 4      | 0.28%   |
| Unknown                     | 4         | 4      | 0.28%   |
| SSSTC                       | 3         | 4      | 0.21%   |
| Phison Electronics          | 3         | 3      | 0.21%   |
| Phison                      | 3         | 3      | 0.21%   |
| Netac                       | 3         | 3      | 0.21%   |
| Mass                        | 3         | 3      | 0.21%   |
| Gigabyte Technology         | 3         | 5      | 0.21%   |
| WALRAM                      | 2         | 3      | 0.14%   |
| UMIS                        | 2         | 2      | 0.14%   |
| SCY                         | 2         | 2      | 0.14%   |
| O2 Micro                    | 2         | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 26        | 1.71%   |
| Kingston SA400S37240G 240GB SSD                   | 24        | 1.58%   |
| Kingston SA400S37480G 480GB SSD                   | 22        | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB                    | 20        | 1.31%   |
| Toshiba MQ01ABF050 500GB                          | 16        | 1.05%   |
| Toshiba DT01ACA100 1TB                            | 16        | 1.05%   |
| Crucial CT240BX500SSD1 240GB                      | 16        | 1.05%   |
| Toshiba HDWD110 1TB                               | 15        | 0.99%   |
| Seagate ST500DM002-1BD142 500GB                   | 15        | 0.99%   |
| Unknown MMC Card  64GB                            | 13        | 0.85%   |
| Toshiba MQ01ABD100 1TB                            | 13        | 0.85%   |
| Unknown MMC Card  32GB                            | 12        | 0.79%   |
| Toshiba MQ04ABF100 1TB                            | 12        | 0.79%   |
| Seagate ST500LT012-1DG142 500GB                   | 12        | 0.79%   |
| Crucial CT480BX500SSD1 480GB                      | 12        | 0.79%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 10        | 0.66%   |
| Seagate ST9500325AS 500GB                         | 10        | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 10        | 0.66%   |
| Kingston SA400S37120G 120GB SSD                   | 10        | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 9         | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 9         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 9         | 0.59%   |
| Samsung NVMe SSD Drive 512GB                      | 9         | 0.59%   |
| HGST HTS545050A7E680 500GB                        | 9         | 0.59%   |
| Crucial CT500MX500SSD1 500GB                      | 9         | 0.59%   |
| Crucial CT120BX500SSD1 120GB                      | 9         | 0.59%   |
| Crucial CT1000MX500SSD1 1TB                       | 9         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 8         | 0.53%   |
| Unknown MMC Card  128GB                           | 8         | 0.53%   |
| HGST HTS541010A9E680 1TB                          | 8         | 0.53%   |
| Toshiba DT01ACA050 500GB                          | 7         | 0.46%   |
| Seagate ST500LT012-9WS142 500GB                   | 7         | 0.46%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB              | 7         | 0.46%   |
| SanDisk NVMe SSD Drive 500GB                      | 7         | 0.46%   |
| Kingston SNVS500G 500GB                           | 7         | 0.46%   |
| Intel HBRPEKNX0101AHO 16GB                        | 7         | 0.46%   |
| Intel HBRPEKNX0101AH 256GB                        | 7         | 0.46%   |
| Crucial CT120BX300SSD1 120GB                      | 7         | 0.46%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                  | 6         | 0.39%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 6         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 178       | 242    | 29.97%  |
| WDC                 | 177       | 236    | 29.8%   |
| Toshiba             | 117       | 139    | 19.7%   |
| Hitachi             | 46        | 54     | 7.74%   |
| HGST                | 37        | 41     | 6.23%   |
| Samsung Electronics | 15        | 19     | 2.53%   |
| Apple               | 8         | 8      | 1.35%   |
| Unknown             | 4         | 4      | 0.67%   |
| Maxtor              | 4         | 6      | 0.67%   |
| JMicron Technology  | 4         | 4      | 0.67%   |
| ASMT                | 2         | 3      | 0.34%   |
| StoreJet            | 1         | 1      | 0.17%   |
| Fujitsu             | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 100       | 141    | 22.68%  |
| WDC                 | 86        | 120    | 19.5%   |
| Crucial             | 83        | 102    | 18.82%  |
| Samsung Electronics | 38        | 50     | 8.62%   |
| China               | 23        | 28     | 5.22%   |
| SanDisk             | 20        | 23     | 4.54%   |
| KingSpec            | 11        | 20     | 2.49%   |
| Lexar               | 7         | 14     | 1.59%   |
| Corsair             | 6         | 11     | 1.36%   |
| Apple               | 6         | 6      | 1.36%   |
| SK hynix            | 5         | 8      | 1.13%   |
| Micron Technology   | 5         | 5      | 1.13%   |
| A-DATA Technology   | 5         | 7      | 1.13%   |
| XrayDisk            | 3         | 3      | 0.68%   |
| LITEON              | 3         | 3      | 0.68%   |
| Intel               | 3         | 5      | 0.68%   |
| Gigabyte Technology | 3         | 5      | 0.68%   |
| Toshiba             | 2         | 5      | 0.45%   |
| SCY                 | 2         | 2      | 0.45%   |
| Netac               | 2         | 2      | 0.45%   |
| LITEONIT            | 2         | 2      | 0.45%   |
| FORESEE             | 2         | 3      | 0.45%   |
| Unknown             | 2         | 2      | 0.45%   |
| ZOTAC               | 1         | 1      | 0.23%   |
| Wdxsky              | 1         | 1      | 0.23%   |
| WALRAM              | 1         | 1      | 0.23%   |
| Vaseky              | 1         | 1      | 0.23%   |
| USB3.0              | 1         | 1      | 0.23%   |
| SABRENT             | 1         | 1      | 0.23%   |
| PNY                 | 1         | 1      | 0.23%   |
| Patriot             | 1         | 1      | 0.23%   |
| OWC                 | 1         | 1      | 0.23%   |
| OSCOO               | 1         | 1      | 0.23%   |
| OCZ                 | 1         | 2      | 0.23%   |
| NGFF                | 1         | 1      | 0.23%   |
| Maxtor              | 1         | 1      | 0.23%   |
| Maxell              | 1         | 1      | 0.23%   |
| LuminouTek          | 1         | 1      | 0.23%   |
| KingDian            | 1         | 2      | 0.23%   |
| Intenso             | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 521       | 758    | 40.23%  |
| SSD     | 399       | 592    | 30.81%  |
| NVMe    | 300       | 446    | 23.17%  |
| MMC     | 55        | 77     | 4.25%   |
| Unknown | 20        | 23     | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 785       | 1333   | 66.98%  |
| NVMe | 300       | 444    | 25.6%   |
| MMC  | 55        | 77     | 4.69%   |
| SAS  | 32        | 42     | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 577       | 882    | 63.27%  |
| 0.51-1.0   | 278       | 385    | 30.48%  |
| 1.01-2.0   | 40        | 52     | 4.39%   |
| 3.01-4.0   | 7         | 8      | 0.77%   |
| 2.01-3.0   | 5         | 12     | 0.55%   |
| 4.01-10.0  | 5         | 11     | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 321       | 29.5%   |
| 101-250        | 266       | 24.45%  |
| 501-1000       | 173       | 15.9%   |
| 1001-2000      | 78        | 7.17%   |
| 1-20           | 71        | 6.53%   |
| 51-100         | 57        | 5.24%   |
| 21-50          | 38        | 3.49%   |
| More than 3000 | 34        | 3.13%   |
| 2001-3000      | 25        | 2.3%    |
| Unknown        | 25        | 2.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 428       | 37.81%  |
| 21-50          | 212       | 18.73%  |
| 101-250        | 140       | 12.37%  |
| 51-100         | 136       | 12.01%  |
| 251-500        | 85        | 7.51%   |
| 501-1000       | 58        | 5.12%   |
| 1001-2000      | 31        | 2.74%   |
| Unknown        | 25        | 2.21%   |
| More than 3000 | 10        | 0.88%   |
| 2001-3000      | 6         | 0.53%   |
| 0              | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB     | 4         | 4      | 4.17%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 4.17%   |
| WDC WD1600BB-00GUC0 160GB           | 2         | 2      | 2.08%   |
| Toshiba MQ01ABD075 752GB            | 2         | 3      | 2.08%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 2.08%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 2.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 2.08%   |
| Seagate ST31000528AS 1TB            | 2         | 2      | 2.08%   |
| Kingston SKC400S371T 1TB SSD        | 2         | 11     | 2.08%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 2.08%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 3      | 2.08%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 2      | 2.08%   |
| HGST HTS545050A7E380 500GB          | 2         | 2      | 2.08%   |
| HGST HTS541010B7E610 1TB            | 2         | 2      | 2.08%   |
| XrayDisk SSD 256GB                  | 1         | 1      | 1.04%   |
| XPG SPECTRIX S40G 1TB               | 1         | 1      | 1.04%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 1      | 1.04%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD    | 1         | 1      | 1.04%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.04%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 1.04%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 1.04%   |
| WDC WD5000AAKX-083CA1 500GB         | 1         | 1      | 1.04%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 1.04%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 2      | 1.04%   |
| WDC WD20EARX-00PASB0 2TB            | 1         | 1      | 1.04%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 1      | 1.04%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 1.04%   |
| WDC WD10EARS-003BB1 1TB             | 1         | 1      | 1.04%   |
| WDC WD Green M.2 2280 240GB         | 1         | 1      | 1.04%   |
| WDC WD Green 2.5 240GB SSD          | 1         | 3      | 1.04%   |
| WDC WD Blue SA510 2.5 1000GB SSD    | 1         | 1      | 1.04%   |
| Vaseky V820/1TB 1024GB              | 1         | 1      | 1.04%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.04%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 1.04%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 1.04%   |
| Toshiba MK1652GSX 160GB             | 1         | 1      | 1.04%   |
| Toshiba DT01ACA100 1TB              | 1         | 1      | 1.04%   |
| Toshiba DT01ACA050 500GB            | 1         | 1      | 1.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 22.34%  |
| WDC                 | 17        | 20     | 18.09%  |
| HGST                | 13        | 14     | 13.83%  |
| Hitachi             | 12        | 16     | 12.77%  |
| Toshiba             | 9         | 10     | 9.57%   |
| Kingston            | 8         | 17     | 8.51%   |
| Samsung Electronics | 2         | 4      | 2.13%   |
| Crucial             | 2         | 2      | 2.13%   |
| XrayDisk            | 1         | 1      | 1.06%   |
| XPG                 | 1         | 1      | 1.06%   |
| Vaseky              | 1         | 1      | 1.06%   |
| SK hynix            | 1         | 1      | 1.06%   |
| Maxtor              | 1         | 1      | 1.06%   |
| LITEON              | 1         | 1      | 1.06%   |
| Intel               | 1         | 2      | 1.06%   |
| Faspeed             | 1         | 1      | 1.06%   |
| China               | 1         | 1      | 1.06%   |
| A-DATA Technology   | 1         | 1      | 1.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 30.43%  |
| HGST                | 13        | 14     | 18.84%  |
| WDC                 | 12        | 13     | 17.39%  |
| Hitachi             | 12        | 16     | 17.39%  |
| Toshiba             | 9         | 10     | 13.04%  |
| Samsung Electronics | 1         | 3      | 1.45%   |
| Maxtor              | 1         | 1      | 1.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 83     | 71.59%  |
| SSD  | 22        | 34     | 25%     |
| NVMe | 3         | 3      | 3.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB  | 1         | 1      | 50%     |
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 675       | 1186   | 61.31%  |
| Works    | 337       | 588    | 30.61%  |
| Malfunc  | 87        | 120    | 7.9%    |
| Failed   | 2         | 2      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 658       | 53.85%  |
| AMD                                  | 225       | 18.41%  |
| Samsung Electronics                  | 68        | 5.56%   |
| SanDisk                              | 66        | 5.4%    |
| Kingston Technology Company          | 35        | 2.86%   |
| SK hynix                             | 31        | 2.54%   |
| Silicon Motion                       | 17        | 1.39%   |
| Micron/Crucial Technology            | 14        | 1.15%   |
| Micron Technology                    | 12        | 0.98%   |
| KIOXIA                               | 11        | 0.9%    |
| Nvidia                               | 10        | 0.82%   |
| Realtek Semiconductor                | 9         | 0.74%   |
| JMicron Technology                   | 9         | 0.74%   |
| Toshiba America Info Systems         | 8         | 0.65%   |
| Marvell Technology Group             | 8         | 0.65%   |
| ADATA Technology                     | 7         | 0.57%   |
| Phison Electronics                   | 6         | 0.49%   |
| ASMedia Technology                   | 6         | 0.49%   |
| Silicon Integrated Systems [SiS]     | 4         | 0.33%   |
| Union Memory (Shenzhen)              | 3         | 0.25%   |
| Solid State Storage Technology       | 3         | 0.25%   |
| MAXIO Technology (Hangzhou)          | 3         | 0.25%   |
| O2 Micro                             | 2         | 0.16%   |
| VIA Technologies                     | 1         | 0.08%   |
| Shenzhen Longsys Electronics         | 1         | 0.08%   |
| Seagate Technology                   | 1         | 0.08%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.08%   |
| Lite-On Technology                   | 1         | 0.08%   |
| Hosin Global Electronics             | 1         | 0.08%   |
| Broadcom / LSI                       | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 160       | 11.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 88        | 6.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 49        | 3.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 45        | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 37        | 2.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 32        | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 28        | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 27        | 1.95%   |
| Intel Volume Management Device NVMe RAID Controller                              | 26        | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 24        | 1.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 22        | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                           | 21        | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 19        | 1.37%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 18        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 18        | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16        | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 15        | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 15        | 1.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 14        | 1.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14        | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 14        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 14        | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 13        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 0.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 12        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 12        | 0.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 11        | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 0.79%   |
| Intel SSD 660P Series                                                            | 10        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 0.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 0.72%   |
| AMD 500 Series Chipset SATA Controller                                           | 10        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 9         | 0.65%   |
| Intel SATA Controller [RAID mode]                                                | 9         | 0.65%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]               | 9         | 0.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 9         | 0.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 9         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 742       | 59.65%  |
| NVMe | 301       | 24.2%   |
| IDE  | 114       | 9.16%   |
| RAID | 87        | 6.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 735       | 72.13%  |
| AMD    | 283       | 27.77%  |
| ARM    | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 2.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 1.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 1.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 0.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.88%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 8         | 0.78%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 8         | 0.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 7         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.68%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 7         | 0.68%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 7         | 0.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 7         | 0.68%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.58%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 6         | 0.58%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.58%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 6         | 0.58%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.58%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 6         | 0.58%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 6         | 0.58%   |
| AMD Custom APU 0405                           | 6         | 0.58%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.49%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 0.49%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 0.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.49%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 5         | 0.49%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 5         | 0.49%   |
| AMD FX-8350 Eight-Core Processor              | 5         | 0.49%   |
| AMD FX-6300 Six-Core Processor                | 5         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 214       | 20.86%  |
| Intel Core i7           | 149       | 14.52%  |
| Intel Core i3           | 86        | 8.38%   |
| Intel Celeron           | 68        | 6.63%   |
| AMD Ryzen 5             | 65        | 6.34%   |
| Other                   | 56        | 5.46%   |
| Intel Pentium           | 37        | 3.61%   |
| AMD Ryzen 7             | 36        | 3.51%   |
| Intel Xeon              | 31        | 3.02%   |
| Intel Core 2 Duo        | 28        | 2.73%   |
| Intel Atom              | 23        | 2.24%   |
| AMD Ryzen 3             | 21        | 2.05%   |
| AMD A6                  | 16        | 1.56%   |
| AMD A10                 | 16        | 1.56%   |
| AMD FX                  | 14        | 1.36%   |
| Intel Pentium Dual-Core | 12        | 1.17%   |
| AMD Ryzen 9             | 12        | 1.17%   |
| AMD A8                  | 12        | 1.17%   |
| Intel Pentium Dual      | 11        | 1.07%   |
| AMD E1                  | 11        | 1.07%   |
| AMD E                   | 10        | 0.97%   |
| AMD A4                  | 8         | 0.78%   |
| AMD E2                  | 7         | 0.68%   |
| AMD Athlon              | 7         | 0.68%   |
| AMD Ryzen 5 PRO         | 6         | 0.58%   |
| Intel Genuine           | 4         | 0.39%   |
| Intel Core i9           | 4         | 0.39%   |
| Intel Core 2            | 4         | 0.39%   |
| AMD Turion II Dual-Core | 4         | 0.39%   |
| AMD A12                 | 4         | 0.39%   |
| Intel Pentium Silver    | 3         | 0.29%   |
| Intel Core 2 Quad       | 3         | 0.29%   |
| Intel Celeron Dual-Core | 3         | 0.29%   |
| AMD Ryzen 7 PRO         | 3         | 0.29%   |
| AMD Phenom              | 3         | 0.29%   |
| AMD Athlon II X2        | 3         | 0.29%   |
| AMD Athlon II           | 3         | 0.29%   |
| Intel Pentium Gold      | 2         | 0.19%   |
| Intel Pentium 4         | 2         | 0.19%   |
| Intel Celeron M         | 2         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 468       | 45.57%  |
| 4       | 368       | 35.83%  |
| 6       | 67        | 6.52%   |
| 8       | 62        | 6.04%   |
| 1       | 19        | 1.85%   |
| 12      | 11        | 1.07%   |
| 3       | 9         | 0.88%   |
| 10      | 7         | 0.68%   |
| Unknown | 6         | 0.58%   |
| 16      | 5         | 0.49%   |
| 14      | 4         | 0.39%   |
| 20      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1012      | 99.31%  |
| 2       | 5         | 0.49%   |
| 4       | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 666       | 65.04%  |
| 1       | 352       | 34.38%  |
| Unknown | 6         | 0.59%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 992       | 97.16%  |
| Unknown        | 15        | 1.47%   |
| 32-bit         | 8         | 0.78%   |
| 64-bit         | 6         | 0.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 325       | 30.57%  |
| 0x206a7    | 47        | 4.42%   |
| 0x306a9    | 37        | 3.48%   |
| 0x406e3    | 31        | 2.92%   |
| 0x806e9    | 26        | 2.45%   |
| 0x1067a    | 26        | 2.45%   |
| 0x806ec    | 24        | 2.26%   |
| 0x306c3    | 24        | 2.26%   |
| 0x40651    | 23        | 2.16%   |
| 0x906ea    | 20        | 1.88%   |
| 0x30678    | 20        | 1.88%   |
| 0x08108109 | 20        | 1.88%   |
| 0x906e9    | 16        | 1.51%   |
| 0x806ea    | 16        | 1.51%   |
| 0x806c1    | 16        | 1.51%   |
| 0x6fd      | 15        | 1.41%   |
| 0x20655    | 15        | 1.41%   |
| 0x08108102 | 15        | 1.41%   |
| 0x406c4    | 13        | 1.22%   |
| 0x0810100b | 13        | 1.22%   |
| 0x08701021 | 12        | 1.13%   |
| 0xa0652    | 11        | 1.03%   |
| 0x0a50000c | 11        | 1.03%   |
| 0x05000119 | 11        | 1.03%   |
| 0x306d4    | 10        | 0.94%   |
| 0x506c9    | 9         | 0.85%   |
| 0x10676    | 9         | 0.85%   |
| 0x08600106 | 9         | 0.85%   |
| 0x0700010f | 9         | 0.85%   |
| 0x06000852 | 9         | 0.85%   |
| 0x706a8    | 8         | 0.75%   |
| 0x07030105 | 8         | 0.75%   |
| 0x506e3    | 7         | 0.66%   |
| 0x406c3    | 7         | 0.66%   |
| 0x06001119 | 7         | 0.66%   |
| 0x010000c8 | 7         | 0.66%   |
| 0xa0653    | 6         | 0.56%   |
| 0x806eb    | 6         | 0.56%   |
| 0x706e5    | 6         | 0.56%   |
| 0x706a1    | 6         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 179       | 17.5%   |
| Haswell          | 77        | 7.53%   |
| SandyBridge      | 66        | 6.45%   |
| IvyBridge        | 56        | 5.47%   |
| Skylake          | 52        | 5.08%   |
| Silvermont       | 48        | 4.69%   |
| Zen+             | 47        | 4.59%   |
| Penryn           | 46        | 4.5%    |
| Zen 2            | 37        | 3.62%   |
| Unknown          | 31        | 3.03%   |
| TigerLake        | 30        | 2.93%   |
| Zen 3            | 26        | 2.54%   |
| Westmere         | 26        | 2.54%   |
| Piledriver       | 25        | 2.44%   |
| Core             | 25        | 2.44%   |
| Zen              | 24        | 2.35%   |
| CometLake        | 24        | 2.35%   |
| Excavator        | 21        | 2.05%   |
| K10              | 20        | 1.96%   |
| Goldmont plus    | 19        | 1.86%   |
| Broadwell        | 19        | 1.86%   |
| Bobcat           | 18        | 1.76%   |
| Icelake          | 17        | 1.66%   |
| Puma             | 13        | 1.27%   |
| Jaguar           | 13        | 1.27%   |
| Goldmont         | 11        | 1.08%   |
| Bonnell          | 10        | 0.98%   |
| K10 Llano        | 7         | 0.68%   |
| Alderlake Hybrid | 7         | 0.68%   |
| Steamroller      | 5         | 0.49%   |
| K8 Hammer        | 5         | 0.49%   |
| P6               | 4         | 0.39%   |
| Nehalem          | 4         | 0.39%   |
| Bulldozer        | 4         | 0.39%   |
| Tremont          | 3         | 0.29%   |
| NetBurst         | 2         | 0.2%    |
| K8 & K10 hybrid  | 1         | 0.1%    |
| Gracemont        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 616       | 51.42%  |
| AMD                              | 310       | 25.88%  |
| Nvidia                           | 262       | 21.87%  |
| Silicon Integrated Systems [SiS] | 4         | 0.33%   |
| Matrox Electronics Systems       | 3         | 0.25%   |
| ATI Technologies                 | 2         | 0.17%   |
| VIA Technologies                 | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 56        | 4.47%   |
| Intel HD Graphics 620                                                                    | 43        | 3.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 3.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 2.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 2.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 2.08%   |
| Intel UHD Graphics 620                                                                   | 24        | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 22        | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 1.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 1.6%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 19        | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 1.44%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 17        | 1.36%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 1.36%   |
| Intel HD Graphics 630                                                                    | 16        | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.12%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.12%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 12        | 0.96%   |
| Intel HD Graphics 5500                                                                   | 12        | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.88%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 10        | 0.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.72%   |
| Intel HD Graphics 530                                                                    | 9         | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 0.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 0.64%   |
| AMD Lucienne                                                                             | 8         | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 7         | 0.56%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 7         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 463       | 45.26%  |
| 1 x AMD        | 224       | 21.9%   |
| 1 x Nvidia     | 120       | 11.73%  |
| Intel + Nvidia | 120       | 11.73%  |
| 2 x AMD        | 36        | 3.52%   |
| Intel + AMD    | 27        | 2.64%   |
| AMD + Nvidia   | 23        | 2.25%   |
| 1 x SiS        | 4         | 0.39%   |
| 1 x Matrox     | 2         | 0.2%    |
| Other          | 1         | 0.1%    |
| 2 x Intel      | 1         | 0.1%    |
| 1 x VIA        | 1         | 0.1%    |
| AMD + Matrox   | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 853       | 82.98%  |
| Proprietary | 143       | 13.91%  |
| Unknown     | 32        | 3.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 623       | 59.62%  |
| 0.01-0.5   | 125       | 11.96%  |
| 1.01-2.0   | 124       | 11.87%  |
| 0.51-1.0   | 73        | 6.99%   |
| 3.01-4.0   | 52        | 4.98%   |
| 5.01-6.0   | 15        | 1.44%   |
| 7.01-8.0   | 13        | 1.24%   |
| 8.01-16.0  | 11        | 1.05%   |
| 2.01-3.0   | 9         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 174       | 15.4%   |
| AU Optronics            | 154       | 13.63%  |
| BOE                     | 138       | 12.21%  |
| Chimei Innolux          | 135       | 11.95%  |
| LG Display              | 86        | 7.61%   |
| Goldstar                | 81        | 7.17%   |
| Hewlett-Packard         | 40        | 3.54%   |
| Lenovo                  | 27        | 2.39%   |
| Dell                    | 25        | 2.21%   |
| AOC                     | 24        | 2.12%   |
| ViewSonic               | 18        | 1.59%   |
| PANDA                   | 14        | 1.24%   |
| Apple                   | 14        | 1.24%   |
| Sony                    | 13        | 1.15%   |
| LG Electronics          | 12        | 1.06%   |
| Unknown                 | 11        | 0.97%   |
| Sharp                   | 10        | 0.88%   |
| Chi Mei Optoelectronics | 10        | 0.88%   |
| ASUSTek Computer        | 10        | 0.88%   |
| SAC                     | 9         | 0.8%    |
| InfoVision              | 8         | 0.71%   |
| Envision                | 8         | 0.71%   |
| Acer                    | 7         | 0.62%   |
| ___                     | 6         | 0.53%   |
| MSI                     | 6         | 0.53%   |
| KTC                     | 6         | 0.53%   |
| CSO                     | 6         | 0.53%   |
| Ancor Communications    | 6         | 0.53%   |
| Valve                   | 5         | 0.44%   |
| LG Philips              | 5         | 0.44%   |
| Packard Bell            | 4         | 0.35%   |
| HKC                     | 4         | 0.35%   |
| Hitachi                 | 4         | 0.35%   |
| SLD                     | 3         | 0.27%   |
| Plain Tree Systems      | 3         | 0.27%   |
| Philips                 | 3         | 0.27%   |
| Mi                      | 3         | 0.27%   |
| Unknown (XXX)           | 2         | 0.18%   |
| STA                     | 2         | 0.18%   |
| SKY                     | 2         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 12        | 1.04%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 11        | 0.95%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 11        | 0.95%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 11        | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 10        | 0.86%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 9         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 9         | 0.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 8         | 0.69%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7         | 0.6%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 7         | 0.6%    |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                 | 6         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 6         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 6         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 6         | 0.52%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 6         | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.52%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 5         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 5         | 0.43%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 5         | 0.43%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 5         | 0.43%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 5         | 0.43%   |
| ___ LCDTV16 ___9000 1360x768                                          | 4         | 0.35%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 4         | 0.35%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 4         | 0.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 4         | 0.35%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.35%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 4         | 0.35%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 4         | 0.35%   |
| Goldstar HDR WFHD GSM5B9F 2560x1080 798x334mm 34.1-inch               | 4         | 0.35%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 4         | 0.35%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 4         | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 4         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 385       | 35.68%  |
| 1366x768 (WXGA)    | 372       | 34.48%  |
| 3840x2160 (4K)     | 48        | 4.45%   |
| 1600x900 (HD+)     | 41        | 3.8%    |
| 1360x768           | 35        | 3.24%   |
| 1440x900 (WXGA+)   | 28        | 2.59%   |
| 1280x800 (WXGA)    | 25        | 2.32%   |
| 1280x1024 (SXGA)   | 19        | 1.76%   |
| 2560x1080          | 18        | 1.67%   |
| 2560x1440 (QHD)    | 16        | 1.48%   |
| 1920x1200 (WUXGA)  | 13        | 1.2%    |
| 1680x1050 (WSXGA+) | 13        | 1.2%    |
| Unknown            | 7         | 0.65%   |
| 800x1280           | 6         | 0.56%   |
| 3440x1440          | 6         | 0.56%   |
| 2560x1600          | 6         | 0.56%   |
| 3840x1080          | 5         | 0.46%   |
| 2160x1440          | 4         | 0.37%   |
| 1024x768 (XGA)     | 4         | 0.37%   |
| 1024x600           | 4         | 0.37%   |
| 3840x1100          | 3         | 0.28%   |
| 1920x540           | 3         | 0.28%   |
| 3286x1080          | 2         | 0.19%   |
| 2880x1800          | 2         | 0.19%   |
| 1024x576           | 2         | 0.19%   |
| 5760x1080          | 1         | 0.09%   |
| 5440x1800          | 1         | 0.09%   |
| 3840x2400          | 1         | 0.09%   |
| 3840x1600          | 1         | 0.09%   |
| 3000x2000          | 1         | 0.09%   |
| 2288x1287          | 1         | 0.09%   |
| 1920x515           | 1         | 0.09%   |
| 1680x945           | 1         | 0.09%   |
| 1600x1200          | 1         | 0.09%   |
| 1280x960           | 1         | 0.09%   |
| 1280x768           | 1         | 0.09%   |
| 1280x720 (HD)      | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 252       | 22.22%  |
| 13      | 190       | 16.75%  |
| 14      | 161       | 14.2%   |
| 21      | 74        | 6.53%   |
| 23      | 73        | 6.44%   |
| Unknown | 39        | 3.44%   |
| 27      | 35        | 3.09%   |
| 24      | 34        | 3%      |
| 17      | 32        | 2.82%   |
| 18      | 31        | 2.73%   |
| 19      | 30        | 2.65%   |
| 34      | 23        | 2.03%   |
| 31      | 19        | 1.68%   |
| 20      | 17        | 1.5%    |
| 12      | 17        | 1.5%    |
| 11      | 17        | 1.5%    |
| 72      | 11        | 0.97%   |
| 32      | 11        | 0.97%   |
| 16      | 9         | 0.79%   |
| 84      | 8         | 0.71%   |
| 10      | 8         | 0.71%   |
| 22      | 7         | 0.62%   |
| 54      | 6         | 0.53%   |
| 48      | 5         | 0.44%   |
| 40      | 5         | 0.44%   |
| 7       | 5         | 0.44%   |
| 49      | 2         | 0.18%   |
| 46      | 2         | 0.18%   |
| 37      | 2         | 0.18%   |
| 28      | 2         | 0.18%   |
| 142     | 1         | 0.09%   |
| 65      | 1         | 0.09%   |
| 58      | 1         | 0.09%   |
| 52      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 3       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 551       | 49.37%  |
| 401-500        | 141       | 12.63%  |
| 501-600        | 130       | 11.65%  |
| 201-300        | 100       | 8.96%   |
| 351-400        | 40        | 3.58%   |
| Unknown        | 39        | 3.49%   |
| 701-800        | 34        | 3.05%   |
| 601-700        | 29        | 2.6%    |
| 1501-2000      | 19        | 1.7%    |
| 1001-1500      | 18        | 1.61%   |
| 801-900        | 7         | 0.63%   |
| 1-100          | 6         | 0.54%   |
| More than 2000 | 1         | 0.09%   |
| 901-1000       | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 801       | 80.5%   |
| 16/10   | 91        | 9.15%   |
| Unknown | 29        | 2.91%   |
| 21/9    | 23        | 2.31%   |
| 5/4     | 20        | 2.01%   |
| 4/3     | 9         | 0.9%    |
| 3/2     | 6         | 0.6%    |
| 0.67    | 5         | 0.5%    |
| 32/9    | 3         | 0.3%    |
| 3.40    | 3         | 0.3%    |
| 1.96    | 2         | 0.2%    |
| 6/5     | 1         | 0.1%    |
| 3.73    | 1         | 0.1%    |
| 1.00    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 299       | 26.53%  |
| 101-110        | 253       | 22.45%  |
| 201-250        | 159       | 14.11%  |
| 151-200        | 63        | 5.59%   |
| 351-500        | 55        | 4.88%   |
| 71-80          | 49        | 4.35%   |
| Unknown        | 39        | 3.46%   |
| 141-150        | 38        | 3.37%   |
| 301-350        | 36        | 3.19%   |
| More than 1000 | 31        | 2.75%   |
| 51-60          | 20        | 1.77%   |
| 121-130        | 15        | 1.33%   |
| 501-1000       | 15        | 1.33%   |
| 61-70          | 14        | 1.24%   |
| 251-300        | 9         | 0.8%    |
| 41-50          | 8         | 0.71%   |
| 111-120        | 8         | 0.71%   |
| 131-140        | 7         | 0.62%   |
| 1-40           | 6         | 0.53%   |
| 91-100         | 3         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 424       | 38.58%  |
| 51-100        | 275       | 25.02%  |
| 121-160       | 242       | 22.02%  |
| 161-240       | 57        | 5.19%   |
| 1-50          | 47        | 4.28%   |
| Unknown       | 39        | 3.55%   |
| More than 240 | 15        | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 804       | 76.94%  |
| 2     | 186       | 17.8%   |
| 0     | 37        | 3.54%   |
| 3     | 17        | 1.63%   |
| 4     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 667       | 42.76%  |
| Intel                            | 380       | 24.36%  |
| Qualcomm Atheros                 | 185       | 11.86%  |
| Broadcom                         | 85        | 5.45%   |
| Ralink                           | 33        | 2.12%   |
| Broadcom Limited                 | 24        | 1.54%   |
| Ralink Technology                | 21        | 1.35%   |
| TP-Link                          | 20        | 1.28%   |
| Xiaomi                           | 15        | 0.96%   |
| MediaTek                         | 15        | 0.96%   |
| Marvell Technology Group         | 15        | 0.96%   |
| Huawei Technologies              | 15        | 0.96%   |
| Samsung Electronics              | 10        | 0.64%   |
| Qualcomm Atheros Communications  | 8         | 0.51%   |
| Nvidia                           | 8         | 0.51%   |
| D-Link System                    | 7         | 0.45%   |
| D-Link                           | 7         | 0.45%   |
| Microsoft                        | 5         | 0.32%   |
| Silicon Integrated Systems [SiS] | 4         | 0.26%   |
| Motorola PCS                     | 4         | 0.26%   |
| JMicron Technology               | 4         | 0.26%   |
| ICS Advent                       | 4         | 0.26%   |
| DisplayLink                      | 3         | 0.19%   |
| ASIX Electronics                 | 3         | 0.19%   |
| VIA Technologies                 | 2         | 0.13%   |
| Lenovo                           | 2         | 0.13%   |
| Spreadtrum Communications        | 1         | 0.06%   |
| Qualcomm                         | 1         | 0.06%   |
| Qcom                             | 1         | 0.06%   |
| Padix (Rockfire)                 | 1         | 0.06%   |
| Oculus VR                        | 1         | 0.06%   |
| Netchip Technology               | 1         | 0.06%   |
| Microchip Technology             | 1         | 0.06%   |
| Mercucys                         | 1         | 0.06%   |
| Manta                            | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| ASUSTek Computer                 | 1         | 0.06%   |
| Arduino SA                       | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 421       | 22.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 120       | 6.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 41        | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 34        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 33        | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 31        | 1.67%   |
| Intel Wi-Fi 6 AX200                                                    | 31        | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 29        | 1.57%   |
| Intel Wireless 8265 / 8275                                             | 27        | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 26        | 1.4%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 22        | 1.19%   |
| Intel Wi-Fi 6 AX201                                                    | 22        | 1.19%   |
| Intel Wireless 8260                                                    | 21        | 1.13%   |
| Intel Wireless 7260                                                    | 21        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 20        | 1.08%   |
| Intel Wireless 7265                                                    | 20        | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 20        | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 18        | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                          | 18        | 0.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 17        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 16        | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 15        | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 13        | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 0.7%    |
| Huawei STG-LX1                                                         | 13        | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 12        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 12        | 0.65%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 12        | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 12        | 0.65%   |
| Ralink MT7601U Wireless Adapter                                        | 11        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                   | 11        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 11        | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 11        | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 10        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 9         | 0.49%   |
| Intel Wireless 3165                                                    | 9         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 331       | 36.45%  |
| Realtek Semiconductor           | 223       | 24.56%  |
| Qualcomm Atheros                | 157       | 17.29%  |
| Broadcom                        | 68        | 7.49%   |
| Ralink                          | 33        | 3.63%   |
| Ralink Technology               | 21        | 2.31%   |
| TP-Link                         | 19        | 2.09%   |
| Broadcom Limited                | 16        | 1.76%   |
| MediaTek                        | 12        | 1.32%   |
| Qualcomm Atheros Communications | 8         | 0.88%   |
| D-Link                          | 6         | 0.66%   |
| Microsoft                       | 5         | 0.55%   |
| D-Link System                   | 4         | 0.44%   |
| Qualcomm                        | 1         | 0.11%   |
| Qcom                            | 1         | 0.11%   |
| Mercucys                        | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| ASUSTek Computer                | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 4.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 3.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 3.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 31        | 3.41%   |
| Intel Wi-Fi 6 AX200                                                     | 31        | 3.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 3.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 3.19%   |
| Intel Wireless 8265 / 8275                                              | 27        | 2.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 26        | 2.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 22        | 2.42%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 2.42%   |
| Intel Wireless 8260                                                     | 21        | 2.31%   |
| Intel Wireless 7260                                                     | 21        | 2.31%   |
| Intel Wireless 7265                                                     | 20        | 2.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 2.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 18        | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 17        | 1.87%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 1.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 15        | 1.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 12        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 1.32%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.21%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 0.99%   |
| Intel Wireless 3165                                                     | 9         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.99%   |
| Realtek 802.11ac NIC                                                    | 8         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 7         | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 0.77%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 7         | 0.77%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 7         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 587       | 63.53%  |
| Intel                            | 157       | 16.99%  |
| Qualcomm Atheros                 | 40        | 4.33%   |
| Broadcom                         | 32        | 3.46%   |
| Xiaomi                           | 15        | 1.62%   |
| Marvell Technology Group         | 15        | 1.62%   |
| Huawei Technologies              | 15        | 1.62%   |
| Samsung Electronics              | 9         | 0.97%   |
| Nvidia                           | 8         | 0.87%   |
| Broadcom Limited                 | 8         | 0.87%   |
| Silicon Integrated Systems [SiS] | 4         | 0.43%   |
| JMicron Technology               | 4         | 0.43%   |
| ICS Advent                       | 4         | 0.43%   |
| Motorola PCS                     | 3         | 0.32%   |
| MediaTek                         | 3         | 0.32%   |
| DisplayLink                      | 3         | 0.32%   |
| D-Link System                    | 3         | 0.32%   |
| ASIX Electronics                 | 3         | 0.32%   |
| VIA Technologies                 | 2         | 0.22%   |
| Lenovo                           | 2         | 0.22%   |
| TP-Link                          | 1         | 0.11%   |
| Spreadtrum Communications        | 1         | 0.11%   |
| Netchip Technology               | 1         | 0.11%   |
| Microchip Technology             | 1         | 0.11%   |
| HMD Global                       | 1         | 0.11%   |
| D-Link                           | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 421       | 44.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 120       | 12.82%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 20        | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 1.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 13        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 1.39%   |
| Huawei STG-LX1                                                         | 13        | 1.39%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 1.28%   |
| Intel Ethernet Connection (4) I219-V                                   | 11        | 1.18%   |
| Intel I211 Gigabit Network Connection                                  | 9         | 0.96%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                   | 7         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 6         | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.64%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 0.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 4         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.43%   |
| Nvidia MCP61 Ethernet                                                  | 4         | 0.43%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.43%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.43%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3         | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.32%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3         | 0.32%   |
| Motorola PCS moto g52                                                  | 3         | 0.32%   |
| MediaTek File-CD Gadget                                                | 3         | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 3         | 0.32%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 864       | 49.91%  |
| WiFi     | 860       | 49.68%  |
| Modem    | 4         | 0.23%   |
| Unknown  | 3         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 671       | 63.36%  |
| Ethernet | 388       | 36.64%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 620       | 60.43%  |
| 1     | 366       | 35.67%  |
| 3     | 19        | 1.85%   |
| 0     | 17        | 1.66%   |
| 4     | 3         | 0.29%   |
| 6     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 919       | 89.05%  |
| Yes  | 113       | 10.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 280       | 39.6%   |
| Realtek Semiconductor           | 135       | 19.09%  |
| Qualcomm Atheros Communications | 51        | 7.21%   |
| Broadcom                        | 45        | 6.36%   |
| Lite-On Technology              | 38        | 5.37%   |
| IMC Networks                    | 34        | 4.81%   |
| Cambridge Silicon Radio         | 33        | 4.67%   |
| Foxconn / Hon Hai               | 22        | 3.11%   |
| Apple                           | 21        | 2.97%   |
| Ralink                          | 12        | 1.7%    |
| Dell                            | 8         | 1.13%   |
| Realtek                         | 7         | 0.99%   |
| Hewlett-Packard                 | 6         | 0.85%   |
| ASUSTek Computer                | 4         | 0.57%   |
| Toshiba                         | 3         | 0.42%   |
| Ralink Technology               | 3         | 0.42%   |
| Foxconn International           | 2         | 0.28%   |
| USI                             | 1         | 0.14%   |
| MediaTek                        | 1         | 0.14%   |
| Alps Electric                   | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 104       | 14.71%  |
| Realtek Bluetooth Radio                             | 79        | 11.17%  |
| Intel AX201 Bluetooth                               | 52        | 7.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 51        | 7.21%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 43        | 6.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 33        | 4.67%   |
| Intel AX200 Bluetooth                               | 31        | 4.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 3.39%   |
| IMC Networks Bluetooth Radio                        | 16        | 2.26%   |
| Intel AX210 Bluetooth                               | 15        | 2.12%   |
| Ralink RT3290 Bluetooth                             | 12        | 1.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 1.56%   |
| Intel Bluetooth Device                              | 11        | 1.56%   |
| Apple Bluetooth USB Host Controller                 | 11        | 1.56%   |
| Lite-On Bluetooth Device                            | 10        | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 1.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 10        | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.27%   |
| IMC Networks Bluetooth Device                       | 9         | 1.27%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 1.13%   |
| Apple Bluetooth Host Controller                     | 8         | 1.13%   |
| Realtek Bluetooth Radio                             | 7         | 0.99%   |
| Broadcom Bluetooth 3.0 Dongle                       | 7         | 0.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.85%   |
| IMC Networks Wireless_Device                        | 6         | 0.85%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.71%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.71%   |
| Broadcom BCM2070 Bluetooth Device                   | 5         | 0.71%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.57%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.57%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 0.57%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.57%   |
| Toshiba Bluetooth Device                            | 3         | 0.42%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 3         | 0.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.42%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 709       | 54.04%  |
| AMD                                          | 313       | 23.86%  |
| Nvidia                                       | 172       | 13.11%  |
| C-Media Electronics                          | 15        | 1.14%   |
| Logitech                                     | 14        | 1.07%   |
| Creative Labs                                | 8         | 0.61%   |
| JMTek                                        | 7         | 0.53%   |
| Generalplus Technology                       | 7         | 0.53%   |
| Kingston Technology                          | 6         | 0.46%   |
| Creative Technology                          | 6         | 0.46%   |
| Razer USA                                    | 5         | 0.38%   |
| Texas Instruments                            | 4         | 0.3%    |
| Silicon Integrated Systems [SiS]             | 4         | 0.3%    |
| Focusrite-Novation                           | 4         | 0.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.23%   |
| VIA Technologies                             | 2         | 0.15%   |
| Trust                                        | 2         | 0.15%   |
| Microsoft                                    | 2         | 0.15%   |
| Lenovo                                       | 2         | 0.15%   |
| Corsair                                      | 2         | 0.15%   |
| Arturia                                      | 2         | 0.15%   |
| Apple                                        | 2         | 0.15%   |
| Unknown                                      | 1         | 0.08%   |
| Synaptics                                    | 1         | 0.08%   |
| Shenzhen Riitek Technology                   | 1         | 0.08%   |
| Realtek Semiconductor                        | 1         | 0.08%   |
| PreSonus Audio Electronics                   | 1         | 0.08%   |
| Plantronics                                  | 1         | 0.08%   |
| Pixart Imaging                               | 1         | 0.08%   |
| Native Instruments                           | 1         | 0.08%   |
| Micro Star International                     | 1         | 0.08%   |
| Medeli Electronics                           | 1         | 0.08%   |
| Hewlett-Packard                              | 1         | 0.08%   |
| GYROCOM C&C                                  | 1         | 0.08%   |
| ESS Technology                               | 1         | 0.08%   |
| eMPIA Technology                             | 1         | 0.08%   |
| EasyPass Industrial                          | 1         | 0.08%   |
| DigiTech                                     | 1         | 0.08%   |
| CMX Systems                                  | 1         | 0.08%   |
| Blue Microphones                             | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 111       | 6.91%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 109       | 6.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 62        | 3.86%   |
| AMD FCH Azalia Controller                                                                         | 59        | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 52        | 3.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 52        | 3.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 42        | 2.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 42        | 2.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 36        | 2.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 35        | 2.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 33        | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 30        | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 29        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 27        | 1.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 27        | 1.68%   |
| Intel 8 Series HD Audio Controller                                                                | 27        | 1.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 27        | 1.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 1.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 23        | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 22        | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 1.18%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 17        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 0.81%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 11        | 0.68%   |
| AMD Trinity HDMI Audio Controller                                                                 | 11        | 0.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 11        | 0.68%   |
| AMD High Definition Audio Controller                                                              | 11        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 151       | 24.63%  |
| SK hynix            | 109       | 17.78%  |
| Kingston            | 77        | 12.56%  |
| Micron Technology   | 75        | 12.23%  |
| Crucial             | 69        | 11.26%  |
| Unknown             | 33        | 5.38%   |
| Ramaxel Technology  | 21        | 3.43%   |
| Corsair             | 18        | 2.94%   |
| A-DATA Technology   | 12        | 1.96%   |
| G.Skill             | 9         | 1.47%   |
| Avant               | 6         | 0.98%   |
| Unknown (ABCD)      | 4         | 0.65%   |
| Patriot             | 3         | 0.49%   |
| Nanya Technology    | 3         | 0.49%   |
| Elpida              | 3         | 0.49%   |
| Unknown             | 3         | 0.49%   |
| Hikvision           | 2         | 0.33%   |
| Unknown (0BF7)      | 1         | 0.16%   |
| Unknown (090E)      | 1         | 0.16%   |
| Unknown (08C8)      | 1         | 0.16%   |
| Team                | 1         | 0.16%   |
| Smart               | 1         | 0.16%   |
| PNY                 | 1         | 0.16%   |
| Lexar               | 1         | 0.16%   |
| Kreton              | 1         | 0.16%   |
| Kllisre             | 1         | 0.16%   |
| Goldenmars          | 1         | 0.16%   |
| GLOWAY              | 1         | 0.16%   |
| Atermiter           | 1         | 0.16%   |
| ASint Technology    | 1         | 0.16%   |
| Ankowall            | 1         | 0.16%   |
| 48spaces            | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 12        | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 10        | 1.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 1.24%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 8         | 1.24%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 8         | 1.24%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.93%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 0.93%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 6         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 5         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 5         | 0.77%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 5         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.77%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.77%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 5         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s               | 5         | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 4         | 0.62%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 4         | 0.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 4         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.62%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.62%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 4         | 0.62%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 4         | 0.62%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 4         | 0.62%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s                 | 4         | 0.62%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 4         | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 3         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.46%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 3         | 0.46%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 3         | 0.46%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 3         | 0.46%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 3         | 0.46%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s                 | 3         | 0.46%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 3         | 0.46%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s             | 3         | 0.46%   |
| Crucial RAM CT8G4SFRA32A.M4FF 8GB SODIMM DDR4 3200MT/s              | 3         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 249       | 51.88%  |
| DDR3    | 157       | 32.71%  |
| LPDDR4  | 21        | 4.38%   |
| DDR2    | 16        | 3.33%   |
| LPDDR3  | 14        | 2.92%   |
| SDRAM   | 13        | 2.71%   |
| Unknown | 3         | 0.63%   |
| LPDDR5  | 2         | 0.42%   |
| DDR5    | 2         | 0.42%   |
| DDR     | 2         | 0.42%   |
| RAM     | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 323       | 67.86%  |
| DIMM         | 115       | 24.16%  |
| Row Of Chips | 36        | 7.56%   |
| Chip         | 1         | 0.21%   |
| Unknown      | 1         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 227       | 41.58%  |
| 4096  | 182       | 33.33%  |
| 16384 | 57        | 10.44%  |
| 2048  | 57        | 10.44%  |
| 32768 | 16        | 2.93%   |
| 1024  | 6         | 1.1%    |
| 64    | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 110       | 19.75%  |
| 2667    | 100       | 17.95%  |
| 3200    | 84        | 15.08%  |
| 2400    | 50        | 8.98%   |
| 2133    | 36        | 6.46%   |
| 1333    | 29        | 5.21%   |
| 1334    | 18        | 3.23%   |
| Unknown | 13        | 2.33%   |
| 3266    | 12        | 2.15%   |
| 4267    | 11        | 1.97%   |
| 667     | 11        | 1.97%   |
| 3600    | 10        | 1.8%    |
| 800     | 7         | 1.26%   |
| 3466    | 6         | 1.08%   |
| 2666    | 5         | 0.9%    |
| 1867    | 5         | 0.9%    |
| 3733    | 4         | 0.72%   |
| 2933    | 4         | 0.72%   |
| 1866    | 4         | 0.72%   |
| 1067    | 4         | 0.72%   |
| 6400    | 3         | 0.54%   |
| 4199    | 3         | 0.54%   |
| 3800    | 3         | 0.54%   |
| 2048    | 3         | 0.54%   |
| 1066    | 3         | 0.54%   |
| 4266    | 2         | 0.36%   |
| 3400    | 2         | 0.36%   |
| 3066    | 2         | 0.36%   |
| 3000    | 2         | 0.36%   |
| 975     | 2         | 0.36%   |
| 8400    | 1         | 0.18%   |
| 4800    | 1         | 0.18%   |
| 4000    | 1         | 0.18%   |
| 3666    | 1         | 0.18%   |
| 3134    | 1         | 0.18%   |
| 2800    | 1         | 0.18%   |
| 933     | 1         | 0.18%   |
| 533     | 1         | 0.18%   |
| 400     | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 25.93%  |
| Brother Industries  | 7         | 25.93%  |
| Seiko Epson         | 6         | 22.22%  |
| Canon               | 6         | 22.22%  |
| QinHeng Electronics | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Brother HL-1200 series     | 4         | 14.81%  |
| Canon MF110/910 Series     | 2         | 7.41%   |
| Brother DCP-1600           | 2         | 7.41%   |
| Seiko Epson XP-2100 Series | 1         | 3.7%    |
| Seiko Epson Printer        | 1         | 3.7%    |
| Seiko Epson L355 Series    | 1         | 3.7%    |
| Seiko Epson L3150 Series   | 1         | 3.7%    |
| Seiko Epson L3110 Series   | 1         | 3.7%    |
| Seiko Epson L210 Series    | 1         | 3.7%    |
| QinHeng CH340S             | 1         | 3.7%    |
| HP Officejet 4500 G510a-f  | 1         | 3.7%    |
| HP LaserJet P1005          | 1         | 3.7%    |
| HP DeskJet 5820 series     | 1         | 3.7%    |
| HP Deskjet 4640 series     | 1         | 3.7%    |
| HP Deskjet 4620 series     | 1         | 3.7%    |
| HP DeskJet 2130 series     | 1         | 3.7%    |
| HP Deskjet 2050 J510       | 1         | 3.7%    |
| Canon PIXMA MP250          | 1         | 3.7%    |
| Canon LBP6000              | 1         | 3.7%    |
| Canon G2000 series         | 1         | 3.7%    |
| Canon G1000 series         | 1         | 3.7%    |
| Brother HL-1210W series    | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 1         | 25%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |
| Canon CanoScan D1250U2                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 172       | 22.78%  |
| IMC Networks                           | 92        | 12.19%  |
| Realtek Semiconductor                  | 55        | 7.28%   |
| Microdia                               | 49        | 6.49%   |
| Cheng Uei Precision Industry (Foxlink) | 47        | 6.23%   |
| Sunplus Innovation Technology          | 39        | 5.17%   |
| Quanta                                 | 38        | 5.03%   |
| Bison Electronics                      | 30        | 3.97%   |
| Suyin                                  | 24        | 3.18%   |
| Lite-On Technology                     | 24        | 3.18%   |
| Silicon Motion                         | 19        | 2.52%   |
| Logitech                               | 17        | 2.25%   |
| Apple                                  | 17        | 2.25%   |
| Syntek                                 | 15        | 1.99%   |
| Acer                                   | 12        | 1.59%   |
| Luxvisions Innotech Limited            | 10        | 1.32%   |
| Generalplus Technology                 | 7         | 0.93%   |
| Z-Star Microelectronics                | 6         | 0.79%   |
| Ricoh                                  | 6         | 0.79%   |
| Lenovo                                 | 6         | 0.79%   |
| Microsoft                              | 5         | 0.66%   |
| Alcor Micro                            | 5         | 0.66%   |
| Sonix Technology                       | 4         | 0.53%   |
| Samsung Electronics                    | 4         | 0.53%   |
| Jieli Technology                       | 4         | 0.53%   |
| Importek                               | 4         | 0.53%   |
| YGTek                                  | 3         | 0.4%    |
| USB Camera CS                          | 3         | 0.4%    |
| KYE Systems (Mouse Systems)            | 3         | 0.4%    |
| webcamvendor                           | 2         | 0.26%   |
| Unknown                                | 2         | 0.26%   |
| SunplusIT                              | 2         | 0.26%   |
| OmniVision Technologies                | 2         | 0.26%   |
| Leap Motion                            | 2         | 0.26%   |
| Huawei Technologies                    | 2         | 0.26%   |
| Foxconn / Hon Hai                      | 2         | 0.26%   |
| DigiTech                               | 2         | 0.26%   |
| ALi                                    | 2         | 0.26%   |
| 8SSC20F27114V1SR0BK1X4S                | 2         | 0.26%   |
| 04004000_P040200_SN0002                | 2         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 36        | 4.73%   |
| Chicony Integrated Camera                                       | 24        | 3.15%   |
| IMC Networks Integrated Camera                                  | 22        | 2.89%   |
| Chicony HD WebCam                                               | 18        | 2.37%   |
| Realtek Integrated_Webcam_HD                                    | 12        | 1.58%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 12        | 1.58%   |
| Bison Integrated Camera                                         | 12        | 1.58%   |
| Chicony HP Wide Vision HD Camera                                | 10        | 1.31%   |
| Syntek Integrated Camera                                        | 9         | 1.18%   |
| Quanta HP TrueVision HD Camera                                  | 9         | 1.18%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 1.18%   |
| Lite-On Integrated Camera                                       | 9         | 1.18%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 9         | 1.18%   |
| Chicony HP TrueVision HD Camera                                 | 9         | 1.18%   |
| Chicony EasyCamera                                              | 9         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 9         | 1.18%   |
| Realtek HP Truevision HD                                        | 8         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 8         | 1.05%   |
| Suyin HP TrueVision HD                                          | 7         | 0.92%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 0.92%   |
| Sunplus HP TrueVision HD Camera                                 | 7         | 0.92%   |
| Microdia Webcam Vitade AF                                       | 7         | 0.92%   |
| Lite-On HP Wide Vision HD Camera                                | 7         | 0.92%   |
| Generalplus GENERAL WEBCAM                                      | 7         | 0.92%   |
| Chicony HP Webcam                                               | 7         | 0.92%   |
| Chicony HP TrueVision HD                                        | 7         | 0.92%   |
| Chicony HD User Facing                                          | 7         | 0.92%   |
| Bison EasyCamera                                                | 7         | 0.92%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 7         | 0.92%   |
| Realtek USB Camera                                              | 6         | 0.79%   |
| Chicony VGA WebCam                                              | 6         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 6         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 6         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD         | 6         | 0.79%   |
| Silicon Motion WebCam SCB-1100N                                 | 5         | 0.66%   |
| Quanta VGA WebCam                                               | 5         | 0.66%   |
| Quanta HD User Facing                                           | 5         | 0.66%   |
| Microdia USB 2.0 Camera                                         | 5         | 0.66%   |
| Microdia HP Webcam                                              | 5         | 0.66%   |
| IMC Networks ov9734_azurewave_camera                            | 5         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 43        | 37.72%  |
| Synaptics                  | 28        | 24.56%  |
| Shenzhen Goodix Technology | 14        | 12.28%  |
| Elan Microelectronics      | 10        | 8.77%   |
| Upek                       | 6         | 5.26%   |
| AuthenTec                  | 6         | 5.26%   |
| LighTuning Technology      | 4         | 3.51%   |
| STMicroelectronics         | 2         | 1.75%   |
| Focal-systems.Corp         | 1         | 0.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 8.77%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 7.89%   |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 7.02%   |
| Elan ELAN:ARM-M4                                                           | 8         | 7.02%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 6.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 6.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.39%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 4.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.39%   |
| Synaptics  WBDI                                                            | 4         | 3.51%   |
| AuthenTec AES2810                                                          | 4         | 3.51%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.63%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.75%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.75%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.88%   |
| Validity Sensors VFS491                                                    | 1         | 0.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.88%   |
| Synaptics WBDI                                                             | 1         | 0.88%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.88%   |
| Synaptics UWP WBDI                                                         | 1         | 0.88%   |
| Synaptics Fingerprint scanner                                              | 1         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.88%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.88%   |
| AuthenTec AES1600                                                          | 1         | 0.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 15        | 78.95%  |
| Upek     | 2         | 10.53%  |
| O2 Micro | 2         | 10.53%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 31.58%  |
| Broadcom 5880                                                                | 5         | 26.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 10.53%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Broadcom 58200                                                               | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 746       | 72.08%  |
| 1     | 239       | 23.09%  |
| 2     | 44        | 4.25%   |
| 3     | 4         | 0.39%   |
| 5     | 1         | 0.1%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 114       | 34.65%  |
| Graphics card            | 65        | 19.76%  |
| Net/wireless             | 49        | 14.89%  |
| Multimedia controller    | 19        | 5.78%   |
| Chipcard                 | 18        | 5.47%   |
| Bluetooth                | 16        | 4.86%   |
| Communication controller | 11        | 3.34%   |
| Camera                   | 9         | 2.74%   |
| Unassigned class         | 8         | 2.43%   |
| Sound                    | 6         | 1.82%   |
| Storage                  | 4         | 1.22%   |
| Network                  | 4         | 1.22%   |
| Net/ethernet             | 3         | 0.91%   |
| Card reader              | 2         | 0.61%   |
| Firewire controller      | 1         | 0.3%    |

