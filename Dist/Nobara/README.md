Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 1772

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| BESSTAR Te... | HM80                        | Desktop     | [84decd497d](https://linux-hardware.org/?probe=84decd497d) | Jan 06, 2025 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [2183eb76b7](https://linux-hardware.org/?probe=2183eb76b7) | Jan 06, 2025 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [dbc98c4f9d](https://linux-hardware.org/?probe=dbc98c4f9d) | Jan 06, 2025 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [ad5192d23c](https://linux-hardware.org/?probe=ad5192d23c) | Jan 06, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f2de07e3ef](https://linux-hardware.org/?probe=f2de07e3ef) | Jan 06, 2025 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [f8371d3425](https://linux-hardware.org/?probe=f8371d3425) | Jan 05, 2025 |
| ASRock        | B450 Pro4                   | Desktop     | [f0fac8b3f2](https://linux-hardware.org/?probe=f0fac8b3f2) | Jan 05, 2025 |
| Dell          | Latitude E5470              | Notebook    | [57a956fe26](https://linux-hardware.org/?probe=57a956fe26) | Jan 04, 2025 |
| MSI           | GP60 2PE                    | Notebook    | [85033de0ee](https://linux-hardware.org/?probe=85033de0ee) | Jan 04, 2025 |
| ONE-NETBOO... | ONEXPLAYER Mini Pro         | Tablet      | [0c88e1238c](https://linux-hardware.org/?probe=0c88e1238c) | Jan 04, 2025 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [5cb8b93a47](https://linux-hardware.org/?probe=5cb8b93a47) | Jan 03, 2025 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [78aeff840f](https://linux-hardware.org/?probe=78aeff840f) | Jan 03, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8a0d66e0ae](https://linux-hardware.org/?probe=8a0d66e0ae) | Jan 02, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9ed77fe056](https://linux-hardware.org/?probe=9ed77fe056) | Jan 02, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [364ab4800d](https://linux-hardware.org/?probe=364ab4800d) | Dec 31, 2024 |
| MSI           | Katana 15 B12VFK            | Notebook    | [1596a8dc1a](https://linux-hardware.org/?probe=1596a8dc1a) | Dec 31, 2024 |
| HP            | 82F2                        | Desktop     | [27ef0f9faa](https://linux-hardware.org/?probe=27ef0f9faa) | Dec 31, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [6762cc7f0e](https://linux-hardware.org/?probe=6762cc7f0e) | Dec 30, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [8e64cf40ca](https://linux-hardware.org/?probe=8e64cf40ca) | Dec 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [a135b01a74](https://linux-hardware.org/?probe=a135b01a74) | Dec 29, 2024 |
| Dell          | Latitude 7640               | Notebook    | [931523acc9](https://linux-hardware.org/?probe=931523acc9) | Dec 28, 2024 |
| Dell          | 0R790T A00                  | Desktop     | [e4545e5825](https://linux-hardware.org/?probe=e4545e5825) | Dec 28, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [1767678641](https://linux-hardware.org/?probe=1767678641) | Dec 27, 2024 |
| Dell          | Precision 5560              | Notebook    | [08e596bd75](https://linux-hardware.org/?probe=08e596bd75) | Dec 24, 2024 |
| Biostar       | X670E VALKYRIE              | Desktop     | [3377f74d6c](https://linux-hardware.org/?probe=3377f74d6c) | Dec 23, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c0781aa880](https://linux-hardware.org/?probe=c0781aa880) | Dec 21, 2024 |
| HP            | 82F2                        | Desktop     | [60bc9eaafd](https://linux-hardware.org/?probe=60bc9eaafd) | Dec 21, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [d873523130](https://linux-hardware.org/?probe=d873523130) | Dec 20, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [c74f2a3d62](https://linux-hardware.org/?probe=c74f2a3d62) | Dec 20, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [2a4b115644](https://linux-hardware.org/?probe=2a4b115644) | Dec 20, 2024 |
| TUXEDO        | W65_W67RC                   | Notebook    | [7b484dafab](https://linux-hardware.org/?probe=7b484dafab) | Dec 19, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ab0167e7ef](https://linux-hardware.org/?probe=ab0167e7ef) | Dec 19, 2024 |
| MSI           | MAG X870 TOMAHAWK WIFI      | Desktop     | [d130ed5ac4](https://linux-hardware.org/?probe=d130ed5ac4) | Dec 19, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [4373e85ee0](https://linux-hardware.org/?probe=4373e85ee0) | Dec 19, 2024 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [685ed908a7](https://linux-hardware.org/?probe=685ed908a7) | Dec 19, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [31002e2c11](https://linux-hardware.org/?probe=31002e2c11) | Dec 18, 2024 |
| ASUSTek       | TUF Gaming FX505DD          | Notebook    | [b9f8f7b1b7](https://linux-hardware.org/?probe=b9f8f7b1b7) | Dec 18, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8898414b6c](https://linux-hardware.org/?probe=8898414b6c) | Dec 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cb5b81704a](https://linux-hardware.org/?probe=cb5b81704a) | Dec 17, 2024 |
| MSI           | PRO B660M-A CEC WIFI DDR... | Desktop     | [460955a4a2](https://linux-hardware.org/?probe=460955a4a2) | Dec 15, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [2e6582243b](https://linux-hardware.org/?probe=2e6582243b) | Dec 14, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [2a73c0dba0](https://linux-hardware.org/?probe=2a73c0dba0) | Dec 14, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [5aad96d6a2](https://linux-hardware.org/?probe=5aad96d6a2) | Dec 12, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [27b32efcbb](https://linux-hardware.org/?probe=27b32efcbb) | Dec 12, 2024 |
| ASUSTek       | Z87-PRO                     | Desktop     | [47f8810b21](https://linux-hardware.org/?probe=47f8810b21) | Dec 10, 2024 |
| Intel         | H61                         | Desktop     | [9182c98522](https://linux-hardware.org/?probe=9182c98522) | Dec 09, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [a9b674b142](https://linux-hardware.org/?probe=a9b674b142) | Dec 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | Notebook    | [5d948ce651](https://linux-hardware.org/?probe=5d948ce651) | Dec 08, 2024 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [5a4b082a2e](https://linux-hardware.org/?probe=5a4b082a2e) | Dec 08, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e74f3d05eb](https://linux-hardware.org/?probe=e74f3d05eb) | Dec 07, 2024 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [e3f868a672](https://linux-hardware.org/?probe=e3f868a672) | Dec 07, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [781388db83](https://linux-hardware.org/?probe=781388db83) | Dec 06, 2024 |
| Dell          | 0KWVT8 A02                  | Desktop     | [3f0222b962](https://linux-hardware.org/?probe=3f0222b962) | Dec 05, 2024 |
| Intel         | H61                         | Desktop     | [a7db65f6c6](https://linux-hardware.org/?probe=a7db65f6c6) | Dec 03, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6f54acb69c](https://linux-hardware.org/?probe=6f54acb69c) | Dec 03, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c430b5f9c4](https://linux-hardware.org/?probe=c430b5f9c4) | Dec 02, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [4f1bc35dbd](https://linux-hardware.org/?probe=4f1bc35dbd) | Dec 02, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7ced21bca6](https://linux-hardware.org/?probe=7ced21bca6) | Dec 02, 2024 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [2aaeb0eac6](https://linux-hardware.org/?probe=2aaeb0eac6) | Dec 02, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [dfd3710904](https://linux-hardware.org/?probe=dfd3710904) | Dec 01, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [329d588b3e](https://linux-hardware.org/?probe=329d588b3e) | Nov 30, 2024 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [e32e466199](https://linux-hardware.org/?probe=e32e466199) | Nov 29, 2024 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [8f59a40a3f](https://linux-hardware.org/?probe=8f59a40a3f) | Nov 29, 2024 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [09eee5a68b](https://linux-hardware.org/?probe=09eee5a68b) | Nov 28, 2024 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [223ec21627](https://linux-hardware.org/?probe=223ec21627) | Nov 28, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [36d1ef2cc9](https://linux-hardware.org/?probe=36d1ef2cc9) | Nov 25, 2024 |
| Lenovo        | ThinkPad T470 20HES22400    | Notebook    | [4a8cc4dd33](https://linux-hardware.org/?probe=4a8cc4dd33) | Nov 25, 2024 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [51ed33c7d7](https://linux-hardware.org/?probe=51ed33c7d7) | Nov 24, 2024 |
| Intel         | X99                         | Desktop     | [67148a7875](https://linux-hardware.org/?probe=67148a7875) | Nov 23, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5d4ce9594c](https://linux-hardware.org/?probe=5d4ce9594c) | Nov 23, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [aaed88422c](https://linux-hardware.org/?probe=aaed88422c) | Nov 22, 2024 |
| Dell          | G3 3500                     | Notebook    | [d340f80f52](https://linux-hardware.org/?probe=d340f80f52) | Nov 22, 2024 |
| Huanan        | X99-F8                      | Desktop     | [8c601c199e](https://linux-hardware.org/?probe=8c601c199e) | Nov 22, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [be07fb315a](https://linux-hardware.org/?probe=be07fb315a) | Nov 20, 2024 |
| Lenovo        | ThinkPad T540p 20BFS3NJ0... | Notebook    | [993e703fe2](https://linux-hardware.org/?probe=993e703fe2) | Nov 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cc9386b2dd](https://linux-hardware.org/?probe=cc9386b2dd) | Nov 19, 2024 |
| Dell          | Vostro 3501                 | Notebook    | [188f410ab2](https://linux-hardware.org/?probe=188f410ab2) | Nov 18, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [0bb978b3d6](https://linux-hardware.org/?probe=0bb978b3d6) | Nov 18, 2024 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [dab12a66ec](https://linux-hardware.org/?probe=dab12a66ec) | Nov 17, 2024 |
| Dell          | Inspiron 7370               | Notebook    | [4ebb5ca686](https://linux-hardware.org/?probe=4ebb5ca686) | Nov 17, 2024 |
| Gigabyte      | X870 GAMING WIFI6           | Desktop     | [561c6e7c57](https://linux-hardware.org/?probe=561c6e7c57) | Nov 16, 2024 |
| Acer          | Nitro ANV15-41              | Notebook    | [41a8d79a11](https://linux-hardware.org/?probe=41a8d79a11) | Nov 14, 2024 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [9bb2ab7160](https://linux-hardware.org/?probe=9bb2ab7160) | Nov 14, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a276aef74](https://linux-hardware.org/?probe=4a276aef74) | Nov 14, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [63d4e9eb77](https://linux-hardware.org/?probe=63d4e9eb77) | Nov 13, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [4b51759f80](https://linux-hardware.org/?probe=4b51759f80) | Nov 13, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [84f5648674](https://linux-hardware.org/?probe=84f5648674) | Nov 12, 2024 |
| Gigabyte      | Z77P-D3                     | Desktop     | [4246bccdbe](https://linux-hardware.org/?probe=4246bccdbe) | Nov 12, 2024 |
| Gigabyte      | X99-Gaming 5P               | Desktop     | [381edc9377](https://linux-hardware.org/?probe=381edc9377) | Nov 11, 2024 |
| Gigabyte      | B760M GAMING X DDR4         | Desktop     | [18074774c5](https://linux-hardware.org/?probe=18074774c5) | Nov 10, 2024 |
| Dell          | Latitude 5501               | Notebook    | [795cc9b2a2](https://linux-hardware.org/?probe=795cc9b2a2) | Nov 09, 2024 |
| GPD           | G1619-01                    | Notebook    | [67400e5fef](https://linux-hardware.org/?probe=67400e5fef) | Nov 09, 2024 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [f450b83e99](https://linux-hardware.org/?probe=f450b83e99) | Nov 08, 2024 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [fc085f33cf](https://linux-hardware.org/?probe=fc085f33cf) | Nov 07, 2024 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [57f123c05b](https://linux-hardware.org/?probe=57f123c05b) | Nov 07, 2024 |
| Intel         | X99                         | Desktop     | [55e94f9a71](https://linux-hardware.org/?probe=55e94f9a71) | Nov 07, 2024 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [65d7d0e79d](https://linux-hardware.org/?probe=65d7d0e79d) | Nov 07, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [28f18e44cd](https://linux-hardware.org/?probe=28f18e44cd) | Nov 06, 2024 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [1880e84034](https://linux-hardware.org/?probe=1880e84034) | Nov 06, 2024 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [98e6f66559](https://linux-hardware.org/?probe=98e6f66559) | Nov 05, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [7650369b4d](https://linux-hardware.org/?probe=7650369b4d) | Nov 05, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b77fe1b29a](https://linux-hardware.org/?probe=b77fe1b29a) | Nov 04, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [62f849e117](https://linux-hardware.org/?probe=62f849e117) | Nov 03, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [61b0699eda](https://linux-hardware.org/?probe=61b0699eda) | Nov 02, 2024 |
| Dell          | G7 7500                     | Notebook    | [54df16b1cb](https://linux-hardware.org/?probe=54df16b1cb) | Nov 02, 2024 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [16f355b56f](https://linux-hardware.org/?probe=16f355b56f) | Nov 01, 2024 |
| Intel         | H61                         | Desktop     | [66d0c733e5](https://linux-hardware.org/?probe=66d0c733e5) | Oct 31, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2d99ad254b](https://linux-hardware.org/?probe=2d99ad254b) | Oct 31, 2024 |
| Dell          | Latitude 5414               | Notebook    | [9412713b3d](https://linux-hardware.org/?probe=9412713b3d) | Oct 30, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [db69d467bc](https://linux-hardware.org/?probe=db69d467bc) | Oct 28, 2024 |
| Dell          | Latitude 7640               | Notebook    | [f092c8cc9f](https://linux-hardware.org/?probe=f092c8cc9f) | Oct 27, 2024 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [83298d1f8c](https://linux-hardware.org/?probe=83298d1f8c) | Oct 27, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [e1d10c7809](https://linux-hardware.org/?probe=e1d10c7809) | Oct 27, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [8e92130871](https://linux-hardware.org/?probe=8e92130871) | Oct 27, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [4da1648423](https://linux-hardware.org/?probe=4da1648423) | Oct 26, 2024 |
| Gigabyte      | B450M H                     | Desktop     | [8647102690](https://linux-hardware.org/?probe=8647102690) | Oct 25, 2024 |
| ASRock        | X570 Taichi                 | Desktop     | [005be99781](https://linux-hardware.org/?probe=005be99781) | Oct 23, 2024 |
| ASUSTek       | P8B WS                      | Desktop     | [b00e01b1f8](https://linux-hardware.org/?probe=b00e01b1f8) | Oct 23, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [6c3c7b5b6e](https://linux-hardware.org/?probe=6c3c7b5b6e) | Oct 22, 2024 |
| ASUSTek       | P8B WS                      | Desktop     | [254c5baca1](https://linux-hardware.org/?probe=254c5baca1) | Oct 22, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [65e030034c](https://linux-hardware.org/?probe=65e030034c) | Oct 21, 2024 |
| Google        | Voema                       | Notebook    | [44b3046dbb](https://linux-hardware.org/?probe=44b3046dbb) | Oct 20, 2024 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [c1a5d4ec9f](https://linux-hardware.org/?probe=c1a5d4ec9f) | Oct 20, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [8c3c800cab](https://linux-hardware.org/?probe=8c3c800cab) | Oct 20, 2024 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [7721fb9198](https://linux-hardware.org/?probe=7721fb9198) | Oct 20, 2024 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [3d9e937b26](https://linux-hardware.org/?probe=3d9e937b26) | Oct 19, 2024 |
| MSI           | Z590-A PRO                  | Desktop     | [d30d302c17](https://linux-hardware.org/?probe=d30d302c17) | Oct 19, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [6a6079e7ce](https://linux-hardware.org/?probe=6a6079e7ce) | Oct 19, 2024 |
| MSI           | Z590-A PRO                  | Desktop     | [81b2d1e1f4](https://linux-hardware.org/?probe=81b2d1e1f4) | Oct 19, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [9023f68b2e](https://linux-hardware.org/?probe=9023f68b2e) | Oct 19, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [ac7fc8a57f](https://linux-hardware.org/?probe=ac7fc8a57f) | Oct 19, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [7c06334b64](https://linux-hardware.org/?probe=7c06334b64) | Oct 19, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [1b2b89b297](https://linux-hardware.org/?probe=1b2b89b297) | Oct 18, 2024 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [4c9ea3cf69](https://linux-hardware.org/?probe=4c9ea3cf69) | Oct 18, 2024 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [4f96194137](https://linux-hardware.org/?probe=4f96194137) | Oct 18, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8366c88c2a](https://linux-hardware.org/?probe=8366c88c2a) | Oct 17, 2024 |
| Positivo      | C4500D                      | Notebook    | [8cc65dc6f7](https://linux-hardware.org/?probe=8cc65dc6f7) | Oct 17, 2024 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [a813c0f99d](https://linux-hardware.org/?probe=a813c0f99d) | Oct 15, 2024 |
| Gigabyte      | Z370 HD3-OP-CF              | Desktop     | [2d9aabb2f9](https://linux-hardware.org/?probe=2d9aabb2f9) | Oct 13, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6920c9c6f9](https://linux-hardware.org/?probe=6920c9c6f9) | Oct 13, 2024 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [6cef126bcc](https://linux-hardware.org/?probe=6cef126bcc) | Oct 12, 2024 |
| Gigabyte      | A520M AORUS ELITE           | Desktop     | [ba7781d62a](https://linux-hardware.org/?probe=ba7781d62a) | Oct 10, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [be6f03c7b0](https://linux-hardware.org/?probe=be6f03c7b0) | Oct 09, 2024 |
| Acer          | TravelMate Spin P414RN-5... | Convertible | [73c9fbba82](https://linux-hardware.org/?probe=73c9fbba82) | Oct 09, 2024 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [6f92c887e2](https://linux-hardware.org/?probe=6f92c887e2) | Oct 09, 2024 |
| ASUSTek       | H97M-E                      | Desktop     | [fc953af8df](https://linux-hardware.org/?probe=fc953af8df) | Oct 09, 2024 |
| HP            | Pavilion g7                 | Notebook    | [ffeaecbfb8](https://linux-hardware.org/?probe=ffeaecbfb8) | Oct 06, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [cbf0fe0aae](https://linux-hardware.org/?probe=cbf0fe0aae) | Oct 06, 2024 |
| Gigabyte      | B550 GAMING X               | Desktop     | [a334df738b](https://linux-hardware.org/?probe=a334df738b) | Oct 05, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1abd4662b5](https://linux-hardware.org/?probe=1abd4662b5) | Oct 04, 2024 |
| Acer          | TravelMate Spin P414RN-5... | Convertible | [aef838689a](https://linux-hardware.org/?probe=aef838689a) | Oct 04, 2024 |
| Medion        | P6634                       | Notebook    | [828ca7861d](https://linux-hardware.org/?probe=828ca7861d) | Oct 04, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2997e9eb80](https://linux-hardware.org/?probe=2997e9eb80) | Oct 03, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [eabed62c84](https://linux-hardware.org/?probe=eabed62c84) | Oct 03, 2024 |
| Acer          | NC-VN7-571G-71KY            | Notebook    | [961929c4a3](https://linux-hardware.org/?probe=961929c4a3) | Oct 02, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2a5b806692](https://linux-hardware.org/?probe=2a5b806692) | Oct 01, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [35d2f6e976](https://linux-hardware.org/?probe=35d2f6e976) | Oct 01, 2024 |
| Lenovo        | NB LN Legion PRO 5 16IRX... | Notebook    | [777ce0c1e8](https://linux-hardware.org/?probe=777ce0c1e8) | Oct 01, 2024 |
| ASRock        | B550M PG Riptide            | Desktop     | [61db53aa55](https://linux-hardware.org/?probe=61db53aa55) | Oct 01, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6102d7ead8](https://linux-hardware.org/?probe=6102d7ead8) | Sep 30, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [2a92f059c6](https://linux-hardware.org/?probe=2a92f059c6) | Sep 30, 2024 |
| Micro Comp... | V3                          | Tablet      | [0199c1086f](https://linux-hardware.org/?probe=0199c1086f) | Sep 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [661a6c1dbe](https://linux-hardware.org/?probe=661a6c1dbe) | Sep 27, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [31ca5c69e0](https://linux-hardware.org/?probe=31ca5c69e0) | Sep 26, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [e3ebc39bd6](https://linux-hardware.org/?probe=e3ebc39bd6) | Sep 26, 2024 |
| Toshiba       | STI NA 1402                 | Notebook    | [41344003cf](https://linux-hardware.org/?probe=41344003cf) | Sep 24, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [4bffdf9667](https://linux-hardware.org/?probe=4bffdf9667) | Sep 24, 2024 |
| HP            | 8053                        | Desktop     | [6d4fb4cdc0](https://linux-hardware.org/?probe=6d4fb4cdc0) | Sep 24, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3943663520](https://linux-hardware.org/?probe=3943663520) | Sep 22, 2024 |
| Pegatron      | NARRA5                      | Desktop     | [21ebe3de7c](https://linux-hardware.org/?probe=21ebe3de7c) | Sep 22, 2024 |
| MSI           | X58 Pro-E                   | Desktop     | [7e3363be7b](https://linux-hardware.org/?probe=7e3363be7b) | Sep 22, 2024 |
| ASRock        | B550 Extreme4               | Desktop     | [67f4dc6df2](https://linux-hardware.org/?probe=67f4dc6df2) | Sep 22, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [4028960ac0](https://linux-hardware.org/?probe=4028960ac0) | Sep 22, 2024 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [dbbdf82c36](https://linux-hardware.org/?probe=dbbdf82c36) | Sep 21, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [114a688c94](https://linux-hardware.org/?probe=114a688c94) | Sep 20, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [31f51ca92c](https://linux-hardware.org/?probe=31f51ca92c) | Sep 19, 2024 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [00f803e8a2](https://linux-hardware.org/?probe=00f803e8a2) | Sep 18, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ccb43a1d7f](https://linux-hardware.org/?probe=ccb43a1d7f) | Sep 17, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [82245bc2ce](https://linux-hardware.org/?probe=82245bc2ce) | Sep 17, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6e992b017a](https://linux-hardware.org/?probe=6e992b017a) | Sep 17, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [bd0c809a5c](https://linux-hardware.org/?probe=bd0c809a5c) | Sep 16, 2024 |
| SHANGZHAOY... | B660-Windwalker WiFi        | Desktop     | [2e5ce6f6d6](https://linux-hardware.org/?probe=2e5ce6f6d6) | Sep 16, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [82c8700c2c](https://linux-hardware.org/?probe=82c8700c2c) | Sep 15, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [ee045918c0](https://linux-hardware.org/?probe=ee045918c0) | Sep 15, 2024 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [1f43f49d79](https://linux-hardware.org/?probe=1f43f49d79) | Sep 14, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [3a2d8ec6fb](https://linux-hardware.org/?probe=3a2d8ec6fb) | Sep 13, 2024 |
| Lenovo        | ThinkPad T540p 20BFS3NJ0... | Notebook    | [48cdbf900a](https://linux-hardware.org/?probe=48cdbf900a) | Sep 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3e9ec89bb2](https://linux-hardware.org/?probe=3e9ec89bb2) | Sep 11, 2024 |
| Acer          | Aspire XC-230               | Desktop     | [25af744fe6](https://linux-hardware.org/?probe=25af744fe6) | Sep 11, 2024 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [634498b151](https://linux-hardware.org/?probe=634498b151) | Sep 11, 2024 |
| MSI           | Bravo 15 B5ED               | Notebook    | [c35283718a](https://linux-hardware.org/?probe=c35283718a) | Sep 11, 2024 |
| OriginPC      | EVO15-S                     | Notebook    | [e831dcf496](https://linux-hardware.org/?probe=e831dcf496) | Sep 10, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [9f7d06f4a9](https://linux-hardware.org/?probe=9f7d06f4a9) | Sep 09, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2a3aeae658](https://linux-hardware.org/?probe=2a3aeae658) | Sep 09, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [ca86aef95f](https://linux-hardware.org/?probe=ca86aef95f) | Sep 09, 2024 |
| ASUSTek       | PRIME B550M-K               | Notebook    | [941a87d145](https://linux-hardware.org/?probe=941a87d145) | Sep 09, 2024 |
| ASUSTek       | PRIME B550M-K               | Notebook    | [d23b83473c](https://linux-hardware.org/?probe=d23b83473c) | Sep 08, 2024 |
| Dell          | Inspiron 13-7378            | Notebook    | [bdc78c2296](https://linux-hardware.org/?probe=bdc78c2296) | Sep 07, 2024 |
| Gigabyte      | Z370 HD3-OP-CF              | Desktop     | [b8bba497a2](https://linux-hardware.org/?probe=b8bba497a2) | Sep 06, 2024 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [9669441dff](https://linux-hardware.org/?probe=9669441dff) | Sep 06, 2024 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [9ae4a883e8](https://linux-hardware.org/?probe=9ae4a883e8) | Sep 06, 2024 |
| ASUSTek       | X99-A                       | Desktop     | [5e83ee6039](https://linux-hardware.org/?probe=5e83ee6039) | Sep 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8a131268aa](https://linux-hardware.org/?probe=8a131268aa) | Sep 05, 2024 |
| SKIKK         | Freya 15 II                 | Notebook    | [dfa0e481b8](https://linux-hardware.org/?probe=dfa0e481b8) | Sep 04, 2024 |
| Gigabyte      | Z370 HD3-OP-CF              | Desktop     | [80ad6abbe1](https://linux-hardware.org/?probe=80ad6abbe1) | Sep 04, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b129e9b2fc](https://linux-hardware.org/?probe=b129e9b2fc) | Sep 04, 2024 |
| Acer          | Veriton N4680G              | Desktop     | [f68b9f3c16](https://linux-hardware.org/?probe=f68b9f3c16) | Sep 03, 2024 |
| HP            | ENVY 17                     | Notebook    | [bd581d250e](https://linux-hardware.org/?probe=bd581d250e) | Sep 02, 2024 |
| ASRock        | X570 Extreme4               | Desktop     | [a5f8e2c232](https://linux-hardware.org/?probe=a5f8e2c232) | Sep 02, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [09a31b189f](https://linux-hardware.org/?probe=09a31b189f) | Sep 02, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [589217f8f1](https://linux-hardware.org/?probe=589217f8f1) | Sep 02, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | Desktop     | [63f20be813](https://linux-hardware.org/?probe=63f20be813) | Sep 02, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [f71f25079f](https://linux-hardware.org/?probe=f71f25079f) | Sep 02, 2024 |
| ASRock        | X570 Extreme4               | Desktop     | [524d7cfc1a](https://linux-hardware.org/?probe=524d7cfc1a) | Sep 01, 2024 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [e85401367d](https://linux-hardware.org/?probe=e85401367d) | Sep 01, 2024 |
| Dell          | Latitude E7470              | Notebook    | [e8dd306c05](https://linux-hardware.org/?probe=e8dd306c05) | Aug 31, 2024 |
| HP            | ENVY 15                     | Notebook    | [0ed23d53d9](https://linux-hardware.org/?probe=0ed23d53d9) | Aug 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | Notebook    | [d5764b3dc3](https://linux-hardware.org/?probe=d5764b3dc3) | Aug 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d3e5b52482](https://linux-hardware.org/?probe=d3e5b52482) | Aug 28, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a6b4018475](https://linux-hardware.org/?probe=a6b4018475) | Aug 27, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [354c28bb51](https://linux-hardware.org/?probe=354c28bb51) | Aug 27, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e909a9e846](https://linux-hardware.org/?probe=e909a9e846) | Aug 27, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [082067d04e](https://linux-hardware.org/?probe=082067d04e) | Aug 27, 2024 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [fafee6010b](https://linux-hardware.org/?probe=fafee6010b) | Aug 27, 2024 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [d349f84342](https://linux-hardware.org/?probe=d349f84342) | Aug 27, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [1dad24fb59](https://linux-hardware.org/?probe=1dad24fb59) | Aug 27, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [09d8b1b16f](https://linux-hardware.org/?probe=09d8b1b16f) | Aug 27, 2024 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [75dc555f11](https://linux-hardware.org/?probe=75dc555f11) | Aug 26, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [77bd51a6c1](https://linux-hardware.org/?probe=77bd51a6c1) | Aug 25, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [868f3a4d90](https://linux-hardware.org/?probe=868f3a4d90) | Aug 24, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [f44ffefe98](https://linux-hardware.org/?probe=f44ffefe98) | Aug 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [682df42cb8](https://linux-hardware.org/?probe=682df42cb8) | Aug 24, 2024 |
| Gigabyte      | Z270X-Gaming 8              | Desktop     | [1b79ddb751](https://linux-hardware.org/?probe=1b79ddb751) | Aug 24, 2024 |
| Intel Clie... | LAPRC510                    | Notebook    | [1fd9d1dc79](https://linux-hardware.org/?probe=1fd9d1dc79) | Aug 21, 2024 |
| Dell          | G15 5511                    | Notebook    | [814c811429](https://linux-hardware.org/?probe=814c811429) | Aug 21, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [7e7177ec16](https://linux-hardware.org/?probe=7e7177ec16) | Aug 19, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8fff051c21](https://linux-hardware.org/?probe=8fff051c21) | Aug 18, 2024 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [351efc3c9e](https://linux-hardware.org/?probe=351efc3c9e) | Aug 18, 2024 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [e587a55332](https://linux-hardware.org/?probe=e587a55332) | Aug 18, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | Notebook    | [446f0c7ee7](https://linux-hardware.org/?probe=446f0c7ee7) | Aug 17, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5b21c486ac](https://linux-hardware.org/?probe=5b21c486ac) | Aug 17, 2024 |
| Gigabyte      | A520M K V2                  | Desktop     | [ed533ddae9](https://linux-hardware.org/?probe=ed533ddae9) | Aug 17, 2024 |
| Gigabyte      | A520M K V2                  | Desktop     | [83538e7d51](https://linux-hardware.org/?probe=83538e7d51) | Aug 16, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [eb6240b054](https://linux-hardware.org/?probe=eb6240b054) | Aug 16, 2024 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [2d5671ed8d](https://linux-hardware.org/?probe=2d5671ed8d) | Aug 16, 2024 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [af25c599ca](https://linux-hardware.org/?probe=af25c599ca) | Aug 12, 2024 |
| MSI           | MPG B760I EDGE WIFI         | Desktop     | [1fa3b8f384](https://linux-hardware.org/?probe=1fa3b8f384) | Aug 11, 2024 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [8e7e8b9882](https://linux-hardware.org/?probe=8e7e8b9882) | Aug 11, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e164b97c6b](https://linux-hardware.org/?probe=e164b97c6b) | Aug 09, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [d9ac4eeac7](https://linux-hardware.org/?probe=d9ac4eeac7) | Aug 09, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [c295cb4e1d](https://linux-hardware.org/?probe=c295cb4e1d) | Aug 09, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Notebook    | [6414beb6f8](https://linux-hardware.org/?probe=6414beb6f8) | Aug 08, 2024 |
| HP            | Pavilion g7                 | Notebook    | [126dbbbc1f](https://linux-hardware.org/?probe=126dbbbc1f) | Aug 06, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [009890f900](https://linux-hardware.org/?probe=009890f900) | Aug 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [47629a128e](https://linux-hardware.org/?probe=47629a128e) | Aug 06, 2024 |
| Biostar       | H510MH                      | Desktop     | [aff65ed9bb](https://linux-hardware.org/?probe=aff65ed9bb) | Aug 05, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b7094c9cc6](https://linux-hardware.org/?probe=b7094c9cc6) | Aug 05, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [29e8dfd962](https://linux-hardware.org/?probe=29e8dfd962) | Aug 05, 2024 |
| Biostar       | H510MH                      | Desktop     | [73c7b009aa](https://linux-hardware.org/?probe=73c7b009aa) | Aug 05, 2024 |
| Lenovo        | G500s 20245                 | Notebook    | [a5fbbc146f](https://linux-hardware.org/?probe=a5fbbc146f) | Aug 05, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [c22bf00268](https://linux-hardware.org/?probe=c22bf00268) | Aug 02, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [0df454ac8c](https://linux-hardware.org/?probe=0df454ac8c) | Aug 02, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [262b4a9344](https://linux-hardware.org/?probe=262b4a9344) | Aug 02, 2024 |
| Gigabyte      | B650 AORUS ELITE AX ICE     | Desktop     | [b78a0e3a63](https://linux-hardware.org/?probe=b78a0e3a63) | Aug 02, 2024 |
| ASRock        | X570 Steel Legend           | Desktop     | [c91f442dbc](https://linux-hardware.org/?probe=c91f442dbc) | Aug 02, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a91a2a9dbd](https://linux-hardware.org/?probe=a91a2a9dbd) | Aug 02, 2024 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [fad0adb50b](https://linux-hardware.org/?probe=fad0adb50b) | Aug 01, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [9285d60b1f](https://linux-hardware.org/?probe=9285d60b1f) | Jul 30, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [9c1c5c8eef](https://linux-hardware.org/?probe=9c1c5c8eef) | Jul 29, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6715f512f6](https://linux-hardware.org/?probe=6715f512f6) | Jul 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1dada87aeb](https://linux-hardware.org/?probe=1dada87aeb) | Jul 26, 2024 |
| Timi          | Mi NoteBook Pro             | Notebook    | [363f9c519e](https://linux-hardware.org/?probe=363f9c519e) | Jul 26, 2024 |
| HP            | Pavilion 17                 | Notebook    | [059579abe8](https://linux-hardware.org/?probe=059579abe8) | Jul 25, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [662024db12](https://linux-hardware.org/?probe=662024db12) | Jul 24, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [840c02e30a](https://linux-hardware.org/?probe=840c02e30a) | Jul 21, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c7518aa4c6](https://linux-hardware.org/?probe=c7518aa4c6) | Jul 20, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [16b5d3d099](https://linux-hardware.org/?probe=16b5d3d099) | Jul 20, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a2cf36d4e8](https://linux-hardware.org/?probe=a2cf36d4e8) | Jul 19, 2024 |
| Sony          | VPCF13UFX                   | Notebook    | [2aa739a934](https://linux-hardware.org/?probe=2aa739a934) | Jul 19, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [fc6a4ed60b](https://linux-hardware.org/?probe=fc6a4ed60b) | Jul 18, 2024 |
| Acer          | Nitro AN515-51              | Notebook    | [1e21d843a7](https://linux-hardware.org/?probe=1e21d843a7) | Jul 18, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6607549265](https://linux-hardware.org/?probe=6607549265) | Jul 17, 2024 |
| Acer          | Aspire E1-772G              | Notebook    | [4c667e9426](https://linux-hardware.org/?probe=4c667e9426) | Jul 16, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [86e19665a9](https://linux-hardware.org/?probe=86e19665a9) | Jul 16, 2024 |
| MSI           | PRO B650-S WIFI             | Desktop     | [c2b885c66a](https://linux-hardware.org/?probe=c2b885c66a) | Jul 16, 2024 |
| Acer          | Aspire E1-772G              | Notebook    | [d5c066a3ec](https://linux-hardware.org/?probe=d5c066a3ec) | Jul 16, 2024 |
| HP            | OMEN Laptop 15-ek1xxx       | Notebook    | [57853c11b0](https://linux-hardware.org/?probe=57853c11b0) | Jul 16, 2024 |
| HP            | OMEN Laptop 15-ek1xxx       | Notebook    | [eba04cac19](https://linux-hardware.org/?probe=eba04cac19) | Jul 16, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [53644a2931](https://linux-hardware.org/?probe=53644a2931) | Jul 14, 2024 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [eadc051df3](https://linux-hardware.org/?probe=eadc051df3) | Jul 13, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [a9609c5b68](https://linux-hardware.org/?probe=a9609c5b68) | Jul 12, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [766f38024b](https://linux-hardware.org/?probe=766f38024b) | Jul 11, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [4c8b2c2853](https://linux-hardware.org/?probe=4c8b2c2853) | Jul 11, 2024 |
| ASRock        | X370 Pro4                   | Desktop     | [f11e620b5b](https://linux-hardware.org/?probe=f11e620b5b) | Jul 11, 2024 |
| ASRock        | X370 Pro4                   | Desktop     | [755857b571](https://linux-hardware.org/?probe=755857b571) | Jul 11, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6236a3d216](https://linux-hardware.org/?probe=6236a3d216) | Jul 10, 2024 |
| Acer          | Swift SFX16-61G             | Notebook    | [bd890bbcfa](https://linux-hardware.org/?probe=bd890bbcfa) | Jul 09, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [215839623e](https://linux-hardware.org/?probe=215839623e) | Jul 09, 2024 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [239d73b099](https://linux-hardware.org/?probe=239d73b099) | Jul 09, 2024 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [43820b64f9](https://linux-hardware.org/?probe=43820b64f9) | Jul 09, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [71a4de6be5](https://linux-hardware.org/?probe=71a4de6be5) | Jul 09, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [34e961b399](https://linux-hardware.org/?probe=34e961b399) | Jul 08, 2024 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [d25386744b](https://linux-hardware.org/?probe=d25386744b) | Jul 08, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [ffbcb2cf5a](https://linux-hardware.org/?probe=ffbcb2cf5a) | Jul 07, 2024 |
| MSI           | PRO B650-S WIFI             | Desktop     | [7d1a47096c](https://linux-hardware.org/?probe=7d1a47096c) | Jul 06, 2024 |
| ASUSTek       | PRIME B450M-A               | Notebook    | [d27fff2ebc](https://linux-hardware.org/?probe=d27fff2ebc) | Jul 06, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [20d1b938e7](https://linux-hardware.org/?probe=20d1b938e7) | Jul 05, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Notebook    | [9971b9e563](https://linux-hardware.org/?probe=9971b9e563) | Jul 05, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0a85e482f2](https://linux-hardware.org/?probe=0a85e482f2) | Jul 05, 2024 |
| TULPAR        | T7 V20.6                    | Notebook    | [c2d1e64ed3](https://linux-hardware.org/?probe=c2d1e64ed3) | Jul 04, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [6c973d4ba6](https://linux-hardware.org/?probe=6c973d4ba6) | Jul 02, 2024 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [8cab008afc](https://linux-hardware.org/?probe=8cab008afc) | Jul 02, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [0d4efe1596](https://linux-hardware.org/?probe=0d4efe1596) | Jun 30, 2024 |
| ASUSTek       | PRIME B760M-A WIFI          | Desktop     | [e642c97c1b](https://linux-hardware.org/?probe=e642c97c1b) | Jun 30, 2024 |
| Unknown       | AX16Pro                     | Notebook    | [2641e1b005](https://linux-hardware.org/?probe=2641e1b005) | Jun 29, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [2b24f333f4](https://linux-hardware.org/?probe=2b24f333f4) | Jun 29, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ebcc1313ce](https://linux-hardware.org/?probe=ebcc1313ce) | Jun 29, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [c45e854d18](https://linux-hardware.org/?probe=c45e854d18) | Jun 28, 2024 |
| Intel         | H61                         | Desktop     | [37c8512569](https://linux-hardware.org/?probe=37c8512569) | Jun 28, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [190ec9dbf4](https://linux-hardware.org/?probe=190ec9dbf4) | Jun 27, 2024 |
| MSI           | GL65 9SCK                   | Notebook    | [6dfd90d8e1](https://linux-hardware.org/?probe=6dfd90d8e1) | Jun 26, 2024 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [7f9e6d2b1b](https://linux-hardware.org/?probe=7f9e6d2b1b) | Jun 26, 2024 |
| Lenovo        | LOQ 15IAX9I 83FQ            | Notebook    | [45183ac6bf](https://linux-hardware.org/?probe=45183ac6bf) | Jun 24, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [fe782c8c71](https://linux-hardware.org/?probe=fe782c8c71) | Jun 23, 2024 |
| Intel Clie... | LAPQC71B                    | Notebook    | [d08a11d6d2](https://linux-hardware.org/?probe=d08a11d6d2) | Jun 20, 2024 |
| ASRock        | H410M-HDV                   | Desktop     | [db3bd3a0a9](https://linux-hardware.org/?probe=db3bd3a0a9) | Jun 20, 2024 |
| ASRock        | H410M-HDV                   | Desktop     | [2b0375bd7d](https://linux-hardware.org/?probe=2b0375bd7d) | Jun 20, 2024 |
| Lenovo        | ThinkBook 14s G2 ITL 20V... | Notebook    | [5f3b725a8a](https://linux-hardware.org/?probe=5f3b725a8a) | Jun 19, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [03bb28cbe2](https://linux-hardware.org/?probe=03bb28cbe2) | Jun 18, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [8d153983d1](https://linux-hardware.org/?probe=8d153983d1) | Jun 18, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [23550a4600](https://linux-hardware.org/?probe=23550a4600) | Jun 17, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [78b31c4750](https://linux-hardware.org/?probe=78b31c4750) | Jun 17, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [c5ba2fab9d](https://linux-hardware.org/?probe=c5ba2fab9d) | Jun 16, 2024 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [289fa5b668](https://linux-hardware.org/?probe=289fa5b668) | Jun 16, 2024 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [5940c3baf9](https://linux-hardware.org/?probe=5940c3baf9) | Jun 16, 2024 |
| Acer          | Aspire A315-54              | Notebook    | [cb70d81ffc](https://linux-hardware.org/?probe=cb70d81ffc) | Jun 16, 2024 |
| MSI           | Z170A GAMING M3             | Desktop     | [c8053d6caa](https://linux-hardware.org/?probe=c8053d6caa) | Jun 16, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [7527e0254e](https://linux-hardware.org/?probe=7527e0254e) | Jun 15, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [1452f03d11](https://linux-hardware.org/?probe=1452f03d11) | Jun 15, 2024 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [df32e85db0](https://linux-hardware.org/?probe=df32e85db0) | Jun 15, 2024 |
| Dell          | Latitude 7212 Rugged Ext... | Tablet      | [21a4bd396e](https://linux-hardware.org/?probe=21a4bd396e) | Jun 15, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [432cebcb58](https://linux-hardware.org/?probe=432cebcb58) | Jun 13, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [1b5d18d182](https://linux-hardware.org/?probe=1b5d18d182) | Jun 13, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [8c13e001be](https://linux-hardware.org/?probe=8c13e001be) | Jun 13, 2024 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [473d08f39f](https://linux-hardware.org/?probe=473d08f39f) | Jun 12, 2024 |
| Gigabyte      | B550 AORUS PRO AX           | Desktop     | [626f9ea78b](https://linux-hardware.org/?probe=626f9ea78b) | Jun 12, 2024 |
| PC Special... | Standard                    | Notebook    | [4af601ff05](https://linux-hardware.org/?probe=4af601ff05) | Jun 12, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [5790548050](https://linux-hardware.org/?probe=5790548050) | Jun 11, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c56f3fc677](https://linux-hardware.org/?probe=c56f3fc677) | Jun 11, 2024 |
| MSI           | MPG Z790 EDGE WIFI          | Desktop     | [e4153a0453](https://linux-hardware.org/?probe=e4153a0453) | Jun 09, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [8cde2593bf](https://linux-hardware.org/?probe=8cde2593bf) | Jun 09, 2024 |
| Gigabyte      | Z690 UD DDR4                | Notebook    | [79ef3851bf](https://linux-hardware.org/?probe=79ef3851bf) | Jun 08, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [bf1d68388b](https://linux-hardware.org/?probe=bf1d68388b) | Jun 08, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [c0181b365b](https://linux-hardware.org/?probe=c0181b365b) | Jun 07, 2024 |
| Dell          | 0P301D A02                  | Desktop     | [d62c7c96c8](https://linux-hardware.org/?probe=d62c7c96c8) | Jun 07, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5bf18fb60c](https://linux-hardware.org/?probe=5bf18fb60c) | Jun 07, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1e0bffcc4c](https://linux-hardware.org/?probe=1e0bffcc4c) | Jun 07, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [9d0db9afbe](https://linux-hardware.org/?probe=9d0db9afbe) | Jun 06, 2024 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [ebaa0e6996](https://linux-hardware.org/?probe=ebaa0e6996) | Jun 06, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [410de4c679](https://linux-hardware.org/?probe=410de4c679) | Jun 06, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [cf9d7ad424](https://linux-hardware.org/?probe=cf9d7ad424) | Jun 06, 2024 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [c5af84ee59](https://linux-hardware.org/?probe=c5af84ee59) | Jun 05, 2024 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [2acdc42990](https://linux-hardware.org/?probe=2acdc42990) | Jun 05, 2024 |
| Dell          | 07KY25 A00                  | Desktop     | [aee7f121ee](https://linux-hardware.org/?probe=aee7f121ee) | Jun 04, 2024 |
| ASRock        | B650E Taichi Lite           | Desktop     | [ff3af03c45](https://linux-hardware.org/?probe=ff3af03c45) | Jun 04, 2024 |
| ASRock        | X470 Taichi                 | Desktop     | [f36f6618b7](https://linux-hardware.org/?probe=f36f6618b7) | Jun 04, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1d5e9aec18](https://linux-hardware.org/?probe=1d5e9aec18) | Jun 03, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [eea3ee6a3f](https://linux-hardware.org/?probe=eea3ee6a3f) | Jun 03, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [3ec8313514](https://linux-hardware.org/?probe=3ec8313514) | Jun 03, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5444732c74](https://linux-hardware.org/?probe=5444732c74) | Jun 01, 2024 |
| ASUSTek       | PRIME B760M-A WIFI          | Desktop     | [73e7cb47e0](https://linux-hardware.org/?probe=73e7cb47e0) | May 31, 2024 |
| Positivo      | C4500D                      | Notebook    | [43183e276d](https://linux-hardware.org/?probe=43183e276d) | May 31, 2024 |
| Dell          | Latitude E6440              | Notebook    | [9141e75479](https://linux-hardware.org/?probe=9141e75479) | May 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e4547bc1b7](https://linux-hardware.org/?probe=e4547bc1b7) | May 29, 2024 |
| HP            | 1497                        | Desktop     | [c2e3a4d71b](https://linux-hardware.org/?probe=c2e3a4d71b) | May 29, 2024 |
| ASUSTek       | ROG Flow X13 GV302XA_GV3... | Convertible | [8e27a0c9ac](https://linux-hardware.org/?probe=8e27a0c9ac) | May 28, 2024 |
| ASUSTek       | P9X79 WS                    | Desktop     | [f897fa7ea6](https://linux-hardware.org/?probe=f897fa7ea6) | May 27, 2024 |
| AZW           | SER V1                      | Desktop     | [15d96a0603](https://linux-hardware.org/?probe=15d96a0603) | May 27, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2d615ff1bb](https://linux-hardware.org/?probe=2d615ff1bb) | May 26, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [b1fe406375](https://linux-hardware.org/?probe=b1fe406375) | May 25, 2024 |
| Dell          | 006K82 A00                  | Desktop     | [55faa2145e](https://linux-hardware.org/?probe=55faa2145e) | May 25, 2024 |
| Gigabyte      | AORUS 5 KB                  | Notebook    | [0083b70388](https://linux-hardware.org/?probe=0083b70388) | May 23, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [28c04475fd](https://linux-hardware.org/?probe=28c04475fd) | May 22, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6162aa6302](https://linux-hardware.org/?probe=6162aa6302) | May 22, 2024 |
| MSI           | B360 GAMING PLUS            | Desktop     | [e84f73a023](https://linux-hardware.org/?probe=e84f73a023) | May 21, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [986474f731](https://linux-hardware.org/?probe=986474f731) | May 21, 2024 |
| ASRock        | X570 Steel Legend           | Desktop     | [64644e0a2b](https://linux-hardware.org/?probe=64644e0a2b) | May 20, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [30bf8fb88d](https://linux-hardware.org/?probe=30bf8fb88d) | May 20, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [7290a9caef](https://linux-hardware.org/?probe=7290a9caef) | May 20, 2024 |
| Acer          | Aspire SW5-012              | Notebook    | [a7ba598273](https://linux-hardware.org/?probe=a7ba598273) | May 20, 2024 |
| Acer          | Aspire 5749Z                | Notebook    | [320fb5a226](https://linux-hardware.org/?probe=320fb5a226) | May 19, 2024 |
| Acer          | Aspire A515-56              | Notebook    | [4b02f37bde](https://linux-hardware.org/?probe=4b02f37bde) | May 18, 2024 |
| HP            | 87D6 SMVB                   | Desktop     | [c237a1fc2c](https://linux-hardware.org/?probe=c237a1fc2c) | May 18, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [54d8293b03](https://linux-hardware.org/?probe=54d8293b03) | May 18, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c0475026a7](https://linux-hardware.org/?probe=c0475026a7) | May 18, 2024 |
| Acer          | Predator PO3-620            | Desktop     | [af96e0ab5d](https://linux-hardware.org/?probe=af96e0ab5d) | May 15, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b64fc122a4](https://linux-hardware.org/?probe=b64fc122a4) | May 14, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [0632772575](https://linux-hardware.org/?probe=0632772575) | May 14, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [31c23bfc00](https://linux-hardware.org/?probe=31c23bfc00) | May 14, 2024 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [933bd4fff9](https://linux-hardware.org/?probe=933bd4fff9) | May 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5a708d5ae8](https://linux-hardware.org/?probe=5a708d5ae8) | May 12, 2024 |
| ASUSTek       | ROG Strix G834JY_G834JY     | Notebook    | [1c595a1a2b](https://linux-hardware.org/?probe=1c595a1a2b) | May 12, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f129104c67](https://linux-hardware.org/?probe=f129104c67) | May 11, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [36cd2d57c9](https://linux-hardware.org/?probe=36cd2d57c9) | May 10, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [f1c0565833](https://linux-hardware.org/?probe=f1c0565833) | May 09, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4bd0ad2bb9](https://linux-hardware.org/?probe=4bd0ad2bb9) | May 09, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5c2ce66225](https://linux-hardware.org/?probe=5c2ce66225) | May 08, 2024 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [b941b8d062](https://linux-hardware.org/?probe=b941b8d062) | May 07, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [0c73837ccd](https://linux-hardware.org/?probe=0c73837ccd) | May 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [84cc2abe63](https://linux-hardware.org/?probe=84cc2abe63) | May 06, 2024 |
| PC Special... | NH5x_7xDPx                  | Notebook    | [35a25ffdfd](https://linux-hardware.org/?probe=35a25ffdfd) | May 06, 2024 |
| Samsung       | 370E4K                      | Notebook    | [f0c626e7ca](https://linux-hardware.org/?probe=f0c626e7ca) | May 05, 2024 |
| Dell          | Inspiron 5502               | Notebook    | [43fee6a80f](https://linux-hardware.org/?probe=43fee6a80f) | May 05, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [55d15ed397](https://linux-hardware.org/?probe=55d15ed397) | May 05, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [6ee8d65521](https://linux-hardware.org/?probe=6ee8d65521) | May 05, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [2fdf2caa36](https://linux-hardware.org/?probe=2fdf2caa36) | May 05, 2024 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [22b510c32b](https://linux-hardware.org/?probe=22b510c32b) | May 04, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2de27a1ebc](https://linux-hardware.org/?probe=2de27a1ebc) | May 04, 2024 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [7411eab31d](https://linux-hardware.org/?probe=7411eab31d) | May 04, 2024 |
| ASRock        | X370 Taichi                 | Desktop     | [08bb9f240a](https://linux-hardware.org/?probe=08bb9f240a) | May 03, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [c8e2add151](https://linux-hardware.org/?probe=c8e2add151) | May 03, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [f0c6a403e2](https://linux-hardware.org/?probe=f0c6a403e2) | May 02, 2024 |
| Intel         | X79G V2.x                   | Desktop     | [00807bfaa6](https://linux-hardware.org/?probe=00807bfaa6) | May 02, 2024 |
| Dell          | 0WMJ54 A00                  | Desktop     | [c1af86a1e6](https://linux-hardware.org/?probe=c1af86a1e6) | May 01, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [e6e296b237](https://linux-hardware.org/?probe=e6e296b237) | May 01, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [901ee2545c](https://linux-hardware.org/?probe=901ee2545c) | Apr 30, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [c8d1f19fe6](https://linux-hardware.org/?probe=c8d1f19fe6) | Apr 29, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d72dcf834b](https://linux-hardware.org/?probe=d72dcf834b) | Apr 29, 2024 |
| HP            | 18E7                        | Desktop     | [e91218e74f](https://linux-hardware.org/?probe=e91218e74f) | Apr 28, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [a9b063c17b](https://linux-hardware.org/?probe=a9b063c17b) | Apr 28, 2024 |
| HP            | 18E7                        | Desktop     | [4442e8fc4a](https://linux-hardware.org/?probe=4442e8fc4a) | Apr 27, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ed27359470](https://linux-hardware.org/?probe=ed27359470) | Apr 27, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [63cd7f6146](https://linux-hardware.org/?probe=63cd7f6146) | Apr 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f619fc2cb1](https://linux-hardware.org/?probe=f619fc2cb1) | Apr 26, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [551ccdf911](https://linux-hardware.org/?probe=551ccdf911) | Apr 26, 2024 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | Desktop     | [849a82e562](https://linux-hardware.org/?probe=849a82e562) | Apr 25, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [31bdb0d059](https://linux-hardware.org/?probe=31bdb0d059) | Apr 24, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [d4c46c8278](https://linux-hardware.org/?probe=d4c46c8278) | Apr 24, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [14164a1cf6](https://linux-hardware.org/?probe=14164a1cf6) | Apr 23, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [1d431b3c1c](https://linux-hardware.org/?probe=1d431b3c1c) | Apr 23, 2024 |
| HP            | 8876 11                     | Notebook    | [a276feeb19](https://linux-hardware.org/?probe=a276feeb19) | Apr 22, 2024 |
| HP            | 8876 11                     | Notebook    | [17290d87ba](https://linux-hardware.org/?probe=17290d87ba) | Apr 22, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [743a3ab71e](https://linux-hardware.org/?probe=743a3ab71e) | Apr 22, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [549ac56060](https://linux-hardware.org/?probe=549ac56060) | Apr 21, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [98d15b6d8d](https://linux-hardware.org/?probe=98d15b6d8d) | Apr 20, 2024 |
| Apple         | MacBookPro16,1              | Notebook    | [af2c346bb9](https://linux-hardware.org/?probe=af2c346bb9) | Apr 20, 2024 |
| Notebook      | W330SU2                     | Notebook    | [7efde9ff70](https://linux-hardware.org/?probe=7efde9ff70) | Apr 20, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1e5130ce4b](https://linux-hardware.org/?probe=1e5130ce4b) | Apr 20, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4b3ef47f33](https://linux-hardware.org/?probe=4b3ef47f33) | Apr 20, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [e79a40955f](https://linux-hardware.org/?probe=e79a40955f) | Apr 19, 2024 |
| Biostar       | TP43E Combo                 | Desktop     | [b952037ea6](https://linux-hardware.org/?probe=b952037ea6) | Apr 19, 2024 |
| Gigabyte      | Z370 HD3-OP-CF              | Desktop     | [0f88ddd572](https://linux-hardware.org/?probe=0f88ddd572) | Apr 19, 2024 |
| Dell          | Latitude E6440              | Notebook    | [82713456e1](https://linux-hardware.org/?probe=82713456e1) | Apr 19, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [7f26f09fac](https://linux-hardware.org/?probe=7f26f09fac) | Apr 19, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [1233f9c380](https://linux-hardware.org/?probe=1233f9c380) | Apr 17, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [1aa89aefa2](https://linux-hardware.org/?probe=1aa89aefa2) | Apr 17, 2024 |
| Acer          | Nitro AN517-52              | Notebook    | [da7720d0f0](https://linux-hardware.org/?probe=da7720d0f0) | Apr 16, 2024 |
| Acer          | Nitro AN517-52              | Notebook    | [a65d6b6abb](https://linux-hardware.org/?probe=a65d6b6abb) | Apr 16, 2024 |
| ASUSTek       | G751JM                      | Notebook    | [78bd2126e9](https://linux-hardware.org/?probe=78bd2126e9) | Apr 15, 2024 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [ad026e12f6](https://linux-hardware.org/?probe=ad026e12f6) | Apr 15, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [b160ab4b5b](https://linux-hardware.org/?probe=b160ab4b5b) | Apr 15, 2024 |
| iOTA          | Unknown                     | Tablet      | [ad2e65fccd](https://linux-hardware.org/?probe=ad2e65fccd) | Apr 14, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [5b1221e03a](https://linux-hardware.org/?probe=5b1221e03a) | Apr 14, 2024 |
| Dell          | G15 5530                    | Notebook    | [8f4e471788](https://linux-hardware.org/?probe=8f4e471788) | Apr 14, 2024 |
| NZXT          | N7 B550                     | Desktop     | [4a8cd3ae3d](https://linux-hardware.org/?probe=4a8cd3ae3d) | Apr 13, 2024 |
| HP            | 158B                        | Desktop     | [3feac8009d](https://linux-hardware.org/?probe=3feac8009d) | Apr 13, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [67a625ad88](https://linux-hardware.org/?probe=67a625ad88) | Apr 13, 2024 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [2292771038](https://linux-hardware.org/?probe=2292771038) | Apr 13, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [44b48f5aa1](https://linux-hardware.org/?probe=44b48f5aa1) | Apr 13, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2bbd6deca8](https://linux-hardware.org/?probe=2bbd6deca8) | Apr 13, 2024 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [08552dc593](https://linux-hardware.org/?probe=08552dc593) | Apr 13, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [51f660c2fd](https://linux-hardware.org/?probe=51f660c2fd) | Apr 12, 2024 |
| ANGXUN        | X99 V1.0                    | Desktop     | [2aceaa68c2](https://linux-hardware.org/?probe=2aceaa68c2) | Apr 12, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [2dc18938a1](https://linux-hardware.org/?probe=2dc18938a1) | Apr 10, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [1b09cf1322](https://linux-hardware.org/?probe=1b09cf1322) | Apr 10, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [46ec5edae0](https://linux-hardware.org/?probe=46ec5edae0) | Apr 10, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [5dc47ea562](https://linux-hardware.org/?probe=5dc47ea562) | Apr 09, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [344cb034bc](https://linux-hardware.org/?probe=344cb034bc) | Apr 08, 2024 |
| System76      | Gazelle                     | Notebook    | [969d376558](https://linux-hardware.org/?probe=969d376558) | Apr 07, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [3b882c0d29](https://linux-hardware.org/?probe=3b882c0d29) | Apr 07, 2024 |
| MSI           | Z170A GAMING M5             | Desktop     | [3ade43a7b8](https://linux-hardware.org/?probe=3ade43a7b8) | Apr 06, 2024 |
| HC Technol... | HCAR4000-MI                 | Desktop     | [c11da7c4fa](https://linux-hardware.org/?probe=c11da7c4fa) | Apr 05, 2024 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [b0756090bc](https://linux-hardware.org/?probe=b0756090bc) | Apr 05, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [6c1225353c](https://linux-hardware.org/?probe=6c1225353c) | Apr 04, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [c41b82e141](https://linux-hardware.org/?probe=c41b82e141) | Apr 04, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4fc3272c07](https://linux-hardware.org/?probe=4fc3272c07) | Apr 04, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a9b4ee8ca9](https://linux-hardware.org/?probe=a9b4ee8ca9) | Apr 04, 2024 |
| ANGXUN        | X99 V1.0                    | Desktop     | [e99eee7fa6](https://linux-hardware.org/?probe=e99eee7fa6) | Apr 03, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ea9c66f246](https://linux-hardware.org/?probe=ea9c66f246) | Apr 03, 2024 |
| MSI           | GF65 Thin 10UE              | Notebook    | [92304837ec](https://linux-hardware.org/?probe=92304837ec) | Apr 03, 2024 |
| ASRock        | B650M Pro RS                | Desktop     | [115bed720d](https://linux-hardware.org/?probe=115bed720d) | Apr 02, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d2f236e563](https://linux-hardware.org/?probe=d2f236e563) | Apr 02, 2024 |
| Alienware     | 17 R4                       | Notebook    | [0c83302e22](https://linux-hardware.org/?probe=0c83302e22) | Apr 02, 2024 |
| ANGXUN        | X99 V1.0                    | Desktop     | [4c7df42efb](https://linux-hardware.org/?probe=4c7df42efb) | Apr 01, 2024 |
| ASUSTek       | Rampage IV BLACK EDITION    | Desktop     | [519130fe28](https://linux-hardware.org/?probe=519130fe28) | Apr 01, 2024 |
| ASUSTek       | Rampage IV BLACK EDITION    | Desktop     | [daddb2bc79](https://linux-hardware.org/?probe=daddb2bc79) | Mar 31, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4eaa4702ec](https://linux-hardware.org/?probe=4eaa4702ec) | Mar 31, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [55199df248](https://linux-hardware.org/?probe=55199df248) | Mar 31, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [67f6104365](https://linux-hardware.org/?probe=67f6104365) | Mar 30, 2024 |
| ASRock        | B550 Steel Legend           | Desktop     | [80bcca8e5b](https://linux-hardware.org/?probe=80bcca8e5b) | Mar 30, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [5750434b60](https://linux-hardware.org/?probe=5750434b60) | Mar 30, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [7d992f4daa](https://linux-hardware.org/?probe=7d992f4daa) | Mar 29, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [12ae68d7a3](https://linux-hardware.org/?probe=12ae68d7a3) | Mar 29, 2024 |
| Dell          | Inspiron 1750               | Notebook    | [0c73b8ab73](https://linux-hardware.org/?probe=0c73b8ab73) | Mar 29, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [b629da0749](https://linux-hardware.org/?probe=b629da0749) | Mar 28, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d689049633](https://linux-hardware.org/?probe=d689049633) | Mar 28, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ff9042cc68](https://linux-hardware.org/?probe=ff9042cc68) | Mar 28, 2024 |
| Gigabyte      | H81M-HD3                    | Desktop     | [af704cb4f0](https://linux-hardware.org/?probe=af704cb4f0) | Mar 28, 2024 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [0d5d136c74](https://linux-hardware.org/?probe=0d5d136c74) | Mar 27, 2024 |
| Dell          | 0YC03K A04                  | Desktop     | [5f8bc97385](https://linux-hardware.org/?probe=5f8bc97385) | Mar 27, 2024 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [63eb2889bf](https://linux-hardware.org/?probe=63eb2889bf) | Mar 26, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 3 2... | Notebook    | [6ddc89666f](https://linux-hardware.org/?probe=6ddc89666f) | Mar 26, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c9687678aa](https://linux-hardware.org/?probe=c9687678aa) | Mar 25, 2024 |
| AWOW          | AiBook 10                   | Tablet      | [0d7ddf1922](https://linux-hardware.org/?probe=0d7ddf1922) | Mar 25, 2024 |
| THUNDEROBO... | 911 Plus                    | Notebook    | [26658bfa2e](https://linux-hardware.org/?probe=26658bfa2e) | Mar 25, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d45555c1f3](https://linux-hardware.org/?probe=d45555c1f3) | Mar 25, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [9599687d82](https://linux-hardware.org/?probe=9599687d82) | Mar 25, 2024 |
| Dell          | Latitude 3120               | Notebook    | [82d08cfae1](https://linux-hardware.org/?probe=82d08cfae1) | Mar 25, 2024 |
| Notebook      | W330SU2                     | Notebook    | [5228fe58bf](https://linux-hardware.org/?probe=5228fe58bf) | Mar 24, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [75f9128122](https://linux-hardware.org/?probe=75f9128122) | Mar 24, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [e6a2094088](https://linux-hardware.org/?probe=e6a2094088) | Mar 24, 2024 |
| NZXT          | N5 Z690                     | Desktop     | [53116e0b19](https://linux-hardware.org/?probe=53116e0b19) | Mar 24, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1f2ecd5d21](https://linux-hardware.org/?probe=1f2ecd5d21) | Mar 24, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [ae288e9605](https://linux-hardware.org/?probe=ae288e9605) | Mar 23, 2024 |
| Shenzhen M... | F7BAA                       | Desktop     | [f304a949e9](https://linux-hardware.org/?probe=f304a949e9) | Mar 23, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [59e0f44e00](https://linux-hardware.org/?probe=59e0f44e00) | Mar 23, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [99f9849b94](https://linux-hardware.org/?probe=99f9849b94) | Mar 23, 2024 |
| HP            | 1497                        | Desktop     | [6400d7689a](https://linux-hardware.org/?probe=6400d7689a) | Mar 23, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [ebc7895287](https://linux-hardware.org/?probe=ebc7895287) | Mar 23, 2024 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [42607732cf](https://linux-hardware.org/?probe=42607732cf) | Mar 23, 2024 |
| ASUSTek       | P8H77-M                     | Desktop     | [86485df1b9](https://linux-hardware.org/?probe=86485df1b9) | Mar 22, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [488589d270](https://linux-hardware.org/?probe=488589d270) | Mar 22, 2024 |
| Apple         | MacBookAir8,1               | Notebook    | [d0c0446bb2](https://linux-hardware.org/?probe=d0c0446bb2) | Mar 19, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [cb3904b8ec](https://linux-hardware.org/?probe=cb3904b8ec) | Mar 19, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5b8baf227c](https://linux-hardware.org/?probe=5b8baf227c) | Mar 18, 2024 |
| Acer          | TM8573T                     | Notebook    | [f60d5f0213](https://linux-hardware.org/?probe=f60d5f0213) | Mar 18, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [a66baca0b3](https://linux-hardware.org/?probe=a66baca0b3) | Mar 17, 2024 |
| Lenovo        | ThinkCentre M91p 4480A5U    | Desktop     | [cf0e48482f](https://linux-hardware.org/?probe=cf0e48482f) | Mar 16, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c05fb5669f](https://linux-hardware.org/?probe=c05fb5669f) | Mar 15, 2024 |
| MSI           | B560M BOMBER                | Desktop     | [e3c62a717e](https://linux-hardware.org/?probe=e3c62a717e) | Mar 14, 2024 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [0abdf7ee8f](https://linux-hardware.org/?probe=0abdf7ee8f) | Mar 14, 2024 |
| HP            | 8767 A                      | Desktop     | [ec0ecfe148](https://linux-hardware.org/?probe=ec0ecfe148) | Mar 14, 2024 |
| Shenzhen M... | F7BAA                       | Desktop     | [331d8bfd8d](https://linux-hardware.org/?probe=331d8bfd8d) | Mar 13, 2024 |
| MSI           | Z87-G45 GAMING              | Desktop     | [6a52290a2c](https://linux-hardware.org/?probe=6a52290a2c) | Mar 10, 2024 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [1b8c43466f](https://linux-hardware.org/?probe=1b8c43466f) | Mar 09, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [34dc8eb985](https://linux-hardware.org/?probe=34dc8eb985) | Mar 09, 2024 |
| Genuine       | ZEUS 15H (GNB15H-9G650)     | Notebook    | [1cdfbc79db](https://linux-hardware.org/?probe=1cdfbc79db) | Mar 09, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [367cca2568](https://linux-hardware.org/?probe=367cca2568) | Mar 07, 2024 |
| Acer          | Veriton N4680G              | Desktop     | [56c46ab94d](https://linux-hardware.org/?probe=56c46ab94d) | Mar 07, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [4e9cbe8d8c](https://linux-hardware.org/?probe=4e9cbe8d8c) | Mar 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [3c51a5f5ed](https://linux-hardware.org/?probe=3c51a5f5ed) | Mar 06, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1fc0257c17](https://linux-hardware.org/?probe=1fc0257c17) | Mar 05, 2024 |
| HP            | 14                          | Notebook    | [6e6138e521](https://linux-hardware.org/?probe=6e6138e521) | Mar 04, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [c7f6639bd8](https://linux-hardware.org/?probe=c7f6639bd8) | Mar 04, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [706ffb75c7](https://linux-hardware.org/?probe=706ffb75c7) | Mar 04, 2024 |
| ASRock        | Z790 PG SONIC               | Desktop     | [294db77884](https://linux-hardware.org/?probe=294db77884) | Mar 04, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [bb92efd03f](https://linux-hardware.org/?probe=bb92efd03f) | Mar 03, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [20b84b5546](https://linux-hardware.org/?probe=20b84b5546) | Mar 03, 2024 |
| Dell          | Latitude 3540               | Notebook    | [bec924d898](https://linux-hardware.org/?probe=bec924d898) | Mar 02, 2024 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [3a49dcc141](https://linux-hardware.org/?probe=3a49dcc141) | Mar 02, 2024 |
| MSI           | MEG Z790 ACE                | Desktop     | [fe820e6252](https://linux-hardware.org/?probe=fe820e6252) | Mar 02, 2024 |
| MSI           | MEG Z790 ACE                | Desktop     | [ec9f9ed05d](https://linux-hardware.org/?probe=ec9f9ed05d) | Mar 02, 2024 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [f170401477](https://linux-hardware.org/?probe=f170401477) | Mar 01, 2024 |
| Biostar       | B550MX/E PRO                | Desktop     | [b5621fd04d](https://linux-hardware.org/?probe=b5621fd04d) | Mar 01, 2024 |
| HP            | Pavilion 15                 | Notebook    | [15858caed0](https://linux-hardware.org/?probe=15858caed0) | Mar 01, 2024 |
| ASUSTek       | G73Sw                       | Notebook    | [4587c66de2](https://linux-hardware.org/?probe=4587c66de2) | Mar 01, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | Notebook    | [fd1c373201](https://linux-hardware.org/?probe=fd1c373201) | Mar 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [120d90cd85](https://linux-hardware.org/?probe=120d90cd85) | Mar 01, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [08024a8cef](https://linux-hardware.org/?probe=08024a8cef) | Mar 01, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f95d07fbe2](https://linux-hardware.org/?probe=f95d07fbe2) | Mar 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [aabae1e88f](https://linux-hardware.org/?probe=aabae1e88f) | Mar 01, 2024 |
| ASUSTek       | G73Sw                       | Notebook    | [3605d5ddc7](https://linux-hardware.org/?probe=3605d5ddc7) | Mar 01, 2024 |
| HP            | 87D6 SMVB                   | Desktop     | [0f6fe5731d](https://linux-hardware.org/?probe=0f6fe5731d) | Feb 29, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | Notebook    | [18a5671738](https://linux-hardware.org/?probe=18a5671738) | Feb 29, 2024 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [d09ab79296](https://linux-hardware.org/?probe=d09ab79296) | Feb 29, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [565e6c2d46](https://linux-hardware.org/?probe=565e6c2d46) | Feb 29, 2024 |
| Gigabyte      | B85M-D3H                    | Notebook    | [dbbdc72e8a](https://linux-hardware.org/?probe=dbbdc72e8a) | Feb 27, 2024 |
| Medion        | Z370H4-EM                   | Desktop     | [4eb64de4c6](https://linux-hardware.org/?probe=4eb64de4c6) | Feb 27, 2024 |
| MSI           | B560M BOMBER                | Desktop     | [51d0000eeb](https://linux-hardware.org/?probe=51d0000eeb) | Feb 26, 2024 |
| Dell          | Latitude E5470              | Notebook    | [10ab411f6f](https://linux-hardware.org/?probe=10ab411f6f) | Feb 25, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [3015e2635f](https://linux-hardware.org/?probe=3015e2635f) | Feb 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [987f6afe4b](https://linux-hardware.org/?probe=987f6afe4b) | Feb 25, 2024 |
| AWOW          | AiBook 10                   | Tablet      | [07372d2796](https://linux-hardware.org/?probe=07372d2796) | Feb 24, 2024 |
| HP            | ProBook 470 G1              | Notebook    | [2ad493fb2d](https://linux-hardware.org/?probe=2ad493fb2d) | Feb 24, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [e0a472d706](https://linux-hardware.org/?probe=e0a472d706) | Feb 24, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [dfae4c4596](https://linux-hardware.org/?probe=dfae4c4596) | Feb 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3b3a145c76](https://linux-hardware.org/?probe=3b3a145c76) | Feb 23, 2024 |
| Acer          | Aspire VN7-592G             | Notebook    | [dd6617c3d7](https://linux-hardware.org/?probe=dd6617c3d7) | Feb 23, 2024 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [6a3f5e5947](https://linux-hardware.org/?probe=6a3f5e5947) | Feb 23, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [98fae51a1e](https://linux-hardware.org/?probe=98fae51a1e) | Feb 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [da357b8940](https://linux-hardware.org/?probe=da357b8940) | Feb 22, 2024 |
| ASRock        | H610M-HDV/M.2+ D5           | Desktop     | [234e2e9bb4](https://linux-hardware.org/?probe=234e2e9bb4) | Feb 21, 2024 |
| Acer          | Nitro AN517-52              | Notebook    | [a5af54a5aa](https://linux-hardware.org/?probe=a5af54a5aa) | Feb 20, 2024 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [51d0c3c66c](https://linux-hardware.org/?probe=51d0c3c66c) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d63b912feb](https://linux-hardware.org/?probe=d63b912feb) | Feb 19, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [710c281afe](https://linux-hardware.org/?probe=710c281afe) | Feb 19, 2024 |
| MSI           | Bravo 15 C7VF               | Notebook    | [82ee626dbd](https://linux-hardware.org/?probe=82ee626dbd) | Feb 19, 2024 |
| BESSTAR Te... | B550                        | Desktop     | [3404bc2a3f](https://linux-hardware.org/?probe=3404bc2a3f) | Feb 19, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [9ca137827d](https://linux-hardware.org/?probe=9ca137827d) | Feb 19, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e138126881](https://linux-hardware.org/?probe=e138126881) | Feb 18, 2024 |
| Dell          | 00F82W A01                  | Desktop     | [5c6a47036f](https://linux-hardware.org/?probe=5c6a47036f) | Feb 18, 2024 |
| Acer          | Aspire ES1-572              | Notebook    | [7c61f04e95](https://linux-hardware.org/?probe=7c61f04e95) | Feb 18, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [af374b16e0](https://linux-hardware.org/?probe=af374b16e0) | Feb 18, 2024 |
| Gigabyte      | B560 HD3                    | Desktop     | [37705691a2](https://linux-hardware.org/?probe=37705691a2) | Feb 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [a3e402d181](https://linux-hardware.org/?probe=a3e402d181) | Feb 17, 2024 |
| ASRock        | B550 Steel Legend           | Desktop     | [e8cd748b8b](https://linux-hardware.org/?probe=e8cd748b8b) | Feb 16, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [f5476226be](https://linux-hardware.org/?probe=f5476226be) | Feb 15, 2024 |
| Dell          | Precision M4800             | Notebook    | [c5630bb66f](https://linux-hardware.org/?probe=c5630bb66f) | Feb 15, 2024 |
| Infinix       | INBOOK X2 PLUS              | Notebook    | [ef58804464](https://linux-hardware.org/?probe=ef58804464) | Feb 15, 2024 |
| Infinix       | INBOOK X2 PLUS              | Notebook    | [bf574e4c09](https://linux-hardware.org/?probe=bf574e4c09) | Feb 15, 2024 |
| Intel         | X79G V2.x                   | Desktop     | [077f5b4397](https://linux-hardware.org/?probe=077f5b4397) | Feb 15, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [cf602689fb](https://linux-hardware.org/?probe=cf602689fb) | Feb 14, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [531e1ffb52](https://linux-hardware.org/?probe=531e1ffb52) | Feb 14, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [1edc94c98a](https://linux-hardware.org/?probe=1edc94c98a) | Feb 14, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [85ad12404c](https://linux-hardware.org/?probe=85ad12404c) | Feb 14, 2024 |
| Acer          | Aspire A115-31              | Notebook    | [118a35f68d](https://linux-hardware.org/?probe=118a35f68d) | Feb 13, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [340060f3d6](https://linux-hardware.org/?probe=340060f3d6) | Feb 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [8cab6ebd29](https://linux-hardware.org/?probe=8cab6ebd29) | Feb 12, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [5d7a35b7b3](https://linux-hardware.org/?probe=5d7a35b7b3) | Feb 12, 2024 |
| HP            | Compaq 615                  | Notebook    | [1761631f89](https://linux-hardware.org/?probe=1761631f89) | Feb 11, 2024 |
| Acer          | TravelMate 7520             | Notebook    | [2cdca7160b](https://linux-hardware.org/?probe=2cdca7160b) | Feb 11, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [526bbe59b5](https://linux-hardware.org/?probe=526bbe59b5) | Feb 11, 2024 |
| HP            | 1850                        | Desktop     | [5c07678884](https://linux-hardware.org/?probe=5c07678884) | Feb 11, 2024 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [9b3e403b41](https://linux-hardware.org/?probe=9b3e403b41) | Feb 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP36... | Convertible | [5db23f0711](https://linux-hardware.org/?probe=5db23f0711) | Feb 10, 2024 |
| ASRock        | Z790 Taichi Lite            | Desktop     | [4e10886ed9](https://linux-hardware.org/?probe=4e10886ed9) | Feb 10, 2024 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [dbf87ca96b](https://linux-hardware.org/?probe=dbf87ca96b) | Feb 10, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c5bef6b5e1](https://linux-hardware.org/?probe=c5bef6b5e1) | Feb 10, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e5f7545d74](https://linux-hardware.org/?probe=e5f7545d74) | Feb 09, 2024 |
| HP            | 3397                        | Desktop     | [a90269d4c8](https://linux-hardware.org/?probe=a90269d4c8) | Feb 09, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e1a5930765](https://linux-hardware.org/?probe=e1a5930765) | Feb 08, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [047b50329c](https://linux-hardware.org/?probe=047b50329c) | Feb 08, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9b330fa0a0](https://linux-hardware.org/?probe=9b330fa0a0) | Feb 08, 2024 |
| HP            | 89E9 0100                   | All in one  | [095148606c](https://linux-hardware.org/?probe=095148606c) | Feb 08, 2024 |
| AZW           | U59                         | Desktop     | [3671f5a1e2](https://linux-hardware.org/?probe=3671f5a1e2) | Feb 08, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4839a7f4fd](https://linux-hardware.org/?probe=4839a7f4fd) | Feb 07, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d0aeeebc1e](https://linux-hardware.org/?probe=d0aeeebc1e) | Feb 07, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f2f39a59eb](https://linux-hardware.org/?probe=f2f39a59eb) | Feb 07, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [9ceb699fc1](https://linux-hardware.org/?probe=9ceb699fc1) | Feb 07, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [021c8aa71a](https://linux-hardware.org/?probe=021c8aa71a) | Feb 07, 2024 |
| ASUSTek       | ROG Flow X13 GV302XA_GV3... | Convertible | [003f33d98f](https://linux-hardware.org/?probe=003f33d98f) | Feb 07, 2024 |
| Dell          | Precision M4800             | Notebook    | [8b1cccf4c2](https://linux-hardware.org/?probe=8b1cccf4c2) | Feb 07, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8362b7c055](https://linux-hardware.org/?probe=8362b7c055) | Feb 06, 2024 |
| Gigabyte      | A520M DS3H                  | Desktop     | [84c4c9b306](https://linux-hardware.org/?probe=84c4c9b306) | Feb 06, 2024 |
| Gigabyte      | B560 HD3                    | Desktop     | [40dfc4b884](https://linux-hardware.org/?probe=40dfc4b884) | Feb 06, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [b04a151ae2](https://linux-hardware.org/?probe=b04a151ae2) | Feb 06, 2024 |
| Gigabyte      | EP43-S3L                    | Desktop     | [57175cc482](https://linux-hardware.org/?probe=57175cc482) | Feb 06, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [848a81b0ad](https://linux-hardware.org/?probe=848a81b0ad) | Feb 04, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2b1d61e309](https://linux-hardware.org/?probe=2b1d61e309) | Feb 04, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [ef9f082a81](https://linux-hardware.org/?probe=ef9f082a81) | Feb 03, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d2b295447b](https://linux-hardware.org/?probe=d2b295447b) | Feb 03, 2024 |
| HP            | 1497                        | Desktop     | [97d05336ec](https://linux-hardware.org/?probe=97d05336ec) | Feb 03, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [87f113db8c](https://linux-hardware.org/?probe=87f113db8c) | Feb 03, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [251ceb1f00](https://linux-hardware.org/?probe=251ceb1f00) | Feb 03, 2024 |
| Toshiba       | Satellite L55-C             | Notebook    | [f32d9dc51a](https://linux-hardware.org/?probe=f32d9dc51a) | Feb 02, 2024 |
| Acer          | Aspire A315-54              | Notebook    | [3621142f4d](https://linux-hardware.org/?probe=3621142f4d) | Feb 02, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d4c61a6527](https://linux-hardware.org/?probe=d4c61a6527) | Feb 01, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [f708da8a98](https://linux-hardware.org/?probe=f708da8a98) | Feb 01, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [8b5fd80f76](https://linux-hardware.org/?probe=8b5fd80f76) | Feb 01, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [31fc253b87](https://linux-hardware.org/?probe=31fc253b87) | Feb 01, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [52f18f604d](https://linux-hardware.org/?probe=52f18f604d) | Feb 01, 2024 |
| Intel         | B75                         | Desktop     | [000ad7f808](https://linux-hardware.org/?probe=000ad7f808) | Jan 31, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [02a1844f63](https://linux-hardware.org/?probe=02a1844f63) | Jan 31, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [cfd7031cd9](https://linux-hardware.org/?probe=cfd7031cd9) | Jan 31, 2024 |
| MSI           | GE62 6QE                    | Notebook    | [6d6f9ba002](https://linux-hardware.org/?probe=6d6f9ba002) | Jan 30, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [df2c10b408](https://linux-hardware.org/?probe=df2c10b408) | Jan 29, 2024 |
| HP            | 1497                        | Desktop     | [edbda38746](https://linux-hardware.org/?probe=edbda38746) | Jan 29, 2024 |
| HP            | 212B                        | Desktop     | [fb3993d66a](https://linux-hardware.org/?probe=fb3993d66a) | Jan 28, 2024 |
| NZXT          | N7 B650E                    | Desktop     | [2a31518f97](https://linux-hardware.org/?probe=2a31518f97) | Jan 28, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a85c3034f2](https://linux-hardware.org/?probe=a85c3034f2) | Jan 27, 2024 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [88efa5aca1](https://linux-hardware.org/?probe=88efa5aca1) | Jan 27, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [68364930e7](https://linux-hardware.org/?probe=68364930e7) | Jan 27, 2024 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [96bce63bad](https://linux-hardware.org/?probe=96bce63bad) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [c1267550bc](https://linux-hardware.org/?probe=c1267550bc) | Jan 27, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [531cd352a8](https://linux-hardware.org/?probe=531cd352a8) | Jan 27, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [840164bd48](https://linux-hardware.org/?probe=840164bd48) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [30139ed46d](https://linux-hardware.org/?probe=30139ed46d) | Jan 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [9e979ee4e4](https://linux-hardware.org/?probe=9e979ee4e4) | Jan 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [3e9fd3e31a](https://linux-hardware.org/?probe=3e9fd3e31a) | Jan 26, 2024 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [13a3740810](https://linux-hardware.org/?probe=13a3740810) | Jan 26, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [04feb5fc7d](https://linux-hardware.org/?probe=04feb5fc7d) | Jan 26, 2024 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [cb67574020](https://linux-hardware.org/?probe=cb67574020) | Jan 26, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | Notebook    | [ec87598c40](https://linux-hardware.org/?probe=ec87598c40) | Jan 26, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [e6dfa57418](https://linux-hardware.org/?probe=e6dfa57418) | Jan 26, 2024 |
| ASRock        | Z97 Anniversary             | Desktop     | [0973057025](https://linux-hardware.org/?probe=0973057025) | Jan 25, 2024 |
| NZXT          | N7 B650E                    | Desktop     | [9354117703](https://linux-hardware.org/?probe=9354117703) | Jan 25, 2024 |
| HP            | Laptop 17z-cp000            | Notebook    | [51e7d942bc](https://linux-hardware.org/?probe=51e7d942bc) | Jan 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [871f86a545](https://linux-hardware.org/?probe=871f86a545) | Jan 21, 2024 |
| Pegatron      | 2AB6                        | Desktop     | [660b2b76ed](https://linux-hardware.org/?probe=660b2b76ed) | Jan 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f7ebff5e4f](https://linux-hardware.org/?probe=f7ebff5e4f) | Jan 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e07a558ed5](https://linux-hardware.org/?probe=e07a558ed5) | Jan 20, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [12e32cbc19](https://linux-hardware.org/?probe=12e32cbc19) | Jan 19, 2024 |
| Gigabyte      | A5 K1                       | Notebook    | [219882fa36](https://linux-hardware.org/?probe=219882fa36) | Jan 19, 2024 |
| Gigabyte      | A5 K1                       | Notebook    | [2270b0b961](https://linux-hardware.org/?probe=2270b0b961) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [96aa415cee](https://linux-hardware.org/?probe=96aa415cee) | Jan 18, 2024 |
| Lenovo        | ThinkPad X131e 3371AF5      | Notebook    | [1741e3b346](https://linux-hardware.org/?probe=1741e3b346) | Jan 18, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d732f80c75](https://linux-hardware.org/?probe=d732f80c75) | Jan 18, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [195a26ad26](https://linux-hardware.org/?probe=195a26ad26) | Jan 17, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b4bb61edfe](https://linux-hardware.org/?probe=b4bb61edfe) | Jan 17, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [781a81dea6](https://linux-hardware.org/?probe=781a81dea6) | Jan 17, 2024 |
| MSI           | Z170-A PRO                  | Desktop     | [bcf19edc1d](https://linux-hardware.org/?probe=bcf19edc1d) | Jan 16, 2024 |
| ASUSTek       | Q87M-E                      | Desktop     | [318aab51d9](https://linux-hardware.org/?probe=318aab51d9) | Jan 15, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c8e849a73](https://linux-hardware.org/?probe=0c8e849a73) | Jan 15, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [3ea676a743](https://linux-hardware.org/?probe=3ea676a743) | Jan 14, 2024 |
| Dell          | 0DYHRY A00                  | Desktop     | [d605dd9a8a](https://linux-hardware.org/?probe=d605dd9a8a) | Jan 14, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [7cccdf824c](https://linux-hardware.org/?probe=7cccdf824c) | Jan 13, 2024 |
| ASRock        | Z97M Pro4                   | Desktop     | [594754cd87](https://linux-hardware.org/?probe=594754cd87) | Jan 13, 2024 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [a3bc588c07](https://linux-hardware.org/?probe=a3bc588c07) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [23c4e3e208](https://linux-hardware.org/?probe=23c4e3e208) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b98091e5e6](https://linux-hardware.org/?probe=b98091e5e6) | Jan 13, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e3c1908003](https://linux-hardware.org/?probe=e3c1908003) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [1b25ee0779](https://linux-hardware.org/?probe=1b25ee0779) | Jan 13, 2024 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [e1560ce8a3](https://linux-hardware.org/?probe=e1560ce8a3) | Jan 13, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | Notebook    | [e4f7fe0969](https://linux-hardware.org/?probe=e4f7fe0969) | Jan 13, 2024 |
| ASRock        | X570 Steel Legend           | Notebook    | [2dc1dca01f](https://linux-hardware.org/?probe=2dc1dca01f) | Jan 13, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [bcbcc04761](https://linux-hardware.org/?probe=bcbcc04761) | Jan 13, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5de7f8ed8](https://linux-hardware.org/?probe=e5de7f8ed8) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [daefd59105](https://linux-hardware.org/?probe=daefd59105) | Jan 13, 2024 |
| Intel         | X79G V2.x                   | Desktop     | [cf61b1759b](https://linux-hardware.org/?probe=cf61b1759b) | Jan 12, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [5f11aaf980](https://linux-hardware.org/?probe=5f11aaf980) | Jan 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8e72c34b9e](https://linux-hardware.org/?probe=8e72c34b9e) | Jan 11, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b0705704b0](https://linux-hardware.org/?probe=b0705704b0) | Jan 11, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [2a5022eba4](https://linux-hardware.org/?probe=2a5022eba4) | Jan 11, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [7c77830f2f](https://linux-hardware.org/?probe=7c77830f2f) | Jan 10, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [03202bdde9](https://linux-hardware.org/?probe=03202bdde9) | Jan 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0df1250b28](https://linux-hardware.org/?probe=0df1250b28) | Jan 10, 2024 |
| Intel         | NUC11PABi5 M68265-400       | Mini pc     | [f6c6a9ba46](https://linux-hardware.org/?probe=f6c6a9ba46) | Jan 10, 2024 |
| ASUSTek       | G10DK                       | Desktop     | [7339bf1ed8](https://linux-hardware.org/?probe=7339bf1ed8) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9cfcebcd8c](https://linux-hardware.org/?probe=9cfcebcd8c) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [0306a42404](https://linux-hardware.org/?probe=0306a42404) | Jan 09, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e1d9aaa0f2](https://linux-hardware.org/?probe=e1d9aaa0f2) | Jan 09, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [cd8ee8db1f](https://linux-hardware.org/?probe=cd8ee8db1f) | Jan 09, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [fc9099926d](https://linux-hardware.org/?probe=fc9099926d) | Jan 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [91485ca232](https://linux-hardware.org/?probe=91485ca232) | Jan 09, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ce4125a4f0](https://linux-hardware.org/?probe=ce4125a4f0) | Jan 09, 2024 |
| Dell          | Latitude E6440              | Notebook    | [bb917628b1](https://linux-hardware.org/?probe=bb917628b1) | Jan 09, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [513efe6ed6](https://linux-hardware.org/?probe=513efe6ed6) | Jan 09, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | Notebook    | [9ff97bbae7](https://linux-hardware.org/?probe=9ff97bbae7) | Jan 09, 2024 |
| HP            | 8054                        | Desktop     | [94be81d143](https://linux-hardware.org/?probe=94be81d143) | Jan 08, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [d9dc289509](https://linux-hardware.org/?probe=d9dc289509) | Jan 08, 2024 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [48871db703](https://linux-hardware.org/?probe=48871db703) | Jan 08, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [1c83544337](https://linux-hardware.org/?probe=1c83544337) | Jan 08, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [4e246bdbaa](https://linux-hardware.org/?probe=4e246bdbaa) | Jan 07, 2024 |
| Alienware     | 0P0JWX A00                  | Desktop     | [47bd2f6e34](https://linux-hardware.org/?probe=47bd2f6e34) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [ea0e1750c9](https://linux-hardware.org/?probe=ea0e1750c9) | Jan 06, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [6a8402b6a7](https://linux-hardware.org/?probe=6a8402b6a7) | Jan 06, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | Notebook    | [b753b7e847](https://linux-hardware.org/?probe=b753b7e847) | Jan 06, 2024 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [c16b44c1ce](https://linux-hardware.org/?probe=c16b44c1ce) | Jan 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7f28dd699b](https://linux-hardware.org/?probe=7f28dd699b) | Jan 06, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [6ced1e30f9](https://linux-hardware.org/?probe=6ced1e30f9) | Jan 06, 2024 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [009c5330a2](https://linux-hardware.org/?probe=009c5330a2) | Jan 06, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [56df310601](https://linux-hardware.org/?probe=56df310601) | Jan 06, 2024 |
| HP            | 83E1                        | Desktop     | [d3f2371283](https://linux-hardware.org/?probe=d3f2371283) | Jan 05, 2024 |
| Dell          | G7 7700                     | Notebook    | [126b71c515](https://linux-hardware.org/?probe=126b71c515) | Jan 05, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [6971ec53cd](https://linux-hardware.org/?probe=6971ec53cd) | Jan 05, 2024 |
| ASRock        | H61M                        | Desktop     | [e4a7c28d85](https://linux-hardware.org/?probe=e4a7c28d85) | Jan 04, 2024 |
| Notebook      | P7xxTM1                     | Notebook    | [9ed3be2a69](https://linux-hardware.org/?probe=9ed3be2a69) | Jan 04, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [42e67a91b0](https://linux-hardware.org/?probe=42e67a91b0) | Jan 04, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bb19b91823](https://linux-hardware.org/?probe=bb19b91823) | Jan 04, 2024 |
| Dell          | 0MG0RG A00                  | Desktop     | [f3847b13ce](https://linux-hardware.org/?probe=f3847b13ce) | Jan 04, 2024 |
| Acer          | Aspire A315-54              | Notebook    | [50c718d2c6](https://linux-hardware.org/?probe=50c718d2c6) | Jan 04, 2024 |
| ASUSTek       | Q500A                       | Notebook    | [c3f961d8be](https://linux-hardware.org/?probe=c3f961d8be) | Jan 03, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [fb4e22f4a6](https://linux-hardware.org/?probe=fb4e22f4a6) | Jan 03, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f10936a9f7](https://linux-hardware.org/?probe=f10936a9f7) | Jan 02, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2ae0bbe734](https://linux-hardware.org/?probe=2ae0bbe734) | Jan 01, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [f0cb030b5f](https://linux-hardware.org/?probe=f0cb030b5f) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e1c9fdb53b](https://linux-hardware.org/?probe=e1c9fdb53b) | Dec 31, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [96395212e8](https://linux-hardware.org/?probe=96395212e8) | Dec 31, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2f69bdfbc7](https://linux-hardware.org/?probe=2f69bdfbc7) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | Notebook    | [8cb3a2ee0a](https://linux-hardware.org/?probe=8cb3a2ee0a) | Dec 30, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [85c8033229](https://linux-hardware.org/?probe=85c8033229) | Dec 30, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ebdb840dba](https://linux-hardware.org/?probe=ebdb840dba) | Dec 30, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [bacd120c51](https://linux-hardware.org/?probe=bacd120c51) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | Notebook    | [274f6e86fc](https://linux-hardware.org/?probe=274f6e86fc) | Dec 29, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [3729a3492e](https://linux-hardware.org/?probe=3729a3492e) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [988bd71a05](https://linux-hardware.org/?probe=988bd71a05) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [9f85581cdb](https://linux-hardware.org/?probe=9f85581cdb) | Dec 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [6b98d84cb0](https://linux-hardware.org/?probe=6b98d84cb0) | Dec 28, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [754b2e0faf](https://linux-hardware.org/?probe=754b2e0faf) | Dec 27, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [be356bc929](https://linux-hardware.org/?probe=be356bc929) | Dec 27, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [aa60bdb2cb](https://linux-hardware.org/?probe=aa60bdb2cb) | Dec 27, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ce4c03fbee](https://linux-hardware.org/?probe=ce4c03fbee) | Dec 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e1bbb2ee71](https://linux-hardware.org/?probe=e1bbb2ee71) | Dec 26, 2023 |
| HP            | 8767 A                      | Desktop     | [6d2a367189](https://linux-hardware.org/?probe=6d2a367189) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5cc2120efc](https://linux-hardware.org/?probe=5cc2120efc) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6bcc868ad6](https://linux-hardware.org/?probe=6bcc868ad6) | Dec 25, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [b00112da41](https://linux-hardware.org/?probe=b00112da41) | Dec 24, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [64a00841b2](https://linux-hardware.org/?probe=64a00841b2) | Dec 23, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [4adc5f3f81](https://linux-hardware.org/?probe=4adc5f3f81) | Dec 22, 2023 |
| Alienware     | 0P0JWX A00                  | Desktop     | [99d0e56ef1](https://linux-hardware.org/?probe=99d0e56ef1) | Dec 22, 2023 |
| HP            | 83E0                        | Desktop     | [07e6f563f9](https://linux-hardware.org/?probe=07e6f563f9) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [18788fe1ea](https://linux-hardware.org/?probe=18788fe1ea) | Dec 22, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [58a2ef76f9](https://linux-hardware.org/?probe=58a2ef76f9) | Dec 22, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [1a4d75f062](https://linux-hardware.org/?probe=1a4d75f062) | Dec 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4b1991c655](https://linux-hardware.org/?probe=4b1991c655) | Dec 21, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [4e3b422400](https://linux-hardware.org/?probe=4e3b422400) | Dec 19, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [925bd9bbac](https://linux-hardware.org/?probe=925bd9bbac) | Dec 19, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [1cd7c1b629](https://linux-hardware.org/?probe=1cd7c1b629) | Dec 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [15decf2dfc](https://linux-hardware.org/?probe=15decf2dfc) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c2a8ace4dd](https://linux-hardware.org/?probe=c2a8ace4dd) | Dec 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [8a69294494](https://linux-hardware.org/?probe=8a69294494) | Dec 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ec58c18087](https://linux-hardware.org/?probe=ec58c18087) | Dec 17, 2023 |
| Acer          | Aspire A515-56T             | Notebook    | [9579acc8a0](https://linux-hardware.org/?probe=9579acc8a0) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF                  | Desktop     | [cdf7a1ffd4](https://linux-hardware.org/?probe=cdf7a1ffd4) | Dec 15, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [93e9419d49](https://linux-hardware.org/?probe=93e9419d49) | Dec 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [6855d17ce1](https://linux-hardware.org/?probe=6855d17ce1) | Dec 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5d1e9e6d47](https://linux-hardware.org/?probe=5d1e9e6d47) | Dec 13, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2c8846a637](https://linux-hardware.org/?probe=2c8846a637) | Dec 12, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [e17d6cbfa7](https://linux-hardware.org/?probe=e17d6cbfa7) | Dec 12, 2023 |
| Dell          | G7 7700                     | Notebook    | [9d4e191ab5](https://linux-hardware.org/?probe=9d4e191ab5) | Dec 12, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [68ba082c42](https://linux-hardware.org/?probe=68ba082c42) | Dec 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [f49dd0f010](https://linux-hardware.org/?probe=f49dd0f010) | Dec 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [dc0acbdb23](https://linux-hardware.org/?probe=dc0acbdb23) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [bc8d773d9d](https://linux-hardware.org/?probe=bc8d773d9d) | Dec 10, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [114391b743](https://linux-hardware.org/?probe=114391b743) | Dec 10, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [46be0f459d](https://linux-hardware.org/?probe=46be0f459d) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [04e25c9660](https://linux-hardware.org/?probe=04e25c9660) | Dec 10, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [e63d83327b](https://linux-hardware.org/?probe=e63d83327b) | Dec 09, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [d5d6865b7d](https://linux-hardware.org/?probe=d5d6865b7d) | Dec 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [ece705bc91](https://linux-hardware.org/?probe=ece705bc91) | Dec 09, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [158658e952](https://linux-hardware.org/?probe=158658e952) | Dec 08, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [3539ea142d](https://linux-hardware.org/?probe=3539ea142d) | Dec 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [9da65cd80e](https://linux-hardware.org/?probe=9da65cd80e) | Dec 07, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [acf5ffd938](https://linux-hardware.org/?probe=acf5ffd938) | Dec 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [5326fc7737](https://linux-hardware.org/?probe=5326fc7737) | Dec 06, 2023 |
| Dell          | G5 5505                     | Notebook    | [74d0a53db4](https://linux-hardware.org/?probe=74d0a53db4) | Dec 06, 2023 |
| Samsung       | 960QFG                      | Convertible | [42e5646709](https://linux-hardware.org/?probe=42e5646709) | Dec 06, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [f1ebc77dfc](https://linux-hardware.org/?probe=f1ebc77dfc) | Dec 05, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [3d56eb720e](https://linux-hardware.org/?probe=3d56eb720e) | Dec 05, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [110604e0da](https://linux-hardware.org/?probe=110604e0da) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [6cd3d66979](https://linux-hardware.org/?probe=6cd3d66979) | Dec 05, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [e1478d8694](https://linux-hardware.org/?probe=e1478d8694) | Dec 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [f1d29c75a0](https://linux-hardware.org/?probe=f1d29c75a0) | Dec 03, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [2787907c00](https://linux-hardware.org/?probe=2787907c00) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e9e31f8aaa](https://linux-hardware.org/?probe=e9e31f8aaa) | Dec 03, 2023 |
| HP            | 0B54h D                     | Desktop     | [bffc586a45](https://linux-hardware.org/?probe=bffc586a45) | Dec 02, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [4f3cfed57b](https://linux-hardware.org/?probe=4f3cfed57b) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a5997eb3f2](https://linux-hardware.org/?probe=a5997eb3f2) | Dec 02, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [0d5166b475](https://linux-hardware.org/?probe=0d5166b475) | Dec 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [f86124413d](https://linux-hardware.org/?probe=f86124413d) | Dec 01, 2023 |
| Acer          | Aspire E5-473               | Notebook    | [f3b2c01ef7](https://linux-hardware.org/?probe=f3b2c01ef7) | Dec 01, 2023 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [322ac1cb94](https://linux-hardware.org/?probe=322ac1cb94) | Dec 01, 2023 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [515d60d68e](https://linux-hardware.org/?probe=515d60d68e) | Dec 01, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [2eaa838401](https://linux-hardware.org/?probe=2eaa838401) | Nov 30, 2023 |
| Acer          | Veriton N4680G              | Desktop     | [033223b8bc](https://linux-hardware.org/?probe=033223b8bc) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6357a41a39](https://linux-hardware.org/?probe=6357a41a39) | Nov 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [37545bd915](https://linux-hardware.org/?probe=37545bd915) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d385ea9309](https://linux-hardware.org/?probe=d385ea9309) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [11d3e45e2d](https://linux-hardware.org/?probe=11d3e45e2d) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [d2dcb1f2da](https://linux-hardware.org/?probe=d2dcb1f2da) | Nov 29, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [b4fbd61258](https://linux-hardware.org/?probe=b4fbd61258) | Nov 28, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5509bd1ba](https://linux-hardware.org/?probe=e5509bd1ba) | Nov 28, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [a39fba5394](https://linux-hardware.org/?probe=a39fba5394) | Nov 27, 2023 |
| Google        | Kench                       | Desktop     | [efdf5874c1](https://linux-hardware.org/?probe=efdf5874c1) | Nov 27, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [ab44413728](https://linux-hardware.org/?probe=ab44413728) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| HP            | 8054                        | Desktop     | [dfa212d5da](https://linux-hardware.org/?probe=dfa212d5da) | Nov 25, 2023 |
| Dell          | Precision 7740              | Notebook    | [50b0f0be08](https://linux-hardware.org/?probe=50b0f0be08) | Nov 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0f9d912f7f](https://linux-hardware.org/?probe=0f9d912f7f) | Nov 24, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [4f1d1d579c](https://linux-hardware.org/?probe=4f1d1d579c) | Nov 24, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [c3b398c792](https://linux-hardware.org/?probe=c3b398c792) | Nov 24, 2023 |
| ASRock        | X370 Gaming X               | Notebook    | [0c39910834](https://linux-hardware.org/?probe=0c39910834) | Nov 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [0714d466f7](https://linux-hardware.org/?probe=0714d466f7) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [639c2b7832](https://linux-hardware.org/?probe=639c2b7832) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [1048b240d5](https://linux-hardware.org/?probe=1048b240d5) | Nov 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [74162bf452](https://linux-hardware.org/?probe=74162bf452) | Nov 19, 2023 |
| LG Electro... | 16Z90R-G.AD75F              | Notebook    | [83d650792f](https://linux-hardware.org/?probe=83d650792f) | Nov 18, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [db393353d9](https://linux-hardware.org/?probe=db393353d9) | Nov 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c00a7584bf](https://linux-hardware.org/?probe=c00a7584bf) | Nov 18, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [adf1b0c27a](https://linux-hardware.org/?probe=adf1b0c27a) | Nov 16, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [168e0af4e6](https://linux-hardware.org/?probe=168e0af4e6) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [ca5d20d4a4](https://linux-hardware.org/?probe=ca5d20d4a4) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [914e24f740](https://linux-hardware.org/?probe=914e24f740) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [aca7636589](https://linux-hardware.org/?probe=aca7636589) | Nov 16, 2023 |
| MSI           | GF62 8RC                    | Notebook    | [8e186cf8b9](https://linux-hardware.org/?probe=8e186cf8b9) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [7856865861](https://linux-hardware.org/?probe=7856865861) | Nov 16, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [0b039b15e7](https://linux-hardware.org/?probe=0b039b15e7) | Nov 15, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [b5e651a2bf](https://linux-hardware.org/?probe=b5e651a2bf) | Nov 15, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [038ffaab27](https://linux-hardware.org/?probe=038ffaab27) | Nov 13, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [f0db6bb1ae](https://linux-hardware.org/?probe=f0db6bb1ae) | Nov 11, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [99fa1c416d](https://linux-hardware.org/?probe=99fa1c416d) | Nov 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [404f1947fd](https://linux-hardware.org/?probe=404f1947fd) | Nov 11, 2023 |
| Microsoft     | Surface Book                | Tablet      | [67575d0e41](https://linux-hardware.org/?probe=67575d0e41) | Nov 08, 2023 |
| ASUSTek       | Q504UAK                     | Convertible | [177cde7808](https://linux-hardware.org/?probe=177cde7808) | Nov 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9f1e875996](https://linux-hardware.org/?probe=9f1e875996) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [993c65a274](https://linux-hardware.org/?probe=993c65a274) | Nov 06, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [615e914ddd](https://linux-hardware.org/?probe=615e914ddd) | Nov 05, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [7ba5de3dfd](https://linux-hardware.org/?probe=7ba5de3dfd) | Nov 05, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c17ad7033c](https://linux-hardware.org/?probe=c17ad7033c) | Nov 05, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [701314a2ff](https://linux-hardware.org/?probe=701314a2ff) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [12b6cd2d09](https://linux-hardware.org/?probe=12b6cd2d09) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [119816ea7d](https://linux-hardware.org/?probe=119816ea7d) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6d39c4f814](https://linux-hardware.org/?probe=6d39c4f814) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e928da88d7](https://linux-hardware.org/?probe=e928da88d7) | Nov 03, 2023 |
| Dell          | Precision 7740              | Notebook    | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [72a2946c83](https://linux-hardware.org/?probe=72a2946c83) | Nov 01, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [8161abddda](https://linux-hardware.org/?probe=8161abddda) | Nov 01, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [5b82a04d09](https://linux-hardware.org/?probe=5b82a04d09) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d9da25aaae](https://linux-hardware.org/?probe=d9da25aaae) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [4254def277](https://linux-hardware.org/?probe=4254def277) | Oct 30, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [d40277c6b4](https://linux-hardware.org/?probe=d40277c6b4) | Oct 30, 2023 |
| System76      | Gazelle                     | Notebook    | [3bc4a66a13](https://linux-hardware.org/?probe=3bc4a66a13) | Oct 29, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [9dad78d2eb](https://linux-hardware.org/?probe=9dad78d2eb) | Oct 27, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [354a804750](https://linux-hardware.org/?probe=354a804750) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fbbcdd8d9f](https://linux-hardware.org/?probe=fbbcdd8d9f) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cac52e6eaf](https://linux-hardware.org/?probe=cac52e6eaf) | Oct 25, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2355d71878](https://linux-hardware.org/?probe=2355d71878) | Oct 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [38cbc0d5d7](https://linux-hardware.org/?probe=38cbc0d5d7) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [29adbcb90f](https://linux-hardware.org/?probe=29adbcb90f) | Oct 24, 2023 |
| ASUSTek       | GL502VSK                    | Notebook    | [5f455e693f](https://linux-hardware.org/?probe=5f455e693f) | Oct 24, 2023 |
| ASRock        | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [24cad9ca71](https://linux-hardware.org/?probe=24cad9ca71) | Oct 22, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [2c786f10b7](https://linux-hardware.org/?probe=2c786f10b7) | Oct 22, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [7b1e876aef](https://linux-hardware.org/?probe=7b1e876aef) | Oct 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [72d780f5f7](https://linux-hardware.org/?probe=72d780f5f7) | Oct 22, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [2f2798b05c](https://linux-hardware.org/?probe=2f2798b05c) | Oct 22, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [451317bd25](https://linux-hardware.org/?probe=451317bd25) | Oct 22, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [fa46708f8f](https://linux-hardware.org/?probe=fa46708f8f) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4a7b98d45e](https://linux-hardware.org/?probe=4a7b98d45e) | Oct 18, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [a4661384e1](https://linux-hardware.org/?probe=a4661384e1) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [fb2bf1baa8](https://linux-hardware.org/?probe=fb2bf1baa8) | Oct 16, 2023 |
| Lenovo        | ThinkPad T450 20BUS1K50X    | Notebook    | [11ccdc870b](https://linux-hardware.org/?probe=11ccdc870b) | Oct 16, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [c5183a57ce](https://linux-hardware.org/?probe=c5183a57ce) | Oct 16, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a116875c3f](https://linux-hardware.org/?probe=a116875c3f) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [9f5a8c985a](https://linux-hardware.org/?probe=9f5a8c985a) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [6f3a56878d](https://linux-hardware.org/?probe=6f3a56878d) | Oct 15, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [d2e0e9fc07](https://linux-hardware.org/?probe=d2e0e9fc07) | Oct 14, 2023 |
| MSI           | GT72S 6QE                   | Notebook    | [9a2d87eb4c](https://linux-hardware.org/?probe=9a2d87eb4c) | Oct 12, 2023 |
| MSI           | GT72S 6QE                   | Notebook    | [4927bfc263](https://linux-hardware.org/?probe=4927bfc263) | Oct 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dc82ec9351](https://linux-hardware.org/?probe=dc82ec9351) | Oct 11, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [1014c56a70](https://linux-hardware.org/?probe=1014c56a70) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [15d9d16ec9](https://linux-hardware.org/?probe=15d9d16ec9) | Oct 09, 2023 |
| Biostar       | A320MH                      | Desktop     | [9623471fc7](https://linux-hardware.org/?probe=9623471fc7) | Oct 09, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [c0e071789f](https://linux-hardware.org/?probe=c0e071789f) | Oct 09, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [85d999063f](https://linux-hardware.org/?probe=85d999063f) | Oct 09, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [536b59322e](https://linux-hardware.org/?probe=536b59322e) | Oct 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e087628f2a](https://linux-hardware.org/?probe=e087628f2a) | Oct 07, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [06f03211a6](https://linux-hardware.org/?probe=06f03211a6) | Oct 06, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [811561ec05](https://linux-hardware.org/?probe=811561ec05) | Oct 04, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d3e6e2aa83](https://linux-hardware.org/?probe=d3e6e2aa83) | Oct 03, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [78c54897a1](https://linux-hardware.org/?probe=78c54897a1) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288f5f8266](https://linux-hardware.org/?probe=288f5f8266) | Sep 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [4bb43a39c1](https://linux-hardware.org/?probe=4bb43a39c1) | Sep 29, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | Notebook    | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [dd4a3f701c](https://linux-hardware.org/?probe=dd4a3f701c) | Sep 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [55c34c64a6](https://linux-hardware.org/?probe=55c34c64a6) | Sep 27, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [87a3517005](https://linux-hardware.org/?probe=87a3517005) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [c33d31195f](https://linux-hardware.org/?probe=c33d31195f) | Sep 26, 2023 |
| Dell          | G5 5505                     | Notebook    | [787ccf4559](https://linux-hardware.org/?probe=787ccf4559) | Sep 25, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [9b6bbb4b56](https://linux-hardware.org/?probe=9b6bbb4b56) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d21f140b5e](https://linux-hardware.org/?probe=d21f140b5e) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c40dbfbd1d](https://linux-hardware.org/?probe=c40dbfbd1d) | Sep 23, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5043f41a8d](https://linux-hardware.org/?probe=5043f41a8d) | Sep 20, 2023 |
| AZW           | GTR V02                     | Desktop     | [2d4817f092](https://linux-hardware.org/?probe=2d4817f092) | Sep 18, 2023 |
| Dell          | G3 3579                     | Notebook    | [eff563e086](https://linux-hardware.org/?probe=eff563e086) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [4c854cc233](https://linux-hardware.org/?probe=4c854cc233) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [27763442c0](https://linux-hardware.org/?probe=27763442c0) | Sep 16, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [cd2fb41835](https://linux-hardware.org/?probe=cd2fb41835) | Sep 15, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [52f0ac41db](https://linux-hardware.org/?probe=52f0ac41db) | Sep 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [caf0257156](https://linux-hardware.org/?probe=caf0257156) | Sep 13, 2023 |
| Dell          | Latitude E6440              | Notebook    | [591c479a8d](https://linux-hardware.org/?probe=591c479a8d) | Sep 13, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [b9f46a8a9b](https://linux-hardware.org/?probe=b9f46a8a9b) | Sep 12, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [f818765b79](https://linux-hardware.org/?probe=f818765b79) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3857377d7a](https://linux-hardware.org/?probe=3857377d7a) | Sep 09, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [b395463f0e](https://linux-hardware.org/?probe=b395463f0e) | Sep 06, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [95d0f9505b](https://linux-hardware.org/?probe=95d0f9505b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [174cff0e19](https://linux-hardware.org/?probe=174cff0e19) | Sep 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [07a44c323f](https://linux-hardware.org/?probe=07a44c323f) | Sep 01, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [a0649549b3](https://linux-hardware.org/?probe=a0649549b3) | Sep 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c865cde7a2](https://linux-hardware.org/?probe=c865cde7a2) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| ASRock        | Z490M Pro4                  | Desktop     | [e07d4a9c90](https://linux-hardware.org/?probe=e07d4a9c90) | Aug 30, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [cdbff2ba81](https://linux-hardware.org/?probe=cdbff2ba81) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [5af1e720cc](https://linux-hardware.org/?probe=5af1e720cc) | Aug 27, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [de1d12ec95](https://linux-hardware.org/?probe=de1d12ec95) | Aug 24, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| ASUSTek       | G751JM                      | Notebook    | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ca9423253c](https://linux-hardware.org/?probe=ca9423253c) | Aug 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 39 | 376       | 27.63%  |
| Nobara 37 | 268       | 19.69%  |
| Nobara 38 | 257       | 18.88%  |
| Nobara 36 | 257       | 18.88%  |
| Nobara 40 | 196       | 14.4%   |
| Nobara 41 | 7         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 1311      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.7.0-204.fsync.fc39.x86_64   | 88        | 6.07%   |
| 6.8.12-200.fsync.fc39.x86_64  | 77        | 5.31%   |
| 6.7.6-201.fsync.fc39.x86_64   | 62        | 4.28%   |
| 6.4.10-202.fsync.fc38.x86_64  | 55        | 3.8%    |
| 6.8.7-201.fsync.fc39.x86_64   | 48        | 3.31%   |
| 6.0.14-201.fsync.fc36.x86_64  | 40        | 2.76%   |
| 6.11.9-200.fsync.fc40.x86_64  | 39        | 2.69%   |
| 6.0.10-201.fc36.x86_64        | 37        | 2.55%   |
| 6.2.14-300.fsync.fc37.x86_64  | 33        | 2.28%   |
| 6.3.12-204.fsync.fc38.x86_64  | 27        | 1.86%   |
| 6.1.14-201.fsync.fc37.x86_64  | 25        | 1.73%   |
| 5.19.14-201.fsync.fc36.x86_64 | 25        | 1.73%   |
| 6.6.9-200.fsync.fc39.x86_64   | 23        | 1.59%   |
| 6.10.3-201.fsync.fc40.x86_64  | 22        | 1.52%   |
| 6.8.5-201.fsync.fc39.x86_64   | 21        | 1.45%   |
| 6.5.9-201.fsync.fc38.x86_64   | 21        | 1.45%   |
| 6.11.3-200.fsync.fc40.x86_64  | 21        | 1.45%   |
| 6.1.11-201.fsync.fc37.x86_64  | 21        | 1.45%   |
| 6.5.6-200.fsync.fc38.x86_64   | 20        | 1.38%   |
| 6.2.12-200.fsync.fc37.x86_64  | 19        | 1.31%   |
| 6.10.6-200.fsync.fc40.x86_64  | 19        | 1.31%   |
| 6.10.7-200.fsync.fc40.x86_64  | 18        | 1.24%   |
| 6.2.6-201.fsync.fc37.x86_64   | 17        | 1.17%   |
| 6.1.9-200.fsync.fc37.x86_64   | 17        | 1.17%   |
| 6.1.4-203.fsync.fc37.x86_64   | 17        | 1.17%   |
| 6.7.5-200.fsync.fc39.x86_64   | 16        | 1.1%    |
| 6.6.7-203.fsync.fc38.x86_64   | 16        | 1.1%    |
| 5.19.9-201.fsync.fc36.x86_64  | 16        | 1.1%    |
| 5.19.7-204.fsync.fc36.x86_64  | 16        | 1.1%    |
| 6.11.7-201.fsync.fc40.x86_64  | 15        | 1.04%   |
| 6.8.12-201.fsync.fc40.x86_64  | 14        | 0.97%   |
| 6.3.10-200.fsync.fc38.x86_64  | 14        | 0.97%   |
| 6.3.7-200.fsync.fc37.x86_64   | 13        | 0.9%    |
| 6.2.10-200.fsync.fc37.x86_64  | 13        | 0.9%    |
| 6.7.0-201.fsync.fc39.x86_64   | 12        | 0.83%   |
| 6.11.0-200.fsync.fc40.x86_64  | 12        | 0.83%   |
| 6.0.7-201.fsync.fc36.x86_64   | 12        | 0.83%   |
| 5.19.16-201.fsync.fc36.x86_64 | 12        | 0.83%   |
| 6.6.8-200.fsync.fc39.x86_64   | 11        | 0.76%   |
| 6.3.12-205.fsync.fc38.x86_64  | 11        | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.7.0   | 106       | 7.35%   |
| 6.8.12  | 96        | 6.65%   |
| 6.7.6   | 69        | 4.78%   |
| 6.4.10  | 63        | 4.37%   |
| 6.3.12  | 53        | 3.67%   |
| 6.8.7   | 52        | 3.6%    |
| 6.0.14  | 40        | 2.77%   |
| 6.11.9  | 39        | 2.7%    |
| 6.0.10  | 37        | 2.56%   |
| 6.2.14  | 34        | 2.36%   |
| 6.6.7   | 28        | 1.94%   |
| 6.5.9   | 28        | 1.94%   |
| 6.1.14  | 25        | 1.73%   |
| 5.19.14 | 25        | 1.73%   |
| 6.6.9   | 23        | 1.59%   |
| 6.10.3  | 22        | 1.52%   |
| 6.8.5   | 21        | 1.46%   |
| 6.5.6   | 21        | 1.46%   |
| 6.3.10  | 21        | 1.46%   |
| 6.11.3  | 21        | 1.46%   |
| 6.1.11  | 21        | 1.46%   |
| 6.2.12  | 19        | 1.32%   |
| 6.10.6  | 19        | 1.32%   |
| 6.10.7  | 18        | 1.25%   |
| 5.19.7  | 18        | 1.25%   |
| 6.6.8   | 17        | 1.18%   |
| 6.5.5   | 17        | 1.18%   |
| 6.2.6   | 17        | 1.18%   |
| 6.11.0  | 17        | 1.18%   |
| 6.1.9   | 17        | 1.18%   |
| 6.1.4   | 17        | 1.18%   |
| 6.7.5   | 16        | 1.11%   |
| 6.2.11  | 16        | 1.11%   |
| 6.1.6   | 16        | 1.11%   |
| 6.0.7   | 16        | 1.11%   |
| 5.19.9  | 16        | 1.11%   |
| 6.5.3   | 15        | 1.04%   |
| 6.11.7  | 15        | 1.04%   |
| 6.3.7   | 14        | 0.97%   |
| 6.2.10  | 13        | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.7     | 191       | 13.59%  |
| 6.8     | 173       | 12.31%  |
| 6.0     | 133       | 9.47%   |
| 6.11    | 116       | 8.26%   |
| 5.19    | 114       | 8.11%   |
| 6.1     | 108       | 7.69%   |
| 6.3     | 107       | 7.62%   |
| 6.2     | 107       | 7.62%   |
| 6.6     | 95        | 6.76%   |
| 6.5     | 88        | 6.26%   |
| 6.4     | 69        | 4.91%   |
| 6.10    | 63        | 4.48%   |
| 5.18    | 34        | 2.42%   |
| 6.12    | 7         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1311      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 637       | 47.57%  |
| KDE5          | 357       | 26.66%  |
| KDE6          | 317       | 23.67%  |
| KDE4          | 11        | 0.82%   |
| Unknown       | 11        | 0.82%   |
| Hyprland      | 2         | 0.15%   |
| GNOME Classic | 2         | 0.15%   |
| X-Cinnamon    | 1         | 0.07%   |
| sway          | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1101      | 82.6%   |
| X11     | 221       | 16.58%  |
| Unknown | 8         | 0.6%    |
| Tty     | 3         | 0.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1027      | 77.28%  |
| SDDM    | 167       | 12.57%  |
| GDM     | 125       | 9.41%   |
| LightDM | 10        | 0.75%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 647       | 49.13%  |
| de_DE   | 116       | 8.81%   |
| en_GB   | 104       | 7.9%    |
| es_ES   | 43        | 3.26%   |
| ru_RU   | 38        | 2.89%   |
| es_MX   | 37        | 2.81%   |
| en_CA   | 35        | 2.66%   |
| pt_BR   | 31        | 2.35%   |
| fr_FR   | 29        | 2.2%    |
| pl_PL   | 27        | 2.05%   |
| it_IT   | 25        | 1.9%    |
| en_AU   | 24        | 1.82%   |
| es_AR   | 16        | 1.21%   |
| de_AT   | 15        | 1.14%   |
| en_IN   | 12        | 0.91%   |
| hu_HU   | 10        | 0.76%   |
| en_NZ   | 10        | 0.76%   |
| Unknown | 6         | 0.46%   |
| es_CO   | 5         | 0.38%   |
| en_DK   | 5         | 0.38%   |
| da_DK   | 5         | 0.38%   |
| tr_TR   | 4         | 0.3%    |
| sv_SE   | 4         | 0.3%    |
| pt_PT   | 4         | 0.3%    |
| nl_NL   | 4         | 0.3%    |
| nb_NO   | 4         | 0.3%    |
| fi_FI   | 4         | 0.3%    |
| nl_BE   | 3         | 0.23%   |
| fr_CA   | 3         | 0.23%   |
| fr_BE   | 3         | 0.23%   |
| es_CL   | 3         | 0.23%   |
| en_SG   | 3         | 0.23%   |
| en_PH   | 3         | 0.23%   |
| en_IL   | 3         | 0.23%   |
| zh_TW   | 2         | 0.15%   |
| uk_UA   | 2         | 0.15%   |
| es_VE   | 2         | 0.15%   |
| es_CR   | 2         | 0.15%   |
| en_ZA   | 2         | 0.15%   |
| en_BW   | 2         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 988       | 74.29%  |
| BIOS | 342       | 25.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 1135      | 86.18%  |
| Ext4  | 179       | 13.59%  |
| Xfs   | 3         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1018      | 76.6%   |
| GPT     | 299       | 22.5%   |
| MBR     | 12        | 0.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1237      | 94%     |
| Yes       | 79        | 6%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1151      | 87.33%  |
| Yes       | 167       | 12.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 315       | 24.03%  |
| MSI                                  | 183       | 13.96%  |
| Gigabyte Technology                  | 146       | 11.14%  |
| Hewlett-Packard                      | 126       | 9.61%   |
| Lenovo                               | 117       | 8.92%   |
| ASRock                               | 96        | 7.32%   |
| Dell                                 | 88        | 6.71%   |
| Acer                                 | 46        | 3.51%   |
| Apple                                | 30        | 2.29%   |
| Intel                                | 16        | 1.22%   |
| Toshiba                              | 7         | 0.53%   |
| Samsung Electronics                  | 7         | 0.53%   |
| Microsoft                            | 7         | 0.53%   |
| Biostar                              | 7         | 0.53%   |
| AZW                                  | 7         | 0.53%   |
| Alienware                            | 6         | 0.46%   |
| Unknown                              | 5         | 0.38%   |
| Shenzhen Meigao Electronic Equipment | 4         | 0.31%   |
| NZXT                                 | 4         | 0.31%   |
| Notebook                             | 4         | 0.31%   |
| Positivo                             | 3         | 0.23%   |
| Pegatron                             | 3         | 0.23%   |
| ONE-NETBOOK                          | 3         | 0.23%   |
| Medion                               | 3         | 0.23%   |
| Infinix                              | 3         | 0.23%   |
| Huanan                               | 3         | 0.23%   |
| Google                               | 3         | 0.23%   |
| Valve                                | 2         | 0.15%   |
| TUXEDO                               | 2         | 0.15%   |
| Timi                                 | 2         | 0.15%   |
| Sony                                 | 2         | 0.15%   |
| PC Specialist                        | 2         | 0.15%   |
| Monster                              | 2         | 0.15%   |
| Micro Computer (HK) Tech Limited     | 2         | 0.15%   |
| Intel Client Systems                 | 2         | 0.15%   |
| HUAWEI                               | 2         | 0.15%   |
| GPU Company                          | 2         | 0.15%   |
| GPD                                  | 2         | 0.15%   |
| Fujitsu                              | 2         | 0.15%   |
| BESSTAR Tech                         | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| MSI MS-7C37                         | 12        | 0.92%   |
| MSI MS-7C56                         | 11        | 0.84%   |
| MSI MS-7B86                         | 10        | 0.76%   |
| Unknown                             | 10        | 0.76%   |
| ASUS TUF Gaming B550-PLUS           | 9         | 0.69%   |
| ASUS All Series                     | 9         | 0.69%   |
| MSI MS-7C02                         | 8         | 0.61%   |
| ASUS TUF Gaming X570-PLUS           | 8         | 0.61%   |
| MSI MS-7D25                         | 7         | 0.53%   |
| ASUS ROG STRIX B550-F GAMING        | 7         | 0.53%   |
| MSI MS-7C91                         | 6         | 0.46%   |
| MSI MS-7B79                         | 6         | 0.46%   |
| Gigabyte X570 AORUS ELITE           | 6         | 0.46%   |
| ASUS TUF Gaming B550M-PLUS          | 6         | 0.46%   |
| MSI MS-7C95                         | 5         | 0.38%   |
| MSI MS-7C35                         | 5         | 0.38%   |
| ASUS PRIME B450M-A                  | 5         | 0.38%   |
| ASUS PRIME A320M-K                  | 5         | 0.38%   |
| ASUS CROSSHAIR VI HERO              | 5         | 0.38%   |
| ASRock B550 Phantom Gaming-ITX/ax   | 5         | 0.38%   |
| MSI MS-7D75                         | 4         | 0.31%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 4         | 0.31%   |
| Gigabyte X570 AORUS MASTER          | 4         | 0.31%   |
| Gigabyte X570 AORUS ELITE WIFI      | 4         | 0.31%   |
| Gigabyte B550 AORUS ELITE V2        | 4         | 0.31%   |
| AZW SER                             | 4         | 0.31%   |
| ASUS TUF Gaming X670E-PLUS WIFI     | 4         | 0.31%   |
| ASUS ROG Strix G513QY_G513QY        | 4         | 0.31%   |
| ASUS ROG STRIX B650E-I GAMING WIFI  | 4         | 0.31%   |
| ASUS ROG Maximus XI HERO            | 4         | 0.31%   |
| ASUS PRIME X570-P                   | 4         | 0.31%   |
| MSI MS-7B17                         | 3         | 0.23%   |
| MSI MS-7A38                         | 3         | 0.23%   |
| MSI MS-7977                         | 3         | 0.23%   |
| Lenovo Legion 5 15ARH05 82B5        | 3         | 0.23%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 3         | 0.23%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 3         | 0.23%   |
| Lenovo IdeaPad C340-14API 81N6      | 3         | 0.23%   |
| Intel X79                           | 3         | 0.23%   |
| HP Pavilion Notebook                | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| ASUS ROG          | 96        | 7.32%   |
| ASUS TUF          | 60        | 4.58%   |
| ASUS PRIME        | 47        | 3.59%   |
| HP Pavilion       | 35        | 2.67%   |
| Lenovo IdeaPad    | 34        | 2.59%   |
| Lenovo ThinkPad   | 27        | 2.06%   |
| Acer Aspire       | 21        | 1.6%    |
| Gigabyte X570     | 19        | 1.45%   |
| ASUS VivoBook     | 19        | 1.45%   |
| Lenovo Legion     | 18        | 1.37%   |
| Dell OptiPlex     | 16        | 1.22%   |
| Dell Latitude     | 16        | 1.22%   |
| Dell Inspiron     | 16        | 1.22%   |
| ASUS ASUS         | 16        | 1.22%   |
| HP Laptop         | 13        | 0.99%   |
| Acer Nitro        | 13        | 0.99%   |
| MSI MS-7C37       | 12        | 0.92%   |
| MSI MS-7C56       | 11        | 0.84%   |
| HP ENVY           | 11        | 0.84%   |
| HP EliteBook      | 11        | 0.84%   |
| Gigabyte B550     | 11        | 0.84%   |
| ASRock B550       | 11        | 0.84%   |
| MSI MS-7B86       | 10        | 0.76%   |
| Dell Precision    | 10        | 0.76%   |
| Unknown           | 10        | 0.76%   |
| HP OMEN           | 9         | 0.69%   |
| Gigabyte B550M    | 9         | 0.69%   |
| ASUS All          | 9         | 0.69%   |
| MSI MS-7C02       | 8         | 0.61%   |
| HP Compaq         | 8         | 0.61%   |
| Dell XPS          | 8         | 0.61%   |
| MSI MS-7D25       | 7         | 0.53%   |
| Microsoft Surface | 7         | 0.53%   |
| ASRock X570       | 7         | 0.53%   |
| ASRock B550M      | 7         | 0.53%   |
| ASRock B450M      | 7         | 0.53%   |
| Toshiba Satellite | 6         | 0.46%   |
| MSI MS-7C91       | 6         | 0.46%   |
| MSI MS-7B79       | 6         | 0.46%   |
| Lenovo Yoga       | 6         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 193       | 14.72%  |
| 2021 | 170       | 12.97%  |
| 2019 | 170       | 12.97%  |
| 2022 | 139       | 10.6%   |
| 2018 | 125       | 9.53%   |
| 2023 | 95        | 7.25%   |
| 2013 | 67        | 5.11%   |
| 2017 | 61        | 4.65%   |
| 2012 | 60        | 4.58%   |
| 2014 | 51        | 3.89%   |
| 2016 | 50        | 3.81%   |
| 2015 | 37        | 2.82%   |
| 2011 | 32        | 2.44%   |
| 2024 | 21        | 1.6%    |
| 2010 | 15        | 1.14%   |
| 2009 | 15        | 1.14%   |
| 2008 | 8         | 0.61%   |
| 2007 | 2         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 732       | 55.84%  |
| Notebook    | 497       | 37.91%  |
| Convertible | 32        | 2.44%   |
| Tablet      | 20        | 1.53%   |
| Mini pc     | 17        | 1.3%    |
| All in one  | 11        | 0.84%   |
| Other       | 1         | 0.08%   |
| Server      | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1311      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1307      | 99.69%  |
| Yes  | 4         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 348       | 26.34%  |
| 16.01-24.0      | 345       | 26.12%  |
| 8.01-16.0       | 200       | 15.14%  |
| 4.01-8.0        | 186       | 14.08%  |
| 24.01-32.0      | 87        | 6.59%   |
| 64.01-256.0     | 75        | 5.68%   |
| 3.01-4.0        | 71        | 5.37%   |
| 1.01-2.0        | 6         | 0.45%   |
| 2.01-3.0        | 2         | 0.15%   |
| More than 256.0 | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 602       | 42.82%  |
| 3.01-4.0   | 322       | 22.9%   |
| 2.01-3.0   | 245       | 17.43%  |
| 8.01-16.0  | 141       | 10.03%  |
| 1.01-2.0   | 73        | 5.19%   |
| 16.01-24.0 | 18        | 1.28%   |
| 24.01-32.0 | 4         | 0.28%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 537       | 39.93%  |
| 2      | 391       | 29.07%  |
| 3      | 195       | 14.5%   |
| 4      | 121       | 9%      |
| 5      | 54        | 4.01%   |
| 6      | 23        | 1.71%   |
| 7      | 11        | 0.82%   |
| 8      | 5         | 0.37%   |
| 10     | 3         | 0.22%   |
| 9      | 3         | 0.22%   |
| 11     | 1         | 0.07%   |
| 0      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1076      | 81.7%   |
| Yes       | 241       | 18.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1173      | 89.27%  |
| No        | 141       | 10.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 998       | 75.66%  |
| No        | 321       | 24.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 952       | 72.23%  |
| No        | 366       | 27.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 382       | 29.07%  |
| Germany      | 142       | 10.81%  |
| UK           | 59        | 4.49%   |
| Canada       | 50        | 3.81%   |
| Russia       | 49        | 3.73%   |
| Brazil       | 46        | 3.5%    |
| Spain        | 44        | 3.35%   |
| Poland       | 38        | 2.89%   |
| Italy        | 35        | 2.66%   |
| France       | 35        | 2.66%   |
| Australia    | 35        | 2.66%   |
| Argentina    | 29        | 2.21%   |
| Mexico       | 25        | 1.9%    |
| Austria      | 24        | 1.83%   |
| India        | 22        | 1.67%   |
| Netherlands  | 19        | 1.45%   |
| Sweden       | 17        | 1.29%   |
| Hungary      | 14        | 1.07%   |
| New Zealand  | 11        | 0.84%   |
| Turkey       | 10        | 0.76%   |
| Portugal     | 10        | 0.76%   |
| Norway       | 10        | 0.76%   |
| Indonesia    | 10        | 0.76%   |
| Finland      | 10        | 0.76%   |
| Colombia     | 10        | 0.76%   |
| Belgium      | 10        | 0.76%   |
| Romania      | 8         | 0.61%   |
| Philippines  | 8         | 0.61%   |
| Chile        | 8         | 0.61%   |
| Venezuela    | 7         | 0.53%   |
| Switzerland  | 6         | 0.46%   |
| Denmark      | 6         | 0.46%   |
| Czechia      | 6         | 0.46%   |
| Saudi Arabia | 5         | 0.38%   |
| Greece       | 5         | 0.38%   |
| Estonia      | 5         | 0.38%   |
| Ukraine      | 4         | 0.3%    |
| South Africa | 4         | 0.3%    |
| Malaysia     | 4         | 0.3%    |
| Israel       | 4         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Vienna            | 12        | 0.88%   |
| Melbourne         | 10        | 0.73%   |
| Los Angeles       | 9         | 0.66%   |
| Berlin            | 9         | 0.66%   |
| Warsaw            | 8         | 0.59%   |
| Sydney            | 8         | 0.59%   |
| Buenos Aires      | 8         | 0.59%   |
| Atlanta           | 8         | 0.59%   |
| Stockholm         | 7         | 0.51%   |
| Toronto           | 6         | 0.44%   |
| New York          | 6         | 0.44%   |
| Madrid            | 6         | 0.44%   |
| Frankfurt am Main | 6         | 0.44%   |
| Denver            | 6         | 0.44%   |
| Calgary           | 6         | 0.44%   |
| Brisbane          | 6         | 0.44%   |
| Milan             | 5         | 0.37%   |
| Guadalajara       | 5         | 0.37%   |
| Auckland          | 5         | 0.37%   |
| Valencia          | 4         | 0.29%   |
| St Petersburg     | 4         | 0.29%   |
| Sao Paulo         | 4         | 0.29%   |
| San Francisco     | 4         | 0.29%   |
| Samara            | 4         | 0.29%   |
| Rome              | 4         | 0.29%   |
| Osnabrück        | 4         | 0.29%   |
| Milano            | 4         | 0.29%   |
| London            | 4         | 0.29%   |
| Kansas City       | 4         | 0.29%   |
| Houston           | 4         | 0.29%   |
| Helsinki          | 4         | 0.29%   |
| Hamburg           | 4         | 0.29%   |
| Gothenburg        | 4         | 0.29%   |
| Fortaleza         | 4         | 0.29%   |
| Düsseldorf       | 4         | 0.29%   |
| Cologne           | 4         | 0.29%   |
| Chennai           | 4         | 0.29%   |
| Brooklyn          | 4         | 0.29%   |
| Baltimore         | 4         | 0.29%   |
| Zurich            | 3         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 433       | 705    | 17.53%  |
| Seagate                      | 268       | 363    | 10.85%  |
| WDC                          | 254       | 367    | 10.28%  |
| SanDisk                      | 202       | 263    | 8.18%   |
| Kingston                     | 142       | 167    | 5.75%   |
| Crucial                      | 120       | 169    | 4.86%   |
| Toshiba                      | 109       | 138    | 4.41%   |
| Micron/Crucial Technology    | 78        | 96     | 3.16%   |
| Phison Electronics           | 74        | 87     | 3%      |
| SK hynix                     | 61        | 68     | 2.47%   |
| Micron Technology            | 59        | 66     | 2.39%   |
| Intel                        | 56        | 70     | 2.27%   |
| Kingston Technology Company  | 42        | 53     | 1.7%    |
| Unknown                      | 39        | 51     | 1.58%   |
| Hitachi                      | 33        | 42     | 1.34%   |
| HGST                         | 28        | 33     | 1.13%   |
| PNY                          | 25        | 34     | 1.01%   |
| A-DATA Technology            | 24        | 26     | 0.97%   |
| KIOXIA                       | 23        | 29     | 0.93%   |
| China                        | 23        | 28     | 0.93%   |
| ADATA Technology             | 22        | 25     | 0.89%   |
| Realtek Semiconductor        | 21        | 24     | 0.85%   |
| Silicon Motion               | 20        | 27     | 0.81%   |
| MAXIO Technology (Hangzhou)  | 19        | 20     | 0.77%   |
| Apple                        | 15        | 17     | 0.61%   |
| Shenzhen Longsys Electronics | 14        | 24     | 0.57%   |
| SPCC                         | 13        | 17     | 0.53%   |
| Intenso                      | 13        | 16     | 0.53%   |
| Team                         | 12        | 12     | 0.49%   |
| GOODRAM                      | 10        | 11     | 0.4%    |
| OCZ                          | 9         | 9      | 0.36%   |
| Unknown                      | 9         | 11     | 0.36%   |
| Phison                       | 8         | 9      | 0.32%   |
| Patriot                      | 8         | 8      | 0.32%   |
| Fanxiang                     | 8         | 9      | 0.32%   |
| Corsair                      | 8         | 9      | 0.32%   |
| Lexar                        | 7         | 8      | 0.28%   |
| JMicron Technology           | 7         | 15     | 0.28%   |
| SABRENT                      | 6         | 7      | 0.24%   |
| Realtek                      | 6         | 7      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 112       | 3.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 67        | 2.38%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 51        | 1.81%   |
| Kingston SA400S37240G 240GB SSD                                   | 38        | 1.35%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 29        | 1.03%   |
| Phison E12 NVMe Controller 480GB                                  | 28        | 0.99%   |
| Samsung SSD 860 EVO 1TB                                           | 27        | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 25        | 0.89%   |
| Samsung SSD 850 EVO 500GB                                         | 25        | 0.89%   |
| Samsung SSD 860 EVO 500GB                                         | 23        | 0.82%   |
| Crucial CT1000MX500SSD1 1TB                                       | 23        | 0.82%   |
| Intel SSD 660P Series 1024GB                                      | 21        | 0.75%   |
| Samsung SSD 850 EVO 250GB                                         | 19        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB               | 19        | 0.67%   |
| Crucial CT1000BX500SSD1 1TB                                       | 19        | 0.67%   |
| Samsung SSD 980 1TB                                               | 18        | 0.64%   |
| Kingston SA400S37480G 480GB SSD                                   | 18        | 0.64%   |
| Phison PS5013 E13 NVMe Controller 512GB                           | 17        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller 1TB                              | 17        | 0.6%    |
| Kingston Company SNV2S1000G 1TB                                   | 17        | 0.6%    |
| Samsung SSD 990 PRO 2TB                                           | 15        | 0.53%   |
| Crucial CT500MX500SSD1 500GB                                      | 15        | 0.53%   |
| Sandisk WD_BLACK SN770 1TB                                        | 14        | 0.5%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                  | 14        | 0.5%    |
| Toshiba DT01ACA100 1TB                                            | 13        | 0.46%   |
| Seagate ST4000DM004-2CV104 4TB                                    | 13        | 0.46%   |
| Sandisk WD_BLACK SN770 2TB                                        | 12        | 0.43%   |
| Samsung SSD 870 EVO 1TB                                           | 12        | 0.43%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 11        | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 11        | 0.39%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 11        | 0.39%   |
| Sandisk WD Black SN850 2TB                                        | 11        | 0.39%   |
| Samsung SSD 870 EVO 2TB                                           | 11        | 0.39%   |
| Samsung SSD 860 EVO 250GB                                         | 11        | 0.39%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB                | 11        | 0.39%   |
| Kingston Company A2000 NVMe SSD 500GB                             | 11        | 0.39%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 11        | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 10        | 0.36%   |
| Unknown MMC Card  64GB                                            | 10        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                                      | 10        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 259       | 348    | 38.83%  |
| WDC                 | 201       | 286    | 30.13%  |
| Toshiba             | 88        | 113    | 13.19%  |
| Hitachi             | 33        | 42     | 4.95%   |
| HGST                | 28        | 33     | 4.2%    |
| Samsung Electronics | 21        | 32     | 3.15%   |
| Apple               | 8         | 8      | 1.2%    |
| SABRENT             | 6         | 7      | 0.9%    |
| JMicron Technology  | 5         | 13     | 0.75%   |
| Unknown             | 4         | 4      | 0.6%    |
| Maxtor              | 3         | 3      | 0.45%   |
| ASMT                | 2         | 5      | 0.3%    |
| USB 3.1             | 1         | 3      | 0.15%   |
| USB                 | 1         | 1      | 0.15%   |
| TO Exter            | 1         | 1      | 0.15%   |
| RSH-339             | 1         | 1      | 0.15%   |
| Intenso             | 1         | 1      | 0.15%   |
| HGST HTS            | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| Fujitsu             | 1         | 1      | 0.15%   |
| ACASIS              | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 208       | 292    | 25.3%   |
| Crucial             | 118       | 167    | 14.36%  |
| Kingston            | 100       | 114    | 12.17%  |
| WDC                 | 62        | 72     | 7.54%   |
| SanDisk             | 52        | 64     | 6.33%   |
| PNY                 | 25        | 34     | 3.04%   |
| A-DATA Technology   | 24        | 26     | 2.92%   |
| China               | 22        | 27     | 2.68%   |
| SPCC                | 13        | 17     | 1.58%   |
| Team                | 11        | 11     | 1.34%   |
| SK hynix            | 11        | 11     | 1.34%   |
| Micron Technology   | 11        | 12     | 1.34%   |
| Intel               | 11        | 14     | 1.34%   |
| Intenso             | 10        | 12     | 1.22%   |
| GOODRAM             | 10        | 11     | 1.22%   |
| OCZ                 | 9         | 9      | 1.09%   |
| Toshiba             | 8         | 10     | 0.97%   |
| Patriot             | 8         | 8      | 0.97%   |
| Corsair             | 7         | 8      | 0.85%   |
| Lexar               | 6         | 7      | 0.73%   |
| KingSpec            | 5         | 6      | 0.61%   |
| Apacer              | 5         | 6      | 0.61%   |
| XrayDisk            | 4         | 4      | 0.49%   |
| Verbatim            | 4         | 6      | 0.49%   |
| Transcend           | 4         | 4      | 0.49%   |
| Netac               | 4         | 4      | 0.49%   |
| Fanxiang            | 4         | 5      | 0.49%   |
| USB3.0              | 3         | 3      | 0.36%   |
| Seagate             | 3         | 3      | 0.36%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.36%   |
| Gigabyte Technology | 3         | 3      | 0.36%   |
| Unknown             | 3         | 5      | 0.36%   |
| Wibtek              | 2         | 2      | 0.24%   |
| Timetec             | 2         | 2      | 0.24%   |
| PNY CS90            | 2         | 2      | 0.24%   |
| Plextor             | 2         | 2      | 0.24%   |
| Mushkin             | 2         | 2      | 0.24%   |
| LITEONIT            | 2         | 2      | 0.24%   |
| LITEON              | 2         | 2      | 0.24%   |
| KingFast            | 2         | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 827       | 1280   | 39.36%  |
| SSD     | 654       | 1031   | 31.13%  |
| HDD     | 547       | 905    | 26.04%  |
| Unknown | 49        | 59     | 2.33%   |
| MMC     | 24        | 27     | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 862       | 1834   | 47.03%  |
| NVMe | 823       | 1266   | 44.9%   |
| SAS  | 124       | 175    | 6.76%   |
| MMC  | 24        | 27     | 1.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 564       | 855    | 42.79%  |
| 0.51-1.0   | 420       | 601    | 31.87%  |
| 1.01-2.0   | 188       | 281    | 14.26%  |
| 3.01-4.0   | 66        | 89     | 5.01%   |
| 4.01-10.0  | 41        | 60     | 3.11%   |
| 2.01-3.0   | 28        | 34     | 2.12%   |
| 10.01-20.0 | 11        | 16     | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 280       | 20.69%  |
| 501-1000       | 275       | 20.33%  |
| 1001-2000      | 266       | 19.66%  |
| 251-500        | 189       | 13.97%  |
| 101-250        | 136       | 10.05%  |
| 2001-3000      | 117       | 8.65%   |
| Unknown        | 32        | 2.37%   |
| 21-50          | 27        | 2%      |
| 51-100         | 19        | 1.4%    |
| 1-20           | 12        | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 260       | 18.6%   |
| 101-250        | 202       | 14.45%  |
| 1-20           | 174       | 12.45%  |
| 501-1000       | 164       | 11.73%  |
| 251-500        | 163       | 11.66%  |
| 51-100         | 140       | 10.01%  |
| 1001-2000      | 128       | 9.16%   |
| More than 3000 | 71        | 5.08%   |
| 2001-3000      | 64        | 4.58%   |
| Unknown        | 32        | 2.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                                     | 2         | 2      | 4.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-08U6AA0 500GB                                    | 1         | 1      | 2.38%   |
| WDC WD30EZRX-00DC0B0 3TB                                        | 1         | 1      | 2.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 1         | 1      | 2.38%   |
| WDC WD20EVDS-63T3B0 2TB                                         | 1         | 1      | 2.38%   |
| WDC WD20EURS-63S48Y0 2TB                                        | 1         | 1      | 2.38%   |
| WDC WD2003FZEX-00Z4SA0 2TB                                      | 1         | 1      | 2.38%   |
| WDC WD10JPVX-60JC3T1 1TB                                        | 1         | 1      | 2.38%   |
| WDC WD10EZEX-08M2NA0 1TB                                        | 1         | 1      | 2.38%   |
| WDC WD10EADS-00L5B1 1TB                                         | 1         | 1      | 2.38%   |
| WDC WD10EACS-00D6B0 1TB                                         | 1         | 1      | 2.38%   |
| WDC WD Green 2.5 240GB SSD                                      | 1         | 1      | 2.38%   |
| Verbatim Vi550 S3 1TB SSD                                       | 1         | 1      | 2.38%   |
| Toshiba MK8052GSX 80GB                                          | 1         | 1      | 2.38%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 1         | 1      | 2.38%   |
| Seagate ST9160314AS 160GB                                       | 1         | 1      | 2.38%   |
| Seagate ST8000DM004-2CX188 8TB                                  | 1         | 1      | 2.38%   |
| Seagate ST6000DM003-2CY186 6TB                                  | 1         | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB                                 | 1         | 1      | 2.38%   |
| Seagate ST3500418AS 500GB                                       | 1         | 1      | 2.38%   |
| Seagate ST2000DX002-2DV164 2TB                                  | 1         | 1      | 2.38%   |
| Seagate ST2000DX001-1NS164 2TB                                  | 1         | 1      | 2.38%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 1         | 1      | 2.38%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 970 EVO 1TB                             | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 1         | 2      | 2.38%   |
| Samsung Electronics SSD 840 PRO Series 128GB                    | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 830 Series 256GB                        | 1         | 1      | 2.38%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 1         | 1      | 2.38%   |
| Samsung Electronics HD161GJ 160GB                               | 1         | 1      | 2.38%   |
| Samsung Electronics HD154UI 1TB                                 | 1         | 1      | 2.38%   |
| Ramsta SSD S800 240GB                                           | 1         | 1      | 2.38%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD                  | 1         | 1      | 2.38%   |
| Hitachi HTS54323 320GB                                          | 1         | 1      | 2.38%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 2.38%   |
| HGST HTS545050A7E380 500GB                                      | 1         | 1      | 2.38%   |
| HGST HTS541010A9E680 1TB                                        | 1         | 1      | 2.38%   |
| Crucial CT1000BX500SSD1 1TB                                     | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 34.15%  |
| Seagate             | 9         | 9      | 21.95%  |
| Samsung Electronics | 7         | 9      | 17.07%  |
| HGST                | 3         | 3      | 7.32%   |
| Verbatim            | 1         | 1      | 2.44%   |
| Toshiba             | 1         | 1      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Ramsta              | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| Hitachi             | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| ASMT                | 1         | 2      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 41.38%  |
| Seagate             | 9         | 9      | 31.03%  |
| HGST                | 3         | 3      | 10.34%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Toshiba             | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| ASMT                | 1         | 2      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 30     | 68.29%  |
| SSD  | 10        | 11     | 24.39%  |
| NVMe | 3         | 3      | 7.32%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1059      | 2637   | 76.35%  |
| Works    | 290       | 620    | 20.91%  |
| Malfunc  | 37        | 44     | 2.67%   |
| Limited  | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 638       | 28.89%  |
| AMD                                  | 511       | 23.14%  |
| Samsung Electronics                  | 280       | 12.68%  |
| SanDisk                              | 163       | 7.38%   |
| Kingston Technology Company          | 87        | 3.94%   |
| Phison Electronics                   | 83        | 3.76%   |
| Micron/Crucial Technology            | 80        | 3.62%   |
| ASMedia Technology                   | 66        | 2.99%   |
| SK hynix                             | 52        | 2.36%   |
| Micron Technology                    | 48        | 2.17%   |
| KIOXIA                               | 24        | 1.09%   |
| Realtek Semiconductor                | 22        | 1%      |
| ADATA Technology                     | 22        | 1%      |
| Silicon Motion                       | 20        | 0.91%   |
| MAXIO Technology (Hangzhou)          | 19        | 0.86%   |
| Shenzhen Longsys Electronics         | 14        | 0.63%   |
| Toshiba America Info Systems         | 13        | 0.59%   |
| Nvidia                               | 9         | 0.41%   |
| Marvell Technology Group             | 9         | 0.41%   |
| Solidigm                             | 7         | 0.32%   |
| JMicron Technology                   | 7         | 0.32%   |
| Seagate Technology                   | 5         | 0.23%   |
| Apple                                | 5         | 0.23%   |
| INNOGRIT                             | 4         | 0.18%   |
| Broadcom / LSI                       | 4         | 0.18%   |
| Solid State Storage Technology       | 3         | 0.14%   |
| Union Memory (Shenzhen)              | 2         | 0.09%   |
| LSI Logic / Symbios Logic            | 2         | 0.09%   |
| Biwin Storage Technology             | 2         | 0.09%   |
| Yangtze Memory Technologies          | 1         | 0.05%   |
| Silicon Image                        | 1         | 0.05%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.05%   |
| Netac Technology                     | 1         | 0.05%   |
| Lite-On Technology                   | 1         | 0.05%   |
| Lenovo                               | 1         | 0.05%   |
| Hewlett-Packard                      | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 255       | 10.51%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 124       | 5.11%   |
| AMD 500 Series Chipset SATA Controller                                         | 112       | 4.61%   |
| AMD 400 Series Chipset SATA Controller                                         | 97        | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 73        | 3.01%   |
| AMD 600 Series Chipset SATA Controller                                         | 73        | 3.01%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 59        | 2.43%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 52        | 2.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 51        | 2.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 46        | 1.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 36        | 1.48%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 34        | 1.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 31        | 1.28%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 31        | 1.28%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 30        | 1.24%   |
| Phison E12 NVMe Controller                                                     | 30        | 1.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 30        | 1.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 29        | 1.19%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 28        | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 28        | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 27        | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 26        | 1.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 26        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 25        | 1.03%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 23        | 0.95%   |
| Intel SSD 660P Series                                                          | 23        | 0.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 0.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 22        | 0.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 22        | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 21        | 0.87%   |
| Phison E16 PCIe4 NVMe Controller                                               | 21        | 0.87%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 21        | 0.87%   |
| Intel SATA Controller [RAID mode]                                              | 21        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21        | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                            | 20        | 0.82%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 19        | 0.78%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 18        | 0.74%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 18        | 0.74%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 17        | 0.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 17        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1033      | 51.29%  |
| NVMe | 823       | 40.86%  |
| RAID | 109       | 5.41%   |
| IDE  | 44        | 2.18%   |
| SAS  | 5         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 703       | 53.62%  |
| AMD    | 608       | 46.38%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 36        | 2.73%   |
| AMD Ryzen 5 3600 6-Core Processor           | 32        | 2.43%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 28        | 2.12%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 21        | 1.59%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 19        | 1.44%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 17        | 1.29%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 16        | 1.21%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 16        | 1.21%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 15        | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 15        | 1.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 15        | 1.14%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 14        | 1.06%   |
| AMD Ryzen 5 7600X 6-Core Processor          | 13        | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 12        | 0.91%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 12        | 0.91%   |
| AMD Ryzen 5 5600 6-Core Processor           | 12        | 0.91%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 12        | 0.91%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 11        | 0.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 11        | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 10        | 0.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 10        | 0.76%   |
| AMD Ryzen 9 7950X3D 16-Core Processor       | 10        | 0.76%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 10        | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 10        | 0.76%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 9         | 0.68%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 9         | 0.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 8         | 0.61%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 8         | 0.61%   |
| AMD Ryzen 7 7700X 8-Core Processor          | 8         | 0.61%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 8         | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 7         | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 7         | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 7         | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7         | 0.53%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 7         | 0.53%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 7         | 0.53%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 7         | 0.53%   |
| AMD Ryzen 9 6900HX with Radeon Graphics     | 7         | 0.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 7         | 0.53%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 7         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 214       | 16.26%  |
| AMD Ryzen 5             | 214       | 16.26%  |
| AMD Ryzen 7             | 212       | 16.11%  |
| Intel Core i7           | 191       | 14.51%  |
| Other                   | 160       | 12.16%  |
| AMD Ryzen 9             | 90        | 6.84%   |
| Intel Core i3           | 46        | 3.5%    |
| Intel Xeon              | 34        | 2.58%   |
| AMD Ryzen 3             | 25        | 1.9%    |
| Intel Celeron           | 21        | 1.6%    |
| AMD FX                  | 14        | 1.06%   |
| Intel Core i9           | 13        | 0.99%   |
| Intel Pentium           | 8         | 0.61%   |
| Intel Core 2 Duo        | 8         | 0.61%   |
| Intel Atom              | 6         | 0.46%   |
| AMD A6                  | 6         | 0.46%   |
| AMD A4                  | 5         | 0.38%   |
| AMD A10                 | 5         | 0.38%   |
| Intel Pentium Dual-Core | 4         | 0.3%    |
| AMD Phenom II X6        | 4         | 0.3%    |
| AMD Phenom II X4        | 4         | 0.3%    |
| AMD A8                  | 3         | 0.23%   |
| Intel Pentium Silver    | 2         | 0.15%   |
| Intel Core 2 Quad       | 2         | 0.15%   |
| AMD Turion 64 X2 Mobile | 2         | 0.15%   |
| AMD Ryzen Threadripper  | 2         | 0.15%   |
| AMD Ryzen 7 PRO         | 2         | 0.15%   |
| AMD Ryzen 5 PRO         | 2         | 0.15%   |
| AMD Athlon              | 2         | 0.15%   |
| Intel Pentium Gold      | 1         | 0.08%   |
| Intel Core m7           | 1         | 0.08%   |
| Intel Core 2 Extreme    | 1         | 0.08%   |
| Intel Core              | 1         | 0.08%   |
| AMD Turion              | 1         | 0.08%   |
| AMD Ryzen 3 PRO         | 1         | 0.08%   |
| AMD PRO A10             | 1         | 0.08%   |
| AMD Phenom II           | 1         | 0.08%   |
| AMD Phenom              | 1         | 0.08%   |
| AMD G                   | 1         | 0.08%   |
| AMD E2                  | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 342       | 26.03%  |
| 6      | 307       | 23.36%  |
| 8      | 286       | 21.77%  |
| 2      | 204       | 15.53%  |
| 12     | 64        | 4.87%   |
| 16     | 42        | 3.2%    |
| 10     | 24        | 1.83%   |
| 14     | 23        | 1.75%   |
| 24     | 10        | 0.76%   |
| 3      | 4         | 0.3%    |
| 1      | 4         | 0.3%    |
| 20     | 3         | 0.23%   |
| 18     | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1307      | 99.69%  |
| 2      | 4         | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1115      | 84.79%  |
| 1      | 200       | 15.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1311      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 773       | 57.64%  |
| 0x08701021 | 40        | 2.98%   |
| 0x0a50000c | 29        | 2.16%   |
| 0x0a601203 | 24        | 1.79%   |
| 0x08108109 | 24        | 1.79%   |
| 0x0a50000d | 22        | 1.64%   |
| 0x306c3    | 20        | 1.49%   |
| 0x306a9    | 20        | 1.49%   |
| 0x0800820d | 19        | 1.42%   |
| 0x0a201016 | 17        | 1.27%   |
| 0x206a7    | 16        | 1.19%   |
| 0x0a20120a | 16        | 1.19%   |
| 0x906ea    | 15        | 1.12%   |
| 0x906e9    | 14        | 1.04%   |
| 0x40651    | 14        | 1.04%   |
| 0xa0652    | 12        | 0.89%   |
| 0x08600106 | 11        | 0.82%   |
| 0x08701030 | 10        | 0.75%   |
| 0x08608103 | 10        | 0.75%   |
| 0x506e3    | 9         | 0.67%   |
| 0x0a404102 | 9         | 0.67%   |
| 0x906a3    | 8         | 0.6%    |
| 0x806c1    | 8         | 0.6%    |
| 0x08600104 | 8         | 0.6%    |
| 0x06000822 | 8         | 0.6%    |
| 0x806e9    | 7         | 0.52%   |
| 0x0a601206 | 7         | 0.52%   |
| 0x0a201204 | 7         | 0.52%   |
| 0x08001138 | 7         | 0.52%   |
| 0xa0655    | 6         | 0.45%   |
| 0x90672    | 6         | 0.45%   |
| 0x0a20120e | 6         | 0.45%   |
| 0x0a201205 | 6         | 0.45%   |
| 0x906ed    | 5         | 0.37%   |
| 0x806d1    | 5         | 0.37%   |
| 0x406e3    | 5         | 0.37%   |
| 0xa0653    | 4         | 0.3%    |
| 0x906ec    | 4         | 0.3%    |
| 0x206d7    | 4         | 0.3%    |
| 0x1067a    | 4         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Zen 3             | 209       | 15.86%  |
| Unknown           | 166       | 12.59%  |
| KabyLake          | 155       | 11.76%  |
| Zen 2             | 126       | 9.56%   |
| Haswell           | 99        | 7.51%   |
| Alderlake Hybrid  | 73        | 5.54%   |
| Zen+              | 70        | 5.31%   |
| CometLake         | 61        | 4.63%   |
| IvyBridge         | 57        | 4.32%   |
| Skylake           | 56        | 4.25%   |
| SandyBridge       | 46        | 3.49%   |
| TigerLake         | 35        | 2.66%   |
| Icelake           | 29        | 2.2%    |
| Zen               | 21        | 1.59%   |
| Piledriver        | 17        | 1.29%   |
| Penryn            | 15        | 1.14%   |
| Broadwell         | 13        | 0.99%   |
| Silvermont        | 11        | 0.83%   |
| K10               | 11        | 0.83%   |
| Goldmont plus     | 9         | 0.68%   |
| Excavator         | 7         | 0.53%   |
| Westmere          | 5         | 0.38%   |
| Steamroller       | 4         | 0.3%    |
| Puma              | 4         | 0.3%    |
| K8 Hammer         | 3         | 0.23%   |
| Bobcat            | 3         | 0.23%   |
| Nehalem           | 2         | 0.15%   |
| Jaguar            | 2         | 0.15%   |
| Goldmont          | 2         | 0.15%   |
| Core              | 2         | 0.15%   |
| Tremont           | 1         | 0.08%   |
| Meteorlake Hybrid | 1         | 0.08%   |
| K8 & K10 hybrid   | 1         | 0.08%   |
| Bulldozer         | 1         | 0.08%   |
| Bonnell           | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 597       | 36.54%  |
| Nvidia | 573       | 35.07%  |
| Intel  | 464       | 28.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 63        | 3.67%   |
| AMD Raphael                                                                 | 60        | 3.49%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 59        | 3.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 55        | 3.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 35        | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 34        | 1.98%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 34        | 1.98%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 32        | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 30        | 1.75%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 30        | 1.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 29        | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 28        | 1.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 28        | 1.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 28        | 1.63%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 28        | 1.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 26        | 1.51%   |
| AMD Rembrandt [Radeon 680M]                                                 | 23        | 1.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 22        | 1.28%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 20        | 1.16%   |
| Intel HD Graphics 620                                                       | 19        | 1.11%   |
| Intel HD Graphics 530                                                       | 19        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 19        | 1.11%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 19        | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 17        | 0.99%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 15        | 0.87%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                             | 14        | 0.82%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 14        | 0.82%   |
| AMD Lucienne                                                                | 14        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 13        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 13        | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 13        | 0.76%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 13        | 0.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 13        | 0.76%   |
| AMD Phoenix1                                                                | 13        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 11        | 0.64%   |
| Intel UHD Graphics 620                                                      | 11        | 0.64%   |
| Intel AlderLake-S GT1                                                       | 11        | 0.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 11        | 0.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 11        | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 10        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 412       | 31.26%  |
| 1 x Nvidia         | 320       | 24.28%  |
| 1 x Intel          | 232       | 17.6%   |
| Intel + Nvidia     | 165       | 12.52%  |
| AMD + Nvidia       | 83        | 6.3%    |
| 2 x AMD            | 70        | 5.31%   |
| Intel + AMD        | 30        | 2.28%   |
| 2 x Nvidia         | 3         | 0.23%   |
| Other              | 1         | 0.08%   |
| 2 x Intel          | 1         | 0.08%   |
| Intel + 2 x Nvidia | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 833       | 63.01%  |
| Proprietary | 463       | 35.02%  |
| Unknown     | 26        | 1.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 633       | 47.31%  |
| 7.01-8.0   | 169       | 12.63%  |
| 8.01-16.0  | 138       | 10.31%  |
| 0.01-0.5   | 131       | 9.79%   |
| 1.01-2.0   | 88        | 6.58%   |
| 3.01-4.0   | 70        | 5.23%   |
| 0.51-1.0   | 41        | 3.06%   |
| 5.01-6.0   | 34        | 2.54%   |
| 16.01-24.0 | 28        | 2.09%   |
| 2.01-3.0   | 6         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 209       | 12.99%  |
| Goldstar                | 133       | 8.27%   |
| AU Optronics            | 123       | 7.64%   |
| BOE                     | 109       | 6.77%   |
| Acer                    | 96        | 5.97%   |
| Dell                    | 87        | 5.41%   |
| Chimei Innolux          | 84        | 5.22%   |
| LG Display              | 78        | 4.85%   |
| BenQ                    | 61        | 3.79%   |
| AOC                     | 58        | 3.6%    |
| ASUSTek Computer        | 56        | 3.48%   |
| Hewlett-Packard         | 50        | 3.11%   |
| Ancor Communications    | 50        | 3.11%   |
| MSI                     | 31        | 1.93%   |
| ViewSonic               | 24        | 1.49%   |
| Philips                 | 24        | 1.49%   |
| PANDA                   | 24        | 1.49%   |
| Apple                   | 24        | 1.49%   |
| Sony                    | 23        | 1.43%   |
| Sharp                   | 21        | 1.31%   |
| Lenovo                  | 21        | 1.31%   |
| Gigabyte Technology     | 16        | 0.99%   |
| Vizio                   | 15        | 0.93%   |
| Sceptre Tech            | 11        | 0.68%   |
| Iiyama                  | 10        | 0.62%   |
| HKC                     | 9         | 0.56%   |
| Toshiba                 | 7         | 0.44%   |
| Mi                      | 7         | 0.44%   |
| InfoVision              | 7         | 0.44%   |
| Unknown                 | 6         | 0.37%   |
| TMX                     | 6         | 0.37%   |
| NEC Computers           | 6         | 0.37%   |
| HUAWEI                  | 6         | 0.37%   |
| Eizo                    | 6         | 0.37%   |
| Insignia                | 5         | 0.31%   |
| Chi Mei Optoelectronics | 5         | 0.31%   |
| SANYO                   | 4         | 0.25%   |
| Pixio                   | 4         | 0.25%   |
| Panasonic               | 4         | 0.25%   |
| DENON                   | 4         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 11        | 0.66%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 9         | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6         | 0.36%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 6         | 0.36%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.36%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 5         | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 5         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 5         | 0.3%    |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 5         | 0.3%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5         | 0.3%    |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.3%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.3%    |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 5         | 0.3%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 4         | 0.24%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 4         | 0.24%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                       | 4         | 0.24%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 4         | 0.24%   |
| LG Display LCD Monitor LGD0555 2880x1920 274x183mm 13.0-inch          | 4         | 0.24%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 4         | 0.24%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.24%   |
| Goldstar 27GL650F GSM5B71 1920x1080 597x336mm 27.0-inch               | 4         | 0.24%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch          | 4         | 0.24%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 4         | 0.24%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 4         | 0.24%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                    | 4         | 0.24%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                    | 4         | 0.24%   |
| Vizio V435-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 3         | 0.18%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                   | 3         | 0.18%   |
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch                | 3         | 0.18%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 3         | 0.18%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 3         | 0.18%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 3         | 0.18%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch | 3         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 701       | 46.92%  |
| 2560x1440 (QHD)    | 206       | 13.79%  |
| 3840x2160 (4K)     | 169       | 11.31%  |
| 1366x768 (WXGA)    | 109       | 7.3%    |
| 3440x1440          | 53        | 3.55%   |
| 1920x1200 (WUXGA)  | 34        | 2.28%   |
| 1680x1050 (WSXGA+) | 26        | 1.74%   |
| 2560x1600          | 24        | 1.61%   |
| 1600x900 (HD+)     | 24        | 1.61%   |
| 2560x1080          | 22        | 1.47%   |
| 1440x900 (WXGA+)   | 18        | 1.2%    |
| 1280x1024 (SXGA)   | 14        | 0.94%   |
| 1360x768           | 13        | 0.87%   |
| 1920x540           | 11        | 0.74%   |
| 3840x1080          | 10        | 0.67%   |
| 2880x1800          | 9         | 0.6%    |
| 2288x1287          | 6         | 0.4%    |
| 3200x2000          | 4         | 0.27%   |
| 2880x1920          | 4         | 0.27%   |
| 2240x1400          | 4         | 0.27%   |
| 1280x800 (WXGA)    | 4         | 0.27%   |
| 800x1280           | 2         | 0.13%   |
| 3840x2400          | 2         | 0.13%   |
| 3840x1600          | 2         | 0.13%   |
| 2736x1824          | 2         | 0.13%   |
| 1600x2560          | 2         | 0.13%   |
| 1600x1200          | 2         | 0.13%   |
| Unknown            | 2         | 0.13%   |
| 5760x1080          | 1         | 0.07%   |
| 3840x2560          | 1         | 0.07%   |
| 3456x2160          | 1         | 0.07%   |
| 3200x1800 (QHD+)   | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 2944x1840          | 1         | 0.07%   |
| 2560x2880          | 1         | 0.07%   |
| 2520x1680          | 1         | 0.07%   |
| 2160x1440          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |
| 1920x550           | 1         | 0.07%   |
| 1280x960           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 274       | 17.23%  |
| 27      | 264       | 16.6%   |
| 24      | 143       | 8.99%   |
| 23      | 111       | 6.98%   |
| 31      | 103       | 6.48%   |
| 21      | 79        | 4.97%   |
| 13      | 73        | 4.59%   |
| 17      | 68        | 4.28%   |
| 34      | 62        | 3.9%    |
| 14      | 60        | 3.77%   |
| 16      | 34        | 2.14%   |
| 84      | 28        | 1.76%   |
| 72      | 21        | 1.32%   |
| 19      | 21        | 1.32%   |
| 32      | 20        | 1.26%   |
| 22      | 20        | 1.26%   |
| Unknown | 19        | 1.19%   |
| 20      | 18        | 1.13%   |
| 40      | 16        | 1.01%   |
| 18      | 16        | 1.01%   |
| 48      | 15        | 0.94%   |
| 26      | 10        | 0.63%   |
| 42      | 9         | 0.57%   |
| 54      | 7         | 0.44%   |
| 49      | 7         | 0.44%   |
| 35      | 7         | 0.44%   |
| 29      | 7         | 0.44%   |
| 142     | 5         | 0.31%   |
| 28      | 5         | 0.31%   |
| 11      | 5         | 0.31%   |
| 7       | 5         | 0.31%   |
| 55      | 4         | 0.25%   |
| 52      | 4         | 0.25%   |
| 33      | 4         | 0.25%   |
| 25      | 4         | 0.25%   |
| 12      | 4         | 0.25%   |
| 69      | 3         | 0.19%   |
| 60      | 3         | 0.19%   |
| 47      | 3         | 0.19%   |
| 43      | 3         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 501-600        | 465       | 30.02%  |
| 301-350        | 395       | 25.5%   |
| 401-500        | 147       | 9.49%   |
| 601-700        | 142       | 9.17%   |
| 701-800        | 85        | 5.49%   |
| 351-400        | 81        | 5.23%   |
| 1501-2000      | 55        | 3.55%   |
| 201-300        | 54        | 3.49%   |
| 1001-1500      | 48        | 3.1%    |
| 801-900        | 31        | 2%      |
| Unknown        | 19        | 1.23%   |
| 901-1000       | 13        | 0.84%   |
| More than 2000 | 6         | 0.39%   |
| 101-200        | 6         | 0.39%   |
| 1-100          | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1063      | 78.86%  |
| 16/10   | 140       | 10.39%  |
| 21/9    | 76        | 5.64%   |
| 5/4     | 16        | 1.19%   |
| 32/9    | 14        | 1.04%   |
| 3/2     | 12        | 0.89%   |
| 4/3     | 7         | 0.52%   |
| 1.00    | 5         | 0.37%   |
| 0.62    | 3         | 0.22%   |
| Unknown | 3         | 0.22%   |
| 1.96    | 2         | 0.15%   |
| 0.67    | 2         | 0.15%   |
| 0.56    | 2         | 0.15%   |
| 2.12    | 1         | 0.07%   |
| 0.89    | 1         | 0.07%   |
| 0.63    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 280       | 17.93%  |
| 201-250        | 277       | 17.73%  |
| 301-350        | 271       | 17.35%  |
| 351-500        | 192       | 12.29%  |
| 81-90          | 97        | 6.21%   |
| More than 1000 | 91        | 5.83%   |
| 151-200        | 67        | 4.29%   |
| 121-130        | 57        | 3.65%   |
| 501-1000       | 56        | 3.59%   |
| 251-300        | 51        | 3.27%   |
| 71-80          | 34        | 2.18%   |
| 111-120        | 28        | 1.79%   |
| Unknown        | 19        | 1.22%   |
| 141-150        | 17        | 1.09%   |
| 1-40           | 8         | 0.51%   |
| 51-60          | 5         | 0.32%   |
| 131-140        | 5         | 0.32%   |
| 61-70          | 4         | 0.26%   |
| 41-50          | 2         | 0.13%   |
| 91-100         | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 596       | 39.73%  |
| 101-120       | 345       | 23%     |
| 121-160       | 336       | 22.4%   |
| 161-240       | 105       | 7%      |
| 1-50          | 66        | 4.4%    |
| More than 240 | 33        | 2.2%    |
| Unknown       | 19        | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 947       | 70.88%  |
| 2     | 308       | 23.05%  |
| 3     | 46        | 3.44%   |
| 0     | 30        | 2.25%   |
| 4     | 5         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 820       | 39.52%  |
| Intel                           | 671       | 32.34%  |
| MediaTek                        | 125       | 6.02%   |
| Qualcomm Atheros                | 114       | 5.49%   |
| Broadcom                        | 77        | 3.71%   |
| TP-Link                         | 39        | 1.88%   |
| Microsoft                       | 35        | 1.69%   |
| Ralink Technology               | 17        | 0.82%   |
| Broadcom Limited                | 15        | 0.72%   |
| Samsung Electronics             | 14        | 0.67%   |
| ASIX Electronics                | 14        | 0.67%   |
| Xiaomi                          | 11        | 0.53%   |
| Marvell Technology Group        | 11        | 0.53%   |
| Ralink                          | 8         | 0.39%   |
| ASUSTek Computer                | 7         | 0.34%   |
| Aquantia                        | 7         | 0.34%   |
| Qualcomm                        | 6         | 0.29%   |
| Nvidia                          | 6         | 0.29%   |
| Qualcomm Atheros Communications | 5         | 0.24%   |
| Google                          | 5         | 0.24%   |
| OPPO Electronics                | 4         | 0.19%   |
| NetGear                         | 4         | 0.19%   |
| Motorola PCS                    | 4         | 0.19%   |
| Mellanox Technologies           | 4         | 0.19%   |
| Lenovo                          | 4         | 0.19%   |
| DisplayLink                     | 4         | 0.19%   |
| D-Link                          | 4         | 0.19%   |
| Hewlett-Packard                 | 3         | 0.14%   |
| Sierra Wireless                 | 2         | 0.1%    |
| Qualcomm Technologies           | 2         | 0.1%    |
| Oculus VR                       | 2         | 0.1%    |
| Linksys                         | 2         | 0.1%    |
| Edimax Technology               | 2         | 0.1%    |
| Dell                            | 2         | 0.1%    |
| D-Link System                   | 2         | 0.1%    |
| Belkin Components               | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM      | 1         | 0.05%   |
| Wacom                           | 1         | 0.05%   |
| U-Blox                          | 1         | 0.05%   |
| T & A Mobile Phones             | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 539       | 22.5%   |
| Realtek RTL8125 2.5GbE Controller                                      | 160       | 6.68%   |
| Intel Wi-Fi 6 AX200                                                    | 119       | 4.97%   |
| Intel Ethernet Controller I225-V                                       | 73        | 3.05%   |
| Intel I211 Gigabit Network Connection                                  | 69        | 2.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 56        | 2.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 55        | 2.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 34        | 1.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 31        | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.21%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 29        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 29        | 1.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28        | 1.17%   |
| Intel Wi-Fi 6 AX201                                                    | 27        | 1.13%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 25        | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 24        | 1%      |
| Intel Wireless 8265 / 8275                                             | 23        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                                   | 23        | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 23        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 22        | 0.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 21        | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 0.83%   |
| Intel Wireless 7265                                                    | 19        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 19        | 0.79%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 18        | 0.75%   |
| Intel Wireless 8260                                                    | 17        | 0.71%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 17        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                   | 17        | 0.71%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 16        | 0.67%   |
| Intel Wireless 7260                                                    | 15        | 0.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 14        | 0.58%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 13        | 0.54%   |
| Realtek 802.11ac NIC                                                   | 13        | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 0.54%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                          | 13        | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 12        | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 12        | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 12        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 503       | 47.27%  |
| Realtek Semiconductor           | 162       | 15.23%  |
| MediaTek                        | 109       | 10.24%  |
| Qualcomm Atheros                | 77        | 7.24%   |
| Broadcom                        | 65        | 6.11%   |
| TP-Link                         | 38        | 3.57%   |
| Microsoft                       | 33        | 3.1%    |
| Ralink Technology               | 17        | 1.6%    |
| Broadcom Limited                | 10        | 0.94%   |
| Ralink                          | 8         | 0.75%   |
| ASUSTek Computer                | 7         | 0.66%   |
| Qualcomm Atheros Communications | 5         | 0.47%   |
| Marvell Technology Group        | 5         | 0.47%   |
| NetGear                         | 4         | 0.38%   |
| D-Link                          | 3         | 0.28%   |
| Sierra Wireless                 | 2         | 0.19%   |
| Qualcomm Technologies           | 2         | 0.19%   |
| Linksys                         | 2         | 0.19%   |
| Edimax Technology               | 2         | 0.19%   |
| Dell                            | 2         | 0.19%   |
| D-Link System                   | 2         | 0.19%   |
| Belkin Components               | 2         | 0.19%   |
| Wacom                           | 1         | 0.09%   |
| Panasonic (Matsushita)          | 1         | 0.09%   |
| Fibocom                         | 1         | 0.09%   |
| AVM                             | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 119       | 11.11%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 55        | 5.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 42        | 3.92%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 34        | 3.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 31        | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 29        | 2.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 29        | 2.71%   |
| Intel Comet Lake PCH CNVi WiFi                                | 29        | 2.71%   |
| Intel Wi-Fi 6 AX201                                           | 27        | 2.52%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 25        | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 24        | 2.24%   |
| Intel Wireless 8265 / 8275                                    | 23        | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 23        | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 22        | 2.05%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 21        | 1.96%   |
| Intel Wireless 7265                                           | 19        | 1.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 19        | 1.77%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 18        | 1.68%   |
| Intel Wireless 8260                                           | 17        | 1.59%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 17        | 1.59%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 16        | 1.49%   |
| Intel Wireless 7260                                           | 15        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 14        | 1.31%   |
| Realtek 802.11ac NIC                                          | 13        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 13        | 1.21%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 12        | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 12        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 12        | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                 | 12        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 10        | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 10        | 0.93%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 10        | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 8         | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 8         | 0.75%   |
| Microsoft Xbox 360 Wireless Adapter                           | 8         | 0.75%   |
| Intel Wireless 3165                                           | 8         | 0.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 7         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 7         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 7         | 0.65%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 6         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 758       | 59.59%  |
| Intel                      | 323       | 25.39%  |
| Qualcomm Atheros           | 47        | 3.69%   |
| Broadcom                   | 25        | 1.97%   |
| MediaTek                   | 16        | 1.26%   |
| ASIX Electronics           | 14        | 1.1%    |
| Xiaomi                     | 11        | 0.86%   |
| Samsung Electronics        | 11        | 0.86%   |
| Aquantia                   | 7         | 0.55%   |
| Qualcomm                   | 6         | 0.47%   |
| Nvidia                     | 6         | 0.47%   |
| Marvell Technology Group   | 6         | 0.47%   |
| Google                     | 5         | 0.39%   |
| Broadcom Limited           | 5         | 0.39%   |
| OPPO Electronics           | 4         | 0.31%   |
| Motorola PCS               | 4         | 0.31%   |
| Mellanox Technologies      | 4         | 0.31%   |
| Lenovo                     | 4         | 0.31%   |
| DisplayLink                | 4         | 0.31%   |
| Hewlett-Packard            | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM | 1         | 0.08%   |
| TP-Link                    | 1         | 0.08%   |
| T & A Mobile Phones        | 1         | 0.08%   |
| Microsoft                  | 1         | 0.08%   |
| JMicron Technology         | 1         | 0.08%   |
| ICS Advent                 | 1         | 0.08%   |
| Huawei Technologies        | 1         | 0.08%   |
| D-Link                     | 1         | 0.08%   |
| Apple                      | 1         | 0.08%   |
| American Megatrends        | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 539       | 41.24%  |
| Realtek RTL8125 2.5GbE Controller                                      | 160       | 12.24%  |
| Intel Ethernet Controller I225-V                                       | 73        | 5.59%   |
| Intel I211 Gigabit Network Connection                                  | 69        | 5.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28        | 2.14%   |
| Intel Ethernet Connection (7) I219-V                                   | 23        | 1.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 1.53%   |
| Intel Ethernet Connection (2) I219-V                                   | 17        | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 14        | 1.07%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                          | 13        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                                   | 12        | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 11        | 0.84%   |
| Intel Ethernet Controller I226-V                                       | 11        | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 9         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.69%   |
| Realtek Killer E2600 GbE Controller                                    | 8         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 8         | 0.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 7         | 0.54%   |
| Intel Ethernet Connection I217-V                                       | 7         | 0.54%   |
| Intel Ethernet Connection (17) I219-V                                  | 7         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 6         | 0.46%   |
| Intel Ethernet Connection (14) I219-V                                  | 6         | 0.46%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.38%   |
| Intel Ethernet Connection (11) I219-V                                  | 5         | 0.38%   |
| Google Pixel 6a                                                        | 5         | 0.38%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 4         | 0.31%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.31%   |
| Motorola PCS moto g84 5G                                               | 4         | 0.31%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.31%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.31%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 0.31%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1174      | 53.73%  |
| WiFi     | 993       | 45.45%  |
| Modem    | 12        | 0.55%   |
| Unknown  | 6         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 725       | 52.73%  |
| WiFi     | 650       | 47.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 717       | 54.44%  |
| 1     | 538       | 40.85%  |
| 3     | 43        | 3.26%   |
| 0     | 14        | 1.06%   |
| 4     | 3         | 0.23%   |
| 6     | 1         | 0.08%   |
| 5     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 882       | 66.52%  |
| Yes  | 444       | 33.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 481       | 49.13%  |
| Realtek Semiconductor           | 89        | 9.09%   |
| Cambridge Silicon Radio         | 75        | 7.66%   |
| MediaTek                        | 55        | 5.62%   |
| IMC Networks                    | 52        | 5.31%   |
| Foxconn / Hon Hai               | 44        | 4.49%   |
| Qualcomm Atheros Communications | 35        | 3.58%   |
| Broadcom                        | 27        | 2.76%   |
| Apple                           | 25        | 2.55%   |
| ASUSTek Computer                | 23        | 2.35%   |
| Lite-On Technology              | 21        | 2.15%   |
| TP-Link                         | 17        | 1.74%   |
| Marvell Semiconductor           | 5         | 0.51%   |
| Toshiba                         | 4         | 0.41%   |
| Ralink                          | 4         | 0.41%   |
| Edimax Technology               | 4         | 0.41%   |
| Unknown                         | 4         | 0.41%   |
| Actions                         | 3         | 0.31%   |
| Realtek                         | 2         | 0.2%    |
| Integrated System Solution      | 2         | 0.2%    |
| Hewlett-Packard                 | 2         | 0.2%    |
| Foxconn International           | 2         | 0.2%    |
| HTC (High Tech Computer)        | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| Dell                            | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 119       | 12.14%  |
| Intel Bluetooth wireless interface                  | 89        | 9.08%   |
| Intel AX201 Bluetooth                               | 79        | 8.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 75        | 7.65%   |
| Realtek Bluetooth Radio                             | 65        | 6.63%   |
| MediaTek Wireless_Device                            | 54        | 5.51%   |
| Intel AX210 Bluetooth                               | 54        | 5.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 47        | 4.8%    |
| Intel AX211 Bluetooth                               | 46        | 4.69%   |
| IMC Networks Wireless_Device                        | 27        | 2.76%   |
| Foxconn / Hon Hai Wireless_Device                   | 24        | 2.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 2.24%   |
| IMC Networks Bluetooth Radio                        | 20        | 2.04%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 17        | 1.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 1.43%   |
| Apple Bluetooth Host Controller                     | 14        | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.33%   |
| ASUS ASUS USB-BT500                                 | 12        | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.82%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 0.61%   |
| Realtek 802.11ac WLAN Adapter                       | 5         | 0.51%   |
| Marvell Bluetooth and Wireless LAN Composite        | 5         | 0.51%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.51%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.51%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.41%   |
| Lite-On Bluetooth Radio                             | 4         | 0.41%   |
| Lite-On Bluetooth Device                            | 4         | 0.41%   |
| IMC Networks Bluetooth Device                       | 4         | 0.41%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.41%   |
| Unknown                                             | 4         | 0.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.31%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.31%   |
| Lite-On Wireless_Device                             | 3         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| AMD                        | 713       | 29.15%  |
| Intel                      | 691       | 28.25%  |
| Nvidia                     | 499       | 20.4%   |
| C-Media Electronics        | 63        | 2.58%   |
| Logitech                   | 55        | 2.25%   |
| Kingston Technology        | 27        | 1.1%    |
| ASUSTek Computer           | 27        | 1.1%    |
| SteelSeries ApS            | 26        | 1.06%   |
| Creative Labs              | 23        | 0.94%   |
| Razer USA                  | 21        | 0.86%   |
| Sony                       | 20        | 0.82%   |
| Micro Star International   | 17        | 0.7%    |
| Creative Technology        | 15        | 0.61%   |
| Corsair                    | 15        | 0.61%   |
| JMTek                      | 13        | 0.53%   |
| Focusrite-Novation         | 12        | 0.49%   |
| Texas Instruments          | 11        | 0.45%   |
| Blue Microphones           | 11        | 0.45%   |
| Hewlett-Packard            | 10        | 0.41%   |
| Samson Technologies        | 9         | 0.37%   |
| Realtek Semiconductor      | 8         | 0.33%   |
| Plantronics                | 8         | 0.33%   |
| PreSonus Audio Electronics | 7         | 0.29%   |
| BEHRINGER International    | 7         | 0.29%   |
| Audio-Technica             | 7         | 0.29%   |
| Astro Gaming               | 6         | 0.25%   |
| Apple                      | 6         | 0.25%   |
| Lenovo                     | 5         | 0.2%    |
| GN Netcom                  | 5         | 0.2%    |
| Generalplus Technology     | 5         | 0.2%    |
| SAVITECH                   | 4         | 0.16%   |
| ROCCAT                     | 4         | 0.16%   |
| Medeli Electronics         | 3         | 0.12%   |
| Jieli Technology           | 3         | 0.12%   |
| Giga-Byte Technology       | 3         | 0.12%   |
| Elgato Systems             | 3         | 0.12%   |
| ASRock                     | 3         | 0.12%   |
| XMOS                       | 2         | 0.08%   |
| VIA Technologies           | 2         | 0.08%   |
| Turtle Beach               | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 270       | 8.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 212       | 7.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 144       | 4.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 98        | 3.25%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 97        | 3.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 71        | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 66        | 2.19%   |
| Nvidia GA104 High Definition Audio Controller                              | 59        | 1.96%   |
| Intel Sunrise Point-LP HD Audio                                            | 54        | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 53        | 1.76%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 53        | 1.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49        | 1.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 43        | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                              | 42        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42        | 1.39%   |
| Intel Comet Lake PCH cAVS                                                  | 41        | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 41        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 40        | 1.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 40        | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 38        | 1.26%   |
| AMD Navi 10 HDMI Audio                                                     | 36        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 35        | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 35        | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                              | 33        | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 33        | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                     | 31        | 1.03%   |
| Intel 200 Series PCH HD Audio                                              | 30        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 0.96%   |
| Intel 8 Series HD Audio Controller                                         | 29        | 0.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 27        | 0.9%    |
| Nvidia TU104 HD Audio Controller                                           | 25        | 0.83%   |
| Intel Raptor Lake High Definition Audio Controller                         | 25        | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 24        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 22        | 0.73%   |
| Nvidia AD107 High Definition Audio Controller                              | 22        | 0.73%   |
| ASUSTek Computer USB Audio                                                 | 22        | 0.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22        | 0.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 19        | 0.63%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 19        | 0.63%   |
| AMD FCH Azalia Controller                                                  | 18        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 69        | 18.8%   |
| Corsair                      | 57        | 15.53%  |
| Kingston                     | 42        | 11.44%  |
| G.Skill                      | 41        | 11.17%  |
| SK hynix                     | 38        | 10.35%  |
| Micron Technology            | 37        | 10.08%  |
| Crucial                      | 20        | 5.45%   |
| Unknown                      | 12        | 3.27%   |
| A-DATA Technology            | 11        | 3%      |
| Team                         | 10        | 2.72%   |
| Unknown                      | 6         | 1.63%   |
| Ramaxel Technology           | 5         | 1.36%   |
| Patriot                      | 4         | 1.09%   |
| Unknown (ABCD)               | 3         | 0.82%   |
| Transcend                    | 1         | 0.27%   |
| Timetec                      | 1         | 0.27%   |
| Patriot Memory (PDP Systems) | 1         | 0.27%   |
| Nanya Technology             | 1         | 0.27%   |
| KLEVV                        | 1         | 0.27%   |
| Hewlett-Packard              | 1         | 0.27%   |
| Gowe                         | 1         | 0.27%   |
| GOODRAM                      | 1         | 0.27%   |
| Golden Empire                | 1         | 0.27%   |
| Elpida                       | 1         | 0.27%   |
| Asgard                       | 1         | 0.27%   |
| AMD                          | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.81%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 1.55%   |
| Unknown                                                          | 6         | 1.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.03%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.03%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.03%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.03%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s              | 4         | 1.03%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 4         | 1.03%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 4         | 1.03%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 3         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.78%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 3         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.78%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s                 | 3         | 0.78%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 3         | 0.78%   |
| G.Skill RAM F5-6000J3038F16G 16GB DIMM DDR5 6000MT/s             | 3         | 0.78%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s            | 3         | 0.78%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s           | 3         | 0.78%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 3         | 0.78%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 2         | 0.52%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 2         | 0.52%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 2         | 0.52%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 2         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.52%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 0.52%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 0.52%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 2         | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.52%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 207       | 63.69%  |
| DDR5    | 49        | 15.08%  |
| DDR3    | 42        | 12.92%  |
| LPDDR4  | 14        | 4.31%   |
| LPDDR5  | 4         | 1.23%   |
| Unknown | 4         | 1.23%   |
| LPDDR3  | 3         | 0.92%   |
| SDRAM   | 1         | 0.31%   |
| DDR2    | 1         | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 176       | 53.82%  |
| SODIMM       | 128       | 39.14%  |
| Row Of Chips | 22        | 6.73%   |
| Unknown      | 1         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 146       | 42.07%  |
| 16384 | 106       | 30.55%  |
| 4096  | 44        | 12.68%  |
| 32768 | 35        | 10.09%  |
| 2048  | 12        | 3.46%   |
| 1024  | 2         | 0.58%   |
| 24576 | 1         | 0.29%   |
| 12288 | 1         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 87        | 25.22%  |
| 3600  | 35        | 10.14%  |
| 2667  | 33        | 9.57%   |
| 1600  | 31        | 8.99%   |
| 6000  | 16        | 4.64%   |
| 2400  | 16        | 4.64%   |
| 4800  | 15        | 4.35%   |
| 5600  | 12        | 3.48%   |
| 3733  | 12        | 3.48%   |
| 2133  | 11        | 3.19%   |
| 3800  | 9         | 2.61%   |
| 4267  | 7         | 2.03%   |
| 1333  | 7         | 2.03%   |
| 6400  | 6         | 1.74%   |
| 5200  | 4         | 1.16%   |
| 4000  | 4         | 1.16%   |
| 3534  | 4         | 1.16%   |
| 3266  | 4         | 1.16%   |
| 1867  | 4         | 1.16%   |
| 3466  | 3         | 0.87%   |
| 3400  | 3         | 0.87%   |
| 2933  | 2         | 0.58%   |
| 2666  | 2         | 0.58%   |
| 1066  | 2         | 0.58%   |
| 8000  | 1         | 0.29%   |
| 7500  | 1         | 0.29%   |
| 5800  | 1         | 0.29%   |
| 4266  | 1         | 0.29%   |
| 3933  | 1         | 0.29%   |
| 3866  | 1         | 0.29%   |
| 3533  | 1         | 0.29%   |
| 3334  | 1         | 0.29%   |
| 3333  | 1         | 0.29%   |
| 3100  | 1         | 0.29%   |
| 3000  | 1         | 0.29%   |
| 2934  | 1         | 0.29%   |
| 2800  | 1         | 0.29%   |
| 1334  | 1         | 0.29%   |
| 975   | 1         | 0.29%   |
| 800   | 1         | 0.29%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 8         | 36.36%  |
| Brother Industries  | 6         | 27.27%  |
| Hewlett-Packard     | 4         | 18.18%  |
| STMicroelectronics  | 1         | 4.55%   |
| Seiko Epson         | 1         | 4.55%   |
| Samsung Electronics | 1         | 4.55%   |
| Dell                | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother HL-L2320D series                                  | 2         | 9.09%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 4.55%   |
| Seiko Epson XP-2100 Series                                | 1         | 4.55%   |
| Samsung Composite Device                                  | 1         | 4.55%   |
| HP ENVY 6400 series                                       | 1         | 4.55%   |
| HP DeskJet Plus 4100 series                               | 1         | 4.55%   |
| HP DeskJet 2300 series                                    | 1         | 4.55%   |
| HP Color LaserJet CP1215                                  | 1         | 4.55%   |
| Dell 1130 Laser Printer                                   | 1         | 4.55%   |
| Canon TS700 series                                        | 1         | 4.55%   |
| Canon TR8500 series                                       | 1         | 4.55%   |
| Canon TR4500 series                                       | 1         | 4.55%   |
| Canon PIXMA MX370 Series                                  | 1         | 4.55%   |
| Canon PIXMA MP495                                         | 1         | 4.55%   |
| Canon PIXMA MG3600 Series                                 | 1         | 4.55%   |
| Canon G2000 series                                        | 1         | 4.55%   |
| Canon CanoScan LiDE 300                                   | 1         | 4.55%   |
| Brother MFC-L2710DN series                                | 1         | 4.55%   |
| Brother MFC-J460DW                                        | 1         | 4.55%   |
| Brother HL-L2370DW series                                 | 1         | 4.55%   |
| Brother DCP-1510                                          | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |
| Mustek Systems  | 1         | 20%     |
| Canon           | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 20%     |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 20%     |
| HP ScanJet 82x0C                                        | 1         | 20%     |
| HP ScanJet 2400c                                        | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 104       | 16.51%  |
| Logitech                               | 63        | 10%     |
| IMC Networks                           | 54        | 8.57%   |
| Microdia                               | 38        | 6.03%   |
| Realtek Semiconductor                  | 36        | 5.71%   |
| Sunplus Innovation Technology          | 33        | 5.24%   |
| Apple                                  | 31        | 4.92%   |
| Quanta                                 | 28        | 4.44%   |
| Bison Electronics                      | 25        | 3.97%   |
| Cheng Uei Precision Industry (Foxlink) | 21        | 3.33%   |
| Syntek                                 | 19        | 3.02%   |
| Sonix Technology                       | 19        | 3.02%   |
| Microsoft                              | 17        | 2.7%    |
| Luxvisions Innotech Limited            | 14        | 2.22%   |
| Acer                                   | 14        | 2.22%   |
| Lite-On Technology                     | 13        | 2.06%   |
| Suyin                                  | 11        | 1.75%   |
| Samsung Electronics                    | 7         | 1.11%   |
| SunplusIT                              | 5         | 0.79%   |
| AVerMedia Technologies                 | 5         | 0.79%   |
| Silicon Motion                         | 4         | 0.63%   |
| Razer USA                              | 4         | 0.63%   |
| MacroSilicon                           | 4         | 0.63%   |
| Elgato Systems                         | 4         | 0.63%   |
| Tobii Technology AB                    | 3         | 0.48%   |
| Generalplus Technology                 | 3         | 0.48%   |
| ARC International                      | 3         | 0.48%   |
| Z-Star Microelectronics                | 2         | 0.32%   |
| Shine-optics                           | 2         | 0.32%   |
| Ricoh                                  | 2         | 0.32%   |
| LG Electronics                         | 2         | 0.32%   |
| Lenovo                                 | 2         | 0.32%   |
| Intel                                  | 2         | 0.32%   |
| HRY                                    | 2         | 0.32%   |
| Hewlett-Packard                        | 2         | 0.32%   |
| Alcor Micro                            | 2         | 0.32%   |
| 2M UVC CAMERA                          | 2         | 0.32%   |
| YGTek                                  | 1         | 0.16%   |
| WCM_USB                                | 1         | 0.16%   |
| Trust                                  | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 24        | 3.77%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 23        | 3.62%   |
| Logitech HD Pro Webcam C920                         | 21        | 3.3%    |
| Realtek Integrated_Webcam_HD                        | 18        | 2.83%   |
| Logitech Webcam C270                                | 16        | 2.52%   |
| IMC Networks Integrated Camera                      | 15        | 2.36%   |
| Microdia Integrated_Webcam_HD                       | 14        | 2.2%    |
| Syntek Integrated Camera                            | 13        | 2.04%   |
| Sonix USB2.0 HD UVC WebCam                          | 12        | 1.89%   |
| Logitech C922 Pro Stream Webcam                     | 11        | 1.73%   |
| Chicony HD WebCam                                   | 11        | 1.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 11        | 1.73%   |
| Bison HD Webcam                                     | 9         | 1.42%   |
| Apple FaceTime HD Camera (Built-in)                 | 8         | 1.26%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 1.1%    |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 1.1%    |
| Microdia USB 2.0 Camera                             | 7         | 1.1%    |
| Quanta HP Wide Vision HD Camera                     | 6         | 0.94%   |
| Quanta HP TrueVision HD Camera                      | 6         | 0.94%   |
| Microsoft LifeCam Cinema                            | 6         | 0.94%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 6         | 0.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 0.94%   |
| Chicony HD User Facing                              | 6         | 0.94%   |
| Bison Integrated Camera                             | 6         | 0.94%   |
| Sunplus HD WebCam                                   | 5         | 0.79%   |
| Sunplus Full HD webcam                              | 5         | 0.79%   |
| Quanta HD User Facing                               | 5         | 0.79%   |
| Logitech StreamCam                                  | 5         | 0.79%   |
| Chicony HP Truevision HD                            | 5         | 0.79%   |
| Apple FaceTime HD Camera                            | 5         | 0.79%   |
| Acer BisonCam,NB Pro                                | 5         | 0.79%   |
| Sonix USB2.0 FHD UVC WebCam                         | 4         | 0.63%   |
| Realtek USB Camera                                  | 4         | 0.63%   |
| MacroSilicon USB Video                              | 4         | 0.63%   |
| Lite-On Integrated Camera                           | 4         | 0.63%   |
| Chicony USB 2.0 Camera                              | 4         | 0.63%   |
| Chicony Integrated IR Camera                        | 4         | 0.63%   |
| Chicony HP Wide Vision HD Camera                    | 4         | 0.63%   |
| Chicony EasyCamera                                  | 4         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 24        | 32.88%  |
| Synaptics                          | 18        | 24.66%  |
| Shenzhen Goodix Technology         | 15        | 20.55%  |
| Elan Microelectronics              | 9         | 12.33%  |
| Realtek USB2.0 Finger Print Bridge | 3         | 4.11%   |
| LighTuning Technology              | 2         | 2.74%   |
| Focal-systems.Corp                 | 2         | 2.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 9         | 12.33%  |
| Shenzhen Goodix  FingerPrint Device                             | 9         | 12.33%  |
| Shenzhen Goodix Fingerprint Reader                              | 5         | 6.85%   |
| Validity Sensors Synaptics WBDI                                 | 4         | 5.48%   |
| Elan ELAN:Fingerprint                                           | 4         | 5.48%   |
| Elan ELAN:ARM-M4                                                | 4         | 5.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 3         | 4.11%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 3         | 4.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 4.11%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 4.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 2         | 2.74%   |
| Synaptics WBDI Device                                           | 2         | 2.74%   |
| Synaptics UWP WBDI                                              | 2         | 2.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 2.74%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 2.74%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                       | 2         | 2.74%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.37%   |
| Validity Sensors VFS491                                         | 1         | 1.37%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.37%   |
| Synaptics WBDI                                                  | 1         | 1.37%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.37%   |
| Synaptics TouchPad                                              | 1         | 1.37%   |
| Synaptics  WBDI                                                 | 1         | 1.37%   |
| Synaptics Prometheus Fingerprint Reader                         | 1         | 1.37%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.37%   |
| Synaptics Fingerprint scanner                                   | 1         | 1.37%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.37%   |
| LighTuning Fingerprint Sensor                                   | 1         | 1.37%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.37%   |
| Elan WBF Fingerprint Sensor                                     | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 11        | 50%     |
| Alcor Micro           | 7         | 31.82%  |
| Realtek Semiconductor | 2         | 9.09%   |
| Gemalto (was Gemplus) | 1         | 4.55%   |
| CHERRY                | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 31.82%  |
| Broadcom 5880                                                                | 5         | 22.73%  |
| Broadcom 58200                                                               | 3         | 13.64%  |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 9.09%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 4.55%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1007      | 75.32%  |
| 1     | 287       | 21.47%  |
| 2     | 38        | 2.84%   |
| 3     | 5         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 96        | 25.74%  |
| Net/wireless             | 92        | 24.66%  |
| Fingerprint reader       | 71        | 19.03%  |
| Multimedia controller    | 59        | 15.82%  |
| Unassigned class         | 12        | 3.22%   |
| Sound                    | 8         | 2.14%   |
| Camera                   | 8         | 2.14%   |
| Bluetooth                | 6         | 1.61%   |
| Net/ethernet             | 5         | 1.34%   |
| Chipcard                 | 4         | 1.07%   |
| Card reader              | 3         | 0.8%    |
| Network                  | 2         | 0.54%   |
| Communication controller | 2         | 0.54%   |
| Unclassified device      | 1         | 0.27%   |
| Storage/raid             | 1         | 0.27%   |
| Storage/nvme             | 1         | 0.27%   |
| Storage                  | 1         | 0.27%   |
| Modem                    | 1         | 0.27%   |

