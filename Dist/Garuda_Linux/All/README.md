Garuda Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Garuda_Linux/Desktop/README.md) and [notebooks](/Dist/Garuda_Linux/Notebook/README.md).

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

Total: 1250

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | PRO B650-S WIFI             | Desktop     | [bf20a2de9e](https://linux-hardware.org/?probe=bf20a2de9e) | Jan 03, 2025 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [b35c367d58](https://linux-hardware.org/?probe=b35c367d58) | Jan 03, 2025 |
| Dell          | Inspiron 7420               | Notebook    | [643874a1e2](https://linux-hardware.org/?probe=643874a1e2) | Jan 03, 2025 |
| Toshiba       | Satellite Pro S500          | Notebook    | [62a9b2c381](https://linux-hardware.org/?probe=62a9b2c381) | Jan 01, 2025 |
| Dell          | Inspiron 7420               | Notebook    | [f4cfceadf3](https://linux-hardware.org/?probe=f4cfceadf3) | Jan 01, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5c9bfe608f](https://linux-hardware.org/?probe=5c9bfe608f) | Dec 30, 2024 |
| Gigabyte      | B650 EAGLE AX               | Desktop     | [0524509879](https://linux-hardware.org/?probe=0524509879) | Dec 29, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [497960e510](https://linux-hardware.org/?probe=497960e510) | Dec 28, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [dadb3385a3](https://linux-hardware.org/?probe=dadb3385a3) | Dec 26, 2024 |
| MSI           | PRO X870-P WIFI             | Desktop     | [e93d4e3b9c](https://linux-hardware.org/?probe=e93d4e3b9c) | Dec 26, 2024 |
| Lenovo        | ThinkPad T430 2347G2U       | Notebook    | [84d841764a](https://linux-hardware.org/?probe=84d841764a) | Dec 25, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3b87937167](https://linux-hardware.org/?probe=3b87937167) | Dec 25, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [ba5d8c06f6](https://linux-hardware.org/?probe=ba5d8c06f6) | Dec 23, 2024 |
| HP            | 18E7                        | Desktop     | [8aadcc618f](https://linux-hardware.org/?probe=8aadcc618f) | Dec 23, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7812efa4c0](https://linux-hardware.org/?probe=7812efa4c0) | Dec 22, 2024 |
| Schenker      | XMG PRO 16 Studio (M24)     | Notebook    | [cb7a4908df](https://linux-hardware.org/?probe=cb7a4908df) | Dec 21, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [6461bf27f1](https://linux-hardware.org/?probe=6461bf27f1) | Dec 20, 2024 |
| Dell          | 042P49 A00                  | Desktop     | [89c68a1188](https://linux-hardware.org/?probe=89c68a1188) | Dec 18, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d0585de2f5](https://linux-hardware.org/?probe=d0585de2f5) | Dec 18, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [49259c4221](https://linux-hardware.org/?probe=49259c4221) | Dec 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e823717ef8](https://linux-hardware.org/?probe=e823717ef8) | Dec 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1c47a9e4d4](https://linux-hardware.org/?probe=1c47a9e4d4) | Dec 18, 2024 |
| MSI           | PRO X870-P WIFI             | Desktop     | [42ae1f2830](https://linux-hardware.org/?probe=42ae1f2830) | Dec 16, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [5b288ec021](https://linux-hardware.org/?probe=5b288ec021) | Dec 16, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [695e646513](https://linux-hardware.org/?probe=695e646513) | Dec 15, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [00a730597f](https://linux-hardware.org/?probe=00a730597f) | Dec 15, 2024 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [627bafd258](https://linux-hardware.org/?probe=627bafd258) | Dec 15, 2024 |
| Samsung       | R530/R730                   | Notebook    | [995d2abd36](https://linux-hardware.org/?probe=995d2abd36) | Dec 14, 2024 |
| ASUSTek       | K501UB                      | Notebook    | [9bb21014e6](https://linux-hardware.org/?probe=9bb21014e6) | Dec 14, 2024 |
| Dell          | G15 5511                    | Notebook    | [fd366d5886](https://linux-hardware.org/?probe=fd366d5886) | Dec 12, 2024 |
| HP            | G62                         | Notebook    | [70f9d38537](https://linux-hardware.org/?probe=70f9d38537) | Dec 11, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [a8cdd032a9](https://linux-hardware.org/?probe=a8cdd032a9) | Dec 10, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [e2d658580f](https://linux-hardware.org/?probe=e2d658580f) | Dec 10, 2024 |
| Biostar       | B350GT3                     | Desktop     | [9ba0340067](https://linux-hardware.org/?probe=9ba0340067) | Dec 10, 2024 |
| Lenovo        | ThinkPad T440s 20ARS1EQ0... | Notebook    | [c4f09615ae](https://linux-hardware.org/?probe=c4f09615ae) | Dec 08, 2024 |
| MSI           | PRO B550-VC                 | Desktop     | [5b3e1150f1](https://linux-hardware.org/?probe=5b3e1150f1) | Dec 08, 2024 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [8f790073ab](https://linux-hardware.org/?probe=8f790073ab) | Dec 07, 2024 |
| Google        | Delbin                      | Notebook    | [e761f97d94](https://linux-hardware.org/?probe=e761f97d94) | Dec 06, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [040113880f](https://linux-hardware.org/?probe=040113880f) | Dec 06, 2024 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [e026d0ed7b](https://linux-hardware.org/?probe=e026d0ed7b) | Dec 06, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [c33d7aa05f](https://linux-hardware.org/?probe=c33d7aa05f) | Dec 05, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [5ff5a0db06](https://linux-hardware.org/?probe=5ff5a0db06) | Dec 03, 2024 |
| Dell          | Latitude 5590               | Notebook    | [02ace3d15e](https://linux-hardware.org/?probe=02ace3d15e) | Dec 03, 2024 |
| Google        | Delbin                      | Notebook    | [0b18a9a18c](https://linux-hardware.org/?probe=0b18a9a18c) | Dec 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1cabb4b7bd](https://linux-hardware.org/?probe=1cabb4b7bd) | Dec 01, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a834234236](https://linux-hardware.org/?probe=a834234236) | Nov 30, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [be9e4b9467](https://linux-hardware.org/?probe=be9e4b9467) | Nov 29, 2024 |
| HP            | 8374 1100                   | All in one  | [9fe1f0456a](https://linux-hardware.org/?probe=9fe1f0456a) | Nov 27, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [faa62fd31d](https://linux-hardware.org/?probe=faa62fd31d) | Nov 27, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [53747d81e3](https://linux-hardware.org/?probe=53747d81e3) | Nov 26, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [94e5e4047f](https://linux-hardware.org/?probe=94e5e4047f) | Nov 24, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [277f85b96b](https://linux-hardware.org/?probe=277f85b96b) | Nov 21, 2024 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [6bf36eceff](https://linux-hardware.org/?probe=6bf36eceff) | Nov 21, 2024 |
| Dell          | Latitude 5590               | Notebook    | [9249e52134](https://linux-hardware.org/?probe=9249e52134) | Nov 19, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cd51b4ca43](https://linux-hardware.org/?probe=cd51b4ca43) | Nov 18, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [21d296d057](https://linux-hardware.org/?probe=21d296d057) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [92b243bc47](https://linux-hardware.org/?probe=92b243bc47) | Nov 17, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [571dd6599b](https://linux-hardware.org/?probe=571dd6599b) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1579ba23ea](https://linux-hardware.org/?probe=1579ba23ea) | Nov 17, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [a386e4310c](https://linux-hardware.org/?probe=a386e4310c) | Nov 17, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [5da217fd03](https://linux-hardware.org/?probe=5da217fd03) | Nov 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9497b471dc](https://linux-hardware.org/?probe=9497b471dc) | Nov 14, 2024 |
| Toshiba       | Satellite L755D             | Notebook    | [026c487fec](https://linux-hardware.org/?probe=026c487fec) | Nov 13, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [e3a4d58208](https://linux-hardware.org/?probe=e3a4d58208) | Nov 12, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [a41e7684ba](https://linux-hardware.org/?probe=a41e7684ba) | Nov 09, 2024 |
| Toshiba       | Satellite Pro L550          | Notebook    | [90ba079d9a](https://linux-hardware.org/?probe=90ba079d9a) | Nov 08, 2024 |
| Dynabook      | Satellite Pro C40-K         | Notebook    | [f8d851c4ec](https://linux-hardware.org/?probe=f8d851c4ec) | Nov 08, 2024 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [cc23916a73](https://linux-hardware.org/?probe=cc23916a73) | Nov 06, 2024 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [2d70625c33](https://linux-hardware.org/?probe=2d70625c33) | Nov 04, 2024 |
| Schenker      | SLIM14_SSL14L19             | Notebook    | [f7c0d965b7](https://linux-hardware.org/?probe=f7c0d965b7) | Nov 03, 2024 |
| Acer          | One 14 Z8-415               | Notebook    | [30bd329571](https://linux-hardware.org/?probe=30bd329571) | Nov 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6e52b4f65d](https://linux-hardware.org/?probe=6e52b4f65d) | Oct 31, 2024 |
| Schenker      | SLIM14_SSL14L19             | Notebook    | [fcf7985ef8](https://linux-hardware.org/?probe=fcf7985ef8) | Oct 31, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [adedc3cad6](https://linux-hardware.org/?probe=adedc3cad6) | Oct 30, 2024 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [cc607f4e72](https://linux-hardware.org/?probe=cc607f4e72) | Oct 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [0ba3e2a6cf](https://linux-hardware.org/?probe=0ba3e2a6cf) | Oct 28, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1299a69914](https://linux-hardware.org/?probe=1299a69914) | Oct 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [07edcf4b71](https://linux-hardware.org/?probe=07edcf4b71) | Oct 27, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [98ad76578b](https://linux-hardware.org/?probe=98ad76578b) | Oct 27, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d0905f7bb9](https://linux-hardware.org/?probe=d0905f7bb9) | Oct 26, 2024 |
| ASUSTek       | PRIME Z790-V AX             | Desktop     | [6cf269e31f](https://linux-hardware.org/?probe=6cf269e31f) | Oct 26, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [f500a67552](https://linux-hardware.org/?probe=f500a67552) | Oct 25, 2024 |
| ASUSTek       | K53E                        | Notebook    | [d27b0b2eee](https://linux-hardware.org/?probe=d27b0b2eee) | Oct 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [0d286dd3ac](https://linux-hardware.org/?probe=0d286dd3ac) | Oct 22, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [42d192db93](https://linux-hardware.org/?probe=42d192db93) | Oct 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9db5365bb8](https://linux-hardware.org/?probe=9db5365bb8) | Oct 20, 2024 |
| Google        | Drobit                      | Notebook    | [26edf296d3](https://linux-hardware.org/?probe=26edf296d3) | Oct 20, 2024 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [f93a2b50ee](https://linux-hardware.org/?probe=f93a2b50ee) | Oct 20, 2024 |
| Acer          | Nitro ANV15-41              | Notebook    | [c96376c69b](https://linux-hardware.org/?probe=c96376c69b) | Oct 13, 2024 |
| Dell          | Latitude 5490               | Notebook    | [968ebd0c22](https://linux-hardware.org/?probe=968ebd0c22) | Oct 11, 2024 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [2fca92d6b4](https://linux-hardware.org/?probe=2fca92d6b4) | Oct 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [214834c74c](https://linux-hardware.org/?probe=214834c74c) | Oct 09, 2024 |
| MSI           | B250M PRO-VDH               | Desktop     | [804981ff9b](https://linux-hardware.org/?probe=804981ff9b) | Oct 08, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [42d1b5a375](https://linux-hardware.org/?probe=42d1b5a375) | Oct 08, 2024 |
| MSI           | B360 GAMING PRO CARBON      | Desktop     | [4f51efa27b](https://linux-hardware.org/?probe=4f51efa27b) | Oct 08, 2024 |
| HP            | 18E4                        | Desktop     | [50cf02b67c](https://linux-hardware.org/?probe=50cf02b67c) | Oct 07, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [fe177c4385](https://linux-hardware.org/?probe=fe177c4385) | Oct 07, 2024 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [385153fdf8](https://linux-hardware.org/?probe=385153fdf8) | Oct 06, 2024 |
| Gigabyte      | A620M H                     | Desktop     | [b144a036c9](https://linux-hardware.org/?probe=b144a036c9) | Oct 03, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [c3e2a3c803](https://linux-hardware.org/?probe=c3e2a3c803) | Oct 01, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [d974cafe12](https://linux-hardware.org/?probe=d974cafe12) | Oct 01, 2024 |
| GPD           | G1618-04                    | Notebook    | [be67fe0e3e](https://linux-hardware.org/?probe=be67fe0e3e) | Sep 30, 2024 |
| ASUSTek       | B150 PRO GAMING D3          | Desktop     | [9342e97a46](https://linux-hardware.org/?probe=9342e97a46) | Sep 28, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [248886a2a4](https://linux-hardware.org/?probe=248886a2a4) | Sep 28, 2024 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [01fc4d5bf5](https://linux-hardware.org/?probe=01fc4d5bf5) | Sep 28, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [316eac0f8f](https://linux-hardware.org/?probe=316eac0f8f) | Sep 26, 2024 |
| Lenovo        | IdeaPad Z580                | Notebook    | [fb42cc4c6f](https://linux-hardware.org/?probe=fb42cc4c6f) | Sep 24, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [25f605fe0b](https://linux-hardware.org/?probe=25f605fe0b) | Sep 24, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [ebda65fac2](https://linux-hardware.org/?probe=ebda65fac2) | Sep 23, 2024 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [99476c9cd3](https://linux-hardware.org/?probe=99476c9cd3) | Sep 23, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [078f9d07a7](https://linux-hardware.org/?probe=078f9d07a7) | Sep 22, 2024 |
| Avell High... | A62 LIV                     | Notebook    | [aa80a76284](https://linux-hardware.org/?probe=aa80a76284) | Sep 20, 2024 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [a6bb869814](https://linux-hardware.org/?probe=a6bb869814) | Sep 18, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c89ae91f7e](https://linux-hardware.org/?probe=c89ae91f7e) | Sep 16, 2024 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [0975c90f12](https://linux-hardware.org/?probe=0975c90f12) | Sep 16, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [aadc023cfc](https://linux-hardware.org/?probe=aadc023cfc) | Sep 15, 2024 |
| Lenovo        | 371C WIN SDK0J40700 3258... | All in one  | [346a96daf6](https://linux-hardware.org/?probe=346a96daf6) | Sep 14, 2024 |
| Alienware     | 14                          | Notebook    | [c47b383fde](https://linux-hardware.org/?probe=c47b383fde) | Sep 13, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [8367955e9f](https://linux-hardware.org/?probe=8367955e9f) | Sep 13, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f8559b33b3](https://linux-hardware.org/?probe=f8559b33b3) | Sep 13, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [19a2e3f88d](https://linux-hardware.org/?probe=19a2e3f88d) | Sep 13, 2024 |
| Dell          | 04VHC5 A05                  | Desktop     | [7f5c1dd188](https://linux-hardware.org/?probe=7f5c1dd188) | Sep 13, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [8b4b16d6c1](https://linux-hardware.org/?probe=8b4b16d6c1) | Sep 11, 2024 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [da6201fca5](https://linux-hardware.org/?probe=da6201fca5) | Sep 11, 2024 |
| Alienware     | 14                          | Notebook    | [dda4311094](https://linux-hardware.org/?probe=dda4311094) | Sep 10, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [07e25442a0](https://linux-hardware.org/?probe=07e25442a0) | Sep 09, 2024 |
| MSI           | Summit E15 A11SCS           | Notebook    | [0de416afaf](https://linux-hardware.org/?probe=0de416afaf) | Sep 09, 2024 |
| Dell          | 0R7HRW A02                  | Desktop     | [2eb397c5dc](https://linux-hardware.org/?probe=2eb397c5dc) | Sep 09, 2024 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [9a7675b128](https://linux-hardware.org/?probe=9a7675b128) | Sep 09, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b53daf6dc1](https://linux-hardware.org/?probe=b53daf6dc1) | Sep 09, 2024 |
| Dell          | 0R7HRW A02                  | Desktop     | [2e00c133ee](https://linux-hardware.org/?probe=2e00c133ee) | Sep 08, 2024 |
| MSI           | B360M BAZOOKA               | Desktop     | [c306aed70e](https://linux-hardware.org/?probe=c306aed70e) | Sep 08, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5db59ecfa9](https://linux-hardware.org/?probe=5db59ecfa9) | Sep 07, 2024 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [c5969aacc7](https://linux-hardware.org/?probe=c5969aacc7) | Sep 06, 2024 |
| ASRock        | B760M-STX                   | Desktop     | [4d715fcdab](https://linux-hardware.org/?probe=4d715fcdab) | Sep 05, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [0abd493e22](https://linux-hardware.org/?probe=0abd493e22) | Sep 02, 2024 |
| Dell          | Inspiron 15 3525            | Notebook    | [4bc238278b](https://linux-hardware.org/?probe=4bc238278b) | Sep 01, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [6be41e3426](https://linux-hardware.org/?probe=6be41e3426) | Sep 01, 2024 |
| Avell High... | A62 LIV                     | Notebook    | [88cbf3c8bc](https://linux-hardware.org/?probe=88cbf3c8bc) | Aug 31, 2024 |
| Avell High... | A62 LIV                     | Notebook    | [11abb87f47](https://linux-hardware.org/?probe=11abb87f47) | Aug 31, 2024 |
| Dell          | Inspiron 15 3525            | Notebook    | [a9efa36c83](https://linux-hardware.org/?probe=a9efa36c83) | Aug 31, 2024 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [b8a3e200f4](https://linux-hardware.org/?probe=b8a3e200f4) | Aug 29, 2024 |
| MSI           | X370 GAMING PLUS            | Desktop     | [cccb0b55d2](https://linux-hardware.org/?probe=cccb0b55d2) | Aug 28, 2024 |
| Monster       | TULPAR T5 V23.2             | Notebook    | [9b4bf39bd8](https://linux-hardware.org/?probe=9b4bf39bd8) | Aug 25, 2024 |
| Intel         | DP965LT AAD41694-210        | Desktop     | [5f5c266187](https://linux-hardware.org/?probe=5f5c266187) | Aug 25, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [21fa7cdf8b](https://linux-hardware.org/?probe=21fa7cdf8b) | Aug 25, 2024 |
| Apple         | MacBookPro15,1              | Notebook    | [18ccfcabb6](https://linux-hardware.org/?probe=18ccfcabb6) | Aug 25, 2024 |
| Dell          | Latitude E7440              | Notebook    | [6cddb30ec0](https://linux-hardware.org/?probe=6cddb30ec0) | Aug 24, 2024 |
| Dell          | Latitude E7440              | Notebook    | [bda506fc26](https://linux-hardware.org/?probe=bda506fc26) | Aug 24, 2024 |
| Alienware     | 17 R4                       | Notebook    | [4607e5603d](https://linux-hardware.org/?probe=4607e5603d) | Aug 24, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [99925cbbf6](https://linux-hardware.org/?probe=99925cbbf6) | Aug 23, 2024 |
| MSI           | PRO B760M-A WIFI            | Desktop     | [dffcb9242a](https://linux-hardware.org/?probe=dffcb9242a) | Aug 23, 2024 |
| Lenovo        | ThinkPad T430 2349RQ3       | Notebook    | [344514d748](https://linux-hardware.org/?probe=344514d748) | Aug 23, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e93db27fa7](https://linux-hardware.org/?probe=e93db27fa7) | Aug 23, 2024 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [e1bd6aa8e1](https://linux-hardware.org/?probe=e1bd6aa8e1) | Aug 23, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [ecb6bbc906](https://linux-hardware.org/?probe=ecb6bbc906) | Aug 23, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4627f152d7](https://linux-hardware.org/?probe=4627f152d7) | Aug 22, 2024 |
| ASRock        | B760M-STX                   | Desktop     | [0a0fc81c8f](https://linux-hardware.org/?probe=0a0fc81c8f) | Aug 22, 2024 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [5b7c55fd49](https://linux-hardware.org/?probe=5b7c55fd49) | Aug 20, 2024 |
| Dell          | 07WP95 A01                  | Desktop     | [a4a7707426](https://linux-hardware.org/?probe=a4a7707426) | Aug 19, 2024 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [c51e04df17](https://linux-hardware.org/?probe=c51e04df17) | Aug 16, 2024 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a2d890c354](https://linux-hardware.org/?probe=a2d890c354) | Aug 16, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [b8416663f7](https://linux-hardware.org/?probe=b8416663f7) | Aug 16, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [3e797134f0](https://linux-hardware.org/?probe=3e797134f0) | Aug 16, 2024 |
| Unknown       | Unknown                     | Notebook    | [a627eeb394](https://linux-hardware.org/?probe=a627eeb394) | Aug 13, 2024 |
| Avell High... | A62 LIV                     | Notebook    | [89892c500e](https://linux-hardware.org/?probe=89892c500e) | Aug 13, 2024 |
| Samsung       | 950QED                      | Convertible | [3e383ce555](https://linux-hardware.org/?probe=3e383ce555) | Aug 12, 2024 |
| Samsung       | 950QED                      | Convertible | [24d637ab46](https://linux-hardware.org/?probe=24d637ab46) | Aug 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ed0cfaf91b](https://linux-hardware.org/?probe=ed0cfaf91b) | Aug 12, 2024 |
| ASUSTek       | TUF Gaming H570-PRO WIFI    | Desktop     | [6442ec1ebd](https://linux-hardware.org/?probe=6442ec1ebd) | Aug 11, 2024 |
| ASUSTek       | TUF Gaming H570-PRO WIFI    | Desktop     | [1a0b227011](https://linux-hardware.org/?probe=1a0b227011) | Aug 11, 2024 |
| Lenovo        | 36DA SDK0J40709 WIN 3259... | All in one  | [518391fcb2](https://linux-hardware.org/?probe=518391fcb2) | Aug 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4bbef13098](https://linux-hardware.org/?probe=4bbef13098) | Aug 08, 2024 |
| Gigabyte      | H410M S2H                   | Desktop     | [699e2bba87](https://linux-hardware.org/?probe=699e2bba87) | Aug 08, 2024 |
| Intel         | DP965LT AAD41694-210        | Desktop     | [73798551a6](https://linux-hardware.org/?probe=73798551a6) | Aug 08, 2024 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [6864d163d8](https://linux-hardware.org/?probe=6864d163d8) | Aug 04, 2024 |
| Samsung       | R530/R730                   | Notebook    | [a67ee0342f](https://linux-hardware.org/?probe=a67ee0342f) | Aug 04, 2024 |
| Dell          | 0RW203                      | Desktop     | [f2871f9938](https://linux-hardware.org/?probe=f2871f9938) | Aug 02, 2024 |
| ONDA          | B550SD4-ITX Ver:1.02        | Desktop     | [1be8c45046](https://linux-hardware.org/?probe=1be8c45046) | Jul 30, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [5ab0ffc9aa](https://linux-hardware.org/?probe=5ab0ffc9aa) | Jul 28, 2024 |
| GPD           | G1618-04                    | Notebook    | [c6aefccb2c](https://linux-hardware.org/?probe=c6aefccb2c) | Jul 27, 2024 |
| Valve         | Galileo                     | Notebook    | [79a07fcefb](https://linux-hardware.org/?probe=79a07fcefb) | Jul 26, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [9b93efc7fa](https://linux-hardware.org/?probe=9b93efc7fa) | Jul 25, 2024 |
| Lenovo        | ThinkPad P71 20HLS0UE00     | Notebook    | [400120df7a](https://linux-hardware.org/?probe=400120df7a) | Jul 25, 2024 |
| Dell          | Precision 7710              | Notebook    | [b0ff7b315d](https://linux-hardware.org/?probe=b0ff7b315d) | Jul 23, 2024 |
| Dell          | Precision 7520              | Notebook    | [ab03c13aca](https://linux-hardware.org/?probe=ab03c13aca) | Jul 23, 2024 |
| Dell          | Precision 7710              | Notebook    | [eaaefe2324](https://linux-hardware.org/?probe=eaaefe2324) | Jul 23, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a1eee06fd3](https://linux-hardware.org/?probe=a1eee06fd3) | Jul 12, 2024 |
| GPU Compan... | GWNC214H34-SL               | Notebook    | [f6c5223f36](https://linux-hardware.org/?probe=f6c5223f36) | Jul 12, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0837d07786](https://linux-hardware.org/?probe=0837d07786) | Jul 11, 2024 |
| Lenovo        | ThinkPad T460s 20F90060G... | Notebook    | [24c071c2e6](https://linux-hardware.org/?probe=24c071c2e6) | Jul 10, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [22139a9f01](https://linux-hardware.org/?probe=22139a9f01) | Jul 09, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [be094b7023](https://linux-hardware.org/?probe=be094b7023) | Jul 09, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | Notebook    | [0a9be595b1](https://linux-hardware.org/?probe=0a9be595b1) | Jul 09, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | Notebook    | [e81695264a](https://linux-hardware.org/?probe=e81695264a) | Jul 09, 2024 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [c17844b884](https://linux-hardware.org/?probe=c17844b884) | Jul 05, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b98a7bf947](https://linux-hardware.org/?probe=b98a7bf947) | Jul 04, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [60c0248abc](https://linux-hardware.org/?probe=60c0248abc) | Jul 04, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [01e4ba3dfd](https://linux-hardware.org/?probe=01e4ba3dfd) | Jul 02, 2024 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [313df6e324](https://linux-hardware.org/?probe=313df6e324) | Jun 29, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [f0ce44ea05](https://linux-hardware.org/?probe=f0ce44ea05) | Jun 29, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [1cf081dbdb](https://linux-hardware.org/?probe=1cf081dbdb) | Jun 28, 2024 |
| Dell          | 0D28YY A03                  | Desktop     | [57fe8e4c14](https://linux-hardware.org/?probe=57fe8e4c14) | Jun 26, 2024 |
| Notebook      | P640RE                      | Notebook    | [e191099edb](https://linux-hardware.org/?probe=e191099edb) | Jun 24, 2024 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [c50af3b6c8](https://linux-hardware.org/?probe=c50af3b6c8) | Jun 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [869129230d](https://linux-hardware.org/?probe=869129230d) | Jun 22, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [cb97b1274c](https://linux-hardware.org/?probe=cb97b1274c) | Jun 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [ba2fcdc6b1](https://linux-hardware.org/?probe=ba2fcdc6b1) | Jun 20, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6900714a99](https://linux-hardware.org/?probe=6900714a99) | Jun 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [33624dc95e](https://linux-hardware.org/?probe=33624dc95e) | Jun 19, 2024 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [e3ecabe043](https://linux-hardware.org/?probe=e3ecabe043) | Jun 19, 2024 |
| ASUSTek       | ROG Strix G713RS_G713RS     | Notebook    | [f33e866e3a](https://linux-hardware.org/?probe=f33e866e3a) | Jun 19, 2024 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [1e8aa7a77f](https://linux-hardware.org/?probe=1e8aa7a77f) | Jun 18, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f5ea2494d3](https://linux-hardware.org/?probe=f5ea2494d3) | Jun 18, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [828e38468b](https://linux-hardware.org/?probe=828e38468b) | Jun 17, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [ffc9e0875c](https://linux-hardware.org/?probe=ffc9e0875c) | Jun 17, 2024 |
| HP            | 18E4                        | Desktop     | [23b6d1c78c](https://linux-hardware.org/?probe=23b6d1c78c) | Jun 16, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [bdfb84bfc5](https://linux-hardware.org/?probe=bdfb84bfc5) | Jun 15, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [8c20971426](https://linux-hardware.org/?probe=8c20971426) | Jun 15, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [2f452e7bed](https://linux-hardware.org/?probe=2f452e7bed) | Jun 14, 2024 |
| Intel         | DP965LT AAD41694-210        | Desktop     | [3e39a37742](https://linux-hardware.org/?probe=3e39a37742) | Jun 14, 2024 |
| Intel         | DP965LT AAD41694-210        | Desktop     | [0677434191](https://linux-hardware.org/?probe=0677434191) | Jun 13, 2024 |
| ECS           | A780GM-A                    | Desktop     | [577391284a](https://linux-hardware.org/?probe=577391284a) | Jun 12, 2024 |
| Dell          | Precision 5690              | Notebook    | [924b1ece6c](https://linux-hardware.org/?probe=924b1ece6c) | Jun 12, 2024 |
| PEAQ          | PNB P1115 MD99343           | Notebook    | [4e29fc0839](https://linux-hardware.org/?probe=4e29fc0839) | Jun 09, 2024 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [4cf9ebee56](https://linux-hardware.org/?probe=4cf9ebee56) | Jun 08, 2024 |
| Samsung       | R530/R730                   | Notebook    | [e9d3fc4719](https://linux-hardware.org/?probe=e9d3fc4719) | Jun 08, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [aa4888abc9](https://linux-hardware.org/?probe=aa4888abc9) | Jun 08, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [e7e349c28e](https://linux-hardware.org/?probe=e7e349c28e) | Jun 07, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [3c0ef8ae3f](https://linux-hardware.org/?probe=3c0ef8ae3f) | Jun 07, 2024 |
| ASUSTek       | PRIME Z790-V AX             | Desktop     | [7685323b5f](https://linux-hardware.org/?probe=7685323b5f) | Jun 07, 2024 |
| MSI           | GL73 8RD                    | Notebook    | [232fab6257](https://linux-hardware.org/?probe=232fab6257) | Jun 07, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5b3c45f75c](https://linux-hardware.org/?probe=5b3c45f75c) | Jun 06, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [f8802d8e00](https://linux-hardware.org/?probe=f8802d8e00) | Jun 06, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [df4dd0037c](https://linux-hardware.org/?probe=df4dd0037c) | Jun 06, 2024 |
| Gigabyte      | B450M K-CF                  | Notebook    | [0cb44e20e0](https://linux-hardware.org/?probe=0cb44e20e0) | Jun 06, 2024 |
| ASUSTek       | PRIME Z790-V AX             | Desktop     | [d5962dc0f4](https://linux-hardware.org/?probe=d5962dc0f4) | Jun 04, 2024 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [e1adf09d60](https://linux-hardware.org/?probe=e1adf09d60) | Jun 02, 2024 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [96cbb6e9fc](https://linux-hardware.org/?probe=96cbb6e9fc) | Jun 02, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [8867eaebbd](https://linux-hardware.org/?probe=8867eaebbd) | May 29, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [9c2659e775](https://linux-hardware.org/?probe=9c2659e775) | May 28, 2024 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [a6443b3b74](https://linux-hardware.org/?probe=a6443b3b74) | May 24, 2024 |
| Dell          | G15 Special Edition 5521    | Notebook    | [5bb64a1498](https://linux-hardware.org/?probe=5bb64a1498) | May 23, 2024 |
| MSI           | PRO B550-VC                 | Desktop     | [e70c5bf67b](https://linux-hardware.org/?probe=e70c5bf67b) | May 22, 2024 |
| Dell          | G15 Special Edition 5521    | Notebook    | [47bfbd5ead](https://linux-hardware.org/?probe=47bfbd5ead) | May 21, 2024 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [7cfed3af06](https://linux-hardware.org/?probe=7cfed3af06) | May 21, 2024 |
| Razer         | Blade 16 - RZ09-0510        | Notebook    | [965dc14fc2](https://linux-hardware.org/?probe=965dc14fc2) | May 20, 2024 |
| HP            | 8053                        | Desktop     | [78a3be9668](https://linux-hardware.org/?probe=78a3be9668) | May 19, 2024 |
| Acer          | Swift SF113-31              | Notebook    | [afefc4eb75](https://linux-hardware.org/?probe=afefc4eb75) | May 18, 2024 |
| Dell          | Latitude 5490               | Notebook    | [65385e527b](https://linux-hardware.org/?probe=65385e527b) | May 18, 2024 |
| Dell          | Latitude 5490               | Notebook    | [dcccf62ee8](https://linux-hardware.org/?probe=dcccf62ee8) | May 18, 2024 |
| MSI           | Modern 15 H B13M            | Notebook    | [f9839d0180](https://linux-hardware.org/?probe=f9839d0180) | May 17, 2024 |
| ASUSTek       | Q87T                        | Desktop     | [6fda8ece6f](https://linux-hardware.org/?probe=6fda8ece6f) | May 15, 2024 |
| Casper        | EXCALIBUR G770              | Notebook    | [06a25f526f](https://linux-hardware.org/?probe=06a25f526f) | May 14, 2024 |
| Dell          | Latitude E6430              | Notebook    | [a145a37354](https://linux-hardware.org/?probe=a145a37354) | May 14, 2024 |
| Dell          | 0YJMC0 A02                  | Desktop     | [80760046ec](https://linux-hardware.org/?probe=80760046ec) | May 13, 2024 |
| Dell          | 0X231R A00                  | Desktop     | [d20f0d688b](https://linux-hardware.org/?probe=d20f0d688b) | May 13, 2024 |
| Casper        | EXCALIBUR G770              | Notebook    | [b092716b6a](https://linux-hardware.org/?probe=b092716b6a) | May 12, 2024 |
| Dell          | G15 Special Edition 5521    | Notebook    | [6ac404598d](https://linux-hardware.org/?probe=6ac404598d) | May 12, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [4e002660a0](https://linux-hardware.org/?probe=4e002660a0) | May 10, 2024 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [4b77160a0a](https://linux-hardware.org/?probe=4b77160a0a) | May 09, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [184ca6c080](https://linux-hardware.org/?probe=184ca6c080) | May 09, 2024 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [8f78e61ba3](https://linux-hardware.org/?probe=8f78e61ba3) | May 06, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [02dec94612](https://linux-hardware.org/?probe=02dec94612) | May 05, 2024 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [38d719b3cc](https://linux-hardware.org/?probe=38d719b3cc) | May 05, 2024 |
| ASRock        | 970 Extreme3                | Desktop     | [78a7df5736](https://linux-hardware.org/?probe=78a7df5736) | May 05, 2024 |
| MSI           | MEG Z390 ACE                | Desktop     | [d564c1c05f](https://linux-hardware.org/?probe=d564c1c05f) | May 03, 2024 |
| Dell          | G5 5590                     | Notebook    | [b32e4a3fcc](https://linux-hardware.org/?probe=b32e4a3fcc) | May 03, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f40340d3fa](https://linux-hardware.org/?probe=f40340d3fa) | May 02, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [fb39aaf8f2](https://linux-hardware.org/?probe=fb39aaf8f2) | May 01, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [b9f81199c9](https://linux-hardware.org/?probe=b9f81199c9) | Apr 30, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2ffec4cb68](https://linux-hardware.org/?probe=2ffec4cb68) | Apr 29, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [9e12aaba51](https://linux-hardware.org/?probe=9e12aaba51) | Apr 29, 2024 |
| Timi          | Redmi G 2022                | Notebook    | [42d8e2e055](https://linux-hardware.org/?probe=42d8e2e055) | Apr 28, 2024 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5a6ea85213](https://linux-hardware.org/?probe=5a6ea85213) | Apr 28, 2024 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [8076b425cd](https://linux-hardware.org/?probe=8076b425cd) | Apr 27, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [baeaf7e578](https://linux-hardware.org/?probe=baeaf7e578) | Apr 26, 2024 |
| HP            | EliteBook 745 G2            | Notebook    | [3386466743](https://linux-hardware.org/?probe=3386466743) | Apr 25, 2024 |
| ASUSTek       | Q87T                        | Desktop     | [2c7eb11783](https://linux-hardware.org/?probe=2c7eb11783) | Apr 23, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4c3f0758e4](https://linux-hardware.org/?probe=4c3f0758e4) | Apr 22, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [9f8a1748ce](https://linux-hardware.org/?probe=9f8a1748ce) | Apr 22, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [f9b7f5d81b](https://linux-hardware.org/?probe=f9b7f5d81b) | Apr 21, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [6f3c85173f](https://linux-hardware.org/?probe=6f3c85173f) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9778349d4b](https://linux-hardware.org/?probe=9778349d4b) | Apr 18, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c7e32d8f0c](https://linux-hardware.org/?probe=c7e32d8f0c) | Apr 18, 2024 |
| MSI           | P65 Creator 8SF             | Notebook    | [4765243dd1](https://linux-hardware.org/?probe=4765243dd1) | Apr 17, 2024 |
| Dell          | Inspiron 7737               | Notebook    | [1f91e64679](https://linux-hardware.org/?probe=1f91e64679) | Apr 17, 2024 |
| Dell          | Inspiron 7737               | Notebook    | [361844ede0](https://linux-hardware.org/?probe=361844ede0) | Apr 17, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [ac52751407](https://linux-hardware.org/?probe=ac52751407) | Apr 16, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [fd2c385c1b](https://linux-hardware.org/?probe=fd2c385c1b) | Apr 16, 2024 |
| ASUSTek       | Q87T                        | Desktop     | [fdcc988e3a](https://linux-hardware.org/?probe=fdcc988e3a) | Apr 16, 2024 |
| MSI           | Stealth GS77 12UE           | Notebook    | [47ff584537](https://linux-hardware.org/?probe=47ff584537) | Apr 14, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [85072c85db](https://linux-hardware.org/?probe=85072c85db) | Apr 11, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [edf7dfcacb](https://linux-hardware.org/?probe=edf7dfcacb) | Apr 10, 2024 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [ee5809d062](https://linux-hardware.org/?probe=ee5809d062) | Apr 09, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [a5050366da](https://linux-hardware.org/?probe=a5050366da) | Apr 09, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ec1a7c3951](https://linux-hardware.org/?probe=ec1a7c3951) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48f3d584f3](https://linux-hardware.org/?probe=48f3d584f3) | Apr 09, 2024 |
| MSI           | Stealth 15M B12UE           | Notebook    | [041874d8e0](https://linux-hardware.org/?probe=041874d8e0) | Apr 08, 2024 |
| Microsoft     | Surface Laptop 4            | Tablet      | [068a8fcd94](https://linux-hardware.org/?probe=068a8fcd94) | Apr 07, 2024 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [91ae8a8c4b](https://linux-hardware.org/?probe=91ae8a8c4b) | Apr 07, 2024 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [79ed318799](https://linux-hardware.org/?probe=79ed318799) | Apr 06, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d0b50bb8cf](https://linux-hardware.org/?probe=d0b50bb8cf) | Apr 06, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [282f54846f](https://linux-hardware.org/?probe=282f54846f) | Apr 05, 2024 |
| Lenovo        | ThinkPad T430 2349RQ3       | Notebook    | [6988a75b14](https://linux-hardware.org/?probe=6988a75b14) | Apr 05, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [fc81346f79](https://linux-hardware.org/?probe=fc81346f79) | Apr 04, 2024 |
| HP            | EliteBook 745 G2            | Notebook    | [8d1226791a](https://linux-hardware.org/?probe=8d1226791a) | Mar 29, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [b1ff4c1ab1](https://linux-hardware.org/?probe=b1ff4c1ab1) | Mar 28, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [82cd14327e](https://linux-hardware.org/?probe=82cd14327e) | Mar 28, 2024 |
| Dell          | Precision 5540              | Notebook    | [e36c4c65ab](https://linux-hardware.org/?probe=e36c4c65ab) | Mar 26, 2024 |
| MSI           | P65 Creator 8SF             | Notebook    | [2ac35fb5df](https://linux-hardware.org/?probe=2ac35fb5df) | Mar 24, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [45f2251b48](https://linux-hardware.org/?probe=45f2251b48) | Mar 23, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [61f15ca75a](https://linux-hardware.org/?probe=61f15ca75a) | Mar 22, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [f59cf641ed](https://linux-hardware.org/?probe=f59cf641ed) | Mar 21, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [55440632d5](https://linux-hardware.org/?probe=55440632d5) | Mar 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [2f1a34dcc7](https://linux-hardware.org/?probe=2f1a34dcc7) | Mar 17, 2024 |
| Lenovo        | ThinkPad X230 23249Q2       | Notebook    | [53750d45df](https://linux-hardware.org/?probe=53750d45df) | Mar 16, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [38ef3d13d7](https://linux-hardware.org/?probe=38ef3d13d7) | Mar 16, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [0335b381d3](https://linux-hardware.org/?probe=0335b381d3) | Mar 14, 2024 |
| HP            | Laptop 15-da1xxx            | Notebook    | [decbe9d726](https://linux-hardware.org/?probe=decbe9d726) | Mar 14, 2024 |
| ASRock        | Z97M Pro4                   | Desktop     | [d82ec98b2f](https://linux-hardware.org/?probe=d82ec98b2f) | Mar 14, 2024 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [3bd7c8ccf4](https://linux-hardware.org/?probe=3bd7c8ccf4) | Mar 14, 2024 |
| GPD           | G1621-02                    | Notebook    | [382319d2bd](https://linux-hardware.org/?probe=382319d2bd) | Mar 13, 2024 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [de707827fb](https://linux-hardware.org/?probe=de707827fb) | Mar 13, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [5ff5755d30](https://linux-hardware.org/?probe=5ff5755d30) | Mar 13, 2024 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a731c5f5eb](https://linux-hardware.org/?probe=a731c5f5eb) | Mar 13, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [edaf44f04b](https://linux-hardware.org/?probe=edaf44f04b) | Mar 10, 2024 |
| MSI           | H610M BOMBER DDR4           | Desktop     | [8795e218dc](https://linux-hardware.org/?probe=8795e218dc) | Mar 10, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [de3cdad359](https://linux-hardware.org/?probe=de3cdad359) | Mar 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [92a2bca1a2](https://linux-hardware.org/?probe=92a2bca1a2) | Mar 08, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [386945e586](https://linux-hardware.org/?probe=386945e586) | Mar 07, 2024 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [35d31a50c0](https://linux-hardware.org/?probe=35d31a50c0) | Mar 07, 2024 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [289e745411](https://linux-hardware.org/?probe=289e745411) | Mar 07, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1fce24506f](https://linux-hardware.org/?probe=1fce24506f) | Mar 06, 2024 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [ce05cbee18](https://linux-hardware.org/?probe=ce05cbee18) | Mar 02, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [798acc343c](https://linux-hardware.org/?probe=798acc343c) | Feb 29, 2024 |
| MSI           | Stealth 15M B12UE           | Notebook    | [59afccdc44](https://linux-hardware.org/?probe=59afccdc44) | Feb 28, 2024 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [37c0d2130b](https://linux-hardware.org/?probe=37c0d2130b) | Feb 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a71e9dba32](https://linux-hardware.org/?probe=a71e9dba32) | Feb 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e8bc13baa1](https://linux-hardware.org/?probe=e8bc13baa1) | Feb 25, 2024 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [c8de9e7dd7](https://linux-hardware.org/?probe=c8de9e7dd7) | Feb 25, 2024 |
| HP            | EliteBook 8560w             | Notebook    | [ea3d798358](https://linux-hardware.org/?probe=ea3d798358) | Feb 25, 2024 |
| HP            | EliteBook 8560w             | Notebook    | [d3a04fdf22](https://linux-hardware.org/?probe=d3a04fdf22) | Feb 25, 2024 |
| HP            | 8053                        | Desktop     | [29dcf353b5](https://linux-hardware.org/?probe=29dcf353b5) | Feb 24, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3a64f7e0a5](https://linux-hardware.org/?probe=3a64f7e0a5) | Feb 22, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [acb58aeb0d](https://linux-hardware.org/?probe=acb58aeb0d) | Feb 21, 2024 |
| Apple         | MacBookPro13,3              | Notebook    | [f6a0a37d75](https://linux-hardware.org/?probe=f6a0a37d75) | Feb 20, 2024 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [6e87a83b16](https://linux-hardware.org/?probe=6e87a83b16) | Feb 20, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [d6a420d5e4](https://linux-hardware.org/?probe=d6a420d5e4) | Feb 18, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [7749f91798](https://linux-hardware.org/?probe=7749f91798) | Feb 18, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [14f9f1afa9](https://linux-hardware.org/?probe=14f9f1afa9) | Feb 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4d44c78868](https://linux-hardware.org/?probe=4d44c78868) | Feb 15, 2024 |
| TECNO         | MEGABOOK T1                 | Notebook    | [33fe01408f](https://linux-hardware.org/?probe=33fe01408f) | Feb 14, 2024 |
| AZW           | GT-R                        | Notebook    | [d40b69a73e](https://linux-hardware.org/?probe=d40b69a73e) | Feb 13, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [9a6d21a18d](https://linux-hardware.org/?probe=9a6d21a18d) | Feb 10, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [1d2758029b](https://linux-hardware.org/?probe=1d2758029b) | Feb 08, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [0b028612c5](https://linux-hardware.org/?probe=0b028612c5) | Feb 08, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [1ef50cb52c](https://linux-hardware.org/?probe=1ef50cb52c) | Feb 05, 2024 |
| Dell          | Inspiron 5759               | Notebook    | [b1fd1650b7](https://linux-hardware.org/?probe=b1fd1650b7) | Feb 04, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [a8ba2aabd5](https://linux-hardware.org/?probe=a8ba2aabd5) | Feb 04, 2024 |
| MSI           | Stealth 15M B12UE           | Notebook    | [b5d23740cc](https://linux-hardware.org/?probe=b5d23740cc) | Feb 04, 2024 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [cf1e9cdc22](https://linux-hardware.org/?probe=cf1e9cdc22) | Feb 03, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [349b53e55a](https://linux-hardware.org/?probe=349b53e55a) | Feb 02, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [c58dd08065](https://linux-hardware.org/?probe=c58dd08065) | Jan 31, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [5996127f6c](https://linux-hardware.org/?probe=5996127f6c) | Jan 31, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [907099b1e7](https://linux-hardware.org/?probe=907099b1e7) | Jan 29, 2024 |
| Gigabyte      | X570S AERO G                | Desktop     | [f485006061](https://linux-hardware.org/?probe=f485006061) | Jan 28, 2024 |
| Acer          | Predator PH317-53           | Notebook    | [4b8b265f8c](https://linux-hardware.org/?probe=4b8b265f8c) | Jan 23, 2024 |
| OriginPC      | EVO17-S                     | Notebook    | [085e0b26d0](https://linux-hardware.org/?probe=085e0b26d0) | Jan 21, 2024 |
| Unknown       | AM02                        | Mini pc     | [e36d8fb228](https://linux-hardware.org/?probe=e36d8fb228) | Jan 20, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [5f1537cd10](https://linux-hardware.org/?probe=5f1537cd10) | Jan 19, 2024 |
| Dell          | 0D24M8 A00                  | Desktop     | [521b297c38](https://linux-hardware.org/?probe=521b297c38) | Jan 19, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [217209efeb](https://linux-hardware.org/?probe=217209efeb) | Jan 18, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [12d61689c2](https://linux-hardware.org/?probe=12d61689c2) | Jan 18, 2024 |
| MSI           | Stealth 15M B12UE           | Notebook    | [64561711ef](https://linux-hardware.org/?probe=64561711ef) | Jan 18, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d4da037a11](https://linux-hardware.org/?probe=d4da037a11) | Jan 17, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a8557f8a49](https://linux-hardware.org/?probe=a8557f8a49) | Jan 17, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [52d8f5119e](https://linux-hardware.org/?probe=52d8f5119e) | Jan 15, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [85ada6019c](https://linux-hardware.org/?probe=85ada6019c) | Jan 15, 2024 |
| MSI           | B350M MORTAR                | Desktop     | [0462bdbc4d](https://linux-hardware.org/?probe=0462bdbc4d) | Jan 14, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [86f3a39f11](https://linux-hardware.org/?probe=86f3a39f11) | Jan 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f618c2c6b8](https://linux-hardware.org/?probe=f618c2c6b8) | Jan 10, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [af4d83b40f](https://linux-hardware.org/?probe=af4d83b40f) | Jan 10, 2024 |
| Razer         | Blade                       | Notebook    | [8bfee68ead](https://linux-hardware.org/?probe=8bfee68ead) | Jan 10, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [a1c9e7aaa5](https://linux-hardware.org/?probe=a1c9e7aaa5) | Jan 08, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [1e21573b13](https://linux-hardware.org/?probe=1e21573b13) | Jan 05, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [0d79087015](https://linux-hardware.org/?probe=0d79087015) | Jan 05, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [9e7c6246dc](https://linux-hardware.org/?probe=9e7c6246dc) | Jan 05, 2024 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [e984790c53](https://linux-hardware.org/?probe=e984790c53) | Jan 04, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b732d30db5](https://linux-hardware.org/?probe=b732d30db5) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [43bc3cd4bd](https://linux-hardware.org/?probe=43bc3cd4bd) | Jan 02, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [93ce6b9074](https://linux-hardware.org/?probe=93ce6b9074) | Jan 02, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [5cde8dcd78](https://linux-hardware.org/?probe=5cde8dcd78) | Jan 01, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [4c2ef0d59a](https://linux-hardware.org/?probe=4c2ef0d59a) | Dec 30, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [8ec110334b](https://linux-hardware.org/?probe=8ec110334b) | Dec 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| NZXT          | N7 B550                     | Desktop     | [2ce2b46a02](https://linux-hardware.org/?probe=2ce2b46a02) | Dec 27, 2023 |
| Intel         | X99-P4 V5.0                 | Desktop     | [875d756d73](https://linux-hardware.org/?probe=875d756d73) | Dec 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c3b34cdeb4](https://linux-hardware.org/?probe=c3b34cdeb4) | Dec 26, 2023 |
| Lenovo        | ThinkPad T500 20828WG       | Notebook    | [a3edf5e69b](https://linux-hardware.org/?probe=a3edf5e69b) | Dec 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [7fcdc0004a](https://linux-hardware.org/?probe=7fcdc0004a) | Dec 25, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [0819197709](https://linux-hardware.org/?probe=0819197709) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [41256541b5](https://linux-hardware.org/?probe=41256541b5) | Dec 21, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [16f9dec3e0](https://linux-hardware.org/?probe=16f9dec3e0) | Dec 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [67c84a4903](https://linux-hardware.org/?probe=67c84a4903) | Dec 19, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [1bd33b2c6b](https://linux-hardware.org/?probe=1bd33b2c6b) | Dec 18, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [30fc775598](https://linux-hardware.org/?probe=30fc775598) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | Notebook    | [19d43a41f8](https://linux-hardware.org/?probe=19d43a41f8) | Dec 17, 2023 |
| HP            | 2B18                        | Desktop     | [7015a76fe4](https://linux-hardware.org/?probe=7015a76fe4) | Dec 15, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [60461068e8](https://linux-hardware.org/?probe=60461068e8) | Dec 13, 2023 |
| HC            | HCAR357-MI                  | Notebook    | [daaf3e0f5f](https://linux-hardware.org/?probe=daaf3e0f5f) | Dec 12, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [3e8d09cc67](https://linux-hardware.org/?probe=3e8d09cc67) | Dec 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [241c795a70](https://linux-hardware.org/?probe=241c795a70) | Dec 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c6f72287f3](https://linux-hardware.org/?probe=c6f72287f3) | Dec 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [afd68e777f](https://linux-hardware.org/?probe=afd68e777f) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [9a8395654c](https://linux-hardware.org/?probe=9a8395654c) | Dec 06, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [a41eb50b0e](https://linux-hardware.org/?probe=a41eb50b0e) | Dec 04, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [16c9e2b55c](https://linux-hardware.org/?probe=16c9e2b55c) | Dec 04, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [e099b86288](https://linux-hardware.org/?probe=e099b86288) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cf6dd1eb40](https://linux-hardware.org/?probe=cf6dd1eb40) | Dec 01, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d307e11a95](https://linux-hardware.org/?probe=d307e11a95) | Dec 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [d46afc319c](https://linux-hardware.org/?probe=d46afc319c) | Nov 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [f71053bf5c](https://linux-hardware.org/?probe=f71053bf5c) | Nov 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [3aa5e4bed1](https://linux-hardware.org/?probe=3aa5e4bed1) | Nov 30, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [68c6f002f5](https://linux-hardware.org/?probe=68c6f002f5) | Nov 28, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [2ddc688d1d](https://linux-hardware.org/?probe=2ddc688d1d) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7077c34a71](https://linux-hardware.org/?probe=7077c34a71) | Nov 27, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [9e97507512](https://linux-hardware.org/?probe=9e97507512) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [77db088b52](https://linux-hardware.org/?probe=77db088b52) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Acer          | Predator PO3-620            | Desktop     | [a052f2ee36](https://linux-hardware.org/?probe=a052f2ee36) | Nov 25, 2023 |
| Supermicro    | H11DSi                      | Server      | [a1cf33e683](https://linux-hardware.org/?probe=a1cf33e683) | Nov 23, 2023 |
| Dell          | Latitude E5520              | Notebook    | [7c773e173a](https://linux-hardware.org/?probe=7c773e173a) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8ae454aca](https://linux-hardware.org/?probe=c8ae454aca) | Nov 20, 2023 |
| Supermicro    | H11DSi                      | Server      | [282df85b76](https://linux-hardware.org/?probe=282df85b76) | Nov 19, 2023 |
| HP            | ZBook 15                    | Notebook    | [7959bd4b85](https://linux-hardware.org/?probe=7959bd4b85) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [89c0fabbb5](https://linux-hardware.org/?probe=89c0fabbb5) | Nov 17, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [4ddc04a5ba](https://linux-hardware.org/?probe=4ddc04a5ba) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0fe7515de5](https://linux-hardware.org/?probe=0fe7515de5) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [6bf67ac977](https://linux-hardware.org/?probe=6bf67ac977) | Nov 15, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [e9e98d1041](https://linux-hardware.org/?probe=e9e98d1041) | Nov 14, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [3567b57191](https://linux-hardware.org/?probe=3567b57191) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [197a03d08f](https://linux-hardware.org/?probe=197a03d08f) | Nov 12, 2023 |
| Samsung       | R530/R730                   | Notebook    | [e1177626c4](https://linux-hardware.org/?probe=e1177626c4) | Nov 11, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [46261b27de](https://linux-hardware.org/?probe=46261b27de) | Nov 09, 2023 |
| HP            | 89E9 0100                   | All in one  | [fafa5e6c96](https://linux-hardware.org/?probe=fafa5e6c96) | Nov 07, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [dd143f192c](https://linux-hardware.org/?probe=dd143f192c) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4a6383e886](https://linux-hardware.org/?probe=4a6383e886) | Nov 04, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [b84c515650](https://linux-hardware.org/?probe=b84c515650) | Nov 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [d802042506](https://linux-hardware.org/?probe=d802042506) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [cdda6b5094](https://linux-hardware.org/?probe=cdda6b5094) | Oct 31, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [5bec5815bb](https://linux-hardware.org/?probe=5bec5815bb) | Oct 31, 2023 |
| ASRock        | H77 Pro4-M                  | Desktop     | [83aeda3c64](https://linux-hardware.org/?probe=83aeda3c64) | Oct 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [0ff396f5c2](https://linux-hardware.org/?probe=0ff396f5c2) | Oct 29, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bf5f9098d7](https://linux-hardware.org/?probe=bf5f9098d7) | Oct 28, 2023 |
| Intel         | H55                         | Desktop     | [f8788bcc72](https://linux-hardware.org/?probe=f8788bcc72) | Oct 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [92c4516951](https://linux-hardware.org/?probe=92c4516951) | Oct 27, 2023 |
| Acer          | Predator PH317-51           | Notebook    | [941e333a3b](https://linux-hardware.org/?probe=941e333a3b) | Oct 27, 2023 |
| HP            | 3397                        | Desktop     | [50b7d4272d](https://linux-hardware.org/?probe=50b7d4272d) | Oct 26, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [4b2be75f68](https://linux-hardware.org/?probe=4b2be75f68) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [4323d57b2f](https://linux-hardware.org/?probe=4323d57b2f) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [817367d444](https://linux-hardware.org/?probe=817367d444) | Oct 23, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [959fc54e2b](https://linux-hardware.org/?probe=959fc54e2b) | Oct 23, 2023 |
| Lenovo        | ThinkPad T460s 20F90060G... | Notebook    | [b44ed99aff](https://linux-hardware.org/?probe=b44ed99aff) | Oct 22, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [73fdacf30c](https://linux-hardware.org/?probe=73fdacf30c) | Oct 18, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [2079534fd9](https://linux-hardware.org/?probe=2079534fd9) | Oct 18, 2023 |
| MSI           | MPG B650 EDGE WIFI          | Desktop     | [5902fdf35f](https://linux-hardware.org/?probe=5902fdf35f) | Oct 18, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [04d307e685](https://linux-hardware.org/?probe=04d307e685) | Oct 16, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [e30927f66e](https://linux-hardware.org/?probe=e30927f66e) | Oct 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4b5b669131](https://linux-hardware.org/?probe=4b5b669131) | Oct 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| HP            | 8053                        | Desktop     | [52151555cb](https://linux-hardware.org/?probe=52151555cb) | Oct 11, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [be6e7011cc](https://linux-hardware.org/?probe=be6e7011cc) | Oct 11, 2023 |
| HP            | 8053                        | Desktop     | [d1ce4588e7](https://linux-hardware.org/?probe=d1ce4588e7) | Oct 11, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [bc5016980d](https://linux-hardware.org/?probe=bc5016980d) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [49d0e884bb](https://linux-hardware.org/?probe=49d0e884bb) | Oct 08, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ad00ca7536](https://linux-hardware.org/?probe=ad00ca7536) | Oct 07, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [61fef3256c](https://linux-hardware.org/?probe=61fef3256c) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3d613c96a8](https://linux-hardware.org/?probe=3d613c96a8) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8bc96db254](https://linux-hardware.org/?probe=8bc96db254) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [61579851ef](https://linux-hardware.org/?probe=61579851ef) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [9410b590b4](https://linux-hardware.org/?probe=9410b590b4) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [2a6facae05](https://linux-hardware.org/?probe=2a6facae05) | Oct 05, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [e7906b9cd7](https://linux-hardware.org/?probe=e7906b9cd7) | Oct 04, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [1c7bef5950](https://linux-hardware.org/?probe=1c7bef5950) | Oct 04, 2023 |
| Intel         | X99                         | Desktop     | [67ec0ac8d0](https://linux-hardware.org/?probe=67ec0ac8d0) | Oct 02, 2023 |
| Unknown       | TB-5000                     | Desktop     | [9c67baa34f](https://linux-hardware.org/?probe=9c67baa34f) | Sep 29, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ecef286c2a](https://linux-hardware.org/?probe=ecef286c2a) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| AMI           | Intel                       | Notebook    | [ebb3577023](https://linux-hardware.org/?probe=ebb3577023) | Sep 23, 2023 |
| HP            | 1998                        | Desktop     | [60208f6be9](https://linux-hardware.org/?probe=60208f6be9) | Sep 22, 2023 |
| ASUSTek       | X455LD                      | Notebook    | [1e79e3536c](https://linux-hardware.org/?probe=1e79e3536c) | Sep 20, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| MSI           | Stealth 14Studio A13VE      | Notebook    | [e57ab86521](https://linux-hardware.org/?probe=e57ab86521) | Sep 16, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [5995975e04](https://linux-hardware.org/?probe=5995975e04) | Sep 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fa347b6b46](https://linux-hardware.org/?probe=fa347b6b46) | Sep 15, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [623cd3e438](https://linux-hardware.org/?probe=623cd3e438) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [78ddadfb89](https://linux-hardware.org/?probe=78ddadfb89) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [3145861387](https://linux-hardware.org/?probe=3145861387) | Sep 12, 2023 |
| Gigabyte      | AX370-Gaming 3-CF           | Desktop     | [b037f9322d](https://linux-hardware.org/?probe=b037f9322d) | Sep 10, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [647634e7fb](https://linux-hardware.org/?probe=647634e7fb) | Sep 10, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [5330a96ef6](https://linux-hardware.org/?probe=5330a96ef6) | Sep 07, 2023 |
| Matsushita... | CF-74JCJBDAM                | Notebook    | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [9441e027c6](https://linux-hardware.org/?probe=9441e027c6) | Sep 04, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3b0d2983a6](https://linux-hardware.org/?probe=3b0d2983a6) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [10951f0a65](https://linux-hardware.org/?probe=10951f0a65) | Sep 01, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [ac6c5c8969](https://linux-hardware.org/?probe=ac6c5c8969) | Sep 01, 2023 |
| MOTION        | NVX00                       | Notebook    | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5d571876c8](https://linux-hardware.org/?probe=5d571876c8) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2f4fd95449](https://linux-hardware.org/?probe=2f4fd95449) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fde9e1a454](https://linux-hardware.org/?probe=fde9e1a454) | Aug 20, 2023 |
| ASUSTek       | M51BC                       | Desktop     | [4a81412fdd](https://linux-hardware.org/?probe=4a81412fdd) | Aug 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [0657120653](https://linux-hardware.org/?probe=0657120653) | Aug 19, 2023 |
| Lenovo        | ThinkPad T61 7661ZSF        | Notebook    | [2a461c159d](https://linux-hardware.org/?probe=2a461c159d) | Aug 18, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [9c90e63339](https://linux-hardware.org/?probe=9c90e63339) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f0b1f6f364](https://linux-hardware.org/?probe=f0b1f6f364) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [a9d7216b70](https://linux-hardware.org/?probe=a9d7216b70) | Aug 15, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4dc7a0831b](https://linux-hardware.org/?probe=4dc7a0831b) | Aug 14, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [369b0195cc](https://linux-hardware.org/?probe=369b0195cc) | Aug 14, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [ef08441bc9](https://linux-hardware.org/?probe=ef08441bc9) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [b0f8b16669](https://linux-hardware.org/?probe=b0f8b16669) | Aug 13, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4daff2c43f](https://linux-hardware.org/?probe=4daff2c43f) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [68fff65eee](https://linux-hardware.org/?probe=68fff65eee) | Aug 10, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [81a2d0415e](https://linux-hardware.org/?probe=81a2d0415e) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [de06cea570](https://linux-hardware.org/?probe=de06cea570) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [4275d43a74](https://linux-hardware.org/?probe=4275d43a74) | Aug 10, 2023 |
| Dell          | Precision 5530              | Notebook    | [3b10bebb7d](https://linux-hardware.org/?probe=3b10bebb7d) | Aug 10, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [65343a7900](https://linux-hardware.org/?probe=65343a7900) | Aug 06, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [af88e64084](https://linux-hardware.org/?probe=af88e64084) | Aug 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [88e9cc22bf](https://linux-hardware.org/?probe=88e9cc22bf) | Aug 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [52319a8cef](https://linux-hardware.org/?probe=52319a8cef) | Aug 03, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b736ced64](https://linux-hardware.org/?probe=6b736ced64) | Aug 03, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [4d98867c44](https://linux-hardware.org/?probe=4d98867c44) | Aug 02, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [675811747f](https://linux-hardware.org/?probe=675811747f) | Aug 02, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ba2cec8099](https://linux-hardware.org/?probe=ba2cec8099) | Aug 01, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [cdbcf58dcb](https://linux-hardware.org/?probe=cdbcf58dcb) | Jul 30, 2023 |
| HP            | ENVY Notebook               | Notebook    | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2dbda5ea48](https://linux-hardware.org/?probe=2dbda5ea48) | Jul 29, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| Alienware     | 13 R3                       | Notebook    | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3a59ab6dd1](https://linux-hardware.org/?probe=3a59ab6dd1) | Jul 26, 2023 |
| HP            | 18E7                        | Desktop     | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| Biostar       | B350GT3                     | Desktop     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Alienware     | 07W25T A00                  | Desktop     | [24dade96af](https://linux-hardware.org/?probe=24dade96af) | Jul 21, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5d2c798252](https://linux-hardware.org/?probe=5d2c798252) | Jul 21, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [79ab32a714](https://linux-hardware.org/?probe=79ab32a714) | Jul 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [228fca7e43](https://linux-hardware.org/?probe=228fca7e43) | Jul 17, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [f47d2eaa8e](https://linux-hardware.org/?probe=f47d2eaa8e) | Jul 16, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [a505a2e91f](https://linux-hardware.org/?probe=a505a2e91f) | Jul 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [eb85c87997](https://linux-hardware.org/?probe=eb85c87997) | Jul 12, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| HP            | 8053                        | Desktop     | [4241a715e6](https://linux-hardware.org/?probe=4241a715e6) | Jul 09, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [5e8900dde2](https://linux-hardware.org/?probe=5e8900dde2) | Jul 02, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [b819a1fb21](https://linux-hardware.org/?probe=b819a1fb21) | Jul 02, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [fe1c9de1b6](https://linux-hardware.org/?probe=fe1c9de1b6) | Jul 02, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [529873f796](https://linux-hardware.org/?probe=529873f796) | Jul 02, 2023 |
| HP            | 1998                        | Desktop     | [cee46b5772](https://linux-hardware.org/?probe=cee46b5772) | Jul 01, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [047aac4298](https://linux-hardware.org/?probe=047aac4298) | Jun 25, 2023 |
| Notebook      | P870DM                      | Notebook    | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [88e2f62c6d](https://linux-hardware.org/?probe=88e2f62c6d) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2278cd4d03](https://linux-hardware.org/?probe=2278cd4d03) | Jun 17, 2023 |
| Biostar       | B350GT3                     | Desktop     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| Dell          | Latitude E6510              | Notebook    | [f3e9e3bbf1](https://linux-hardware.org/?probe=f3e9e3bbf1) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [29d4909dd4](https://linux-hardware.org/?probe=29d4909dd4) | Jun 12, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f73406fa5d](https://linux-hardware.org/?probe=f73406fa5d) | Jun 04, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [1c2d6e0e5e](https://linux-hardware.org/?probe=1c2d6e0e5e) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Notebook                    | Notebook    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | Desktop     | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| Dell          | Precision 5520              | Notebook    | [c7097157ab](https://linux-hardware.org/?probe=c7097157ab) | May 28, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Win elemen... | M600                        | Desktop     | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [262bc7c88f](https://linux-hardware.org/?probe=262bc7c88f) | May 21, 2023 |
| MICROBYTE     | ezbook                      | Notebook    | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| Win elemen... | M600                        | Desktop     | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [ad5fd46d55](https://linux-hardware.org/?probe=ad5fd46d55) | May 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| MSI           | GL75 9SD                    | Notebook    | [522594401b](https://linux-hardware.org/?probe=522594401b) | May 07, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Lenovo        | ThinkPad W520 42824UU       | Notebook    | [c8474ef15e](https://linux-hardware.org/?probe=c8474ef15e) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [182acb48b9](https://linux-hardware.org/?probe=182acb48b9) | May 01, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Monster       | TULPAR T5 V21.7             | Notebook    | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f48b78bda1](https://linux-hardware.org/?probe=f48b78bda1) | Apr 23, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bb189b2507](https://linux-hardware.org/?probe=bb189b2507) | Apr 22, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [a76057a8be](https://linux-hardware.org/?probe=a76057a8be) | Apr 19, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a0e44bf0d1](https://linux-hardware.org/?probe=a0e44bf0d1) | Apr 13, 2023 |
| Win elemen... | M600                        | Desktop     | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | Desktop     | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [e2521c6d93](https://linux-hardware.org/?probe=e2521c6d93) | Apr 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | 8053                        | Desktop     | [9897b3e51f](https://linux-hardware.org/?probe=9897b3e51f) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [7a2bce56b1](https://linux-hardware.org/?probe=7a2bce56b1) | Mar 26, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [946646a961](https://linux-hardware.org/?probe=946646a961) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [de7c54aec1](https://linux-hardware.org/?probe=de7c54aec1) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [fdea1b7da5](https://linux-hardware.org/?probe=fdea1b7da5) | Mar 22, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [f886dec5e7](https://linux-hardware.org/?probe=f886dec5e7) | Mar 22, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9cd7e18a6d](https://linux-hardware.org/?probe=9cd7e18a6d) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [87292d633d](https://linux-hardware.org/?probe=87292d633d) | Mar 21, 2023 |
| HP            | 8053                        | Desktop     | [82eb90837f](https://linux-hardware.org/?probe=82eb90837f) | Mar 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e0317127ea](https://linux-hardware.org/?probe=e0317127ea) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [40372e4af3](https://linux-hardware.org/?probe=40372e4af3) | Mar 19, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [da8abe8a8e](https://linux-hardware.org/?probe=da8abe8a8e) | Mar 19, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [15f0543609](https://linux-hardware.org/?probe=15f0543609) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d10f13efc](https://linux-hardware.org/?probe=9d10f13efc) | Mar 18, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [a3234542a9](https://linux-hardware.org/?probe=a3234542a9) | Mar 17, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [8bab1523ae](https://linux-hardware.org/?probe=8bab1523ae) | Mar 16, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [02015c3c38](https://linux-hardware.org/?probe=02015c3c38) | Mar 15, 2023 |
| HP            | 8053                        | Desktop     | [273a6c822b](https://linux-hardware.org/?probe=273a6c822b) | Mar 12, 2023 |
| HP            | 8053                        | Desktop     | [be27383efc](https://linux-hardware.org/?probe=be27383efc) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [51b92fb276](https://linux-hardware.org/?probe=51b92fb276) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Dell          | 0VYXHD A00                  | Desktop     | [d7618c5b6c](https://linux-hardware.org/?probe=d7618c5b6c) | Mar 08, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [f43d0b8fa2](https://linux-hardware.org/?probe=f43d0b8fa2) | Mar 06, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [b2fa34d832](https://linux-hardware.org/?probe=b2fa34d832) | Feb 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [575a7f4897](https://linux-hardware.org/?probe=575a7f4897) | Feb 26, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [466f8533fb](https://linux-hardware.org/?probe=466f8533fb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| HP            | Unknown                     | Notebook    | [06f5e98fdd](https://linux-hardware.org/?probe=06f5e98fdd) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [0cf7067e58](https://linux-hardware.org/?probe=0cf7067e58) | Feb 18, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| Dell          | Precision 7710              | Notebook    | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| MobileDema... | xTablet T1200               | Notebook    | [905b6efd7a](https://linux-hardware.org/?probe=905b6efd7a) | Feb 12, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [59271934a3](https://linux-hardware.org/?probe=59271934a3) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [5140856482](https://linux-hardware.org/?probe=5140856482) | Feb 06, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [62c1d53a4a](https://linux-hardware.org/?probe=62c1d53a4a) | Feb 06, 2023 |
| HP            | Unknown                     | Notebook    | [b1dacc0d29](https://linux-hardware.org/?probe=b1dacc0d29) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [2c6c4d9777](https://linux-hardware.org/?probe=2c6c4d9777) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [683f389938](https://linux-hardware.org/?probe=683f389938) | Feb 04, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [91dbb8d045](https://linux-hardware.org/?probe=91dbb8d045) | Jan 26, 2023 |
| Standard      | Unknown                     | Notebook    | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [918dbdb148](https://linux-hardware.org/?probe=918dbdb148) | Jan 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [39bd375140](https://linux-hardware.org/?probe=39bd375140) | Jan 19, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [64553c4fd7](https://linux-hardware.org/?probe=64553c4fd7) | Jan 17, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [87e7a60bfa](https://linux-hardware.org/?probe=87e7a60bfa) | Jan 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [919b330a89](https://linux-hardware.org/?probe=919b330a89) | Jan 15, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [7eac1c6a7a](https://linux-hardware.org/?probe=7eac1c6a7a) | Jan 13, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [06fc7ee349](https://linux-hardware.org/?probe=06fc7ee349) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [5e29a1afb7](https://linux-hardware.org/?probe=5e29a1afb7) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [8daa546122](https://linux-hardware.org/?probe=8daa546122) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [1ba0c80baf](https://linux-hardware.org/?probe=1ba0c80baf) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| HP            | ProBook 6570b               | Notebook    | [71e645c6db](https://linux-hardware.org/?probe=71e645c6db) | Jan 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [c3162b7bfa](https://linux-hardware.org/?probe=c3162b7bfa) | Jan 07, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [8d0c80e474](https://linux-hardware.org/?probe=8d0c80e474) | Jan 07, 2023 |
| HP            | ProBook 6570b               | Notebook    | [6db7bfdd12](https://linux-hardware.org/?probe=6db7bfdd12) | Jan 07, 2023 |
| Dell          | G15 5515                    | Notebook    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| HP            | ProBook 6570b               | Notebook    | [32d96991fd](https://linux-hardware.org/?probe=32d96991fd) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| Intel         | X79M-S                      | Desktop     | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [901f1e43f0](https://linux-hardware.org/?probe=901f1e43f0) | Dec 31, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [631ee5c81c](https://linux-hardware.org/?probe=631ee5c81c) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [1c406a3696](https://linux-hardware.org/?probe=1c406a3696) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [08ac155787](https://linux-hardware.org/?probe=08ac155787) | Dec 31, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [9561e51689](https://linux-hardware.org/?probe=9561e51689) | Dec 31, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| Intel         | H61                         | Desktop     | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8fe5127ba0](https://linux-hardware.org/?probe=8fe5127ba0) | Dec 25, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [0e92e9aaf2](https://linux-hardware.org/?probe=0e92e9aaf2) | Dec 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5cc9050d12](https://linux-hardware.org/?probe=5cc9050d12) | Dec 22, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [7ce8a10de4](https://linux-hardware.org/?probe=7ce8a10de4) | Dec 21, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [a4c1397ad3](https://linux-hardware.org/?probe=a4c1397ad3) | Dec 21, 2022 |
| Alienware     | m15 R7                      | Notebook    | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [b262201707](https://linux-hardware.org/?probe=b262201707) | Dec 10, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [d9fbac807d](https://linux-hardware.org/?probe=d9fbac807d) | Dec 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [a7f86279b6](https://linux-hardware.org/?probe=a7f86279b6) | Dec 04, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [0247b424ca](https://linux-hardware.org/?probe=0247b424ca) | Dec 04, 2022 |
| Dell          | Latitude E5450              | Notebook    | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| Dell          | Latitude E7450              | Notebook    | [2df62b206f](https://linux-hardware.org/?probe=2df62b206f) | Dec 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [93aed684b7](https://linux-hardware.org/?probe=93aed684b7) | Dec 03, 2022 |
| Standard      | Unknown                     | Notebook    | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [8967d04a19](https://linux-hardware.org/?probe=8967d04a19) | Nov 25, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | Desktop     | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [5c079d3e41](https://linux-hardware.org/?probe=5c079d3e41) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [2a5b05500a](https://linux-hardware.org/?probe=2a5b05500a) | Nov 11, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [f0b3051737](https://linux-hardware.org/?probe=f0b3051737) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| Dell          | Precision 3571              | Notebook    | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | Notebook    | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [8641947cf9](https://linux-hardware.org/?probe=8641947cf9) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| HP            | 2B2C                        | Desktop     | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5fa4e96f1c](https://linux-hardware.org/?probe=5fa4e96f1c) | Oct 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [b0fb3c2590](https://linux-hardware.org/?probe=b0fb3c2590) | Oct 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e744ed6ac6](https://linux-hardware.org/?probe=e744ed6ac6) | Oct 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [06fbfa78a5](https://linux-hardware.org/?probe=06fbfa78a5) | Oct 11, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e009be07a6](https://linux-hardware.org/?probe=e009be07a6) | Oct 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [1c50c72b71](https://linux-hardware.org/?probe=1c50c72b71) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Fujitsu       | FMVA1200G                   | Notebook    | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Acer          | Aspire V5-552P              | Notebook    | [46395f51b5](https://linux-hardware.org/?probe=46395f51b5) | Sep 27, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| HP            | Notebook                    | Notebook    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Dell          | Precision 7510              | Notebook    | [5f94678049](https://linux-hardware.org/?probe=5f94678049) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1cf1136fb8](https://linux-hardware.org/?probe=1cf1136fb8) | Sep 13, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [c1c2e05a86](https://linux-hardware.org/?probe=c1c2e05a86) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1a8681a1f5](https://linux-hardware.org/?probe=1a8681a1f5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [cfb1abc54b](https://linux-hardware.org/?probe=cfb1abc54b) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [87fac1a064](https://linux-hardware.org/?probe=87fac1a064) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2c79168e77](https://linux-hardware.org/?probe=2c79168e77) | Sep 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [40482ce9a3](https://linux-hardware.org/?probe=40482ce9a3) | Sep 01, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f9fbb00a0b](https://linux-hardware.org/?probe=f9fbb00a0b) | Aug 23, 2022 |
| HP            | Notebook                    | Notebook    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [822e93c1db](https://linux-hardware.org/?probe=822e93c1db) | Aug 02, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [e8770aea50](https://linux-hardware.org/?probe=e8770aea50) | Jul 14, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f44445fbe2](https://linux-hardware.org/?probe=f44445fbe2) | Jul 13, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [9ade46617e](https://linux-hardware.org/?probe=9ade46617e) | Jul 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [042c11425c](https://linux-hardware.org/?probe=042c11425c) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Samsung       | 730QDA                      | Convertible | [c46de205cd](https://linux-hardware.org/?probe=c46de205cd) | May 17, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Razer         | Blade                       | Notebook    | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| HP            | 8433 11                     | Desktop     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c092681184](https://linux-hardware.org/?probe=c092681184) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| HP            | 8767 A                      | Desktop     | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [6dc9aa1e88](https://linux-hardware.org/?probe=6dc9aa1e88) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | Notebook    | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Garuda_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 519       | 60.35%  |
| Garuda Linux Rolling | 234       | 27.21%  |
| Garuda Linux         | 107       | 12.44%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 843       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 6.12.4-zen1-1-zen  | 15        | 1.52%   |
| 6.10.6-zen1-1-zen  | 14        | 1.42%   |
| 6.5.9-zen2-1-zen   | 13        | 1.32%   |
| 6.1.1-zen1-1-zen   | 13        | 1.32%   |
| 6.9.3-zen1-1-zen   | 12        | 1.21%   |
| 6.6.8-zen1-1-zen   | 12        | 1.21%   |
| 6.11.5-zen1-1-zen  | 12        | 1.21%   |
| 6.0.2-zen1-1-zen   | 11        | 1.11%   |
| 6.10.10-zen1-1-zen | 10        | 1.01%   |
| 6.4.12-zen1-1-zen  | 9         | 0.91%   |
| 6.2.13-zen-1-zen   | 9         | 0.91%   |
| 5.17.1-zen1-1-zen  | 9         | 0.91%   |
| 6.9.5-zen1-1-zen   | 8         | 0.81%   |
| 6.8.2-zen2-1-zen   | 8         | 0.81%   |
| 6.7.0-zen3-1-zen   | 8         | 0.81%   |
| 6.8.7-zen1-2-zen   | 7         | 0.71%   |
| 6.6.7-zen1-1-zen   | 7         | 0.71%   |
| 6.4.10-zen2-1-zen  | 7         | 0.71%   |
| 6.11.6-zen1-1-zen  | 7         | 0.71%   |
| 6.10.8-zen1-1-zen  | 7         | 0.71%   |
| 5.15.2-zen1-1-zen  | 7         | 0.71%   |
| 5.14.14-zen1-1-zen | 7         | 0.71%   |
| 6.9.7-zen1-1-zen   | 6         | 0.61%   |
| 6.8.9-zen1-2-zen   | 6         | 0.61%   |
| 6.8.4-zen1-1-zen   | 6         | 0.61%   |
| 6.7.9-zen1-1-zen   | 6         | 0.61%   |
| 6.2.10-zen1-1-zen  | 6         | 0.61%   |
| 6.12.1-zen1-1-zen  | 6         | 0.61%   |
| 6.11.8-zen1-2-zen  | 6         | 0.61%   |
| 5.17.9-zen1-1-zen  | 6         | 0.61%   |
| 6.9.8-zen1-1-zen   | 5         | 0.51%   |
| 6.8.9-zen1-1-zen   | 5         | 0.51%   |
| 6.8.1-zen1-1-zen   | 5         | 0.51%   |
| 6.7.6-zen1-1-zen   | 5         | 0.51%   |
| 6.7.5-zen1-1-zen   | 5         | 0.51%   |
| 6.6.3-zen1-1-zen   | 5         | 0.51%   |
| 6.6.2-zen1-1-zen   | 5         | 0.51%   |
| 6.5.5-zen1-1-zen   | 5         | 0.51%   |
| 6.3.8-zen1-1-zen   | 5         | 0.51%   |
| 6.2.7-zen1-1-zen   | 5         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.12.4  | 16        | 1.62%   |
| 6.6.8   | 14        | 1.42%   |
| 6.5.9   | 14        | 1.42%   |
| 6.10.6  | 14        | 1.42%   |
| 6.1.1   | 14        | 1.42%   |
| 6.9.3   | 13        | 1.32%   |
| 6.8.7   | 13        | 1.32%   |
| 6.8.9   | 12        | 1.22%   |
| 6.11.5  | 12        | 1.22%   |
| 6.0.2   | 12        | 1.22%   |
| 6.8.2   | 11        | 1.11%   |
| 6.10.10 | 11        | 1.11%   |
| 5.17.1  | 11        | 1.11%   |
| 6.7.6   | 9         | 0.91%   |
| 6.4.12  | 9         | 0.91%   |
| 6.2.13  | 9         | 0.91%   |
| 6.9.5   | 8         | 0.81%   |
| 6.7.0   | 8         | 0.81%   |
| 6.4.10  | 8         | 0.81%   |
| 6.10.8  | 8         | 0.81%   |
| 6.8.4   | 7         | 0.71%   |
| 6.6.7   | 7         | 0.71%   |
| 6.5.5   | 7         | 0.71%   |
| 6.2.10  | 7         | 0.71%   |
| 6.11.6  | 7         | 0.71%   |
| 5.15.2  | 7         | 0.71%   |
| 5.14.14 | 7         | 0.71%   |
| 6.9.8   | 6         | 0.61%   |
| 6.9.7   | 6         | 0.61%   |
| 6.7.9   | 6         | 0.61%   |
| 6.6.3   | 6         | 0.61%   |
| 6.6.2   | 6         | 0.61%   |
| 6.2.7   | 6         | 0.61%   |
| 6.12.7  | 6         | 0.61%   |
| 6.12.1  | 6         | 0.61%   |
| 6.11.8  | 6         | 0.61%   |
| 6.1.9   | 6         | 0.61%   |
| 6.0.8   | 6         | 0.61%   |
| 5.18.16 | 6         | 0.61%   |
| 5.17.9  | 6         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6     | 69        | 7.22%   |
| 6.1     | 63        | 6.59%   |
| 6.8     | 57        | 5.96%   |
| 6.10    | 55        | 5.75%   |
| 5.15    | 54        | 5.65%   |
| 6.9     | 50        | 5.23%   |
| 6.4     | 50        | 5.23%   |
| 6.0     | 49        | 5.13%   |
| 6.11    | 43        | 4.5%    |
| 6.2     | 41        | 4.29%   |
| 5.16    | 41        | 4.29%   |
| 6.5     | 39        | 4.08%   |
| 6.7     | 38        | 3.97%   |
| 5.18    | 36        | 3.77%   |
| 5.10    | 36        | 3.77%   |
| 6.12    | 34        | 3.56%   |
| 5.19    | 32        | 3.35%   |
| 5.17    | 31        | 3.24%   |
| 5.14    | 27        | 2.82%   |
| 6.3     | 24        | 2.51%   |
| 5.12    | 23        | 2.41%   |
| 5.11    | 23        | 2.41%   |
| 5.13    | 21        | 2.2%    |
| 5.9     | 13        | 1.36%   |
| 5.8     | 5         | 0.52%   |
| 5.6     | 1         | 0.1%    |
| 5.4     | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 843       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 433       | 49.32%  |
| KDE6              | 166       | 18.91%  |
| GNOME             | 95        | 10.82%  |
| KDE               | 60        | 6.83%   |
| XFCE              | 42        | 4.78%   |
| X-Cinnamon        | 21        | 2.39%   |
| sway              | 11        | 1.25%   |
| hyprland          | 11        | 1.25%   |
| Unknown           | 7         | 0.8%    |
| Deepin            | 6         | 0.68%   |
| Cinnamon          | 5         | 0.57%   |
| qtile-default     | 4         | 0.46%   |
| MATE              | 4         | 0.46%   |
| LXQt              | 4         | 0.46%   |
| i3                | 3         | 0.34%   |
| qtile             | 2         | 0.23%   |
| Yaru:ubuntu:GNOME | 1         | 0.11%   |
| Unity             | 1         | 0.11%   |
| Budgie            | 1         | 0.11%   |
| awesome           | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 586       | 67.59%  |
| Wayland | 260       | 29.99%  |
| Unknown | 11        | 1.27%   |
| Tty     | 10        | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 387       | 45.1%   |
| Unknown | 335       | 39.04%  |
| LightDM | 71        | 8.28%   |
| GDM     | 56        | 6.53%   |
| GREETD  | 8         | 0.93%   |
| EMPTTY  | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 425       | 50.06%  |
| en_GB   | 80        | 9.42%   |
| de_DE   | 62        | 7.3%    |
| en_CA   | 36        | 4.24%   |
| it_IT   | 31        | 3.65%   |
| en_IN   | 29        | 3.42%   |
| pt_BR   | 20        | 2.36%   |
| pl_PL   | 16        | 1.88%   |
| es_ES   | 14        | 1.65%   |
| ru_RU   | 12        | 1.41%   |
| fr_FR   | 12        | 1.41%   |
| nl_NL   | 10        | 1.18%   |
| tr_TR   | 9         | 1.06%   |
| es_MX   | 9         | 1.06%   |
| en_AU   | 7         | 0.82%   |
| en_ZA   | 6         | 0.71%   |
| sv_SE   | 5         | 0.59%   |
| de_AT   | 5         | 0.59%   |
| fr_CA   | 4         | 0.47%   |
| es_CO   | 4         | 0.47%   |
| de_CH   | 4         | 0.47%   |
| hu_HU   | 3         | 0.35%   |
| es_AR   | 3         | 0.35%   |
| en_DK   | 3         | 0.35%   |
| sk_SK   | 2         | 0.24%   |
| ja_JP   | 2         | 0.24%   |
| fr_BE   | 2         | 0.24%   |
| fi_FI   | 2         | 0.24%   |
| es_VE   | 2         | 0.24%   |
| es_EC   | 2         | 0.24%   |
| en_AG   | 2         | 0.24%   |
| el_GR   | 2         | 0.24%   |
| da_DK   | 2         | 0.24%   |
| cs_CZ   | 2         | 0.24%   |
| Unknown | 2         | 0.24%   |
| zh_CN   | 1         | 0.12%   |
| vi_VN   | 1         | 0.12%   |
| uk_UA   | 1         | 0.12%   |
| sl_SI   | 1         | 0.12%   |
| nl_BE   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 486       | 56.98%  |
| BIOS | 367       | 43.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 820       | 97.16%  |
| Overlay | 11        | 1.3%    |
| Tmpfs   | 8         | 0.95%   |
| Ext4    | 2         | 0.24%   |
| XXXXX   | 1         | 0.12%   |
| Xfs     | 1         | 0.12%   |
| F2fs    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 494       | 57.71%  |
| Unknown | 329       | 38.43%  |
| MBR     | 33        | 3.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 730       | 85.38%  |
| Yes       | 125       | 14.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 596       | 69.54%  |
| Yes       | 261       | 30.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 174       | 20.64%  |
| Lenovo                               | 112       | 13.29%  |
| Hewlett-Packard                      | 97        | 11.51%  |
| MSI                                  | 88        | 10.44%  |
| Dell                                 | 81        | 9.61%   |
| Gigabyte Technology                  | 60        | 7.12%   |
| Acer                                 | 45        | 5.34%   |
| ASRock                               | 32        | 3.8%    |
| Apple                                | 21        | 2.49%   |
| Intel                                | 8         | 0.95%   |
| HUAWEI                               | 8         | 0.95%   |
| Unknown                              | 8         | 0.95%   |
| Samsung Electronics                  | 7         | 0.83%   |
| Alienware                            | 7         | 0.83%   |
| Razer                                | 6         | 0.71%   |
| Notebook                             | 6         | 0.71%   |
| Fujitsu                              | 6         | 0.71%   |
| Toshiba                              | 5         | 0.59%   |
| Shenzhen Meigao Electronic Equipment | 5         | 0.59%   |
| AZW                                  | 5         | 0.59%   |
| Microsoft                            | 4         | 0.47%   |
| Medion                               | 3         | 0.36%   |
| Google                               | 3         | 0.36%   |
| XIAOMI                               | 2         | 0.24%   |
| Sony                                 | 2         | 0.24%   |
| Schenker                             | 2         | 0.24%   |
| Pegatron                             | 2         | 0.24%   |
| Monster                              | 2         | 0.24%   |
| HONOR                                | 2         | 0.24%   |
| HC Technology.                       | 2         | 0.24%   |
| GPU Company                          | 2         | 0.24%   |
| GPD                                  | 2         | 0.24%   |
| Casper                               | 2         | 0.24%   |
| Biostar                              | 2         | 0.24%   |
| Win element                          | 1         | 0.12%   |
| Valve                                | 1         | 0.12%   |
| Timi                                 | 1         | 0.12%   |
| T-bao                                | 1         | 0.12%   |
| Supermicro                           | 1         | 0.12%   |
| Standard                             | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 12        | 1.42%   |
| ASUS TUF Gaming X570-PLUS                         | 9         | 1.07%   |
| MSI MS-7C91                                       | 5         | 0.59%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY              | 5         | 0.59%   |
| Apple MacBookPro9,2                               | 5         | 0.59%   |
| MSI MS-7C56                                       | 4         | 0.47%   |
| MSI MS-7C02                                       | 4         | 0.47%   |
| MSI MS-7B86                                       | 4         | 0.47%   |
| ASUS TUF Gaming B550-PLUS WIFI II                 | 4         | 0.47%   |
| Shenzhen Meigao Electronic Equipment Venus series | 3         | 0.36%   |
| MSI MS-7C37                                       | 3         | 0.36%   |
| MSI MS-7B79                                       | 3         | 0.36%   |
| HP Laptop 15-da0xxx                               | 3         | 0.36%   |
| Dell Inspiron 15 7000 Gaming                      | 3         | 0.36%   |
| AZW SER                                           | 3         | 0.36%   |
| ASUS Vivobook Go E1504FA_E1504FA                  | 3         | 0.36%   |
| ASUS ROG STRIX X570-E GAMING                      | 3         | 0.36%   |
| ASUS All Series                                   | 3         | 0.36%   |
| XIAOMI Redmi Book Pro 15 2023                     | 2         | 0.24%   |
| Razer Blade                                       | 2         | 0.24%   |
| Notebook P7xxDM2(-G)                              | 2         | 0.24%   |
| MSI MS-7E10                                       | 2         | 0.24%   |
| MSI MS-7D75                                       | 2         | 0.24%   |
| MSI MS-7B93                                       | 2         | 0.24%   |
| MSI MS-7B89                                       | 2         | 0.24%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS0JT00          | 2         | 0.24%   |
| Lenovo ThinkPad W530 24474KG                      | 2         | 0.24%   |
| Lenovo IdeaPad 3 15ITL05 81X8                     | 2         | 0.24%   |
| HUAWEI HVY-WXX9                                   | 2         | 0.24%   |
| HP ProDesk 600 G1 SFF                             | 2         | 0.24%   |
| HP ProBook 640 G1                                 | 2         | 0.24%   |
| HP Pavilion Laptop 15-cc1xx                       | 2         | 0.24%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 2         | 0.24%   |
| HP Pavilion Gaming Laptop 15-cx0xxx               | 2         | 0.24%   |
| HP Pavilion Gaming Desktop 690-00xx               | 2         | 0.24%   |
| HP Pavilion dv6                                   | 2         | 0.24%   |
| HP OMEN Laptop 15-en0xxx                          | 2         | 0.24%   |
| HP OMEN by Laptop 15-dh1xxx                       | 2         | 0.24%   |
| HP Notebook                                       | 2         | 0.24%   |
| HP Laptop 15-ef2xxx                               | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 45        | 5.34%   |
| Lenovo ThinkPad    | 36        | 4.27%   |
| ASUS TUF           | 29        | 3.44%   |
| Lenovo IdeaPad     | 28        | 3.32%   |
| Dell Inspiron      | 26        | 3.08%   |
| ASUS PRIME         | 25        | 2.97%   |
| HP Pavilion        | 22        | 2.61%   |
| Acer Aspire        | 22        | 2.61%   |
| ASUS VivoBook      | 20        | 2.37%   |
| HP Laptop          | 18        | 2.14%   |
| Dell Latitude      | 16        | 1.9%    |
| Lenovo Legion      | 14        | 1.66%   |
| Unknown            | 12        | 1.42%   |
| Dell Precision     | 11        | 1.3%    |
| Dell OptiPlex      | 11        | 1.3%    |
| Acer Nitro         | 10        | 1.19%   |
| ASUS ASUS          | 9         | 1.07%   |
| HP OMEN            | 8         | 0.95%   |
| Lenovo Yoga        | 7         | 0.83%   |
| Lenovo ThinkCentre | 7         | 0.83%   |
| HP EliteBook       | 7         | 0.83%   |
| Dell XPS           | 7         | 0.83%   |
| Apple MacBookPro9  | 7         | 0.83%   |
| Razer Blade        | 6         | 0.71%   |
| Gigabyte B550      | 6         | 0.71%   |
| Gigabyte B450      | 6         | 0.71%   |
| Toshiba Satellite  | 5         | 0.59%   |
| MSI MS-7C91        | 5         | 0.59%   |
| HP ProBook         | 5         | 0.59%   |
| HP EliteDesk       | 5         | 0.59%   |
| Gigabyte X570      | 5         | 0.59%   |
| Acer Swift         | 5         | 0.59%   |
| MSI MS-7C56        | 4         | 0.47%   |
| MSI MS-7C02        | 4         | 0.47%   |
| MSI MS-7B86        | 4         | 0.47%   |
| Microsoft Surface  | 4         | 0.47%   |
| HP Victus          | 4         | 0.47%   |
| HP ENVY            | 4         | 0.47%   |
| Dell G15           | 4         | 0.47%   |
| ASUS Zenbook       | 4         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 123       | 14.59%  |
| 2021    | 109       | 12.93%  |
| 2019    | 89        | 10.56%  |
| 2018    | 78        | 9.25%   |
| 2022    | 74        | 8.78%   |
| 2017    | 66        | 7.83%   |
| 2013    | 49        | 5.81%   |
| 2012    | 48        | 5.69%   |
| 2023    | 40        | 4.74%   |
| 2014    | 39        | 4.63%   |
| 2016    | 32        | 3.8%    |
| 2011    | 26        | 3.08%   |
| 2015    | 19        | 2.25%   |
| 2024    | 17        | 2.02%   |
| 2010    | 11        | 1.3%    |
| 2009    | 10        | 1.19%   |
| 2008    | 9         | 1.07%   |
| 2007    | 3         | 0.36%   |
| Unknown | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 446       | 52.91%  |
| Desktop     | 340       | 40.33%  |
| Convertible | 26        | 3.08%   |
| Mini pc     | 12        | 1.42%   |
| All in one  | 11        | 1.3%    |
| Tablet      | 7         | 0.83%   |
| Server      | 1         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 843       | 99.88%  |
| Enabled  | 1         | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 840       | 99.64%  |
| Yes  | 3         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 215       | 25.21%  |
| 32.01-64.0  | 181       | 21.22%  |
| 8.01-16.0   | 168       | 19.7%   |
| 4.01-8.0    | 162       | 18.99%  |
| 64.01-256.0 | 44        | 5.16%   |
| 3.01-4.0    | 42        | 4.92%   |
| 24.01-32.0  | 40        | 4.69%   |
| 2.01-3.0    | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 364       | 39.74%  |
| 3.01-4.0    | 198       | 21.62%  |
| 2.01-3.0    | 175       | 19.1%   |
| 8.01-16.0   | 96        | 10.48%  |
| 1.01-2.0    | 61        | 6.66%   |
| 16.01-24.0  | 16        | 1.75%   |
| 32.01-64.0  | 2         | 0.22%   |
| 0.51-1.0    | 2         | 0.22%   |
| 24.01-32.0  | 1         | 0.11%   |
| 64.01-256.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 377       | 43.48%  |
| 2      | 264       | 30.45%  |
| 3      | 111       | 12.8%   |
| 4      | 52        | 6%      |
| 5      | 28        | 3.23%   |
| 6      | 13        | 1.5%    |
| 7      | 10        | 1.15%   |
| 9      | 7         | 0.81%   |
| 11     | 2         | 0.23%   |
| 18     | 1         | 0.12%   |
| 14     | 1         | 0.12%   |
| 0      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 669       | 78.52%  |
| Yes       | 183       | 21.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 709       | 83.81%  |
| No        | 137       | 16.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 682       | 80.14%  |
| No        | 169       | 19.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 641       | 74.88%  |
| No        | 215       | 25.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 240       | 28.27%  |
| Germany      | 87        | 10.25%  |
| Canada       | 49        | 5.77%   |
| UK           | 45        | 5.3%    |
| Italy        | 45        | 5.3%    |
| India        | 34        | 4%      |
| Brazil       | 28        | 3.3%    |
| Poland       | 24        | 2.83%   |
| Spain        | 19        | 2.24%   |
| Netherlands  | 18        | 2.12%   |
| France       | 18        | 2.12%   |
| Turkey       | 16        | 1.88%   |
| Sweden       | 13        | 1.53%   |
| Russia       | 13        | 1.53%   |
| Mexico       | 13        | 1.53%   |
| Romania      | 10        | 1.18%   |
| Australia    | 10        | 1.18%   |
| Switzerland  | 8         | 0.94%   |
| South Africa | 8         | 0.94%   |
| Belgium      | 8         | 0.94%   |
| Austria      | 8         | 0.94%   |
| Greece       | 7         | 0.82%   |
| Denmark      | 7         | 0.82%   |
| Colombia     | 7         | 0.82%   |
| Hungary      | 6         | 0.71%   |
| Norway       | 5         | 0.59%   |
| Finland      | 5         | 0.59%   |
| Czechia      | 5         | 0.59%   |
| Japan        | 4         | 0.47%   |
| Indonesia    | 4         | 0.47%   |
| Vietnam      | 3         | 0.35%   |
| Slovenia     | 3         | 0.35%   |
| Singapore    | 3         | 0.35%   |
| Serbia       | 3         | 0.35%   |
| Portugal     | 3         | 0.35%   |
| Pakistan     | 3         | 0.35%   |
| Latvia       | 3         | 0.35%   |
| Ecuador      | 3         | 0.35%   |
| Croatia      | 3         | 0.35%   |
| Bulgaria     | 3         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Milan             | 9         | 1.01%   |
| Berlin            | 9         | 1.01%   |
| London            | 7         | 0.79%   |
| Istanbul          | 7         | 0.79%   |
| Chicago           | 7         | 0.79%   |
| Toronto           | 6         | 0.68%   |
| Sydney            | 6         | 0.68%   |
| Athens            | 6         | 0.68%   |
| Warsaw            | 5         | 0.56%   |
| Prague            | 5         | 0.56%   |
| New York          | 5         | 0.56%   |
| Mississauga       | 5         | 0.56%   |
| Los Angeles       | 5         | 0.56%   |
| Florence          | 5         | 0.56%   |
| Denver            | 5         | 0.56%   |
| Dallas            | 5         | 0.56%   |
| Copenhagen        | 5         | 0.56%   |
| Cape Town         | 5         | 0.56%   |
| Valencia          | 4         | 0.45%   |
| Sao Paulo         | 4         | 0.45%   |
| San Jose          | 4         | 0.45%   |
| Portland          | 4         | 0.45%   |
| Montreal          | 4         | 0.45%   |
| Melbourne         | 4         | 0.45%   |
| Krakow            | 4         | 0.45%   |
| Kansas City       | 4         | 0.45%   |
| Hyderabad         | 4         | 0.45%   |
| Frankfurt am Main | 4         | 0.45%   |
| Düsseldorf       | 4         | 0.45%   |
| Drums             | 4         | 0.45%   |
| Wittenbach        | 3         | 0.34%   |
| Stockholm         | 3         | 0.34%   |
| Singapore         | 3         | 0.34%   |
| Seattle           | 3         | 0.34%   |
| Rotterdam         | 3         | 0.34%   |
| Riga              | 3         | 0.34%   |
| Pune              | 3         | 0.34%   |
| Poznan            | 3         | 0.34%   |
| New Glasgow       | 3         | 0.34%   |
| Munich            | 3         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 263       | 437    | 16.82%  |
| Seagate                     | 188       | 281    | 12.02%  |
| WDC                         | 169       | 254    | 10.81%  |
| Sandisk                     | 123       | 156    | 7.86%   |
| Toshiba                     | 83        | 116    | 5.31%   |
| Kingston                    | 68        | 88     | 4.35%   |
| Crucial                     | 58        | 77     | 3.71%   |
| SK hynix                    | 50        | 65     | 3.2%    |
| Intel                       | 44        | 55     | 2.81%   |
| Unknown                     | 37        | 45     | 2.37%   |
| Phison Electronics          | 37        | 51     | 2.37%   |
| Micron Technology           | 31        | 39     | 1.98%   |
| Hitachi                     | 28        | 29     | 1.79%   |
| Micron/Crucial Technology   | 27        | 32     | 1.73%   |
| HGST                        | 25        | 32     | 1.6%    |
| Kingston Technology Company | 24        | 27     | 1.53%   |
| Silicon Motion              | 23        | 24     | 1.47%   |
| SPCC                        | 15        | 18     | 0.96%   |
| KIOXIA                      | 14        | 16     | 0.9%    |
| China                       | 14        | 19     | 0.9%    |
| A-DATA Technology           | 14        | 21     | 0.9%    |
| MAXIO Technology (Hangzhou) | 13        | 16     | 0.83%   |
| Phison                      | 12        | 13     | 0.77%   |
| ADATA Technology            | 12        | 16     | 0.77%   |
| PNY                         | 11        | 11     | 0.7%    |
| Realtek Semiconductor       | 9         | 15     | 0.58%   |
| Apple                       | 9         | 14     | 0.58%   |
| SABRENT                     | 7         | 10     | 0.45%   |
| Intenso                     | 6         | 8      | 0.38%   |
| Corsair                     | 6         | 11     | 0.38%   |
| Transcend                   | 5         | 5      | 0.32%   |
| Team                        | 5         | 9      | 0.32%   |
| OCZ                         | 5         | 6      | 0.32%   |
| JMicron Technology          | 5         | 5      | 0.32%   |
| Hewlett-Packard             | 5         | 5      | 0.32%   |
| Unknown                     | 5         | 6      | 0.32%   |
| Patriot                     | 4         | 11     | 0.26%   |
| LITEONIT                    | 4         | 4      | 0.26%   |
| LITEON                      | 4         | 4      | 0.26%   |
| GOODRAM                     | 4         | 7      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 55        | 3.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 27        | 1.53%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 19        | 1.08%   |
| Samsung SSD 860 EVO 500GB                                         | 16        | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 14        | 0.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                  | 14        | 0.79%   |
| Samsung SSD 850 EVO 250GB                                         | 14        | 0.79%   |
| Intel SSD 660P Series 1024GB                                      | 14        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 13        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 12        | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 12        | 0.68%   |
| Samsung NVMe SSD Drive 1TB                                        | 12        | 0.68%   |
| Phison E16 PCIe4 NVMe Controller 1TB                              | 12        | 0.68%   |
| Phison E12 NVMe Controller 480GB                                  | 12        | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 12        | 0.68%   |
| Samsung SSD 850 EVO 500GB                                         | 11        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                                      | 11        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                                       | 11        | 0.62%   |
| Samsung SSD 860 EVO 1TB                                           | 10        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB               | 10        | 0.57%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB                | 10        | 0.57%   |
| Unknown MMC Card  64GB                                            | 9         | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB                                    | 9         | 0.51%   |
| Samsung SSD 870 EVO 1TB                                           | 9         | 0.51%   |
| Kingston SA400S37240G 240GB SSD                                   | 9         | 0.51%   |
| HGST HTS721010A9E630 1TB                                          | 9         | 0.51%   |
| Toshiba DT01ACA100 1TB                                            | 8         | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 8         | 0.45%   |
| Samsung SSD 980 1TB                                               | 8         | 0.45%   |
| Samsung SSD 860 QVO 1TB                                           | 8         | 0.45%   |
| Kingston SA400S37480G 480GB SSD                                   | 8         | 0.45%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 8         | 0.45%   |
| Seagate ST1000LM049-2GH172 1TB                                    | 7         | 0.4%    |
| Sandisk WD Black SN850 2TB                                        | 7         | 0.4%    |
| Samsung SSD 860 EVO 250GB                                         | 7         | 0.4%    |
| SABRENT Disk 2TB                                                  | 7         | 0.4%    |
| Micron/Crucial P1 NVMe PCIe SSD 1TB                               | 7         | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 6         | 0.34%   |
| WDC WD10JPVX-22JC3T0 1TB                                          | 6         | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                                          | 6         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 179       | 265    | 38.17%  |
| WDC                 | 131       | 212    | 27.93%  |
| Toshiba             | 61        | 84     | 13.01%  |
| Hitachi             | 28        | 29     | 5.97%   |
| HGST                | 25        | 32     | 5.33%   |
| Samsung Electronics | 9         | 12     | 1.92%   |
| SABRENT             | 7         | 10     | 1.49%   |
| Unknown             | 5         | 7      | 1.07%   |
| Apple               | 4         | 8      | 0.85%   |
| TO Exter            | 3         | 3      | 0.64%   |
| JMicron Technology  | 3         | 3      | 0.64%   |
| Intenso             | 3         | 4      | 0.64%   |
| ASMT                | 2         | 3      | 0.43%   |
| Maxtor              | 1         | 1      | 0.21%   |
| LaCie               | 1         | 1      | 0.21%   |
| KESU                | 1         | 1      | 0.21%   |
| Initio              | 1         | 1      | 0.21%   |
| Inateck             | 1         | 1      | 0.21%   |
| IBM/Hitachi         | 1         | 1      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| External            | 1         | 1      | 0.21%   |
| ASMedia             | 1         | 2      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 118       | 166    | 27.06%  |
| Crucial             | 53        | 70     | 12.16%  |
| Kingston            | 43        | 54     | 9.86%   |
| SanDisk             | 33        | 46     | 7.57%   |
| WDC                 | 20        | 21     | 4.59%   |
| SPCC                | 14        | 17     | 3.21%   |
| China               | 14        | 19     | 3.21%   |
| A-DATA Technology   | 14        | 21     | 3.21%   |
| Toshiba             | 11        | 17     | 2.52%   |
| SK hynix            | 10        | 15     | 2.29%   |
| PNY                 | 10        | 10     | 2.29%   |
| Micron Technology   | 6         | 7      | 1.38%   |
| Team                | 5         | 9      | 1.15%   |
| OCZ                 | 5         | 6      | 1.15%   |
| Transcend           | 4         | 4      | 0.92%   |
| LITEONIT            | 4         | 4      | 0.92%   |
| LITEON              | 4         | 4      | 0.92%   |
| GOODRAM             | 4         | 7      | 0.92%   |
| Emtec               | 4         | 6      | 0.92%   |
| Unknown             | 4         | 5      | 0.92%   |
| X12                 | 3         | 3      | 0.69%   |
| Patriot             | 3         | 10     | 0.69%   |
| Netac               | 3         | 3      | 0.69%   |
| Mushkin             | 3         | 4      | 0.69%   |
| Hewlett-Packard     | 3         | 3      | 0.69%   |
| Corsair             | 3         | 5      | 0.69%   |
| TCSUNBOW            | 2         | 3      | 0.46%   |
| T-FORCE             | 2         | 2      | 0.46%   |
| Lexar               | 2         | 2      | 0.46%   |
| Intenso             | 2         | 3      | 0.46%   |
| FORESEE             | 2         | 2      | 0.46%   |
| Apple               | 2         | 2      | 0.46%   |
| WODPOSIT            | 1         | 2      | 0.23%   |
| WDC WDS             | 1         | 1      | 0.23%   |
| VisionTek           | 1         | 2      | 0.23%   |
| USB30               | 1         | 2      | 0.23%   |
| Unknown             | 1         | 1      | 0.23%   |
| TAMMUZ              | 1         | 2      | 0.23%   |
| SATAFIRM            | 1         | 1      | 0.23%   |
| Qumo                | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 530       | 837    | 39.91%  |
| HDD     | 373       | 682    | 28.09%  |
| SSD     | 361       | 581    | 27.18%  |
| Unknown | 36        | 39     | 2.71%   |
| MMC     | 28        | 31     | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 529       | 828    | 45.06%  |
| SATA | 529       | 1179   | 45.06%  |
| SAS  | 88        | 132    | 7.5%    |
| MMC  | 28        | 31     | 2.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 331       | 531    | 40.32%  |
| 0.51-1.0   | 281       | 409    | 34.23%  |
| 1.01-2.0   | 113       | 184    | 13.76%  |
| 3.01-4.0   | 41        | 61     | 4.99%   |
| 2.01-3.0   | 24        | 39     | 2.92%   |
| 4.01-10.0  | 24        | 30     | 2.92%   |
| 10.01-20.0 | 7         | 9      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 392       | 45.27%  |
| 1001-2000      | 158       | 18.24%  |
| 2001-3000      | 110       | 12.7%   |
| 501-1000       | 106       | 12.24%  |
| 251-500        | 35        | 4.04%   |
| Unknown        | 35        | 4.04%   |
| 1-20           | 22        | 2.54%   |
| 101-250        | 8         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 195       | 21.52%  |
| 251-500        | 150       | 16.56%  |
| 501-1000       | 141       | 15.56%  |
| 1001-2000      | 110       | 12.14%  |
| More than 3000 | 100       | 11.04%  |
| 51-100         | 85        | 9.38%   |
| 2001-3000      | 62        | 6.84%   |
| Unknown        | 35        | 3.86%   |
| 1-20           | 22        | 2.43%   |
| 21-50          | 5         | 0.55%   |
| 0              | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD6004FZWX-00BKVA0 6TB                                      | 2         | 2      | 2.11%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 2         | 2      | 2.11%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 2         | 2      | 2.11%   |
| Toshiba DT01ACA100 1TB                                          | 2         | 2      | 2.11%   |
| Toshiba DT01ACA050 500GB                                        | 2         | 2      | 2.11%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 2         | 2      | 2.11%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 2         | 2      | 2.11%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 2      | 2.11%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB       | 2         | 4      | 2.11%   |
| Intenso USB 3.0 device 1TB                                      | 2         | 2      | 2.11%   |
| HGST HTS725050A7E630 500GB                                      | 2         | 5      | 2.11%   |
| HGST HTS721010A9E630 1TB                                        | 2         | 2      | 2.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 1.05%   |
| WDC WD6400AAKS-65A7B0 640GB                                     | 1         | 1      | 1.05%   |
| WDC WD5000BEVT-60A0RT0 500GB                                    | 1         | 1      | 1.05%   |
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 1.05%   |
| WDC WD5000AAKX-003CA0 500GB                                     | 1         | 3      | 1.05%   |
| WDC WD5000AAKS-00E4A0 500GB                                     | 1         | 1      | 1.05%   |
| WDC WD40EZRZ-00WN9B0 4TB                                        | 1         | 1      | 1.05%   |
| WDC WD3200AAKS-75L9A0 320GB                                     | 1         | 1      | 1.05%   |
| WDC WD30EZRX-00DC0B0 3TB                                        | 1         | 1      | 1.05%   |
| WDC WD30EZRX-00D8PB0 3TB                                        | 1         | 1      | 1.05%   |
| WDC WD30EFRX-68EUZN0 3TB                                        | 1         | 2      | 1.05%   |
| WDC WD3000FYYZ-01UL1B0 3TB                                      | 1         | 2      | 1.05%   |
| WDC WD2500JD-98HBC0 250GB                                       | 1         | 1      | 1.05%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 1         | 1      | 1.05%   |
| WDC WD20EARX-00PASB0 2TB                                        | 1         | 1      | 1.05%   |
| WDC WD2002FAEX-007BA0 2TB                                       | 1         | 1      | 1.05%   |
| WDC WD15EADS-22P8B0 1TB                                         | 1         | 3      | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 1         | 1      | 1.05%   |
| WDC WD10EZRX-00L4HB0 1TB                                        | 1         | 1      | 1.05%   |
| WDC WD10EZEX-75WN4A1 1TB                                        | 1         | 1      | 1.05%   |
| WDC WD10EZEX-75WN4A0 1TB                                        | 1         | 1      | 1.05%   |
| WDC WD10EZEX-60ZF5A0 1TB                                        | 1         | 1      | 1.05%   |
| WDC WD10EALX-009BA0 1TB                                         | 1         | 1      | 1.05%   |
| WDC WD10EADS-22M2B0 1TB                                         | 1         | 1      | 1.05%   |
| WDC WD10EADS-00M2B0 1TB                                         | 1         | 1      | 1.05%   |
| WDC WD10EACS-07D6B1 1TB                                         | 1         | 1      | 1.05%   |
| Transcend TS1TSSD230S 1TB                                       | 1         | 1      | 1.05%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                            | 1         | 1      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 29        | 38     | 32.58%  |
| Seagate                   | 16        | 17     | 17.98%  |
| Samsung Electronics       | 9         | 24     | 10.11%  |
| Hitachi                   | 7         | 7      | 7.87%   |
| HGST                      | 5         | 11     | 5.62%   |
| Toshiba                   | 4         | 4      | 4.49%   |
| SanDisk                   | 3         | 3      | 3.37%   |
| SK hynix                  | 2         | 4      | 2.25%   |
| Realtek Semiconductor     | 2         | 4      | 2.25%   |
| Kingston                  | 2         | 2      | 2.25%   |
| Intenso                   | 2         | 2      | 2.25%   |
| Crucial                   | 2         | 2      | 2.25%   |
| Transcend                 | 1         | 1      | 1.12%   |
| OCZ                       | 1         | 1      | 1.12%   |
| Micron/Crucial Technology | 1         | 1      | 1.12%   |
| Hewlett-Packard           | 1         | 1      | 1.12%   |
| Apple                     | 1         | 1      | 1.12%   |
| A-DATA Technology         | 1         | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 28        | 37     | 44.44%  |
| Seagate | 16        | 17     | 25.4%   |
| Hitachi | 7         | 7      | 11.11%  |
| HGST    | 5         | 11     | 7.94%   |
| Toshiba | 4         | 4      | 6.35%   |
| Intenso | 2         | 2      | 3.17%   |
| Apple   | 1         | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 79     | 66.67%  |
| SSD  | 18        | 19     | 22.22%  |
| NVMe | 9         | 26     | 11.11%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 464       | 1072   | 47.54%  |
| Works    | 436       | 974    | 44.67%  |
| Malfunc  | 76        | 124    | 7.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 438       | 33.08%  |
| AMD                            | 266       | 20.09%  |
| Samsung Electronics            | 164       | 12.39%  |
| Sandisk                        | 107       | 8.08%   |
| Phison Electronics             | 53        | 4%      |
| Kingston Technology Company    | 51        | 3.85%   |
| SK hynix                       | 40        | 3.02%   |
| Micron/Crucial Technology      | 29        | 2.19%   |
| Silicon Motion                 | 24        | 1.81%   |
| Micron Technology              | 24        | 1.81%   |
| ASMedia Technology             | 24        | 1.81%   |
| Toshiba America Info Systems   | 14        | 1.06%   |
| ADATA Technology               | 14        | 1.06%   |
| MAXIO Technology (Hangzhou)    | 13        | 0.98%   |
| KIOXIA                         | 13        | 0.98%   |
| Realtek Semiconductor          | 10        | 0.76%   |
| Marvell Technology Group       | 10        | 0.76%   |
| Union Memory (Shenzhen)        | 5         | 0.38%   |
| Solid State Storage Technology | 3         | 0.23%   |
| JMicron Technology             | 3         | 0.23%   |
| Apple                          | 3         | 0.23%   |
| Solidigm                       | 2         | 0.15%   |
| Shenzhen Longsys Electronics   | 2         | 0.15%   |
| Seagate Technology             | 2         | 0.15%   |
| Broadcom / LSI                 | 2         | 0.15%   |
| Biwin Storage Technology       | 2         | 0.15%   |
| Yangtze Memory Technologies    | 1         | 0.08%   |
| Transcend                      | 1         | 0.08%   |
| Nvidia                         | 1         | 0.08%   |
| LSI Logic / Symbios Logic      | 1         | 0.08%   |
| Lenovo                         | 1         | 0.08%   |
| INNOGRIT                       | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 159       | 10.77%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 92        | 6.23%   |
| AMD 400 Series Chipset SATA Controller                                         | 45        | 3.05%   |
| AMD 500 Series Chipset SATA Controller                                         | 43        | 2.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 33        | 2.23%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 31        | 2.1%    |
| Intel Volume Management Device NVMe RAID Controller                            | 31        | 2.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 31        | 2.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 30        | 2.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 30        | 2.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 29        | 1.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 28        | 1.9%    |
| Phison E12 NVMe Controller                                                     | 22        | 1.49%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 22        | 1.49%   |
| AMD 600 Series Chipset SATA Controller                                         | 22        | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 1.35%   |
| Intel SSD 660P Series                                                          | 19        | 1.29%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 17        | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 16        | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 16        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15        | 1.02%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 15        | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 1.02%   |
| Phison E16 PCIe4 NVMe Controller                                               | 14        | 0.95%   |
| Intel SATA Controller [RAID Mode]                                              | 14        | 0.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 13        | 0.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 13        | 0.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 13        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 13        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 12        | 0.81%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 12        | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 12        | 0.81%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 11        | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 11        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11        | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 10        | 0.68%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 10        | 0.68%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 10        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 612       | 48.84%  |
| NVMe | 526       | 41.98%  |
| RAID | 83        | 6.62%   |
| IDE  | 31        | 2.47%   |
| SAS  | 1         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 492       | 58.36%  |
| AMD    | 351       | 41.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 1.78%   |
| AMD Ryzen 5 3600 6-Core Processor             | 14        | 1.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 1.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 11        | 1.3%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 1.3%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 11        | 1.3%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 1.18%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 10        | 1.18%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 10        | 1.18%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 0.95%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 8         | 0.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.71%   |
| Intel 12th Gen Core i5-12600K                 | 6         | 0.71%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 6         | 0.71%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 6         | 0.71%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 6         | 0.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 0.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.71%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 6         | 0.71%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.59%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 5         | 0.59%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.59%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 5         | 0.59%   |
| AMD Ryzen 9 7900X 12-Core Processor           | 5         | 0.59%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 5         | 0.59%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 5         | 0.59%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.59%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 5         | 0.59%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 5         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 162       | 19.22%  |
| Intel Core i5           | 131       | 15.54%  |
| AMD Ryzen 7             | 121       | 14.35%  |
| AMD Ryzen 5             | 114       | 13.52%  |
| Other                   | 96        | 11.39%  |
| AMD Ryzen 9             | 48        | 5.69%   |
| Intel Core i3           | 44        | 5.22%   |
| Intel Celeron           | 15        | 1.78%   |
| AMD Ryzen 3             | 13        | 1.54%   |
| Intel Xeon              | 12        | 1.42%   |
| AMD FX                  | 12        | 1.42%   |
| Intel Pentium           | 9         | 1.07%   |
| Intel Core i9           | 9         | 1.07%   |
| Intel Core 2 Duo        | 7         | 0.83%   |
| AMD Ryzen 7 PRO         | 6         | 0.71%   |
| AMD A8                  | 6         | 0.71%   |
| AMD A10                 | 5         | 0.59%   |
| AMD A6                  | 4         | 0.47%   |
| Intel Pentium Silver    | 3         | 0.36%   |
| Intel Pentium Dual-Core | 3         | 0.36%   |
| AMD Ryzen Threadripper  | 3         | 0.36%   |
| AMD A4                  | 3         | 0.36%   |
| AMD Phenom II X6        | 2         | 0.24%   |
| AMD Athlon              | 2         | 0.24%   |
| AMD A12                 | 2         | 0.24%   |
| Intel Core m3           | 1         | 0.12%   |
| Intel Core 2 Quad       | 1         | 0.12%   |
| Intel Core 2            | 1         | 0.12%   |
| Intel Core              | 1         | 0.12%   |
| AMD Turion              | 1         | 0.12%   |
| AMD Ryzen 5 PRO         | 1         | 0.12%   |
| AMD Phenom II X4        | 1         | 0.12%   |
| AMD Phenom II X2        | 1         | 0.12%   |
| AMD EPYC                | 1         | 0.12%   |
| AMD Athlon X4           | 1         | 0.12%   |
| AMD Athlon Dual Core    | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 257       | 30.49%  |
| 2      | 179       | 21.23%  |
| 8      | 166       | 19.69%  |
| 6      | 160       | 18.98%  |
| 12     | 28        | 3.32%   |
| 16     | 16        | 1.9%    |
| 14     | 14        | 1.66%   |
| 10     | 13        | 1.54%   |
| 24     | 4         | 0.47%   |
| 20     | 2         | 0.24%   |
| 48     | 1         | 0.12%   |
| 7      | 1         | 0.12%   |
| 3      | 1         | 0.12%   |
| 1      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 840       | 99.64%  |
| 2      | 3         | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 718       | 85.17%  |
| 1      | 125       | 14.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 843       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 574       | 66.51%  |
| 0x306a9    | 18        | 2.09%   |
| 0x0a50000c | 17        | 1.97%   |
| 0x206a7    | 14        | 1.62%   |
| 0x08108109 | 13        | 1.51%   |
| 0x306c3    | 11        | 1.27%   |
| 0x08701021 | 11        | 1.27%   |
| 0x806c1    | 10        | 1.16%   |
| 0x0800820d | 10        | 1.16%   |
| 0x906ea    | 9         | 1.04%   |
| 0x0a601203 | 9         | 1.04%   |
| 0x0a50000d | 9         | 1.04%   |
| 0x08600106 | 8         | 0.93%   |
| 0x906e9    | 7         | 0.81%   |
| 0x506e3    | 7         | 0.81%   |
| 0xa0652    | 6         | 0.7%    |
| 0x0a404102 | 6         | 0.7%    |
| 0x0a20120a | 6         | 0.7%    |
| 0x806ea    | 5         | 0.58%   |
| 0x806e9    | 5         | 0.58%   |
| 0x08608103 | 5         | 0.58%   |
| 0x08600103 | 4         | 0.46%   |
| 0xa0653    | 3         | 0.35%   |
| 0x806ec    | 3         | 0.35%   |
| 0x406e3    | 3         | 0.35%   |
| 0x40651    | 3         | 0.35%   |
| 0x0a704103 | 3         | 0.35%   |
| 0x0a50000b | 3         | 0.35%   |
| 0x0a201025 | 3         | 0.35%   |
| 0x0a201009 | 3         | 0.35%   |
| 0x08a00008 | 3         | 0.35%   |
| 0x08600104 | 3         | 0.35%   |
| 0x08108102 | 3         | 0.35%   |
| 0x08001137 | 3         | 0.35%   |
| 0x06006705 | 3         | 0.35%   |
| 0x906ed    | 2         | 0.23%   |
| 0x906a3    | 2         | 0.23%   |
| 0x90672    | 2         | 0.23%   |
| 0x106e5    | 2         | 0.23%   |
| 0x1067a    | 2         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 132       | 15.62%  |
| Unknown           | 108       | 12.78%  |
| Zen 3             | 93        | 11.01%  |
| Zen 2             | 76        | 8.99%   |
| Zen+              | 55        | 6.51%   |
| Haswell           | 53        | 6.27%   |
| IvyBridge         | 50        | 5.92%   |
| TigerLake         | 34        | 4.02%   |
| SandyBridge       | 33        | 3.91%   |
| CometLake         | 33        | 3.91%   |
| Skylake           | 32        | 3.79%   |
| Alderlake Hybrid  | 24        | 2.84%   |
| Zen               | 17        | 2.01%   |
| Broadwell         | 14        | 1.66%   |
| Piledriver        | 13        | 1.54%   |
| Penryn            | 11        | 1.3%    |
| Westmere          | 8         | 0.95%   |
| IceLake           | 8         | 0.95%   |
| Excavator         | 8         | 0.95%   |
| Goldmont plus     | 7         | 0.83%   |
| Steamroller       | 5         | 0.59%   |
| Puma              | 5         | 0.59%   |
| Nehalem           | 5         | 0.59%   |
| Silvermont        | 4         | 0.47%   |
| K10               | 4         | 0.47%   |
| Goldmont          | 4         | 0.47%   |
| Jaguar            | 2         | 0.24%   |
| Core              | 2         | 0.24%   |
| Meteorlake Hybrid | 1         | 0.12%   |
| K8 Hammer         | 1         | 0.12%   |
| K8 & K10 hybrid   | 1         | 0.12%   |
| K10 Llano         | 1         | 0.12%   |
| Bulldozer         | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 396       | 36.1%   |
| Nvidia | 362       | 33%     |
| AMD    | 339       | 30.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 36        | 3.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 33        | 2.92%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 31        | 2.74%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 30        | 2.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 28        | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 27        | 2.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 25        | 2.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 23        | 2.03%   |
| Intel HD Graphics 630                                                       | 23        | 2.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 23        | 2.03%   |
| Intel UHD Graphics 620                                                      | 21        | 1.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 18        | 1.59%   |
| AMD Rembrandt [Radeon 680M]                                                 | 18        | 1.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 18        | 1.59%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 16        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15        | 1.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 15        | 1.33%   |
| AMD Raphael                                                                 | 15        | 1.33%   |
| AMD Lucienne                                                                | 15        | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 14        | 1.24%   |
| Intel HD Graphics 620                                                       | 13        | 1.15%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 13        | 1.15%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 12        | 1.06%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 12        | 1.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 11        | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 10        | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 10        | 0.88%   |
| Intel HD Graphics 5500                                                      | 10        | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 10        | 0.88%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 10        | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 9         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 9         | 0.8%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 9         | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 8         | 0.71%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 8         | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8         | 0.71%   |
| Intel HD Graphics 530                                                       | 8         | 0.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 8         | 0.71%   |
| AMD Phoenix1                                                                | 8         | 0.71%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 8         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 239       | 28.12%  |
| 1 x Intel          | 212       | 24.94%  |
| Intel + Nvidia     | 149       | 17.53%  |
| 1 x Nvidia         | 140       | 16.47%  |
| AMD + Nvidia       | 66        | 7.76%   |
| 2 x AMD            | 19        | 2.24%   |
| Intel + AMD        | 17        | 2%      |
| 2 x Nvidia         | 4         | 0.47%   |
| 2 x Intel          | 2         | 0.24%   |
| Intel + 2 x Nvidia | 2         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 534       | 62.6%   |
| Proprietary | 306       | 35.87%  |
| Unknown     | 13        | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 490       | 56.84%  |
| 0.01-0.5   | 76        | 8.82%   |
| 7.01-8.0   | 75        | 8.7%    |
| 1.01-2.0   | 57        | 6.61%   |
| 8.01-16.0  | 56        | 6.5%    |
| 3.01-4.0   | 47        | 5.45%   |
| 5.01-6.0   | 30        | 3.48%   |
| 0.51-1.0   | 16        | 1.86%   |
| 16.01-24.0 | 11        | 1.28%   |
| 2.01-3.0   | 4         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 114       | 11.05%  |
| Samsung Electronics     | 108       | 10.47%  |
| BOE                     | 91        | 8.82%   |
| Chimei Innolux          | 80        | 7.75%   |
| LG Display              | 67        | 6.49%   |
| Dell                    | 58        | 5.62%   |
| Goldstar                | 54        | 5.23%   |
| Acer                    | 45        | 4.36%   |
| AOC                     | 38        | 3.68%   |
| Hewlett-Packard         | 32        | 3.1%    |
| BenQ                    | 24        | 2.33%   |
| Ancor Communications    | 23        | 2.23%   |
| Sharp                   | 21        | 2.03%   |
| PANDA                   | 20        | 1.94%   |
| Apple                   | 19        | 1.84%   |
| ASUSTek Computer        | 18        | 1.74%   |
| Philips                 | 17        | 1.65%   |
| Lenovo                  | 15        | 1.45%   |
| Unknown                 | 14        | 1.36%   |
| MSI                     | 13        | 1.26%   |
| ViewSonic               | 9         | 0.87%   |
| Gigabyte Technology     | 9         | 0.87%   |
| Sony                    | 8         | 0.78%   |
| Mi                      | 7         | 0.68%   |
| Iiyama                  | 7         | 0.68%   |
| Vizio                   | 6         | 0.58%   |
| NEC Computers           | 6         | 0.58%   |
| HKC                     | 6         | 0.58%   |
| Insignia                | 5         | 0.48%   |
| TMX                     | 4         | 0.39%   |
| InfoVision              | 4         | 0.39%   |
| Unknown                 | 4         | 0.39%   |
| Toshiba                 | 3         | 0.29%   |
| Sceptre Tech            | 3         | 0.29%   |
| Panasonic               | 3         | 0.29%   |
| LG Electronics          | 3         | 0.29%   |
| HUAWEI                  | 3         | 0.29%   |
| Eizo                    | 3         | 0.29%   |
| CSO                     | 3         | 0.29%   |
| Chi Mei Optoelectronics | 3         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 8         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.65%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.56%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 5         | 0.46%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 5         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.37%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                      | 4         | 0.37%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 4         | 0.37%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.37%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 4         | 0.37%   |
| Unknown                                                               | 4         | 0.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.28%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 3         | 0.28%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 3         | 0.28%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 3         | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 3         | 0.28%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 3         | 0.28%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 0.28%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3         | 0.28%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                      | 3         | 0.28%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 3         | 0.28%   |
| Acer XB271HU ACR0490 2560x1440 598x336mm 27.0-inch                    | 3         | 0.28%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 2         | 0.19%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 2         | 0.19%   |
| ViewSonic VX3258 SERIES VSCDE35 2560x1440 697x392mm 31.5-inch         | 2         | 0.19%   |
| TMX TL156MDMP31-0 TMX2005 3200x2000 336x210mm 15.6-inch               | 2         | 0.19%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 2         | 0.19%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 2         | 0.19%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 0.19%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 0.19%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 2         | 0.19%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 484       | 49.44%  |
| 1366x768 (WXGA)    | 94        | 9.6%    |
| 3840x2160 (4K)     | 92        | 9.4%    |
| 2560x1440 (QHD)    | 81        | 8.27%   |
| 1920x1200 (WUXGA)  | 24        | 2.45%   |
| 1680x1050 (WSXGA+) | 23        | 2.35%   |
| 1600x900 (HD+)     | 23        | 2.35%   |
| 3440x1440          | 22        | 2.25%   |
| 2560x1600          | 13        | 1.33%   |
| 1440x900 (WXGA+)   | 12        | 1.23%   |
| 2560x1080          | 11        | 1.12%   |
| 1280x1024 (SXGA)   | 11        | 1.12%   |
| Unknown            | 11        | 1.12%   |
| 2288x1287          | 9         | 0.92%   |
| 2880x1800          | 8         | 0.82%   |
| 3840x1080          | 7         | 0.72%   |
| 1280x800 (WXGA)    | 7         | 0.72%   |
| 3840x2400          | 3         | 0.31%   |
| 3840x1200          | 3         | 0.31%   |
| 2256x1504          | 3         | 0.31%   |
| 1920x540           | 3         | 0.31%   |
| 1360x768           | 3         | 0.31%   |
| 1280x720 (HD)      | 3         | 0.31%   |
| 7680x2160          | 2         | 0.2%    |
| 3200x2000          | 2         | 0.2%    |
| 3000x2000          | 2         | 0.2%    |
| 2880x1440          | 2         | 0.2%    |
| 2160x1440          | 2         | 0.2%    |
| 1600x1200          | 2         | 0.2%    |
| 9600x2160          | 1         | 0.1%    |
| 800x1280           | 1         | 0.1%    |
| 504x315            | 1         | 0.1%    |
| 480x1920           | 1         | 0.1%    |
| 4480x1440          | 1         | 0.1%    |
| 3840x1600          | 1         | 0.1%    |
| 3520x1080          | 1         | 0.1%    |
| 3360x1050          | 1         | 0.1%    |
| 3200x1800 (QHD+)   | 1         | 0.1%    |
| 2880x1920          | 1         | 0.1%    |
| 2736x1824          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 267       | 26.05%  |
| 27      | 109       | 10.63%  |
| 24      | 78        | 7.61%   |
| 14      | 65        | 6.34%   |
| 13      | 58        | 5.66%   |
| 23      | 57        | 5.56%   |
| 31      | 53        | 5.17%   |
| Unknown | 53        | 5.17%   |
| 17      | 46        | 4.49%   |
| 21      | 35        | 3.41%   |
| 34      | 26        | 2.54%   |
| 16      | 22        | 2.15%   |
| 19      | 17        | 1.66%   |
| 22      | 16        | 1.56%   |
| 18      | 14        | 1.37%   |
| 20      | 13        | 1.27%   |
| 72      | 11        | 1.07%   |
| 142     | 8         | 0.78%   |
| 40      | 6         | 0.59%   |
| 26      | 6         | 0.59%   |
| 25      | 6         | 0.59%   |
| 84      | 5         | 0.49%   |
| 54      | 5         | 0.49%   |
| 43      | 5         | 0.49%   |
| 28      | 4         | 0.39%   |
| 12      | 4         | 0.39%   |
| 49      | 3         | 0.29%   |
| 32      | 3         | 0.29%   |
| 29      | 3         | 0.29%   |
| 11      | 3         | 0.29%   |
| 74      | 2         | 0.2%    |
| 65      | 2         | 0.2%    |
| 48      | 2         | 0.2%    |
| 35      | 2         | 0.2%    |
| 33      | 2         | 0.2%    |
| 7       | 2         | 0.2%    |
| 85      | 1         | 0.1%    |
| 64      | 1         | 0.1%    |
| 58      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 371       | 37.1%   |
| 501-600        | 224       | 22.4%   |
| 401-500        | 84        | 8.4%    |
| 601-700        | 71        | 7.1%    |
| 351-400        | 59        | 5.9%    |
| Unknown        | 53        | 5.3%    |
| 201-300        | 42        | 4.2%    |
| 701-800        | 32        | 3.2%    |
| 1001-1500      | 21        | 2.1%    |
| 1501-2000      | 19        | 1.9%    |
| 801-900        | 11        | 1.1%    |
| More than 2000 | 8         | 0.8%    |
| 901-1000       | 3         | 0.3%    |
| 101-200        | 1         | 0.1%    |
| 1-100          | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 687       | 75.74%  |
| 16/10   | 98        | 10.8%   |
| Unknown | 41        | 4.52%   |
| 21/9    | 32        | 3.53%   |
| 5/4     | 12        | 1.32%   |
| 3/2     | 12        | 1.32%   |
| 1.00    | 9         | 0.99%   |
| 4/3     | 5         | 0.55%   |
| 32/9    | 5         | 0.55%   |
| 3.20    | 2         | 0.22%   |
| 2.00    | 2         | 0.22%   |
| 0.62    | 1         | 0.11%   |
| 0.25    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 269       | 26.74%  |
| 201-250        | 141       | 14.02%  |
| 301-350        | 114       | 11.33%  |
| 81-90          | 100       | 9.94%   |
| 351-500        | 89        | 8.85%   |
| Unknown        | 53        | 5.27%   |
| 121-130        | 44        | 4.37%   |
| 151-200        | 43        | 4.27%   |
| More than 1000 | 38        | 3.78%   |
| 251-300        | 30        | 2.98%   |
| 71-80          | 21        | 2.09%   |
| 501-1000       | 21        | 2.09%   |
| 111-120        | 16        | 1.59%   |
| 141-150        | 14        | 1.39%   |
| 61-70          | 4         | 0.4%    |
| 51-60          | 3         | 0.3%    |
| 91-100         | 3         | 0.3%    |
| 1-40           | 2         | 0.2%    |
| 131-140        | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 299       | 31.02%  |
| 51-100        | 298       | 30.91%  |
| 101-120       | 186       | 19.29%  |
| 161-240       | 69        | 7.16%   |
| Unknown       | 53        | 5.5%    |
| 1-50          | 32        | 3.32%   |
| More than 240 | 27        | 2.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 625       | 72.42%  |
| 2     | 200       | 23.17%  |
| 3     | 30        | 3.48%   |
| 0     | 5         | 0.58%   |
| 4     | 3         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 519       | 38.27%  |
| Intel                             | 452       | 33.33%  |
| Qualcomm Atheros                  | 96        | 7.08%   |
| MediaTek                          | 70        | 5.16%   |
| Broadcom                          | 50        | 3.69%   |
| TP-Link                           | 18        | 1.33%   |
| Ralink Technology                 | 14        | 1.03%   |
| Samsung Electronics               | 13        | 0.96%   |
| Microsoft                         | 12        | 0.88%   |
| NetGear                           | 10        | 0.74%   |
| ASIX Electronics                  | 10        | 0.74%   |
| DisplayLink                       | 9         | 0.66%   |
| Xiaomi                            | 7         | 0.52%   |
| Sierra Wireless                   | 6         | 0.44%   |
| Aquantia                          | 6         | 0.44%   |
| Qualcomm                          | 5         | 0.37%   |
| Ralink                            | 4         | 0.29%   |
| Linksys                           | 4         | 0.29%   |
| Dell                              | 4         | 0.29%   |
| Broadcom Limited                  | 4         | 0.29%   |
| ASUSTek Computer                  | 3         | 0.22%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.15%   |
| Wacom                             | 2         | 0.15%   |
| Qualcomm Atheros Communications   | 2         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.15%   |
| Marvell Technology Group          | 2         | 0.15%   |
| Hewlett-Packard                   | 2         | 0.15%   |
| Google                            | 2         | 0.15%   |
| Ericsson Business Mobile Networks | 2         | 0.15%   |
| D-Link                            | 2         | 0.15%   |
| AVM                               | 2         | 0.15%   |
| Unknown                           | 2         | 0.15%   |
| ZyXEL Communications              | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Sitecom Europe                    | 1         | 0.07%   |
| Shenzhen Goodix Technology        | 1         | 0.07%   |
| Quectel Wireless Solutions        | 1         | 0.07%   |
| Qualcomm Technologies             | 1         | 0.07%   |
| QinHeng Electronics               | 1         | 0.07%   |
| Nvidia                            | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 330       | 20.95%  |
| Realtek RTL8125 2.5GbE Controller                                      | 71        | 4.51%   |
| Intel Wi-Fi 6 AX200                                                    | 67        | 4.25%   |
| Intel I211 Gigabit Network Connection                                  | 34        | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 32        | 2.03%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 28        | 1.78%   |
| Intel Ethernet Controller I225-V                                       | 28        | 1.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 27        | 1.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 27        | 1.71%   |
| Intel Wi-Fi 6 AX201                                                    | 25        | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 24        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 24        | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 22        | 1.4%    |
| Intel Wireless 8265 / 8275                                             | 21        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 20        | 1.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 20        | 1.27%   |
| Intel Wireless 7265                                                    | 20        | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 16        | 1.02%   |
| Intel Ethernet Connection I217-LM                                      | 15        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 15        | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 0.89%   |
| Intel Wireless 7260                                                    | 14        | 0.89%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 14        | 0.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 12        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 0.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 11        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 10        | 0.63%   |
| Intel Wireless 3165                                                    | 10        | 0.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 10        | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 9         | 0.57%   |
| Realtek Killer E2600 GbE Controller                                    | 9         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 9         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 8         | 0.51%   |
| Intel Wireless 8260                                                    | 8         | 0.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 8         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 363       | 48.79%  |
| Realtek Semiconductor           | 123       | 16.53%  |
| Qualcomm Atheros                | 74        | 9.95%   |
| MediaTek                        | 57        | 7.66%   |
| Broadcom                        | 38        | 5.11%   |
| TP-Link                         | 17        | 2.28%   |
| Ralink Technology               | 14        | 1.88%   |
| NetGear                         | 10        | 1.34%   |
| Microsoft                       | 10        | 1.34%   |
| Sierra Wireless                 | 6         | 0.81%   |
| Ralink                          | 4         | 0.54%   |
| Linksys                         | 4         | 0.54%   |
| Broadcom Limited                | 3         | 0.4%    |
| ASUSTek Computer                | 3         | 0.4%    |
| Wacom                           | 2         | 0.27%   |
| Qualcomm Atheros Communications | 2         | 0.27%   |
| Qualcomm                        | 2         | 0.27%   |
| Dell                            | 2         | 0.27%   |
| D-Link                          | 2         | 0.27%   |
| AVM                             | 2         | 0.27%   |
| ZyXEL Communications            | 1         | 0.13%   |
| Sitecom Europe                  | 1         | 0.13%   |
| Qualcomm Technologies           | 1         | 0.13%   |
| Marvell Technology Group        | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| Accton Technology               | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 67        | 8.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 32        | 4.27%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 28        | 3.74%   |
| Intel Wi-Fi 6 AX201                                           | 25        | 3.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 24        | 3.2%    |
| Intel Cannon Lake PCH CNVi WiFi                               | 24        | 3.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 23        | 3.07%   |
| Intel Comet Lake PCH CNVi WiFi                                | 22        | 2.94%   |
| Intel Wireless 8265 / 8275                                    | 21        | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 20        | 2.67%   |
| Intel Wireless 7265                                           | 20        | 2.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 16        | 2.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 15        | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 14        | 1.87%   |
| Intel Wireless 7260                                           | 14        | 1.87%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 14        | 1.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 12        | 1.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                | 12        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 11        | 1.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 11        | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 10        | 1.34%   |
| Intel Wireless 3165                                           | 10        | 1.34%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 10        | 1.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 9         | 1.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                         | 9         | 1.2%    |
| Intel Wireless 8260                                           | 8         | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 8         | 1.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 7         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 7         | 0.93%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 7         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 7         | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 6         | 0.8%    |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 6         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 5         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 5         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 0.67%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter             | 5         | 0.67%   |
| Intel Wireless 3160                                           | 5         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 0.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 4         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 466       | 59.59%  |
| Intel                         | 185       | 23.66%  |
| Qualcomm Atheros              | 34        | 4.35%   |
| Broadcom                      | 25        | 3.2%    |
| MediaTek                      | 14        | 1.79%   |
| ASIX Electronics              | 10        | 1.28%   |
| DisplayLink                   | 9         | 1.15%   |
| Xiaomi                        | 7         | 0.9%    |
| Aquantia                      | 6         | 0.77%   |
| Samsung Electronics           | 5         | 0.64%   |
| Qualcomm                      | 3         | 0.38%   |
| Microsoft                     | 2         | 0.26%   |
| Unknown                       | 2         | 0.26%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.13%   |
| TP-Link                       | 1         | 0.13%   |
| QinHeng Electronics           | 1         | 0.13%   |
| OnePlus Technology (Shenzhen) | 1         | 0.13%   |
| Nvidia                        | 1         | 0.13%   |
| Motorola PCS                  | 1         | 0.13%   |
| Marvell Technology Group      | 1         | 0.13%   |
| Lenovo                        | 1         | 0.13%   |
| ICS Advent                    | 1         | 0.13%   |
| Hewlett-Packard               | 1         | 0.13%   |
| Google                        | 1         | 0.13%   |
| Broadcom Limited              | 1         | 0.13%   |
| Belkin Components             | 1         | 0.13%   |
| Alteon Networks               | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 330       | 41.04%  |
| Realtek RTL8125 2.5GbE Controller                                               | 71        | 8.83%   |
| Intel I211 Gigabit Network Connection                                           | 34        | 4.23%   |
| Intel Ethernet Controller I225-V                                                | 28        | 3.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 27        | 3.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 27        | 3.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 24        | 2.99%   |
| Intel Ethernet Connection I217-LM                                               | 15        | 1.87%   |
| Realtek Killer E2600 GbE Controller                                             | 9         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                            | 9         | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                               | 9         | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 9         | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 8         | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 7         | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                            | 7         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                           | 7         | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 6         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 5         | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 5         | 0.62%   |
| Realtek USB 10/100/1G/2.5G LAN                                                  | 5         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                       | 5         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                                        | 5         | 0.62%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                               | 5         | 0.62%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 4         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 4         | 0.5%    |
| MediaTek Infinix SMART 5                                                        | 4         | 0.5%    |
| Intel Ethernet Connection I218-LM                                               | 4         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                           | 4         | 0.5%    |
| Intel 82579V Gigabit Network Connection                                         | 4         | 0.5%    |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 4         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 3         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                      | 3         | 0.37%   |
| Intel Ethernet Connection I219-LM                                               | 3         | 0.37%   |
| Intel Ethernet Connection I217-V                                                | 3         | 0.37%   |
| Intel Ethernet Connection (7) I219-LM                                           | 3         | 0.37%   |
| Intel Ethernet Connection (3) I218-LM                                           | 3         | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                                           | 3         | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                            | 3         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                            | 2         | 0.25%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 2         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 707       | 50.18%  |
| WiFi     | 681       | 48.33%  |
| Modem    | 18        | 1.28%   |
| Unknown  | 3         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 519       | 59.18%  |
| Ethernet | 357       | 40.71%  |
| Modem    | 1         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 467       | 55.14%  |
| 1     | 340       | 40.14%  |
| 3     | 28        | 3.31%   |
| 0     | 9         | 1.06%   |
| 6     | 2         | 0.24%   |
| 4     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 592       | 69.32%  |
| Yes  | 262       | 30.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 327       | 50.23%  |
| Realtek Semiconductor           | 83        | 12.75%  |
| Qualcomm Atheros Communications | 41        | 6.3%    |
| IMC Networks                    | 38        | 5.84%   |
| Cambridge Silicon Radio         | 29        | 4.45%   |
| Foxconn / Hon Hai               | 23        | 3.53%   |
| MediaTek                        | 20        | 3.07%   |
| Broadcom                        | 17        | 2.61%   |
| Apple                           | 17        | 2.61%   |
| Lite-On Technology              | 16        | 2.46%   |
| ASUSTek Computer                | 16        | 2.46%   |
| Realtek                         | 4         | 0.61%   |
| Dell                            | 4         | 0.61%   |
| TP-Link                         | 2         | 0.31%   |
| Toshiba                         | 2         | 0.31%   |
| Hewlett-Packard                 | 2         | 0.31%   |
| Unknown                         | 2         | 0.31%   |
| USI                             | 1         | 0.15%   |
| Opticis                         | 1         | 0.15%   |
| Marvell Semiconductor           | 1         | 0.15%   |
| Edimax Technology               | 1         | 0.15%   |
| Dynex                           | 1         | 0.15%   |
| Belkin Components               | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |
| AboCom Systems                  | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 71        | 10.91%  |
| Intel AX201 Bluetooth                               | 71        | 10.91%  |
| Intel AX200 Bluetooth                               | 62        | 9.52%   |
| Realtek Bluetooth Radio                             | 50        | 7.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 38        | 5.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29        | 4.45%   |
| Intel AX210 Bluetooth                               | 27        | 4.15%   |
| IMC Networks Wireless_Device                        | 23        | 3.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 20        | 3.07%   |
| MediaTek Wireless_Device                            | 19        | 2.92%   |
| Intel AX211 Bluetooth                               | 19        | 2.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 2.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 2.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 2.15%   |
| IMC Networks Bluetooth Radio                        | 12        | 1.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 1.69%   |
| Apple Bluetooth USB Host Controller                 | 11        | 1.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 1.23%   |
| Realtek 802.11ac WLAN Adapter                       | 7         | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.08%   |
| ASUS ASUS USB-BT500                                 | 6         | 0.92%   |
| Lite-On Bluetooth Device                            | 5         | 0.77%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.77%   |
| Realtek Bluetooth Radio                             | 4         | 0.61%   |
| Lite-On Wireless_Device                             | 4         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.61%   |
| Apple Bluetooth Host Controller                     | 4         | 0.61%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.46%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.46%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.46%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.46%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.46%   |
| ASUS Bluetooth Radio                                | 3         | 0.46%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2         | 0.31%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.31%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 495       | 35.97%  |
| AMD                         | 383       | 27.83%  |
| Nvidia                      | 278       | 20.2%   |
| C-Media Electronics         | 29        | 2.11%   |
| Logitech                    | 23        | 1.67%   |
| JMTek                       | 12        | 0.87%   |
| Kingston Technology         | 10        | 0.73%   |
| Texas Instruments           | 7         | 0.51%   |
| Sony                        | 7         | 0.51%   |
| Generalplus Technology      | 7         | 0.51%   |
| Creative Labs               | 7         | 0.51%   |
| Realtek Semiconductor       | 6         | 0.44%   |
| ASUSTek Computer            | 6         | 0.44%   |
| Micro Star International    | 5         | 0.36%   |
| Focusrite-Novation          | 5         | 0.36%   |
| Creative Technology         | 5         | 0.36%   |
| Corsair                     | 5         | 0.36%   |
| Blue Microphones            | 5         | 0.36%   |
| RODE Microphones            | 4         | 0.29%   |
| Razer USA                   | 4         | 0.29%   |
| XMOS                        | 3         | 0.22%   |
| Trust                       | 3         | 0.22%   |
| SteelSeries ApS             | 3         | 0.22%   |
| Samson Technologies         | 3         | 0.22%   |
| Hewlett-Packard             | 3         | 0.22%   |
| GN Netcom                   | 3         | 0.22%   |
| Yamaha                      | 2         | 0.15%   |
| Turtle Beach                | 2         | 0.15%   |
| Sennheiser Communications   | 2         | 0.15%   |
| Samsung Electronics         | 2         | 0.15%   |
| ROCCAT                      | 2         | 0.15%   |
| M-Audio                     | 2         | 0.15%   |
| Jieli Technology            | 2         | 0.15%   |
| Huawei Technologies         | 2         | 0.15%   |
| Harman International        | 2         | 0.15%   |
| FiiO Electronics Technology | 2         | 0.15%   |
| FIFINE Microphones          | 2         | 0.15%   |
| Digidesign                  | 2         | 0.15%   |
| Astro Gaming                | 2         | 0.15%   |
| Apple                       | 2         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 180       | 10.47%  |
| AMD Starship/Matisse HD Audio Controller                                   | 85        | 4.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 77        | 4.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 50        | 2.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 47        | 2.73%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 45        | 2.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 44        | 2.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 42        | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 35        | 2.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 34        | 1.98%   |
| Nvidia GA104 High Definition Audio Controller                              | 32        | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 1.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 31        | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 30        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 28        | 1.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 28        | 1.63%   |
| Intel Comet Lake PCH cAVS                                                  | 25        | 1.45%   |
| Nvidia GA106 High Definition Audio Controller                              | 22        | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                              | 21        | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 1.22%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 21        | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                              | 20        | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 20        | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 18        | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                              | 17        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 16        | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 0.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 0.87%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 0.87%   |
| AMD Navi 10 HDMI Audio                                                     | 15        | 0.87%   |
| AMD FCH Azalia Controller                                                  | 15        | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 14        | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 13        | 0.76%   |
| Nvidia GA107 High Definition Audio Controller                              | 13        | 0.76%   |
| Intel Broadwell-U Audio Controller                                         | 12        | 0.7%    |
| Intel Alder Lake-S HD Audio Controller                                     | 12        | 0.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 122       | 19.87%  |
| SK hynix                                | 98        | 15.96%  |
| Micron Technology                       | 63        | 10.26%  |
| Corsair                                 | 57        | 9.28%   |
| Kingston                                | 54        | 8.79%   |
| Crucial                                 | 49        | 7.98%   |
| G.Skill                                 | 46        | 7.49%   |
| Unknown                                 | 20        | 3.26%   |
| A-DATA Technology                       | 15        | 2.44%   |
| Ramaxel Technology                      | 12        | 1.95%   |
| Patriot                                 | 10        | 1.63%   |
| Team                                    | 9         | 1.47%   |
| Unknown                                 | 7         | 1.14%   |
| Unknown (ABCD)                          | 5         | 0.81%   |
| Nanya Technology                        | 5         | 0.81%   |
| Patriot Memory (PDP Systems)            | 4         | 0.65%   |
| Elpida                                  | 4         | 0.65%   |
| Timetec                                 | 3         | 0.49%   |
| Smart                                   | 3         | 0.49%   |
| Hewlett-Packard                         | 3         | 0.49%   |
| Transcend                               | 2         | 0.33%   |
| ASint Technology                        | 2         | 0.33%   |
| Apacer                                  | 2         | 0.33%   |
| Wilk                                    | 1         | 0.16%   |
| Unknown (0x0CAB)                        | 1         | 0.16%   |
| Toshiba                                 | 1         | 0.16%   |
| Smart Brazil                            | 1         | 0.16%   |
| Silicon Power Computer & Communications | 1         | 0.16%   |
| Sesame                                  | 1         | 0.16%   |
| PNY                                     | 1         | 0.16%   |
| Patriot Memory                          | 1         | 0.16%   |
| Lexar Co Limited                        | 1         | 0.16%   |
| KLEVV                                   | 1         | 0.16%   |
| Kimtigo                                 | 1         | 0.16%   |
| Huanan                                  | 1         | 0.16%   |
| GOODRAM                                 | 1         | 0.16%   |
| Essencore                               | 1         | 0.16%   |
| CSX                                     | 1         | 0.16%   |
| Avant                                   | 1         | 0.16%   |
| AMD                                     | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.07%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.07%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 7         | 1.07%   |
| Unknown                                                          | 7         | 1.07%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.91%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 0.91%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 6         | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 5         | 0.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.76%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.61%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 4         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 4         | 0.61%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.61%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s              | 4         | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 3         | 0.46%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.46%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 3         | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.46%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s                       | 3         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.46%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.46%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.46%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s         | 3         | 0.46%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 3         | 0.46%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 3         | 0.46%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 2         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 329       | 62.08%  |
| DDR3    | 102       | 19.25%  |
| DDR5    | 46        | 8.68%   |
| LPDDR4  | 19        | 3.58%   |
| LPDDR5  | 12        | 2.26%   |
| LPDDR3  | 8         | 1.51%   |
| DDR2    | 6         | 1.13%   |
| Unknown | 5         | 0.94%   |
| DRAM    | 2         | 0.38%   |
| SDRAM   | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 301       | 56.37%  |
| DIMM         | 195       | 36.52%  |
| Row Of Chips | 35        | 6.55%   |
| FB-DIMM      | 1         | 0.19%   |
| Chip         | 1         | 0.19%   |
| Unknown      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 274       | 47.08%  |
| 16384 | 138       | 23.71%  |
| 4096  | 113       | 19.42%  |
| 32768 | 41        | 7.04%   |
| 2048  | 15        | 2.58%   |
| 1024  | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 129       | 22.16%  |
| 2667  | 78        | 13.4%   |
| 1600  | 77        | 13.23%  |
| 3600  | 48        | 8.25%   |
| 2400  | 41        | 7.04%   |
| 4800  | 25        | 4.3%    |
| 2133  | 18        | 3.09%   |
| 1333  | 14        | 2.41%   |
| 6400  | 11        | 1.89%   |
| 5600  | 9         | 1.55%   |
| 3666  | 8         | 1.37%   |
| 2933  | 8         | 1.37%   |
| 1334  | 8         | 1.37%   |
| 4267  | 7         | 1.2%    |
| 4266  | 7         | 1.2%    |
| 6000  | 6         | 1.03%   |
| 3266  | 6         | 1.03%   |
| 3000  | 6         | 1.03%   |
| 3733  | 5         | 0.86%   |
| 3400  | 5         | 0.86%   |
| 2666  | 5         | 0.86%   |
| 3800  | 4         | 0.69%   |
| 1867  | 4         | 0.69%   |
| 1866  | 4         | 0.69%   |
| 1800  | 4         | 0.69%   |
| 800   | 4         | 0.69%   |
| 4000  | 3         | 0.52%   |
| 667   | 3         | 0.52%   |
| 8400  | 2         | 0.34%   |
| 7500  | 2         | 0.34%   |
| 5200  | 2         | 0.34%   |
| 4133  | 2         | 0.34%   |
| 3866  | 2         | 0.34%   |
| 3534  | 2         | 0.34%   |
| 3466  | 2         | 0.34%   |
| 2800  | 2         | 0.34%   |
| 1067  | 2         | 0.34%   |
| 1066  | 2         | 0.34%   |
| 7467  | 1         | 0.17%   |
| 5808  | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 44.44%  |
| Brother Industries  | 4         | 22.22%  |
| Samsung Electronics | 2         | 11.11%  |
| Dymo-CoStar         | 2         | 11.11%  |
| Kyocera             | 1         | 5.56%   |
| Fuji Xerox          | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450      | 2         | 11.11%  |
| Brother HL-5370DW series         | 2         | 11.11%  |
| Samsung M337x 387x 407x Series   | 1         | 5.56%   |
| Samsung M267x 287x Series        | 1         | 5.56%   |
| Kyocera FS-1030D printer         | 1         | 5.56%   |
| HP Smart Tank 530 series         | 1         | 5.56%   |
| HP OfficeJet Pro 8020 series     | 1         | 5.56%   |
| HP LaserJet 200 colorMFP M275nw  | 1         | 5.56%   |
| HP DeskJet Plus 4100 series      | 1         | 5.56%   |
| HP DeskJet 4100 series           | 1         | 5.56%   |
| HP Deskjet 3520 series           | 1         | 5.56%   |
| HP Deskjet 2050 J510             | 1         | 5.56%   |
| HP Color LaserJet CP1215         | 1         | 5.56%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 5.56%   |
| Brother MFC Composite Device     | 1         | 5.56%   |
| Brother HL-L2395DW series        | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 94        | 18.18%  |
| IMC Networks                           | 64        | 12.38%  |
| Logitech                               | 41        | 7.93%   |
| Quanta                                 | 37        | 7.16%   |
| Microdia                               | 35        | 6.77%   |
| Realtek Semiconductor                  | 32        | 6.19%   |
| Bison Electronics                      | 30        | 5.8%    |
| Sunplus Innovation Technology          | 28        | 5.42%   |
| Luxvisions Innotech Limited            | 19        | 3.68%   |
| Apple                                  | 18        | 3.48%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 2.9%    |
| Syntek                                 | 12        | 2.32%   |
| Microsoft                              | 11        | 2.13%   |
| Suyin                                  | 8         | 1.55%   |
| Sonix Technology                       | 7         | 1.35%   |
| Lite-On Technology                     | 7         | 1.35%   |
| Silicon Motion                         | 5         | 0.97%   |
| SunplusIT                              | 4         | 0.77%   |
| ShineTech                              | 4         | 0.77%   |
| Generalplus Technology                 | 4         | 0.77%   |
| Acer                                   | 4         | 0.77%   |
| Samsung Electronics                    | 3         | 0.58%   |
| Jieli Technology                       | 3         | 0.58%   |
| Creative Technology                    | 3         | 0.58%   |
| Alcor Micro                            | 3         | 0.58%   |
| Primax Electronics                     | 2         | 0.39%   |
| MacroSilicon                           | 2         | 0.39%   |
| Lenovo                                 | 2         | 0.39%   |
| Z-Star Microelectronics                | 1         | 0.19%   |
| WaveRider Communications               | 1         | 0.19%   |
| Valve Software                         | 1         | 0.19%   |
| Trust                                  | 1         | 0.19%   |
| Tobii Technology AB                    | 1         | 0.19%   |
| Shine-optics                           | 1         | 0.19%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.19%   |
| Razer USA                              | 1         | 0.19%   |
| OmniVision Technologies                | 1         | 0.19%   |
| Nexight                                | 1         | 0.19%   |
| KYE Systems (Mouse Systems)            | 1         | 0.19%   |
| Intel                                  | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 31        | 5.94%   |
| IMC Networks Integrated Camera                       | 21        | 4.02%   |
| Microdia Integrated_Webcam_HD                        | 18        | 3.45%   |
| Chicony Integrated Camera                            | 17        | 3.26%   |
| Chicony HD Webcam                                    | 11        | 2.11%   |
| Syntek Integrated Camera                             | 10        | 1.92%   |
| Logitech Webcam C270                                 | 10        | 1.92%   |
| Sunplus Integrated_Webcam_HD                         | 9         | 1.72%   |
| Bison Integrated Camera                              | 9         | 1.72%   |
| Realtek Integrated_Webcam_HD                         | 8         | 1.53%   |
| Quanta HD User Facing                                | 8         | 1.53%   |
| Bison HD Webcam                                      | 8         | 1.53%   |
| Apple FaceTime HD Camera                             | 8         | 1.53%   |
| Logitech HD Pro Webcam C920                          | 7         | 1.34%   |
| Chicony HP Wide Vision HD Camera                     | 7         | 1.34%   |
| Chicony HD User Facing                               | 7         | 1.34%   |
| Sonix USB2.0 HD UVC WebCam                           | 6         | 1.15%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 6         | 1.15%   |
| Quanta HP Wide Vision HD Camera                      | 5         | 0.96%   |
| Luxvisions Innotech Limited Integrated Camera        | 5         | 0.96%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.96%   |
| Logitech C922 Pro Stream Webcam                      | 5         | 0.96%   |
| Logitech BRIO Ultra HD Webcam                        | 5         | 0.96%   |
| Chicony EasyCamera                                   | 5         | 0.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 5         | 0.96%   |
| ShineTech USB2.0 HD UVC WebCam                       | 4         | 0.77%   |
| Quanta USB2.0 HD UVC WebCam                          | 4         | 0.77%   |
| Lite-On HP Wide Vision HD Camera                     | 4         | 0.77%   |
| Generalplus GENERAL WEBCAM                           | 4         | 0.77%   |
| Chicony Integrated HD WebCam                         | 4         | 0.77%   |
| Chicony Chicony USB2.0 Camera                        | 4         | 0.77%   |
| Samsung Galaxy series, misc. (MTP mode)              | 3         | 0.57%   |
| Quanta HP TrueVision HD Camera                       | 3         | 0.57%   |
| Quanta ACER HD User Facing                           | 3         | 0.57%   |
| Microsoft LifeCam HD-3000                            | 3         | 0.57%   |
| Microdia Streaming Camera W8GS                       | 3         | 0.57%   |
| Logitech Webcam C930e                                | 3         | 0.57%   |
| Jieli USB PHY 2.0                                    | 3         | 0.57%   |
| IMC Networks HD Camera                               | 3         | 0.57%   |
| Chicony USB 2.0 Camera                               | 3         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 22        | 26.51%  |
| Synaptics                  | 22        | 26.51%  |
| Shenzhen Goodix Technology | 13        | 15.66%  |
| Elan Microelectronics      | 12        | 14.46%  |
| LighTuning Technology      | 6         | 7.23%   |
| AuthenTec                  | 5         | 6.02%   |
| Focal-systems.Corp         | 2         | 2.41%   |
| Samsung Electronics        | 1         | 1.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                           | 7         | 8.43%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 7.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 7.23%   |
| Elan ELAN:Fingerprint                                                      | 5         | 6.02%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 4.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 4.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 4.82%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 3.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.61%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.61%   |
| Synaptics UWP WBDI                                                         | 3         | 3.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.41%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.41%   |
| Synaptics WBDI Device                                                      | 2         | 2.41%   |
| Synaptics WBDI                                                             | 2         | 2.41%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 2.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 2.41%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 2.41%   |
| AuthenTec AES2810                                                          | 2         | 2.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.2%    |
| Validity Sensors VFS491                                                    | 1         | 1.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.2%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.2%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.2%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.2%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 1.2%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.2%    |
| Synaptics UWP WBDI Device                                                  | 1         | 1.2%    |
| Synaptics  WBDI                                                            | 1         | 1.2%    |
| Synaptics Fingerprint scanner                                              | 1         | 1.2%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.2%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.2%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.2%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.2%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 16        | 48.48%  |
| Alcor Micro           | 9         | 27.27%  |
| Upek                  | 3         | 9.09%   |
| Lenovo                | 2         | 6.06%   |
| SCM Microsystems      | 1         | 3.03%   |
| O2 Micro              | 1         | 3.03%   |
| Advanced Card Systems | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 27.27%  |
| Broadcom 5880                                                                | 6         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 15.15%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 12.12%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.06%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 3.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.03%   |
| Broadcom 58200                                                               | 1         | 3.03%   |
| Advanced Card Systems ACR122U                                                | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 410       | 47.4%   |
| 0     | 302       | 34.91%  |
| 2     | 126       | 14.57%  |
| 3     | 26        | 3.01%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 472       | 63.87%  |
| Fingerprint reader       | 82        | 11.1%   |
| Graphics card            | 48        | 6.5%    |
| Net/wireless             | 43        | 5.82%   |
| Chipcard                 | 32        | 4.33%   |
| Multimedia controller    | 21        | 2.84%   |
| Camera                   | 12        | 1.62%   |
| Net/ethernet             | 10        | 1.35%   |
| Unassigned class         | 5         | 0.68%   |
| Storage                  | 4         | 0.54%   |
| Network                  | 3         | 0.41%   |
| Sound                    | 2         | 0.27%   |
| Bluetooth                | 2         | 0.27%   |
| Wireless                 | 1         | 0.14%   |
| Storage/raid             | 1         | 0.14%   |
| Modem                    | 1         | 0.14%   |

