Clear Linux - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Clear Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Clear_Linux/Desktop/README.md) and [notebooks](/Dist/Clear_Linux/Notebook/README.md).

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

Total: 1499

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [ffa58b22a6](https://linux-hardware.org/?probe=ffa58b22a6) | Dec 29, 2024 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [c76825324c](https://linux-hardware.org/?probe=c76825324c) | Dec 28, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2bc9b23a42](https://linux-hardware.org/?probe=2bc9b23a42) | Dec 21, 2024 |
| Dell          | Inspiron 3580               | Notebook    | [cd4f2164a0](https://linux-hardware.org/?probe=cd4f2164a0) | Dec 02, 2024 |
| HP            | 18E7                        | Desktop     | [2e2890fa90](https://linux-hardware.org/?probe=2e2890fa90) | Nov 25, 2024 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4ece0e89f1](https://linux-hardware.org/?probe=4ece0e89f1) | Nov 20, 2024 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [888308f02a](https://linux-hardware.org/?probe=888308f02a) | Nov 13, 2024 |
| HP            | 18E7                        | Desktop     | [bb9d771e55](https://linux-hardware.org/?probe=bb9d771e55) | Nov 11, 2024 |
| MECHREVO      | Kuangshi16Pro Series GM6... | Notebook    | [e0254a7e9a](https://linux-hardware.org/?probe=e0254a7e9a) | Nov 10, 2024 |
| Gigabyte      | B660 DS3H AX DDR4           | Desktop     | [980e65b389](https://linux-hardware.org/?probe=980e65b389) | Nov 09, 2024 |
| HUAWEI        | MDF-XX                      | Notebook    | [9f0d1d9bb2](https://linux-hardware.org/?probe=9f0d1d9bb2) | Nov 04, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [03f25d4aa0](https://linux-hardware.org/?probe=03f25d4aa0) | Oct 25, 2024 |
| ASUSTek       | GL503VM                     | Notebook    | [667f613a0f](https://linux-hardware.org/?probe=667f613a0f) | Oct 21, 2024 |
| ASUSTek       | GL503VM                     | Notebook    | [4b0399845f](https://linux-hardware.org/?probe=4b0399845f) | Oct 21, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [572c893f92](https://linux-hardware.org/?probe=572c893f92) | Oct 20, 2024 |
| ASUSTek       | H110-PLUS                   | Desktop     | [1ed40dc81e](https://linux-hardware.org/?probe=1ed40dc81e) | Oct 06, 2024 |
| HP            | ProLiant DL380e Gen8        | Server      | [735d113f73](https://linux-hardware.org/?probe=735d113f73) | Sep 20, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [b2095e6211](https://linux-hardware.org/?probe=b2095e6211) | Sep 16, 2024 |
| Samsung       | 940XGK                      | Notebook    | [1be7f39bff](https://linux-hardware.org/?probe=1be7f39bff) | Sep 15, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [9cf000f67c](https://linux-hardware.org/?probe=9cf000f67c) | Sep 12, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [8279710a58](https://linux-hardware.org/?probe=8279710a58) | Sep 09, 2024 |
| Gigabyte      | H87-HD3                     | Desktop     | [c080e185a8](https://linux-hardware.org/?probe=c080e185a8) | Sep 08, 2024 |
| Positivo      | C14CR21                     | Notebook    | [1ee6ac63c7](https://linux-hardware.org/?probe=1ee6ac63c7) | Aug 30, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [de5916af69](https://linux-hardware.org/?probe=de5916af69) | Aug 28, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [3c0cd2dbe3](https://linux-hardware.org/?probe=3c0cd2dbe3) | Aug 22, 2024 |
| Dell          | Latitude 5580               | Notebook    | [a1b30c87cb](https://linux-hardware.org/?probe=a1b30c87cb) | Aug 14, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [92819d0f8c](https://linux-hardware.org/?probe=92819d0f8c) | Aug 13, 2024 |
| ASUSTek       | H110-PLUS                   | Desktop     | [d96d59b833](https://linux-hardware.org/?probe=d96d59b833) | Aug 03, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [79c6d52e0b](https://linux-hardware.org/?probe=79c6d52e0b) | Jul 31, 2024 |
| HP            | 8462                        | Desktop     | [4369a9a9e3](https://linux-hardware.org/?probe=4369a9a9e3) | Jul 29, 2024 |
| ASUSTek       | H110-PLUS                   | Desktop     | [66abd24072](https://linux-hardware.org/?probe=66abd24072) | Jul 29, 2024 |
| Chuwi         | Hi10 X                      | Tablet      | [ba2c5ebeb6](https://linux-hardware.org/?probe=ba2c5ebeb6) | Jul 28, 2024 |
| Intel         | NUC8BEB J72692-307          | Mini pc     | [3d53b9ce1d](https://linux-hardware.org/?probe=3d53b9ce1d) | Jul 20, 2024 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [86cafd9087](https://linux-hardware.org/?probe=86cafd9087) | Jun 27, 2024 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [fa847c686c](https://linux-hardware.org/?probe=fa847c686c) | Jun 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [36f7e8a03a](https://linux-hardware.org/?probe=36f7e8a03a) | Jun 07, 2024 |
| Acer          | Aspire E5-571PG             | Notebook    | [500ff80ad3](https://linux-hardware.org/?probe=500ff80ad3) | May 25, 2024 |
| Dell          | Latitude 5424 Rugged        | Notebook    | [dde3595035](https://linux-hardware.org/?probe=dde3595035) | May 17, 2024 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [3a38ccbd81](https://linux-hardware.org/?probe=3a38ccbd81) | May 11, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [bcd9091312](https://linux-hardware.org/?probe=bcd9091312) | May 11, 2024 |
| Chuwi         | CoreBook X                  | Notebook    | [de2cd02e92](https://linux-hardware.org/?probe=de2cd02e92) | Apr 18, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [fc3d11e3f3](https://linux-hardware.org/?probe=fc3d11e3f3) | Apr 18, 2024 |
| ASUSTek       | Strix GL504GS_GL504GS       | Notebook    | [fafcb22109](https://linux-hardware.org/?probe=fafcb22109) | Apr 17, 2024 |
| HP            | Laptop 14s-dr2xxx           | Notebook    | [30ab271b58](https://linux-hardware.org/?probe=30ab271b58) | Apr 08, 2024 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [74f33723a8](https://linux-hardware.org/?probe=74f33723a8) | Mar 11, 2024 |
| LattePanda    | Sigma                       | Desktop     | [ae1ba16921](https://linux-hardware.org/?probe=ae1ba16921) | Mar 10, 2024 |
| Dell          | Latitude 7400               | Notebook    | [97c11ef92d](https://linux-hardware.org/?probe=97c11ef92d) | Feb 28, 2024 |
| ASRock        | Z97 Pro4                    | Desktop     | [9c48e758c6](https://linux-hardware.org/?probe=9c48e758c6) | Feb 26, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [969a1bdb7c](https://linux-hardware.org/?probe=969a1bdb7c) | Feb 23, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [5184bd82b1](https://linux-hardware.org/?probe=5184bd82b1) | Feb 23, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [c347074123](https://linux-hardware.org/?probe=c347074123) | Feb 20, 2024 |
| ASRock        | Z97 Pro4                    | Desktop     | [d6189a161e](https://linux-hardware.org/?probe=d6189a161e) | Feb 20, 2024 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [861a8f057e](https://linux-hardware.org/?probe=861a8f057e) | Feb 05, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [e2c0eadcb1](https://linux-hardware.org/?probe=e2c0eadcb1) | Feb 05, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [ecd2bc3e73](https://linux-hardware.org/?probe=ecd2bc3e73) | Feb 03, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [293e2aa334](https://linux-hardware.org/?probe=293e2aa334) | Feb 03, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [d01e00588d](https://linux-hardware.org/?probe=d01e00588d) | Feb 03, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [d6ddc23d9b](https://linux-hardware.org/?probe=d6ddc23d9b) | Jan 31, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [fc26b8ad18](https://linux-hardware.org/?probe=fc26b8ad18) | Jan 31, 2024 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [2e4fa19ae6](https://linux-hardware.org/?probe=2e4fa19ae6) | Jan 29, 2024 |
| Acer          | TravelMate P414-51          | Notebook    | [c21caad3b4](https://linux-hardware.org/?probe=c21caad3b4) | Jan 23, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [c72427a053](https://linux-hardware.org/?probe=c72427a053) | Jan 21, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [80001dbe10](https://linux-hardware.org/?probe=80001dbe10) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [13451bf305](https://linux-hardware.org/?probe=13451bf305) | Jan 15, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [0420a7ddaa](https://linux-hardware.org/?probe=0420a7ddaa) | Jan 09, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [2f34cc5377](https://linux-hardware.org/?probe=2f34cc5377) | Jan 06, 2024 |
| Acer          | Aspire A515-56G             | Notebook    | [084e91606c](https://linux-hardware.org/?probe=084e91606c) | Jan 04, 2024 |
| Acer          | Aspire A515-56G             | Notebook    | [e1554fcb98](https://linux-hardware.org/?probe=e1554fcb98) | Jan 04, 2024 |
| Samsung       | 930QED                      | Convertible | [c9d218a2c8](https://linux-hardware.org/?probe=c9d218a2c8) | Jan 02, 2024 |
| Google        | Gallop                      | Notebook    | [917756724c](https://linux-hardware.org/?probe=917756724c) | Jan 01, 2024 |
| Hampoo        | Cherry Trail CR             | Desktop     | [2c180fa555](https://linux-hardware.org/?probe=2c180fa555) | Dec 20, 2023 |
| Huanan        | X99-TF                      | Desktop     | [2bf94ff272](https://linux-hardware.org/?probe=2bf94ff272) | Dec 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e521354b60](https://linux-hardware.org/?probe=e521354b60) | Dec 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [76a6e4545f](https://linux-hardware.org/?probe=76a6e4545f) | Dec 11, 2023 |
| Dell          | XPS 9320                    | Notebook    | [91f9b06d7f](https://linux-hardware.org/?probe=91f9b06d7f) | Dec 10, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [88ed16eec1](https://linux-hardware.org/?probe=88ed16eec1) | Nov 26, 2023 |
| Dell          | Vostro 3401                 | Notebook    | [3496a45338](https://linux-hardware.org/?probe=3496a45338) | Nov 25, 2023 |
| Acer          | TravelMate P2510-G2-M       | Notebook    | [262eaee181](https://linux-hardware.org/?probe=262eaee181) | Nov 22, 2023 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [a6dbcbf7a9](https://linux-hardware.org/?probe=a6dbcbf7a9) | Nov 17, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [c864159547](https://linux-hardware.org/?probe=c864159547) | Nov 03, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [43a85c50bf](https://linux-hardware.org/?probe=43a85c50bf) | Nov 02, 2023 |
| Samsung       | 935QDB                      | Convertible | [a132043246](https://linux-hardware.org/?probe=a132043246) | Oct 25, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [88e833ab8a](https://linux-hardware.org/?probe=88e833ab8a) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [62ca050eaf](https://linux-hardware.org/?probe=62ca050eaf) | Oct 24, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ed92a60842](https://linux-hardware.org/?probe=ed92a60842) | Oct 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [48405d326c](https://linux-hardware.org/?probe=48405d326c) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [436e243db6](https://linux-hardware.org/?probe=436e243db6) | Oct 21, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [f8330df761](https://linux-hardware.org/?probe=f8330df761) | Oct 20, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [486e66cdee](https://linux-hardware.org/?probe=486e66cdee) | Oct 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d77237b330](https://linux-hardware.org/?probe=d77237b330) | Oct 18, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [b605b832db](https://linux-hardware.org/?probe=b605b832db) | Oct 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [02fda3f9f3](https://linux-hardware.org/?probe=02fda3f9f3) | Oct 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [8448bccd6f](https://linux-hardware.org/?probe=8448bccd6f) | Oct 14, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [7bbf6155e7](https://linux-hardware.org/?probe=7bbf6155e7) | Oct 14, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [aee02d5429](https://linux-hardware.org/?probe=aee02d5429) | Sep 22, 2023 |
| Dell          | XPS 9320                    | Notebook    | [1fe2e34799](https://linux-hardware.org/?probe=1fe2e34799) | Sep 22, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [c5fccb4455](https://linux-hardware.org/?probe=c5fccb4455) | Sep 15, 2023 |
| Google        | Terra                       | Notebook    | [c96e879351](https://linux-hardware.org/?probe=c96e879351) | Sep 15, 2023 |
| HP            | ProLiant DL380 G6           | Server      | [a3caa9967a](https://linux-hardware.org/?probe=a3caa9967a) | Sep 14, 2023 |
| Google        | Terra                       | Notebook    | [3f63d76318](https://linux-hardware.org/?probe=3f63d76318) | Sep 14, 2023 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [f3ca596dc5](https://linux-hardware.org/?probe=f3ca596dc5) | Sep 14, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [904a4a7d23](https://linux-hardware.org/?probe=904a4a7d23) | Sep 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [d178c2211b](https://linux-hardware.org/?probe=d178c2211b) | Sep 13, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [93a0ee494d](https://linux-hardware.org/?probe=93a0ee494d) | Sep 11, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [bacfcd3028](https://linux-hardware.org/?probe=bacfcd3028) | Sep 07, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [f735c5a6e7](https://linux-hardware.org/?probe=f735c5a6e7) | Sep 06, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [3a7f86cf53](https://linux-hardware.org/?probe=3a7f86cf53) | Sep 02, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [3176d728c4](https://linux-hardware.org/?probe=3176d728c4) | Aug 27, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e3bc104b50](https://linux-hardware.org/?probe=e3bc104b50) | Aug 25, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [e71571b95d](https://linux-hardware.org/?probe=e71571b95d) | Aug 24, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [58af8f5102](https://linux-hardware.org/?probe=58af8f5102) | Aug 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [42398338fe](https://linux-hardware.org/?probe=42398338fe) | Aug 18, 2023 |
| HP            | 843B                        | Desktop     | [b809c37499](https://linux-hardware.org/?probe=b809c37499) | Aug 13, 2023 |
| MSI           | MPG Z790I EDGE WIFI         | Desktop     | [a395d59ef5](https://linux-hardware.org/?probe=a395d59ef5) | Jul 23, 2023 |
| Fujitsu       | LIFEBOOK S938               | Notebook    | [8d2f776940](https://linux-hardware.org/?probe=8d2f776940) | Jul 08, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a8c3d57d88](https://linux-hardware.org/?probe=a8c3d57d88) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [6df0ae15e1](https://linux-hardware.org/?probe=6df0ae15e1) | Jul 01, 2023 |
| Intel Clie... | STK1AW32SC                  | Stick pc    | [0f27631293](https://linux-hardware.org/?probe=0f27631293) | Jun 26, 2023 |
| Intel Clie... | STK1AW32SC                  | Stick pc    | [21a187daab](https://linux-hardware.org/?probe=21a187daab) | Jun 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [a579703f97](https://linux-hardware.org/?probe=a579703f97) | Jun 09, 2023 |
| Lenovo        | IdeaPad Z570 1024CPU        | Notebook    | [eb1c70f7af](https://linux-hardware.org/?probe=eb1c70f7af) | May 28, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [a3456d6048](https://linux-hardware.org/?probe=a3456d6048) | May 26, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [7ccc4cd858](https://linux-hardware.org/?probe=7ccc4cd858) | May 19, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [3e80b3baf6](https://linux-hardware.org/?probe=3e80b3baf6) | May 19, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [9017bcff99](https://linux-hardware.org/?probe=9017bcff99) | May 17, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [162219b0fe](https://linux-hardware.org/?probe=162219b0fe) | May 14, 2023 |
| Lenovo        | IdeaPad Z570 1024CPU        | Notebook    | [18bcbf2f00](https://linux-hardware.org/?probe=18bcbf2f00) | May 06, 2023 |
| Lenovo        | IdeaPad Z570 1024CPU        | Notebook    | [8e8c638dd7](https://linux-hardware.org/?probe=8e8c638dd7) | May 06, 2023 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [5575cdf0c2](https://linux-hardware.org/?probe=5575cdf0c2) | May 02, 2023 |
| Lenovo        | IdeaPad Z570 1024CPU        | Notebook    | [0e948e2cf6](https://linux-hardware.org/?probe=0e948e2cf6) | May 01, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [d458ae07b2](https://linux-hardware.org/?probe=d458ae07b2) | Apr 17, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [7d73434389](https://linux-hardware.org/?probe=7d73434389) | Apr 16, 2023 |
| Medion        | S14409                      | Notebook    | [d031a8b813](https://linux-hardware.org/?probe=d031a8b813) | Apr 16, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [8d989af69a](https://linux-hardware.org/?probe=8d989af69a) | Apr 15, 2023 |
| HP            | 1589                        | Desktop     | [b5309b9a82](https://linux-hardware.org/?probe=b5309b9a82) | Apr 14, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d79c9f1cf1](https://linux-hardware.org/?probe=d79c9f1cf1) | Apr 12, 2023 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [deab2a5eac](https://linux-hardware.org/?probe=deab2a5eac) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bce7f8b531](https://linux-hardware.org/?probe=bce7f8b531) | Mar 27, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [afba39d63c](https://linux-hardware.org/?probe=afba39d63c) | Mar 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1ca9befb7a](https://linux-hardware.org/?probe=1ca9befb7a) | Mar 18, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [c87e2c7e16](https://linux-hardware.org/?probe=c87e2c7e16) | Mar 16, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [3edca09442](https://linux-hardware.org/?probe=3edca09442) | Mar 16, 2023 |
| HP            | 843B                        | Desktop     | [2e7bf7ff44](https://linux-hardware.org/?probe=2e7bf7ff44) | Mar 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [99095e84f5](https://linux-hardware.org/?probe=99095e84f5) | Mar 12, 2023 |
| MSI           | MPG Z490 GAMING CARBON W... | Desktop     | [a6c5296f86](https://linux-hardware.org/?probe=a6c5296f86) | Mar 12, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [612562b44d](https://linux-hardware.org/?probe=612562b44d) | Mar 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f06981aa62](https://linux-hardware.org/?probe=f06981aa62) | Mar 08, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b1697b4550](https://linux-hardware.org/?probe=b1697b4550) | Mar 05, 2023 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Convertible | [4fbc244180](https://linux-hardware.org/?probe=4fbc244180) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [4625dc0660](https://linux-hardware.org/?probe=4625dc0660) | Mar 04, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [fcea958b77](https://linux-hardware.org/?probe=fcea958b77) | Feb 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [e7edf0f7c3](https://linux-hardware.org/?probe=e7edf0f7c3) | Feb 23, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [ade0244936](https://linux-hardware.org/?probe=ade0244936) | Feb 21, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0BY0... | Notebook    | [56c81f1044](https://linux-hardware.org/?probe=56c81f1044) | Feb 20, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [7890bf1c68](https://linux-hardware.org/?probe=7890bf1c68) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [20c0b96948](https://linux-hardware.org/?probe=20c0b96948) | Feb 12, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [62ead89718](https://linux-hardware.org/?probe=62ead89718) | Feb 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5dbc5260b2](https://linux-hardware.org/?probe=5dbc5260b2) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [7c0c804a3e](https://linux-hardware.org/?probe=7c0c804a3e) | Jan 29, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [93020dd688](https://linux-hardware.org/?probe=93020dd688) | Jan 28, 2023 |
| HP            | 212A                        | Desktop     | [5b9c217d02](https://linux-hardware.org/?probe=5b9c217d02) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430s 2356GRG      | Notebook    | [cd81d567a2](https://linux-hardware.org/?probe=cd81d567a2) | Jan 24, 2023 |
| MSI           | TRX40 PRO 10G               | Desktop     | [492a6fb119](https://linux-hardware.org/?probe=492a6fb119) | Jan 14, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [52164aa403](https://linux-hardware.org/?probe=52164aa403) | Jan 10, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [527a92f562](https://linux-hardware.org/?probe=527a92f562) | Dec 31, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [414db30bff](https://linux-hardware.org/?probe=414db30bff) | Dec 30, 2022 |
| HP            | 8399                        | Desktop     | [8a4ef9ab88](https://linux-hardware.org/?probe=8a4ef9ab88) | Dec 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [5e4cb87810](https://linux-hardware.org/?probe=5e4cb87810) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5ba954d88a](https://linux-hardware.org/?probe=5ba954d88a) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [318b7c1400](https://linux-hardware.org/?probe=318b7c1400) | Dec 19, 2022 |
| Google        | Cyan                        | Notebook    | [fff3502929](https://linux-hardware.org/?probe=fff3502929) | Dec 19, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [915c2dd055](https://linux-hardware.org/?probe=915c2dd055) | Dec 17, 2022 |
| Google        | Eve                         | Convertible | [44d285c1f9](https://linux-hardware.org/?probe=44d285c1f9) | Dec 13, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| HP            | ProBook 4540s               | Notebook    | [98ed2d6cdf](https://linux-hardware.org/?probe=98ed2d6cdf) | Dec 10, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6b0e2d1aa9](https://linux-hardware.org/?probe=6b0e2d1aa9) | Dec 10, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [52fb3214d5](https://linux-hardware.org/?probe=52fb3214d5) | Dec 09, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [706e40ed5a](https://linux-hardware.org/?probe=706e40ed5a) | Dec 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [aff020417f](https://linux-hardware.org/?probe=aff020417f) | Dec 01, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5947cba303](https://linux-hardware.org/?probe=5947cba303) | Nov 28, 2022 |
| Unknown       | V00                         | Mini pc     | [54723a3c4c](https://linux-hardware.org/?probe=54723a3c4c) | Nov 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [694a3d79be](https://linux-hardware.org/?probe=694a3d79be) | Nov 26, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [c53295ce70](https://linux-hardware.org/?probe=c53295ce70) | Nov 25, 2022 |
| ASUSTek       | P8H61-I LX/RM/SI            | Desktop     | [61cfa154b0](https://linux-hardware.org/?probe=61cfa154b0) | Nov 24, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [2ed85718c2](https://linux-hardware.org/?probe=2ed85718c2) | Nov 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [ad63d86cb9](https://linux-hardware.org/?probe=ad63d86cb9) | Nov 23, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [be2b867450](https://linux-hardware.org/?probe=be2b867450) | Nov 20, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [adb0e2aa98](https://linux-hardware.org/?probe=adb0e2aa98) | Nov 19, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [4480153621](https://linux-hardware.org/?probe=4480153621) | Nov 18, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b1266ce009](https://linux-hardware.org/?probe=b1266ce009) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [8084d88d4b](https://linux-hardware.org/?probe=8084d88d4b) | Nov 17, 2022 |
| Dell          | Precision 5530              | Notebook    | [9737fe3732](https://linux-hardware.org/?probe=9737fe3732) | Nov 12, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c1103d767e](https://linux-hardware.org/?probe=c1103d767e) | Nov 12, 2022 |
| HP            | 3397                        | Desktop     | [27c0a5213d](https://linux-hardware.org/?probe=27c0a5213d) | Nov 11, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [4b0ce24e6e](https://linux-hardware.org/?probe=4b0ce24e6e) | Nov 11, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [2f18264021](https://linux-hardware.org/?probe=2f18264021) | Nov 11, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [86f71fb0e6](https://linux-hardware.org/?probe=86f71fb0e6) | Nov 10, 2022 |
| Lenovo        | ThinkPad P53 20QQS2CY00     | Notebook    | [98e9599ea3](https://linux-hardware.org/?probe=98e9599ea3) | Nov 08, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [9d1fda5ecb](https://linux-hardware.org/?probe=9d1fda5ecb) | Nov 06, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [768e2bbf53](https://linux-hardware.org/?probe=768e2bbf53) | Nov 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [28cc86118e](https://linux-hardware.org/?probe=28cc86118e) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [18db43ffed](https://linux-hardware.org/?probe=18db43ffed) | Oct 31, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [1fb51cc10c](https://linux-hardware.org/?probe=1fb51cc10c) | Oct 31, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2ae55c9228](https://linux-hardware.org/?probe=2ae55c9228) | Oct 27, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [34f98de888](https://linux-hardware.org/?probe=34f98de888) | Oct 27, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [b29a0df34f](https://linux-hardware.org/?probe=b29a0df34f) | Oct 27, 2022 |
| Dell          | Latitude 3120               | Notebook    | [2799c3fe8e](https://linux-hardware.org/?probe=2799c3fe8e) | Oct 24, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [a78f249f0e](https://linux-hardware.org/?probe=a78f249f0e) | Oct 23, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [87e23bcbe6](https://linux-hardware.org/?probe=87e23bcbe6) | Oct 19, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [543bbf49af](https://linux-hardware.org/?probe=543bbf49af) | Oct 19, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [f13dd4393d](https://linux-hardware.org/?probe=f13dd4393d) | Oct 19, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [ff225777df](https://linux-hardware.org/?probe=ff225777df) | Oct 18, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [0c9c2f85b4](https://linux-hardware.org/?probe=0c9c2f85b4) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [b966faf224](https://linux-hardware.org/?probe=b966faf224) | Oct 14, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [2105a7b1c9](https://linux-hardware.org/?probe=2105a7b1c9) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [28a985f0e9](https://linux-hardware.org/?probe=28a985f0e9) | Oct 06, 2022 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [908c7afaf3](https://linux-hardware.org/?probe=908c7afaf3) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [eaafe4ad36](https://linux-hardware.org/?probe=eaafe4ad36) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [b31ac1623d](https://linux-hardware.org/?probe=b31ac1623d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | Notebook    | [9eaff58099](https://linux-hardware.org/?probe=9eaff58099) | Oct 05, 2022 |
| Dell          | Latitude 5420               | Notebook    | [e4d629b41b](https://linux-hardware.org/?probe=e4d629b41b) | Oct 04, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [bc172de17b](https://linux-hardware.org/?probe=bc172de17b) | Oct 02, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5bdf95fbdc](https://linux-hardware.org/?probe=5bdf95fbdc) | Oct 02, 2022 |
| Notebook      | NL40_50GU                   | Notebook    | [da07f4c223](https://linux-hardware.org/?probe=da07f4c223) | Sep 23, 2022 |
| Mbenben       | Mai II                      | Notebook    | [2cfb10385b](https://linux-hardware.org/?probe=2cfb10385b) | Sep 22, 2022 |
| ASUSTek       | X455LAB                     | Notebook    | [4a71131e80](https://linux-hardware.org/?probe=4a71131e80) | Sep 19, 2022 |
| ASUSTek       | X455LAB                     | Notebook    | [f7c5412964](https://linux-hardware.org/?probe=f7c5412964) | Sep 19, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [3074b849bf](https://linux-hardware.org/?probe=3074b849bf) | Sep 19, 2022 |
| Dell          | Latitude 5420               | Notebook    | [2d9d6512bc](https://linux-hardware.org/?probe=2d9d6512bc) | Sep 19, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [5de472d6c0](https://linux-hardware.org/?probe=5de472d6c0) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [857c240dc4](https://linux-hardware.org/?probe=857c240dc4) | Sep 17, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [172a6c16be](https://linux-hardware.org/?probe=172a6c16be) | Sep 14, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [7ec64e9e08](https://linux-hardware.org/?probe=7ec64e9e08) | Sep 13, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [d6fed8866c](https://linux-hardware.org/?probe=d6fed8866c) | Sep 13, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [c719d7f544](https://linux-hardware.org/?probe=c719d7f544) | Sep 11, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [4a00a1ca0b](https://linux-hardware.org/?probe=4a00a1ca0b) | Sep 10, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [08aadcd875](https://linux-hardware.org/?probe=08aadcd875) | Sep 10, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1QQ0... | Notebook    | [242fae3988](https://linux-hardware.org/?probe=242fae3988) | Sep 08, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [0bbd51f049](https://linux-hardware.org/?probe=0bbd51f049) | Sep 04, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [5561c4d69e](https://linux-hardware.org/?probe=5561c4d69e) | Sep 04, 2022 |
| Lenovo        | ThinkPad X201 3680IJ9       | Notebook    | [a4fcabd03d](https://linux-hardware.org/?probe=a4fcabd03d) | Sep 04, 2022 |
| Google        | Auron_Paine                 | Notebook    | [19a461dd93](https://linux-hardware.org/?probe=19a461dd93) | Sep 04, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [934feeca3d](https://linux-hardware.org/?probe=934feeca3d) | Sep 04, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [fdc3c39ae8](https://linux-hardware.org/?probe=fdc3c39ae8) | Sep 03, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [6f2658db8b](https://linux-hardware.org/?probe=6f2658db8b) | Sep 03, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [8cd8165ff0](https://linux-hardware.org/?probe=8cd8165ff0) | Sep 02, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [4da7c712b4](https://linux-hardware.org/?probe=4da7c712b4) | Sep 01, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6503feb8b7](https://linux-hardware.org/?probe=6503feb8b7) | Aug 20, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [6605c5f8ec](https://linux-hardware.org/?probe=6605c5f8ec) | Aug 18, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [1dda2df118](https://linux-hardware.org/?probe=1dda2df118) | Aug 18, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [59e3f96082](https://linux-hardware.org/?probe=59e3f96082) | Aug 18, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [db33232b90](https://linux-hardware.org/?probe=db33232b90) | Aug 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [fd8393bd6d](https://linux-hardware.org/?probe=fd8393bd6d) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a083c7a306](https://linux-hardware.org/?probe=a083c7a306) | Aug 06, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [7711256117](https://linux-hardware.org/?probe=7711256117) | Aug 05, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c810dc35f9](https://linux-hardware.org/?probe=c810dc35f9) | Aug 05, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f013fa996e](https://linux-hardware.org/?probe=f013fa996e) | Aug 04, 2022 |
| Lenovo        | ThinkPad E585 20KV000YUS    | Notebook    | [ddb45bfaff](https://linux-hardware.org/?probe=ddb45bfaff) | Jul 31, 2022 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [2fe4fe7fe5](https://linux-hardware.org/?probe=2fe4fe7fe5) | Jul 30, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [c5f4ae1ac4](https://linux-hardware.org/?probe=c5f4ae1ac4) | Jul 26, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [76f5f39b78](https://linux-hardware.org/?probe=76f5f39b78) | Jul 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8bf5cae166](https://linux-hardware.org/?probe=8bf5cae166) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [e311d24fa1](https://linux-hardware.org/?probe=e311d24fa1) | Jul 22, 2022 |
| Huanan        | X99-TF                      | Desktop     | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| Dell          | Latitude E6320              | Notebook    | [e4104ce925](https://linux-hardware.org/?probe=e4104ce925) | Jul 15, 2022 |
| Dell          | Latitude E6320              | Notebook    | [8b0774a179](https://linux-hardware.org/?probe=8b0774a179) | Jul 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [2ee086df64](https://linux-hardware.org/?probe=2ee086df64) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [aae85dbe4b](https://linux-hardware.org/?probe=aae85dbe4b) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [628dd44ea9](https://linux-hardware.org/?probe=628dd44ea9) | Jul 15, 2022 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [a02c08c229](https://linux-hardware.org/?probe=a02c08c229) | Jul 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [1747257b56](https://linux-hardware.org/?probe=1747257b56) | Jul 10, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [f69a70c4b4](https://linux-hardware.org/?probe=f69a70c4b4) | Jul 08, 2022 |
| Google        | Cave                        | Notebook    | [fd843b1768](https://linux-hardware.org/?probe=fd843b1768) | Jul 07, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f852861149](https://linux-hardware.org/?probe=f852861149) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6b942bfd10](https://linux-hardware.org/?probe=6b942bfd10) | Jul 05, 2022 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [59417db2d7](https://linux-hardware.org/?probe=59417db2d7) | Jul 05, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [32463f298d](https://linux-hardware.org/?probe=32463f298d) | Jul 05, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [147320c75c](https://linux-hardware.org/?probe=147320c75c) | Jul 04, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [47ee319e1b](https://linux-hardware.org/?probe=47ee319e1b) | Jul 04, 2022 |
| Acer          | Aspire TC-1660 V:1.1        | Desktop     | [4b65cbc6e6](https://linux-hardware.org/?probe=4b65cbc6e6) | Jul 03, 2022 |
| HP            | Pavilion 15                 | Notebook    | [82bc7e7316](https://linux-hardware.org/?probe=82bc7e7316) | Jun 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [f9630aadbb](https://linux-hardware.org/?probe=f9630aadbb) | Jun 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c49e821c3c](https://linux-hardware.org/?probe=c49e821c3c) | Jun 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [929cd4988f](https://linux-hardware.org/?probe=929cd4988f) | Jun 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [cc5c87a20e](https://linux-hardware.org/?probe=cc5c87a20e) | Jun 24, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [465ffdd126](https://linux-hardware.org/?probe=465ffdd126) | Jun 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [a4027cc5e4](https://linux-hardware.org/?probe=a4027cc5e4) | Jun 20, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [cdaacd4b95](https://linux-hardware.org/?probe=cdaacd4b95) | Jun 18, 2022 |
| Huanan        | X99-TF                      | Desktop     | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [da44ae8ded](https://linux-hardware.org/?probe=da44ae8ded) | Jun 15, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [4e33fa1a1d](https://linux-hardware.org/?probe=4e33fa1a1d) | Jun 15, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [71f9801165](https://linux-hardware.org/?probe=71f9801165) | Jun 15, 2022 |
| Dell          | Latitude E6510              | Notebook    | [d0ec96cd37](https://linux-hardware.org/?probe=d0ec96cd37) | Jun 14, 2022 |
| MSI           | H510M PRO                   | Desktop     | [b75b035492](https://linux-hardware.org/?probe=b75b035492) | Jun 14, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [c8b26ae553](https://linux-hardware.org/?probe=c8b26ae553) | Jun 13, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [63e26e87be](https://linux-hardware.org/?probe=63e26e87be) | Jun 13, 2022 |
| HP            | 1850                        | Desktop     | [0048661597](https://linux-hardware.org/?probe=0048661597) | Jun 12, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [52c72a47d9](https://linux-hardware.org/?probe=52c72a47d9) | Jun 09, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [5d777eeb71](https://linux-hardware.org/?probe=5d777eeb71) | Jun 09, 2022 |
| Biostar       | H61MLV3                     | Desktop     | [dd47d4aac6](https://linux-hardware.org/?probe=dd47d4aac6) | Jun 08, 2022 |
| Biostar       | H61MLV3                     | Desktop     | [906bb764d6](https://linux-hardware.org/?probe=906bb764d6) | Jun 08, 2022 |
| Huanan        | X99-TF                      | Desktop     | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [58566ab4b6](https://linux-hardware.org/?probe=58566ab4b6) | May 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c908e08818](https://linux-hardware.org/?probe=c908e08818) | May 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [b8a514c650](https://linux-hardware.org/?probe=b8a514c650) | May 29, 2022 |
| Alienware     | 17 R4                       | Notebook    | [0a7c1705c9](https://linux-hardware.org/?probe=0a7c1705c9) | May 27, 2022 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [36ee0ea60c](https://linux-hardware.org/?probe=36ee0ea60c) | May 27, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [a6dafabf0c](https://linux-hardware.org/?probe=a6dafabf0c) | May 27, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [38875f631e](https://linux-hardware.org/?probe=38875f631e) | May 27, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [af7e6249f0](https://linux-hardware.org/?probe=af7e6249f0) | May 27, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [44ceac3592](https://linux-hardware.org/?probe=44ceac3592) | May 27, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [61fe0db491](https://linux-hardware.org/?probe=61fe0db491) | May 26, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [47f48c626a](https://linux-hardware.org/?probe=47f48c626a) | May 26, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9c2c8025ed](https://linux-hardware.org/?probe=9c2c8025ed) | May 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [4de838a88c](https://linux-hardware.org/?probe=4de838a88c) | May 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [26745bace2](https://linux-hardware.org/?probe=26745bace2) | May 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [4ba0a0ec3c](https://linux-hardware.org/?probe=4ba0a0ec3c) | May 24, 2022 |
| Dell          | Latitude 7480               | Notebook    | [33c94e6121](https://linux-hardware.org/?probe=33c94e6121) | May 24, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [5076d170e0](https://linux-hardware.org/?probe=5076d170e0) | May 24, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d0d6870830](https://linux-hardware.org/?probe=d0d6870830) | May 23, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [2cd1f7fd5e](https://linux-hardware.org/?probe=2cd1f7fd5e) | May 23, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [90d0bb5bc0](https://linux-hardware.org/?probe=90d0bb5bc0) | May 22, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [48047cdaf6](https://linux-hardware.org/?probe=48047cdaf6) | May 22, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [e856d4589a](https://linux-hardware.org/?probe=e856d4589a) | May 21, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [830532746e](https://linux-hardware.org/?probe=830532746e) | May 20, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [27289062cb](https://linux-hardware.org/?probe=27289062cb) | May 19, 2022 |
| Medion        | MS-7728                     | Desktop     | [72b22a927a](https://linux-hardware.org/?probe=72b22a927a) | May 19, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [73bd0df4ae](https://linux-hardware.org/?probe=73bd0df4ae) | May 19, 2022 |
| Google        | Celes                       | Notebook    | [ca6be0abba](https://linux-hardware.org/?probe=ca6be0abba) | May 19, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [23879a78d3](https://linux-hardware.org/?probe=23879a78d3) | May 18, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [dd9eac2f81](https://linux-hardware.org/?probe=dd9eac2f81) | May 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [fccf22ebe1](https://linux-hardware.org/?probe=fccf22ebe1) | May 14, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [5af3adc742](https://linux-hardware.org/?probe=5af3adc742) | May 13, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [8551aac5e5](https://linux-hardware.org/?probe=8551aac5e5) | May 12, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [58c936ec28](https://linux-hardware.org/?probe=58c936ec28) | May 11, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [ba9835cb43](https://linux-hardware.org/?probe=ba9835cb43) | May 10, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | Notebook    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Supermicro    | H8QG6                       | Server      | [d341c929e0](https://linux-hardware.org/?probe=d341c929e0) | May 08, 2022 |
| Google        | Lick                        | Notebook    | [60e52e55e1](https://linux-hardware.org/?probe=60e52e55e1) | May 06, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [d04d5e927d](https://linux-hardware.org/?probe=d04d5e927d) | May 05, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [fc3604980a](https://linux-hardware.org/?probe=fc3604980a) | May 04, 2022 |
| ASRock        | H370 Pro4                   | Desktop     | [ccf085e9dc](https://linux-hardware.org/?probe=ccf085e9dc) | May 02, 2022 |
| TODOS INDU... | Easytouch_2022_V1           | Notebook    | [efc26220c4](https://linux-hardware.org/?probe=efc26220c4) | May 01, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [31fdda39b1](https://linux-hardware.org/?probe=31fdda39b1) | May 01, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3782e39a43](https://linux-hardware.org/?probe=3782e39a43) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [b4d4e52220](https://linux-hardware.org/?probe=b4d4e52220) | Apr 30, 2022 |
| Google        | Lick                        | Notebook    | [33d1e6209a](https://linux-hardware.org/?probe=33d1e6209a) | Apr 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1fc7423fdf](https://linux-hardware.org/?probe=1fc7423fdf) | Apr 27, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [d7757bf097](https://linux-hardware.org/?probe=d7757bf097) | Apr 27, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [288bb26592](https://linux-hardware.org/?probe=288bb26592) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [1f95a73d57](https://linux-hardware.org/?probe=1f95a73d57) | Apr 26, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [f0aea29124](https://linux-hardware.org/?probe=f0aea29124) | Apr 25, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [fb612cbcd5](https://linux-hardware.org/?probe=fb612cbcd5) | Apr 24, 2022 |
| Gateway       | NE570                       | Notebook    | [1cb22c0c86](https://linux-hardware.org/?probe=1cb22c0c86) | Apr 23, 2022 |
| HP            | 158B                        | Desktop     | [af3f62d027](https://linux-hardware.org/?probe=af3f62d027) | Apr 22, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [d103edc70e](https://linux-hardware.org/?probe=d103edc70e) | Apr 21, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [e5d8c4e246](https://linux-hardware.org/?probe=e5d8c4e246) | Apr 21, 2022 |
| Gateway       | NE570                       | Notebook    | [d4b1bdce70](https://linux-hardware.org/?probe=d4b1bdce70) | Apr 17, 2022 |
| Framework     | Laptop                      | Notebook    | [25577a2915](https://linux-hardware.org/?probe=25577a2915) | Apr 16, 2022 |
| Dell          | Latitude 3550               | Notebook    | [03ed6ab7b4](https://linux-hardware.org/?probe=03ed6ab7b4) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [ae8fe4a156](https://linux-hardware.org/?probe=ae8fe4a156) | Apr 16, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [839159351b](https://linux-hardware.org/?probe=839159351b) | Apr 16, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [29a530e6bb](https://linux-hardware.org/?probe=29a530e6bb) | Apr 16, 2022 |
| Framework     | Laptop                      | Notebook    | [84da421304](https://linux-hardware.org/?probe=84da421304) | Apr 16, 2022 |
| MSI           | CX700                       | Notebook    | [b7715b0ff7](https://linux-hardware.org/?probe=b7715b0ff7) | Apr 15, 2022 |
| Gateway       | NE570                       | Notebook    | [3635e5c663](https://linux-hardware.org/?probe=3635e5c663) | Apr 14, 2022 |
| Gateway       | NE570                       | Notebook    | [068d4c39f2](https://linux-hardware.org/?probe=068d4c39f2) | Apr 13, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [9380c2aaf9](https://linux-hardware.org/?probe=9380c2aaf9) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [48e5060f20](https://linux-hardware.org/?probe=48e5060f20) | Apr 10, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [ff682e31dc](https://linux-hardware.org/?probe=ff682e31dc) | Apr 09, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [f29ab972e7](https://linux-hardware.org/?probe=f29ab972e7) | Apr 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [de86ebaf94](https://linux-hardware.org/?probe=de86ebaf94) | Apr 06, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [a19db5a006](https://linux-hardware.org/?probe=a19db5a006) | Apr 05, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45188a0370](https://linux-hardware.org/?probe=45188a0370) | Apr 04, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [4ac3657579](https://linux-hardware.org/?probe=4ac3657579) | Apr 04, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [1395229a99](https://linux-hardware.org/?probe=1395229a99) | Apr 04, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [2671214482](https://linux-hardware.org/?probe=2671214482) | Apr 01, 2022 |
| HP            | 843B                        | Desktop     | [9c9f43770f](https://linux-hardware.org/?probe=9c9f43770f) | Mar 30, 2022 |
| HP            | 843B                        | Desktop     | [84ae0f086f](https://linux-hardware.org/?probe=84ae0f086f) | Mar 30, 2022 |
| HP            | Pavilion g4                 | Notebook    | [5f8c09baeb](https://linux-hardware.org/?probe=5f8c09baeb) | Mar 28, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [baaaec9d38](https://linux-hardware.org/?probe=baaaec9d38) | Mar 27, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [6d9a59620b](https://linux-hardware.org/?probe=6d9a59620b) | Mar 26, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | Notebook    | [95526f5b3e](https://linux-hardware.org/?probe=95526f5b3e) | Mar 25, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [87a81b14f0](https://linux-hardware.org/?probe=87a81b14f0) | Mar 25, 2022 |
| Teclast       | F6                          | Notebook    | [d4e2f31492](https://linux-hardware.org/?probe=d4e2f31492) | Mar 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [76b97dcfe7](https://linux-hardware.org/?probe=76b97dcfe7) | Mar 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ec3089df82](https://linux-hardware.org/?probe=ec3089df82) | Mar 25, 2022 |
| Google        | Falco                       | Notebook    | [77727aa3fe](https://linux-hardware.org/?probe=77727aa3fe) | Mar 24, 2022 |
| Hampoo        | I1D6_C189A                  | Tablet      | [9deb58b002](https://linux-hardware.org/?probe=9deb58b002) | Mar 23, 2022 |
| Google        | Falco                       | Notebook    | [279dc118ab](https://linux-hardware.org/?probe=279dc118ab) | Mar 22, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [b171a344f7](https://linux-hardware.org/?probe=b171a344f7) | Mar 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [8b31578713](https://linux-hardware.org/?probe=8b31578713) | Mar 18, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [781207a46b](https://linux-hardware.org/?probe=781207a46b) | Mar 17, 2022 |
| TrekStor      | Primebook C13               | Convertible | [2c908202fc](https://linux-hardware.org/?probe=2c908202fc) | Mar 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [29ac5f13cd](https://linux-hardware.org/?probe=29ac5f13cd) | Mar 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [11bd4e97e6](https://linux-hardware.org/?probe=11bd4e97e6) | Mar 13, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [d82602f02f](https://linux-hardware.org/?probe=d82602f02f) | Mar 11, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [8a97b4f2d3](https://linux-hardware.org/?probe=8a97b4f2d3) | Mar 09, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [fbd59f7138](https://linux-hardware.org/?probe=fbd59f7138) | Mar 07, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c3a014ca22](https://linux-hardware.org/?probe=c3a014ca22) | Mar 07, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c6fa3e547d](https://linux-hardware.org/?probe=c6fa3e547d) | Mar 05, 2022 |
| Dell          | Latitude 7285               | Tablet      | [78f2672479](https://linux-hardware.org/?probe=78f2672479) | Mar 01, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [d4d9841cbe](https://linux-hardware.org/?probe=d4d9841cbe) | Feb 28, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [4980da013a](https://linux-hardware.org/?probe=4980da013a) | Feb 25, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [8dfdb07f98](https://linux-hardware.org/?probe=8dfdb07f98) | Feb 24, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [a8c8bdd208](https://linux-hardware.org/?probe=a8c8bdd208) | Feb 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [73c98934ee](https://linux-hardware.org/?probe=73c98934ee) | Feb 23, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1b5b236f76](https://linux-hardware.org/?probe=1b5b236f76) | Feb 21, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [15efc7df1a](https://linux-hardware.org/?probe=15efc7df1a) | Feb 18, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [4a66255bed](https://linux-hardware.org/?probe=4a66255bed) | Feb 17, 2022 |
| Dell          | Latitude 7285               | Tablet      | [f21545dd14](https://linux-hardware.org/?probe=f21545dd14) | Feb 16, 2022 |
| ASUSTek       | H81M-CS                     | Desktop     | [28b9a2b500](https://linux-hardware.org/?probe=28b9a2b500) | Feb 14, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [81f2a365be](https://linux-hardware.org/?probe=81f2a365be) | Feb 13, 2022 |
| ASUSTek       | H81M-CS                     | Desktop     | [4f647b985e](https://linux-hardware.org/?probe=4f647b985e) | Feb 12, 2022 |
| Dell          | 0K240Y A04                  | Desktop     | [4342c15fb0](https://linux-hardware.org/?probe=4342c15fb0) | Feb 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T430 2349L38       | Notebook    | [85d1c3705e](https://linux-hardware.org/?probe=85d1c3705e) | Feb 09, 2022 |
| ECS           | BSWI-DA                     | Desktop     | [2b3dda83e5](https://linux-hardware.org/?probe=2b3dda83e5) | Feb 04, 2022 |
| HP            | 1495                        | Desktop     | [b5cb1ae686](https://linux-hardware.org/?probe=b5cb1ae686) | Feb 03, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [087f6b0b86](https://linux-hardware.org/?probe=087f6b0b86) | Feb 02, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [ffe5569ab0](https://linux-hardware.org/?probe=ffe5569ab0) | Feb 01, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [a91c7ce0bd](https://linux-hardware.org/?probe=a91c7ce0bd) | Jan 26, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [c6c0f18149](https://linux-hardware.org/?probe=c6c0f18149) | Jan 26, 2022 |
| MSI           | GE60 2OC\2OE                | Notebook    | [dee5b3e5a3](https://linux-hardware.org/?probe=dee5b3e5a3) | Jan 25, 2022 |
| Itautec       | Infoway N8755               | Notebook    | [34a8012b59](https://linux-hardware.org/?probe=34a8012b59) | Jan 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [5906cdc7bb](https://linux-hardware.org/?probe=5906cdc7bb) | Jan 24, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [c86dafbe5c](https://linux-hardware.org/?probe=c86dafbe5c) | Jan 24, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [b6b0ace138](https://linux-hardware.org/?probe=b6b0ace138) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [047f9adb4a](https://linux-hardware.org/?probe=047f9adb4a) | Jan 15, 2022 |
| HP            | 1495                        | Desktop     | [f391be3ce3](https://linux-hardware.org/?probe=f391be3ce3) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a0574d0765](https://linux-hardware.org/?probe=a0574d0765) | Jan 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | Notebook    | [7e5c6d4e15](https://linux-hardware.org/?probe=7e5c6d4e15) | Jan 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c781a61663](https://linux-hardware.org/?probe=c781a61663) | Jan 11, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [bd78c03781](https://linux-hardware.org/?probe=bd78c03781) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3bf9ad038a](https://linux-hardware.org/?probe=3bf9ad038a) | Jan 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [cd230f0c61](https://linux-hardware.org/?probe=cd230f0c61) | Jan 08, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [0e1dd5f9da](https://linux-hardware.org/?probe=0e1dd5f9da) | Jan 08, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [e6e6da8cf0](https://linux-hardware.org/?probe=e6e6da8cf0) | Jan 07, 2022 |
| Google        | Auron_Paine                 | Notebook    | [0481d53f47](https://linux-hardware.org/?probe=0481d53f47) | Jan 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0e61f69494](https://linux-hardware.org/?probe=0e61f69494) | Jan 05, 2022 |
| Google        | Auron_Paine                 | Notebook    | [141027ba98](https://linux-hardware.org/?probe=141027ba98) | Jan 05, 2022 |
| Intel         | NUC5CPYB H61145-408         | Mini pc     | [0e14f8a417](https://linux-hardware.org/?probe=0e14f8a417) | Jan 05, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [4b12ee93be](https://linux-hardware.org/?probe=4b12ee93be) | Jan 02, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [e80c5b0522](https://linux-hardware.org/?probe=e80c5b0522) | Jan 01, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | Notebook    | [82cef16846](https://linux-hardware.org/?probe=82cef16846) | Dec 29, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7f8ea5d071](https://linux-hardware.org/?probe=7f8ea5d071) | Dec 26, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [f9b23903e3](https://linux-hardware.org/?probe=f9b23903e3) | Dec 25, 2021 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [a74c0d09dd](https://linux-hardware.org/?probe=a74c0d09dd) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [44b1bbbb9c](https://linux-hardware.org/?probe=44b1bbbb9c) | Dec 18, 2021 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [332c4bba00](https://linux-hardware.org/?probe=332c4bba00) | Dec 18, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [ce9a3f2c74](https://linux-hardware.org/?probe=ce9a3f2c74) | Dec 13, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [877a0414c3](https://linux-hardware.org/?probe=877a0414c3) | Dec 12, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [c4efae322a](https://linux-hardware.org/?probe=c4efae322a) | Dec 12, 2021 |
| HP            | 21D0                        | Desktop     | [50548c11b7](https://linux-hardware.org/?probe=50548c11b7) | Dec 04, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [b4bda60130](https://linux-hardware.org/?probe=b4bda60130) | Dec 02, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [d4f31ef495](https://linux-hardware.org/?probe=d4f31ef495) | Dec 01, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [6490a6beba](https://linux-hardware.org/?probe=6490a6beba) | Nov 29, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [36fa5a689f](https://linux-hardware.org/?probe=36fa5a689f) | Nov 28, 2021 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [f3e1cfcdab](https://linux-hardware.org/?probe=f3e1cfcdab) | Nov 26, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [aad237dc74](https://linux-hardware.org/?probe=aad237dc74) | Nov 25, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [2879c07a24](https://linux-hardware.org/?probe=2879c07a24) | Nov 23, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [9a09876c14](https://linux-hardware.org/?probe=9a09876c14) | Nov 22, 2021 |
| Intel         | NUC11TNBv7 K87766-403       | Mini pc     | [b23894b3e4](https://linux-hardware.org/?probe=b23894b3e4) | Nov 20, 2021 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [8c90375658](https://linux-hardware.org/?probe=8c90375658) | Nov 20, 2021 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [a385b829b0](https://linux-hardware.org/?probe=a385b829b0) | Nov 20, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [767039524f](https://linux-hardware.org/?probe=767039524f) | Nov 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [564ef15a99](https://linux-hardware.org/?probe=564ef15a99) | Nov 16, 2021 |
| HP            | 339A                        | Desktop     | [a30141ff62](https://linux-hardware.org/?probe=a30141ff62) | Nov 14, 2021 |
| HP            | 339A                        | Desktop     | [46b4ce405b](https://linux-hardware.org/?probe=46b4ce405b) | Nov 13, 2021 |
| Dell          | Inspiron 13-7378            | Notebook    | [e1384fb15b](https://linux-hardware.org/?probe=e1384fb15b) | Nov 12, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [401da402d8](https://linux-hardware.org/?probe=401da402d8) | Nov 12, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [7daf6ea0a5](https://linux-hardware.org/?probe=7daf6ea0a5) | Nov 12, 2021 |
| Maibenben     | E5100                       | Notebook    | [26a4ff554a](https://linux-hardware.org/?probe=26a4ff554a) | Nov 11, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [45992e5117](https://linux-hardware.org/?probe=45992e5117) | Nov 11, 2021 |
| Dell          | 0CRH6C A00                  | Desktop     | [0741aa1566](https://linux-hardware.org/?probe=0741aa1566) | Nov 10, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [3ba991c901](https://linux-hardware.org/?probe=3ba991c901) | Nov 10, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [640758abea](https://linux-hardware.org/?probe=640758abea) | Nov 09, 2021 |
| Google        | Auron_Paine                 | Notebook    | [1227213ee7](https://linux-hardware.org/?probe=1227213ee7) | Nov 07, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [ecae91dfa5](https://linux-hardware.org/?probe=ecae91dfa5) | Nov 07, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [cc4231496b](https://linux-hardware.org/?probe=cc4231496b) | Nov 07, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [7cdc55e110](https://linux-hardware.org/?probe=7cdc55e110) | Nov 06, 2021 |
| Pegatron      | SKLD4-P1                    | Desktop     | [c4b1d5c274](https://linux-hardware.org/?probe=c4b1d5c274) | Nov 01, 2021 |
| Pegatron      | SKLD4-P1                    | Desktop     | [715a0f960e](https://linux-hardware.org/?probe=715a0f960e) | Nov 01, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [f92fa1f111](https://linux-hardware.org/?probe=f92fa1f111) | Oct 31, 2021 |
| Dell          | Latitude 7370               | Notebook    | [6bf3c3796e](https://linux-hardware.org/?probe=6bf3c3796e) | Oct 30, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [0812a6b105](https://linux-hardware.org/?probe=0812a6b105) | Oct 29, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [0e2d73ad29](https://linux-hardware.org/?probe=0e2d73ad29) | Oct 29, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [1f0c766b1c](https://linux-hardware.org/?probe=1f0c766b1c) | Oct 27, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [51c82ff556](https://linux-hardware.org/?probe=51c82ff556) | Oct 24, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [1587d2dbaf](https://linux-hardware.org/?probe=1587d2dbaf) | Oct 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f55ca527be](https://linux-hardware.org/?probe=f55ca527be) | Oct 21, 2021 |
| Dell          | 0DF42J A00                  | Desktop     | [61ad2cb211](https://linux-hardware.org/?probe=61ad2cb211) | Oct 17, 2021 |
| Dell          | 0DF42J A00                  | Desktop     | [16a04162fc](https://linux-hardware.org/?probe=16a04162fc) | Oct 17, 2021 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [ec77ed1da7](https://linux-hardware.org/?probe=ec77ed1da7) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [89840aac65](https://linux-hardware.org/?probe=89840aac65) | Oct 13, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [fcc9eab970](https://linux-hardware.org/?probe=fcc9eab970) | Oct 12, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| Dell          | Latitude E5470              | Notebook    | [08d4c126fa](https://linux-hardware.org/?probe=08d4c126fa) | Oct 11, 2021 |
| Shuttle       | FH67H                       | Desktop     | [fcf20902e3](https://linux-hardware.org/?probe=fcf20902e3) | Oct 10, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7b579629bb](https://linux-hardware.org/?probe=7b579629bb) | Oct 09, 2021 |
| MSI           | Modern 14 B10MW             | Notebook    | [3f23aa5dc4](https://linux-hardware.org/?probe=3f23aa5dc4) | Oct 07, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [62bd532ea6](https://linux-hardware.org/?probe=62bd532ea6) | Oct 07, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [ee15b6dab0](https://linux-hardware.org/?probe=ee15b6dab0) | Oct 07, 2021 |
| MSI           | Modern 14 B10MW             | Notebook    | [cef5dd6d30](https://linux-hardware.org/?probe=cef5dd6d30) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [77a6cb9eba](https://linux-hardware.org/?probe=77a6cb9eba) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [99c08de77b](https://linux-hardware.org/?probe=99c08de77b) | Oct 07, 2021 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [64a01bd96e](https://linux-hardware.org/?probe=64a01bd96e) | Oct 06, 2021 |
| ASRock        | H97 Anniversary             | Desktop     | [a73dde5e98](https://linux-hardware.org/?probe=a73dde5e98) | Oct 05, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [39257b61d6](https://linux-hardware.org/?probe=39257b61d6) | Oct 05, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [b9fef09cfa](https://linux-hardware.org/?probe=b9fef09cfa) | Oct 05, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [09f20340ed](https://linux-hardware.org/?probe=09f20340ed) | Oct 05, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [90dbdbed7b](https://linux-hardware.org/?probe=90dbdbed7b) | Oct 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [34ce7d14dc](https://linux-hardware.org/?probe=34ce7d14dc) | Oct 04, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [8fa08d58ef](https://linux-hardware.org/?probe=8fa08d58ef) | Oct 03, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [6b4706ee1a](https://linux-hardware.org/?probe=6b4706ee1a) | Oct 03, 2021 |
| HP            | 843B                        | Desktop     | [66ea3388b1](https://linux-hardware.org/?probe=66ea3388b1) | Oct 01, 2021 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [9a089b5eb3](https://linux-hardware.org/?probe=9a089b5eb3) | Sep 30, 2021 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | Desktop     | [2f27c4c6f0](https://linux-hardware.org/?probe=2f27c4c6f0) | Sep 29, 2021 |
| HP            | 843B                        | Desktop     | [3f53b96972](https://linux-hardware.org/?probe=3f53b96972) | Sep 28, 2021 |
| HP            | 843B                        | Desktop     | [8de340a761](https://linux-hardware.org/?probe=8de340a761) | Sep 28, 2021 |
| Dell          | Latitude 5480               | Notebook    | [bd21f22540](https://linux-hardware.org/?probe=bd21f22540) | Sep 28, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [5c64bfd9d4](https://linux-hardware.org/?probe=5c64bfd9d4) | Sep 25, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [f7722f86bc](https://linux-hardware.org/?probe=f7722f86bc) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [a08d8ecd94](https://linux-hardware.org/?probe=a08d8ecd94) | Sep 21, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [3af02e9c48](https://linux-hardware.org/?probe=3af02e9c48) | Sep 19, 2021 |
| Hampoo        | Cherry Trail CR             | Desktop     | [a059116962](https://linux-hardware.org/?probe=a059116962) | Sep 18, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [790a43aecb](https://linux-hardware.org/?probe=790a43aecb) | Sep 16, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [f5e45f9ef5](https://linux-hardware.org/?probe=f5e45f9ef5) | Sep 16, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [73d4452fc3](https://linux-hardware.org/?probe=73d4452fc3) | Sep 15, 2021 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [6ddab6806e](https://linux-hardware.org/?probe=6ddab6806e) | Sep 14, 2021 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [72352cd62b](https://linux-hardware.org/?probe=72352cd62b) | Sep 14, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [05f3bfe1fe](https://linux-hardware.org/?probe=05f3bfe1fe) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [a48ec730b7](https://linux-hardware.org/?probe=a48ec730b7) | Sep 13, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [356430d4ae](https://linux-hardware.org/?probe=356430d4ae) | Sep 11, 2021 |
| HP            | 1589                        | Desktop     | [0a77f3540b](https://linux-hardware.org/?probe=0a77f3540b) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f8b30bd0cf](https://linux-hardware.org/?probe=f8b30bd0cf) | Sep 04, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [dfe0340402](https://linux-hardware.org/?probe=dfe0340402) | Sep 04, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3758bf5026](https://linux-hardware.org/?probe=3758bf5026) | Sep 01, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [575b7af6a0](https://linux-hardware.org/?probe=575b7af6a0) | Aug 30, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [9505862c5e](https://linux-hardware.org/?probe=9505862c5e) | Aug 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [596f8a121f](https://linux-hardware.org/?probe=596f8a121f) | Aug 27, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [246709cb9b](https://linux-hardware.org/?probe=246709cb9b) | Aug 27, 2021 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [afd5f8b9b1](https://linux-hardware.org/?probe=afd5f8b9b1) | Aug 27, 2021 |
| ASRock        | AB350 Gaming K4             | Desktop     | [f25ecb1f4d](https://linux-hardware.org/?probe=f25ecb1f4d) | Aug 25, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [6d4b2d1904](https://linux-hardware.org/?probe=6d4b2d1904) | Aug 19, 2021 |
| Unknown       | Intel X79                   | Desktop     | [1c9353265e](https://linux-hardware.org/?probe=1c9353265e) | Aug 17, 2021 |
| Dell          | Precision 7550              | Notebook    | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [698b26501e](https://linux-hardware.org/?probe=698b26501e) | Aug 15, 2021 |
| Acer          | Aspire F5-573               | Notebook    | [8a33fea383](https://linux-hardware.org/?probe=8a33fea383) | Aug 14, 2021 |
| Acer          | Aspire F5-573               | Notebook    | [cada2d25da](https://linux-hardware.org/?probe=cada2d25da) | Aug 14, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [bf398306f4](https://linux-hardware.org/?probe=bf398306f4) | Aug 12, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [e879ad305a](https://linux-hardware.org/?probe=e879ad305a) | Aug 12, 2021 |
| ASRock        | H470M-STX                   | Desktop     | [73dd46e48a](https://linux-hardware.org/?probe=73dd46e48a) | Aug 11, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [0e5b41af2a](https://linux-hardware.org/?probe=0e5b41af2a) | Aug 10, 2021 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | Notebook    | [e81b578a28](https://linux-hardware.org/?probe=e81b578a28) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| HP            | 8767 A                      | Desktop     | [5944b600c5](https://linux-hardware.org/?probe=5944b600c5) | Aug 09, 2021 |
| HP            | 8767 A                      | Desktop     | [39a268c1b4](https://linux-hardware.org/?probe=39a268c1b4) | Aug 09, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [dbcb2750e9](https://linux-hardware.org/?probe=dbcb2750e9) | Aug 09, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [b5ab852570](https://linux-hardware.org/?probe=b5ab852570) | Aug 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [18469458d9](https://linux-hardware.org/?probe=18469458d9) | Aug 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [157f15a6de](https://linux-hardware.org/?probe=157f15a6de) | Aug 08, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [605fe34818](https://linux-hardware.org/?probe=605fe34818) | Aug 06, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [236eefa6a3](https://linux-hardware.org/?probe=236eefa6a3) | Aug 06, 2021 |
| HP            | 8767 A                      | Desktop     | [e3b0eb537d](https://linux-hardware.org/?probe=e3b0eb537d) | Aug 04, 2021 |
| HP            | 8767 A                      | Desktop     | [7b9311366d](https://linux-hardware.org/?probe=7b9311366d) | Aug 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1bcb4e3744](https://linux-hardware.org/?probe=1bcb4e3744) | Aug 03, 2021 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [a98e8d0283](https://linux-hardware.org/?probe=a98e8d0283) | Aug 02, 2021 |
| Gigabyte      | P57                         | Notebook    | [7a9fa5b7d1](https://linux-hardware.org/?probe=7a9fa5b7d1) | Jul 31, 2021 |
| HP            | ENVY Laptop 17m-cg0xxx      | Notebook    | [c4b65848bf](https://linux-hardware.org/?probe=c4b65848bf) | Jul 28, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [bcdd6f776b](https://linux-hardware.org/?probe=bcdd6f776b) | Jul 28, 2021 |
| HP            | ENVY Laptop 17m-cg0xxx      | Notebook    | [e999c3f146](https://linux-hardware.org/?probe=e999c3f146) | Jul 28, 2021 |
| Lenovo        | ThinkPad X220 4291CF7       | Notebook    | [259e7f5b9c](https://linux-hardware.org/?probe=259e7f5b9c) | Jul 24, 2021 |
| ASUSTek       | TP550LA                     | Notebook    | [2a5843180d](https://linux-hardware.org/?probe=2a5843180d) | Jul 23, 2021 |
| ASRock        | H470M-STX                   | Desktop     | [2b06fc5589](https://linux-hardware.org/?probe=2b06fc5589) | Jul 22, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [092ad1b8e7](https://linux-hardware.org/?probe=092ad1b8e7) | Jul 22, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [490d082b82](https://linux-hardware.org/?probe=490d082b82) | Jul 21, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [9f6c5866ae](https://linux-hardware.org/?probe=9f6c5866ae) | Jul 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [74f54d66b2](https://linux-hardware.org/?probe=74f54d66b2) | Jul 20, 2021 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [dda8f08beb](https://linux-hardware.org/?probe=dda8f08beb) | Jul 19, 2021 |
| MSI           | TRX40 PRO 10G               | Desktop     | [a06646b4da](https://linux-hardware.org/?probe=a06646b4da) | Jul 19, 2021 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [f7dd2b2f25](https://linux-hardware.org/?probe=f7dd2b2f25) | Jul 19, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b07887acc1](https://linux-hardware.org/?probe=b07887acc1) | Jul 18, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [eda44f6d7c](https://linux-hardware.org/?probe=eda44f6d7c) | Jul 18, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [f608273dd1](https://linux-hardware.org/?probe=f608273dd1) | Jul 16, 2021 |
| ASRock        | H470M-STX                   | Desktop     | [929192be0f](https://linux-hardware.org/?probe=929192be0f) | Jul 14, 2021 |
| HP            | 1497                        | Desktop     | [12f471ea0d](https://linux-hardware.org/?probe=12f471ea0d) | Jul 12, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [426d32adfa](https://linux-hardware.org/?probe=426d32adfa) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [e6d4cd2e90](https://linux-hardware.org/?probe=e6d4cd2e90) | Jul 10, 2021 |
| Lenovo        | ThinkServer TS140           | Desktop     | [ce4504e2f0](https://linux-hardware.org/?probe=ce4504e2f0) | Jul 09, 2021 |
| Lenovo        | ThinkServer TS140           | Desktop     | [927c1f1b83](https://linux-hardware.org/?probe=927c1f1b83) | Jul 09, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [5a442d1b82](https://linux-hardware.org/?probe=5a442d1b82) | Jul 09, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1b90aa16a1](https://linux-hardware.org/?probe=1b90aa16a1) | Jul 09, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [97bc068489](https://linux-hardware.org/?probe=97bc068489) | Jul 09, 2021 |
| MSI           | GS43VR 7RE                  | Notebook    | [93e4c242e8](https://linux-hardware.org/?probe=93e4c242e8) | Jul 09, 2021 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [f42d2049ab](https://linux-hardware.org/?probe=f42d2049ab) | Jul 09, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [40450f88e3](https://linux-hardware.org/?probe=40450f88e3) | Jul 07, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [7eb7b4a001](https://linux-hardware.org/?probe=7eb7b4a001) | Jul 07, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | Latitude 3330               | Notebook    | [f6a5d02ff8](https://linux-hardware.org/?probe=f6a5d02ff8) | Jul 02, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [e185c99124](https://linux-hardware.org/?probe=e185c99124) | Jul 02, 2021 |
| Dell          | Inspiron 7773               | Notebook    | [0f2d634052](https://linux-hardware.org/?probe=0f2d634052) | Jul 01, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [4c4e08cbed](https://linux-hardware.org/?probe=4c4e08cbed) | Jul 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [2279bef5dc](https://linux-hardware.org/?probe=2279bef5dc) | Jun 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [6bf8a2ed63](https://linux-hardware.org/?probe=6bf8a2ed63) | Jun 27, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [fd2d0c3aea](https://linux-hardware.org/?probe=fd2d0c3aea) | Jun 25, 2021 |
| HP            | ZBook 17 G3                 | Notebook    | [bb110af1eb](https://linux-hardware.org/?probe=bb110af1eb) | Jun 24, 2021 |
| HP            | ZBook 17 G3                 | Notebook    | [e118524a10](https://linux-hardware.org/?probe=e118524a10) | Jun 24, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [83bdc57e22](https://linux-hardware.org/?probe=83bdc57e22) | Jun 24, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [913c59fc58](https://linux-hardware.org/?probe=913c59fc58) | Jun 21, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [617842a492](https://linux-hardware.org/?probe=617842a492) | Jun 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [489dc53e4d](https://linux-hardware.org/?probe=489dc53e4d) | Jun 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [077a1849dd](https://linux-hardware.org/?probe=077a1849dd) | Jun 20, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [e414cae554](https://linux-hardware.org/?probe=e414cae554) | Jun 18, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [70c81260fe](https://linux-hardware.org/?probe=70c81260fe) | Jun 18, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [90f62d9ea2](https://linux-hardware.org/?probe=90f62d9ea2) | Jun 18, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [6ea7ce0821](https://linux-hardware.org/?probe=6ea7ce0821) | Jun 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [2cc70c86d4](https://linux-hardware.org/?probe=2cc70c86d4) | Jun 17, 2021 |
| EVOO          | EVC156-1                    | Notebook    | [a1d5d4829c](https://linux-hardware.org/?probe=a1d5d4829c) | Jun 15, 2021 |
| EVOO          | EVC156-1                    | Notebook    | [3823b50f55](https://linux-hardware.org/?probe=3823b50f55) | Jun 15, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [f2d7281431](https://linux-hardware.org/?probe=f2d7281431) | Jun 13, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [e21a83e794](https://linux-hardware.org/?probe=e21a83e794) | Jun 12, 2021 |
| Google        | Coral                       | Notebook    | [f6cf3ed923](https://linux-hardware.org/?probe=f6cf3ed923) | Jun 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5d0ad3d400](https://linux-hardware.org/?probe=5d0ad3d400) | Jun 08, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [c4cbc7b811](https://linux-hardware.org/?probe=c4cbc7b811) | Jun 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [fbfc225ce7](https://linux-hardware.org/?probe=fbfc225ce7) | Jun 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [6bad6316a0](https://linux-hardware.org/?probe=6bad6316a0) | Jun 07, 2021 |
| MOTILE        | M141                        | Notebook    | [533abc5ae4](https://linux-hardware.org/?probe=533abc5ae4) | Jun 06, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [fc5e5fb4f1](https://linux-hardware.org/?probe=fc5e5fb4f1) | Jun 05, 2021 |
| Dell          | Latitude 3330               | Notebook    | [0374f02ff3](https://linux-hardware.org/?probe=0374f02ff3) | Jun 03, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [b8ca5e61ae](https://linux-hardware.org/?probe=b8ca5e61ae) | Jun 03, 2021 |
| MSI           | Z590 PRO WIFI               | Desktop     | [35b29f391f](https://linux-hardware.org/?probe=35b29f391f) | Jun 01, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [d5f17bf23f](https://linux-hardware.org/?probe=d5f17bf23f) | Jun 01, 2021 |
| ASUSTek       | TUF Gaming B460-PRO         | Desktop     | [93390ed697](https://linux-hardware.org/?probe=93390ed697) | May 29, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [db4f728d1e](https://linux-hardware.org/?probe=db4f728d1e) | May 29, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [47d3f247b0](https://linux-hardware.org/?probe=47d3f247b0) | May 29, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [8477c386b6](https://linux-hardware.org/?probe=8477c386b6) | May 29, 2021 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [bbe9417568](https://linux-hardware.org/?probe=bbe9417568) | May 28, 2021 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [f750a7b519](https://linux-hardware.org/?probe=f750a7b519) | May 28, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [57a08ffceb](https://linux-hardware.org/?probe=57a08ffceb) | May 28, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [435091e995](https://linux-hardware.org/?probe=435091e995) | May 24, 2021 |
| ASUSTek       | X550LB                      | Notebook    | [fb64646c9b](https://linux-hardware.org/?probe=fb64646c9b) | May 24, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [8a9dc6ab53](https://linux-hardware.org/?probe=8a9dc6ab53) | May 24, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [ec7f85c26e](https://linux-hardware.org/?probe=ec7f85c26e) | May 22, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [616f23126b](https://linux-hardware.org/?probe=616f23126b) | May 22, 2021 |
| Acer          | TMP453-MG                   | Notebook    | [07291bacfe](https://linux-hardware.org/?probe=07291bacfe) | May 22, 2021 |
| Dell          | Latitude 3330               | Notebook    | [363f4f7708](https://linux-hardware.org/?probe=363f4f7708) | May 20, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [12903a99bf](https://linux-hardware.org/?probe=12903a99bf) | May 20, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [8748a193b6](https://linux-hardware.org/?probe=8748a193b6) | May 19, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [34c12e6041](https://linux-hardware.org/?probe=34c12e6041) | May 18, 2021 |
| Acer          | Aspire 7750                 | Notebook    | [ecf8d0fa55](https://linux-hardware.org/?probe=ecf8d0fa55) | May 18, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [6673a828e8](https://linux-hardware.org/?probe=6673a828e8) | May 18, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [3db3d9cb4a](https://linux-hardware.org/?probe=3db3d9cb4a) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d91a5890c9](https://linux-hardware.org/?probe=d91a5890c9) | May 18, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5343885c32](https://linux-hardware.org/?probe=5343885c32) | May 17, 2021 |
| Samsung       | 760XBE                      | Notebook    | [641aa732da](https://linux-hardware.org/?probe=641aa732da) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | Desktop     | [887f18105e](https://linux-hardware.org/?probe=887f18105e) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | Desktop     | [644431aa47](https://linux-hardware.org/?probe=644431aa47) | May 17, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d12a52a705](https://linux-hardware.org/?probe=d12a52a705) | May 14, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [2fd333bc52](https://linux-hardware.org/?probe=2fd333bc52) | May 14, 2021 |
| Samsung       | 760XBE                      | Notebook    | [8065c7647a](https://linux-hardware.org/?probe=8065c7647a) | May 14, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [a100d4cd8a](https://linux-hardware.org/?probe=a100d4cd8a) | May 12, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e57ab59850](https://linux-hardware.org/?probe=e57ab59850) | May 12, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [36d2d6ef64](https://linux-hardware.org/?probe=36d2d6ef64) | May 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [b7dc673e5c](https://linux-hardware.org/?probe=b7dc673e5c) | May 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [9936062c88](https://linux-hardware.org/?probe=9936062c88) | May 07, 2021 |
| AZW           | AP35                        | Desktop     | [ac530e40ad](https://linux-hardware.org/?probe=ac530e40ad) | May 05, 2021 |
| Lenovo        | ThinkPad 10 2nd 20E4S0UD... | Tablet      | [14574d255e](https://linux-hardware.org/?probe=14574d255e) | May 04, 2021 |
| Biostar       | B360MHD PRO2                | Desktop     | [88839213ee](https://linux-hardware.org/?probe=88839213ee) | May 03, 2021 |
| ASUSTek       | Q304UAK                     | Convertible | [7ad86811c5](https://linux-hardware.org/?probe=7ad86811c5) | May 03, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [23d951aa64](https://linux-hardware.org/?probe=23d951aa64) | May 02, 2021 |
| AZW           | AP35                        | Desktop     | [867223f2cf](https://linux-hardware.org/?probe=867223f2cf) | May 02, 2021 |
| AZW           | AP35                        | Desktop     | [45487d6ab8](https://linux-hardware.org/?probe=45487d6ab8) | May 02, 2021 |
| Intel         | S1200SP H57534-212          | Server      | [98c12554cb](https://linux-hardware.org/?probe=98c12554cb) | May 02, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bba0c4ade9](https://linux-hardware.org/?probe=bba0c4ade9) | May 01, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [806898fe25](https://linux-hardware.org/?probe=806898fe25) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [aa9bfbf347](https://linux-hardware.org/?probe=aa9bfbf347) | Apr 29, 2021 |
| Acer          | Aspire ES1-111M             | Notebook    | [298d859193](https://linux-hardware.org/?probe=298d859193) | Apr 27, 2021 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [5c8af3a6f6](https://linux-hardware.org/?probe=5c8af3a6f6) | Apr 26, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a0753ae0f8](https://linux-hardware.org/?probe=a0753ae0f8) | Apr 26, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [6d786229f3](https://linux-hardware.org/?probe=6d786229f3) | Apr 21, 2021 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [d659fa1ad2](https://linux-hardware.org/?probe=d659fa1ad2) | Apr 21, 2021 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [285fc011a7](https://linux-hardware.org/?probe=285fc011a7) | Apr 18, 2021 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [24cda07874](https://linux-hardware.org/?probe=24cda07874) | Apr 18, 2021 |
| Dell          | Latitude 5310               | Notebook    | [c308a5a20b](https://linux-hardware.org/?probe=c308a5a20b) | Apr 17, 2021 |
| Intel         | B75                         | Desktop     | [b87d332f6c](https://linux-hardware.org/?probe=b87d332f6c) | Apr 17, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a16e9aea15](https://linux-hardware.org/?probe=a16e9aea15) | Apr 17, 2021 |
| Dell          | Latitude 5310               | Notebook    | [2eab1c1ad2](https://linux-hardware.org/?probe=2eab1c1ad2) | Apr 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [e6cc5fbf7f](https://linux-hardware.org/?probe=e6cc5fbf7f) | Apr 15, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [a7b1f80885](https://linux-hardware.org/?probe=a7b1f80885) | Apr 15, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [e8e1b223c6](https://linux-hardware.org/?probe=e8e1b223c6) | Apr 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [4849762adf](https://linux-hardware.org/?probe=4849762adf) | Apr 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [270515effb](https://linux-hardware.org/?probe=270515effb) | Apr 13, 2021 |
| ASUSTek       | X99-E WS                    | Desktop     | [4e03caf1b2](https://linux-hardware.org/?probe=4e03caf1b2) | Apr 13, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [b4fb702e4a](https://linux-hardware.org/?probe=b4fb702e4a) | Apr 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [5ff30ea7db](https://linux-hardware.org/?probe=5ff30ea7db) | Apr 11, 2021 |
| Dell          | Latitude 7280               | Notebook    | [1c4da429ac](https://linux-hardware.org/?probe=1c4da429ac) | Apr 09, 2021 |
| Dell          | Latitude E7450              | Notebook    | [8d1df1806c](https://linux-hardware.org/?probe=8d1df1806c) | Apr 08, 2021 |
| Dell          | Latitude E7450              | Notebook    | [24492fbd03](https://linux-hardware.org/?probe=24492fbd03) | Apr 07, 2021 |
| HP            | Notebook                    | Notebook    | [e8e5c7f100](https://linux-hardware.org/?probe=e8e5c7f100) | Apr 04, 2021 |
| AZW           | AP35                        | Desktop     | [d9275d56b3](https://linux-hardware.org/?probe=d9275d56b3) | Apr 02, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [7ffd62b3fa](https://linux-hardware.org/?probe=7ffd62b3fa) | Mar 31, 2021 |
| Lenovo        | ThinkPad T430 2347AY1       | Notebook    | [74bcb6eabd](https://linux-hardware.org/?probe=74bcb6eabd) | Mar 29, 2021 |
| Lenovo        | ThinkPad T430 2347AY1       | Notebook    | [453cb24e69](https://linux-hardware.org/?probe=453cb24e69) | Mar 29, 2021 |
| Intel         | NUC8i5INB K29935-402        | Mini pc     | [985aa77681](https://linux-hardware.org/?probe=985aa77681) | Mar 28, 2021 |
| Intel         | NUC8i5INB K29935-402        | Mini pc     | [39245df30b](https://linux-hardware.org/?probe=39245df30b) | Mar 27, 2021 |
| HP            | 18E4                        | Desktop     | [d97f86a6f8](https://linux-hardware.org/?probe=d97f86a6f8) | Mar 26, 2021 |
| Samsung       | SF311/SF411/SF511           | Notebook    | [fb1261d331](https://linux-hardware.org/?probe=fb1261d331) | Mar 25, 2021 |
| Notebook      | W65_W67RN,RC1,RCY           | Notebook    | [c3d75ecf4f](https://linux-hardware.org/?probe=c3d75ecf4f) | Mar 25, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [ac590318bb](https://linux-hardware.org/?probe=ac590318bb) | Mar 22, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f8c5a69d8e](https://linux-hardware.org/?probe=f8c5a69d8e) | Mar 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [f99039c20b](https://linux-hardware.org/?probe=f99039c20b) | Mar 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [3c469f8c33](https://linux-hardware.org/?probe=3c469f8c33) | Mar 20, 2021 |
| Mediacom      | Unknown                     | Notebook    | [5dbde592d4](https://linux-hardware.org/?probe=5dbde592d4) | Mar 18, 2021 |
| ASUSTek       | P55VA                       | Notebook    | [b4b0177e41](https://linux-hardware.org/?probe=b4b0177e41) | Mar 18, 2021 |
| ASUSTek       | P55VA                       | Notebook    | [b06371c249](https://linux-hardware.org/?probe=b06371c249) | Mar 18, 2021 |
| Dell          | Latitude E6420              | Notebook    | [b006880df4](https://linux-hardware.org/?probe=b006880df4) | Mar 17, 2021 |
| GMK           | NucBox                      | Desktop     | [d9c312187f](https://linux-hardware.org/?probe=d9c312187f) | Mar 12, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [e3774fdabc](https://linux-hardware.org/?probe=e3774fdabc) | Mar 09, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [06bec9c32d](https://linux-hardware.org/?probe=06bec9c32d) | Mar 09, 2021 |
| Dell          | Latitude E6420              | Notebook    | [027c467458](https://linux-hardware.org/?probe=027c467458) | Mar 09, 2021 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [df35c7e959](https://linux-hardware.org/?probe=df35c7e959) | Mar 09, 2021 |
| HP            | Notebook                    | Notebook    | [2a28d46c73](https://linux-hardware.org/?probe=2a28d46c73) | Mar 09, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| Intel         | B75                         | Desktop     | [6a917fae14](https://linux-hardware.org/?probe=6a917fae14) | Mar 08, 2021 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [21eb2bd6e0](https://linux-hardware.org/?probe=21eb2bd6e0) | Mar 07, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6093659817](https://linux-hardware.org/?probe=6093659817) | Mar 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9161109236](https://linux-hardware.org/?probe=9161109236) | Mar 06, 2021 |
| MAXSUN        | TA300 Series                | Desktop     | [efbd8e2910](https://linux-hardware.org/?probe=efbd8e2910) | Mar 06, 2021 |
| HP            | ZBook 17                    | Notebook    | [065ff8443f](https://linux-hardware.org/?probe=065ff8443f) | Mar 06, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [aff55f2cad](https://linux-hardware.org/?probe=aff55f2cad) | Mar 05, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [0fda599193](https://linux-hardware.org/?probe=0fda599193) | Mar 05, 2021 |
| HP            | 2AF7                        | Desktop     | [32795fb797](https://linux-hardware.org/?probe=32795fb797) | Mar 04, 2021 |
| Intel         | B75                         | Desktop     | [55e99d4728](https://linux-hardware.org/?probe=55e99d4728) | Mar 01, 2021 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [008868f177](https://linux-hardware.org/?probe=008868f177) | Feb 28, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [cd9d36e77b](https://linux-hardware.org/?probe=cd9d36e77b) | Feb 28, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [07963851fe](https://linux-hardware.org/?probe=07963851fe) | Feb 26, 2021 |
| Lenovo        | ThinkPad T410 2537VQ4       | Notebook    | [576fa34b0c](https://linux-hardware.org/?probe=576fa34b0c) | Feb 25, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [229409a8dc](https://linux-hardware.org/?probe=229409a8dc) | Feb 25, 2021 |
| Dell          | XPS 12 9250                 | Tablet      | [336e949796](https://linux-hardware.org/?probe=336e949796) | Feb 24, 2021 |
| Acer          | Aspire V5-572P              | Notebook    | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [b6c7d98eb2](https://linux-hardware.org/?probe=b6c7d98eb2) | Feb 23, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [4fd5f831b6](https://linux-hardware.org/?probe=4fd5f831b6) | Feb 22, 2021 |
| Gigabyte      | Z490 AORUS XTREME           | Desktop     | [78d71ec4a3](https://linux-hardware.org/?probe=78d71ec4a3) | Feb 22, 2021 |
| Gigabyte      | Z490 AORUS XTREME           | Desktop     | [cfc160c199](https://linux-hardware.org/?probe=cfc160c199) | Feb 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [93e1220042](https://linux-hardware.org/?probe=93e1220042) | Feb 22, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [78ec6d58ba](https://linux-hardware.org/?probe=78ec6d58ba) | Feb 22, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [7d749b3ecc](https://linux-hardware.org/?probe=7d749b3ecc) | Feb 21, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [9b1c3d7ac7](https://linux-hardware.org/?probe=9b1c3d7ac7) | Feb 21, 2021 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [ea79d1d8e0](https://linux-hardware.org/?probe=ea79d1d8e0) | Feb 21, 2021 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [79b6fc3c82](https://linux-hardware.org/?probe=79b6fc3c82) | Feb 19, 2021 |
| iEi           | B202 V1.0                   | Desktop     | [3dce687709](https://linux-hardware.org/?probe=3dce687709) | Feb 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [0730e68b60](https://linux-hardware.org/?probe=0730e68b60) | Feb 13, 2021 |
| Lenovo        | ZHAOYANG E49L 20178         | Notebook    | [bf121d7dcf](https://linux-hardware.org/?probe=bf121d7dcf) | Feb 12, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [9db992e10a](https://linux-hardware.org/?probe=9db992e10a) | Feb 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [5c52adac31](https://linux-hardware.org/?probe=5c52adac31) | Feb 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [fb9143648d](https://linux-hardware.org/?probe=fb9143648d) | Feb 09, 2021 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [ca7a345241](https://linux-hardware.org/?probe=ca7a345241) | Feb 08, 2021 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [db90964fa8](https://linux-hardware.org/?probe=db90964fa8) | Feb 07, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [414df2922d](https://linux-hardware.org/?probe=414df2922d) | Feb 07, 2021 |
| HP            | ENVY Notebook               | Notebook    | [c951e2abbd](https://linux-hardware.org/?probe=c951e2abbd) | Feb 07, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [21dd1bcda6](https://linux-hardware.org/?probe=21dd1bcda6) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2a1e54967b](https://linux-hardware.org/?probe=2a1e54967b) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [656d39b38c](https://linux-hardware.org/?probe=656d39b38c) | Feb 05, 2021 |
| Supermicro    | X10DRD-iNT                  | Server      | [21124e85cc](https://linux-hardware.org/?probe=21124e85cc) | Feb 05, 2021 |
| MSI           | B360 GAMING PLUS            | Desktop     | [f409735b4a](https://linux-hardware.org/?probe=f409735b4a) | Feb 01, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a775a17be3](https://linux-hardware.org/?probe=a775a17be3) | Feb 01, 2021 |
| Acer          | Predator G9-791             | Notebook    | [e498f5aa1d](https://linux-hardware.org/?probe=e498f5aa1d) | Jan 30, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [928c36893b](https://linux-hardware.org/?probe=928c36893b) | Jan 29, 2021 |
| Sony          | SVF14N25CXB                 | Notebook    | [1db1e6aec9](https://linux-hardware.org/?probe=1db1e6aec9) | Jan 28, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [5e7f5ea64a](https://linux-hardware.org/?probe=5e7f5ea64a) | Jan 28, 2021 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [81aa504e98](https://linux-hardware.org/?probe=81aa504e98) | Jan 28, 2021 |
| MOTILE        | M141                        | Notebook    | [f26f420164](https://linux-hardware.org/?probe=f26f420164) | Jan 28, 2021 |
| MOTILE        | M141                        | Notebook    | [2931763d11](https://linux-hardware.org/?probe=2931763d11) | Jan 28, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [a85ceac13e](https://linux-hardware.org/?probe=a85ceac13e) | Jan 26, 2021 |
| AMI           | Intel                       | Notebook    | [c290895be0](https://linux-hardware.org/?probe=c290895be0) | Jan 23, 2021 |
| Dell          | Latitude E6510              | Notebook    | [bc65564608](https://linux-hardware.org/?probe=bc65564608) | Jan 22, 2021 |
| Dell          | Latitude E6510              | Notebook    | [19035e3a57](https://linux-hardware.org/?probe=19035e3a57) | Jan 22, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [06fb5d662a](https://linux-hardware.org/?probe=06fb5d662a) | Jan 21, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [8d455bbc9b](https://linux-hardware.org/?probe=8d455bbc9b) | Jan 20, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [a298dd061d](https://linux-hardware.org/?probe=a298dd061d) | Jan 16, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [e289a86560](https://linux-hardware.org/?probe=e289a86560) | Jan 16, 2021 |
| Acer          | Spin SP111-34N              | Convertible | [5012e25bd9](https://linux-hardware.org/?probe=5012e25bd9) | Jan 12, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [041ad86a38](https://linux-hardware.org/?probe=041ad86a38) | Jan 12, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [ae008b3ccf](https://linux-hardware.org/?probe=ae008b3ccf) | Jan 11, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ee3769c94b](https://linux-hardware.org/?probe=ee3769c94b) | Jan 11, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [1099ad6dc9](https://linux-hardware.org/?probe=1099ad6dc9) | Jan 10, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [cd5fa09ba3](https://linux-hardware.org/?probe=cd5fa09ba3) | Jan 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [9f873d681e](https://linux-hardware.org/?probe=9f873d681e) | Jan 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [b7f5733608](https://linux-hardware.org/?probe=b7f5733608) | Jan 06, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4cf58c8a8c](https://linux-hardware.org/?probe=4cf58c8a8c) | Jan 02, 2021 |
| Dell          | Latitude E7240              | Notebook    | [17308a75c0](https://linux-hardware.org/?probe=17308a75c0) | Dec 27, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [5b174411b3](https://linux-hardware.org/?probe=5b174411b3) | Dec 26, 2020 |
| Microsoft     | Surface 3                   | Tablet      | [186a31d5a9](https://linux-hardware.org/?probe=186a31d5a9) | Dec 25, 2020 |
| MSI           | A320M-A PRO                 | Desktop     | [0edf382cee](https://linux-hardware.org/?probe=0edf382cee) | Dec 25, 2020 |
| MSI           | A320M-A PRO                 | Desktop     | [550ec69d3e](https://linux-hardware.org/?probe=550ec69d3e) | Dec 25, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [f1ae9f4de0](https://linux-hardware.org/?probe=f1ae9f4de0) | Dec 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0c7cdd9f71](https://linux-hardware.org/?probe=0c7cdd9f71) | Dec 23, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [656256db83](https://linux-hardware.org/?probe=656256db83) | Dec 22, 2020 |
| Gigabyte      | H310M H                     | Desktop     | [dfa5c13a96](https://linux-hardware.org/?probe=dfa5c13a96) | Dec 22, 2020 |
| HP            | 8459                        | Desktop     | [b5eb47ab31](https://linux-hardware.org/?probe=b5eb47ab31) | Dec 19, 2020 |
| Samsung       | 530XBB                      | Notebook    | [7b63094c3e](https://linux-hardware.org/?probe=7b63094c3e) | Dec 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [84e8731eff](https://linux-hardware.org/?probe=84e8731eff) | Dec 17, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1842fb451a](https://linux-hardware.org/?probe=1842fb451a) | Dec 15, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [dd14b01c46](https://linux-hardware.org/?probe=dd14b01c46) | Dec 13, 2020 |
| Unknown       | Unknown                     | Notebook    | [df193070a4](https://linux-hardware.org/?probe=df193070a4) | Dec 13, 2020 |
| Unknown       | Unknown                     | Notebook    | [7b57f91f5d](https://linux-hardware.org/?probe=7b57f91f5d) | Dec 13, 2020 |
| Unknown       | Unknown                     | Notebook    | [ef997b1269](https://linux-hardware.org/?probe=ef997b1269) | Dec 12, 2020 |
| Unknown       | Unknown                     | Notebook    | [a49b1a585c](https://linux-hardware.org/?probe=a49b1a585c) | Dec 12, 2020 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [653c485c8d](https://linux-hardware.org/?probe=653c485c8d) | Dec 08, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c381251f06](https://linux-hardware.org/?probe=c381251f06) | Dec 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [13f3852d03](https://linux-hardware.org/?probe=13f3852d03) | Dec 07, 2020 |
| ASRockRack    | EPC621D8A                   | Server      | [e8d1fe0309](https://linux-hardware.org/?probe=e8d1fe0309) | Dec 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [d1d2da5f71](https://linux-hardware.org/?probe=d1d2da5f71) | Dec 03, 2020 |
| HP            | 8459                        | Desktop     | [3755e58561](https://linux-hardware.org/?probe=3755e58561) | Dec 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [8dc7798fa5](https://linux-hardware.org/?probe=8dc7798fa5) | Dec 02, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [246bca0206](https://linux-hardware.org/?probe=246bca0206) | Dec 02, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [e33b92bbf1](https://linux-hardware.org/?probe=e33b92bbf1) | Dec 01, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [dfd9578421](https://linux-hardware.org/?probe=dfd9578421) | Dec 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [733c9bf866](https://linux-hardware.org/?probe=733c9bf866) | Dec 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [a0855e797f](https://linux-hardware.org/?probe=a0855e797f) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [4a9f777280](https://linux-hardware.org/?probe=4a9f777280) | Nov 30, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e6a375087e](https://linux-hardware.org/?probe=e6a375087e) | Nov 28, 2020 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [af0867c0cd](https://linux-hardware.org/?probe=af0867c0cd) | Nov 28, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [91806f966b](https://linux-hardware.org/?probe=91806f966b) | Nov 28, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [410ff74e69](https://linux-hardware.org/?probe=410ff74e69) | Nov 28, 2020 |
| Avell High... | A62 LIV                     | Notebook    | [765753e831](https://linux-hardware.org/?probe=765753e831) | Nov 26, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [e9cff0432f](https://linux-hardware.org/?probe=e9cff0432f) | Nov 24, 2020 |
| Chuwi         | GemiBook                    | Notebook    | [4b86f47f1e](https://linux-hardware.org/?probe=4b86f47f1e) | Nov 24, 2020 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [10d20f60df](https://linux-hardware.org/?probe=10d20f60df) | Nov 21, 2020 |
| Unknown       | CMGB                        | Mini pc     | [66a02f462f](https://linux-hardware.org/?probe=66a02f462f) | Nov 19, 2020 |
| Dell          | 0XDN97 A01                  | Server      | [91ca885cf4](https://linux-hardware.org/?probe=91ca885cf4) | Nov 16, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [66a2004080](https://linux-hardware.org/?probe=66a2004080) | Nov 12, 2020 |
| Unknown       | Unknown                     | Desktop     | [65fba277e7](https://linux-hardware.org/?probe=65fba277e7) | Nov 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [2a8118e258](https://linux-hardware.org/?probe=2a8118e258) | Nov 11, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [8a9747401a](https://linux-hardware.org/?probe=8a9747401a) | Nov 07, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [6b3b488150](https://linux-hardware.org/?probe=6b3b488150) | Nov 05, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [ab463224ae](https://linux-hardware.org/?probe=ab463224ae) | Nov 02, 2020 |
| iEi           | B202 V1.0                   | Desktop     | [ad705b0098](https://linux-hardware.org/?probe=ad705b0098) | Oct 29, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [f08f791eaf](https://linux-hardware.org/?probe=f08f791eaf) | Oct 28, 2020 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [511ec72263](https://linux-hardware.org/?probe=511ec72263) | Oct 27, 2020 |
| Lenovo        | B50-70 20384                | Notebook    | [cca8e03499](https://linux-hardware.org/?probe=cca8e03499) | Oct 24, 2020 |
| Panasonic     | CF-C2CKFZFCM                | Notebook    | [a6a2539a17](https://linux-hardware.org/?probe=a6a2539a17) | Oct 23, 2020 |
| ASUSTek       | B85M-K                      | Desktop     | [593f27d247](https://linux-hardware.org/?probe=593f27d247) | Oct 19, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d1194ef869](https://linux-hardware.org/?probe=d1194ef869) | Oct 18, 2020 |
| HP            | 250 G3                      | Notebook    | [100536aea2](https://linux-hardware.org/?probe=100536aea2) | Oct 17, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [6f659f9071](https://linux-hardware.org/?probe=6f659f9071) | Oct 17, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [94f16e9c34](https://linux-hardware.org/?probe=94f16e9c34) | Oct 16, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [c495aa4352](https://linux-hardware.org/?probe=c495aa4352) | Oct 16, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [6c2688ebfc](https://linux-hardware.org/?probe=6c2688ebfc) | Oct 16, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [5d60295214](https://linux-hardware.org/?probe=5d60295214) | Oct 15, 2020 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [bb0de25ace](https://linux-hardware.org/?probe=bb0de25ace) | Oct 15, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4b18f0db05](https://linux-hardware.org/?probe=4b18f0db05) | Oct 14, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [45a21ef843](https://linux-hardware.org/?probe=45a21ef843) | Oct 14, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [40a7a6d4ae](https://linux-hardware.org/?probe=40a7a6d4ae) | Oct 13, 2020 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [2b044d627b](https://linux-hardware.org/?probe=2b044d627b) | Oct 13, 2020 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [204e4aff9e](https://linux-hardware.org/?probe=204e4aff9e) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eed7ced527](https://linux-hardware.org/?probe=eed7ced527) | Oct 11, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9c37b1dfff](https://linux-hardware.org/?probe=9c37b1dfff) | Oct 11, 2020 |
| Panasonic     | CF-19ADUAEDM                | Notebook    | [67c288d5cc](https://linux-hardware.org/?probe=67c288d5cc) | Oct 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [968e3c668b](https://linux-hardware.org/?probe=968e3c668b) | Oct 08, 2020 |
| Panasonic     | CF-19ADUAEDM                | Notebook    | [a730dd736c](https://linux-hardware.org/?probe=a730dd736c) | Oct 07, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [f4c1b393b4](https://linux-hardware.org/?probe=f4c1b393b4) | Oct 05, 2020 |
| Panasonic     | CF-19ADUAEDM                | Notebook    | [6312d92efd](https://linux-hardware.org/?probe=6312d92efd) | Oct 05, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [e03efe3ba7](https://linux-hardware.org/?probe=e03efe3ba7) | Oct 05, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8d84313282](https://linux-hardware.org/?probe=8d84313282) | Oct 04, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [57e753215c](https://linux-hardware.org/?probe=57e753215c) | Oct 04, 2020 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [13353e2037](https://linux-hardware.org/?probe=13353e2037) | Oct 02, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7f79b48532](https://linux-hardware.org/?probe=7f79b48532) | Sep 30, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [1b0a93d73d](https://linux-hardware.org/?probe=1b0a93d73d) | Sep 29, 2020 |
| Lenovo        | ThinkPad E580 20KS002BCD    | Notebook    | [e89a66365d](https://linux-hardware.org/?probe=e89a66365d) | Sep 29, 2020 |
| Lenovo        | B50-70 20384                | Notebook    | [b2dfec8760](https://linux-hardware.org/?probe=b2dfec8760) | Sep 29, 2020 |
| Teclast       | X4                          | Tablet      | [1adea48d3e](https://linux-hardware.org/?probe=1adea48d3e) | Sep 28, 2020 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [462b8c10a5](https://linux-hardware.org/?probe=462b8c10a5) | Sep 27, 2020 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [70099a5fed](https://linux-hardware.org/?probe=70099a5fed) | Sep 27, 2020 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [8a2c7d0a65](https://linux-hardware.org/?probe=8a2c7d0a65) | Sep 25, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [cf1b29d15f](https://linux-hardware.org/?probe=cf1b29d15f) | Sep 24, 2020 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [b0f3a8c5f0](https://linux-hardware.org/?probe=b0f3a8c5f0) | Sep 24, 2020 |
| HP            | 250 G3                      | Notebook    | [c0207d3878](https://linux-hardware.org/?probe=c0207d3878) | Sep 24, 2020 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [5e54f25f85](https://linux-hardware.org/?probe=5e54f25f85) | Sep 24, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [77bafd89ba](https://linux-hardware.org/?probe=77bafd89ba) | Sep 21, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8352a0ac0e](https://linux-hardware.org/?probe=8352a0ac0e) | Sep 20, 2020 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [00c43e6a62](https://linux-hardware.org/?probe=00c43e6a62) | Sep 20, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [5152450400](https://linux-hardware.org/?probe=5152450400) | Sep 19, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [ece1d236b5](https://linux-hardware.org/?probe=ece1d236b5) | Sep 18, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [0b12ffde57](https://linux-hardware.org/?probe=0b12ffde57) | Sep 17, 2020 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [23c1513c53](https://linux-hardware.org/?probe=23c1513c53) | Sep 15, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [78aebc9965](https://linux-hardware.org/?probe=78aebc9965) | Sep 14, 2020 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [54e7b188f7](https://linux-hardware.org/?probe=54e7b188f7) | Sep 13, 2020 |
| Dell          | XPS 13 9343                 | Notebook    | [7414554e2d](https://linux-hardware.org/?probe=7414554e2d) | Sep 10, 2020 |
| MASSCOM VI... | L133                        | Notebook    | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| Dell          | Latitude E7240              | Notebook    | [4834754ce2](https://linux-hardware.org/?probe=4834754ce2) | Sep 09, 2020 |
| HP            | 82F2 A01                    | Desktop     | [f01ac2045a](https://linux-hardware.org/?probe=f01ac2045a) | Sep 05, 2020 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [bd721e65ce](https://linux-hardware.org/?probe=bd721e65ce) | Sep 05, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [783ffb159a](https://linux-hardware.org/?probe=783ffb159a) | Sep 02, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [a00607ac5f](https://linux-hardware.org/?probe=a00607ac5f) | Sep 01, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [e76eecbdaa](https://linux-hardware.org/?probe=e76eecbdaa) | Sep 01, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [988ca31973](https://linux-hardware.org/?probe=988ca31973) | Aug 31, 2020 |
| PC Special... | Fusion IV                   | Notebook    | [55da1618ab](https://linux-hardware.org/?probe=55da1618ab) | Aug 30, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4cd583b4b7](https://linux-hardware.org/?probe=4cd583b4b7) | Aug 30, 2020 |
| Acer          | Aspire TC-885G V:1.1        | Desktop     | [4053fd88a8](https://linux-hardware.org/?probe=4053fd88a8) | Aug 29, 2020 |
| Acer          | Aspire 7750G                | Notebook    | [91041cbcfb](https://linux-hardware.org/?probe=91041cbcfb) | Aug 28, 2020 |
| Acer          | Aspire 7750G                | Notebook    | [072119fece](https://linux-hardware.org/?probe=072119fece) | Aug 28, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [44e4d217af](https://linux-hardware.org/?probe=44e4d217af) | Aug 28, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [af37124d62](https://linux-hardware.org/?probe=af37124d62) | Aug 28, 2020 |
| ASRock        | TRX40 Taichi                | Desktop     | [dae871210e](https://linux-hardware.org/?probe=dae871210e) | Aug 23, 2020 |
| ASRock        | TRX40 Taichi                | Desktop     | [d5e4a3484b](https://linux-hardware.org/?probe=d5e4a3484b) | Aug 23, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [97fdcce42e](https://linux-hardware.org/?probe=97fdcce42e) | Aug 22, 2020 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f880ed8f66](https://linux-hardware.org/?probe=f880ed8f66) | Aug 20, 2020 |
| Positivo      | C500                        | Notebook    | [71530651bb](https://linux-hardware.org/?probe=71530651bb) | Aug 18, 2020 |
| ASRock        | H410M-HDV/M.2               | Desktop     | [8c6f947041](https://linux-hardware.org/?probe=8c6f947041) | Aug 16, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [db484283e2](https://linux-hardware.org/?probe=db484283e2) | Aug 12, 2020 |
| HP            | 802E                        | Desktop     | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | Laptop 15q-bu1xx            | Notebook    | [bc222c5b5c](https://linux-hardware.org/?probe=bc222c5b5c) | Aug 10, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [92e76957f9](https://linux-hardware.org/?probe=92e76957f9) | Aug 10, 2020 |
| HP            | 802E                        | Desktop     | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | Desktop     | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [3e4a555186](https://linux-hardware.org/?probe=3e4a555186) | Aug 10, 2020 |
| HP            | 8459                        | Desktop     | [c0c5068e12](https://linux-hardware.org/?probe=c0c5068e12) | Aug 08, 2020 |
| ASRock        | 970A-G                      | Desktop     | [9fcf5d6433](https://linux-hardware.org/?probe=9fcf5d6433) | Aug 08, 2020 |
| Sony          | VPCF236FM                   | Notebook    | [44a563d6db](https://linux-hardware.org/?probe=44a563d6db) | Aug 06, 2020 |
| Lenovo        | ThinkPad Helix 37024V8      | Notebook    | [12ef944776](https://linux-hardware.org/?probe=12ef944776) | Aug 05, 2020 |
| Lenovo        | ThinkPad Helix 37024V8      | Notebook    | [8e8e86364e](https://linux-hardware.org/?probe=8e8e86364e) | Aug 05, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [b90097a987](https://linux-hardware.org/?probe=b90097a987) | Aug 03, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | Notebook    | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [eba5d19e5f](https://linux-hardware.org/?probe=eba5d19e5f) | Aug 01, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| Dell          | 0773VG A01                  | Desktop     | [e423142ac2](https://linux-hardware.org/?probe=e423142ac2) | Jul 28, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f526c1ab74](https://linux-hardware.org/?probe=f526c1ab74) | Jul 24, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [023e756c41](https://linux-hardware.org/?probe=023e756c41) | Jul 23, 2020 |
| Samsung       | 760XBE                      | Notebook    | [1daa9fb781](https://linux-hardware.org/?probe=1daa9fb781) | Jul 23, 2020 |
| Samsung       | 760XBE                      | Notebook    | [fdc5b78be7](https://linux-hardware.org/?probe=fdc5b78be7) | Jul 23, 2020 |
| HP            | 8425                        | Desktop     | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| Sony          | VPCEB18FD                   | Notebook    | [bbd63881ce](https://linux-hardware.org/?probe=bbd63881ce) | Jul 19, 2020 |
| Sony          | VPCEB18FD                   | Notebook    | [2970161a20](https://linux-hardware.org/?probe=2970161a20) | Jul 19, 2020 |
| Dell          | Latitude 7410               | Convertible | [5c0f317a1d](https://linux-hardware.org/?probe=5c0f317a1d) | Jul 15, 2020 |
| Lenovo        | ThinkPad E460 20ET0014US    | Notebook    | [92026f05a8](https://linux-hardware.org/?probe=92026f05a8) | Jul 07, 2020 |
| HP            | 1497                        | Desktop     | [114fc860bc](https://linux-hardware.org/?probe=114fc860bc) | Jul 06, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [844578109a](https://linux-hardware.org/?probe=844578109a) | Jul 06, 2020 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [ef35af0360](https://linux-hardware.org/?probe=ef35af0360) | Jul 05, 2020 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [a77123da13](https://linux-hardware.org/?probe=a77123da13) | Jul 05, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5b37542530](https://linux-hardware.org/?probe=5b37542530) | Jul 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [f8b39e4272](https://linux-hardware.org/?probe=f8b39e4272) | Jul 01, 2020 |
| Medion        | Unknown                     | Notebook    | [994978528e](https://linux-hardware.org/?probe=994978528e) | Jun 30, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [77345420dd](https://linux-hardware.org/?probe=77345420dd) | Jun 30, 2020 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [aa9335e337](https://linux-hardware.org/?probe=aa9335e337) | Jun 28, 2020 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [c7c8369ab1](https://linux-hardware.org/?probe=c7c8369ab1) | Jun 28, 2020 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [8502e65ee5](https://linux-hardware.org/?probe=8502e65ee5) | Jun 28, 2020 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f61fb65566](https://linux-hardware.org/?probe=f61fb65566) | Jun 27, 2020 |
| ASRock        | X99 Extreme11               | Desktop     | [fa8d061f8f](https://linux-hardware.org/?probe=fa8d061f8f) | Jun 27, 2020 |
| ASRock        | X99 Extreme11               | Desktop     | [2f6eabe3fc](https://linux-hardware.org/?probe=2f6eabe3fc) | Jun 27, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aba4b6462f](https://linux-hardware.org/?probe=aba4b6462f) | Jun 27, 2020 |
| Google        | Coral                       | Notebook    | [96a7dea193](https://linux-hardware.org/?probe=96a7dea193) | Jun 26, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [ad7aca7798](https://linux-hardware.org/?probe=ad7aca7798) | Jun 25, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [326b11f044](https://linux-hardware.org/?probe=326b11f044) | Jun 22, 2020 |
| Intel         | X79 INTEL(INTEL Xeon E5/... | Desktop     | [79099f1375](https://linux-hardware.org/?probe=79099f1375) | Jun 18, 2020 |
| Acer          | Spin SP513-51               | Convertible | [384fc377ab](https://linux-hardware.org/?probe=384fc377ab) | Jun 18, 2020 |
| ASUSTek       | TUF Z370-PLUS GAMING II     | Desktop     | [44fc6290e2](https://linux-hardware.org/?probe=44fc6290e2) | Jun 17, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [a7e9be3818](https://linux-hardware.org/?probe=a7e9be3818) | Jun 16, 2020 |
| Dell          | Vostro 7590                 | Notebook    | [9cbd8b38c1](https://linux-hardware.org/?probe=9cbd8b38c1) | Jun 16, 2020 |
| Acer          | Aspire S7-391               | Notebook    | [3bd6e82237](https://linux-hardware.org/?probe=3bd6e82237) | Jun 15, 2020 |
| Dell          | Inspiron 3443               | Notebook    | [a6c281883a](https://linux-hardware.org/?probe=a6c281883a) | Jun 14, 2020 |
| Acer          | Spin SP513-51               | Convertible | [5a62b3876c](https://linux-hardware.org/?probe=5a62b3876c) | Jun 12, 2020 |
| Acer          | Spin SP513-51               | Convertible | [500d8a55a9](https://linux-hardware.org/?probe=500d8a55a9) | Jun 12, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [4eba6cb14f](https://linux-hardware.org/?probe=4eba6cb14f) | Jun 12, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [de91036bf6](https://linux-hardware.org/?probe=de91036bf6) | Jun 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [de0f29b8a1](https://linux-hardware.org/?probe=de0f29b8a1) | Jun 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b59aed06a2](https://linux-hardware.org/?probe=b59aed06a2) | Jun 11, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [601eeac41c](https://linux-hardware.org/?probe=601eeac41c) | Jun 10, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [72e82818d9](https://linux-hardware.org/?probe=72e82818d9) | Jun 10, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1ef78276ca](https://linux-hardware.org/?probe=1ef78276ca) | Jun 09, 2020 |
| HP            | 340S G7                     | Notebook    | [c433639026](https://linux-hardware.org/?probe=c433639026) | Jun 09, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [b8d172d989](https://linux-hardware.org/?probe=b8d172d989) | Jun 08, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [c304a8f6f8](https://linux-hardware.org/?probe=c304a8f6f8) | Jun 08, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Clear_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Clear Linux 36010 | 34        | 3.17%   |
| Clear Linux 35000 | 29        | 2.71%   |
| Clear Linux 32480 | 19        | 1.77%   |
| Clear Linux 34930 | 15        | 1.4%    |
| Clear Linux 32270 | 15        | 1.4%    |
| Clear Linux 32760 | 13        | 1.21%   |
| Clear Linux 34820 | 12        | 1.12%   |
| Clear Linux 33590 | 12        | 1.12%   |
| Clear Linux 32380 | 11        | 1.03%   |
| Clear Linux 34860 | 10        | 0.93%   |
| Clear Linux 32330 | 10        | 0.93%   |
| Clear Linux 34500 | 9         | 0.84%   |
| Clear Linux 33010 | 9         | 0.84%   |
| Clear Linux 35110 | 8         | 0.75%   |
| Clear Linux 33660 | 8         | 0.75%   |
| Clear Linux 32910 | 8         | 0.75%   |
| Clear Linux 34290 | 7         | 0.65%   |
| Clear Linux       | 7         | 0.65%   |
| Clear Linux 40130 | 6         | 0.56%   |
| Clear Linux 37000 | 6         | 0.56%   |
| Clear Linux 36250 | 6         | 0.56%   |
| Clear Linux 36070 | 6         | 0.56%   |
| Clear Linux 34700 | 6         | 0.56%   |
| Clear Linux 34670 | 6         | 0.56%   |
| Clear Linux 34350 | 6         | 0.56%   |
| Clear Linux 34250 | 6         | 0.56%   |
| Clear Linux 33980 | 6         | 0.56%   |
| Clear Linux 33460 | 6         | 0.56%   |
| Clear Linux 33440 | 6         | 0.56%   |
| Clear Linux 32600 | 6         | 0.56%   |
| Clear Linux 32390 | 6         | 0.56%   |
| Clear Linux 40750 | 5         | 0.47%   |
| Clear Linux 38280 | 5         | 0.47%   |
| Clear Linux 37980 | 5         | 0.47%   |
| Clear Linux 36640 | 5         | 0.47%   |
| Clear Linux 35550 | 5         | 0.47%   |
| Clear Linux 35470 | 5         | 0.47%   |
| Clear Linux 35250 | 5         | 0.47%   |
| Clear Linux 35190 | 5         | 0.47%   |
| Clear Linux 35090 | 5         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Clear Linux | 925       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.16.13-1132.native | 56        | 5.28%   |
| 5.13.13-1070.native | 49        | 4.62%   |
| 5.10.19-1032.native | 30        | 2.83%   |
| 5.5.6-914.native    | 27        | 2.55%   |
| 5.7.13-975.native   | 24        | 2.26%   |
| 5.4.18-902.native   | 23        | 2.17%   |
| 5.12.14-1051.native | 18        | 1.7%    |
| 5.13.8-1065.native  | 13        | 1.23%   |
| 5.5.5-911.native    | 12        | 1.13%   |
| 5.5.15-930.native   | 12        | 1.13%   |
| 5.9.12-1004.native  | 11        | 1.04%   |
| 5.6.6-942.native    | 9         | 0.85%   |
| 5.5.3-908.native    | 9         | 0.85%   |
| 5.12.8-1045.native  | 9         | 0.85%   |
| 5.9.8-1000.native   | 8         | 0.75%   |
| 5.7.7-967.native    | 8         | 0.75%   |
| 5.7.6-966.native    | 8         | 0.75%   |
| 5.5.9-918.native    | 8         | 0.75%   |
| 5.10.17-1026.native | 8         | 0.75%   |
| 6.5.7-1371.native   | 7         | 0.66%   |
| 5.7.2-962.native    | 7         | 0.66%   |
| 5.6.8-945.native    | 7         | 0.66%   |
| 5.5.4-909.native    | 7         | 0.66%   |
| 5.12.5-1041.native  | 7         | 0.66%   |
| 6.10.6-1459.native  | 6         | 0.57%   |
| 6.1.1-1228.native   | 6         | 0.57%   |
| 5.5.8-917.native    | 6         | 0.57%   |
| 5.3.9-863.native    | 6         | 0.57%   |
| 5.3.8-854.native    | 6         | 0.57%   |
| 5.3.5-847.native    | 6         | 0.57%   |
| 5.18.16-1165.native | 6         | 0.57%   |
| 5.16.17-1136.native | 6         | 0.57%   |
| 5.12.16-1054.native | 6         | 0.57%   |
| 5.10.18-1027.native | 6         | 0.57%   |
| 5.10.10-1017.native | 6         | 0.57%   |
| 5.1.5-770.native    | 6         | 0.57%   |
| 5.0.18-767.native   | 6         | 0.57%   |
| 6.1.2-1232.native   | 5         | 0.47%   |
| 5.9.1-992.native    | 5         | 0.47%   |
| 5.8.14-991.native   | 5         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.13 | 56        | 5.28%   |
| 5.13.13 | 49        | 4.62%   |
| 5.10.19 | 30        | 2.83%   |
| 5.5.6   | 27        | 2.55%   |
| 5.7.13  | 24        | 2.26%   |
| 5.4.18  | 23        | 2.17%   |
| 5.12.14 | 18        | 1.7%    |
| 5.5.3   | 13        | 1.23%   |
| 5.13.8  | 13        | 1.23%   |
| 5.5.5   | 12        | 1.13%   |
| 5.5.15  | 12        | 1.13%   |
| 5.9.12  | 11        | 1.04%   |
| 5.5.4   | 11        | 1.04%   |
| 5.6.8   | 10        | 0.94%   |
| 5.6.6   | 9         | 0.85%   |
| 5.5.9   | 9         | 0.85%   |
| 5.12.8  | 9         | 0.85%   |
| 5.9.8   | 8         | 0.75%   |
| 5.7.7   | 8         | 0.75%   |
| 5.7.6   | 8         | 0.75%   |
| 5.10.17 | 8         | 0.75%   |
| 6.5.7   | 7         | 0.66%   |
| 6.1.1   | 7         | 0.66%   |
| 5.7.2   | 7         | 0.66%   |
| 5.17.9  | 7         | 0.66%   |
| 5.12.5  | 7         | 0.66%   |
| 6.10.6  | 6         | 0.57%   |
| 5.6.15  | 6         | 0.57%   |
| 5.5.8   | 6         | 0.57%   |
| 5.5.13  | 6         | 0.57%   |
| 5.3.9   | 6         | 0.57%   |
| 5.3.8   | 6         | 0.57%   |
| 5.3.5   | 6         | 0.57%   |
| 5.18.16 | 6         | 0.57%   |
| 5.16.18 | 6         | 0.57%   |
| 5.16.17 | 6         | 0.57%   |
| 5.12.16 | 6         | 0.57%   |
| 5.10.18 | 6         | 0.57%   |
| 5.10.10 | 6         | 0.57%   |
| 5.1.5   | 6         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.5     | 105       | 10.29%  |
| 5.10    | 91        | 8.92%   |
| 5.16    | 84        | 8.24%   |
| 5.13    | 72        | 7.06%   |
| 5.7     | 67        | 6.57%   |
| 5.4     | 67        | 6.57%   |
| 5.6     | 59        | 5.78%   |
| 5.12    | 53        | 5.2%    |
| 5.9     | 42        | 4.12%   |
| 5.3     | 37        | 3.63%   |
| 6.1     | 27        | 2.65%   |
| 5.18    | 25        | 2.45%   |
| 5.15    | 23        | 2.25%   |
| 6.0     | 22        | 2.16%   |
| 5.2     | 22        | 2.16%   |
| 5.8     | 21        | 2.06%   |
| 5.0     | 21        | 2.06%   |
| 5.17    | 20        | 1.96%   |
| 6.6     | 19        | 1.86%   |
| 5.1     | 18        | 1.76%   |
| 6.2     | 17        | 1.67%   |
| 5.14    | 17        | 1.67%   |
| 6.10    | 16        | 1.57%   |
| 6.5     | 13        | 1.27%   |
| 5.19    | 12        | 1.18%   |
| 4.19    | 11        | 1.08%   |
| 6.7     | 9         | 0.88%   |
| 6.4     | 8         | 0.78%   |
| 6.3     | 7         | 0.69%   |
| 6.11    | 6         | 0.59%   |
| 6.8     | 5         | 0.49%   |
| 6.9     | 3         | 0.29%   |
| 6.12    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 925       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 779       | 82%     |
| Unknown         | 99        | 10.42%  |
| KDE             | 21        | 2.21%   |
| KDE5            | 18        | 1.89%   |
| GNOME Flashback | 18        | 1.89%   |
| XFCE            | 10        | 1.05%   |
| KDE6            | 2         | 0.21%   |
| GNOME-Flashback | 2         | 0.21%   |
| awesome         | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 801       | 85.39%  |
| Wayland | 125       | 13.33%  |
| Tty     | 10        | 1.07%   |
| Unknown | 2         | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 911       | 98.27%  |
| GDM     | 15        | 1.62%   |
| SDDM    | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 570       | 60.38%  |
| Unknown    | 90        | 9.53%   |
| ru_RU      | 48        | 5.08%   |
| C          | 38        | 4.03%   |
| es_MX      | 31        | 3.28%   |
| de_DE      | 31        | 3.28%   |
| it_IT      | 20        | 2.12%   |
| en_GB      | 19        | 2.01%   |
| fr_FR      | 17        | 1.8%    |
| pt_BR      | 15        | 1.59%   |
| pl_PL      | 12        | 1.27%   |
| zh_CN      | 10        | 1.06%   |
| es_ES      | 9         | 0.95%   |
| pt_PT      | 4         | 0.42%   |
| en_AU      | 4         | 0.42%   |
| tr_TR      | 3         | 0.32%   |
| bg_BG      | 3         | 0.32%   |
| zh_TW      | 2         | 0.21%   |
| nl_BE      | 2         | 0.21%   |
| fi_FI      | 2         | 0.21%   |
| en_ZA      | 2         | 0.21%   |
| tr_CY      | 1         | 0.11%   |
| sv_SE      | 1         | 0.11%   |
| nl_NL      | 1         | 0.11%   |
| ka_GE      | 1         | 0.11%   |
| hu_HU      | 1         | 0.11%   |
| fo_FO      | 1         | 0.11%   |
| es_CL      | 1         | 0.11%   |
| en_US.UTF8 | 1         | 0.11%   |
| en_IN      | 1         | 0.11%   |
| de_AT      | 1         | 0.11%   |
| da_DK      | 1         | 0.11%   |
| ar_SA      | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 924       | 99.89%  |
| EFI  | 1         | 0.11%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 812       | 86.57%  |
| Unknown | 103       | 10.98%  |
| Xfs     | 12        | 1.28%   |
| Btrfs   | 11        | 1.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 903       | 96.99%  |
| GPT     | 28        | 3.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 922       | 99.68%  |
| Yes       | 3         | 0.32%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 917       | 99.03%  |
| Yes       | 9         | 0.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 146       | 15.78%  |
| Dell                | 128       | 13.84%  |
| Hewlett-Packard     | 118       | 12.76%  |
| Lenovo              | 111       | 12%     |
| Gigabyte Technology | 62        | 6.7%    |
| Acer                | 50        | 5.41%   |
| MSI                 | 43        | 4.65%   |
| Intel               | 42        | 4.54%   |
| ASRock              | 34        | 3.68%   |
| Apple               | 30        | 3.24%   |
| Samsung Electronics | 14        | 1.51%   |
| Unknown             | 14        | 1.51%   |
| Google              | 13        | 1.41%   |
| Microsoft           | 9         | 0.97%   |
| Toshiba             | 7         | 0.76%   |
| HUAWEI              | 6         | 0.65%   |
| Fujitsu             | 6         | 0.65%   |
| Sony                | 5         | 0.54%   |
| Chuwi               | 5         | 0.54%   |
| Timi                | 4         | 0.43%   |
| Supermicro          | 4         | 0.43%   |
| Hampoo              | 4         | 0.43%   |
| Positivo            | 3         | 0.32%   |
| Medion              | 3         | 0.32%   |
| Complet             | 3         | 0.32%   |
| Biostar             | 3         | 0.32%   |
| AMI                 | 3         | 0.32%   |
| Alienware           | 3         | 0.32%   |
| Teclast             | 2         | 0.22%   |
| Shuttle             | 2         | 0.22%   |
| Pegatron            | 2         | 0.22%   |
| Panasonic           | 2         | 0.22%   |
| Notebook            | 2         | 0.22%   |
| MOTILE              | 2         | 0.22%   |
| MECHREVO            | 2         | 0.22%   |
| Huanan              | 2         | 0.22%   |
| Foxconn             | 2         | 0.22%   |
| TrekStor            | 1         | 0.11%   |
| TODOS INDUSTRIAL    | 1         | 0.11%   |
| SYS                 | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 17        | 1.84%   |
| ASUS All Series                            | 12        | 1.3%    |
| Dell XPS 15 9560                           | 5         | 0.54%   |
| Dell OptiPlex 9020                         | 5         | 0.54%   |
| Intel NUC8i7BEH                            | 4         | 0.43%   |
| Intel DN2820FYB H24582-205                 | 4         | 0.43%   |
| HP Notebook                                | 4         | 0.43%   |
| Dell OptiPlex 7010                         | 4         | 0.43%   |
| Apple MacBookPro11,5                       | 4         | 0.43%   |
| MSI MS-7C95                                | 3         | 0.32%   |
| MSI MS-7C60                                | 3         | 0.32%   |
| MSI MS-7C02                                | 3         | 0.32%   |
| Microsoft Surface Book 2                   | 3         | 0.32%   |
| Lenovo MIIX 310-10ICR 80SG                 | 3         | 0.32%   |
| Lenovo G500 20236                          | 3         | 0.32%   |
| HP Pavilion Notebook                       | 3         | 0.32%   |
| HP Pavilion 15                             | 3         | 0.32%   |
| HP EliteBook 8460p                         | 3         | 0.32%   |
| HP EliteBook 840 G1                        | 3         | 0.32%   |
| Dell XPS 13 9360                           | 3         | 0.32%   |
| Dell Inspiron 5570                         | 3         | 0.32%   |
| Dell Inspiron 3537                         | 3         | 0.32%   |
| Complet MY8312                             | 3         | 0.32%   |
| ASUS VivoBook_ASUSLaptop X515DA_M515DA     | 3         | 0.32%   |
| ASRock TRX40 Creator                       | 3         | 0.32%   |
| Apple MacBookPro9,2                        | 3         | 0.32%   |
| Apple MacBookPro8,1                        | 3         | 0.32%   |
| Apple MacBookPro10,1                       | 3         | 0.32%   |
| Timi Xiaomi NoteBook Pro                   | 2         | 0.22%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D | 2         | 0.22%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 2         | 0.22%   |
| MSI GS43VR 7RE                             | 2         | 0.22%   |
| MOTILE M141                                | 2         | 0.22%   |
| Lenovo IdeaPad 110-15ACL 80TJ              | 2         | 0.22%   |
| Lenovo G50-70 20351                        | 2         | 0.22%   |
| Intel NUC8i7HVK                            | 2         | 0.22%   |
| Intel NUC8i5BEK                            | 2         | 0.22%   |
| Intel NUC6CAYB J23203-403                  | 2         | 0.22%   |
| Intel NUC5PPYB H76558-109                  | 2         | 0.22%   |
| Intel NUC10i7FNH                           | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 42        | 4.54%   |
| Acer Aspire        | 41        | 4.43%   |
| Dell Inspiron      | 33        | 3.57%   |
| Dell Latitude      | 31        | 3.35%   |
| Dell XPS           | 30        | 3.24%   |
| Lenovo IdeaPad     | 26        | 2.81%   |
| HP Pavilion        | 23        | 2.49%   |
| ASUS ROG           | 23        | 2.49%   |
| ASUS PRIME         | 22        | 2.38%   |
| HP EliteBook       | 19        | 2.05%   |
| Dell OptiPlex      | 17        | 1.84%   |
| Unknown            | 17        | 1.84%   |
| ASUS VivoBook      | 16        | 1.73%   |
| ASUS TUF           | 12        | 1.3%    |
| ASUS All           | 12        | 1.3%    |
| HP Laptop          | 10        | 1.08%   |
| Microsoft Surface  | 9         | 0.97%   |
| Dell Precision     | 9         | 0.97%   |
| Lenovo ThinkCentre | 8         | 0.86%   |
| HP ENVY            | 8         | 0.86%   |
| HP Compaq          | 8         | 0.86%   |
| Toshiba Satellite  | 6         | 0.65%   |
| HP Stream          | 6         | 0.65%   |
| ASUS ZenBook       | 6         | 0.65%   |
| Apple MacBookPro11 | 6         | 0.65%   |
| Lenovo Yoga        | 5         | 0.54%   |
| Gigabyte X570      | 5         | 0.54%   |
| Dell Vostro        | 5         | 0.54%   |
| Apple MacBookPro8  | 5         | 0.54%   |
| Lenovo MIIX        | 4         | 0.43%   |
| Intel NUC8i7BEH    | 4         | 0.43%   |
| Intel DN2820FYB    | 4         | 0.43%   |
| HP ZBook           | 4         | 0.43%   |
| HP ProLiant        | 4         | 0.43%   |
| HP Notebook        | 4         | 0.43%   |
| Fujitsu LIFEBOOK   | 4         | 0.43%   |
| ASRock TRX40       | 4         | 0.43%   |
| MSI MS-7C95        | 3         | 0.32%   |
| MSI MS-7C60        | 3         | 0.32%   |
| MSI MS-7C02        | 3         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 122       | 13.19%  |
| 2019 | 115       | 12.43%  |
| 2020 | 86        | 9.3%    |
| 2012 | 85        | 9.19%   |
| 2017 | 83        | 8.97%   |
| 2016 | 74        | 8%      |
| 2014 | 73        | 7.89%   |
| 2013 | 72        | 7.78%   |
| 2015 | 66        | 7.14%   |
| 2021 | 48        | 5.19%   |
| 2011 | 46        | 4.97%   |
| 2022 | 27        | 2.92%   |
| 2010 | 14        | 1.51%   |
| 2023 | 7         | 0.76%   |
| 2024 | 2         | 0.22%   |
| 2009 | 2         | 0.22%   |
| 2007 | 2         | 0.22%   |
| 2008 | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 493       | 53.3%   |
| Desktop     | 327       | 35.35%  |
| Mini pc     | 42        | 4.54%   |
| Convertible | 24        | 2.59%   |
| Tablet      | 22        | 2.38%   |
| Server      | 10        | 1.08%   |
| All in one  | 6         | 0.65%   |
| Stick pc    | 1         | 0.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 925       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 912       | 98.59%  |
| Yes  | 13        | 1.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 239       | 25.51%  |
| 4.01-8.0        | 202       | 21.56%  |
| 8.01-16.0       | 173       | 18.46%  |
| 3.01-4.0        | 144       | 15.37%  |
| 32.01-64.0      | 99        | 10.57%  |
| 64.01-256.0     | 43        | 4.59%   |
| 24.01-32.0      | 17        | 1.81%   |
| 1.01-2.0        | 14        | 1.49%   |
| More than 256.0 | 4         | 0.43%   |
| 2.01-3.0        | 2         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 352       | 35.13%  |
| 2.01-3.0    | 322       | 32.14%  |
| 3.01-4.0    | 148       | 14.77%  |
| 4.01-8.0    | 125       | 12.48%  |
| 8.01-16.0   | 32        | 3.19%   |
| 0.51-1.0    | 19        | 1.9%    |
| 16.01-24.0  | 2         | 0.2%    |
| 32.01-64.0  | 1         | 0.1%    |
| 64.01-256.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 561       | 59.05%  |
| 2      | 234       | 24.63%  |
| 3      | 83        | 8.74%   |
| 4      | 37        | 3.89%   |
| 5      | 17        | 1.79%   |
| 6      | 9         | 0.95%   |
| 0      | 5         | 0.53%   |
| 7      | 4         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 695       | 74.89%  |
| Yes       | 233       | 25.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 749       | 80.71%  |
| No        | 179       | 19.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 730       | 78.41%  |
| No        | 201       | 21.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 637       | 68.2%   |
| No        | 297       | 31.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 231       | 24.87%  |
| Russia       | 73        | 7.86%   |
| Germany      | 53        | 5.71%   |
| UK           | 48        | 5.17%   |
| Italy        | 41        | 4.41%   |
| Brazil       | 41        | 4.41%   |
| Canada       | 31        | 3.34%   |
| Australia    | 30        | 3.23%   |
| India        | 25        | 2.69%   |
| Poland       | 24        | 2.58%   |
| France       | 23        | 2.48%   |
| Netherlands  | 20        | 2.15%   |
| Spain        | 19        | 2.05%   |
| Mexico       | 16        | 1.72%   |
| Romania      | 14        | 1.51%   |
| Sweden       | 12        | 1.29%   |
| Bulgaria     | 12        | 1.29%   |
| Argentina    | 12        | 1.29%   |
| Ukraine      | 10        | 1.08%   |
| Turkey       | 10        | 1.08%   |
| Portugal     | 10        | 1.08%   |
| Switzerland  | 9         | 0.97%   |
| China        | 9         | 0.97%   |
| South Africa | 8         | 0.86%   |
| Norway       | 8         | 0.86%   |
| Indonesia    | 8         | 0.86%   |
| Belgium      | 7         | 0.75%   |
| Hong Kong    | 6         | 0.65%   |
| Finland      | 6         | 0.65%   |
| Austria      | 6         | 0.65%   |
| Vietnam      | 5         | 0.54%   |
| Thailand     | 5         | 0.54%   |
| Chile        | 5         | 0.54%   |
| Serbia       | 4         | 0.43%   |
| Israel       | 4         | 0.43%   |
| Hungary      | 4         | 0.43%   |
| Denmark      | 4         | 0.43%   |
| Taiwan       | 3         | 0.32%   |
| Saudi Arabia | 3         | 0.32%   |
| New Zealand  | 3         | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 20        | 2.06%   |
| Sydney            | 9         | 0.93%   |
| St Petersburg     | 9         | 0.93%   |
| Rome              | 9         | 0.93%   |
| Brisbane          | 9         | 0.93%   |
| Berlin            | 8         | 0.82%   |
| Sao Paulo         | 6         | 0.62%   |
| Portland          | 6         | 0.62%   |
| Chicago           | 6         | 0.62%   |
| Zurich            | 5         | 0.51%   |
| Tucson            | 5         | 0.51%   |
| Toronto           | 5         | 0.51%   |
| Sofia             | 5         | 0.51%   |
| Seattle           | 5         | 0.51%   |
| Houston           | 5         | 0.51%   |
| Warsaw            | 4         | 0.41%   |
| Vancouver         | 4         | 0.41%   |
| San Francisco     | 4         | 0.41%   |
| Mumbai            | 4         | 0.41%   |
| Mexico City       | 4         | 0.41%   |
| Melbourne         | 4         | 0.41%   |
| Lodz              | 4         | 0.41%   |
| Johannesburg      | 4         | 0.41%   |
| Fort Worth        | 4         | 0.41%   |
| Central           | 4         | 0.41%   |
| Buenos Aires      | 4         | 0.41%   |
| Bengaluru         | 4         | 0.41%   |
| Wroclaw           | 3         | 0.31%   |
| Vigneux-sur-Seine | 3         | 0.31%   |
| Thunder Bay       | 3         | 0.31%   |
| Stockholm         | 3         | 0.31%   |
| Springfield       | 3         | 0.31%   |
| Shelbyville       | 3         | 0.31%   |
| San Jose          | 3         | 0.31%   |
| Samara            | 3         | 0.31%   |
| Rho               | 3         | 0.31%   |
| Palermo           | 3         | 0.31%   |
| Minsk             | 3         | 0.31%   |
| Milan             | 3         | 0.31%   |
| Lisbon            | 3         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 209       | 320    | 15.12%  |
| Seagate                   | 168       | 233    | 12.16%  |
| WDC                       | 131       | 169    | 9.48%   |
| Toshiba                   | 103       | 125    | 7.45%   |
| Unknown                   | 94        | 127    | 6.8%    |
| SanDisk                   | 91        | 107    | 6.58%   |
| Kingston                  | 69        | 85     | 4.99%   |
| SK hynix                  | 44        | 50     | 3.18%   |
| Intel                     | 44        | 53     | 3.18%   |
| Crucial                   | 40        | 51     | 2.89%   |
| HGST                      | 30        | 38     | 2.17%   |
| Hitachi                   | 25        | 28     | 1.81%   |
| Phison                    | 23        | 32     | 1.66%   |
| Micron Technology         | 22        | 27     | 1.59%   |
| A-DATA Technology         | 22        | 24     | 1.59%   |
| Apple                     | 19        | 20     | 1.37%   |
| JMicron Technology        | 15        | 15     | 1.09%   |
| SPCC                      | 13        | 14     | 0.94%   |
| Silicon Motion            | 11        | 13     | 0.8%    |
| Transcend                 | 10        | 10     | 0.72%   |
| Patriot                   | 10        | 11     | 0.72%   |
| Micron/Crucial Technology | 10        | 13     | 0.72%   |
| China                     | 10        | 32     | 0.72%   |
| KIOXIA                    | 9         | 16     | 0.65%   |
| Phison Electronics        | 8         | 8      | 0.58%   |
| LITEONIT                  | 8         | 15     | 0.58%   |
| PNY                       | 7         | 13     | 0.51%   |
| LITEON                    | 7         | 8      | 0.51%   |
| Hewlett-Packard           | 7         | 8      | 0.51%   |
| XPG                       | 6         | 6      | 0.43%   |
| KingSpec                  | 6         | 7      | 0.43%   |
| ADATA Technology          | 6         | 6      | 0.43%   |
| Team                      | 5         | 5      | 0.36%   |
| Corsair                   | 5         | 9      | 0.36%   |
| OCZ                       | 4         | 6      | 0.29%   |
| Netac                     | 4         | 4      | 0.29%   |
| KingDian                  | 4         | 6      | 0.29%   |
| Fujitsu                   | 4         | 5      | 0.29%   |
| FORESEE                   | 4         | 4      | 0.29%   |
| Apacer                    | 4         | 5      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 26        | 1.73%   |
| Samsung NVMe SSD Drive 500GB                        | 25        | 1.66%   |
| Unknown MMC Card  64GB                              | 24        | 1.59%   |
| Samsung SSD 850 EVO 250GB                           | 17        | 1.13%   |
| Samsung NVMe SSD Drive 1TB                          | 15        | 1%      |
| Samsung NVMe SSD Drive 256GB                        | 14        | 0.93%   |
| Kingston SA400S37240G 240GB SSD                     | 14        | 0.93%   |
| Unknown MMC Card  128GB                             | 13        | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB                      | 12        | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 12        | 0.8%    |
| HGST HTS721010A9E630 1TB                            | 12        | 0.8%    |
| Unknown SD/MMC/MS PRO 128GB                         | 11        | 0.73%   |
| Toshiba NVMe SSD Drive 512GB                        | 10        | 0.66%   |
| Toshiba MQ01ABF050 500GB                            | 10        | 0.66%   |
| SanDisk NVMe SSD Drive 256GB                        | 10        | 0.66%   |
| Samsung NVMe SSD Drive 1024GB                       | 10        | 0.66%   |
| JMicron Tech 250GB                                  | 10        | 0.66%   |
| Crucial CT500MX500SSD1 500GB                        | 10        | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 9         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                     | 9         | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                      | 9         | 0.6%    |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 9         | 0.6%    |
| Toshiba NVMe SSD Drive 256GB                        | 8         | 0.53%   |
| Toshiba MQ01ABD100 1TB                              | 8         | 0.53%   |
| Toshiba DT01ACA100 1TB                              | 8         | 0.53%   |
| Samsung NVMe SSD Drive 512GB                        | 8         | 0.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 8         | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 8         | 0.53%   |
| Intel NVMe SSD Drive 512GB                          | 8         | 0.53%   |
| SK hynix NVMe SSD Drive 512GB                       | 7         | 0.46%   |
| SK hynix NVMe SSD Drive 256GB                       | 7         | 0.46%   |
| SanDisk NVMe SSD Drive 512GB                        | 7         | 0.46%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.46%   |
| Samsung SSD 860 EVO 250GB                           | 7         | 0.46%   |
| Intel NVMe SSD Drive 1024GB                         | 7         | 0.46%   |
| Toshiba DT01ACA050 500GB                            | 6         | 0.4%    |
| Samsung SSD 860 QVO 1TB                             | 6         | 0.4%    |
| Samsung SSD 850 PRO 256GB                           | 6         | 0.4%    |
| Samsung SSD 850 EVO 500GB                           | 6         | 0.4%    |
| Phison NVMe SSD Drive 1TB                           | 6         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 160       | 218    | 36.87%  |
| WDC                 | 108       | 138    | 24.88%  |
| Toshiba             | 63        | 82     | 14.52%  |
| HGST                | 30        | 38     | 6.91%   |
| Hitachi             | 25        | 28     | 5.76%   |
| Unknown             | 11        | 12     | 2.53%   |
| Samsung Electronics | 10        | 10     | 2.3%    |
| JMicron Technology  | 5         | 5      | 1.15%   |
| SABRENT             | 3         | 3      | 0.69%   |
| Hewlett-Packard     | 3         | 4      | 0.69%   |
| Fujitsu             | 3         | 4      | 0.69%   |
| Apple               | 3         | 3      | 0.69%   |
| Maxtor              | 2         | 2      | 0.46%   |
| USB3.0              | 1         | 1      | 0.23%   |
| TO Exter            | 1         | 1      | 0.23%   |
| MARVELL             | 1         | 1      | 0.23%   |
| HPE                 | 1         | 1      | 0.23%   |
| H/W                 | 1         | 2      | 0.23%   |
| External            | 1         | 1      | 0.23%   |
| ASMT                | 1         | 2      | 0.23%   |
| Unknown             | 1         | 5      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 119       | 173    | 22.62%  |
| Kingston            | 59        | 70     | 11.22%  |
| SanDisk             | 46        | 50     | 8.75%   |
| Crucial             | 40        | 51     | 7.6%    |
| WDC                 | 26        | 31     | 4.94%   |
| A-DATA Technology   | 21        | 23     | 3.99%   |
| SK hynix            | 20        | 24     | 3.8%    |
| Micron Technology   | 15        | 17     | 2.85%   |
| Apple               | 15        | 16     | 2.85%   |
| Toshiba             | 14        | 15     | 2.66%   |
| SPCC                | 13        | 14     | 2.47%   |
| Intel               | 13        | 14     | 2.47%   |
| Transcend           | 10        | 10     | 1.9%    |
| Patriot             | 10        | 11     | 1.9%    |
| China               | 10        | 32     | 1.9%    |
| LITEONIT            | 8         | 15     | 1.52%   |
| PNY                 | 7         | 13     | 1.33%   |
| LITEON              | 7         | 8      | 1.33%   |
| KingSpec            | 6         | 7      | 1.14%   |
| Team                | 5         | 5      | 0.95%   |
| OCZ                 | 4         | 6      | 0.76%   |
| KingDian            | 4         | 6      | 0.76%   |
| Hewlett-Packard     | 4         | 4      | 0.76%   |
| FORESEE             | 4         | 4      | 0.76%   |
| Corsair             | 4         | 8      | 0.76%   |
| Apacer              | 4         | 5      | 0.76%   |
| Teclast             | 3         | 3      | 0.57%   |
| Plextor             | 3         | 3      | 0.57%   |
| Netac               | 3         | 3      | 0.57%   |
| Seagate             | 2         | 2      | 0.38%   |
| Intenso             | 2         | 2      | 0.38%   |
| Hikvision           | 2         | 2      | 0.38%   |
| GOODRAM             | 2         | 2      | 0.38%   |
| WDC WDS2            | 1         | 1      | 0.19%   |
| WDC WDS1            | 1         | 1      | 0.19%   |
| W800S               | 1         | 1      | 0.19%   |
| Verbatim            | 1         | 2      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |
| Smart               | 1         | 1      | 0.19%   |
| SD                  | 1         | 2      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 460       | 675    | 36.08%  |
| HDD     | 388       | 561    | 30.43%  |
| NVMe    | 320       | 436    | 25.1%   |
| MMC     | 74        | 104    | 5.8%    |
| Unknown | 33        | 39     | 2.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 688       | 1201   | 60.03%  |
| NVMe | 320       | 435    | 27.92%  |
| MMC  | 74        | 104    | 6.46%   |
| SAS  | 64        | 75     | 5.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 521       | 786    | 60.79%  |
| 0.51-1.0   | 218       | 295    | 25.44%  |
| 1.01-2.0   | 62        | 78     | 7.23%   |
| 4.01-10.0  | 21        | 28     | 2.45%   |
| 3.01-4.0   | 16        | 21     | 1.87%   |
| 2.01-3.0   | 10        | 11     | 1.17%   |
| 10.01-20.0 | 9         | 17     | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 338       | 35.1%   |
| 251-500        | 206       | 21.39%  |
| 501-1000       | 132       | 13.71%  |
| 51-100         | 70        | 7.27%   |
| Unknown        | 67        | 6.96%   |
| 21-50          | 55        | 5.71%   |
| 1001-2000      | 50        | 5.19%   |
| More than 3000 | 26        | 2.7%    |
| 2001-3000      | 15        | 1.56%   |
| 1-20           | 4         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 446       | 45.01%  |
| 21-50          | 231       | 23.31%  |
| 51-100         | 84        | 8.48%   |
| 101-250        | 72        | 7.27%   |
| Unknown        | 67        | 6.76%   |
| 251-500        | 35        | 3.53%   |
| 501-1000       | 25        | 2.52%   |
| 1001-2000      | 16        | 1.61%   |
| More than 3000 | 11        | 1.11%   |
| 2001-3000      | 4         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LM030-2E717D 500GB | 2         | 2      | 66.67%  |
| Fujitsu MHZ2250BH G1 250GB      | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Fujitsu | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| Fujitsu | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Detected | 905       | 1772   | 97.21%  |
| Works    | 23        | 40     | 2.47%   |
| Malfunc  | 3         | 3      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 674       | 57.46%  |
| AMD                          | 124       | 10.57%  |
| Samsung Electronics          | 119       | 10.14%  |
| SanDisk                      | 45        | 3.84%   |
| Phison Electronics           | 29        | 2.47%   |
| Toshiba America Info Systems | 26        | 2.22%   |
| SK hynix                     | 24        | 2.05%   |
| ASMedia Technology           | 24        | 2.05%   |
| ADATA Technology             | 14        | 1.19%   |
| Kingston Technology Company  | 13        | 1.11%   |
| Marvell Technology Group     | 12        | 1.02%   |
| Silicon Motion               | 11        | 0.94%   |
| Micron/Crucial Technology    | 10        | 0.85%   |
| KIOXIA                       | 10        | 0.85%   |
| Micron Technology            | 7         | 0.6%    |
| Broadcom / LSI               | 5         | 0.43%   |
| Seagate Technology           | 4         | 0.34%   |
| Yangtze Memory Technologies  | 3         | 0.26%   |
| Realtek Semiconductor        | 3         | 0.26%   |
| MAXIO Technology (Hangzhou)  | 3         | 0.26%   |
| LSI Logic / Symbios Logic    | 3         | 0.26%   |
| Hewlett-Packard              | 3         | 0.26%   |
| Shenzhen Longsys Electronics | 2         | 0.17%   |
| Lite-On Technology           | 2         | 0.17%   |
| JMicron Technology           | 1         | 0.09%   |
| Biwin Storage Technology     | 1         | 0.09%   |
| Apple                        | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 100       | 7.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 65        | 5.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 65        | 5.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 57        | 4.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 50        | 3.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 42        | 3.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 31        | 2.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 30        | 2.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 25        | 1.95%   |
| Intel SATA Controller [RAID Mode]                                              | 25        | 1.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 25        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 25        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 22        | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21        | 1.64%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 21        | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 1.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 20        | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 1.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19        | 1.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 19        | 1.48%   |
| AMD 400 Series Chipset SATA Controller                                         | 19        | 1.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 17        | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 17        | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 16        | 1.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13        | 1.01%   |
| Intel SSD 660P Series                                                          | 13        | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 0.86%   |
| Phison E12 NVMe Controller                                                     | 11        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11        | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 11        | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 10        | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                               | 10        | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 10        | 0.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9         | 0.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 0.7%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 8         | 0.62%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 8         | 0.62%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 8         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 710       | 60.68%  |
| NVMe | 326       | 27.86%  |
| RAID | 95        | 8.12%   |
| IDE  | 31        | 2.65%   |
| SAS  | 7         | 0.6%    |
| SCSI | 1         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 789       | 85.3%   |
| AMD    | 136       | 14.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz              | 19        | 2.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 12        | 1.3%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 11        | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 10        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 10        | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 10        | 1.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 10        | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 9         | 0.97%   |
| Intel Core i5-4200U CPU @ 1.60GHz              | 9         | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 9         | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 8         | 0.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 8         | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 8         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 8         | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 8         | 0.86%   |
| Intel Celeron CPU N3350 @ 1.10GHz              | 8         | 0.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 8         | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 7         | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 7         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 7         | 0.76%   |
| Intel Celeron CPU N2830 @ 2.16GHz              | 7         | 0.76%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 7         | 0.76%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 6         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 6         | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz              | 6         | 0.65%   |
| Intel Core i7-8559U CPU @ 2.70GHz              | 6         | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 6         | 0.65%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 6         | 0.65%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 6         | 0.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 6         | 0.65%   |
| AMD Ryzen 5 3600 6-Core Processor              | 6         | 0.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 6         | 0.65%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 5         | 0.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 5         | 0.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 5         | 0.54%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 5         | 0.54%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz             | 5         | 0.54%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz             | 5         | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 5         | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 5         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 266       | 28.76%  |
| Intel Core i7          | 217       | 23.46%  |
| Intel Celeron          | 84        | 9.08%   |
| Intel Core i3          | 65        | 7.03%   |
| Other                  | 57        | 6.16%   |
| AMD Ryzen 5            | 35        | 3.78%   |
| Intel Xeon             | 33        | 3.57%   |
| Intel Pentium          | 25        | 2.7%    |
| AMD Ryzen 7            | 23        | 2.49%   |
| Intel Atom             | 15        | 1.62%   |
| AMD Ryzen 3            | 15        | 1.62%   |
| AMD Ryzen Threadripper | 13        | 1.41%   |
| Intel Core i9          | 12        | 1.3%    |
| AMD Ryzen 9            | 11        | 1.19%   |
| AMD FX                 | 9         | 0.97%   |
| Intel Pentium Silver   | 7         | 0.76%   |
| AMD A8                 | 6         | 0.65%   |
| AMD A10                | 5         | 0.54%   |
| AMD A6                 | 4         | 0.43%   |
| AMD Ryzen 7 PRO        | 3         | 0.32%   |
| AMD Athlon             | 3         | 0.32%   |
| Intel Core m5          | 2         | 0.22%   |
| Intel Core m3          | 2         | 0.22%   |
| AMD E1                 | 2         | 0.22%   |
| AMD A4                 | 2         | 0.22%   |
| Intel Xeon Platinum    | 1         | 0.11%   |
| Intel Pentium Gold     | 1         | 0.11%   |
| Intel Genuine          | 1         | 0.11%   |
| Intel Core M           | 1         | 0.11%   |
| Intel Core             | 1         | 0.11%   |
| AMD Ryzen 5 PRO        | 1         | 0.11%   |
| AMD Opteron            | 1         | 0.11%   |
| AMD E2                 | 1         | 0.11%   |
| AMD A12                | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 390       | 42.16%  |
| 2      | 326       | 35.24%  |
| 6      | 94        | 10.16%  |
| 8      | 49        | 5.3%    |
| 12     | 19        | 2.05%   |
| 24     | 10        | 1.08%   |
| 10     | 10        | 1.08%   |
| 16     | 9         | 0.97%   |
| 14     | 5         | 0.54%   |
| 64     | 3         | 0.32%   |
| 32     | 3         | 0.32%   |
| 1      | 3         | 0.32%   |
| 20     | 2         | 0.22%   |
| 36     | 1         | 0.11%   |
| 28     | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 914       | 98.81%  |
| 2      | 10        | 1.08%   |
| 4      | 1         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 667       | 71.95%  |
| 1      | 260       | 28.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 850       | 91.2%   |
| Unknown        | 82        | 8.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 876       | 94.19%  |
| 0x906ea    | 5         | 0.54%   |
| 0x806ea    | 5         | 0.54%   |
| 0x506e3    | 5         | 0.54%   |
| 0x40651    | 5         | 0.54%   |
| 0x306a9    | 5         | 0.54%   |
| 0x906e9    | 4         | 0.43%   |
| 0x306c3    | 4         | 0.43%   |
| 0x30678    | 4         | 0.43%   |
| 0x706a1    | 3         | 0.32%   |
| 0x406c4    | 2         | 0.22%   |
| 0x306d4    | 2         | 0.22%   |
| 0x206a7    | 2         | 0.22%   |
| 0x806ec    | 1         | 0.11%   |
| 0x806eb    | 1         | 0.11%   |
| 0x806e9    | 1         | 0.11%   |
| 0x706a8    | 1         | 0.11%   |
| 0x506c9    | 1         | 0.11%   |
| 0x406c3    | 1         | 0.11%   |
| 0x40671    | 1         | 0.11%   |
| 0x08108109 | 1         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 217       | 23.46%  |
| Haswell          | 109       | 11.78%  |
| IvyBridge        | 93        | 10.05%  |
| Skylake          | 67        | 7.24%   |
| SandyBridge      | 61        | 6.59%   |
| Silvermont       | 54        | 5.84%   |
| Unknown          | 41        | 4.43%   |
| Zen+             | 37        | 4%      |
| Zen 2            | 34        | 3.68%   |
| Broadwell        | 34        | 3.68%   |
| Goldmont plus    | 30        | 3.24%   |
| CometLake        | 22        | 2.38%   |
| TigerLake        | 21        | 2.27%   |
| Goldmont         | 19        | 2.05%   |
| Zen              | 16        | 1.73%   |
| Westmere         | 15        | 1.62%   |
| Piledriver       | 15        | 1.62%   |
| Zen 3            | 14        | 1.51%   |
| IceLake          | 8         | 0.86%   |
| Puma             | 6         | 0.65%   |
| Excavator        | 6         | 0.65%   |
| Jaguar           | 2         | 0.22%   |
| Bulldozer        | 2         | 0.22%   |
| Steamroller      | 1         | 0.11%   |
| Alderlake Hybrid | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 633       | 55.92%  |
| Nvidia                     | 319       | 28.18%  |
| AMD                        | 176       | 15.55%  |
| Matrox Electronics Systems | 3         | 0.27%   |
| ASPEED Technology          | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 54        | 4.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 3.84%   |
| Intel UHD Graphics 620                                                                   | 36        | 3.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 2.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 30        | 2.62%   |
| Intel HD Graphics 630                                                                    | 27        | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 2.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 2.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 2.1%    |
| Intel HD Graphics 620                                                                    | 23        | 2.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 23        | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 1.75%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.75%   |
| Intel HD Graphics 530                                                                    | 20        | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.31%   |
| Intel HD Graphics 500                                                                    | 14        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 1.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 1.05%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 11        | 0.96%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 11        | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 9         | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 9         | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 8         | 0.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.7%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8         | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.61%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 7         | 0.61%   |
| Intel AlderLake-S GT1                                                                    | 7         | 0.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 439       | 47.1%   |
| 1 x Nvidia               | 165       | 17.7%   |
| Intel + Nvidia           | 143       | 15.34%  |
| 1 x AMD                  | 133       | 14.27%  |
| Intel + AMD              | 30        | 3.22%   |
| 2 x AMD                  | 6         | 0.64%   |
| AMD + Nvidia             | 5         | 0.54%   |
| 2 x Nvidia               | 3         | 0.32%   |
| Other                    | 2         | 0.21%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.11%   |
| Nvidia + Matrox          | 1         | 0.11%   |
| 1 x Matrox               | 1         | 0.11%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.11%   |
| 1 x ASPEED               | 1         | 0.11%   |
| AMD + Matrox             | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 890       | 96.01%  |
| Proprietary | 34        | 3.67%   |
| Unknown     | 3         | 0.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 884       | 95.26%  |
| 7.01-8.0   | 10        | 1.08%   |
| 3.01-4.0   | 10        | 1.08%   |
| 1.01-2.0   | 10        | 1.08%   |
| 0.51-1.0   | 5         | 0.54%   |
| 5.01-6.0   | 4         | 0.43%   |
| 16.01-24.0 | 2         | 0.22%   |
| 8.01-16.0  | 2         | 0.22%   |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 148       | 14.7%   |
| AU Optronics            | 124       | 12.31%  |
| BOE                     | 94        | 9.33%   |
| LG Display              | 78        | 7.75%   |
| Chimei Innolux          | 76        | 7.55%   |
| Dell                    | 64        | 6.36%   |
| Goldstar                | 50        | 4.97%   |
| Sharp                   | 36        | 3.57%   |
| Hewlett-Packard         | 31        | 3.08%   |
| Apple                   | 27        | 2.68%   |
| AOC                     | 27        | 2.68%   |
| BenQ                    | 25        | 2.48%   |
| Acer                    | 22        | 2.18%   |
| Ancor Communications    | 21        | 2.09%   |
| PANDA                   | 18        | 1.79%   |
| ViewSonic               | 16        | 1.59%   |
| Philips                 | 15        | 1.49%   |
| Lenovo                  | 11        | 1.09%   |
| ASUSTek Computer        | 9         | 0.89%   |
| MSI                     | 8         | 0.79%   |
| Sony                    | 7         | 0.7%    |
| Chi Mei Optoelectronics | 7         | 0.7%    |
| Hitachi                 | 6         | 0.6%    |
| Toshiba                 | 5         | 0.5%    |
| Panasonic               | 5         | 0.5%    |
| Iiyama                  | 5         | 0.5%    |
| Vizio                   | 4         | 0.4%    |
| LG Electronics          | 4         | 0.4%    |
| InfoVision              | 4         | 0.4%    |
| Unknown                 | 3         | 0.3%    |
| Medion                  | 3         | 0.3%    |
| CSO                     | 3         | 0.3%    |
| Unknown (XXX)           | 2         | 0.2%    |
| Sceptre Tech            | 2         | 0.2%    |
| RTK                     | 2         | 0.2%    |
| NEC Computers           | 2         | 0.2%    |
| MiTAC                   | 2         | 0.2%    |
| Medion Akoya            | 2         | 0.2%    |
| Insignia                | 2         | 0.2%    |
| Gigabyte Technology     | 2         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 6         | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.58%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 6         | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.58%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 5         | 0.48%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                  | 5         | 0.48%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 5         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 4         | 0.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 0.39%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 4         | 0.39%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                  | 4         | 0.39%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 4         | 0.39%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.39%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                    | 4         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 3         | 0.29%   |
| Samsung Electronics U28E510 SAM0D63 3840x2160 610x350mm 27.7-inch        | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch    | 3         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 3         | 0.29%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 3         | 0.29%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 3         | 0.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.29%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 3         | 0.29%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch                 | 3         | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                 | 3         | 0.29%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 3         | 0.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch         | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.29%   |
| BOE LCD Monitor BOE0AF2 2560x1600 302x189mm 14.0-inch                    | 3         | 0.29%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 3         | 0.29%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 447       | 45.52%  |
| 1366x768 (WXGA)    | 185       | 18.84%  |
| 3840x2160 (4K)     | 92        | 9.37%   |
| 2560x1440 (QHD)    | 34        | 3.46%   |
| 1600x900 (HD+)     | 25        | 2.55%   |
| 1920x1200 (WUXGA)  | 22        | 2.24%   |
| 1680x1050 (WSXGA+) | 19        | 1.93%   |
| 1280x1024 (SXGA)   | 18        | 1.83%   |
| 3440x1440          | 17        | 1.73%   |
| 2560x1080          | 15        | 1.53%   |
| 1440x900 (WXGA+)   | 13        | 1.32%   |
| 2560x1600          | 12        | 1.22%   |
| 1280x800 (WXGA)    | 10        | 1.02%   |
| 2880x1800          | 9         | 0.92%   |
| 1360x768           | 8         | 0.81%   |
| 3200x1800 (QHD+)   | 6         | 0.61%   |
| 2160x1440          | 5         | 0.51%   |
| Unknown            | 5         | 0.51%   |
| 3840x1080          | 4         | 0.41%   |
| 3840x2400          | 3         | 0.31%   |
| 2880x1920          | 3         | 0.31%   |
| 1920x540           | 3         | 0.31%   |
| 1024x768 (XGA)     | 3         | 0.31%   |
| 5760x2160          | 2         | 0.2%    |
| 3840x1600          | 2         | 0.2%    |
| 3456x2160          | 2         | 0.2%    |
| 2736x1824          | 2         | 0.2%    |
| 4480x1440          | 1         | 0.1%    |
| 4093x4093          | 1         | 0.1%    |
| 3840x1100          | 1         | 0.1%    |
| 3600x1080          | 1         | 0.1%    |
| 3360x1050          | 1         | 0.1%    |
| 3000x2000          | 1         | 0.1%    |
| 2944x1840          | 1         | 0.1%    |
| 2400x1600          | 1         | 0.1%    |
| 2256x1504          | 1         | 0.1%    |
| 2160x1350          | 1         | 0.1%    |
| 2160x1200          | 1         | 0.1%    |
| 2048x1152          | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 250       | 24.85%  |
| 13      | 106       | 10.54%  |
| 27      | 88        | 8.75%   |
| 24      | 80        | 7.95%   |
| 14      | 71        | 7.06%   |
| 23      | 55        | 5.47%   |
| 21      | 46        | 4.57%   |
| 17      | 37        | 3.68%   |
| 34      | 25        | 2.49%   |
| Unknown | 25        | 2.49%   |
| 11      | 24        | 2.39%   |
| 31      | 23        | 2.29%   |
| 12      | 23        | 2.29%   |
| 84      | 17        | 1.69%   |
| 19      | 16        | 1.59%   |
| 22      | 15        | 1.49%   |
| 18      | 13        | 1.29%   |
| 20      | 12        | 1.19%   |
| 54      | 8         | 0.8%    |
| 26      | 7         | 0.7%    |
| 72      | 6         | 0.6%    |
| 40      | 6         | 0.6%    |
| 16      | 6         | 0.6%    |
| 48      | 5         | 0.5%    |
| 37      | 5         | 0.5%    |
| 25      | 5         | 0.5%    |
| 35      | 4         | 0.4%    |
| 32      | 4         | 0.4%    |
| 52      | 3         | 0.3%    |
| 29      | 3         | 0.3%    |
| 86      | 2         | 0.2%    |
| 55      | 2         | 0.2%    |
| 49      | 2         | 0.2%    |
| 46      | 2         | 0.2%    |
| 43      | 2         | 0.2%    |
| 10      | 2         | 0.2%    |
| 65      | 1         | 0.1%    |
| 57      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 370       | 37.37%  |
| 501-600     | 207       | 20.91%  |
| 201-300     | 114       | 11.52%  |
| 401-500     | 91        | 9.19%   |
| 601-700     | 43        | 4.34%   |
| 351-400     | 42        | 4.24%   |
| 701-800     | 31        | 3.13%   |
| 1001-1500   | 25        | 2.53%   |
| Unknown     | 25        | 2.53%   |
| 1501-2000   | 23        | 2.32%   |
| 801-900     | 16        | 1.62%   |
| 901-1000    | 3         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 742       | 78.94%  |
| 16/10   | 94        | 10%     |
| 21/9    | 33        | 3.51%   |
| 5/4     | 19        | 2.02%   |
| Unknown | 19        | 2.02%   |
| 3/2     | 15        | 1.6%    |
| 4/3     | 7         | 0.74%   |
| 32/9    | 5         | 0.53%   |
| 0.56    | 3         | 0.32%   |
| 3.40    | 1         | 0.11%   |
| 1.96    | 1         | 0.11%   |
| 1.00    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 250       | 24.98%  |
| 201-250        | 158       | 15.78%  |
| 81-90          | 122       | 12.19%  |
| 301-350        | 94        | 9.39%   |
| 351-500        | 58        | 5.79%   |
| 71-80          | 53        | 5.29%   |
| More than 1000 | 41        | 4.1%    |
| 151-200        | 39        | 3.9%    |
| 251-300        | 32        | 3.2%    |
| 51-60          | 25        | 2.5%    |
| 121-130        | 25        | 2.5%    |
| Unknown        | 25        | 2.5%    |
| 61-70          | 23        | 2.3%    |
| 501-1000       | 23        | 2.3%    |
| 141-150        | 22        | 2.2%    |
| 111-120        | 6         | 0.6%    |
| 41-50          | 2         | 0.2%    |
| 91-100         | 2         | 0.2%    |
| 131-140        | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 293       | 30.18%  |
| 121-160       | 265       | 27.29%  |
| 101-120       | 246       | 25.33%  |
| 161-240       | 79        | 8.14%   |
| More than 240 | 32        | 3.3%    |
| 1-50          | 31        | 3.19%   |
| Unknown       | 25        | 2.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 800       | 86.02%  |
| 2     | 115       | 12.37%  |
| 3     | 9         | 0.97%   |
| 0     | 6         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 509       | 37.99%  |
| Realtek Semiconductor             | 450       | 33.58%  |
| Qualcomm Atheros                  | 163       | 12.16%  |
| Broadcom                          | 61        | 4.55%   |
| Broadcom Limited                  | 24        | 1.79%   |
| Ralink Technology                 | 17        | 1.27%   |
| TP-Link                           | 10        | 0.75%   |
| Aquantia                          | 10        | 0.75%   |
| Ralink                            | 7         | 0.52%   |
| Microsoft                         | 7         | 0.52%   |
| Marvell Technology Group          | 7         | 0.52%   |
| Dell                              | 6         | 0.45%   |
| ASUSTek Computer                  | 6         | 0.45%   |
| MediaTek                          | 5         | 0.37%   |
| ASIX Electronics                  | 5         | 0.37%   |
| Xiaomi                            | 4         | 0.3%    |
| Samsung Electronics               | 4         | 0.3%    |
| Qualcomm Atheros Communications   | 4         | 0.3%    |
| Motorola PCS                      | 3         | 0.22%   |
| Huawei Technologies               | 3         | 0.22%   |
| Hewlett-Packard                   | 3         | 0.22%   |
| Edimax Technology                 | 3         | 0.22%   |
| DisplayLink                       | 3         | 0.22%   |
| Apple                             | 3         | 0.22%   |
| Microchip Technology              | 2         | 0.15%   |
| JMicron Technology                | 2         | 0.15%   |
| HMD Global                        | 2         | 0.15%   |
| Google                            | 2         | 0.15%   |
| D-Link                            | 2         | 0.15%   |
| U-Blox                            | 1         | 0.07%   |
| Sierra Wireless                   | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| QinHeng Electronics               | 1         | 0.07%   |
| Nordic Semiconductor ASA          | 1         | 0.07%   |
| Micro Star International          | 1         | 0.07%   |
| Leaflabs                          | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| Ericsson Business Mobile Networks | 1         | 0.07%   |
| Digital Equipment                 | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 302       | 18.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 57        | 3.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 43        | 2.68%   |
| Intel Wi-Fi 6 AX200                                                            | 36        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 35        | 2.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 31        | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 27        | 1.68%   |
| Intel Wireless 8265 / 8275                                                     | 27        | 1.68%   |
| Intel I211 Gigabit Network Connection                                          | 27        | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 26        | 1.62%   |
| Intel Wireless 3165                                                            | 26        | 1.62%   |
| Intel Wireless 8260                                                            | 25        | 1.56%   |
| Intel Wireless 7265                                                            | 25        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24        | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                                | 24        | 1.5%    |
| Intel Ethernet Connection I217-LM                                              | 22        | 1.37%   |
| Intel Ethernet Connection (2) I219-V                                           | 22        | 1.37%   |
| Intel Wireless 7260                                                            | 21        | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 20        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                              | 19        | 1.18%   |
| Intel Ethernet Controller I225-V                                               | 19        | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 17        | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 17        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                           | 16        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 15        | 0.93%   |
| Intel Wi-Fi 6 AX201                                                            | 15        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 15        | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 14        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 14        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 13        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 12        | 0.75%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 11        | 0.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 11        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                          | 11        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 11        | 0.69%   |
| Intel Wireless 3160                                                            | 10        | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 10        | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 10        | 0.62%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 10        | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 389       | 50.13%  |
| Qualcomm Atheros                | 135       | 17.4%   |
| Realtek Semiconductor           | 113       | 14.56%  |
| Broadcom                        | 46        | 5.93%   |
| Broadcom Limited                | 20        | 2.58%   |
| Ralink Technology               | 17        | 2.19%   |
| TP-Link                         | 8         | 1.03%   |
| Ralink                          | 7         | 0.9%    |
| Marvell Technology Group        | 6         | 0.77%   |
| Dell                            | 6         | 0.77%   |
| ASUSTek Computer                | 6         | 0.77%   |
| Microsoft                       | 5         | 0.64%   |
| Qualcomm Atheros Communications | 4         | 0.52%   |
| MediaTek                        | 4         | 0.52%   |
| Edimax Technology               | 3         | 0.39%   |
| D-Link                          | 2         | 0.26%   |
| Sierra Wireless                 | 1         | 0.13%   |
| Qualcomm                        | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |
| AVM                             | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 36        | 4.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 35        | 4.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 31        | 3.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 27        | 3.46%   |
| Intel Wireless 8265 / 8275                                     | 27        | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 26        | 3.33%   |
| Intel Wireless 3165                                            | 26        | 3.33%   |
| Intel Wireless 8260                                            | 25        | 3.2%    |
| Intel Wireless 7265                                            | 25        | 3.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 24        | 3.07%   |
| Intel Wireless 7260                                            | 21        | 2.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17        | 2.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 2.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.92%   |
| Intel Wi-Fi 6 AX201                                            | 15        | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 1.92%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 14        | 1.79%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 12        | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 1.41%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 11        | 1.41%   |
| Intel Wireless 3160                                            | 10        | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 1.28%   |
| Intel Centrino Wireless-N 2230                                 | 9         | 1.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 9         | 1.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 0.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 7         | 0.9%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 0.9%    |
| Ralink MT7601U Wireless Adapter                                | 6         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.77%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 6         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.77%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 0.77%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 6         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 401       | 50.82%  |
| Intel                    | 268       | 33.97%  |
| Qualcomm Atheros         | 42        | 5.32%   |
| Broadcom                 | 27        | 3.42%   |
| Aquantia                 | 10        | 1.27%   |
| ASIX Electronics         | 5         | 0.63%   |
| Xiaomi                   | 4         | 0.51%   |
| Broadcom Limited         | 4         | 0.51%   |
| Samsung Electronics      | 3         | 0.38%   |
| Motorola PCS             | 3         | 0.38%   |
| DisplayLink              | 3         | 0.38%   |
| Apple                    | 3         | 0.38%   |
| TP-Link                  | 2         | 0.25%   |
| Microsoft                | 2         | 0.25%   |
| JMicron Technology       | 2         | 0.25%   |
| HMD Global               | 2         | 0.25%   |
| Google                   | 2         | 0.25%   |
| QinHeng Electronics      | 1         | 0.13%   |
| MediaTek                 | 1         | 0.13%   |
| Marvell Technology Group | 1         | 0.13%   |
| ICS Advent               | 1         | 0.13%   |
| Huawei Technologies      | 1         | 0.13%   |
| Hewlett-Packard          | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 302       | 37.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 57        | 7.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 43        | 5.3%    |
| Intel I211 Gigabit Network Connection                                          | 27        | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 24        | 2.96%   |
| Intel Ethernet Connection I217-LM                                              | 22        | 2.71%   |
| Intel Ethernet Connection (2) I219-V                                           | 22        | 2.71%   |
| Realtek RTL8125 2.5GbE Controller                                              | 19        | 2.34%   |
| Intel Ethernet Controller I225-V                                               | 19        | 2.34%   |
| Intel Ethernet Connection (7) I219-V                                           | 16        | 1.97%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 1.48%   |
| Intel Ethernet Connection (2) I219-LM                                          | 11        | 1.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 11        | 1.36%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 10        | 1.23%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 1.11%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 8         | 0.99%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 0.86%   |
| Intel I210 Gigabit Network Connection                                          | 7         | 0.86%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.74%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 0.74%   |
| Intel Ethernet Connection (10) I219-V                                          | 6         | 0.74%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 0.62%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 0.49%   |
| Intel Ethernet Connection I219-V                                               | 4         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                           | 4         | 0.49%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 4         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 0.37%   |
| Motorola PCS moto g play - 2023                                                | 3         | 0.37%   |
| Intel I350 Gigabit Network Connection                                          | 3         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 749       | 50.2%   |
| WiFi     | 730       | 48.93%  |
| Modem    | 12        | 0.8%    |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 537       | 56.11%  |
| Ethernet | 420       | 43.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 483       | 51.99%  |
| 1     | 385       | 41.44%  |
| 3     | 31        | 3.34%   |
| 0     | 21        | 2.26%   |
| 4     | 5         | 0.54%   |
| 5     | 4         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 789       | 84.75%  |
| Yes  | 142       | 15.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 342       | 53.19%  |
| Qualcomm Atheros Communications | 63        | 9.8%    |
| Realtek Semiconductor           | 57        | 8.86%   |
| Cambridge Silicon Radio         | 31        | 4.82%   |
| Apple                           | 30        | 4.67%   |
| Broadcom                        | 25        | 3.89%   |
| Lite-On Technology              | 22        | 3.42%   |
| IMC Networks                    | 18        | 2.8%    |
| Foxconn / Hon Hai               | 15        | 2.33%   |
| ASUSTek Computer                | 7         | 1.09%   |
| Marvell Semiconductor           | 6         | 0.93%   |
| Realtek                         | 3         | 0.47%   |
| MediaTek                        | 3         | 0.47%   |
| Hewlett-Packard                 | 3         | 0.47%   |
| Foxconn International           | 3         | 0.47%   |
| TP-Link                         | 2         | 0.31%   |
| Toshiba                         | 2         | 0.31%   |
| Ralink                          | 2         | 0.31%   |
| HTC (High Tech Computer)        | 2         | 0.31%   |
| USI                             | 1         | 0.16%   |
| Micro Star International        | 1         | 0.16%   |
| Edimax Technology               | 1         | 0.16%   |
| Dell                            | 1         | 0.16%   |
| Creative Technology             | 1         | 0.16%   |
| Belkin Components               | 1         | 0.16%   |
| Alps Electric                   | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 136       | 21.15%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 64        | 9.95%   |
| Intel AX201 Bluetooth                               | 54        | 8.4%    |
| Intel AX200 Bluetooth                               | 35        | 5.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 32        | 4.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 4.82%   |
| Realtek Bluetooth Radio                             | 25        | 3.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 24        | 3.73%   |
| Apple Bluetooth Host Controller                     | 19        | 2.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 13        | 2.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.87%   |
| Intel AX210 Bluetooth                               | 10        | 1.56%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.4%    |
| Apple Bluetooth USB Host Controller                 | 9         | 1.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 1.24%   |
| Intel AX211 Bluetooth                               | 8         | 1.24%   |
| IMC Networks Bluetooth Device                       | 7         | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.62%   |
| Marvell Bluetooth and Wireless LAN Composite        | 4         | 0.62%   |
| Lite-On Bluetooth Device                            | 4         | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.62%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.62%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.47%   |
| Realtek Bluetooth Radio                             | 3         | 0.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.47%   |
| MediaTek Wireless_Device                            | 3         | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.47%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.47%   |
| Broadcom BCM20702A0                                 | 3         | 0.47%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2         | 0.31%   |
| Toshiba BCM43142A0                                  | 2         | 0.31%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 759       | 59.53%  |
| Nvidia                               | 218       | 17.1%   |
| AMD                                  | 187       | 14.67%  |
| C-Media Electronics                  | 16        | 1.25%   |
| Logitech                             | 10        | 0.78%   |
| ASUSTek Computer                     | 9         | 0.71%   |
| JMTek                                | 5         | 0.39%   |
| SteelSeries ApS                      | 4         | 0.31%   |
| Micro Star International             | 4         | 0.31%   |
| Creative Technology                  | 4         | 0.31%   |
| Creative Labs                        | 4         | 0.31%   |
| ASRock                               | 4         | 0.31%   |
| Plantronics                          | 3         | 0.24%   |
| KORG                                 | 3         | 0.24%   |
| Corsair                              | 3         | 0.24%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.16%   |
| Realtek Semiconductor                | 2         | 0.16%   |
| JBL                                  | 2         | 0.16%   |
| GN Netcom                            | 2         | 0.16%   |
| Generalplus Technology               | 2         | 0.16%   |
| Blue Microphones                     | 2         | 0.16%   |
| Yamaha                               | 1         | 0.08%   |
| VIA Technologies                     | 1         | 0.08%   |
| Turtle Beach                         | 1         | 0.08%   |
| Texas Instruments                    | 1         | 0.08%   |
| TEAC                                 | 1         | 0.08%   |
| Sony                                 | 1         | 0.08%   |
| Sennheiser Communications            | 1         | 0.08%   |
| Schiit Audio                         | 1         | 0.08%   |
| Samsung Electronics                  | 1         | 0.08%   |
| PreSonus Audio Electronics           | 1         | 0.08%   |
| MAG Technology                       | 1         | 0.08%   |
| Kingston Technology                  | 1         | 0.08%   |
| GYROCOM C&C                          | 1         | 0.08%   |
| Guillemot                            | 1         | 0.08%   |
| Giga-Byte Technology                 | 1         | 0.08%   |
| Focusrite-Novation                   | 1         | 0.08%   |
| DSEA A/S                             | 1         | 0.08%   |
| Dell                                 | 1         | 0.08%   |
| Cooler Master                        | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 97        | 6.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 89        | 6.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 59        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 54        | 3.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 49        | 3.32%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 47        | 3.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 41        | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 40        | 2.71%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 37        | 2.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 33        | 2.24%   |
| Intel 8 Series HD Audio Controller                                                                | 33        | 2.24%   |
| Intel Broadwell-U Audio Controller                                                                | 31        | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 31        | 2.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 2.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 1.83%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 25        | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 1.63%   |
| Intel 200 Series PCH HD Audio                                                                     | 24        | 1.63%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 23        | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 20        | 1.36%   |
| Intel CM238 HD Audio Controller                                                                   | 20        | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 20        | 1.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 19        | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 19        | 1.29%   |
| AMD FCH Azalia Controller                                                                         | 17        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 1.02%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 14        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 12        | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 11        | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 11        | 0.75%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 11        | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 10        | 0.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 25%     |
| SK hynix            | 8         | 22.22%  |
| Corsair             | 5         | 13.89%  |
| Unknown             | 4         | 11.11%  |
| Micron Technology   | 2         | 5.56%   |
| Kingston            | 2         | 5.56%   |
| Goldkey             | 2         | 5.56%   |
| Crucial             | 2         | 5.56%   |
| Unknown (ABCD)      | 1         | 2.78%   |
| A-DATA Technology   | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH400SO51208-1333 4GB DIMM DDR3 1333MT/s            | 2         | 5.41%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.7%    |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                   | 1         | 2.7%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 2.7%    |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s        | 1         | 2.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 2.7%    |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 2.7%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 2.7%    |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.7%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.7%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.7%    |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.7%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 2.7%    |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1333MT/s            | 1         | 2.7%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Samsung RAM M471A2G44AM0-CTD 16GB Row Of Chips DDR4 2667MT/s     | 1         | 2.7%    |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s          | 1         | 2.7%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.7%    |
| Micron RAM MT53E512M32D2NP 1GB LPDDR4 3733MT/s                   | 1         | 2.7%    |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 2.7%    |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                 | 1         | 2.7%    |
| Kingston RAM 99U5428-101.A00LF 8GB DIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s            | 1         | 2.7%    |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Corsair RAM CMY32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s             | 1         | 2.7%    |
| Corsair RAM CMSX16GX4M1A2400C16 16GB SODIMM DDR4 2400MT/s        | 1         | 2.7%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 1         | 2.7%    |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s            | 1         | 2.7%    |
| Corsair RAM CM4X16GC3000C15K4 16GB DIMM DDR4 3000MT/s            | 1         | 2.7%    |
| A-DATA RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 41.18%  |
| DDR3   | 13        | 38.24%  |
| LPDDR4 | 3         | 8.82%   |
| LPDDR3 | 2         | 5.88%   |
| SDRAM  | 1         | 2.94%   |
| DDR5   | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 54.55%  |
| DIMM         | 10        | 30.3%   |
| Row Of Chips | 4         | 12.12%  |
| Unknown      | 1         | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 38.24%  |
| 4096  | 12        | 35.29%  |
| 16384 | 7         | 20.59%  |
| 2048  | 2         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 9         | 25%     |
| 2667  | 7         | 19.44%  |
| 2400  | 4         | 11.11%  |
| 1333  | 3         | 8.33%   |
| 5600  | 1         | 2.78%   |
| 4267  | 1         | 2.78%   |
| 4199  | 1         | 2.78%   |
| 3733  | 1         | 2.78%   |
| 3600  | 1         | 2.78%   |
| 3200  | 1         | 2.78%   |
| 3000  | 1         | 2.78%   |
| 2933  | 1         | 2.78%   |
| 2800  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 1867  | 1         | 2.78%   |
| 1800  | 1         | 2.78%   |
| 1334  | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 8         | 28.57%  |
| Hewlett-Packard     | 7         | 25%     |
| Seiko Epson         | 4         | 14.29%  |
| Samsung Electronics | 3         | 10.71%  |
| Brother Industries  | 2         | 7.14%   |
| Ricoh               | 1         | 3.57%   |
| MIIIW               | 1         | 3.57%   |
| Kyocera             | 1         | 3.57%   |
| Dymo-CoStar         | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series            | 3         | 10.71%  |
| Seiko Epson L360 Series              | 2         | 7.14%   |
| Seiko Epson L355 Series              | 1         | 3.57%   |
| Seiko Epson L3150 Series             | 1         | 3.57%   |
| Samsung SCX-4216F Scanner            | 1         | 3.57%   |
| Samsung SCX-4200 series              | 1         | 3.57%   |
| Samsung ML-1640 Series Laser Printer | 1         | 3.57%   |
| Ricoh Printing Support               | 1         | 3.57%   |
| MIIIW MW Keyboard Air Mini           | 1         | 3.57%   |
| Kyocera FS-1030D printer             | 1         | 3.57%   |
| HP LaserJet 1200                     | 1         | 3.57%   |
| HP HP Laser 107w                     | 1         | 3.57%   |
| HP ENVY Pro 6400 series              | 1         | 3.57%   |
| HP ENVY 6000 series                  | 1         | 3.57%   |
| HP ENVY 4520 series                  | 1         | 3.57%   |
| HP Deskjet 3520 series               | 1         | 3.57%   |
| HP Deskjet 2540 series               | 1         | 3.57%   |
| Dymo-CoStar DYMO LabelWriter 4XL     | 1         | 3.57%   |
| Canon PIXMA MG3600 Series            | 1         | 3.57%   |
| Canon MF3010                         | 1         | 3.57%   |
| Canon LBP6000                        | 1         | 3.57%   |
| Canon iP2700 series                  | 1         | 3.57%   |
| Canon G3010 series                   | 1         | 3.57%   |
| Brother HL-L2310D series             | 1         | 3.57%   |
| Brother HL-2240D series              | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP ScanJet 6200c                   | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan 8800F               | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 117       | 21.99%  |
| Realtek Semiconductor                  | 51        | 9.59%   |
| Microdia                               | 48        | 9.02%   |
| IMC Networks                           | 42        | 7.89%   |
| Sunplus Innovation Technology          | 40        | 7.52%   |
| Bison Electronics                      | 31        | 5.83%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 4.14%   |
| Quanta                                 | 21        | 3.95%   |
| Apple                                  | 20        | 3.76%   |
| Logitech                               | 19        | 3.57%   |
| Suyin                                  | 13        | 2.44%   |
| Silicon Motion                         | 11        | 2.07%   |
| Syntek                                 | 10        | 1.88%   |
| Microsoft                              | 10        | 1.88%   |
| Alcor Micro                            | 10        | 1.88%   |
| Acer                                   | 10        | 1.88%   |
| Lite-On Technology                     | 8         | 1.5%    |
| Samsung Electronics                    | 6         | 1.13%   |
| Luxvisions Innotech Limited            | 5         | 0.94%   |
| KYE Systems (Mouse Systems)            | 3         | 0.56%   |
| ARC International                      | 3         | 0.56%   |
| Z-Star Microelectronics                | 2         | 0.38%   |
| Unknown                                | 2         | 0.38%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.38%   |
| Ricoh                                  | 2         | 0.38%   |
| Hewlett-Packard                        | 2         | 0.38%   |
| Creative Technology                    | 2         | 0.38%   |
| YGTek                                  | 1         | 0.19%   |
| Y Media                                | 1         | 0.19%   |
| Xiaomi                                 | 1         | 0.19%   |
| Tobii Technology AB                    | 1         | 0.19%   |
| SunplusIT                              | 1         | 0.19%   |
| Spreadtrum Communications              | 1         | 0.19%   |
| Primax Electronics                     | 1         | 0.19%   |
| Magic Control Technology               | 1         | 0.19%   |
| lihappe8                               | 1         | 0.19%   |
| Lenovo                                 | 1         | 0.19%   |
| Importek                               | 1         | 0.19%   |
| icSpring                               | 1         | 0.19%   |
| Genesys Logic                          | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 28        | 5.19%   |
| Chicony HD WebCam                                              | 19        | 3.52%   |
| Chicony Integrated Camera                                      | 18        | 3.33%   |
| Realtek Integrated_Webcam_HD                                   | 17        | 3.15%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 14        | 2.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 11        | 2.04%   |
| Sunplus HD WebCam                                              | 9         | 1.67%   |
| Bison Integrated Camera                                        | 9         | 1.67%   |
| Apple FaceTime HD Camera                                       | 8         | 1.48%   |
| Logitech Webcam C270                                           | 7         | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam                                  | 7         | 1.3%    |
| Apple FaceTime HD Camera (Built-in)                            | 7         | 1.3%    |
| Sunplus Integrated_Webcam_HD                                   | 6         | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 6         | 1.11%   |
| Chicony Lenovo EasyCamera                                      | 6         | 1.11%   |
| Bison EasyCamera                                               | 6         | 1.11%   |
| Suyin HP TrueVision HD                                         | 5         | 0.93%   |
| Realtek Lenovo EasyCamera                                      | 5         | 0.93%   |
| Quanta HD Webcam                                               | 5         | 0.93%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 5         | 0.93%   |
| Chicony VGA Webcam                                             | 5         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 5         | 0.93%   |
| Bison HD Webcam                                                | 5         | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                             | 5         | 0.93%   |
| Alcor Micro USB 2.0 Camera                                     | 5         | 0.93%   |
| Syntek EasyCamera                                              | 4         | 0.74%   |
| Microdia Integrated Webcam HD                                  | 4         | 0.74%   |
| Logitech HD Pro Webcam C920                                    | 4         | 0.74%   |
| Lite-On Integrated Camera                                      | 4         | 0.74%   |
| IMC Networks Integrated Camera                                 | 4         | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 0.74%   |
| Chicony USB 2.0 Camera                                         | 4         | 0.74%   |
| Chicony HP Webcam [2 MP Macro]                                 | 4         | 0.74%   |
| Chicony HP HD Camera                                           | 4         | 0.74%   |
| Chicony FJ Camera                                              | 4         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.74%   |
| Bison Lenovo EasyCamera                                        | 4         | 0.74%   |
| Alcor Micro USB 2.0 PC Camera                                  | 4         | 0.74%   |
| Suyin HD WebCam                                                | 3         | 0.56%   |
| Sunplus XiaoMi USB 2.0 Webcam                                  | 3         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 39.68%  |
| Synaptics                  | 13        | 20.63%  |
| Elan Microelectronics      | 6         | 9.52%   |
| Shenzhen Goodix Technology | 5         | 7.94%   |
| AuthenTec                  | 5         | 7.94%   |
| LighTuning Technology      | 4         | 6.35%   |
| Upek                       | 3         | 4.76%   |
| Samsung Electronics        | 2         | 3.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 12.7%   |
| Elan ELAN:Fingerprint                                                      | 6         | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 7.94%   |
| Synaptics UWP WBDI                                                         | 4         | 6.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 6.35%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 4.76%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 4.76%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.17%   |
| Validity Sensors VFS491                                                    | 2         | 3.17%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 3.17%   |
| Samsung Fingerprint Device                                                 | 2         | 3.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.17%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.59%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.59%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.59%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 1.59%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.59%   |
| Synaptics  WBDI                                                            | 1         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.59%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.59%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.59%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.59%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 16        | 53.33%  |
| Alcor Micro                | 5         | 16.67%  |
| Upek                       | 4         | 13.33%  |
| Lenovo                     | 1         | 3.33%   |
| Gemalto (was Gemplus)      | 1         | 3.33%   |
| Athena Smartcard Solutions | 1         | 3.33%   |
| Aladdin Knowledge Systems  | 1         | 3.33%   |
| Advanced Card Systems      | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 20%     |
| Broadcom 5880                                                                | 5         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 13.33%  |
| Broadcom 58200                                                               | 3         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.33%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.33%   |
| Athena Smartcard Solutions ASEDrive V3C                                      | 1         | 3.33%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 3.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 621       | 65.78%  |
| 1     | 267       | 28.28%  |
| 2     | 50        | 5.3%    |
| 3     | 6         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 75        | 19.33%  |
| Net/wireless             | 65        | 16.75%  |
| Fingerprint reader       | 63        | 16.24%  |
| Multimedia controller    | 41        | 10.57%  |
| Firewire controller      | 35        | 9.02%   |
| Chipcard                 | 30        | 7.73%   |
| Net/ethernet             | 14        | 3.61%   |
| Unassigned class         | 11        | 2.84%   |
| Sound                    | 11        | 2.84%   |
| Storage/ide              | 10        | 2.58%   |
| Camera                   | 10        | 2.58%   |
| Communication controller | 8         | 2.06%   |
| Bluetooth                | 4         | 1.03%   |
| Network                  | 3         | 0.77%   |
| Modem                    | 3         | 0.77%   |
| Storage/nvme             | 2         | 0.52%   |
| Storage                  | 2         | 0.52%   |
| Card reader              | 1         | 0.26%   |

