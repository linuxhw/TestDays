ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 2807

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [c959833db6](https://linux-hardware.org/?probe=c959833db6) | Jun 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [3932620fb9](https://linux-hardware.org/?probe=3932620fb9) | Jun 30, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [eb31590a2c](https://linux-hardware.org/?probe=eb31590a2c) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [b8194aee09](https://linux-hardware.org/?probe=b8194aee09) | Jun 28, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [98ad52d973](https://linux-hardware.org/?probe=98ad52d973) | Jun 28, 2023 |
| AZW           | GTR V02                     | Desktop     | [d8a1975328](https://linux-hardware.org/?probe=d8a1975328) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| HP            | 2B2C                        | Desktop     | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [dc32791d25](https://linux-hardware.org/?probe=dc32791d25) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [adf7a275be](https://linux-hardware.org/?probe=adf7a275be) | Jun 27, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6958b0e619](https://linux-hardware.org/?probe=6958b0e619) | Jun 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9e3cbeb0f5](https://linux-hardware.org/?probe=9e3cbeb0f5) | Jun 27, 2023 |
| Dell          | Latitude E6230              | Notebook    | [b52e22e663](https://linux-hardware.org/?probe=b52e22e663) | Jun 27, 2023 |
| ASRock        | G31M-S                      | Desktop     | [2437008395](https://linux-hardware.org/?probe=2437008395) | Jun 26, 2023 |
| HP            | 859B                        | Desktop     | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [13c7f88d66](https://linux-hardware.org/?probe=13c7f88d66) | Jun 26, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [b598080123](https://linux-hardware.org/?probe=b598080123) | Jun 26, 2023 |
| MSI           | GP72MVR 7RGX                | Notebook    | [7fa12ec2d8](https://linux-hardware.org/?probe=7fa12ec2d8) | Jun 26, 2023 |
| HP            | 8599                        | Desktop     | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [bc4e778aa5](https://linux-hardware.org/?probe=bc4e778aa5) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [3b27404402](https://linux-hardware.org/?probe=3b27404402) | Jun 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3df76bbd0e](https://linux-hardware.org/?probe=3df76bbd0e) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [49172baecf](https://linux-hardware.org/?probe=49172baecf) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1a21c582de](https://linux-hardware.org/?probe=1a21c582de) | Jun 26, 2023 |
| HP            | 2B2C                        | Desktop     | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [1a5d46559c](https://linux-hardware.org/?probe=1a5d46559c) | Jun 25, 2023 |
| Intel         | X99H                        | Desktop     | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [f84d78f3cf](https://linux-hardware.org/?probe=f84d78f3cf) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Intel         | H61                         | Desktop     | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| HP            | 0A54h                       | Desktop     | [7383b90fc8](https://linux-hardware.org/?probe=7383b90fc8) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| AZW           | GT-R                        | Notebook    | [11f032f354](https://linux-hardware.org/?probe=11f032f354) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cafe332307](https://linux-hardware.org/?probe=cafe332307) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [007cf1edce](https://linux-hardware.org/?probe=007cf1edce) | Jun 23, 2023 |
| HP            | 0A54h                       | Desktop     | [8cf79bc35e](https://linux-hardware.org/?probe=8cf79bc35e) | Jun 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbe9c9751](https://linux-hardware.org/?probe=abbe9c9751) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [645a24c7bc](https://linux-hardware.org/?probe=645a24c7bc) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Dell          | Latitude E6420              | Notebook    | [162293d893](https://linux-hardware.org/?probe=162293d893) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | GL73 8RD                    | Notebook    | [2739b46bbe](https://linux-hardware.org/?probe=2739b46bbe) | Jun 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [70b047f976](https://linux-hardware.org/?probe=70b047f976) | Jun 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [2807f81cc7](https://linux-hardware.org/?probe=2807f81cc7) | Jun 22, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [bbdbdd30a9](https://linux-hardware.org/?probe=bbdbdd30a9) | Jun 22, 2023 |
| HP            | 2B2C                        | Desktop     | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| HP            | 802F                        | Desktop     | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Sony          | SVE1712C1EW                 | Notebook    | [12f0ee026f](https://linux-hardware.org/?probe=12f0ee026f) | Jun 22, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [5199a5d1f8](https://linux-hardware.org/?probe=5199a5d1f8) | Jun 22, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [198b248306](https://linux-hardware.org/?probe=198b248306) | Jun 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [31d17d4d65](https://linux-hardware.org/?probe=31d17d4d65) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [eba6a24be2](https://linux-hardware.org/?probe=eba6a24be2) | Jun 21, 2023 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| HP            | 802F                        | Desktop     | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0a36c0985d](https://linux-hardware.org/?probe=0a36c0985d) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0ccace2cfb](https://linux-hardware.org/?probe=0ccace2cfb) | Jun 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3e09affd03](https://linux-hardware.org/?probe=3e09affd03) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [3acc831573](https://linux-hardware.org/?probe=3acc831573) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [f4cf5bef09](https://linux-hardware.org/?probe=f4cf5bef09) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9fe2c6961e](https://linux-hardware.org/?probe=9fe2c6961e) | Jun 18, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [2131eadb5b](https://linux-hardware.org/?probe=2131eadb5b) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [8385742d7d](https://linux-hardware.org/?probe=8385742d7d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Intel         | H55                         | Desktop     | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| HP            | 886C                        | Desktop     | [ef429234c7](https://linux-hardware.org/?probe=ef429234c7) | Jun 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1412c501d2](https://linux-hardware.org/?probe=1412c501d2) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [896d66d33f](https://linux-hardware.org/?probe=896d66d33f) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [b26c331bfc](https://linux-hardware.org/?probe=b26c331bfc) | Jun 16, 2023 |
| Intel         | H55                         | Desktop     | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [82c3257031](https://linux-hardware.org/?probe=82c3257031) | Jun 16, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4448a99385](https://linux-hardware.org/?probe=4448a99385) | Jun 16, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Intel         | H61                         | Desktop     | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [dba6acd01e](https://linux-hardware.org/?probe=dba6acd01e) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [550aa0fda6](https://linux-hardware.org/?probe=550aa0fda6) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [0e499971b7](https://linux-hardware.org/?probe=0e499971b7) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0b917dc778](https://linux-hardware.org/?probe=0b917dc778) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bd6a04d15d](https://linux-hardware.org/?probe=bd6a04d15d) | Jun 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a1f1e134c](https://linux-hardware.org/?probe=6a1f1e134c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c3ec3eaa27](https://linux-hardware.org/?probe=c3ec3eaa27) | Jun 13, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [b9e0fd4223](https://linux-hardware.org/?probe=b9e0fd4223) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [58235def6c](https://linux-hardware.org/?probe=58235def6c) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7be8732d39](https://linux-hardware.org/?probe=7be8732d39) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [66a01fdc35](https://linux-hardware.org/?probe=66a01fdc35) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [f92739d54b](https://linux-hardware.org/?probe=f92739d54b) | Jun 11, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| HP            | OMEN by Laptop 15t-en000    | Notebook    | [cdda8d0103](https://linux-hardware.org/?probe=cdda8d0103) | Jun 11, 2023 |
| HP            | 2B0D A01                    | All in one  | [b4f5677d00](https://linux-hardware.org/?probe=b4f5677d00) | Jun 11, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [8a07e36a48](https://linux-hardware.org/?probe=8a07e36a48) | Jun 11, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [396e828c07](https://linux-hardware.org/?probe=396e828c07) | Jun 11, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [864729436a](https://linux-hardware.org/?probe=864729436a) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [07dac575d9](https://linux-hardware.org/?probe=07dac575d9) | Jun 10, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [49ebfc0459](https://linux-hardware.org/?probe=49ebfc0459) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| MSI           | MS-B9321                    | Desktop     | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| Lenovo        | ThinkPad T440 20B6005RUS    | Notebook    | [e7ea5a9368](https://linux-hardware.org/?probe=e7ea5a9368) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5446a0003e](https://linux-hardware.org/?probe=5446a0003e) | Jun 10, 2023 |
| HP            | Notebook                    | Notebook    | [9487146a2f](https://linux-hardware.org/?probe=9487146a2f) | Jun 09, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [9b52b20f3e](https://linux-hardware.org/?probe=9b52b20f3e) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [c5accf4cf8](https://linux-hardware.org/?probe=c5accf4cf8) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [45e51a6b5d](https://linux-hardware.org/?probe=45e51a6b5d) | Jun 09, 2023 |
| HP            | 2B0D A01                    | All in one  | [84275606e0](https://linux-hardware.org/?probe=84275606e0) | Jun 09, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [c14dcffa32](https://linux-hardware.org/?probe=c14dcffa32) | Jun 08, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3f04b950e8](https://linux-hardware.org/?probe=3f04b950e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [8d48df5869](https://linux-hardware.org/?probe=8d48df5869) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [73bc5d84c9](https://linux-hardware.org/?probe=73bc5d84c9) | Jun 07, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [281be42f34](https://linux-hardware.org/?probe=281be42f34) | Jun 07, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [6eeacffa3c](https://linux-hardware.org/?probe=6eeacffa3c) | Jun 07, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [db91b1b71c](https://linux-hardware.org/?probe=db91b1b71c) | Jun 07, 2023 |
| Dell          | 06D7TR A01                  | Desktop     | [8db1a8c132](https://linux-hardware.org/?probe=8db1a8c132) | Jun 06, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d2c05f91c4](https://linux-hardware.org/?probe=d2c05f91c4) | Jun 06, 2023 |
| HP            | 8053                        | Desktop     | [29a84ce224](https://linux-hardware.org/?probe=29a84ce224) | Jun 06, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [249f9343d0](https://linux-hardware.org/?probe=249f9343d0) | Jun 06, 2023 |
| Win elemen... | M600                        | Desktop     | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bdfe605b6a](https://linux-hardware.org/?probe=bdfe605b6a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Dell          | Precision 7510              | Notebook    | [2a465173d3](https://linux-hardware.org/?probe=2a465173d3) | Jun 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [18663e1382](https://linux-hardware.org/?probe=18663e1382) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [c11012336c](https://linux-hardware.org/?probe=c11012336c) | Jun 05, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [917462f8c8](https://linux-hardware.org/?probe=917462f8c8) | Jun 05, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a39c2e8d55](https://linux-hardware.org/?probe=a39c2e8d55) | Jun 04, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [b0efe96508](https://linux-hardware.org/?probe=b0efe96508) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [6f8af3d7af](https://linux-hardware.org/?probe=6f8af3d7af) | Jun 03, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [b92c18e955](https://linux-hardware.org/?probe=b92c18e955) | Jun 03, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 2325SLU       | Notebook    | [3a1d630346](https://linux-hardware.org/?probe=3a1d630346) | Jun 03, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [30a95a3f53](https://linux-hardware.org/?probe=30a95a3f53) | Jun 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [e28ef4a6b7](https://linux-hardware.org/?probe=e28ef4a6b7) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c9e073b763](https://linux-hardware.org/?probe=c9e073b763) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [ca1bce793b](https://linux-hardware.org/?probe=ca1bce793b) | Jun 01, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1bd92e67d7](https://linux-hardware.org/?probe=1bd92e67d7) | Jun 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [d75bfc397f](https://linux-hardware.org/?probe=d75bfc397f) | Jun 01, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [270fcf5e69](https://linux-hardware.org/?probe=270fcf5e69) | May 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [d21f59bea5](https://linux-hardware.org/?probe=d21f59bea5) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Acer          | Predator G9-793             | Notebook    | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [eae4d1e9ba](https://linux-hardware.org/?probe=eae4d1e9ba) | May 31, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2ad4b7fd55](https://linux-hardware.org/?probe=2ad4b7fd55) | May 30, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| HP            | 82DC 1000                   | All in one  | [8300907fc1](https://linux-hardware.org/?probe=8300907fc1) | May 30, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [5c089f9b06](https://linux-hardware.org/?probe=5c089f9b06) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Dell          | 002KVM A01                  | Desktop     | [09d2d63c82](https://linux-hardware.org/?probe=09d2d63c82) | May 30, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8e0413af72](https://linux-hardware.org/?probe=8e0413af72) | May 30, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [9171b7f0f0](https://linux-hardware.org/?probe=9171b7f0f0) | May 29, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [829c193554](https://linux-hardware.org/?probe=829c193554) | May 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [b90162f812](https://linux-hardware.org/?probe=b90162f812) | May 29, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [77e5b682ff](https://linux-hardware.org/?probe=77e5b682ff) | May 28, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [519e04a228](https://linux-hardware.org/?probe=519e04a228) | May 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [efd2db0783](https://linux-hardware.org/?probe=efd2db0783) | May 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [cb642c7b9d](https://linux-hardware.org/?probe=cb642c7b9d) | May 27, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [b5fd752412](https://linux-hardware.org/?probe=b5fd752412) | May 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d5d9543a5a](https://linux-hardware.org/?probe=d5d9543a5a) | May 26, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [ca130b5f89](https://linux-hardware.org/?probe=ca130b5f89) | May 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3392305134](https://linux-hardware.org/?probe=3392305134) | May 26, 2023 |
| HP            | 8437                        | Desktop     | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| ASUSTek       | X751LAB                     | Notebook    | [02b17f35d9](https://linux-hardware.org/?probe=02b17f35d9) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13906a8f3d](https://linux-hardware.org/?probe=13906a8f3d) | May 26, 2023 |
| A14CR         | Unknown                     | Notebook    | [a504061244](https://linux-hardware.org/?probe=a504061244) | May 25, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b00cde0e71](https://linux-hardware.org/?probe=b00cde0e71) | May 25, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [52e1964d2c](https://linux-hardware.org/?probe=52e1964d2c) | May 25, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| Dell          | Precision 7510              | Notebook    | [8c677420fa](https://linux-hardware.org/?probe=8c677420fa) | May 25, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1387725836](https://linux-hardware.org/?probe=1387725836) | May 24, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c309714d15](https://linux-hardware.org/?probe=c309714d15) | May 23, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a2986e9b7a](https://linux-hardware.org/?probe=a2986e9b7a) | May 23, 2023 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [b7efa91563](https://linux-hardware.org/?probe=b7efa91563) | May 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Dell          | Precision 7510              | Notebook    | [15458a1b29](https://linux-hardware.org/?probe=15458a1b29) | May 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [87b976a24c](https://linux-hardware.org/?probe=87b976a24c) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [a1fb857bcc](https://linux-hardware.org/?probe=a1fb857bcc) | May 22, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | Notebook    | [7cba5b3595](https://linux-hardware.org/?probe=7cba5b3595) | May 22, 2023 |
| HP            | 8599                        | Desktop     | [2e9caaf13a](https://linux-hardware.org/?probe=2e9caaf13a) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [cf10c1fb13](https://linux-hardware.org/?probe=cf10c1fb13) | May 21, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| ASUSTek       | X540SC                      | Notebook    | [240bb6c246](https://linux-hardware.org/?probe=240bb6c246) | May 21, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [e7a27c7429](https://linux-hardware.org/?probe=e7a27c7429) | May 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [2df0364d3c](https://linux-hardware.org/?probe=2df0364d3c) | May 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [222ebac915](https://linux-hardware.org/?probe=222ebac915) | May 21, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [bc16fc021e](https://linux-hardware.org/?probe=bc16fc021e) | May 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1fdf5742d0](https://linux-hardware.org/?probe=1fdf5742d0) | May 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [3e94769b79](https://linux-hardware.org/?probe=3e94769b79) | May 20, 2023 |
| Lenovo        | ThinkPad T430 2347EA2       | Notebook    | [dc3fdbd5ff](https://linux-hardware.org/?probe=dc3fdbd5ff) | May 20, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [14e978a000](https://linux-hardware.org/?probe=14e978a000) | May 20, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [d687dbc74a](https://linux-hardware.org/?probe=d687dbc74a) | May 20, 2023 |
| HP            | 8433 11                     | Desktop     | [5d9e3a1dcc](https://linux-hardware.org/?probe=5d9e3a1dcc) | May 20, 2023 |
| Eluktronic... | MAG-15 1660Ti               | Notebook    | [55ced5d6bb](https://linux-hardware.org/?probe=55ced5d6bb) | May 20, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b001b01a08](https://linux-hardware.org/?probe=b001b01a08) | May 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [76592cf444](https://linux-hardware.org/?probe=76592cf444) | May 19, 2023 |
| NEC Comput... | PC-VK26TXZCM                | Notebook    | [064b725160](https://linux-hardware.org/?probe=064b725160) | May 19, 2023 |
| Lenovo        | ThinkPad T430 2347EA2       | Notebook    | [c718a18472](https://linux-hardware.org/?probe=c718a18472) | May 19, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [dde73bc060](https://linux-hardware.org/?probe=dde73bc060) | May 18, 2023 |
| Medion        | BTDD-TI                     | All in one  | [cc45e1f2f4](https://linux-hardware.org/?probe=cc45e1f2f4) | May 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [763654d8fc](https://linux-hardware.org/?probe=763654d8fc) | May 18, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [3c8dcfcf15](https://linux-hardware.org/?probe=3c8dcfcf15) | May 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [856242dc26](https://linux-hardware.org/?probe=856242dc26) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b4a6b7f7](https://linux-hardware.org/?probe=70b4a6b7f7) | May 18, 2023 |
| HP            | 339A                        | Desktop     | [44a6e1f861](https://linux-hardware.org/?probe=44a6e1f861) | May 17, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [7f3487434e](https://linux-hardware.org/?probe=7f3487434e) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e236450e11](https://linux-hardware.org/?probe=e236450e11) | May 17, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [0c26a47ae5](https://linux-hardware.org/?probe=0c26a47ae5) | May 17, 2023 |
| Acer          | Predator G9-793             | Notebook    | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f4514801d8](https://linux-hardware.org/?probe=f4514801d8) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e31c83db5e](https://linux-hardware.org/?probe=e31c83db5e) | May 16, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d9b18c7990](https://linux-hardware.org/?probe=d9b18c7990) | May 16, 2023 |
| HP            | ENVY dv6                    | Notebook    | [2490803f28](https://linux-hardware.org/?probe=2490803f28) | May 16, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [b06c75ac5e](https://linux-hardware.org/?probe=b06c75ac5e) | May 16, 2023 |
| Lenovo        | ThinkPad T440 20B7S1MF0D    | Notebook    | [6173458650](https://linux-hardware.org/?probe=6173458650) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [19feb08b89](https://linux-hardware.org/?probe=19feb08b89) | May 15, 2023 |
| Google        | Sumo                        | Desktop     | [1455a81901](https://linux-hardware.org/?probe=1455a81901) | May 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [93979d632e](https://linux-hardware.org/?probe=93979d632e) | May 15, 2023 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [55210b06ca](https://linux-hardware.org/?probe=55210b06ca) | May 15, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [53f395d7fa](https://linux-hardware.org/?probe=53f395d7fa) | May 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [9beabf1347](https://linux-hardware.org/?probe=9beabf1347) | May 15, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [eaef457c8a](https://linux-hardware.org/?probe=eaef457c8a) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| Unknown       | HX90                        | Desktop     | [85edf2e24e](https://linux-hardware.org/?probe=85edf2e24e) | May 14, 2023 |
| ASUSTek       | G752VT                      | Notebook    | [e8459680a4](https://linux-hardware.org/?probe=e8459680a4) | May 14, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [5bd115a1b4](https://linux-hardware.org/?probe=5bd115a1b4) | May 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [0d1450cd2d](https://linux-hardware.org/?probe=0d1450cd2d) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [57e94dd4b7](https://linux-hardware.org/?probe=57e94dd4b7) | May 14, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [1556b05d13](https://linux-hardware.org/?probe=1556b05d13) | May 14, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [5e7cf34522](https://linux-hardware.org/?probe=5e7cf34522) | May 14, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [748e0f187f](https://linux-hardware.org/?probe=748e0f187f) | May 14, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [677e681a2d](https://linux-hardware.org/?probe=677e681a2d) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [d0f5ee2781](https://linux-hardware.org/?probe=d0f5ee2781) | May 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [71f2dc616d](https://linux-hardware.org/?probe=71f2dc616d) | May 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [bfb11f92b1](https://linux-hardware.org/?probe=bfb11f92b1) | May 11, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [12d23bdebb](https://linux-hardware.org/?probe=12d23bdebb) | May 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [efc35b1887](https://linux-hardware.org/?probe=efc35b1887) | May 11, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [bdd9bcedf5](https://linux-hardware.org/?probe=bdd9bcedf5) | May 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | Desktop     | [0b4b06b5fa](https://linux-hardware.org/?probe=0b4b06b5fa) | May 10, 2023 |
| ASUSTek       | UX410UAK                    | Notebook    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| Lenovo        | 36EB SDK0K17763 WIN 1801... | Desktop     | [4d68e2912b](https://linux-hardware.org/?probe=4d68e2912b) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [90bec72fa7](https://linux-hardware.org/?probe=90bec72fa7) | May 09, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [756ed502db](https://linux-hardware.org/?probe=756ed502db) | May 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13bace1181](https://linux-hardware.org/?probe=13bace1181) | May 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d3de6b6b31](https://linux-hardware.org/?probe=d3de6b6b31) | May 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d055c2e022](https://linux-hardware.org/?probe=d055c2e022) | May 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [18b79bbfa4](https://linux-hardware.org/?probe=18b79bbfa4) | May 07, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d58e08c9ab](https://linux-hardware.org/?probe=d58e08c9ab) | May 07, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6a93900fb9](https://linux-hardware.org/?probe=6a93900fb9) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| System76      | Oryx Pro                    | Notebook    | [6026e88ad4](https://linux-hardware.org/?probe=6026e88ad4) | May 06, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [faabff7b74](https://linux-hardware.org/?probe=faabff7b74) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1143344e93](https://linux-hardware.org/?probe=1143344e93) | May 06, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [d572509eb2](https://linux-hardware.org/?probe=d572509eb2) | May 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [91661b66d1](https://linux-hardware.org/?probe=91661b66d1) | May 06, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [5d12a9965b](https://linux-hardware.org/?probe=5d12a9965b) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [09e73cade8](https://linux-hardware.org/?probe=09e73cade8) | May 05, 2023 |
| ASRock        | H370 Pro4                   | Desktop     | [afffccef92](https://linux-hardware.org/?probe=afffccef92) | May 05, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e28a5499a4](https://linux-hardware.org/?probe=e28a5499a4) | May 05, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [624e1c3f06](https://linux-hardware.org/?probe=624e1c3f06) | May 05, 2023 |
| System76      | Oryx Pro                    | Notebook    | [fe799bc532](https://linux-hardware.org/?probe=fe799bc532) | May 04, 2023 |
| Gigabyte      | 2AC8                        | Desktop     | [4f5b51c45e](https://linux-hardware.org/?probe=4f5b51c45e) | May 04, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| Intel         | DG43GT AAE62768-300         | Desktop     | [e0f10df0f9](https://linux-hardware.org/?probe=e0f10df0f9) | May 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [728b1e3209](https://linux-hardware.org/?probe=728b1e3209) | May 03, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [c20844716d](https://linux-hardware.org/?probe=c20844716d) | May 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2b17563b98](https://linux-hardware.org/?probe=2b17563b98) | May 02, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [8b4f50125b](https://linux-hardware.org/?probe=8b4f50125b) | May 02, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f4f7391b8a](https://linux-hardware.org/?probe=f4f7391b8a) | May 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a43268d9b](https://linux-hardware.org/?probe=9a43268d9b) | May 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| Acer          | Aspire A514-54G             | Notebook    | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [1ef93daf0b](https://linux-hardware.org/?probe=1ef93daf0b) | Apr 28, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [cde129cf45](https://linux-hardware.org/?probe=cde129cf45) | Apr 26, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [add3c03eef](https://linux-hardware.org/?probe=add3c03eef) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9824006277](https://linux-hardware.org/?probe=9824006277) | Apr 26, 2023 |
| HP            | 18E7                        | Desktop     | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| System76      | Oryx Pro                    | Notebook    | [298bf97b70](https://linux-hardware.org/?probe=298bf97b70) | Apr 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [962bffed9f](https://linux-hardware.org/?probe=962bffed9f) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a2c2f1f536](https://linux-hardware.org/?probe=a2c2f1f536) | Apr 25, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [c897ecd954](https://linux-hardware.org/?probe=c897ecd954) | Apr 25, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [90fa428095](https://linux-hardware.org/?probe=90fa428095) | Apr 25, 2023 |
| ZOTAC         | ZBOX-CI527/CI547NANO        | Mini pc     | [97f86da425](https://linux-hardware.org/?probe=97f86da425) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| ASRock        | Z690 Extreme                | Desktop     | [3767d30290](https://linux-hardware.org/?probe=3767d30290) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [5b14b21a19](https://linux-hardware.org/?probe=5b14b21a19) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [4e69a80310](https://linux-hardware.org/?probe=4e69a80310) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [d48ffa8191](https://linux-hardware.org/?probe=d48ffa8191) | Apr 21, 2023 |
| Packard Be... | EasyNote TSX62HR            | Notebook    | [7e7dbc9acd](https://linux-hardware.org/?probe=7e7dbc9acd) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [8e02f43636](https://linux-hardware.org/?probe=8e02f43636) | Apr 20, 2023 |
| Acer          | Predator G9-793             | Notebook    | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [bebc7ec91b](https://linux-hardware.org/?probe=bebc7ec91b) | Apr 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [618b59dac2](https://linux-hardware.org/?probe=618b59dac2) | Apr 19, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4185aada87](https://linux-hardware.org/?probe=4185aada87) | Apr 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [512bad7a33](https://linux-hardware.org/?probe=512bad7a33) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6ce11cef12](https://linux-hardware.org/?probe=6ce11cef12) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [3decfdc1f6](https://linux-hardware.org/?probe=3decfdc1f6) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3738d57a9c](https://linux-hardware.org/?probe=3738d57a9c) | Apr 15, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Latitude 3590               | Notebook    | [eed6f4df10](https://linux-hardware.org/?probe=eed6f4df10) | Apr 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ef5829077e](https://linux-hardware.org/?probe=ef5829077e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e0e2242a64](https://linux-hardware.org/?probe=e0e2242a64) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fa729987de](https://linux-hardware.org/?probe=fa729987de) | Apr 09, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ca9fe9c7f1](https://linux-hardware.org/?probe=ca9fe9c7f1) | Apr 09, 2023 |
| HP            | ENVY 15                     | Notebook    | [5ecc7b36c8](https://linux-hardware.org/?probe=5ecc7b36c8) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX7602ZM            | Notebook    | [aeded4c133](https://linux-hardware.org/?probe=aeded4c133) | Apr 08, 2023 |
| HP            | Pavilion dv4                | Notebook    | [a554538ed8](https://linux-hardware.org/?probe=a554538ed8) | Apr 07, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2acb260eb1](https://linux-hardware.org/?probe=2acb260eb1) | Apr 07, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cd157a6ebf](https://linux-hardware.org/?probe=cd157a6ebf) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ebc3f9d008](https://linux-hardware.org/?probe=ebc3f9d008) | Apr 06, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bdb5d286b5](https://linux-hardware.org/?probe=bdb5d286b5) | Apr 06, 2023 |
| Dell          | Latitude 3510               | Notebook    | [e927d04a2d](https://linux-hardware.org/?probe=e927d04a2d) | Apr 06, 2023 |
| Biostar       | TZ77B                       | Desktop     | [c5d5603dc4](https://linux-hardware.org/?probe=c5d5603dc4) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| Shenzhen W... | GB1                         | Mini pc     | [ca02164e4d](https://linux-hardware.org/?probe=ca02164e4d) | Apr 01, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [2cc7a15de5](https://linux-hardware.org/?probe=2cc7a15de5) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490s 20NXS0DS0... | Notebook    | [1228998af5](https://linux-hardware.org/?probe=1228998af5) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [09679af7dc](https://linux-hardware.org/?probe=09679af7dc) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e78d2454c](https://linux-hardware.org/?probe=1e78d2454c) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [514d8ed8d6](https://linux-hardware.org/?probe=514d8ed8d6) | Mar 30, 2023 |
| HP            | 8399                        | Desktop     | [d8c0ad05f5](https://linux-hardware.org/?probe=d8c0ad05f5) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a1d2ac5e6e](https://linux-hardware.org/?probe=a1d2ac5e6e) | Mar 30, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7554f35f1d](https://linux-hardware.org/?probe=7554f35f1d) | Mar 30, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [8808e457a1](https://linux-hardware.org/?probe=8808e457a1) | Mar 29, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [2f1975360e](https://linux-hardware.org/?probe=2f1975360e) | Mar 28, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [5ac9dd16da](https://linux-hardware.org/?probe=5ac9dd16da) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| Dell          | 0W2F8G A02                  | Desktop     | [511510b501](https://linux-hardware.org/?probe=511510b501) | Mar 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [da016d15c7](https://linux-hardware.org/?probe=da016d15c7) | Mar 27, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1ed601999d](https://linux-hardware.org/?probe=1ed601999d) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [69eb2dad8f](https://linux-hardware.org/?probe=69eb2dad8f) | Mar 26, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [7c10ad8eb9](https://linux-hardware.org/?probe=7c10ad8eb9) | Mar 26, 2023 |
| MSI           | GT70                        | Notebook    | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [3772f7397b](https://linux-hardware.org/?probe=3772f7397b) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [915cac124b](https://linux-hardware.org/?probe=915cac124b) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [9d9e4e184f](https://linux-hardware.org/?probe=9d9e4e184f) | Mar 25, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6c4d5eee3f](https://linux-hardware.org/?probe=6c4d5eee3f) | Mar 25, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [765602e7bf](https://linux-hardware.org/?probe=765602e7bf) | Mar 24, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [a04e0acbcf](https://linux-hardware.org/?probe=a04e0acbcf) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5b6af55009](https://linux-hardware.org/?probe=5b6af55009) | Mar 23, 2023 |
| HP            | 828A                        | Desktop     | [cce5214801](https://linux-hardware.org/?probe=cce5214801) | Mar 22, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b784685da3](https://linux-hardware.org/?probe=b784685da3) | Mar 21, 2023 |
| System76      | Pangolin                    | Notebook    | [ee7dd00fbf](https://linux-hardware.org/?probe=ee7dd00fbf) | Mar 19, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| HP            | 18E8                        | Desktop     | [bf7c3c9080](https://linux-hardware.org/?probe=bf7c3c9080) | Mar 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [42391e1ac6](https://linux-hardware.org/?probe=42391e1ac6) | Mar 16, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7630033ffb](https://linux-hardware.org/?probe=7630033ffb) | Mar 15, 2023 |
| Lenovo        | 36EB NOK                    | Desktop     | [b6d8243d49](https://linux-hardware.org/?probe=b6d8243d49) | Mar 15, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [60bd2eeae4](https://linux-hardware.org/?probe=60bd2eeae4) | Mar 15, 2023 |
| HP            | 828A                        | Desktop     | [9d6df1b56e](https://linux-hardware.org/?probe=9d6df1b56e) | Mar 15, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [77b68431f7](https://linux-hardware.org/?probe=77b68431f7) | Mar 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94932937e](https://linux-hardware.org/?probe=b94932937e) | Mar 14, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [54d17115b9](https://linux-hardware.org/?probe=54d17115b9) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [79932e56ad](https://linux-hardware.org/?probe=79932e56ad) | Mar 13, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1de50d9986](https://linux-hardware.org/?probe=1de50d9986) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [1fc9174c06](https://linux-hardware.org/?probe=1fc9174c06) | Mar 11, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [9e6843fe2e](https://linux-hardware.org/?probe=9e6843fe2e) | Mar 10, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [77d13c9c12](https://linux-hardware.org/?probe=77d13c9c12) | Mar 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dd06fbb0f9](https://linux-hardware.org/?probe=dd06fbb0f9) | Mar 10, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [bdf01893f8](https://linux-hardware.org/?probe=bdf01893f8) | Mar 10, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [b46bb47333](https://linux-hardware.org/?probe=b46bb47333) | Mar 09, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [24444c6d30](https://linux-hardware.org/?probe=24444c6d30) | Mar 08, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [f500d72edd](https://linux-hardware.org/?probe=f500d72edd) | Mar 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [42e5be35d6](https://linux-hardware.org/?probe=42e5be35d6) | Mar 08, 2023 |
| HP            | 8055                        | Desktop     | [0b9ddd5940](https://linux-hardware.org/?probe=0b9ddd5940) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| Huanan        | X79-ZD3 INTEL (INTEL Xeo... | Desktop     | [0e00a19a03](https://linux-hardware.org/?probe=0e00a19a03) | Mar 07, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8f08518290](https://linux-hardware.org/?probe=8f08518290) | Mar 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [819f8b1cad](https://linux-hardware.org/?probe=819f8b1cad) | Mar 06, 2023 |
| Dell          | G7 7500                     | Notebook    | [d5abfa6d0d](https://linux-hardware.org/?probe=d5abfa6d0d) | Mar 06, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [a6c7741454](https://linux-hardware.org/?probe=a6c7741454) | Mar 06, 2023 |
| Dell          | G7 7500                     | Notebook    | [bfaad602b7](https://linux-hardware.org/?probe=bfaad602b7) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [e560390e4f](https://linux-hardware.org/?probe=e560390e4f) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d1560d3d1](https://linux-hardware.org/?probe=3d1560d3d1) | Mar 05, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f98c3014](https://linux-hardware.org/?probe=c2f98c3014) | Mar 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f163816260](https://linux-hardware.org/?probe=f163816260) | Mar 04, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5523730c91](https://linux-hardware.org/?probe=5523730c91) | Mar 04, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [422fa2cf16](https://linux-hardware.org/?probe=422fa2cf16) | Mar 02, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f441cc82e4](https://linux-hardware.org/?probe=f441cc82e4) | Mar 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [edf5f00bf8](https://linux-hardware.org/?probe=edf5f00bf8) | Mar 01, 2023 |
| Sony          | VPCEH10EB                   | Notebook    | [9c8bb09559](https://linux-hardware.org/?probe=9c8bb09559) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [ecdef0f6db](https://linux-hardware.org/?probe=ecdef0f6db) | Mar 01, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [6bd63e7974](https://linux-hardware.org/?probe=6bd63e7974) | Mar 01, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db5b346bd5](https://linux-hardware.org/?probe=db5b346bd5) | Feb 28, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [166a6bbb4b](https://linux-hardware.org/?probe=166a6bbb4b) | Feb 28, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [dd74cb518b](https://linux-hardware.org/?probe=dd74cb518b) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [068ad292bd](https://linux-hardware.org/?probe=068ad292bd) | Feb 27, 2023 |
| Gigabyte      | X99-UD4P-CF                 | Desktop     | [b78a53985a](https://linux-hardware.org/?probe=b78a53985a) | Feb 26, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [267da4138c](https://linux-hardware.org/?probe=267da4138c) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de7aec7f12](https://linux-hardware.org/?probe=de7aec7f12) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8a2a361aff](https://linux-hardware.org/?probe=8a2a361aff) | Feb 26, 2023 |
| Lenovo        | ThinkPad L470 20J4003WGE    | Notebook    | [42f6425b2d](https://linux-hardware.org/?probe=42f6425b2d) | Feb 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | Notebook    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Gigabyte      | B85N PHOENIX                | Desktop     | [5fe00f35c4](https://linux-hardware.org/?probe=5fe00f35c4) | Feb 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [31bd9738ca](https://linux-hardware.org/?probe=31bd9738ca) | Feb 25, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [4066713adb](https://linux-hardware.org/?probe=4066713adb) | Feb 24, 2023 |
| Dell          | 0MM599                      | Desktop     | [00304aefe6](https://linux-hardware.org/?probe=00304aefe6) | Feb 24, 2023 |
| AZW           | GTR V02                     | Desktop     | [c8d4bfd6e3](https://linux-hardware.org/?probe=c8d4bfd6e3) | Feb 23, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [e60b570c27](https://linux-hardware.org/?probe=e60b570c27) | Feb 23, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [950130a7b4](https://linux-hardware.org/?probe=950130a7b4) | Feb 23, 2023 |
| Lenovo        | 36EB NOK                    | Desktop     | [019ad99dd4](https://linux-hardware.org/?probe=019ad99dd4) | Feb 22, 2023 |
| ASUSTek       | X55VD                       | Notebook    | [6b71d8369a](https://linux-hardware.org/?probe=6b71d8369a) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | Desktop     | [d8b3285c55](https://linux-hardware.org/?probe=d8b3285c55) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [65f3a9d691](https://linux-hardware.org/?probe=65f3a9d691) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Dell          | 0RN4PJ A01                  | Server      | [0c272543ed](https://linux-hardware.org/?probe=0c272543ed) | Feb 21, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [b5aebe4c92](https://linux-hardware.org/?probe=b5aebe4c92) | Feb 21, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [accbe9322f](https://linux-hardware.org/?probe=accbe9322f) | Feb 20, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f8a26128a4](https://linux-hardware.org/?probe=f8a26128a4) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [28a0794b08](https://linux-hardware.org/?probe=28a0794b08) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e87f489185](https://linux-hardware.org/?probe=e87f489185) | Feb 20, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [6f65703034](https://linux-hardware.org/?probe=6f65703034) | Feb 19, 2023 |
| HP            | ENVY 15                     | Notebook    | [7d53c3db41](https://linux-hardware.org/?probe=7d53c3db41) | Feb 19, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1263eaf1f9](https://linux-hardware.org/?probe=1263eaf1f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [2b1fc8eb09](https://linux-hardware.org/?probe=2b1fc8eb09) | Feb 19, 2023 |
| HP            | 8053                        | Desktop     | [e495e287bc](https://linux-hardware.org/?probe=e495e287bc) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [e59ac2cec0](https://linux-hardware.org/?probe=e59ac2cec0) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [f36e84dcaf](https://linux-hardware.org/?probe=f36e84dcaf) | Feb 16, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [2cb0dc3d69](https://linux-hardware.org/?probe=2cb0dc3d69) | Feb 13, 2023 |
| ASRock        | Z690 Steel Legend           | Desktop     | [6935bc6a6e](https://linux-hardware.org/?probe=6935bc6a6e) | Feb 13, 2023 |
| Intel         | NUC7i3BNB J22859-316        | Mini pc     | [fc5fbe9d48](https://linux-hardware.org/?probe=fc5fbe9d48) | Feb 13, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [abe1e578c0](https://linux-hardware.org/?probe=abe1e578c0) | Feb 12, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [480da10129](https://linux-hardware.org/?probe=480da10129) | Feb 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [cbf6311f2c](https://linux-hardware.org/?probe=cbf6311f2c) | Feb 12, 2023 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [fdbc3256cf](https://linux-hardware.org/?probe=fdbc3256cf) | Feb 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [19547b9a43](https://linux-hardware.org/?probe=19547b9a43) | Feb 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4344acac5e](https://linux-hardware.org/?probe=4344acac5e) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4340c10db](https://linux-hardware.org/?probe=e4340c10db) | Feb 10, 2023 |
| System76      | Oryx Pro                    | Notebook    | [20fad7d628](https://linux-hardware.org/?probe=20fad7d628) | Feb 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2f694f36cc](https://linux-hardware.org/?probe=2f694f36cc) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a545753206](https://linux-hardware.org/?probe=a545753206) | Feb 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c7de2e3ca2](https://linux-hardware.org/?probe=c7de2e3ca2) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Toshiba       | Satellite L70-B             | Notebook    | [f47ccc62c7](https://linux-hardware.org/?probe=f47ccc62c7) | Feb 09, 2023 |
| Toshiba       | Satellite L70-B             | Notebook    | [68ba5288c0](https://linux-hardware.org/?probe=68ba5288c0) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [5fe8eef781](https://linux-hardware.org/?probe=5fe8eef781) | Feb 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [47c66d7783](https://linux-hardware.org/?probe=47c66d7783) | Feb 08, 2023 |
| Quanta        | 2AF5 011                    | Desktop     | [e62b8a3165](https://linux-hardware.org/?probe=e62b8a3165) | Feb 07, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [420ccdfca6](https://linux-hardware.org/?probe=420ccdfca6) | Feb 07, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [2d40451b53](https://linux-hardware.org/?probe=2d40451b53) | Feb 06, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [a865465884](https://linux-hardware.org/?probe=a865465884) | Feb 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [a41f5126d3](https://linux-hardware.org/?probe=a41f5126d3) | Feb 04, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [a4b17f9deb](https://linux-hardware.org/?probe=a4b17f9deb) | Feb 04, 2023 |
| Unknown       | HX90                        | Desktop     | [60ade05817](https://linux-hardware.org/?probe=60ade05817) | Feb 03, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [395e2c6424](https://linux-hardware.org/?probe=395e2c6424) | Feb 03, 2023 |
| Monster       | TULPAR T5 V20.1             | Notebook    | [b224ac6a46](https://linux-hardware.org/?probe=b224ac6a46) | Feb 03, 2023 |
| Acer          | WMCP78M                     | Desktop     | [cd9dccabaf](https://linux-hardware.org/?probe=cd9dccabaf) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [62d193dd49](https://linux-hardware.org/?probe=62d193dd49) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [181cdf6a58](https://linux-hardware.org/?probe=181cdf6a58) | Feb 03, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [de152b340c](https://linux-hardware.org/?probe=de152b340c) | Feb 01, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [a2ff80e7dd](https://linux-hardware.org/?probe=a2ff80e7dd) | Feb 01, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [d7b81788e7](https://linux-hardware.org/?probe=d7b81788e7) | Feb 01, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5abc8dccdb](https://linux-hardware.org/?probe=5abc8dccdb) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3aaad3b44c](https://linux-hardware.org/?probe=3aaad3b44c) | Jan 29, 2023 |
| SYWZ          | S210H Series                | Desktop     | [4d1018a808](https://linux-hardware.org/?probe=4d1018a808) | Jan 29, 2023 |
| HP            | 8053                        | Desktop     | [88120ce3f4](https://linux-hardware.org/?probe=88120ce3f4) | Jan 28, 2023 |
| MSI           | Raider GE76 12UHS           | Notebook    | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [2cf59bd38d](https://linux-hardware.org/?probe=2cf59bd38d) | Jan 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [85ad9c7e62](https://linux-hardware.org/?probe=85ad9c7e62) | Jan 25, 2023 |
| HP            | Folio 13                    | Notebook    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [a95489f0b7](https://linux-hardware.org/?probe=a95489f0b7) | Jan 24, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [5b2fd24ed7](https://linux-hardware.org/?probe=5b2fd24ed7) | Jan 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [d0f4730f71](https://linux-hardware.org/?probe=d0f4730f71) | Jan 23, 2023 |
| HP            | 8750                        | Desktop     | [e8b02ffbb5](https://linux-hardware.org/?probe=e8b02ffbb5) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [66287c2f72](https://linux-hardware.org/?probe=66287c2f72) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [369b022d8e](https://linux-hardware.org/?probe=369b022d8e) | Jan 22, 2023 |
| Timi          | TM1701                      | Notebook    | [bec2d3a691](https://linux-hardware.org/?probe=bec2d3a691) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| Dell          | Latitude 7480               | Notebook    | [0d4396d043](https://linux-hardware.org/?probe=0d4396d043) | Jan 21, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [ae81429a64](https://linux-hardware.org/?probe=ae81429a64) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [560159c251](https://linux-hardware.org/?probe=560159c251) | Jan 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [be0b035640](https://linux-hardware.org/?probe=be0b035640) | Jan 20, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [acf0fd5893](https://linux-hardware.org/?probe=acf0fd5893) | Jan 20, 2023 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [8aa69f1dae](https://linux-hardware.org/?probe=8aa69f1dae) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [0ea710bda6](https://linux-hardware.org/?probe=0ea710bda6) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [0f21d67175](https://linux-hardware.org/?probe=0f21d67175) | Jan 20, 2023 |
| Acer          | Predator G3-710             | Desktop     | [c7f97640a5](https://linux-hardware.org/?probe=c7f97640a5) | Jan 19, 2023 |
| AZW           | GTR V02                     | Desktop     | [524948189b](https://linux-hardware.org/?probe=524948189b) | Jan 19, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [b6a8598370](https://linux-hardware.org/?probe=b6a8598370) | Jan 19, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [68d2fcbdcf](https://linux-hardware.org/?probe=68d2fcbdcf) | Jan 18, 2023 |
| Alienware     | M17xR4                      | Notebook    | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [e221c08388](https://linux-hardware.org/?probe=e221c08388) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [d2bb65ed09](https://linux-hardware.org/?probe=d2bb65ed09) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [0306622813](https://linux-hardware.org/?probe=0306622813) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [84edd23a21](https://linux-hardware.org/?probe=84edd23a21) | Jan 18, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [8e4a061e95](https://linux-hardware.org/?probe=8e4a061e95) | Jan 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [60a0157a51](https://linux-hardware.org/?probe=60a0157a51) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6643ab6cf1](https://linux-hardware.org/?probe=6643ab6cf1) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [91fed2c125](https://linux-hardware.org/?probe=91fed2c125) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9fe6c51640](https://linux-hardware.org/?probe=9fe6c51640) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [d569a3f698](https://linux-hardware.org/?probe=d569a3f698) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [0ece2f508b](https://linux-hardware.org/?probe=0ece2f508b) | Jan 14, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [dd5156dd62](https://linux-hardware.org/?probe=dd5156dd62) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4f439c171e](https://linux-hardware.org/?probe=4f439c171e) | Jan 14, 2023 |
| HP            | 886C                        | Desktop     | [3f75def118](https://linux-hardware.org/?probe=3f75def118) | Jan 13, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e275cc7891](https://linux-hardware.org/?probe=e275cc7891) | Jan 13, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [5e5d5428a3](https://linux-hardware.org/?probe=5e5d5428a3) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c62282370](https://linux-hardware.org/?probe=7c62282370) | Jan 12, 2023 |
| AZW           | GTR V02                     | Desktop     | [cde45335ab](https://linux-hardware.org/?probe=cde45335ab) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [2dadad3f74](https://linux-hardware.org/?probe=2dadad3f74) | Jan 12, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [d859e0ff10](https://linux-hardware.org/?probe=d859e0ff10) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [71c61d98b9](https://linux-hardware.org/?probe=71c61d98b9) | Jan 10, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [4e7660a1e0](https://linux-hardware.org/?probe=4e7660a1e0) | Jan 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a786384700](https://linux-hardware.org/?probe=a786384700) | Jan 10, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [787c4388c8](https://linux-hardware.org/?probe=787c4388c8) | Jan 09, 2023 |
| System76      | Oryx Pro                    | Notebook    | [e3f5a24a6e](https://linux-hardware.org/?probe=e3f5a24a6e) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [46ae333889](https://linux-hardware.org/?probe=46ae333889) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bdc427771d](https://linux-hardware.org/?probe=bdc427771d) | Jan 08, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [ebf4546adf](https://linux-hardware.org/?probe=ebf4546adf) | Jan 08, 2023 |
| HP            | 2B2C                        | Desktop     | [1a74d92aaf](https://linux-hardware.org/?probe=1a74d92aaf) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6f2c3e2284](https://linux-hardware.org/?probe=6f2c3e2284) | Jan 08, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [16c789a53c](https://linux-hardware.org/?probe=16c789a53c) | Jan 07, 2023 |
| Dell          | Precision M3800             | Notebook    | [ca9cfa3f5a](https://linux-hardware.org/?probe=ca9cfa3f5a) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ef473bb212](https://linux-hardware.org/?probe=ef473bb212) | Jan 07, 2023 |
| Dell          | Precision M3800             | Notebook    | [454d4b6b55](https://linux-hardware.org/?probe=454d4b6b55) | Jan 07, 2023 |
| Acer          | Predator G9-793             | Notebook    | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a7fbae334f](https://linux-hardware.org/?probe=a7fbae334f) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [e9f54fc1f0](https://linux-hardware.org/?probe=e9f54fc1f0) | Jan 07, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [67b5b9902a](https://linux-hardware.org/?probe=67b5b9902a) | Jan 06, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [7281c172f4](https://linux-hardware.org/?probe=7281c172f4) | Jan 06, 2023 |
| Gigabyte      | P55-USB3                    | Desktop     | [7c741c709a](https://linux-hardware.org/?probe=7c741c709a) | Jan 06, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [74859544a4](https://linux-hardware.org/?probe=74859544a4) | Jan 06, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [922a46c59e](https://linux-hardware.org/?probe=922a46c59e) | Jan 06, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [42ee9415a1](https://linux-hardware.org/?probe=42ee9415a1) | Jan 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| System76      | Pangolin                    | Notebook    | [823d50a20f](https://linux-hardware.org/?probe=823d50a20f) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [458cb8c4de](https://linux-hardware.org/?probe=458cb8c4de) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a84d0d7b42](https://linux-hardware.org/?probe=a84d0d7b42) | Jan 06, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [8027cc9eeb](https://linux-hardware.org/?probe=8027cc9eeb) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [113e1b51b7](https://linux-hardware.org/?probe=113e1b51b7) | Jan 04, 2023 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| HP            | ENVY 15                     | Notebook    | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [23bfcb7f4c](https://linux-hardware.org/?probe=23bfcb7f4c) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [b55d0dfc1e](https://linux-hardware.org/?probe=b55d0dfc1e) | Jan 03, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [2ec9ac6337](https://linux-hardware.org/?probe=2ec9ac6337) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Dell          | Precision 7740              | Notebook    | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [0229b8166f](https://linux-hardware.org/?probe=0229b8166f) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [5749628668](https://linux-hardware.org/?probe=5749628668) | Jan 01, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [63adf72d53](https://linux-hardware.org/?probe=63adf72d53) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| HP            | Folio 13                    | Notebook    | [9f00cfe432](https://linux-hardware.org/?probe=9f00cfe432) | Dec 31, 2022 |
| HP            | Folio 13                    | Notebook    | [3ed5b405cb](https://linux-hardware.org/?probe=3ed5b405cb) | Dec 31, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [bdd6f3912d](https://linux-hardware.org/?probe=bdd6f3912d) | Dec 30, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [056ae8185c](https://linux-hardware.org/?probe=056ae8185c) | Dec 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [6cf8d26754](https://linux-hardware.org/?probe=6cf8d26754) | Dec 30, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [33fd3ed258](https://linux-hardware.org/?probe=33fd3ed258) | Dec 29, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [338e7b0029](https://linux-hardware.org/?probe=338e7b0029) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | Notebook    | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [dc6cc81a73](https://linux-hardware.org/?probe=dc6cc81a73) | Dec 24, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3948dcc7ef](https://linux-hardware.org/?probe=3948dcc7ef) | Dec 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bc1c9956b3](https://linux-hardware.org/?probe=bc1c9956b3) | Dec 23, 2022 |
| Dell          | Inspiron 7580               | Notebook    | [eb5b708877](https://linux-hardware.org/?probe=eb5b708877) | Dec 22, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [de140c1edd](https://linux-hardware.org/?probe=de140c1edd) | Dec 22, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [59d46f37db](https://linux-hardware.org/?probe=59d46f37db) | Dec 22, 2022 |
| Sony          | SVF15N26CXB                 | Notebook    | [ffc2ea8936](https://linux-hardware.org/?probe=ffc2ea8936) | Dec 22, 2022 |
| ASUSTek       | VANGUARD B85                | Desktop     | [73560a1b6a](https://linux-hardware.org/?probe=73560a1b6a) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4906017260](https://linux-hardware.org/?probe=4906017260) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [085b8c23b4](https://linux-hardware.org/?probe=085b8c23b4) | Dec 21, 2022 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [58da003de3](https://linux-hardware.org/?probe=58da003de3) | Dec 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [e2942bceb2](https://linux-hardware.org/?probe=e2942bceb2) | Dec 20, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [a269c3ef8a](https://linux-hardware.org/?probe=a269c3ef8a) | Dec 20, 2022 |
| ASUSTek       | X555QA                      | Notebook    | [3a7e8867bd](https://linux-hardware.org/?probe=3a7e8867bd) | Dec 19, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c8b402d4df](https://linux-hardware.org/?probe=c8b402d4df) | Dec 18, 2022 |
| Dell          | Latitude 5580               | Notebook    | [b45e1798cc](https://linux-hardware.org/?probe=b45e1798cc) | Dec 18, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [911e6f6d33](https://linux-hardware.org/?probe=911e6f6d33) | Dec 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7adfddc31e](https://linux-hardware.org/?probe=7adfddc31e) | Dec 16, 2022 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [adb08a48f3](https://linux-hardware.org/?probe=adb08a48f3) | Dec 15, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [535643e246](https://linux-hardware.org/?probe=535643e246) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [20c4b98c2c](https://linux-hardware.org/?probe=20c4b98c2c) | Dec 14, 2022 |
| MSI           | GE72VR 6RF                  | Notebook    | [ce2ebf80a1](https://linux-hardware.org/?probe=ce2ebf80a1) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5a9654c743](https://linux-hardware.org/?probe=5a9654c743) | Dec 13, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [2212bad256](https://linux-hardware.org/?probe=2212bad256) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [20cb7a525a](https://linux-hardware.org/?probe=20cb7a525a) | Dec 12, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [65bc0e828c](https://linux-hardware.org/?probe=65bc0e828c) | Dec 08, 2022 |
| LG Electro... | C500                        | Notebook    | [078e13cadd](https://linux-hardware.org/?probe=078e13cadd) | Dec 08, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1613228bb2](https://linux-hardware.org/?probe=1613228bb2) | Dec 08, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [04a09baf04](https://linux-hardware.org/?probe=04a09baf04) | Dec 08, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [e7495f12e4](https://linux-hardware.org/?probe=e7495f12e4) | Dec 08, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [7ba193202d](https://linux-hardware.org/?probe=7ba193202d) | Dec 08, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [4a41ed7fae](https://linux-hardware.org/?probe=4a41ed7fae) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3a91c2e245](https://linux-hardware.org/?probe=3a91c2e245) | Dec 07, 2022 |
| MSI           | GE72VR 6RF                  | Notebook    | [23a83a5e8e](https://linux-hardware.org/?probe=23a83a5e8e) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [fceea368d5](https://linux-hardware.org/?probe=fceea368d5) | Dec 06, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0fcd09c9f8](https://linux-hardware.org/?probe=0fcd09c9f8) | Dec 06, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [311215d00b](https://linux-hardware.org/?probe=311215d00b) | Dec 05, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [e5058b43c3](https://linux-hardware.org/?probe=e5058b43c3) | Dec 05, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [b8546e4162](https://linux-hardware.org/?probe=b8546e4162) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ac92442dbc](https://linux-hardware.org/?probe=ac92442dbc) | Dec 04, 2022 |
| ASUSTek       | X555QA                      | Notebook    | [677ef3b3f2](https://linux-hardware.org/?probe=677ef3b3f2) | Dec 03, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [abb243027a](https://linux-hardware.org/?probe=abb243027a) | Dec 03, 2022 |
| Acer          | Aspire XC-780               | Desktop     | [b385e11c00](https://linux-hardware.org/?probe=b385e11c00) | Dec 01, 2022 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [3b7321ba87](https://linux-hardware.org/?probe=3b7321ba87) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | Notebook    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [fd897211fa](https://linux-hardware.org/?probe=fd897211fa) | Nov 30, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [186950bae6](https://linux-hardware.org/?probe=186950bae6) | Nov 29, 2022 |
| MSI           | Katana GF76 11UD            | Notebook    | [48bb9075a7](https://linux-hardware.org/?probe=48bb9075a7) | Nov 29, 2022 |
| HP            | 8876 11                     | Desktop     | [babda62ffa](https://linux-hardware.org/?probe=babda62ffa) | Nov 29, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [3ba81fa674](https://linux-hardware.org/?probe=3ba81fa674) | Nov 28, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [3c50a742a9](https://linux-hardware.org/?probe=3c50a742a9) | Nov 28, 2022 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [da2828f715](https://linux-hardware.org/?probe=da2828f715) | Nov 28, 2022 |
| System76      | Oryx Pro                    | Notebook    | [c7d2918a69](https://linux-hardware.org/?probe=c7d2918a69) | Nov 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7cb4ad7428](https://linux-hardware.org/?probe=7cb4ad7428) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| HP            | 18E7                        | Desktop     | [5a5c2667a5](https://linux-hardware.org/?probe=5a5c2667a5) | Nov 26, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| Gigabyte      | Z87X-SLI                    | Desktop     | [19719414c0](https://linux-hardware.org/?probe=19719414c0) | Nov 24, 2022 |
| HP            | 8750                        | Desktop     | [b1ac308187](https://linux-hardware.org/?probe=b1ac308187) | Nov 24, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1071e10a2c](https://linux-hardware.org/?probe=1071e10a2c) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [69d71bba75](https://linux-hardware.org/?probe=69d71bba75) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a74fdb05b](https://linux-hardware.org/?probe=9a74fdb05b) | Nov 22, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [24fb42db2b](https://linux-hardware.org/?probe=24fb42db2b) | Nov 21, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [88bbdb925b](https://linux-hardware.org/?probe=88bbdb925b) | Nov 20, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d7ee80553a](https://linux-hardware.org/?probe=d7ee80553a) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [f55a45b87f](https://linux-hardware.org/?probe=f55a45b87f) | Nov 20, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [912f6ac7a3](https://linux-hardware.org/?probe=912f6ac7a3) | Nov 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f7ebd3f633](https://linux-hardware.org/?probe=f7ebd3f633) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e3d6c78ed4](https://linux-hardware.org/?probe=e3d6c78ed4) | Nov 20, 2022 |
| ASUSTek       | P5K                         | Desktop     | [44b338a17d](https://linux-hardware.org/?probe=44b338a17d) | Nov 19, 2022 |
| HP            | 2B2C                        | Desktop     | [91862a2497](https://linux-hardware.org/?probe=91862a2497) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [41266bf8f0](https://linux-hardware.org/?probe=41266bf8f0) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [945910eb8a](https://linux-hardware.org/?probe=945910eb8a) | Nov 18, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [560c24bf74](https://linux-hardware.org/?probe=560c24bf74) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [abbaaa8589](https://linux-hardware.org/?probe=abbaaa8589) | Nov 17, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [33a412b9d5](https://linux-hardware.org/?probe=33a412b9d5) | Nov 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [882e91c53a](https://linux-hardware.org/?probe=882e91c53a) | Nov 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [83c0e1f2a1](https://linux-hardware.org/?probe=83c0e1f2a1) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2ea755455d](https://linux-hardware.org/?probe=2ea755455d) | Nov 16, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [30916d8420](https://linux-hardware.org/?probe=30916d8420) | Nov 16, 2022 |
| HP            | 2B2C                        | Desktop     | [2eb8311f18](https://linux-hardware.org/?probe=2eb8311f18) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9876aa0fd](https://linux-hardware.org/?probe=c9876aa0fd) | Nov 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a7cae7b96](https://linux-hardware.org/?probe=9a7cae7b96) | Nov 15, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| Acer          | Predator G3-710             | Desktop     | [4be3a9e016](https://linux-hardware.org/?probe=4be3a9e016) | Nov 13, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [e7820d3dfb](https://linux-hardware.org/?probe=e7820d3dfb) | Nov 13, 2022 |
| Toshiba       | Satellite L775              | Notebook    | [a8c9c0ffda](https://linux-hardware.org/?probe=a8c9c0ffda) | Nov 12, 2022 |
| Dell          | Latitude 3380               | Notebook    | [f770a70f68](https://linux-hardware.org/?probe=f770a70f68) | Nov 12, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [91bdce735b](https://linux-hardware.org/?probe=91bdce735b) | Nov 12, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [01dbd42727](https://linux-hardware.org/?probe=01dbd42727) | Nov 10, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [dde7e92189](https://linux-hardware.org/?probe=dde7e92189) | Nov 10, 2022 |
| Dell          | Precision 3571              | Notebook    | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| CSL-Comput... | R Evolve C14i               | Notebook    | [2a99a4d733](https://linux-hardware.org/?probe=2a99a4d733) | Nov 10, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [44c3eceeee](https://linux-hardware.org/?probe=44c3eceeee) | Nov 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bf5e7a39a0](https://linux-hardware.org/?probe=bf5e7a39a0) | Nov 09, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [02b3508a99](https://linux-hardware.org/?probe=02b3508a99) | Nov 09, 2022 |
| Dell          | Latitude E5470              | Notebook    | [a9c69c7418](https://linux-hardware.org/?probe=a9c69c7418) | Nov 09, 2022 |
| Dell          | Precision 3571              | Notebook    | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | Notebook    | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [533c6216c7](https://linux-hardware.org/?probe=533c6216c7) | Nov 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [f715c6e15c](https://linux-hardware.org/?probe=f715c6e15c) | Nov 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [caf9066e2a](https://linux-hardware.org/?probe=caf9066e2a) | Nov 06, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [78196c6656](https://linux-hardware.org/?probe=78196c6656) | Nov 05, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [52c7829518](https://linux-hardware.org/?probe=52c7829518) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| HP            | 8768 A                      | Desktop     | [adc86e7963](https://linux-hardware.org/?probe=adc86e7963) | Nov 04, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6491b1d525](https://linux-hardware.org/?probe=6491b1d525) | Nov 04, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e7254fb467](https://linux-hardware.org/?probe=e7254fb467) | Nov 04, 2022 |
| Alienware     | 14                          | Notebook    | [0c11295ebe](https://linux-hardware.org/?probe=0c11295ebe) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [813cfb5bdf](https://linux-hardware.org/?probe=813cfb5bdf) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f790aefcad](https://linux-hardware.org/?probe=f790aefcad) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [d81e8b3ea2](https://linux-hardware.org/?probe=d81e8b3ea2) | Nov 01, 2022 |
| ASUSTek       | Zephyrus S GX531GS_GX531... | Notebook    | [4823244248](https://linux-hardware.org/?probe=4823244248) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [69768228d4](https://linux-hardware.org/?probe=69768228d4) | Nov 01, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [a3abf820e1](https://linux-hardware.org/?probe=a3abf820e1) | Oct 31, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| ASRock        | B450M Pro4-F R2.0           | Desktop     | [5fb37123e0](https://linux-hardware.org/?probe=5fb37123e0) | Oct 30, 2022 |
| ASRock        | Z690 Steel Legend           | Desktop     | [cbfd203fd4](https://linux-hardware.org/?probe=cbfd203fd4) | Oct 29, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [39d64a1014](https://linux-hardware.org/?probe=39d64a1014) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [7b414a3c7c](https://linux-hardware.org/?probe=7b414a3c7c) | Oct 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4f5623de73](https://linux-hardware.org/?probe=4f5623de73) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [865ff52614](https://linux-hardware.org/?probe=865ff52614) | Oct 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4411ceb907](https://linux-hardware.org/?probe=4411ceb907) | Oct 27, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [f1a5637218](https://linux-hardware.org/?probe=f1a5637218) | Oct 27, 2022 |
| Dell          | Precision 7530              | Notebook    | [daee9e9524](https://linux-hardware.org/?probe=daee9e9524) | Oct 26, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [696c30d8c3](https://linux-hardware.org/?probe=696c30d8c3) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [76fa0d836f](https://linux-hardware.org/?probe=76fa0d836f) | Oct 25, 2022 |
| HP            | 1589                        | Desktop     | [ad8920e059](https://linux-hardware.org/?probe=ad8920e059) | Oct 25, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [802e0f0c61](https://linux-hardware.org/?probe=802e0f0c61) | Oct 24, 2022 |
| NEC Comput... | PC-VK27MXZCG                | Notebook    | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Latitude E6440              | Notebook    | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [839e67703e](https://linux-hardware.org/?probe=839e67703e) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [a73e4a9246](https://linux-hardware.org/?probe=a73e4a9246) | Oct 23, 2022 |
| Toshiba       | Satellite L775              | Notebook    | [180b9ab9ae](https://linux-hardware.org/?probe=180b9ab9ae) | Oct 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [02643d35a4](https://linux-hardware.org/?probe=02643d35a4) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aca44a3eab](https://linux-hardware.org/?probe=aca44a3eab) | Oct 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWA0DW0... | Notebook    | [117e1e8e03](https://linux-hardware.org/?probe=117e1e8e03) | Oct 20, 2022 |
| Acer          | Aspire 7720Z                | Notebook    | [164c89c324](https://linux-hardware.org/?probe=164c89c324) | Oct 20, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [6a7e7ac7ce](https://linux-hardware.org/?probe=6a7e7ac7ce) | Oct 19, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [2a207c39d4](https://linux-hardware.org/?probe=2a207c39d4) | Oct 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [19048aa8f0](https://linux-hardware.org/?probe=19048aa8f0) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [e1a32857ba](https://linux-hardware.org/?probe=e1a32857ba) | Oct 19, 2022 |
| HP            | 3397                        | Desktop     | [b32a50dc29](https://linux-hardware.org/?probe=b32a50dc29) | Oct 19, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [6f441865a9](https://linux-hardware.org/?probe=6f441865a9) | Oct 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [3c91e0c6ec](https://linux-hardware.org/?probe=3c91e0c6ec) | Oct 19, 2022 |
| Dell          | Latitude 3380               | Notebook    | [352bedd96b](https://linux-hardware.org/?probe=352bedd96b) | Oct 18, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [fc51a7c9dc](https://linux-hardware.org/?probe=fc51a7c9dc) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [9357d641ef](https://linux-hardware.org/?probe=9357d641ef) | Oct 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [e8828a135a](https://linux-hardware.org/?probe=e8828a135a) | Oct 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [30dfac67f5](https://linux-hardware.org/?probe=30dfac67f5) | Oct 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc0a9a6b24](https://linux-hardware.org/?probe=fc0a9a6b24) | Oct 18, 2022 |
| HP            | 18E7                        | Desktop     | [db33d9c2c2](https://linux-hardware.org/?probe=db33d9c2c2) | Oct 18, 2022 |
| ASRock        | H310M-STX                   | Desktop     | [56f9a169fa](https://linux-hardware.org/?probe=56f9a169fa) | Oct 18, 2022 |
| Sony          | SVE14A27CXH                 | Notebook    | [85398590ee](https://linux-hardware.org/?probe=85398590ee) | Oct 18, 2022 |
| Sony          | SVE14A27CXH                 | Notebook    | [76a531edcf](https://linux-hardware.org/?probe=76a531edcf) | Oct 18, 2022 |
| Gigabyte      | B360M DS3H                  | Desktop     | [ca57bb441c](https://linux-hardware.org/?probe=ca57bb441c) | Oct 18, 2022 |
| LG Electro... | C500                        | Notebook    | [f688cc0536](https://linux-hardware.org/?probe=f688cc0536) | Oct 18, 2022 |
| HP            | 8399                        | Desktop     | [2637ec62e5](https://linux-hardware.org/?probe=2637ec62e5) | Oct 18, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [04bef71f33](https://linux-hardware.org/?probe=04bef71f33) | Oct 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9d471dbf37](https://linux-hardware.org/?probe=9d471dbf37) | Oct 18, 2022 |
| Dell          | Latitude 3380               | Notebook    | [76a82ca1e6](https://linux-hardware.org/?probe=76a82ca1e6) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [ab6969eabd](https://linux-hardware.org/?probe=ab6969eabd) | Oct 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [57436f7d31](https://linux-hardware.org/?probe=57436f7d31) | Oct 17, 2022 |
| HP            | 2B36                        | Desktop     | [b4e2f30d82](https://linux-hardware.org/?probe=b4e2f30d82) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [b140bed0ec](https://linux-hardware.org/?probe=b140bed0ec) | Oct 17, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [f7e44be1b5](https://linux-hardware.org/?probe=f7e44be1b5) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [4ab8d609e7](https://linux-hardware.org/?probe=4ab8d609e7) | Oct 16, 2022 |
| HP            | 86EE                        | All in one  | [8a8d043075](https://linux-hardware.org/?probe=8a8d043075) | Oct 16, 2022 |
| Acer          | Predator G3-710             | Desktop     | [289b6c8a18](https://linux-hardware.org/?probe=289b6c8a18) | Oct 16, 2022 |
| Dell          | Latitude 3350               | Notebook    | [4c634a0308](https://linux-hardware.org/?probe=4c634a0308) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [411a334a74](https://linux-hardware.org/?probe=411a334a74) | Oct 16, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [8781d340f7](https://linux-hardware.org/?probe=8781d340f7) | Oct 16, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [ed4dba1f16](https://linux-hardware.org/?probe=ed4dba1f16) | Oct 14, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d928c22430](https://linux-hardware.org/?probe=d928c22430) | Oct 14, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [ad1d808caa](https://linux-hardware.org/?probe=ad1d808caa) | Oct 14, 2022 |
| Schenker      | SLIM_13_14_SSL13_14L18      | Notebook    | [b7bd0894f2](https://linux-hardware.org/?probe=b7bd0894f2) | Oct 13, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [478ba58d34](https://linux-hardware.org/?probe=478ba58d34) | Oct 13, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [11573d282c](https://linux-hardware.org/?probe=11573d282c) | Oct 13, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [1a2fe5eeb4](https://linux-hardware.org/?probe=1a2fe5eeb4) | Oct 12, 2022 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [79f94ede46](https://linux-hardware.org/?probe=79f94ede46) | Oct 11, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [8e93637f42](https://linux-hardware.org/?probe=8e93637f42) | Oct 11, 2022 |
| ASUSTek       | X705UDR                     | Notebook    | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [3341f329c9](https://linux-hardware.org/?probe=3341f329c9) | Oct 11, 2022 |
| System76      | Oryx Pro                    | Notebook    | [5e2fd69a86](https://linux-hardware.org/?probe=5e2fd69a86) | Oct 11, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa7d067a6f](https://linux-hardware.org/?probe=aa7d067a6f) | Oct 11, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [1a8e6d1061](https://linux-hardware.org/?probe=1a8e6d1061) | Oct 10, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [b90b027e31](https://linux-hardware.org/?probe=b90b027e31) | Oct 10, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [ed74f1da66](https://linux-hardware.org/?probe=ed74f1da66) | Oct 10, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [b98f2dc115](https://linux-hardware.org/?probe=b98f2dc115) | Oct 08, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [593d28a4cf](https://linux-hardware.org/?probe=593d28a4cf) | Oct 08, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [c7ae238295](https://linux-hardware.org/?probe=c7ae238295) | Oct 07, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [c963b4157a](https://linux-hardware.org/?probe=c963b4157a) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [c5cc32bb50](https://linux-hardware.org/?probe=c5cc32bb50) | Oct 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| MSI           | CR61 3M                     | Notebook    | [496910c25b](https://linux-hardware.org/?probe=496910c25b) | Oct 04, 2022 |
| Lenovo        | ThinkPad Edge 03193UG       | Notebook    | [49afe38831](https://linux-hardware.org/?probe=49afe38831) | Oct 04, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4a364c0802](https://linux-hardware.org/?probe=4a364c0802) | Oct 04, 2022 |
| Sony          | SVE14A27CXH                 | Notebook    | [09cb572f35](https://linux-hardware.org/?probe=09cb572f35) | Oct 03, 2022 |
| MSI           | CR61 3M                     | Notebook    | [818a721825](https://linux-hardware.org/?probe=818a721825) | Oct 02, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [318010d949](https://linux-hardware.org/?probe=318010d949) | Oct 01, 2022 |
| Casper        | C15B                        | Desktop     | [be4c7469a6](https://linux-hardware.org/?probe=be4c7469a6) | Oct 01, 2022 |
| ASRock        | H87M Pro4                   | Desktop     | [bf8e635afa](https://linux-hardware.org/?probe=bf8e635afa) | Oct 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [f6e2c51367](https://linux-hardware.org/?probe=f6e2c51367) | Sep 30, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [e7ef06706d](https://linux-hardware.org/?probe=e7ef06706d) | Sep 30, 2022 |
| ASRock        | H87M Pro4                   | Desktop     | [f8bb8b6de8](https://linux-hardware.org/?probe=f8bb8b6de8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [adf7389f06](https://linux-hardware.org/?probe=adf7389f06) | Sep 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [afe1282d38](https://linux-hardware.org/?probe=afe1282d38) | Sep 29, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Dell          | Latitude 3410               | Notebook    | [0f7ad40255](https://linux-hardware.org/?probe=0f7ad40255) | Sep 29, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [b248539946](https://linux-hardware.org/?probe=b248539946) | Sep 29, 2022 |
| HP            | 2B2C                        | Desktop     | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [37a7291916](https://linux-hardware.org/?probe=37a7291916) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [113f7431d5](https://linux-hardware.org/?probe=113f7431d5) | Sep 28, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [cf8fefa8b5](https://linux-hardware.org/?probe=cf8fefa8b5) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [d0f2ed977a](https://linux-hardware.org/?probe=d0f2ed977a) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [ecdbe4f54f](https://linux-hardware.org/?probe=ecdbe4f54f) | Sep 28, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [9489561c26](https://linux-hardware.org/?probe=9489561c26) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | Notebook    | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [45031620df](https://linux-hardware.org/?probe=45031620df) | Sep 27, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [4a86d53530](https://linux-hardware.org/?probe=4a86d53530) | Sep 25, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [71766e04c0](https://linux-hardware.org/?probe=71766e04c0) | Sep 23, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3666836ba0](https://linux-hardware.org/?probe=3666836ba0) | Sep 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [6cb872fe4a](https://linux-hardware.org/?probe=6cb872fe4a) | Sep 22, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [832a8d1947](https://linux-hardware.org/?probe=832a8d1947) | Sep 22, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a06139b33d](https://linux-hardware.org/?probe=a06139b33d) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82ec942b27](https://linux-hardware.org/?probe=82ec942b27) | Sep 17, 2022 |
| Packard Be... | IMEDIA S3850                | Desktop     | [1fd4536a73](https://linux-hardware.org/?probe=1fd4536a73) | Sep 16, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [37681cbc64](https://linux-hardware.org/?probe=37681cbc64) | Sep 11, 2022 |
| ASUSTek       | E402BA                      | Notebook    | [e672656164](https://linux-hardware.org/?probe=e672656164) | Sep 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6bb6224efd](https://linux-hardware.org/?probe=6bb6224efd) | Sep 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 1729      | 90.48%  |
| ArcoLinux             | 134       | 7.01%   |
| ArcoLinux 20.6.5      | 11        | 0.58%   |
| ArcoLinux 20.7.5      | 8         | 0.42%   |
| ArcoLinux 20.3.4      | 4         | 0.21%   |
| ArcoLinux 20.3.3      | 3         | 0.16%   |
| ArcoLinux 20.2.12     | 3         | 0.16%   |
| ArcoLinux 19.12.15    | 3         | 0.16%   |
| ArcoLinux 19.07.11    | 3         | 0.16%   |
| ArcoLinux 20.1.4      | 2         | 0.1%    |
| ArcoLinux 19.02.4     | 2         | 0.1%    |
| ArcoLinux I3-v19.02.4 | 1         | 0.05%   |
| ArcoLinux 6.9.2       | 1         | 0.05%   |
| ArcoLinux 6.9.1       | 1         | 0.05%   |
| ArcoLinux 20.5.7      | 1         | 0.05%   |
| ArcoLinux 20.5.2      | 1         | 0.05%   |
| ArcoLinux 20.4.11     | 1         | 0.05%   |
| ArcoLinux 20.2.9      | 1         | 0.05%   |
| ArcoLinux 19.11.3     | 1         | 0.05%   |
| ArcoLinux 19.03.3     | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 1894      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.15.7-arch1-1  | 48        | 2.08%   |
| 5.15.10-arch1-1 | 39        | 1.69%   |
| 5.13.13-arch1-1 | 38        | 1.65%   |
| 6.3.2-arch1-1   | 26        | 1.13%   |
| 5.14.14-arch1-1 | 26        | 1.13%   |
| 5.16.11-arch1-1 | 25        | 1.09%   |
| 6.2.11-arch1-1  | 24        | 1.04%   |
| 6.2.8-arch1-1   | 23        | 1%      |
| 6.3.9-arch1-1   | 22        | 0.96%   |
| 5.13.12-arch1-1 | 22        | 0.96%   |
| 5.14.12-arch1-1 | 21        | 0.91%   |
| 6.1.12-arch1-1  | 20        | 0.87%   |
| 6.3.7-arch1-1   | 19        | 0.83%   |
| 5.17.1-arch1-1  | 18        | 0.78%   |
| 6.3.8-arch1-1   | 16        | 0.69%   |
| 6.3.3-arch1-1   | 16        | 0.69%   |
| 5.8.14-arch1-1  | 16        | 0.69%   |
| 5.12.13-arch1-2 | 16        | 0.69%   |
| 6.3.5-arch1-1   | 15        | 0.65%   |
| 6.3.4-arch1-1   | 15        | 0.65%   |
| 5.9.14-arch1-1  | 15        | 0.65%   |
| 5.19.13-arch1-1 | 15        | 0.65%   |
| 5.16.2-arch1-1  | 15        | 0.65%   |
| 5.12.15-arch1-1 | 15        | 0.65%   |
| 6.3.6-arch1-1   | 14        | 0.61%   |
| 6.3.1-arch2-1   | 14        | 0.61%   |
| 6.0.8-arch1-1   | 14        | 0.61%   |
| 5.15.5-arch1-1  | 14        | 0.61%   |
| 5.15.11-arch2-1 | 14        | 0.61%   |
| 6.3.1-arch1-1   | 13        | 0.56%   |
| 6.0.12-arch1-1  | 13        | 0.56%   |
| 5.9.8-arch1-1   | 13        | 0.56%   |
| 5.17.9-arch1-1  | 13        | 0.56%   |
| 5.15.4-arch1-1  | 13        | 0.56%   |
| 5.12.12-arch1-1 | 13        | 0.56%   |
| 6.0.2-arch1-1   | 12        | 0.52%   |
| 5.9.1-arch1-1   | 12        | 0.52%   |
| 5.17.5-arch1-1  | 12        | 0.52%   |
| 5.15.2-arch1-1  | 12        | 0.52%   |
| 5.12.10-arch1-1 | 12        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.7  | 59        | 2.56%   |
| 5.15.10 | 41        | 1.78%   |
| 5.13.13 | 38        | 1.65%   |
| 6.3.2   | 35        | 1.52%   |
| 6.3.1   | 32        | 1.39%   |
| 6.1.12  | 28        | 1.22%   |
| 5.16.11 | 28        | 1.22%   |
| 6.3.8   | 27        | 1.17%   |
| 6.2.11  | 27        | 1.17%   |
| 6.2.8   | 26        | 1.13%   |
| 5.14.14 | 26        | 1.13%   |
| 6.3.9   | 25        | 1.09%   |
| 6.0.2   | 25        | 1.09%   |
| 5.17.1  | 25        | 1.09%   |
| 6.3.3   | 24        | 1.04%   |
| 5.14.12 | 24        | 1.04%   |
| 5.13.12 | 24        | 1.04%   |
| 6.3.7   | 22        | 0.96%   |
| 6.3.5   | 22        | 0.96%   |
| 6.3.4   | 22        | 0.96%   |
| 6.0.8   | 19        | 0.83%   |
| 5.9.14  | 19        | 0.83%   |
| 5.16.2  | 19        | 0.83%   |
| 5.9.8   | 18        | 0.78%   |
| 5.17.5  | 18        | 0.78%   |
| 5.15.4  | 18        | 0.78%   |
| 5.12.15 | 18        | 0.78%   |
| 5.12.13 | 18        | 0.78%   |
| 6.3.6   | 17        | 0.74%   |
| 6.2.10  | 17        | 0.74%   |
| 5.8.14  | 17        | 0.74%   |
| 6.2.12  | 16        | 0.69%   |
| 5.9.6   | 16        | 0.69%   |
| 5.15.5  | 16        | 0.69%   |
| 6.1.1   | 15        | 0.65%   |
| 6.0.12  | 15        | 0.65%   |
| 5.9.1   | 15        | 0.65%   |
| 5.19.13 | 15        | 0.65%   |
| 5.15.11 | 15        | 0.65%   |
| 6.1.11  | 14        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15     | 300       | 13.58%  |
| 6.3      | 217       | 9.82%   |
| 5.10     | 214       | 9.69%   |
| 6.1      | 171       | 7.74%   |
| 6.2      | 138       | 6.25%   |
| 5.16     | 132       | 5.98%   |
| 5.14     | 131       | 5.93%   |
| 6.0      | 122       | 5.52%   |
| 5.13     | 110       | 4.98%   |
| 5.9      | 109       | 4.93%   |
| 5.12     | 107       | 4.84%   |
| 5.17     | 92        | 4.16%   |
| 5.18     | 87        | 3.94%   |
| 5.11     | 77        | 3.49%   |
| 5.19     | 72        | 3.26%   |
| 5.4      | 60        | 2.72%   |
| 5.8      | 34        | 1.54%   |
| 5.6      | 7         | 0.32%   |
| 5.7      | 6         | 0.27%   |
| 5.5      | 5         | 0.23%   |
| 5.3      | 3         | 0.14%   |
| 5.0      | 3         | 0.14%   |
| 5.15.96  | 2         | 0.09%   |
| 4.19     | 2         | 0.09%   |
| 6.4      | 1         | 0.05%   |
| 6.3.0    | 1         | 0.05%   |
| 6.2.0    | 1         | 0.05%   |
| 5.2      | 1         | 0.05%   |
| 5.15.107 | 1         | 0.05%   |
| 4.20     | 1         | 0.05%   |
| 4.18     | 1         | 0.05%   |
| 4.17     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1894      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 649       | 32.19%  |
| KDE5           | 400       | 19.84%  |
| i3             | 138       | 6.85%   |
| GNOME          | 128       | 6.35%   |
| awesome        | 113       | 5.61%   |
| qtile          | 74        | 3.67%   |
| X-Cinnamon     | 65        | 3.22%   |
| bspwm          | 62        | 3.08%   |
| xmonad         | 52        | 2.58%   |
| DWM            | 44        | 2.18%   |
| Hyprland       | 39        | 1.93%   |
| LeftWM         | 31        | 1.54%   |
| Cinnamon       | 29        | 1.44%   |
| Unknown        | 26        | 1.29%   |
| KDE            | 25        | 1.24%   |
| Deepin         | 25        | 1.24%   |
| LXQt           | 17        | 0.84%   |
| MATE           | 16        | 0.79%   |
| chadwm         | 15        | 0.74%   |
| Budgie         | 13        | 0.64%   |
| i3-with-shmlog | 12        | 0.6%    |
| herbstluftwm   | 12        | 0.6%    |
| sway           | 5         | 0.25%   |
| ICEWM          | 4         | 0.2%    |
| Cutefish       | 4         | 0.2%    |
| Unity          | 3         | 0.15%   |
| spectrwm       | 3         | 0.15%   |
| openbox        | 3         | 0.15%   |
| cwm            | 3         | 0.15%   |
| dusk           | 2         | 0.1%    |
| jwm            | 1         | 0.05%   |
| Hypr           | 1         | 0.05%   |
| GNOME Classic  | 1         | 0.05%   |
| dwm-sc         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1707      | 88.81%  |
| Wayland | 107       | 5.57%   |
| Tty     | 96        | 4.99%   |
| Unknown | 12        | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1142      | 56.87%  |
| LightDM | 340       | 16.93%  |
| TDM     | 295       | 14.69%  |
| Unknown | 176       | 8.76%   |
| GDM     | 44        | 2.19%   |
| Ly      | 6         | 0.3%    |
| LXDM    | 3         | 0.15%   |
| XDM     | 1         | 0.05%   |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1078      | 56.15%  |
| en_GB   | 162       | 8.44%   |
| de_DE   | 92        | 4.79%   |
| en_CA   | 67        | 3.49%   |
| en_IN   | 50        | 2.6%    |
| fr_FR   | 38        | 1.98%   |
| en_AU   | 37        | 1.93%   |
| ru_RU   | 33        | 1.72%   |
| es_ES   | 30        | 1.56%   |
| C       | 30        | 1.56%   |
| pt_BR   | 28        | 1.46%   |
| pl_PL   | 21        | 1.09%   |
| it_IT   | 16        | 0.83%   |
| en_ZA   | 16        | 0.83%   |
| Unknown | 14        | 0.73%   |
| es_AR   | 13        | 0.68%   |
| tr_TR   | 12        | 0.63%   |
| sv_SE   | 12        | 0.63%   |
| hu_HU   | 12        | 0.63%   |
| es_MX   | 11        | 0.57%   |
| nl_NL   | 9         | 0.47%   |
| en_DK   | 8         | 0.42%   |
| fr_CA   | 7         | 0.36%   |
| en_IE   | 7         | 0.36%   |
| pt_PT   | 6         | 0.31%   |
| fi_FI   | 6         | 0.31%   |
| en_IL   | 6         | 0.31%   |
| zh_CN   | 5         | 0.26%   |
| ru_UA   | 5         | 0.26%   |
| nl_BE   | 5         | 0.26%   |
| en_SG   | 5         | 0.26%   |
| en_PH   | 5         | 0.26%   |
| de_ch   | 5         | 0.26%   |
| ja_JP   | 4         | 0.21%   |
| es_CO   | 4         | 0.21%   |
| en_AG   | 4         | 0.21%   |
| de_AT   | 4         | 0.21%   |
| nb_NO   | 3         | 0.16%   |
| fr_BE   | 3         | 0.16%   |
| es_CL   | 3         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1403      | 73.34%  |
| BIOS | 510       | 26.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1407      | 72.56%  |
| Btrfs    | 392       | 20.22%  |
| Overlay  | 92        | 4.74%   |
| Xfs      | 24        | 1.24%   |
| F2fs     | 12        | 0.62%   |
| Unknown  | 8         | 0.41%   |
| Jfs      | 2         | 0.1%    |
| Tmpfs    | 1         | 0.05%   |
| Reiserfs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1486      | 77.36%  |
| MBR     | 271       | 14.11%  |
| Unknown | 164       | 8.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1454      | 74.3%   |
| Yes       | 503       | 25.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1134      | 59.25%  |
| Yes       | 780       | 40.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 389       | 20.54%  |
| Lenovo              | 316       | 16.68%  |
| Hewlett-Packard     | 207       | 10.93%  |
| Dell                | 205       | 10.82%  |
| Gigabyte Technology | 154       | 8.13%   |
| MSI                 | 153       | 8.08%   |
| Acer                | 78        | 4.12%   |
| ASRock              | 75        | 3.96%   |
| Apple               | 45        | 2.38%   |
| Toshiba             | 23        | 1.21%   |
| Intel               | 19        | 1%      |
| Supermicro          | 18        | 0.95%   |
| Unknown             | 18        | 0.95%   |
| HUAWEI              | 12        | 0.63%   |
| Sony                | 11        | 0.58%   |
| System76            | 10        | 0.53%   |
| Samsung Electronics | 10        | 0.53%   |
| Medion              | 10        | 0.53%   |
| Fujitsu             | 9         | 0.48%   |
| Alienware           | 9         | 0.48%   |
| Razer               | 8         | 0.42%   |
| TUXEDO              | 7         | 0.37%   |
| Timi                | 7         | 0.37%   |
| Notebook            | 6         | 0.32%   |
| Chuwi               | 5         | 0.26%   |
| AZW                 | 5         | 0.26%   |
| Pegatron            | 4         | 0.21%   |
| Packard Bell        | 4         | 0.21%   |
| ZOTAC               | 3         | 0.16%   |
| Schenker            | 3         | 0.16%   |
| Microsoft           | 3         | 0.16%   |
| LG Electronics      | 3         | 0.16%   |
| Foxconn             | 3         | 0.16%   |
| Casper              | 3         | 0.16%   |
| Biostar             | 3         | 0.16%   |
| BESSTAR Tech        | 3         | 0.16%   |
| Teclast             | 2         | 0.11%   |
| SYWZ                | 2         | 0.11%   |
| Shuttle             | 2         | 0.11%   |
| NEC Computers       | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 23        | 1.21%   |
| ASUS TUF Gaming X570-PLUS        | 17        | 0.9%    |
| ASUS All Series                  | 17        | 0.9%    |
| ASUS ROG STRIX B550-F GAMING     | 12        | 0.63%   |
| Supermicro SYS-5019A-FTN4        | 10        | 0.53%   |
| ASUS PRIME X570-P                | 10        | 0.53%   |
| MSI MS-7C37                      | 9         | 0.48%   |
| MSI MS-7C91                      | 8         | 0.42%   |
| ASUS PRIME X470-PRO              | 8         | 0.42%   |
| MSI MS-7B89                      | 7         | 0.37%   |
| HP Pavilion Notebook             | 7         | 0.37%   |
| MSI MS-7B79                      | 6         | 0.32%   |
| HP Notebook                      | 6         | 0.32%   |
| MSI MS-7C95                      | 5         | 0.26%   |
| MSI MS-7C02                      | 5         | 0.26%   |
| MSI MS-7A38                      | 5         | 0.26%   |
| MSI MS-7971                      | 5         | 0.26%   |
| HP Laptop 15s-eq2xxx             | 5         | 0.26%   |
| Gigabyte X570 AORUS PRO WIFI     | 5         | 0.26%   |
| Gigabyte X570 AORUS MASTER       | 5         | 0.26%   |
| Gigabyte B450 AORUS ELITE        | 5         | 0.26%   |
| Dell OptiPlex 7010               | 5         | 0.26%   |
| ASUS ROG CROSSHAIR VIII HERO     | 5         | 0.26%   |
| ASUS PRIME B450M-A               | 5         | 0.26%   |
| ASUS PRIME A320M-K               | 5         | 0.26%   |
| ASRock B450M Pro4                | 5         | 0.26%   |
| Razer Blade                      | 4         | 0.21%   |
| MSI MS-7B98                      | 4         | 0.21%   |
| MSI MS-7B86                      | 4         | 0.21%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ | 4         | 0.21%   |
| HUAWEI KLVL-WXX9                 | 4         | 0.21%   |
| HP ProDesk 600 G1 SFF            | 4         | 0.21%   |
| HP Laptop 15-da0xxx              | 4         | 0.21%   |
| HP EliteBook 840 G3              | 4         | 0.21%   |
| Gigabyte X570 AORUS ELITE        | 4         | 0.21%   |
| Gigabyte B450M DS3H V2           | 4         | 0.21%   |
| Dell XPS 15 9570                 | 4         | 0.21%   |
| Dell OptiPlex 9020               | 4         | 0.21%   |
| Dell OptiPlex 9010               | 4         | 0.21%   |
| ASUS Z170 PRO GAMING             | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 149       | 7.87%   |
| ASUS PRIME                | 73        | 3.85%   |
| ASUS ROG                  | 69        | 3.64%   |
| Lenovo IdeaPad            | 65        | 3.43%   |
| Dell Inspiron             | 60        | 3.17%   |
| Dell Latitude             | 49        | 2.59%   |
| Acer Aspire               | 49        | 2.59%   |
| ASUS TUF                  | 47        | 2.48%   |
| HP Pavilion               | 39        | 2.06%   |
| Dell XPS                  | 29        | 1.53%   |
| Dell OptiPlex             | 29        | 1.53%   |
| HP Laptop                 | 28        | 1.48%   |
| ASUS VivoBook             | 28        | 1.48%   |
| Lenovo Legion             | 26        | 1.37%   |
| HP EliteBook              | 24        | 1.27%   |
| Unknown                   | 23        | 1.21%   |
| Gigabyte X570             | 20        | 1.06%   |
| Toshiba Satellite         | 19        | 1%      |
| HP ENVY                   | 19        | 1%      |
| Dell Precision            | 17        | 0.9%    |
| ASUS All                  | 17        | 0.9%    |
| Lenovo Yoga               | 16        | 0.84%   |
| Lenovo ThinkCentre        | 14        | 0.74%   |
| Dell Vostro               | 12        | 0.63%   |
| Gigabyte B450M            | 11        | 0.58%   |
| Gigabyte B450             | 11        | 0.58%   |
| Acer Nitro                | 11        | 0.58%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.53%   |
| MSI MS-7C37               | 9         | 0.48%   |
| HP OMEN                   | 9         | 0.48%   |
| HP EliteDesk              | 9         | 0.48%   |
| HP Compaq                 | 9         | 0.48%   |
| Razer Blade               | 8         | 0.42%   |
| MSI MS-7C91               | 8         | 0.42%   |
| HP ProBook                | 8         | 0.42%   |
| ASUS ZenBook              | 8         | 0.42%   |
| ASUS P8Z77-V              | 8         | 0.42%   |
| ASRock B450M              | 8         | 0.42%   |
| Apple MacBookPro11        | 8         | 0.42%   |
| MSI MS-7B89               | 7         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 261       | 13.78%  |
| 2020    | 252       | 13.31%  |
| 2018    | 235       | 12.41%  |
| 2017    | 162       | 8.55%   |
| 2021    | 157       | 8.29%   |
| 2013    | 120       | 6.34%   |
| 2016    | 114       | 6.02%   |
| 2015    | 107       | 5.65%   |
| 2012    | 106       | 5.6%    |
| 2011    | 99        | 5.23%   |
| 2014    | 87        | 4.59%   |
| 2010    | 64        | 3.38%   |
| 2022    | 53        | 2.8%    |
| 2009    | 27        | 1.43%   |
| 2008    | 25        | 1.32%   |
| 2007    | 11        | 0.58%   |
| 2023    | 7         | 0.37%   |
| 2006    | 5         | 0.26%   |
| 2005    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 976       | 51.53%  |
| Desktop     | 825       | 43.56%  |
| Convertible | 38        | 2.01%   |
| Mini pc     | 23        | 1.21%   |
| All in one  | 20        | 1.06%   |
| Tablet      | 6         | 0.32%   |
| Server      | 5         | 0.26%   |
| Stick pc    | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1893      | 99.95%  |
| Enabled  | 1         | 0.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1888      | 99.68%  |
| Yes  | 6         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 512       | 26.67%  |
| 4.01-8.0        | 435       | 22.66%  |
| 8.01-16.0       | 335       | 17.45%  |
| 32.01-64.0      | 311       | 16.2%   |
| 3.01-4.0        | 174       | 9.06%   |
| 64.01-256.0     | 78        | 4.06%   |
| 24.01-32.0      | 47        | 2.45%   |
| 1.01-2.0        | 18        | 0.94%   |
| 2.01-3.0        | 8         | 0.42%   |
| More than 256.0 | 1         | 0.05%   |
| Unknown         | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 627       | 29.45%  |
| 2.01-3.0   | 529       | 24.85%  |
| 4.01-8.0   | 353       | 16.58%  |
| 3.01-4.0   | 307       | 14.42%  |
| 0.51-1.0   | 178       | 8.36%   |
| 8.01-16.0  | 96        | 4.51%   |
| 0.01-0.5   | 27        | 1.27%   |
| 16.01-24.0 | 10        | 0.47%   |
| 24.01-32.0 | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 893       | 45.47%  |
| 2      | 573       | 29.18%  |
| 3      | 236       | 12.02%  |
| 4      | 135       | 6.87%   |
| 5      | 67        | 3.41%   |
| 6      | 26        | 1.32%   |
| 7      | 14        | 0.71%   |
| 0      | 6         | 0.31%   |
| 9      | 5         | 0.25%   |
| 11     | 3         | 0.15%   |
| 8      | 3         | 0.15%   |
| 21     | 1         | 0.05%   |
| 19     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1398      | 73.39%  |
| Yes       | 507       | 26.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1674      | 88.06%  |
| No        | 227       | 11.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1437      | 75.71%  |
| No        | 461       | 24.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1307      | 68.04%  |
| No        | 614       | 31.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 424       | 22.23%  |
| Germany      | 145       | 7.6%    |
| UK           | 114       | 5.98%   |
| Canada       | 89        | 4.67%   |
| India        | 77        | 4.04%   |
| Brazil       | 58        | 3.04%   |
| France       | 57        | 2.99%   |
| Belgium      | 47        | 2.46%   |
| Spain        | 46        | 2.41%   |
| Russia       | 46        | 2.41%   |
| Netherlands  | 42        | 2.2%    |
| Poland       | 40        | 2.1%    |
| Australia    | 40        | 2.1%    |
| Sweden       | 36        | 1.89%   |
| Italy        | 35        | 1.84%   |
| Turkey       | 34        | 1.78%   |
| Switzerland  | 24        | 1.26%   |
| Argentina    | 23        | 1.21%   |
| Mexico       | 22        | 1.15%   |
| Hungary      | 22        | 1.15%   |
| Romania      | 21        | 1.1%    |
| Norway       | 19        | 1%      |
| Indonesia    | 19        | 1%      |
| Ukraine      | 18        | 0.94%   |
| South Africa | 17        | 0.89%   |
| Portugal     | 17        | 0.89%   |
| Greece       | 17        | 0.89%   |
| Finland      | 17        | 0.89%   |
| Bulgaria     | 17        | 0.89%   |
| Austria      | 14        | 0.73%   |
| Denmark      | 12        | 0.63%   |
| Czechia      | 12        | 0.63%   |
| Colombia     | 12        | 0.63%   |
| Bangladesh   | 12        | 0.63%   |
| Ireland      | 11        | 0.58%   |
| China        | 11        | 0.58%   |
| Serbia       | 10        | 0.52%   |
| Malaysia     | 10        | 0.52%   |
| Japan        | 10        | 0.52%   |
| Egypt        | 9         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sydney            | 20        | 0.99%   |
| Berlin            | 19        | 0.94%   |
| Durham            | 17        | 0.84%   |
| Madrid            | 13        | 0.64%   |
| Warsaw            | 12        | 0.59%   |
| Paris             | 12        | 0.59%   |
| Moscow            | 12        | 0.59%   |
| Toronto           | 11        | 0.54%   |
| New York          | 11        | 0.54%   |
| Lier              | 11        | 0.54%   |
| Istanbul          | 11        | 0.54%   |
| Houston           | 11        | 0.54%   |
| Vienna            | 10        | 0.5%    |
| London            | 10        | 0.5%    |
| Amsterdam         | 10        | 0.5%    |
| Stockholm         | 9         | 0.45%   |
| Sao Paulo         | 9         | 0.45%   |
| Helsinki          | 9         | 0.45%   |
| Sofia             | 8         | 0.4%    |
| Pune              | 8         | 0.4%    |
| Frankfurt am Main | 8         | 0.4%    |
| Budapest          | 8         | 0.4%    |
| Bengaluru         | 8         | 0.4%    |
| Atlanta           | 8         | 0.4%    |
| Athens            | 8         | 0.4%    |
| Zurich            | 7         | 0.35%   |
| Wilrijk           | 7         | 0.35%   |
| St Petersburg     | 7         | 0.35%   |
| Portland          | 7         | 0.35%   |
| Dhaka             | 7         | 0.35%   |
| Chicago           | 7         | 0.35%   |
| Bucharest         | 7         | 0.35%   |
| Brooklyn          | 7         | 0.35%   |
| Brisbane          | 7         | 0.35%   |
| Tallinn           | 6         | 0.3%    |
| Spokane           | 6         | 0.3%    |
| Rio de Janeiro    | 6         | 0.3%    |
| Oslo              | 6         | 0.3%    |
| Milan             | 6         | 0.3%    |
| Melbourne         | 6         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 624       | 1061   | 18.97%  |
| WDC                         | 500       | 819    | 15.2%   |
| Seagate                     | 433       | 650    | 13.16%  |
| Toshiba                     | 193       | 244    | 5.87%   |
| SanDisk                     | 175       | 214    | 5.32%   |
| Kingston                    | 168       | 234    | 5.11%   |
| Crucial                     | 132       | 193    | 4.01%   |
| SK hynix                    | 89        | 113    | 2.71%   |
| Intel                       | 86        | 124    | 2.61%   |
| Hitachi                     | 67        | 78     | 2.04%   |
| Unknown                     | 61        | 88     | 1.85%   |
| A-DATA Technology           | 56        | 70     | 1.7%    |
| HGST                        | 44        | 59     | 1.34%   |
| Micron Technology           | 41        | 47     | 1.25%   |
| Phison Electronics          | 35        | 44     | 1.06%   |
| Apple                       | 29        | 41     | 0.88%   |
| Phison                      | 28        | 45     | 0.85%   |
| PNY                         | 27        | 41     | 0.82%   |
| Micron/Crucial Technology   | 25        | 35     | 0.76%   |
| KIOXIA                      | 24        | 28     | 0.73%   |
| SPCC                        | 23        | 29     | 0.7%    |
| Silicon Motion              | 21        | 24     | 0.64%   |
| JMicron Technology          | 20        | 23     | 0.61%   |
| China                       | 20        | 36     | 0.61%   |
| Corsair                     | 19        | 35     | 0.58%   |
| LITEON                      | 15        | 19     | 0.46%   |
| Kingston Technology Company | 15        | 18     | 0.46%   |
| Hewlett-Packard             | 13        | 17     | 0.4%    |
| Transcend                   | 12        | 16     | 0.36%   |
| Patriot                     | 12        | 21     | 0.36%   |
| OCZ                         | 12        | 14     | 0.36%   |
| Gigabyte Technology         | 12        | 16     | 0.36%   |
| Intenso                     | 11        | 14     | 0.33%   |
| XPG                         | 10        | 13     | 0.3%    |
| SABRENT                     | 10        | 11     | 0.3%    |
| LITEONIT                    | 10        | 10     | 0.3%    |
| ADATA Technology            | 10        | 10     | 0.3%    |
| Realtek Semiconductor       | 9         | 10     | 0.27%   |
| Plextor                     | 9         | 9      | 0.27%   |
| ASMT                        | 8         | 10     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 77        | 2.04%   |
| Samsung SSD 860 EVO 500GB                           | 53        | 1.4%    |
| Seagate ST1000LM035-1RK172 1TB                      | 41        | 1.09%   |
| Kingston SA400S37240G 240GB SSD                     | 39        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 38        | 1.01%   |
| Samsung SSD 850 EVO 250GB                           | 32        | 0.85%   |
| Samsung SSD 860 EVO 1TB                             | 30        | 0.8%    |
| Crucial CT1000MX500SSD1 1TB                         | 29        | 0.77%   |
| Toshiba MQ01ABD100 1TB                              | 28        | 0.74%   |
| Samsung SSD 850 EVO 500GB                           | 27        | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB                      | 26        | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 24        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 23        | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB                      | 23        | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB                        | 23        | 0.61%   |
| Samsung SSD 860 EVO 250GB                           | 23        | 0.61%   |
| Toshiba MQ04ABF100 1TB                              | 21        | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 21        | 0.56%   |
| Unknown SD/MMC/MS PRO 250GB                         | 19        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 19        | 0.5%    |
| Samsung SSD 870 EVO 1TB                             | 18        | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 18        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                     | 18        | 0.48%   |
| Kingston SA400S37120G 120GB SSD                     | 18        | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB                      | 17        | 0.45%   |
| Seagate Expansion 1TB                               | 16        | 0.42%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 16        | 0.42%   |
| Crucial CT500MX500SSD1 500GB                        | 16        | 0.42%   |
| Samsung SSD 970 EVO 1TB                             | 15        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 14        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 14        | 0.37%   |
| Toshiba HDWD110 1TB                                 | 14        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB                      | 14        | 0.37%   |
| JMicron Generic 240GB                               | 14        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 14        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 13        | 0.34%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 13        | 0.34%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 13        | 0.34%   |
| Seagate ST1000LM048-2E7172 1TB                      | 12        | 0.32%   |
| Samsung SSD 840 EVO 250GB                           | 12        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 419       | 621    | 36.98%  |
| WDC                 | 353       | 588    | 31.16%  |
| Toshiba             | 140       | 179    | 12.36%  |
| Hitachi             | 67        | 78     | 5.91%   |
| HGST                | 43        | 57     | 3.8%    |
| Samsung Electronics | 40        | 51     | 3.53%   |
| Unknown             | 21        | 29     | 1.85%   |
| Apple               | 9         | 13     | 0.79%   |
| SSK                 | 4         | 4      | 0.35%   |
| Maxtor              | 4         | 6      | 0.35%   |
| Hewlett-Packard     | 4         | 5      | 0.35%   |
| ASMT                | 4         | 6      | 0.35%   |
| USB3.0              | 2         | 3      | 0.18%   |
| LaCie               | 2         | 2      | 0.18%   |
| Intenso             | 2         | 2      | 0.18%   |
| Fujitsu             | 2         | 2      | 0.18%   |
| Fantom              | 2         | 5      | 0.18%   |
| ASMedia             | 2         | 3      | 0.18%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| RSH-319             | 1         | 1      | 0.09%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| KESU                | 1         | 1      | 0.09%   |
| JMicron Technology  | 1         | 3      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |
| HPE                 | 1         | 1      | 0.09%   |
| HGST HUS            | 1         | 1      | 0.09%   |
| HGST HTS            | 1         | 1      | 0.09%   |
| H/W                 | 1         | 3      | 0.09%   |
| External            | 1         | 1      | 0.09%   |
| ExcelStor           | 1         | 2      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 337       | 543    | 27.87%  |
| Kingston            | 134       | 177    | 11.08%  |
| Crucial             | 115       | 162    | 9.51%   |
| WDC                 | 102       | 137    | 8.44%   |
| SanDisk             | 99        | 115    | 8.19%   |
| A-DATA Technology   | 38        | 50     | 3.14%   |
| SK hynix            | 29        | 43     | 2.4%    |
| PNY                 | 26        | 37     | 2.15%   |
| Toshiba             | 21        | 28     | 1.74%   |
| Intel               | 21        | 27     | 1.74%   |
| China               | 20        | 36     | 1.65%   |
| SPCC                | 19        | 23     | 1.57%   |
| Micron Technology   | 18        | 22     | 1.49%   |
| Apple               | 18        | 20     | 1.49%   |
| Patriot             | 12        | 21     | 0.99%   |
| OCZ                 | 12        | 14     | 0.99%   |
| LITEON              | 12        | 16     | 0.99%   |
| Transcend           | 11        | 15     | 0.91%   |
| LITEONIT            | 10        | 10     | 0.83%   |
| Intenso             | 9         | 12     | 0.74%   |
| Corsair             | 8         | 16     | 0.66%   |
| Plextor             | 7         | 7      | 0.58%   |
| Hewlett-Packard     | 7         | 10     | 0.58%   |
| Team                | 6         | 7      | 0.5%    |
| GOODRAM             | 6         | 9      | 0.5%    |
| Gigabyte Technology | 6         | 7      | 0.5%    |
| Seagate             | 5         | 8      | 0.41%   |
| Mushkin             | 5         | 8      | 0.41%   |
| KingSpec            | 5         | 5      | 0.41%   |
| Verbatim            | 4         | 4      | 0.33%   |
| TO Exter            | 4         | 4      | 0.33%   |
| Lexar               | 4         | 4      | 0.33%   |
| External            | 4         | 8      | 0.33%   |
| ASMT                | 4         | 4      | 0.33%   |
| Unknown             | 3         | 3      | 0.25%   |
| Leven               | 3         | 3      | 0.25%   |
| HS-SSD-C100         | 3         | 4      | 0.25%   |
| Unknown             | 3         | 3      | 0.25%   |
| Vaseky              | 2         | 4      | 0.17%   |
| T-FORCE             | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 988       | 1693   | 34.44%  |
| HDD     | 940       | 1672   | 32.76%  |
| NVMe    | 872       | 1344   | 30.39%  |
| MMC     | 39        | 57     | 1.36%   |
| Unknown | 30        | 40     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1435      | 3142   | 57.01%  |
| NVMe | 861       | 1318   | 34.21%  |
| SAS  | 182       | 289    | 7.23%   |
| MMC  | 39        | 57     | 1.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 999       | 1703   | 47.94%  |
| 0.51-1.0   | 716       | 1024   | 34.36%  |
| 1.01-2.0   | 217       | 377    | 10.41%  |
| 3.01-4.0   | 60        | 98     | 2.88%   |
| 4.01-10.0  | 52        | 99     | 2.5%    |
| 2.01-3.0   | 36        | 56     | 1.73%   |
| 10.01-20.0 | 4         | 8      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 426       | 21.08%  |
| 251-500        | 397       | 19.64%  |
| 501-1000       | 324       | 16.03%  |
| 1001-2000      | 251       | 12.42%  |
| More than 3000 | 250       | 12.37%  |
| 2001-3000      | 91        | 4.5%    |
| 1-20           | 86        | 4.26%   |
| Unknown        | 85        | 4.21%   |
| 51-100         | 79        | 3.91%   |
| 21-50          | 32        | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 518       | 24.63%  |
| 21-50          | 369       | 17.55%  |
| 101-250        | 316       | 15.03%  |
| 51-100         | 236       | 11.22%  |
| 251-500        | 203       | 9.65%   |
| 501-1000       | 168       | 7.99%   |
| 1001-2000      | 103       | 4.9%    |
| Unknown        | 85        | 4.04%   |
| More than 3000 | 62        | 2.95%   |
| 2001-3000      | 41        | 1.95%   |
| 0              | 2         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 11        | 11     | 2.79%   |
| Toshiba MQ01ABD100 1TB                                          | 10        | 13     | 2.54%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 7         | 8      | 1.78%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 7         | 9      | 1.78%   |
| Toshiba MQ01ABF050 500GB                                        | 5         | 5      | 1.27%   |
| Seagate ST9320325AS 320GB                                       | 5         | 6      | 1.27%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 1.27%   |
| Hitachi HTS547575A9E384 752GB                                   | 5         | 5      | 1.27%   |
| Seagate ST3500413AS 500GB                                       | 4         | 4      | 1.02%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 4         | 4      | 1.02%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 4         | 4      | 1.02%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 3         | 3      | 0.76%   |
| Seagate ST3500312CS 500GB                                       | 3         | 5      | 0.76%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 3         | 6      | 0.76%   |
| Seagate ST1000LM014-1EJ164 1TB                                  | 3         | 3      | 0.76%   |
| SanDisk SSD PLUS 1000GB                                         | 3         | 3      | 0.76%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 3      | 0.76%   |
| Hitachi HDS721010CLA332 1TB                                     | 3         | 4      | 0.76%   |
| WDC WDS500G1X0E-00AFY0 500GB                                    | 2         | 2      | 0.51%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 2         | 2      | 0.51%   |
| WDC WD5000AAKX-603CA0 500GB                                     | 2         | 6      | 0.51%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 2         | 2      | 0.51%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 2         | 3      | 0.51%   |
| WDC WD40EFRX-68N32N0 4TB                                        | 2         | 6      | 0.51%   |
| WDC WD3200AVJS-63B6A0 320GB                                     | 2         | 5      | 0.51%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 2         | 2      | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB                                        | 2         | 3      | 0.51%   |
| WDC WD20EARX-00PASB0 2TB                                        | 2         | 2      | 0.51%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 2         | 4      | 0.51%   |
| WDC WD2002FAEX-007BA0 2TB                                       | 2         | 2      | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 2         | 2      | 0.51%   |
| WDC WD10EZEX-00WN4A0 1TB                                        | 2         | 2      | 0.51%   |
| WDC WD10EARS-22Y5B1 1TB                                         | 2         | 2      | 0.51%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 2         | 5      | 0.51%   |
| WDC WD10EADS-11M2B1 1TB                                         | 2         | 2      | 0.51%   |
| WDC WD10EADS-114BB1 1TB                                         | 2         | 2      | 0.51%   |
| WDC WD1003FZEX-00K3CA0 1TB                                      | 2         | 3      | 0.51%   |
| Toshiba MQ04ABF100 1TB                                          | 2         | 3      | 0.51%   |
| Toshiba DT01ACA100 1TB                                          | 2         | 4      | 0.51%   |
| Seagate ST9500325AS 500GB                                       | 2         | 2      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 100       | 121    | 26.67%  |
| WDC                       | 90        | 141    | 24%     |
| Toshiba                   | 31        | 38     | 8.27%   |
| Samsung Electronics       | 31        | 41     | 8.27%   |
| Hitachi                   | 22        | 26     | 5.87%   |
| HGST                      | 12        | 16     | 3.2%    |
| Sandisk                   | 9         | 9      | 2.4%    |
| Kingston                  | 9         | 11     | 2.4%    |
| Intel                     | 9         | 13     | 2.4%    |
| SK hynix                  | 6         | 7      | 1.6%    |
| Crucial                   | 6         | 6      | 1.6%    |
| Micron Technology         | 5         | 8      | 1.33%   |
| Corsair                   | 4         | 12     | 1.07%   |
| A-DATA Technology         | 4         | 4      | 1.07%   |
| Transcend                 | 3         | 3      | 0.8%    |
| Maxtor                    | 3         | 5      | 0.8%    |
| Hewlett-Packard           | 3         | 3      | 0.8%    |
| Micron/Crucial Technology | 2         | 4      | 0.53%   |
| LITEONIT                  | 2         | 2      | 0.53%   |
| Drevo                     | 2         | 2      | 0.53%   |
| China                     | 2         | 3      | 0.53%   |
| ASMedia                   | 2         | 3      | 0.53%   |
| Apple                     | 2         | 2      | 0.53%   |
| XPG                       | 1         | 1      | 0.27%   |
| USB3.0                    | 1         | 2      | 0.27%   |
| Team                      | 1         | 1      | 0.27%   |
| SSSTC                     | 1         | 1      | 0.27%   |
| SPCC                      | 1         | 1      | 0.27%   |
| Realtek Semiconductor     | 1         | 1      | 0.27%   |
| Plextor                   | 1         | 1      | 0.27%   |
| Patriot                   | 1         | 1      | 0.27%   |
| Mushkin                   | 1         | 1      | 0.27%   |
| Lenovo                    | 1         | 1      | 0.27%   |
| LaCie                     | 1         | 1      | 0.27%   |
| JMicron Technology        | 1         | 1      | 0.27%   |
| Inateck                   | 1         | 1      | 0.27%   |
| HS-SSD-C100               | 1         | 1      | 0.27%   |
| HGST HTS                  | 1         | 1      | 0.27%   |
| Unknown                   | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 121    | 36.76%  |
| WDC                 | 87        | 135    | 31.99%  |
| Toshiba             | 29        | 36     | 10.66%  |
| Hitachi             | 22        | 26     | 8.09%   |
| HGST                | 12        | 16     | 4.41%   |
| Samsung Electronics | 8         | 8      | 2.94%   |
| Maxtor              | 3         | 5      | 1.1%    |
| Hewlett-Packard     | 2         | 2      | 0.74%   |
| ASMedia             | 2         | 3      | 0.74%   |
| Apple               | 2         | 2      | 0.74%   |
| USB3.0              | 1         | 2      | 0.37%   |
| LaCie               | 1         | 1      | 0.37%   |
| Inateck             | 1         | 1      | 0.37%   |
| HGST HTS            | 1         | 1      | 0.37%   |
| Unknown             | 1         | 1      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 253       | 360    | 70.87%  |
| SSD  | 81        | 104    | 22.69%  |
| NVMe | 23        | 33     | 6.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB                      | 1         | 1      | 10%     |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 10%     |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 10%     |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 10%     |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 10%     |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 10%     |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 10%     |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 10%     |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 10%     |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 30%     |
| Samsung Electronics | 3         | 3      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| HGST                | 2         | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1569      | 3608   | 68.25%  |
| Detected | 373       | 690    | 16.22%  |
| Malfunc  | 347       | 497    | 15.09%  |
| Failed   | 10        | 11     | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1206      | 44.06%  |
| AMD                            | 492       | 17.98%  |
| Samsung Electronics            | 348       | 12.71%  |
| SanDisk                        | 144       | 5.26%   |
| Phison Electronics             | 80        | 2.92%   |
| SK hynix                       | 61        | 2.23%   |
| Kingston Technology Company    | 54        | 1.97%   |
| ASMedia Technology             | 51        | 1.86%   |
| Micron/Crucial Technology      | 44        | 1.61%   |
| Marvell Technology Group       | 31        | 1.13%   |
| Toshiba America Info Systems   | 29        | 1.06%   |
| KIOXIA                         | 29        | 1.06%   |
| ADATA Technology               | 28        | 1.02%   |
| Silicon Motion                 | 27        | 0.99%   |
| Micron Technology              | 25        | 0.91%   |
| Realtek Semiconductor          | 16        | 0.58%   |
| Nvidia                         | 14        | 0.51%   |
| Seagate Technology             | 10        | 0.37%   |
| Lite-On Technology             | 7         | 0.26%   |
| JMicron Technology             | 7         | 0.26%   |
| Union Memory (Shenzhen)        | 6         | 0.22%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.11%   |
| Lenovo                         | 3         | 0.11%   |
| Apple                          | 3         | 0.11%   |
| VIA Technologies               | 2         | 0.07%   |
| Silicon Image                  | 2         | 0.07%   |
| Shenzhen Longsys Electronics   | 2         | 0.07%   |
| Netac Technology               | 2         | 0.07%   |
| LSI Logic / Symbios Logic      | 2         | 0.07%   |
| Broadcom / LSI                 | 2         | 0.07%   |
| Adaptec                        | 2         | 0.07%   |
| TenaFe                         | 1         | 0.04%   |
| Solid State Storage Technology | 1         | 0.04%   |
| INNOGRIT                       | 1         | 0.04%   |
| Hewlett-Packard                | 1         | 0.04%   |
| Biwin Storage Technology       | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 363       | 11.89%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 190       | 6.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 117       | 3.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 110       | 3.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 87        | 2.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 76        | 2.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 68        | 2.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 63        | 2.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 61        | 2%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 58        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 55        | 1.8%    |
| Samsung NVMe SSD Controller 980                                                | 53        | 1.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 52        | 1.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 50        | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 49        | 1.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 49        | 1.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 46        | 1.51%   |
| Phison E12 NVMe Controller                                                     | 41        | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 41        | 1.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 39        | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 37        | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 35        | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 33        | 1.08%   |
| Intel SSD 660P Series                                                          | 32        | 1.05%   |
| Intel SATA Controller [RAID mode]                                              | 31        | 1.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 30        | 0.98%   |
| Phison E16 PCIe4 NVMe Controller                                               | 28        | 0.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 28        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 27        | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.85%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 25        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 25        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 25        | 0.82%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 25        | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 23        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 22        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                            | 20        | 0.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 20        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 20        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1503      | 57.21%  |
| NVMe | 861       | 32.78%  |
| RAID | 153       | 5.82%   |
| IDE  | 105       | 4%      |
| SAS  | 3         | 0.11%   |
| SCSI | 2         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1321      | 69.75%  |
| AMD     | 572       | 30.2%   |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 35        | 1.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 27        | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 27        | 1.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 24        | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 24        | 1.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 23        | 1.21%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 23        | 1.21%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 21        | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 19        | 1%      |
| AMD Ryzen 7 2700X Eight-Core Processor      | 19        | 1%      |
| AMD Ryzen 5 5600X 6-Core Processor          | 19        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz           | 18        | 0.95%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 18        | 0.95%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 18        | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 16        | 0.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 15        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 15        | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 15        | 0.79%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 15        | 0.79%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15        | 0.79%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 13        | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 13        | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 13        | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 13        | 0.68%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 12        | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 12        | 0.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 12        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 12        | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 12        | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 12        | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 12        | 0.63%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 11        | 0.58%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 11        | 0.58%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 11        | 0.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 11        | 0.58%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 11        | 0.58%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 11        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 10        | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 10        | 0.53%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 10        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 453       | 23.87%  |
| Intel Core i7           | 438       | 23.08%  |
| AMD Ryzen 5             | 187       | 9.85%   |
| AMD Ryzen 7             | 160       | 8.43%   |
| Intel Core i3           | 105       | 5.53%   |
| Other                   | 102       | 5.37%   |
| AMD Ryzen 9             | 70        | 3.69%   |
| Intel Xeon              | 42        | 2.21%   |
| Intel Pentium           | 42        | 2.21%   |
| Intel Celeron           | 41        | 2.16%   |
| AMD Ryzen 3             | 38        | 2%      |
| Intel Core 2 Duo        | 27        | 1.42%   |
| Intel Core i9           | 24        | 1.26%   |
| AMD FX                  | 21        | 1.11%   |
| Intel Atom              | 20        | 1.05%   |
| AMD A6                  | 12        | 0.63%   |
| AMD A10                 | 12        | 0.63%   |
| AMD Ryzen 7 PRO         | 9         | 0.47%   |
| Intel Pentium Dual-Core | 7         | 0.37%   |
| AMD A8                  | 7         | 0.37%   |
| AMD A4                  | 7         | 0.37%   |
| AMD Ryzen Threadripper  | 6         | 0.32%   |
| AMD Phenom II X4        | 6         | 0.32%   |
| AMD A12                 | 6         | 0.32%   |
| Intel Pentium Silver    | 5         | 0.26%   |
| Intel Pentium Dual      | 5         | 0.26%   |
| Intel Core 2 Quad       | 5         | 0.26%   |
| Intel Core 2            | 4         | 0.21%   |
| AMD Ryzen 5 PRO         | 4         | 0.21%   |
| Intel Xeon Silver       | 3         | 0.16%   |
| Intel Core m3           | 3         | 0.16%   |
| AMD E2                  | 3         | 0.16%   |
| AMD Athlon 64 X2        | 3         | 0.16%   |
| AMD Athlon              | 3         | 0.16%   |
| Intel Pentium Gold      | 2         | 0.11%   |
| AMD Phenom II X6        | 2         | 0.11%   |
| AMD E1                  | 2         | 0.11%   |
| AMD Athlon II X2        | 2         | 0.11%   |
| Intel Pentium 4         | 1         | 0.05%   |
| Intel Genuine           | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 677       | 35.65%  |
| 2       | 553       | 29.12%  |
| 6       | 310       | 16.32%  |
| 8       | 236       | 12.43%  |
| 12      | 49        | 2.58%   |
| 16      | 26        | 1.37%   |
| 10      | 16        | 0.84%   |
| 3       | 10        | 0.53%   |
| 1       | 10        | 0.53%   |
| 14      | 6         | 0.32%   |
| 24      | 2         | 0.11%   |
| 40      | 1         | 0.05%   |
| 32      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1890      | 99.74%  |
| 2       | 4         | 0.21%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1490      | 78.59%  |
| 1       | 405       | 21.36%  |
| Unknown | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1887      | 99.63%  |
| Unknown        | 7         | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 420       | 21.38%  |
| 0x306c3    | 91        | 4.63%   |
| 0x906ea    | 89        | 4.53%   |
| 0x306a9    | 86        | 4.38%   |
| 0x206a7    | 77        | 3.92%   |
| 0x08701021 | 71        | 3.62%   |
| 0x906e9    | 60        | 3.05%   |
| 0x806ea    | 49        | 2.49%   |
| 0x506e3    | 48        | 2.44%   |
| 0x806e9    | 47        | 2.39%   |
| 0x0800820d | 44        | 2.24%   |
| 0x406e3    | 43        | 2.19%   |
| 0x0a201016 | 36        | 1.83%   |
| 0x40651    | 33        | 1.68%   |
| 0x0a50000c | 33        | 1.68%   |
| 0x806ec    | 32        | 1.63%   |
| 0x806c1    | 32        | 1.63%   |
| 0x08600106 | 30        | 1.53%   |
| 0x08108109 | 29        | 1.48%   |
| 0x306d4    | 28        | 1.43%   |
| 0xa0652    | 24        | 1.22%   |
| 0x08108102 | 24        | 1.22%   |
| 0x20655    | 23        | 1.17%   |
| 0x08701013 | 23        | 1.17%   |
| 0x1067a    | 22        | 1.12%   |
| 0x0a201009 | 22        | 1.12%   |
| 0x08608103 | 18        | 0.92%   |
| 0x706e5    | 15        | 0.76%   |
| 0xa0655    | 13        | 0.66%   |
| 0x806eb    | 12        | 0.61%   |
| 0x106e5    | 12        | 0.61%   |
| 0x08101016 | 12        | 0.61%   |
| 0x30678    | 11        | 0.56%   |
| 0x08600103 | 11        | 0.56%   |
| 0x0810100b | 11        | 0.56%   |
| 0x906ed    | 10        | 0.51%   |
| 0x706a8    | 10        | 0.51%   |
| 0x506f1    | 10        | 0.51%   |
| 0x08600104 | 10        | 0.51%   |
| 0x06006705 | 10        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 405       | 21.33%  |
| Haswell          | 172       | 9.06%   |
| Zen 2            | 160       | 8.43%   |
| Zen 3            | 130       | 6.85%   |
| IvyBridge        | 128       | 6.74%   |
| Skylake          | 122       | 6.42%   |
| Zen+             | 108       | 5.69%   |
| SandyBridge      | 99        | 5.21%   |
| CometLake        | 62        | 3.26%   |
| Zen              | 45        | 2.37%   |
| TigerLake        | 45        | 2.37%   |
| Westmere         | 42        | 2.21%   |
| Broadwell        | 41        | 2.16%   |
| Unknown          | 37        | 1.95%   |
| IceLake          | 36        | 1.9%    |
| Penryn           | 35        | 1.84%   |
| Excavator        | 30        | 1.58%   |
| Silvermont       | 29        | 1.53%   |
| Alderlake Hybrid | 28        | 1.47%   |
| Piledriver       | 26        | 1.37%   |
| Goldmont plus    | 20        | 1.05%   |
| Goldmont         | 18        | 0.95%   |
| Nehalem          | 16        | 0.84%   |
| K10              | 15        | 0.79%   |
| Core             | 15        | 0.79%   |
| Steamroller      | 8         | 0.42%   |
| Puma             | 5         | 0.26%   |
| K8 Hammer        | 4         | 0.21%   |
| Jaguar           | 4         | 0.21%   |
| Tremont          | 3         | 0.16%   |
| Bulldozer        | 3         | 0.16%   |
| Bonnell          | 3         | 0.16%   |
| Bobcat           | 2         | 0.11%   |
| NetBurst         | 1         | 0.05%   |
| K8 & K10 hybrid  | 1         | 0.05%   |
| K10 Llano        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 990       | 42.62%  |
| Nvidia                     | 775       | 33.36%  |
| AMD                        | 541       | 23.29%  |
| ASPEED Technology          | 15        | 0.65%   |
| Matrox Electronics Systems | 1         | 0.04%   |
| ATI Technologies           | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 75        | 3.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 73        | 3.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 62        | 2.61%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 60        | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 58        | 2.44%   |
| Intel HD Graphics 620                                                       | 56        | 2.36%   |
| Intel UHD Graphics 620                                                      | 53        | 2.23%   |
| AMD Renoir                                                                  | 50        | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 47        | 1.98%   |
| Intel HD Graphics 630                                                       | 46        | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 42        | 1.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 41        | 1.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 39        | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 39        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 35        | 1.47%   |
| Intel HD Graphics 530                                                       | 34        | 1.43%   |
| Intel HD Graphics 5500                                                      | 33        | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 31        | 1.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 31        | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                         | 29        | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 29        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 28        | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 25        | 1.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 25        | 1.05%   |
| AMD Lucienne                                                                | 24        | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 23        | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 23        | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 21        | 0.88%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 20        | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 19        | 0.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 19        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 17        | 0.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 17        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 17        | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 15        | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 15        | 0.63%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 15        | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 15        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 15        | 0.63%   |
| ASPEED Technology ASPEED Graphics Family                                    | 15        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 604       | 31.61%  |
| 1 x AMD        | 427       | 22.34%  |
| 1 x Nvidia     | 425       | 22.24%  |
| Intel + Nvidia | 310       | 16.22%  |
| Intel + AMD    | 48        | 2.51%   |
| AMD + Nvidia   | 39        | 2.04%   |
| 2 x AMD        | 29        | 1.52%   |
| 1 x ASPEED     | 14        | 0.73%   |
| 2 x Intel      | 6         | 0.31%   |
| 2 x Nvidia     | 4         | 0.21%   |
| Other          | 3         | 0.16%   |
| 1 x Matrox     | 1         | 0.05%   |
| AMD + ASPEED   | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1345      | 70.09%  |
| Proprietary | 523       | 27.25%  |
| Unknown     | 51        | 2.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 985       | 50.83%  |
| 1.01-2.0   | 184       | 9.49%   |
| 7.01-8.0   | 172       | 8.88%   |
| 3.01-4.0   | 159       | 8.2%    |
| 0.01-0.5   | 157       | 8.1%    |
| 0.51-1.0   | 88        | 4.54%   |
| 5.01-6.0   | 82        | 4.23%   |
| 8.01-16.0  | 82        | 4.23%   |
| 2.01-3.0   | 21        | 1.08%   |
| 16.01-24.0 | 6         | 0.31%   |
| 4.01-5.0   | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 251       | 11.32%  |
| AU Optronics            | 208       | 9.38%   |
| LG Display              | 199       | 8.97%   |
| BOE                     | 175       | 7.89%   |
| Chimei Innolux          | 170       | 7.66%   |
| Dell                    | 164       | 7.39%   |
| Goldstar                | 146       | 6.58%   |
| Acer                    | 88        | 3.97%   |
| AOC                     | 73        | 3.29%   |
| BenQ                    | 70        | 3.16%   |
| Hewlett-Packard         | 68        | 3.07%   |
| Ancor Communications    | 67        | 3.02%   |
| Sharp                   | 43        | 1.94%   |
| Philips                 | 36        | 1.62%   |
| Apple                   | 36        | 1.62%   |
| Lenovo                  | 32        | 1.44%   |
| ASUSTek Computer        | 32        | 1.44%   |
| PANDA                   | 25        | 1.13%   |
| ViewSonic               | 24        | 1.08%   |
| Sony                    | 23        | 1.04%   |
| MSI                     | 20        | 0.9%    |
| Iiyama                  | 18        | 0.81%   |
| Chi Mei Optoelectronics | 16        | 0.72%   |
| Eizo                    | 15        | 0.68%   |
| CSO                     | 14        | 0.63%   |
| Vizio                   | 11        | 0.5%    |
| Unknown                 | 11        | 0.5%    |
| Sceptre Tech            | 10        | 0.45%   |
| Panasonic               | 10        | 0.45%   |
| InfoVision              | 10        | 0.45%   |
| LG Electronics          | 8         | 0.36%   |
| Gigabyte Technology     | 8         | 0.36%   |
| Unknown                 | 8         | 0.36%   |
| Toshiba                 | 7         | 0.32%   |
| Vestel Elektronik       | 5         | 0.23%   |
| HannStar                | 5         | 0.23%   |
| VIE                     | 4         | 0.18%   |
| Microstep               | 4         | 0.18%   |
| Fujitsu Siemens         | 4         | 0.18%   |
| MStar                   | 3         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 12        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 0.52%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 10        | 0.43%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.39%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9         | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 9         | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.35%   |
| Unknown                                                               | 8         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 7         | 0.3%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 7         | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 7         | 0.3%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 7         | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 6         | 0.26%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 6         | 0.26%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.26%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 0.26%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6         | 0.26%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 5         | 0.22%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.22%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 5         | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5         | 0.22%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 5         | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.22%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.22%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.22%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 0.22%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 5         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1021      | 48.92%  |
| 1366x768 (WXGA)    | 285       | 13.66%  |
| 2560x1440 (QHD)    | 171       | 8.19%   |
| 3840x2160 (4K)     | 148       | 7.09%   |
| 1600x900 (HD+)     | 65        | 3.11%   |
| 2560x1080          | 42        | 2.01%   |
| 1920x1200 (WUXGA)  | 41        | 1.96%   |
| 1680x1050 (WSXGA+) | 38        | 1.82%   |
| 1440x900 (WXGA+)   | 36        | 1.72%   |
| 1280x1024 (SXGA)   | 36        | 1.72%   |
| 3440x1440          | 31        | 1.49%   |
| 1280x800 (WXGA)    | 25        | 1.2%    |
| 3840x1080          | 17        | 0.81%   |
| 1360x768           | 17        | 0.81%   |
| Unknown            | 17        | 0.81%   |
| 2880x1800          | 15        | 0.72%   |
| 2560x1600          | 12        | 0.57%   |
| 2160x1440          | 10        | 0.48%   |
| 1920x540           | 10        | 0.48%   |
| 3840x2400          | 6         | 0.29%   |
| 3200x1800 (QHD+)   | 6         | 0.29%   |
| 1600x1200          | 6         | 0.29%   |
| 3840x1600          | 5         | 0.24%   |
| 2288x1287          | 2         | 0.1%    |
| 2160x1350          | 2         | 0.1%    |
| 2048x1152          | 2         | 0.1%    |
| 1024x600           | 2         | 0.1%    |
| 7280x1440          | 1         | 0.05%   |
| 6400x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5360x1440          | 1         | 0.05%   |
| 480x1920           | 1         | 0.05%   |
| 4096x2160          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3520x1080          | 1         | 0.05%   |
| 3286x1080          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |
| 3240x2160          | 1         | 0.05%   |
| 3200x2000          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 511       | 23.17%  |
| 27      | 225       | 10.2%   |
| 24      | 197       | 8.93%   |
| 14      | 162       | 7.35%   |
| 13      | 152       | 6.89%   |
| 23      | 144       | 6.53%   |
| 21      | 134       | 6.08%   |
| 17      | 114       | 5.17%   |
| Unknown | 78        | 3.54%   |
| 31      | 75        | 3.4%    |
| 34      | 60        | 2.72%   |
| 19      | 39        | 1.77%   |
| 18      | 37        | 1.68%   |
| 12      | 37        | 1.68%   |
| 22      | 31        | 1.41%   |
| 20      | 20        | 0.91%   |
| 84      | 19        | 0.86%   |
| 72      | 18        | 0.82%   |
| 32      | 15        | 0.68%   |
| 40      | 13        | 0.59%   |
| 16      | 13        | 0.59%   |
| 54      | 12        | 0.54%   |
| 28      | 11        | 0.5%    |
| 25      | 11        | 0.5%    |
| 11      | 9         | 0.41%   |
| 48      | 6         | 0.27%   |
| 26      | 6         | 0.27%   |
| 39      | 5         | 0.23%   |
| 10      | 5         | 0.23%   |
| 65      | 4         | 0.18%   |
| 52      | 4         | 0.18%   |
| 49      | 4         | 0.18%   |
| 42      | 4         | 0.18%   |
| 37      | 4         | 0.18%   |
| 35      | 4         | 0.18%   |
| 29      | 4         | 0.18%   |
| 46      | 3         | 0.14%   |
| 43      | 3         | 0.14%   |
| 74      | 2         | 0.09%   |
| 36      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 757       | 35.31%  |
| 501-600        | 515       | 24.02%  |
| 401-500        | 235       | 10.96%  |
| 201-300        | 136       | 6.34%   |
| 351-400        | 122       | 5.69%   |
| 601-700        | 112       | 5.22%   |
| 701-800        | 79        | 3.68%   |
| Unknown        | 78        | 3.64%   |
| 1501-2000      | 39        | 1.82%   |
| 1001-1500      | 36        | 1.68%   |
| 801-900        | 27        | 1.26%   |
| 901-1000       | 7         | 0.33%   |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1536      | 78.85%  |
| 16/10   | 188       | 9.65%   |
| 21/9    | 79        | 4.06%   |
| Unknown | 62        | 3.18%   |
| 5/4     | 33        | 1.69%   |
| 3/2     | 20        | 1.03%   |
| 4/3     | 14        | 0.72%   |
| 32/9    | 8         | 0.41%   |
| 6/5     | 4         | 0.21%   |
| 3.40    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.80    | 1         | 0.05%   |
| 0.25    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 504       | 23.14%  |
| 201-250        | 417       | 19.15%  |
| 81-90          | 251       | 11.52%  |
| 301-350        | 230       | 10.56%  |
| 351-500        | 160       | 7.35%   |
| 121-130        | 90        | 4.13%   |
| 151-200        | 83        | 3.81%   |
| Unknown        | 78        | 3.58%   |
| 251-300        | 71        | 3.26%   |
| More than 1000 | 64        | 2.94%   |
| 71-80          | 62        | 2.85%   |
| 141-150        | 51        | 2.34%   |
| 501-1000       | 41        | 1.88%   |
| 61-70          | 33        | 1.52%   |
| 51-60          | 11        | 0.51%   |
| 111-120        | 11        | 0.51%   |
| 131-140        | 9         | 0.41%   |
| 91-100         | 8         | 0.37%   |
| 41-50          | 4         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 698       | 33.37%  |
| 121-160       | 598       | 28.59%  |
| 101-120       | 511       | 24.43%  |
| 161-240       | 111       | 5.31%   |
| Unknown       | 78        | 3.73%   |
| 1-50          | 50        | 2.39%   |
| More than 240 | 46        | 2.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1418      | 73.24%  |
| 2     | 401       | 20.71%  |
| 0     | 61        | 3.15%   |
| 3     | 52        | 2.69%   |
| 4     | 4         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1075      | 38.46%  |
| Intel                                  | 1058      | 37.85%  |
| Qualcomm Atheros                       | 281       | 10.05%  |
| Broadcom                               | 106       | 3.79%   |
| MediaTek                               | 31        | 1.11%   |
| Ralink Technology                      | 26        | 0.93%   |
| TP-Link                                | 24        | 0.86%   |
| Broadcom Limited                       | 22        | 0.79%   |
| Marvell Technology Group               | 12        | 0.43%   |
| ASIX Electronics                       | 12        | 0.43%   |
| Nvidia                                 | 11        | 0.39%   |
| Sierra Wireless                        | 10        | 0.36%   |
| Microsoft                              | 9         | 0.32%   |
| Samsung Electronics                    | 8         | 0.29%   |
| Dell                                   | 8         | 0.29%   |
| Aquantia                               | 8         | 0.29%   |
| Ralink                                 | 7         | 0.25%   |
| Qualcomm Atheros Communications        | 5         | 0.18%   |
| Lenovo                                 | 5         | 0.18%   |
| Huawei Technologies                    | 5         | 0.18%   |
| Ericsson Business Mobile Networks      | 5         | 0.18%   |
| DisplayLink                            | 5         | 0.18%   |
| D-Link System                          | 5         | 0.18%   |
| Qualcomm                               | 4         | 0.14%   |
| NetGear                                | 4         | 0.14%   |
| Insyde Software                        | 4         | 0.14%   |
| Hewlett-Packard                        | 4         | 0.14%   |
| Xiaomi                                 | 3         | 0.11%   |
| JMicron Technology                     | 3         | 0.11%   |
| Fibocom                                | 3         | 0.11%   |
| D-Link                                 | 3         | 0.11%   |
| Oculus VR                              | 2         | 0.07%   |
| Emulex                                 | 2         | 0.07%   |
| ASUSTek Computer                       | 2         | 0.07%   |
| U-Blox                                 | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Solarflare Communications              | 1         | 0.04%   |
| Seeed Technology                       | 1         | 0.04%   |
| ROCCAT                                 | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 796       | 23.78%  |
| Intel Wi-Fi 6 AX200                                               | 155       | 4.63%   |
| Intel I211 Gigabit Network Connection                             | 92        | 2.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 86        | 2.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 67        | 2%      |
| Intel Wireless 8265 / 8275                                        | 65        | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 63        | 1.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 55        | 1.64%   |
| Intel Wireless 7260                                               | 51        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 50        | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 50        | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 44        | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 42        | 1.25%   |
| Intel Wireless 8260                                               | 40        | 1.19%   |
| Intel Ethernet Controller I225-V                                  | 37        | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 35        | 1.05%   |
| Intel Wireless-AC 9260                                            | 35        | 1.05%   |
| Intel Wireless 7265                                               | 35        | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 35        | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 34        | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 33        | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 31        | 0.93%   |
| Intel Wireless 3165                                               | 30        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 19        | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 19        | 0.57%   |
| Intel Wireless 3160                                               | 18        | 0.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 18        | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 17        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.48%   |
| Intel Centrino Ultimate-N 6300                                    | 16        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 15        | 0.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 808       | 53.87%  |
| Realtek Semiconductor                 | 244       | 16.27%  |
| Qualcomm Atheros                      | 219       | 14.6%   |
| Broadcom                              | 76        | 5.07%   |
| MediaTek                              | 31        | 2.07%   |
| Ralink Technology                     | 26        | 1.73%   |
| TP-Link                               | 21        | 1.4%    |
| Broadcom Limited                      | 16        | 1.07%   |
| Sierra Wireless                       | 10        | 0.67%   |
| Microsoft                             | 9         | 0.6%    |
| Ralink                                | 7         | 0.47%   |
| Qualcomm Atheros Communications       | 5         | 0.33%   |
| NetGear                               | 4         | 0.27%   |
| Dell                                  | 4         | 0.27%   |
| Fibocom                               | 3         | 0.2%    |
| D-Link                                | 3         | 0.2%    |
| Marvell Technology Group              | 2         | 0.13%   |
| Hewlett-Packard                       | 2         | 0.13%   |
| D-Link System                         | 2         | 0.13%   |
| ASUSTek Computer                      | 2         | 0.13%   |
| Realtek                               | 1         | 0.07%   |
| Ovislink                              | 1         | 0.07%   |
| IMC Networks                          | 1         | 0.07%   |
| Edimax Technology                     | 1         | 0.07%   |
| CyberTAN Technology                   | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 155       | 10.27%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 67        | 4.44%   |
| Intel Wireless 8265 / 8275                                     | 65        | 4.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 55        | 3.64%   |
| Intel Wireless 7260                                            | 51        | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 50        | 3.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 44        | 2.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 42        | 2.78%   |
| Intel Wireless 8260                                            | 40        | 2.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 35        | 2.32%   |
| Intel Wireless-AC 9260                                         | 35        | 2.32%   |
| Intel Wireless 7265                                            | 35        | 2.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 34        | 2.25%   |
| Intel Wi-Fi 6 AX201                                            | 34        | 2.25%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 33        | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 31        | 2.05%   |
| Intel Wireless 3165                                            | 30        | 1.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 1.26%   |
| Intel Wireless 3160                                            | 18        | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 18        | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 17        | 1.13%   |
| Intel Centrino Ultimate-N 6300                                 | 16        | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 15        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 13        | 0.86%   |
| Ralink MT7601U Wireless Adapter                                | 13        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 0.86%   |
| Intel Centrino Advanced-N 6200                                 | 13        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 12        | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 12        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 0.73%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 11        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 10        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 986       | 55.96%  |
| Intel                                  | 545       | 30.93%  |
| Qualcomm Atheros                       | 88        | 4.99%   |
| Broadcom                               | 48        | 2.72%   |
| ASIX Electronics                       | 12        | 0.68%   |
| Nvidia                                 | 11        | 0.62%   |
| Marvell Technology Group               | 10        | 0.57%   |
| Aquantia                               | 8         | 0.45%   |
| Broadcom Limited                       | 6         | 0.34%   |
| DisplayLink                            | 5         | 0.28%   |
| Samsung Electronics                    | 4         | 0.23%   |
| Qualcomm                               | 4         | 0.23%   |
| Lenovo                                 | 4         | 0.23%   |
| Insyde Software                        | 4         | 0.23%   |
| Xiaomi                                 | 3         | 0.17%   |
| TP-Link                                | 3         | 0.17%   |
| JMicron Technology                     | 3         | 0.17%   |
| Huawei Technologies                    | 3         | 0.17%   |
| D-Link System                          | 3         | 0.17%   |
| Emulex                                 | 2         | 0.11%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Solarflare Communications              | 1         | 0.06%   |
| Novatel Wireless                       | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| MediaTek                               | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| Google                                 | 1         | 0.06%   |
| Apple                                  | 1         | 0.06%   |
| 3Com                                   | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 796       | 43.95%  |
| Intel I211 Gigabit Network Connection                             | 92        | 5.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 86        | 4.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 63        | 3.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 62        | 3.42%   |
| Intel Ethernet Connection (2) I219-V                              | 50        | 2.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 47        | 2.6%    |
| Intel Ethernet Controller I225-V                                  | 37        | 2.04%   |
| Intel Ethernet Connection (7) I219-V                              | 35        | 1.93%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 1.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11        | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 10        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.55%   |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 8         | 0.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.39%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.39%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.33%   |
| Intel Ethernet Connection (12) I219-V                             | 5         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1670      | 53.27%  |
| WiFi     | 1437      | 45.84%  |
| Modem    | 26        | 0.83%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1079      | 54.19%  |
| Ethernet | 912       | 45.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1067      | 56.13%  |
| 1     | 745       | 39.19%  |
| 3     | 58        | 3.05%   |
| 4     | 20        | 1.05%   |
| 0     | 8         | 0.42%   |
| 5     | 2         | 0.11%   |
| 9     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1470      | 76.01%  |
| Yes  | 464       | 23.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 695       | 52.41%  |
| Realtek Semiconductor           | 136       | 10.26%  |
| Qualcomm Atheros Communications | 96        | 7.24%   |
| Cambridge Silicon Radio         | 83        | 6.26%   |
| IMC Networks                    | 59        | 4.45%   |
| Broadcom                        | 51        | 3.85%   |
| Apple                           | 47        | 3.54%   |
| Lite-On Technology              | 38        | 2.87%   |
| ASUSTek Computer                | 37        | 2.79%   |
| Foxconn / Hon Hai               | 27        | 2.04%   |
| MediaTek                        | 11        | 0.83%   |
| Dell                            | 9         | 0.68%   |
| Toshiba                         | 6         | 0.45%   |
| Realtek                         | 6         | 0.45%   |
| Belkin Components               | 4         | 0.3%    |
| TP-Link                         | 3         | 0.23%   |
| Edimax Technology               | 3         | 0.23%   |
| Dynex                           | 3         | 0.23%   |
| HTC (High Tech Computer)        | 2         | 0.15%   |
| Hewlett-Packard                 | 2         | 0.15%   |
| SINO WEALTH                     | 1         | 0.08%   |
| Ralink Technology               | 1         | 0.08%   |
| Ralink                          | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| Marvell Semiconductor           | 1         | 0.08%   |
| Creative Technology             | 1         | 0.08%   |
| Chicony Electronics             | 1         | 0.08%   |
| Actions                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 234       | 17.62%  |
| Intel AX200 Bluetooth                                 | 149       | 11.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 96        | 7.23%   |
| Intel AX201 Bluetooth                                 | 91        | 6.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 83        | 6.25%   |
| Realtek Bluetooth Radio                               | 80        | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                    | 63        | 4.74%   |
| Intel Wireless-AC 3168 Bluetooth                      | 41        | 3.09%   |
| Realtek  Bluetooth 4.2 Adapter                        | 38        | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 36        | 2.71%   |
| Apple Bluetooth USB Host Controller                   | 22        | 1.66%   |
| IMC Networks Bluetooth Radio                          | 20        | 1.51%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 19        | 1.43%   |
| IMC Networks Bluetooth Device                         | 19        | 1.43%   |
| Apple Bluetooth Host Controller                       | 19        | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                           | 17        | 1.28%   |
| Lite-On Bluetooth Device                              | 14        | 1.05%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 14        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 13        | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 12        | 0.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 12        | 0.9%    |
| Intel Bluetooth Device                                | 11        | 0.83%   |
| Intel AX210 Bluetooth                                 | 11        | 0.83%   |
| ASUS ASUS USB-BT500                                   | 11        | 0.83%   |
| MediaTek Wireless_Device                              | 10        | 0.75%   |
| Realtek RTL8821A Bluetooth                            | 9         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 9         | 0.68%   |
| IMC Networks Wireless_Device                          | 9         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                    | 8         | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 7         | 0.53%   |
| Realtek Bluetooth Radio                               | 6         | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                      | 6         | 0.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 6         | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 6         | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 4         | 0.3%    |
| Realtek RTL8723B Bluetooth                            | 4         | 0.3%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4         | 0.3%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 4         | 0.3%    |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 4         | 0.3%    |
| ASUS BCM20702A0                                       | 4         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1281      | 42.64%  |
| AMD                                  | 674       | 22.44%  |
| Nvidia                               | 621       | 20.67%  |
| C-Media Electronics                  | 64        | 2.13%   |
| Logitech                             | 42        | 1.4%    |
| Kingston Technology                  | 26        | 0.87%   |
| Texas Instruments                    | 22        | 0.73%   |
| JMTek                                | 17        | 0.57%   |
| Razer USA                            | 14        | 0.47%   |
| Focusrite-Novation                   | 14        | 0.47%   |
| Corsair                              | 13        | 0.43%   |
| Creative Technology                  | 12        | 0.4%    |
| Realtek Semiconductor                | 11        | 0.37%   |
| Generalplus Technology               | 9         | 0.3%    |
| Creative Labs                        | 9         | 0.3%    |
| ASUSTek Computer                     | 9         | 0.3%    |
| SteelSeries ApS                      | 8         | 0.27%   |
| RODE Microphones                     | 7         | 0.23%   |
| BEHRINGER International              | 7         | 0.23%   |
| SAVITECH                             | 6         | 0.2%    |
| Samson Technologies                  | 6         | 0.2%    |
| GN Netcom                            | 6         | 0.2%    |
| XMOS                                 | 5         | 0.17%   |
| Sony                                 | 5         | 0.17%   |
| Blue Microphones                     | 5         | 0.17%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.13%   |
| Sennheiser Communications            | 4         | 0.13%   |
| Scarlett                             | 4         | 0.13%   |
| PreSonus Audio Electronics           | 4         | 0.13%   |
| Plantronics                          | 4         | 0.13%   |
| Lenovo                               | 4         | 0.13%   |
| Yamaha                               | 3         | 0.1%    |
| VIA Technologies                     | 3         | 0.1%    |
| Native Instruments                   | 3         | 0.1%    |
| Hewlett-Packard                      | 3         | 0.1%    |
| FIFINE Microphones                   | 3         | 0.1%    |
| Audio-Technica                       | 3         | 0.1%    |
| Asahi Kasei Microsystems             | 3         | 0.1%    |
| Turtle Beach                         | 2         | 0.07%   |
| Project                              | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 223       | 6.27%   |
| AMD Starship/Matisse HD Audio Controller                                   | 176       | 4.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 169       | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 123       | 3.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 119       | 3.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 106       | 2.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 102       | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 101       | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 73        | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 73        | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 73        | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 71        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 63        | 1.77%   |
| Intel 200 Series PCH HD Audio                                              | 62        | 1.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 53        | 1.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 53        | 1.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 51        | 1.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 49        | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 49        | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 48        | 1.35%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 47        | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 46        | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 45        | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 42        | 1.18%   |
| Intel Comet Lake PCH cAVS                                                  | 42        | 1.18%   |
| Intel 8 Series HD Audio Controller                                         | 42        | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 39        | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 39        | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 35        | 0.98%   |
| Nvidia GA104 High Definition Audio Controller                              | 33        | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 32        | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 32        | 0.9%    |
| AMD Navi 10 HDMI Audio                                                     | 30        | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 30        | 0.84%   |
| Nvidia TU104 HD Audio Controller                                           | 27        | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.76%   |
| AMD FCH Azalia Controller                                                  | 27        | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25        | 0.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 24        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 23        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 424       | 20.62%  |
| SK hynix            | 346       | 16.83%  |
| Kingston            | 218       | 10.6%   |
| Micron Technology   | 201       | 9.78%   |
| Corsair             | 201       | 9.78%   |
| Crucial             | 161       | 7.83%   |
| G.Skill             | 121       | 5.89%   |
| Unknown             | 106       | 5.16%   |
| A-DATA Technology   | 37        | 1.8%    |
| Ramaxel Technology  | 32        | 1.56%   |
| Team                | 30        | 1.46%   |
| Nanya Technology    | 22        | 1.07%   |
| Elpida              | 19        | 0.92%   |
| Patriot             | 15        | 0.73%   |
| Unknown (ABCD)      | 11        | 0.54%   |
| GOODRAM             | 9         | 0.44%   |
| Unknown             | 8         | 0.39%   |
| Avant               | 7         | 0.34%   |
| Silicon Power       | 6         | 0.29%   |
| Apacer              | 6         | 0.29%   |
| Transcend           | 5         | 0.24%   |
| PNY                 | 5         | 0.24%   |
| Goldkey             | 5         | 0.24%   |
| Neo Forza           | 4         | 0.19%   |
| ASint Technology    | 4         | 0.19%   |
| CSX                 | 3         | 0.15%   |
| AMD                 | 3         | 0.15%   |
| Unknown (0x0B5E)    | 2         | 0.1%    |
| Unifosa             | 2         | 0.1%    |
| Teikon              | 2         | 0.1%    |
| Smart               | 2         | 0.1%    |
| Sesame              | 2         | 0.1%    |
| Lexar               | 2         | 0.1%    |
| Kingmax             | 2         | 0.1%    |
| GeIL                | 2         | 0.1%    |
| Wodposit            | 1         | 0.05%   |
| V-Color             | 1         | 0.05%   |
| Unknown (898F)      | 1         | 0.05%   |
| Unknown (0x8634)    | 1         | 0.05%   |
| Unknown (0x8319)    | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 1%      |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.72%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 16        | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 14        | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.59%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.59%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16384MB DIMM DDR4 3200MT/s         | 12        | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 12        | 0.54%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 12        | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 11        | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.45%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 10        | 0.45%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 10        | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 9         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 8         | 0.36%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 8         | 0.36%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 8         | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.36%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 8         | 0.36%   |
| Unknown                                                          | 8         | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.32%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 7         | 0.32%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 7         | 0.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.32%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 7         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1052      | 60.11%  |
| DDR3    | 516       | 29.49%  |
| LPDDR4  | 41        | 2.34%   |
| LPDDR3  | 37        | 2.11%   |
| Unknown | 27        | 1.54%   |
| SDRAM   | 24        | 1.37%   |
| DDR2    | 23        | 1.31%   |
| DDR5    | 22        | 1.26%   |
| LPDDR5  | 5         | 0.29%   |
| DDR     | 3         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 916       | 52.28%  |
| DIMM         | 735       | 41.95%  |
| Row Of Chips | 91        | 5.19%   |
| Chip         | 9         | 0.51%   |
| RIMM         | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 852       | 44.38%  |
| 4096  | 504       | 26.25%  |
| 16384 | 341       | 17.76%  |
| 2048  | 128       | 6.67%   |
| 32768 | 76        | 3.96%   |
| 1024  | 16        | 0.83%   |
| 512   | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 16    | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 371       | 19.02%  |
| 3200    | 323       | 16.56%  |
| 2667    | 313       | 16.04%  |
| 2400    | 175       | 8.97%   |
| 2133    | 95        | 4.87%   |
| 1333    | 88        | 4.51%   |
| 3600    | 87        | 4.46%   |
| 1334    | 36        | 1.85%   |
| 1867    | 35        | 1.79%   |
| 3733    | 29        | 1.49%   |
| 3000    | 27        | 1.38%   |
| 3400    | 25        | 1.28%   |
| 3266    | 24        | 1.23%   |
| 1067    | 21        | 1.08%   |
| 3800    | 16        | 0.82%   |
| 800     | 16        | 0.82%   |
| Unknown | 16        | 0.82%   |
| 4267    | 15        | 0.77%   |
| 4800    | 14        | 0.72%   |
| 3533    | 14        | 0.72%   |
| 1866    | 14        | 0.72%   |
| 667     | 14        | 0.72%   |
| 3866    | 13        | 0.67%   |
| 2933    | 13        | 0.67%   |
| 3466    | 12        | 0.62%   |
| 2800    | 12        | 0.62%   |
| 2666    | 12        | 0.62%   |
| 1800    | 10        | 0.51%   |
| 4199    | 7         | 0.36%   |
| 8400    | 6         | 0.31%   |
| 3666    | 6         | 0.31%   |
| 3334    | 6         | 0.31%   |
| 6400    | 5         | 0.26%   |
| 5200    | 5         | 0.26%   |
| 3534    | 5         | 0.26%   |
| 2465    | 5         | 0.26%   |
| 2048    | 5         | 0.26%   |
| 1648    | 5         | 0.26%   |
| 4266    | 4         | 0.21%   |
| 4000    | 4         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 16        | 34.04%  |
| Brother Industries    | 16        | 34.04%  |
| Seiko Epson           | 5         | 10.64%  |
| Canon                 | 4         | 8.51%   |
| Samsung Electronics   | 2         | 4.26%   |
| MIIIW                 | 1         | 2.13%   |
| Lexmark International | 1         | 2.13%   |
| Gprinter              | 1         | 2.13%   |
| Dymo-CoStar           | 1         | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson ET-4700 Series             | 2         | 4.17%   |
| HP DeskJet F4100 Printer series        | 2         | 4.17%   |
| HP DeskJet 2620 All-in-One Printer     | 2         | 4.17%   |
| Brother Printer                        | 2         | 4.17%   |
| Brother DCP-7055 scanner/printer       | 2         | 4.17%   |
| Seiko Epson XP-240 Series              | 1         | 2.08%   |
| Seiko Epson XP-2100 Series             | 1         | 2.08%   |
| Seiko Epson ET-2710 Series             | 1         | 2.08%   |
| Samsung SCX-3400 Series                | 1         | 2.08%   |
| Samsung SCX-3200 Series                | 1         | 2.08%   |
| MIIIW MW Keyboard Air Mini             | 1         | 2.08%   |
| Lexmark International B2236dw          | 1         | 2.08%   |
| HP OfficeJet Pro 8020 series           | 1         | 2.08%   |
| HP OfficeJet Pro 6960                  | 1         | 2.08%   |
| HP OfficeJet 5200 series               | 1         | 2.08%   |
| HP OfficeJet 4650 series               | 1         | 2.08%   |
| HP LaserJet Professional P1102w        | 1         | 2.08%   |
| HP LaserJet P1005                      | 1         | 2.08%   |
| HP LaserJet M203-M206                  | 1         | 2.08%   |
| HP LaserJet 1015                       | 1         | 2.08%   |
| HP ENVY 4500 series                    | 1         | 2.08%   |
| HP Deskjet 4640 series                 | 1         | 2.08%   |
| HP DeskJet 3700 series                 | 1         | 2.08%   |
| HP DeskJet 2700 series                 | 1         | 2.08%   |
| HP Deskjet 1050 J410                   | 1         | 2.08%   |
| Gprinter GP-58                         | 1         | 2.08%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 2.08%   |
| Canon TS5100 series                    | 1         | 2.08%   |
| Canon PIXMA MG3600 Series              | 1         | 2.08%   |
| Canon G2000 series                     | 1         | 2.08%   |
| Canon CanoScan LiDE 300                | 1         | 2.08%   |
| Brother MFC-L3770CDW series            | 1         | 2.08%   |
| Brother MFC-L3750CDW                   | 1         | 2.08%   |
| Brother MFC-J6545DW                    | 1         | 2.08%   |
| Brother MFC-J497DW                     | 1         | 2.08%   |
| Brother MFC-J485DW                     | 1         | 2.08%   |
| Brother MFC-J450DW                     | 1         | 2.08%   |
| Brother MFC-7460DN                     | 1         | 2.08%   |
| Brother HL-L2300D series               | 1         | 2.08%   |
| Brother HL-3140CW series               | 1         | 2.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 50%     |
| Hewlett-Packard | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 25%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 25%     |
| HP ScanJet 2400c                                        | 1         | 25%     |
| HP ScanJet 2200c                                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 267       | 23.34%  |
| IMC Networks                           | 126       | 11.01%  |
| Logitech                               | 92        | 8.04%   |
| Realtek Semiconductor                  | 88        | 7.69%   |
| Microdia                               | 86        | 7.52%   |
| Bison Electronics                      | 66        | 5.77%   |
| Sunplus Innovation Technology          | 59        | 5.16%   |
| Quanta                                 | 44        | 3.85%   |
| Apple                                  | 36        | 3.15%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 2.8%    |
| Acer                                   | 30        | 2.62%   |
| Syntek                                 | 28        | 2.45%   |
| Lite-On Technology                     | 24        | 2.1%    |
| Suyin                                  | 22        | 1.92%   |
| Luxvisions Innotech Limited            | 13        | 1.14%   |
| Lenovo                                 | 11        | 0.96%   |
| Microsoft                              | 10        | 0.87%   |
| Samsung Electronics                    | 9         | 0.79%   |
| Silicon Motion                         | 8         | 0.7%    |
| Sonix Technology                       | 7         | 0.61%   |
| Primax Electronics                     | 6         | 0.52%   |
| Generalplus Technology                 | 6         | 0.52%   |
| KYE Systems (Mouse Systems)            | 5         | 0.44%   |
| Creative Technology                    | 5         | 0.44%   |
| Alcor Micro                            | 5         | 0.44%   |
| Razer USA                              | 4         | 0.35%   |
| Hewlett-Packard                        | 4         | 0.35%   |
| GEMBIRD                                | 4         | 0.35%   |
| Ricoh                                  | 3         | 0.26%   |
| MacroSilicon                           | 3         | 0.26%   |
| Importek                               | 3         | 0.26%   |
| Z-Star Microelectronics                | 2         | 0.17%   |
| WaveRider Communications               | 2         | 0.17%   |
| USB Camera                             | 2         | 0.17%   |
| Sunplus Technology                     | 2         | 0.17%   |
| Ruision                                | 2         | 0.17%   |
| AVerMedia Technologies                 | 2         | 0.17%   |
| ARC International                      | 2         | 0.17%   |
| Anker                                  | 2         | 0.17%   |
| Unknown                                | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 72        | 6.26%   |
| IMC Networks Integrated Camera                      | 37        | 3.22%   |
| Realtek Integrated_Webcam_HD                        | 35        | 3.04%   |
| Microdia Integrated_Webcam_HD                       | 34        | 2.96%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 30        | 2.61%   |
| Chicony HD WebCam                                   | 28        | 2.43%   |
| Bison Integrated Camera                             | 25        | 2.17%   |
| Logitech HD Pro Webcam C920                         | 23        | 2%      |
| Logitech Webcam C270                                | 21        | 1.83%   |
| Syntek Integrated Camera                            | 18        | 1.57%   |
| Sunplus Integrated_Webcam_HD                        | 17        | 1.48%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 17        | 1.48%   |
| Lite-On Integrated Camera                           | 14        | 1.22%   |
| Chicony USB2.0 Camera                               | 12        | 1.04%   |
| Chicony USB2.0 VGA UVC WebCam                       | 11        | 0.96%   |
| Chicony HP Wide Vision HD Camera                    | 11        | 0.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 11        | 0.96%   |
| Logitech C922 Pro Stream Webcam                     | 10        | 0.87%   |
| Chicony HP Truevision HD                            | 10        | 0.87%   |
| Apple Built-in iSight                               | 10        | 0.87%   |
| Samsung Galaxy A5 (MTP)                             | 9         | 0.78%   |
| Quanta HD Webcam                                    | 9         | 0.78%   |
| Microdia Integrated Webcam                          | 9         | 0.78%   |
| Chicony EasyCamera                                  | 9         | 0.78%   |
| Acer EasyCamera                                     | 9         | 0.78%   |
| Quanta HP TrueVision HD Camera                      | 8         | 0.7%    |
| Quanta HD User Facing                               | 8         | 0.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 8         | 0.7%    |
| Chicony HD User Facing                              | 8         | 0.7%    |
| Bison BisonCam,NB Pro                               | 8         | 0.7%    |
| Apple FaceTime HD Camera (Built-in)                 | 8         | 0.7%    |
| Acer HD Webcam                                      | 8         | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                        | 7         | 0.61%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 0.61%   |
| Chicony HP TrueVision HD Camera                     | 7         | 0.61%   |
| Chicony HP HD Camera                                | 7         | 0.61%   |
| Bison BisonCam, NB Pro                              | 7         | 0.61%   |
| Acer Integrated Camera                              | 7         | 0.61%   |
| Realtek Integrated Webcam HD                        | 6         | 0.52%   |
| Microsoft LifeCam HD-3000                           | 6         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 77        | 39.49%  |
| Synaptics                  | 45        | 23.08%  |
| Shenzhen Goodix Technology | 31        | 15.9%   |
| Elan Microelectronics      | 13        | 6.67%   |
| Upek                       | 11        | 5.64%   |
| LighTuning Technology      | 10        | 5.13%   |
| AuthenTec                  | 6         | 3.08%   |
| STMicroelectronics         | 1         | 0.51%   |
| DigitalPersona             | 1         | 0.51%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 9.74%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 9.23%   |
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 7.18%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 6.15%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 5.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 5.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 5.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 3.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.59%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 3.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 3.59%   |
| Elan ELAN:Fingerprint                                                      | 7         | 3.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.08%   |
| Synaptics  WBDI                                                            | 6         | 3.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.56%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.56%   |
| Synaptics UWP WBDI                                                         | 4         | 2.05%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.54%   |
| Validity Sensors VFS491                                                    | 2         | 1.03%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.03%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 1.03%   |
| Synaptics WBDI Device                                                      | 2         | 1.03%   |
| Synaptics WBDI                                                             | 2         | 1.03%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 1.03%   |
| AuthenTec AES1600                                                          | 2         | 1.03%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.51%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.51%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.51%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.51%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.51%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.51%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.51%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.51%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.51%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.51%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.51%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.51%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 34        | 39.08%  |
| Broadcom              | 32        | 36.78%  |
| O2 Micro              | 6         | 6.9%    |
| Upek                  | 4         | 4.6%    |
| Lenovo                | 4         | 4.6%    |
| Gemalto (was Gemplus) | 2         | 2.3%    |
| Yubico.com            | 1         | 1.15%   |
| SCM Microsystems      | 1         | 1.15%   |
| OmniKey               | 1         | 1.15%   |
| Clay Logic            | 1         | 1.15%   |
| Cherry                | 1         | 1.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 39.08%  |
| Broadcom 5880                                                                | 10        | 11.49%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 9.2%    |
| Broadcom 58200                                                               | 7         | 8.05%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 6.9%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.6%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.6%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 2.3%    |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 1.15%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.15%   |
| OmniKey CardMan 1021                                                         | 1         | 1.15%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.15%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.15%   |
| Cherry Smart Card Reader USB                                                 | 1         | 1.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1415      | 73.01%  |
| 1     | 418       | 21.57%  |
| 2     | 96        | 4.95%   |
| 3     | 5         | 0.26%   |
| 4     | 4         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 195       | 31.81%  |
| Graphics card            | 162       | 26.43%  |
| Chipcard                 | 83        | 13.54%  |
| Net/wireless             | 55        | 8.97%   |
| Camera                   | 29        | 4.73%   |
| Multimedia controller    | 28        | 4.57%   |
| Communication controller | 16        | 2.61%   |
| Unassigned class         | 15        | 2.45%   |
| Bluetooth                | 9         | 1.47%   |
| Network                  | 4         | 0.65%   |
| Net/ethernet             | 4         | 0.65%   |
| Card reader              | 3         | 0.49%   |
| Storage/nvme             | 2         | 0.33%   |
| Storage                  | 2         | 0.33%   |
| Modem                    | 2         | 0.33%   |
| Dvb card                 | 2         | 0.33%   |
| Wireless                 | 1         | 0.16%   |
| Sound                    | 1         | 0.16%   |

