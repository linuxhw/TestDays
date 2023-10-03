Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 10613

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | G7 7700                     | Notebook    | [62bd529b36](https://linux-hardware.org/?probe=62bd529b36) | Oct 01, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [5479e52948](https://linux-hardware.org/?probe=5479e52948) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1dc06a927c](https://linux-hardware.org/?probe=1dc06a927c) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| MSI           | B560M PRO                   | Desktop     | [ce2f5b7349](https://linux-hardware.org/?probe=ce2f5b7349) | Sep 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [29617a5db5](https://linux-hardware.org/?probe=29617a5db5) | Sep 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [e55a394d41](https://linux-hardware.org/?probe=e55a394d41) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F60097US    | Notebook    | [607d788fde](https://linux-hardware.org/?probe=607d788fde) | Sep 28, 2023 |
| Acer          | Aspire ES1-732              | Notebook    | [f30d62d67b](https://linux-hardware.org/?probe=f30d62d67b) | Sep 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [4c1a2e1e21](https://linux-hardware.org/?probe=4c1a2e1e21) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [3ee705f2f3](https://linux-hardware.org/?probe=3ee705f2f3) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [2b86c9fac4](https://linux-hardware.org/?probe=2b86c9fac4) | Sep 28, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [9d767beb12](https://linux-hardware.org/?probe=9d767beb12) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [7ed50e5e43](https://linux-hardware.org/?probe=7ed50e5e43) | Sep 27, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [0dcef3e6c3](https://linux-hardware.org/?probe=0dcef3e6c3) | Sep 27, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7cfa1007ee](https://linux-hardware.org/?probe=7cfa1007ee) | Sep 27, 2023 |
| Dell          | Inspiron N5040              | Notebook    | [c48d158b62](https://linux-hardware.org/?probe=c48d158b62) | Sep 27, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [84ad07c3f9](https://linux-hardware.org/?probe=84ad07c3f9) | Sep 27, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a9c8158139](https://linux-hardware.org/?probe=a9c8158139) | Sep 27, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| Google        | Blorb                       | Notebook    | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [124f7a0f29](https://linux-hardware.org/?probe=124f7a0f29) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [65369ae480](https://linux-hardware.org/?probe=65369ae480) | Sep 25, 2023 |
| HP            | 8949 11                     | Desktop     | [acb62cff2b](https://linux-hardware.org/?probe=acb62cff2b) | Sep 25, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [381be3d212](https://linux-hardware.org/?probe=381be3d212) | Sep 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [508cf38973](https://linux-hardware.org/?probe=508cf38973) | Sep 24, 2023 |
| HP            | ENVY m4                     | Notebook    | [8d7da36940](https://linux-hardware.org/?probe=8d7da36940) | Sep 24, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [4fb741bdb3](https://linux-hardware.org/?probe=4fb741bdb3) | Sep 23, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [c970ee5a12](https://linux-hardware.org/?probe=c970ee5a12) | Sep 23, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [fbeac0cab4](https://linux-hardware.org/?probe=fbeac0cab4) | Sep 23, 2023 |
| HP            | 8055                        | Desktop     | [d8ea4bc33a](https://linux-hardware.org/?probe=d8ea4bc33a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [537e551c45](https://linux-hardware.org/?probe=537e551c45) | Sep 23, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [14d87bfb5d](https://linux-hardware.org/?probe=14d87bfb5d) | Sep 22, 2023 |
| Lenovo        | IdeaPad Flex-14IWL 81SQ     | Convertible | [480d8732d2](https://linux-hardware.org/?probe=480d8732d2) | Sep 22, 2023 |
| Lenovo        | IdeaPad Flex-14IWL 81SQ     | Convertible | [28af4771b9](https://linux-hardware.org/?probe=28af4771b9) | Sep 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a9f9ccb4f9](https://linux-hardware.org/?probe=a9f9ccb4f9) | Sep 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c2c49834e5](https://linux-hardware.org/?probe=c2c49834e5) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [8b39e51416](https://linux-hardware.org/?probe=8b39e51416) | Sep 21, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c2d2a28c33](https://linux-hardware.org/?probe=c2d2a28c33) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ae7455bac3](https://linux-hardware.org/?probe=ae7455bac3) | Sep 21, 2023 |
| Dell          | Precision 7520              | Notebook    | [2fd68ca236](https://linux-hardware.org/?probe=2fd68ca236) | Sep 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [816502caea](https://linux-hardware.org/?probe=816502caea) | Sep 21, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [b449a82c4f](https://linux-hardware.org/?probe=b449a82c4f) | Sep 21, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [66262df4c4](https://linux-hardware.org/?probe=66262df4c4) | Sep 21, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [192f065f70](https://linux-hardware.org/?probe=192f065f70) | Sep 21, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [063f211c4d](https://linux-hardware.org/?probe=063f211c4d) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6337af2f4c](https://linux-hardware.org/?probe=6337af2f4c) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [dde4d0b10f](https://linux-hardware.org/?probe=dde4d0b10f) | Sep 20, 2023 |
| ASUSTek       | Z450UA                      | Notebook    | [60d85e59da](https://linux-hardware.org/?probe=60d85e59da) | Sep 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [00c6b8cced](https://linux-hardware.org/?probe=00c6b8cced) | Sep 20, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [01d8f27500](https://linux-hardware.org/?probe=01d8f27500) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d8305c7c45](https://linux-hardware.org/?probe=d8305c7c45) | Sep 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0H200    | Notebook    | [c38151f281](https://linux-hardware.org/?probe=c38151f281) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7ff48f538f](https://linux-hardware.org/?probe=7ff48f538f) | Sep 19, 2023 |
| HP            | 212B                        | Desktop     | [1d71ef5e64](https://linux-hardware.org/?probe=1d71ef5e64) | Sep 19, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6088e9b2fa](https://linux-hardware.org/?probe=6088e9b2fa) | Sep 19, 2023 |
| HP            | 3047h                       | Desktop     | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [286398db3c](https://linux-hardware.org/?probe=286398db3c) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ad024119be](https://linux-hardware.org/?probe=ad024119be) | Sep 19, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c2cd300139](https://linux-hardware.org/?probe=c2cd300139) | Sep 19, 2023 |
| Microsoft     | Surface Pro 2               | Tablet      | [6b14cbf5b9](https://linux-hardware.org/?probe=6b14cbf5b9) | Sep 18, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [19e013b8e8](https://linux-hardware.org/?probe=19e013b8e8) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [75f2d2b31d](https://linux-hardware.org/?probe=75f2d2b31d) | Sep 18, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [7b293fe65e](https://linux-hardware.org/?probe=7b293fe65e) | Sep 18, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [e517de2d8f](https://linux-hardware.org/?probe=e517de2d8f) | Sep 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [78535377d6](https://linux-hardware.org/?probe=78535377d6) | Sep 18, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [15dd923faa](https://linux-hardware.org/?probe=15dd923faa) | Sep 17, 2023 |
| HP            | 212B                        | Desktop     | [a041c8b5a9](https://linux-hardware.org/?probe=a041c8b5a9) | Sep 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [10709d2c51](https://linux-hardware.org/?probe=10709d2c51) | Sep 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [a25ee31882](https://linux-hardware.org/?probe=a25ee31882) | Sep 17, 2023 |
| Lenovo        | 3181 NO DPK                 | Mini pc     | [53531ff3b6](https://linux-hardware.org/?probe=53531ff3b6) | Sep 17, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [1398fa87b2](https://linux-hardware.org/?probe=1398fa87b2) | Sep 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b8459514db](https://linux-hardware.org/?probe=b8459514db) | Sep 17, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [8db77afc82](https://linux-hardware.org/?probe=8db77afc82) | Sep 17, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [2e5c8bb8ed](https://linux-hardware.org/?probe=2e5c8bb8ed) | Sep 17, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [0ebcb848ff](https://linux-hardware.org/?probe=0ebcb848ff) | Sep 16, 2023 |
| HP            | 3647h                       | Desktop     | [89c406366a](https://linux-hardware.org/?probe=89c406366a) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b7ff5a9cf2](https://linux-hardware.org/?probe=b7ff5a9cf2) | Sep 16, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [a6d51b9c90](https://linux-hardware.org/?probe=a6d51b9c90) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [c40357b67a](https://linux-hardware.org/?probe=c40357b67a) | Sep 16, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [cbc5e29bf6](https://linux-hardware.org/?probe=cbc5e29bf6) | Sep 16, 2023 |
| Biostar       | X370GTN                     | Desktop     | [1ac44acadd](https://linux-hardware.org/?probe=1ac44acadd) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [567443136d](https://linux-hardware.org/?probe=567443136d) | Sep 15, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [4d35879250](https://linux-hardware.org/?probe=4d35879250) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [2073aca95d](https://linux-hardware.org/?probe=2073aca95d) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [fa484cf261](https://linux-hardware.org/?probe=fa484cf261) | Sep 15, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [4d0eb9b8d2](https://linux-hardware.org/?probe=4d0eb9b8d2) | Sep 15, 2023 |
| MSI           | PRO B660M-B DDR4            | Desktop     | [9463a6f106](https://linux-hardware.org/?probe=9463a6f106) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [43f6a3bfc1](https://linux-hardware.org/?probe=43f6a3bfc1) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [dcd2b90824](https://linux-hardware.org/?probe=dcd2b90824) | Sep 14, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [ba15fb6ed7](https://linux-hardware.org/?probe=ba15fb6ed7) | Sep 14, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [5d79965e45](https://linux-hardware.org/?probe=5d79965e45) | Sep 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1703cfdd5e](https://linux-hardware.org/?probe=1703cfdd5e) | Sep 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7769de42b0](https://linux-hardware.org/?probe=7769de42b0) | Sep 13, 2023 |
| HP            | 0A60h                       | Desktop     | [107f849e6b](https://linux-hardware.org/?probe=107f849e6b) | Sep 13, 2023 |
| Dell          | Latitude 7410               | Notebook    | [59abc2d869](https://linux-hardware.org/?probe=59abc2d869) | Sep 12, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | Notebook    | [9506117d6f](https://linux-hardware.org/?probe=9506117d6f) | Sep 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c6f2b822c7](https://linux-hardware.org/?probe=c6f2b822c7) | Sep 12, 2023 |
| HP            | 870C                        | Desktop     | [3de222afdb](https://linux-hardware.org/?probe=3de222afdb) | Sep 12, 2023 |
| HP            | 620                         | Notebook    | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6a7ee91a3f](https://linux-hardware.org/?probe=6a7ee91a3f) | Sep 11, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [3859055e8d](https://linux-hardware.org/?probe=3859055e8d) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0ac203a0c5](https://linux-hardware.org/?probe=0ac203a0c5) | Sep 11, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [667560b69c](https://linux-hardware.org/?probe=667560b69c) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [793d3e47ff](https://linux-hardware.org/?probe=793d3e47ff) | Sep 10, 2023 |
| Toshiba       | Satellite M645              | Notebook    | [40c02e9bc9](https://linux-hardware.org/?probe=40c02e9bc9) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [6b9804a536](https://linux-hardware.org/?probe=6b9804a536) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [d824341957](https://linux-hardware.org/?probe=d824341957) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3021f551f4](https://linux-hardware.org/?probe=3021f551f4) | Sep 09, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [6e5224fa1d](https://linux-hardware.org/?probe=6e5224fa1d) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3f937bad2e](https://linux-hardware.org/?probe=3f937bad2e) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [1474c70336](https://linux-hardware.org/?probe=1474c70336) | Sep 09, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [524bbba65a](https://linux-hardware.org/?probe=524bbba65a) | Sep 09, 2023 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [11e5581873](https://linux-hardware.org/?probe=11e5581873) | Sep 08, 2023 |
| HP            | 2B36                        | Desktop     | [20552523c6](https://linux-hardware.org/?probe=20552523c6) | Sep 08, 2023 |
| HP            | 339A                        | Desktop     | [4ba272aaf9](https://linux-hardware.org/?probe=4ba272aaf9) | Sep 08, 2023 |
| HP            | 2B36                        | Desktop     | [7697b6ff27](https://linux-hardware.org/?probe=7697b6ff27) | Sep 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [480df18bcb](https://linux-hardware.org/?probe=480df18bcb) | Sep 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b5ea617856](https://linux-hardware.org/?probe=b5ea617856) | Sep 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [d35d89339d](https://linux-hardware.org/?probe=d35d89339d) | Sep 08, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | Notebook    | [650c9dbdd3](https://linux-hardware.org/?probe=650c9dbdd3) | Sep 07, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7cbd11709c](https://linux-hardware.org/?probe=7cbd11709c) | Sep 07, 2023 |
| MSI           | B360M GAMING PLUS           | Desktop     | [1faaa87b61](https://linux-hardware.org/?probe=1faaa87b61) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [699fb7e97e](https://linux-hardware.org/?probe=699fb7e97e) | Sep 07, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [84368e642c](https://linux-hardware.org/?probe=84368e642c) | Sep 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9e7c97275d](https://linux-hardware.org/?probe=9e7c97275d) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [04d60f1b2d](https://linux-hardware.org/?probe=04d60f1b2d) | Sep 06, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [68fe74d684](https://linux-hardware.org/?probe=68fe74d684) | Sep 06, 2023 |
| HP            | 1905                        | Desktop     | [e0da3a1a45](https://linux-hardware.org/?probe=e0da3a1a45) | Sep 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [6c4c9936b0](https://linux-hardware.org/?probe=6c4c9936b0) | Sep 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [4a5a98638e](https://linux-hardware.org/?probe=4a5a98638e) | Sep 06, 2023 |
| ASRock        | Z690 PG Velocita            | Desktop     | [0064d9d9e2](https://linux-hardware.org/?probe=0064d9d9e2) | Sep 06, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [89ce951011](https://linux-hardware.org/?probe=89ce951011) | Sep 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0f5597eb7e](https://linux-hardware.org/?probe=0f5597eb7e) | Sep 05, 2023 |
| MSI           | MS-B0A81                    | Desktop     | [2c4cc9e78f](https://linux-hardware.org/?probe=2c4cc9e78f) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [945acb9ea2](https://linux-hardware.org/?probe=945acb9ea2) | Sep 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [24a7c8a496](https://linux-hardware.org/?probe=24a7c8a496) | Sep 04, 2023 |
| Chuwi         | MiniBook X                  | Convertible | [a298625ea9](https://linux-hardware.org/?probe=a298625ea9) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [d7b4b0f2f1](https://linux-hardware.org/?probe=d7b4b0f2f1) | Sep 04, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [590b5224d9](https://linux-hardware.org/?probe=590b5224d9) | Sep 04, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [80f9f3915b](https://linux-hardware.org/?probe=80f9f3915b) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [908a64b09a](https://linux-hardware.org/?probe=908a64b09a) | Sep 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [8146fce36b](https://linux-hardware.org/?probe=8146fce36b) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [7ebd20a049](https://linux-hardware.org/?probe=7ebd20a049) | Sep 03, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [4ee783a52f](https://linux-hardware.org/?probe=4ee783a52f) | Sep 03, 2023 |
| Notebook      | NK50S5_SZ                   | Notebook    | [f0718be353](https://linux-hardware.org/?probe=f0718be353) | Sep 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [49101faf53](https://linux-hardware.org/?probe=49101faf53) | Sep 02, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [e446721809](https://linux-hardware.org/?probe=e446721809) | Sep 02, 2023 |
| Biostar       | A320MH                      | Desktop     | [8791e4dd20](https://linux-hardware.org/?probe=8791e4dd20) | Sep 02, 2023 |
| Google        | Galtic                      | Notebook    | [e9ccd3a286](https://linux-hardware.org/?probe=e9ccd3a286) | Sep 01, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [a19ece12f0](https://linux-hardware.org/?probe=a19ece12f0) | Sep 01, 2023 |
| HP            | 82F1                        | Desktop     | [6fca2da71a](https://linux-hardware.org/?probe=6fca2da71a) | Sep 01, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [1cb91dff9e](https://linux-hardware.org/?probe=1cb91dff9e) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [e9f211faf1](https://linux-hardware.org/?probe=e9f211faf1) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b1a3900bdd](https://linux-hardware.org/?probe=b1a3900bdd) | Sep 01, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42eb5f3ad4](https://linux-hardware.org/?probe=42eb5f3ad4) | Aug 31, 2023 |
| BANGHO        | GM-15Z12 RTX3060 i7         | Notebook    | [4e77460452](https://linux-hardware.org/?probe=4e77460452) | Aug 31, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [0e6c0b300b](https://linux-hardware.org/?probe=0e6c0b300b) | Aug 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [88b6c0365c](https://linux-hardware.org/?probe=88b6c0365c) | Aug 31, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | Notebook    | [a5fd9c62e8](https://linux-hardware.org/?probe=a5fd9c62e8) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bec8171350](https://linux-hardware.org/?probe=bec8171350) | Aug 30, 2023 |
| Dell          | 07KY25 A00                  | Desktop     | [9346896df5](https://linux-hardware.org/?probe=9346896df5) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [c9fa671277](https://linux-hardware.org/?probe=c9fa671277) | Aug 29, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [071fa35482](https://linux-hardware.org/?probe=071fa35482) | Aug 29, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [4a38e28073](https://linux-hardware.org/?probe=4a38e28073) | Aug 29, 2023 |
| GPD           | G1619-01                    | Notebook    | [0e12028a4d](https://linux-hardware.org/?probe=0e12028a4d) | Aug 28, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [d0453c59f5](https://linux-hardware.org/?probe=d0453c59f5) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [efc8be8369](https://linux-hardware.org/?probe=efc8be8369) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [85640356ad](https://linux-hardware.org/?probe=85640356ad) | Aug 28, 2023 |
| MSI           | 970A-G46                    | Desktop     | [5b4c3411dc](https://linux-hardware.org/?probe=5b4c3411dc) | Aug 28, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [db36b0429d](https://linux-hardware.org/?probe=db36b0429d) | Aug 27, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [2d9703804d](https://linux-hardware.org/?probe=2d9703804d) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [c675cc9767](https://linux-hardware.org/?probe=c675cc9767) | Aug 27, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9c34344e6d](https://linux-hardware.org/?probe=9c34344e6d) | Aug 26, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [2eb35196a6](https://linux-hardware.org/?probe=2eb35196a6) | Aug 26, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [c154878ecd](https://linux-hardware.org/?probe=c154878ecd) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| Lenovo        | ThinkPad T430 2349KAG       | Notebook    | [f2348b8eee](https://linux-hardware.org/?probe=f2348b8eee) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [24c8bedd43](https://linux-hardware.org/?probe=24c8bedd43) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [d31df9053b](https://linux-hardware.org/?probe=d31df9053b) | Aug 23, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [74fe0374b3](https://linux-hardware.org/?probe=74fe0374b3) | Aug 23, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3c5cdd0318](https://linux-hardware.org/?probe=3c5cdd0318) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [99448eedb6](https://linux-hardware.org/?probe=99448eedb6) | Aug 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [e4c7b8207c](https://linux-hardware.org/?probe=e4c7b8207c) | Aug 20, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | Notebook    | [10b7d76c38](https://linux-hardware.org/?probe=10b7d76c38) | Aug 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [50af29acb9](https://linux-hardware.org/?probe=50af29acb9) | Aug 19, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [f8c85e442f](https://linux-hardware.org/?probe=f8c85e442f) | Aug 19, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [47b747684d](https://linux-hardware.org/?probe=47b747684d) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [540a2db767](https://linux-hardware.org/?probe=540a2db767) | Aug 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [28b621194b](https://linux-hardware.org/?probe=28b621194b) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [99b060481a](https://linux-hardware.org/?probe=99b060481a) | Aug 18, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [753e0098e5](https://linux-hardware.org/?probe=753e0098e5) | Aug 17, 2023 |
| ASRock        | H61M-HG4                    | Desktop     | [6fbc46fea9](https://linux-hardware.org/?probe=6fbc46fea9) | Aug 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [54a5786749](https://linux-hardware.org/?probe=54a5786749) | Aug 17, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b63e7d3466](https://linux-hardware.org/?probe=b63e7d3466) | Aug 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c093ae6eb5](https://linux-hardware.org/?probe=c093ae6eb5) | Aug 17, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [3b6cc87ac7](https://linux-hardware.org/?probe=3b6cc87ac7) | Aug 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [c965074769](https://linux-hardware.org/?probe=c965074769) | Aug 17, 2023 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [086cffe9b9](https://linux-hardware.org/?probe=086cffe9b9) | Aug 16, 2023 |
| BESSTAR Te... | VB9                         | Mini pc     | [f4f73b1d87](https://linux-hardware.org/?probe=f4f73b1d87) | Aug 16, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Notebook    | [e9690dda8e](https://linux-hardware.org/?probe=e9690dda8e) | Aug 16, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| HP            | 15                          | Notebook    | [9b9e2459a8](https://linux-hardware.org/?probe=9b9e2459a8) | Aug 15, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [214e2092c6](https://linux-hardware.org/?probe=214e2092c6) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4907b10657](https://linux-hardware.org/?probe=4907b10657) | Aug 15, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [639ec473a1](https://linux-hardware.org/?probe=639ec473a1) | Aug 15, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [0d11484b59](https://linux-hardware.org/?probe=0d11484b59) | Aug 15, 2023 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [a14844e2b4](https://linux-hardware.org/?probe=a14844e2b4) | Aug 14, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f4bcea527c](https://linux-hardware.org/?probe=f4bcea527c) | Aug 14, 2023 |
| ASUSTek       | G15CE                       | Desktop     | [a9ac3a3ce4](https://linux-hardware.org/?probe=a9ac3a3ce4) | Aug 13, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e0c6e5b185](https://linux-hardware.org/?probe=e0c6e5b185) | Aug 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e0e2f927ae](https://linux-hardware.org/?probe=e0e2f927ae) | Aug 13, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [3be73537be](https://linux-hardware.org/?probe=3be73537be) | Aug 13, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | Notebook    | [f709dd85f7](https://linux-hardware.org/?probe=f709dd85f7) | Aug 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [fe5f1d5c1b](https://linux-hardware.org/?probe=fe5f1d5c1b) | Aug 12, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [e39fddb92c](https://linux-hardware.org/?probe=e39fddb92c) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [1f4aa5bf97](https://linux-hardware.org/?probe=1f4aa5bf97) | Aug 12, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4fe6eb4d59](https://linux-hardware.org/?probe=4fe6eb4d59) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [79cc445925](https://linux-hardware.org/?probe=79cc445925) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [b9d1b6d44a](https://linux-hardware.org/?probe=b9d1b6d44a) | Aug 12, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [6f5a32d65f](https://linux-hardware.org/?probe=6f5a32d65f) | Aug 11, 2023 |
| Gigabyte      | M720-US3                    | Desktop     | [222bc02e4f](https://linux-hardware.org/?probe=222bc02e4f) | Aug 11, 2023 |
| Acer          | TMP255-M                    | Notebook    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| HP            | 83E8                        | Desktop     | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [22916d4c12](https://linux-hardware.org/?probe=22916d4c12) | Aug 10, 2023 |
| HP            | 872E                        | Mini pc     | [0318907909](https://linux-hardware.org/?probe=0318907909) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [0521e62bf9](https://linux-hardware.org/?probe=0521e62bf9) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [198fcb1fc2](https://linux-hardware.org/?probe=198fcb1fc2) | Aug 10, 2023 |
| Positivo      | Presley 3                   | Notebook    | [16ddbd1a75](https://linux-hardware.org/?probe=16ddbd1a75) | Aug 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [00bb870b78](https://linux-hardware.org/?probe=00bb870b78) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4a7cc2835f](https://linux-hardware.org/?probe=4a7cc2835f) | Aug 09, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [f50b51555f](https://linux-hardware.org/?probe=f50b51555f) | Aug 09, 2023 |
| Positivo      | Presley 3                   | Notebook    | [9edde2ea30](https://linux-hardware.org/?probe=9edde2ea30) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3702186068](https://linux-hardware.org/?probe=3702186068) | Aug 08, 2023 |
| Lenovo        | ThinkPad T440 20B7S4NV07    | Notebook    | [af7992a11e](https://linux-hardware.org/?probe=af7992a11e) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [77f61b77f5](https://linux-hardware.org/?probe=77f61b77f5) | Aug 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7889f62638](https://linux-hardware.org/?probe=7889f62638) | Aug 08, 2023 |
| Lenovo        | ThinkPad X230 2324BV7       | Notebook    | [e1f092d38b](https://linux-hardware.org/?probe=e1f092d38b) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [fa4f74161f](https://linux-hardware.org/?probe=fa4f74161f) | Aug 08, 2023 |
| Dell          | Inspiron 7306 2n1           | Convertible | [d2e707746f](https://linux-hardware.org/?probe=d2e707746f) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | Notebook    | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [121b892fa8](https://linux-hardware.org/?probe=121b892fa8) | Aug 08, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [61c59e48d2](https://linux-hardware.org/?probe=61c59e48d2) | Aug 08, 2023 |
| Jumper        | QCYL-200                    | Notebook    | [24da6190dc](https://linux-hardware.org/?probe=24da6190dc) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| AZW           | U59                         | Desktop     | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [f7845429c8](https://linux-hardware.org/?probe=f7845429c8) | Aug 07, 2023 |
| Dell          | Latitude 5480               | Notebook    | [f3f7a29ca0](https://linux-hardware.org/?probe=f3f7a29ca0) | Aug 07, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [36a20bb009](https://linux-hardware.org/?probe=36a20bb009) | Aug 07, 2023 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [4323af2ade](https://linux-hardware.org/?probe=4323af2ade) | Aug 07, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [e9dfd6bbb6](https://linux-hardware.org/?probe=e9dfd6bbb6) | Aug 06, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [0a7dc12f31](https://linux-hardware.org/?probe=0a7dc12f31) | Aug 06, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c130dece41](https://linux-hardware.org/?probe=c130dece41) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [6a53759849](https://linux-hardware.org/?probe=6a53759849) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [230032816b](https://linux-hardware.org/?probe=230032816b) | Aug 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [97505d521e](https://linux-hardware.org/?probe=97505d521e) | Aug 06, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [34dc1bc754](https://linux-hardware.org/?probe=34dc1bc754) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [f03fa524d7](https://linux-hardware.org/?probe=f03fa524d7) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [5e28b5b07a](https://linux-hardware.org/?probe=5e28b5b07a) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | Notebook    | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| HP            | 8055                        | Desktop     | [21c8e1fdc2](https://linux-hardware.org/?probe=21c8e1fdc2) | Aug 03, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [2e309e76d7](https://linux-hardware.org/?probe=2e309e76d7) | Aug 03, 2023 |
| HP            | 2215                        | Desktop     | [f0589325fc](https://linux-hardware.org/?probe=f0589325fc) | Aug 03, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [0f5b976e39](https://linux-hardware.org/?probe=0f5b976e39) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [92f3b39535](https://linux-hardware.org/?probe=92f3b39535) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [c4e404738e](https://linux-hardware.org/?probe=c4e404738e) | Aug 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [56e2fa207e](https://linux-hardware.org/?probe=56e2fa207e) | Aug 01, 2023 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [1f69ed5c1e](https://linux-hardware.org/?probe=1f69ed5c1e) | Aug 01, 2023 |
| TUXEDO        | N7x0WU                      | Notebook    | [05c525a9a7](https://linux-hardware.org/?probe=05c525a9a7) | Jul 31, 2023 |
| HP            | ProBook 4740s               | Notebook    | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [65dcccd422](https://linux-hardware.org/?probe=65dcccd422) | Jul 30, 2023 |
| HP            | ProBook 4740s               | Notebook    | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [19b97459c1](https://linux-hardware.org/?probe=19b97459c1) | Jul 30, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [1fe8eab1c6](https://linux-hardware.org/?probe=1fe8eab1c6) | Jul 30, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [5319374e1d](https://linux-hardware.org/?probe=5319374e1d) | Jul 30, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8672df49e2](https://linux-hardware.org/?probe=8672df49e2) | Jul 30, 2023 |
| ASUSTek       | UX461UN                     | Convertible | [8f48f3562c](https://linux-hardware.org/?probe=8f48f3562c) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c8391bd952](https://linux-hardware.org/?probe=c8391bd952) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [c8116c748a](https://linux-hardware.org/?probe=c8116c748a) | Jul 29, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [d23aa8f750](https://linux-hardware.org/?probe=d23aa8f750) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [701402e2a7](https://linux-hardware.org/?probe=701402e2a7) | Jul 29, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [151b7d8d31](https://linux-hardware.org/?probe=151b7d8d31) | Jul 29, 2023 |
| Lenovo        | ThinkPad T420 4180C31       | Notebook    | [7fafc1656d](https://linux-hardware.org/?probe=7fafc1656d) | Jul 28, 2023 |
| Lenovo        | ThinkPad E575 20H8S02W00    | Notebook    | [afde3ea804](https://linux-hardware.org/?probe=afde3ea804) | Jul 28, 2023 |
| Dell          | 0PU052                      | Desktop     | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [06731541dd](https://linux-hardware.org/?probe=06731541dd) | Jul 28, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [cedff6ca6f](https://linux-hardware.org/?probe=cedff6ca6f) | Jul 28, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [b32778a4bd](https://linux-hardware.org/?probe=b32778a4bd) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| Google        | Blooglet                    | Notebook    | [d8c14e29b6](https://linux-hardware.org/?probe=d8c14e29b6) | Jul 27, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e550626a11](https://linux-hardware.org/?probe=e550626a11) | Jul 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [900f299e10](https://linux-hardware.org/?probe=900f299e10) | Jul 26, 2023 |
| Acer          | TMP255-M                    | Notebook    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [96dcaad094](https://linux-hardware.org/?probe=96dcaad094) | Jul 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b5b201f80a](https://linux-hardware.org/?probe=b5b201f80a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [784b86f367](https://linux-hardware.org/?probe=784b86f367) | Jul 25, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [4872d1fdf6](https://linux-hardware.org/?probe=4872d1fdf6) | Jul 25, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [9acc2dda36](https://linux-hardware.org/?probe=9acc2dda36) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [5262229deb](https://linux-hardware.org/?probe=5262229deb) | Jul 25, 2023 |
| MSI           | ZH77A-G41                   | Desktop     | [8528da5360](https://linux-hardware.org/?probe=8528da5360) | Jul 24, 2023 |
| Dell          | Latitude 9330               | Convertible | [715c703b85](https://linux-hardware.org/?probe=715c703b85) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [8f3dc1cb65](https://linux-hardware.org/?probe=8f3dc1cb65) | Jul 24, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [a8f7397fcf](https://linux-hardware.org/?probe=a8f7397fcf) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [7a6a20b8ed](https://linux-hardware.org/?probe=7a6a20b8ed) | Jul 23, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [4cd0b97344](https://linux-hardware.org/?probe=4cd0b97344) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [6094ce5501](https://linux-hardware.org/?probe=6094ce5501) | Jul 23, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b0e064a98a](https://linux-hardware.org/?probe=b0e064a98a) | Jul 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [46218bae31](https://linux-hardware.org/?probe=46218bae31) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| Dell          | Vostro 3578                 | Notebook    | [bd32828bf5](https://linux-hardware.org/?probe=bd32828bf5) | Jul 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [7a3abd2e4d](https://linux-hardware.org/?probe=7a3abd2e4d) | Jul 22, 2023 |
| AMI           | Intel                       | Desktop     | [fe2999b2aa](https://linux-hardware.org/?probe=fe2999b2aa) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42fc5ff144](https://linux-hardware.org/?probe=42fc5ff144) | Jul 21, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [1c164d4bc9](https://linux-hardware.org/?probe=1c164d4bc9) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [65972dbe80](https://linux-hardware.org/?probe=65972dbe80) | Jul 21, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [6df8743ac8](https://linux-hardware.org/?probe=6df8743ac8) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2dbb6f2466](https://linux-hardware.org/?probe=2dbb6f2466) | Jul 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [3014bea7d8](https://linux-hardware.org/?probe=3014bea7d8) | Jul 20, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [f2a5e69f00](https://linux-hardware.org/?probe=f2a5e69f00) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [765ac65603](https://linux-hardware.org/?probe=765ac65603) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e6bbbc4d41](https://linux-hardware.org/?probe=e6bbbc4d41) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d605ad77f](https://linux-hardware.org/?probe=3d605ad77f) | Jul 19, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b098dc2f61](https://linux-hardware.org/?probe=b098dc2f61) | Jul 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [f62d1b0d14](https://linux-hardware.org/?probe=f62d1b0d14) | Jul 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [e2973a88aa](https://linux-hardware.org/?probe=e2973a88aa) | Jul 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [ad6ff2b754](https://linux-hardware.org/?probe=ad6ff2b754) | Jul 16, 2023 |
| HP            | 83E0                        | Desktop     | [35abf30fff](https://linux-hardware.org/?probe=35abf30fff) | Jul 16, 2023 |
| ASUSTek       | X75A1                       | Notebook    | [745ef2a79f](https://linux-hardware.org/?probe=745ef2a79f) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [d06ca4b9c2](https://linux-hardware.org/?probe=d06ca4b9c2) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [103e7e5196](https://linux-hardware.org/?probe=103e7e5196) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [a9cb1108f6](https://linux-hardware.org/?probe=a9cb1108f6) | Jul 15, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6b86cc4c89](https://linux-hardware.org/?probe=6b86cc4c89) | Jul 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [479e8276b4](https://linux-hardware.org/?probe=479e8276b4) | Jul 15, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c9a21bf55e](https://linux-hardware.org/?probe=c9a21bf55e) | Jul 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [be15faa71b](https://linux-hardware.org/?probe=be15faa71b) | Jul 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b8b0b27baf](https://linux-hardware.org/?probe=b8b0b27baf) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [3ab66add04](https://linux-hardware.org/?probe=3ab66add04) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [95577f518a](https://linux-hardware.org/?probe=95577f518a) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [4092f45d41](https://linux-hardware.org/?probe=4092f45d41) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [1ee27caac4](https://linux-hardware.org/?probe=1ee27caac4) | Jul 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [7f06f99146](https://linux-hardware.org/?probe=7f06f99146) | Jul 13, 2023 |
| HP            | 3397                        | Desktop     | [d20efc761c](https://linux-hardware.org/?probe=d20efc761c) | Jul 13, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e69bd50c8e](https://linux-hardware.org/?probe=e69bd50c8e) | Jul 13, 2023 |
| ASUSTek       | X456UV                      | Notebook    | [b0a9e3905f](https://linux-hardware.org/?probe=b0a9e3905f) | Jul 13, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8cf9bcf47](https://linux-hardware.org/?probe=c8cf9bcf47) | Jul 13, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [51cf410b69](https://linux-hardware.org/?probe=51cf410b69) | Jul 12, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [fbc602a7b6](https://linux-hardware.org/?probe=fbc602a7b6) | Jul 12, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [e62935623d](https://linux-hardware.org/?probe=e62935623d) | Jul 12, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [fa1cb6ffb8](https://linux-hardware.org/?probe=fa1cb6ffb8) | Jul 12, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [a1334a7b0f](https://linux-hardware.org/?probe=a1334a7b0f) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [611ea83c30](https://linux-hardware.org/?probe=611ea83c30) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8aadac9d4b](https://linux-hardware.org/?probe=8aadac9d4b) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| Dell          | Latitude 3490               | Notebook    | [6fcb4ace67](https://linux-hardware.org/?probe=6fcb4ace67) | Jul 10, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [1473d3cd3b](https://linux-hardware.org/?probe=1473d3cd3b) | Jul 10, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [b463aaca78](https://linux-hardware.org/?probe=b463aaca78) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [1e5cf5e071](https://linux-hardware.org/?probe=1e5cf5e071) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2d5d457159](https://linux-hardware.org/?probe=2d5d457159) | Jul 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e853f79dd4](https://linux-hardware.org/?probe=e853f79dd4) | Jul 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [9fd763e236](https://linux-hardware.org/?probe=9fd763e236) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [9120c3aa90](https://linux-hardware.org/?probe=9120c3aa90) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [b48f49fab3](https://linux-hardware.org/?probe=b48f49fab3) | Jul 09, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [290c9aca96](https://linux-hardware.org/?probe=290c9aca96) | Jul 09, 2023 |
| Acer          | TravelMate P2510-G2-M       | Notebook    | [c96a405528](https://linux-hardware.org/?probe=c96a405528) | Jul 09, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [a2bd9b682d](https://linux-hardware.org/?probe=a2bd9b682d) | Jul 08, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [362fd95251](https://linux-hardware.org/?probe=362fd95251) | Jul 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e394b88e49](https://linux-hardware.org/?probe=e394b88e49) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| ASUSTek       | UX550VE                     | Notebook    | [b782a00935](https://linux-hardware.org/?probe=b782a00935) | Jul 08, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [2378ebea87](https://linux-hardware.org/?probe=2378ebea87) | Jul 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [59782374c4](https://linux-hardware.org/?probe=59782374c4) | Jul 07, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Framework     | Laptop                      | Notebook    | [ea4c4585d0](https://linux-hardware.org/?probe=ea4c4585d0) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [851a3a00cf](https://linux-hardware.org/?probe=851a3a00cf) | Jul 05, 2023 |
| Dell          | Latitude 3490               | Notebook    | [a730cef547](https://linux-hardware.org/?probe=a730cef547) | Jul 05, 2023 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [7de6676a0c](https://linux-hardware.org/?probe=7de6676a0c) | Jul 05, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [b67973ece1](https://linux-hardware.org/?probe=b67973ece1) | Jul 04, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f3828ea18b](https://linux-hardware.org/?probe=f3828ea18b) | Jul 04, 2023 |
| MSI           | FX603                       | Notebook    | [8b0664bd4e](https://linux-hardware.org/?probe=8b0664bd4e) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [cc0464c9a4](https://linux-hardware.org/?probe=cc0464c9a4) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7aaa5d2eec](https://linux-hardware.org/?probe=7aaa5d2eec) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [6686fca24b](https://linux-hardware.org/?probe=6686fca24b) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [ccb318cd32](https://linux-hardware.org/?probe=ccb318cd32) | Jul 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b66a2be1fe](https://linux-hardware.org/?probe=b66a2be1fe) | Jul 03, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [40b92fc7ba](https://linux-hardware.org/?probe=40b92fc7ba) | Jul 02, 2023 |
| HP            | 8918                        | Desktop     | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [e0810c9450](https://linux-hardware.org/?probe=e0810c9450) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [c0fa0d6c73](https://linux-hardware.org/?probe=c0fa0d6c73) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [a5b11bc53c](https://linux-hardware.org/?probe=a5b11bc53c) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [f182eda3d3](https://linux-hardware.org/?probe=f182eda3d3) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [559c10480e](https://linux-hardware.org/?probe=559c10480e) | Jun 30, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [661dc06ef7](https://linux-hardware.org/?probe=661dc06ef7) | Jun 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e555922bb2](https://linux-hardware.org/?probe=e555922bb2) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| HP            | 89B5 A                      | Desktop     | [f0330163de](https://linux-hardware.org/?probe=f0330163de) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [1c349accca](https://linux-hardware.org/?probe=1c349accca) | Jun 29, 2023 |
| Alienware     | 17 R4                       | Notebook    | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| Google        | Reef                        | Notebook    | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b94582735c](https://linux-hardware.org/?probe=b94582735c) | Jun 28, 2023 |
| Acer          | Aspire VN7-593G             | Notebook    | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6f96789257](https://linux-hardware.org/?probe=6f96789257) | Jun 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f46408c9b6](https://linux-hardware.org/?probe=f46408c9b6) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [f94b4ddd1b](https://linux-hardware.org/?probe=f94b4ddd1b) | Jun 27, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [5e1d8d04f2](https://linux-hardware.org/?probe=5e1d8d04f2) | Jun 26, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [6e179dbfb0](https://linux-hardware.org/?probe=6e179dbfb0) | Jun 26, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9dbf9f98a6](https://linux-hardware.org/?probe=9dbf9f98a6) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9af91d0ced](https://linux-hardware.org/?probe=9af91d0ced) | Jun 26, 2023 |
| HP            | 1493                        | Desktop     | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4493e92d84](https://linux-hardware.org/?probe=4493e92d84) | Jun 25, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [e460d017ec](https://linux-hardware.org/?probe=e460d017ec) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14bd8b577f](https://linux-hardware.org/?probe=14bd8b577f) | Jun 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd418c39bf](https://linux-hardware.org/?probe=bd418c39bf) | Jun 25, 2023 |
| HP            | 8437                        | Desktop     | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [df9521a37d](https://linux-hardware.org/?probe=df9521a37d) | Jun 24, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [090549881a](https://linux-hardware.org/?probe=090549881a) | Jun 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [85221c654f](https://linux-hardware.org/?probe=85221c654f) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [96c2d6503c](https://linux-hardware.org/?probe=96c2d6503c) | Jun 24, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e23ab4ba9](https://linux-hardware.org/?probe=0e23ab4ba9) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [08974b3246](https://linux-hardware.org/?probe=08974b3246) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [38c278b214](https://linux-hardware.org/?probe=38c278b214) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [816c32de98](https://linux-hardware.org/?probe=816c32de98) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [a6a3ed2eae](https://linux-hardware.org/?probe=a6a3ed2eae) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Intel         | NUC7i3BNB J22859-308        | Mini pc     | [3b9990b59d](https://linux-hardware.org/?probe=3b9990b59d) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Framework     | Laptop                      | Notebook    | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [adee2af879](https://linux-hardware.org/?probe=adee2af879) | Jun 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [bfe09e12f0](https://linux-hardware.org/?probe=bfe09e12f0) | Jun 18, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [be5a148c53](https://linux-hardware.org/?probe=be5a148c53) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c454cb2cf0](https://linux-hardware.org/?probe=c454cb2cf0) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [a281272278](https://linux-hardware.org/?probe=a281272278) | Jun 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [0673ab5ff5](https://linux-hardware.org/?probe=0673ab5ff5) | Jun 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bcb3a62b53](https://linux-hardware.org/?probe=bcb3a62b53) | Jun 17, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [777a9e4f49](https://linux-hardware.org/?probe=777a9e4f49) | Jun 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [5b54def91d](https://linux-hardware.org/?probe=5b54def91d) | Jun 16, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [8f65b1ab5b](https://linux-hardware.org/?probe=8f65b1ab5b) | Jun 16, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [38138ba23d](https://linux-hardware.org/?probe=38138ba23d) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [8124f64b22](https://linux-hardware.org/?probe=8124f64b22) | Jun 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c5491fb02f](https://linux-hardware.org/?probe=c5491fb02f) | Jun 16, 2023 |
| Dell          | Latitude E5400              | Notebook    | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| MSI           | X299 GAMING PRO CARBON A... | Desktop     | [6385c09651](https://linux-hardware.org/?probe=6385c09651) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [39b295867e](https://linux-hardware.org/?probe=39b295867e) | Jun 15, 2023 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | Desktop     | [31d4ce59c3](https://linux-hardware.org/?probe=31d4ce59c3) | Jun 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b1e56a3c92](https://linux-hardware.org/?probe=b1e56a3c92) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [3a944bbbd5](https://linux-hardware.org/?probe=3a944bbbd5) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [581aba0aa2](https://linux-hardware.org/?probe=581aba0aa2) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [8515730b56](https://linux-hardware.org/?probe=8515730b56) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [3b552a7f4a](https://linux-hardware.org/?probe=3b552a7f4a) | Jun 15, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f6175fd764](https://linux-hardware.org/?probe=f6175fd764) | Jun 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [09b0f43143](https://linux-hardware.org/?probe=09b0f43143) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8f84dca464](https://linux-hardware.org/?probe=8f84dca464) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [4402afe7ad](https://linux-hardware.org/?probe=4402afe7ad) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [78c4871863](https://linux-hardware.org/?probe=78c4871863) | Jun 14, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| Google        | Atlas                       | Notebook    | [ecd53b626a](https://linux-hardware.org/?probe=ecd53b626a) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| ASUSTek       | UX530UQ                     | Notebook    | [c952ec8390](https://linux-hardware.org/?probe=c952ec8390) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [e18c667ddc](https://linux-hardware.org/?probe=e18c667ddc) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [311a7e116c](https://linux-hardware.org/?probe=311a7e116c) | Jun 13, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [9347870cd0](https://linux-hardware.org/?probe=9347870cd0) | Jun 13, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [a4c87fb2bc](https://linux-hardware.org/?probe=a4c87fb2bc) | Jun 12, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [2069778d1f](https://linux-hardware.org/?probe=2069778d1f) | Jun 12, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [3e121c01dd](https://linux-hardware.org/?probe=3e121c01dd) | Jun 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3918c9dc55](https://linux-hardware.org/?probe=3918c9dc55) | Jun 12, 2023 |
| Emdoor        | AG958                       | Notebook    | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| Dell          | Latitude 5580               | Notebook    | [1e37ff326f](https://linux-hardware.org/?probe=1e37ff326f) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [f62e645bd3](https://linux-hardware.org/?probe=f62e645bd3) | Jun 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9747487f82](https://linux-hardware.org/?probe=9747487f82) | Jun 11, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [5275807836](https://linux-hardware.org/?probe=5275807836) | Jun 11, 2023 |
| HP            | ProBook 470 G0              | Notebook    | [d3fdf73c3e](https://linux-hardware.org/?probe=d3fdf73c3e) | Jun 10, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [af18d05812](https://linux-hardware.org/?probe=af18d05812) | Jun 10, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [450b8ab5a7](https://linux-hardware.org/?probe=450b8ab5a7) | Jun 10, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [03ef8fea42](https://linux-hardware.org/?probe=03ef8fea42) | Jun 10, 2023 |
| ASUSTek       | UX530UQ                     | Notebook    | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| HP            | 82C9                        | Desktop     | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [f4f543eaa6](https://linux-hardware.org/?probe=f4f543eaa6) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| HP            | 3397                        | Desktop     | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| WOOKING       | X16                         | Notebook    | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| Multilaser    | UB820                       | All in one  | [7a1e5beb6e](https://linux-hardware.org/?probe=7a1e5beb6e) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| HP            | 3397                        | Desktop     | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| Google        | Chell                       | Notebook    | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | Desktop     | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| Dell          | Latitude 5530               | Notebook    | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [77e1fa9533](https://linux-hardware.org/?probe=77e1fa9533) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [c33bc572fd](https://linux-hardware.org/?probe=c33bc572fd) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| Dell          | 055H3G A01                  | Desktop     | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| Dell          | Latitude 3340               | Notebook    | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | Notebook    | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| HP            | 3397                        | Desktop     | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| HP            | 8918                        | Desktop     | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [cdb426bfb4](https://linux-hardware.org/?probe=cdb426bfb4) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b34bb8b33a](https://linux-hardware.org/?probe=b34bb8b33a) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [35eb509619](https://linux-hardware.org/?probe=35eb509619) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| MSI           | U200                        | Notebook    | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [d25f4736b7](https://linux-hardware.org/?probe=d25f4736b7) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Lenovo        | 370B SDK0J40700 WIN 3258... | All in one  | [e98c5409ac](https://linux-hardware.org/?probe=e98c5409ac) | Jun 01, 2023 |
| MSI           | P55-GD55                    | Desktop     | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| Acer          | Aspire 3830TG               | Notebook    | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| Dell          | Precision 3550              | Notebook    | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2139621391](https://linux-hardware.org/?probe=2139621391) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| HP            | 0B54h D                     | Desktop     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| HP            | 2B36                        | Desktop     | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d8aa236e2d](https://linux-hardware.org/?probe=d8aa236e2d) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | Notebook    | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [9ea6e59b81](https://linux-hardware.org/?probe=9ea6e59b81) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [f898014dd5](https://linux-hardware.org/?probe=f898014dd5) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4945ea3fba](https://linux-hardware.org/?probe=4945ea3fba) | May 26, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [b5e28ef2ab](https://linux-hardware.org/?probe=b5e28ef2ab) | May 23, 2023 |
| HP            | 8876 11                     | Desktop     | [889144e990](https://linux-hardware.org/?probe=889144e990) | May 23, 2023 |
| AMI           | Intel                       | Desktop     | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [781e226978](https://linux-hardware.org/?probe=781e226978) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [68caefd4e9](https://linux-hardware.org/?probe=68caefd4e9) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | Desktop     | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| AMI           | Intel                       | Desktop     | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Unknown       | HX90                        | Desktop     | [d640a32296](https://linux-hardware.org/?probe=d640a32296) | May 21, 2023 |
| Getac         | V110G3                      | Notebook    | [4a80145aac](https://linux-hardware.org/?probe=4a80145aac) | May 21, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [953734fc80](https://linux-hardware.org/?probe=953734fc80) | May 20, 2023 |
| Lenovo        | 3714 NOK                    | Desktop     | [0da1ff78c6](https://linux-hardware.org/?probe=0da1ff78c6) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [c59f2a4b1e](https://linux-hardware.org/?probe=c59f2a4b1e) | May 19, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| Getac         | V110G3                      | Notebook    | [1b04290d0e](https://linux-hardware.org/?probe=1b04290d0e) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | Desktop     | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | Notebook    | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [d98feea8ad](https://linux-hardware.org/?probe=d98feea8ad) | May 17, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a776d86dad](https://linux-hardware.org/?probe=a776d86dad) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [a74974308d](https://linux-hardware.org/?probe=a74974308d) | May 16, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a4cbf66286](https://linux-hardware.org/?probe=a4cbf66286) | May 16, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [a1d85d1caf](https://linux-hardware.org/?probe=a1d85d1caf) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [0770462dab](https://linux-hardware.org/?probe=0770462dab) | May 15, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [f732fbd488](https://linux-hardware.org/?probe=f732fbd488) | May 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [59214a0e61](https://linux-hardware.org/?probe=59214a0e61) | May 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | Desktop     | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [58c658819c](https://linux-hardware.org/?probe=58c658819c) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [7f4f38aeb1](https://linux-hardware.org/?probe=7f4f38aeb1) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | Notebook    | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| HP            | 3047h                       | Desktop     | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| MSI           | GT70 2PC                    | Notebook    | [c98c889dbf](https://linux-hardware.org/?probe=c98c889dbf) | May 11, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Dell          | Precision 7520              | Notebook    | [184802dbab](https://linux-hardware.org/?probe=184802dbab) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ec8e4b5f19](https://linux-hardware.org/?probe=ec8e4b5f19) | May 11, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Lenovo        | ThinkCentre M71z 1761E4U    | Desktop     | [a865f3d92e](https://linux-hardware.org/?probe=a865f3d92e) | May 11, 2023 |
| Dell          | Latitude E6440              | Notebook    | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57a74239f8](https://linux-hardware.org/?probe=57a74239f8) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [962ca6e507](https://linux-hardware.org/?probe=962ca6e507) | May 10, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| Acer          | TravelMate P653-M           | Notebook    | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Intel         | NUC13ANBi7 M89645-202       | Mini pc     | [6f1e53a7ec](https://linux-hardware.org/?probe=6f1e53a7ec) | May 10, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [69f4dd51d9](https://linux-hardware.org/?probe=69f4dd51d9) | May 10, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [532e5b78de](https://linux-hardware.org/?probe=532e5b78de) | May 09, 2023 |
| MSI           | B85-G43                     | Desktop     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [462a9b182b](https://linux-hardware.org/?probe=462a9b182b) | May 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [5e78ff90cc](https://linux-hardware.org/?probe=5e78ff90cc) | May 08, 2023 |
| TUXEDO        | N24_25BU                    | Notebook    | [9cd4e499ae](https://linux-hardware.org/?probe=9cd4e499ae) | May 07, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Gateway       | RS780                       | Desktop     | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Dell          | Inspiron 5585               | Notebook    | [f838e48bd3](https://linux-hardware.org/?probe=f838e48bd3) | May 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [87e972803c](https://linux-hardware.org/?probe=87e972803c) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| Intel         | H61                         | Desktop     | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0c0ad48cc6](https://linux-hardware.org/?probe=0c0ad48cc6) | May 07, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [7ad914a8a9](https://linux-hardware.org/?probe=7ad914a8a9) | May 06, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [9b843f40a1](https://linux-hardware.org/?probe=9b843f40a1) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4d21a72bfb](https://linux-hardware.org/?probe=4d21a72bfb) | May 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffab85a31a](https://linux-hardware.org/?probe=ffab85a31a) | May 05, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [5989cc1ac0](https://linux-hardware.org/?probe=5989cc1ac0) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [9258699383](https://linux-hardware.org/?probe=9258699383) | May 03, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [1909560f36](https://linux-hardware.org/?probe=1909560f36) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [c0f2b10022](https://linux-hardware.org/?probe=c0f2b10022) | May 02, 2023 |
| MECHREVO      | WUJIE16 Pro                 | Notebook    | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [17097573de](https://linux-hardware.org/?probe=17097573de) | May 02, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [09a404ced5](https://linux-hardware.org/?probe=09a404ced5) | May 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7ffccfda78](https://linux-hardware.org/?probe=7ffccfda78) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | Desktop     | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | Desktop     | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| HP            | ENVY Notebook               | Notebook    | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Pegatron      | Benicia                     | Desktop     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [44b55b4721](https://linux-hardware.org/?probe=44b55b4721) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Multilaser    | UB820                       | All in one  | [3796d857b1](https://linux-hardware.org/?probe=3796d857b1) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [38c117ee87](https://linux-hardware.org/?probe=38c117ee87) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [3c50d5d61c](https://linux-hardware.org/?probe=3c50d5d61c) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [f2d4f962d2](https://linux-hardware.org/?probe=f2d4f962d2) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [f75685d3be](https://linux-hardware.org/?probe=f75685d3be) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | Desktop     | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Google        | Fleex                       | Notebook    | [19603bb256](https://linux-hardware.org/?probe=19603bb256) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [6e1df0f6ee](https://linux-hardware.org/?probe=6e1df0f6ee) | Apr 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [3efc88e5df](https://linux-hardware.org/?probe=3efc88e5df) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [87538ce2ba](https://linux-hardware.org/?probe=87538ce2ba) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [648c4c3622](https://linux-hardware.org/?probe=648c4c3622) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Dell          | Precision 3550              | Notebook    | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [e8e85fe2af](https://linux-hardware.org/?probe=e8e85fe2af) | Apr 18, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| Dell          | Precision 3571              | Notebook    | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | Desktop     | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [0c49ead576](https://linux-hardware.org/?probe=0c49ead576) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| Positivo      | C14CR01                     | Notebook    | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| HP            | 802E                        | Desktop     | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| ASUSTek       | GR6                         | Desktop     | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| AZW           | GT-R                        | Notebook    | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4e6c5f4b6](https://linux-hardware.org/?probe=f4e6c5f4b6) | Apr 12, 2023 |
| Dell          | Precision 5520              | Notebook    | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | Desktop     | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [8e2b7b11ec](https://linux-hardware.org/?probe=8e2b7b11ec) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | Notebook    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| Lenovo        | SKYBAY SDK0J40679 WIN 32... | All in one  | [810692eb45](https://linux-hardware.org/?probe=810692eb45) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| MACHENIKE     | T58-V                       | Notebook    | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Huanan        | X99-F8                      | Desktop     | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| HP            | 84FD                        | Desktop     | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [770d8a9253](https://linux-hardware.org/?probe=770d8a9253) | Apr 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [8c29713fe9](https://linux-hardware.org/?probe=8c29713fe9) | Apr 05, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [695bc9e499](https://linux-hardware.org/?probe=695bc9e499) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5fb3f8e0ef](https://linux-hardware.org/?probe=5fb3f8e0ef) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4061ae40b8](https://linux-hardware.org/?probe=4061ae40b8) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [7d6ecc10d8](https://linux-hardware.org/?probe=7d6ecc10d8) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | Desktop     | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| Star Labs     | StarBook                    | Notebook    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | Notebook    | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 3003      | 39.44%  |
| Manjaro 22.0.0 | 323       | 4.24%   |
| Manjaro 20.1   | 291       | 3.82%   |
| Manjaro 20.2.1 | 283       | 3.72%   |
| Manjaro 20.2   | 243       | 3.19%   |
| Manjaro 20.0.3 | 223       | 2.93%   |
| Manjaro 21.2.6 | 176       | 2.31%   |
| Manjaro 23.0.0 | 171       | 2.25%   |
| Manjaro 21.1.0 | 149       | 1.96%   |
| Manjaro 18.1.5 | 143       | 1.88%   |
| Manjaro 21.2.0 | 127       | 1.67%   |
| Manjaro 21.2.5 | 126       | 1.65%   |
| Manjaro 21.1.6 | 114       | 1.5%    |
| Manjaro 21.0.7 | 113       | 1.48%   |
| Manjaro 20.0   | 101       | 1.33%   |
| Manjaro 19.0.2 | 97        | 1.27%   |
| Manjaro 18.0.4 | 96        | 1.26%   |
| Manjaro 21.0   | 87        | 1.14%   |
| Manjaro 21.0.5 | 80        | 1.05%   |
| Manjaro 20.1.2 | 80        | 1.05%   |
| Manjaro 21.2.3 | 74        | 0.97%   |
| Manjaro 21.2.1 | 73        | 0.96%   |
| Manjaro 22.1.0 | 72        | 0.95%   |
| Manjaro 20.1.1 | 71        | 0.93%   |
| Manjaro 20.0.1 | 69        | 0.91%   |
| Manjaro 22.0.4 | 56        | 0.74%   |
| Manjaro 21.3.7 | 56        | 0.74%   |
| Manjaro 21.3.6 | 50        | 0.66%   |
| Manjaro 21.0.4 | 50        | 0.66%   |
| Manjaro 21.2.2 | 46        | 0.6%    |
| Manjaro 21.2.4 | 45        | 0.59%   |
| Manjaro 21.1.2 | 41        | 0.54%   |
| Manjaro 21.1.4 | 37        | 0.49%   |
| Manjaro 21.0.1 | 36        | 0.47%   |
| Manjaro 22.0.5 | 35        | 0.46%   |
| Manjaro 21.0.2 | 34        | 0.45%   |
| Manjaro 21.3.1 | 32        | 0.42%   |
| Manjaro 21.3.0 | 31        | 0.41%   |
| Manjaro 21.0.3 | 31        | 0.41%   |
| Manjaro 22.1.1 | 30        | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 6986      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 294       | 3.53%   |
| 5.13.19-2-MANJARO | 181       | 2.17%   |
| 5.8.6-1-MANJARO   | 140       | 1.68%   |
| 5.9.11-3-MANJARO  | 129       | 1.55%   |
| 5.8.11-1-MANJARO  | 122       | 1.46%   |
| 5.15.28-1-MANJARO | 118       | 1.42%   |
| 5.10.42-1-MANJARO | 102       | 1.22%   |
| 6.1.1-1-MANJARO   | 101       | 1.21%   |
| 5.8.18-1-MANJARO  | 101       | 1.21%   |
| 5.15.32-1-MANJARO | 100       | 1.2%    |
| 6.1.12-1-MANJARO  | 86        | 1.03%   |
| 5.15.12-1-MANJARO | 82        | 0.98%   |
| 6.1.31-2-MANJARO  | 81        | 0.97%   |
| 5.6.16-1-MANJARO  | 74        | 0.89%   |
| 5.15.60-1-MANJARO | 74        | 0.89%   |
| 5.8.16-2-MANJARO  | 73        | 0.88%   |
| 5.10.2-2-MANJARO  | 65        | 0.78%   |
| 5.15.65-1-MANJARO | 62        | 0.74%   |
| 5.7.9-1-MANJARO   | 61        | 0.73%   |
| 5.10.36-2-MANJARO | 61        | 0.73%   |
| 5.6.19-2-MANJARO  | 60        | 0.72%   |
| 5.10.7-3-MANJARO  | 60        | 0.72%   |
| 5.7.0-3-MANJARO   | 58        | 0.7%    |
| 5.8.3-2-MANJARO   | 57        | 0.68%   |
| 5.6.15-1-MANJARO  | 57        | 0.68%   |
| 5.12.9-1-MANJARO  | 54        | 0.65%   |
| 5.7.17-2-MANJARO  | 52        | 0.62%   |
| 5.15.78-1-MANJARO | 51        | 0.61%   |
| 5.15.41-1-MANJARO | 51        | 0.61%   |
| 5.14.10-1-MANJARO | 51        | 0.61%   |
| 5.9.1-1-MANJARO   | 50        | 0.6%    |
| 5.17.1-3-MANJARO  | 49        | 0.59%   |
| 5.16.14-1-MANJARO | 49        | 0.59%   |
| 5.10.23-1-MANJARO | 49        | 0.59%   |
| 5.15.74-3-MANJARO | 48        | 0.58%   |
| 5.15.7-1-MANJARO  | 48        | 0.58%   |
| 5.11.6-1-MANJARO  | 47        | 0.56%   |
| 5.15.85-1-MANJARO | 45        | 0.54%   |
| 5.15.25-1-MANJARO | 45        | 0.54%   |
| 5.10.34-1-MANJARO | 45        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 294       | 3.53%   |
| 5.13.19 | 182       | 2.18%   |
| 5.8.6   | 140       | 1.68%   |
| 5.9.11  | 136       | 1.63%   |
| 5.8.11  | 123       | 1.48%   |
| 5.15.28 | 118       | 1.42%   |
| 5.10.42 | 102       | 1.22%   |
| 6.1.1   | 101       | 1.21%   |
| 5.8.18  | 101       | 1.21%   |
| 5.15.32 | 101       | 1.21%   |
| 6.1.31  | 87        | 1.04%   |
| 6.1.12  | 86        | 1.03%   |
| 5.15.12 | 82        | 0.98%   |
| 5.8.16  | 74        | 0.89%   |
| 5.6.16  | 74        | 0.89%   |
| 5.15.60 | 74        | 0.89%   |
| 5.7.0   | 73        | 0.88%   |
| 5.9.1   | 69        | 0.83%   |
| 5.6.19  | 66        | 0.79%   |
| 5.10.2  | 65        | 0.78%   |
| 5.15.65 | 62        | 0.74%   |
| 5.10.7  | 62        | 0.74%   |
| 5.7.9   | 61        | 0.73%   |
| 5.17.1  | 61        | 0.73%   |
| 5.10.36 | 61        | 0.73%   |
| 5.8.3   | 58        | 0.7%    |
| 5.6.15  | 57        | 0.68%   |
| 5.12.9  | 54        | 0.65%   |
| 5.7.17  | 53        | 0.64%   |
| 5.15.78 | 51        | 0.61%   |
| 5.15.41 | 51        | 0.61%   |
| 5.14.10 | 51        | 0.61%   |
| 5.15.7  | 50        | 0.6%    |
| 5.16.14 | 49        | 0.59%   |
| 5.15.74 | 49        | 0.59%   |
| 5.10.23 | 49        | 0.59%   |
| 5.11.6  | 48        | 0.58%   |
| 5.6.12  | 46        | 0.55%   |
| 5.15.2  | 46        | 0.55%   |
| 5.15.85 | 45        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1268      | 16.21%  |
| 5.10    | 922       | 11.79%  |
| 6.1     | 679       | 8.68%   |
| 5.4     | 631       | 8.07%   |
| 5.9     | 590       | 7.54%   |
| 5.8     | 553       | 7.07%   |
| 5.6     | 393       | 5.03%   |
| 5.13    | 359       | 4.59%   |
| 5.7     | 264       | 3.38%   |
| 4.19    | 199       | 2.54%   |
| 5.11    | 185       | 2.37%   |
| 5.16    | 175       | 2.24%   |
| 5.12    | 157       | 2.01%   |
| 5.14    | 153       | 1.96%   |
| 6.0     | 152       | 1.94%   |
| 5.17    | 142       | 1.82%   |
| 5.19    | 138       | 1.76%   |
| 5.18    | 131       | 1.68%   |
| 5.5     | 109       | 1.39%   |
| 5.3     | 92        | 1.18%   |
| 6.2     | 91        | 1.16%   |
| 6.3     | 90        | 1.15%   |
| 6.5     | 74        | 0.95%   |
| 6.4     | 73        | 0.93%   |
| 4.14    | 60        | 0.77%   |
| 5.2     | 41        | 0.52%   |
| 5.0     | 30        | 0.38%   |
| 5.1     | 26        | 0.33%   |
| 4.20    | 14        | 0.18%   |
| 4.18    | 12        | 0.15%   |
| 4.9     | 4         | 0.05%   |
| 4.16    | 4         | 0.05%   |
| 4.17    | 3         | 0.04%   |
| 6.6     | 2         | 0.03%   |
| 4.7     | 2         | 0.03%   |
| 4.4     | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6983      | 99.96%  |
| i686    | 2         | 0.03%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 2712      | 37.51%  |
| XFCE                     | 1514      | 20.94%  |
| GNOME                    | 1506      | 20.83%  |
| KDE                      | 566       | 7.83%   |
| Unknown                  | 320       | 4.43%   |
| X-Cinnamon               | 181       | 2.5%    |
| i3                       | 134       | 1.85%   |
| MATE                     | 68        | 0.94%   |
| Cinnamon                 | 57        | 0.79%   |
| Deepin                   | 50        | 0.69%   |
| Budgie                   | 31        | 0.43%   |
| awesome                  | 18        | 0.25%   |
| LXQt                     | 17        | 0.24%   |
| sway                     | 13        | 0.18%   |
| LXDE                     | 7         | 0.1%    |
| bspwm                    | 5         | 0.07%   |
| i3-with-shmlog           | 4         | 0.06%   |
| qtile                    | 3         | 0.04%   |
| GNOME Classic            | 3         | 0.04%   |
| DWM                      | 3         | 0.04%   |
| Yaru:ubuntu:GNOME        | 2         | 0.03%   |
| leftwm                   | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| Hyprland                 | 2         | 0.03%   |
| GNOME Flashback          | 2         | 0.03%   |
| Enlightenment            | 2         | 0.03%   |
| xinitrc                  | 1         | 0.01%   |
| Unity                    | 1         | 0.01%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.01%   |
| openbox                  | 1         | 0.01%   |
| herbstluftwm             | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5987      | 84.21%  |
| Wayland | 913       | 12.84%  |
| Unknown | 143       | 2.01%   |
| Tty     | 67        | 0.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2983      | 41.62%  |
| SDDM    | 1820      | 25.39%  |
| LightDM | 1218      | 16.99%  |
| GDM     | 901       | 12.57%  |
| TDM     | 218       | 3.04%   |
| LXDM    | 10        | 0.14%   |
| GREETD  | 8         | 0.11%   |
| SLiM    | 3         | 0.04%   |
| XDM     | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| LYNDE   | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2933      | 41.41%  |
| de_DE   | 569       | 8.03%   |
| ru_RU   | 494       | 6.98%   |
| en_GB   | 487       | 6.88%   |
| Unknown | 422       | 5.96%   |
| pt_BR   | 299       | 4.22%   |
| fr_FR   | 194       | 2.74%   |
| it_IT   | 156       | 2.2%    |
| en_CA   | 153       | 2.16%   |
| es_ES   | 150       | 2.12%   |
| pl_PL   | 126       | 1.78%   |
| en_AU   | 91        | 1.28%   |
| en_IN   | 83        | 1.17%   |
| es_MX   | 64        | 0.9%    |
| zh_CN   | 53        | 0.75%   |
| de_AT   | 46        | 0.65%   |
| nl_NL   | 42        | 0.59%   |
| ru_UA   | 39        | 0.55%   |
| es_AR   | 37        | 0.52%   |
| en_IE   | 30        | 0.42%   |
| sv_SE   | 27        | 0.38%   |
| fi_FI   | 24        | 0.34%   |
| es_CL   | 24        | 0.34%   |
| de_CH   | 24        | 0.34%   |
| hu_HU   | 23        | 0.32%   |
| cs_CZ   | 23        | 0.32%   |
| pt_PT   | 22        | 0.31%   |
| C       | 22        | 0.31%   |
| tr_TR   | 21        | 0.3%    |
| en_NZ   | 20        | 0.28%   |
| en_ZA   | 19        | 0.27%   |
| en_DK   | 19        | 0.27%   |
| uk_UA   | 18        | 0.25%   |
| es_CO   | 18        | 0.25%   |
| en_PH   | 17        | 0.24%   |
| fr_CA   | 16        | 0.23%   |
| el_GR   | 14        | 0.2%    |
| en_IL   | 13        | 0.18%   |
| nl_BE   | 12        | 0.17%   |
| ja_JP   | 12        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3945      | 55.47%  |
| EFI  | 3167      | 44.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5874      | 83.01%  |
| Btrfs    | 716       | 10.12%  |
| Overlay  | 140       | 1.98%   |
| Unknown  | 129       | 1.82%   |
| Xfs      | 85        | 1.2%    |
| Tmpfs    | 85        | 1.2%    |
| F2fs     | 27        | 0.38%   |
| Ext3     | 5         | 0.07%   |
| Ext2     | 5         | 0.07%   |
| Zfs      | 4         | 0.06%   |
| Reiserfs | 3         | 0.04%   |
| XXXX     | 1         | 0.01%   |
| XXXfs    | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3305      | 46.33%  |
| Unknown | 3217      | 45.1%   |
| MBR     | 611       | 8.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6210      | 87.55%  |
| Yes       | 883       | 12.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4855      | 68.32%  |
| Yes       | 2251      | 31.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1278      | 18.29%  |
| Lenovo              | 1119      | 16.02%  |
| Hewlett-Packard     | 910       | 13.03%  |
| Dell                | 745       | 10.66%  |
| Gigabyte Technology | 559       | 8%      |
| MSI                 | 550       | 7.87%   |
| Acer                | 352       | 5.04%   |
| ASRock              | 293       | 4.19%   |
| Apple               | 138       | 1.98%   |
| Intel               | 95        | 1.36%   |
| HUAWEI              | 71        | 1.02%   |
| Samsung Electronics | 67        | 0.96%   |
| Toshiba             | 66        | 0.94%   |
| Unknown             | 46        | 0.66%   |
| Timi                | 41        | 0.59%   |
| Fujitsu             | 40        | 0.57%   |
| Google              | 34        | 0.49%   |
| Sony                | 33        | 0.47%   |
| Notebook            | 30        | 0.43%   |
| TUXEDO              | 22        | 0.31%   |
| Microsoft           | 22        | 0.31%   |
| Biostar             | 22        | 0.31%   |
| Pegatron            | 18        | 0.26%   |
| Medion              | 18        | 0.26%   |
| AZW                 | 18        | 0.26%   |
| Alienware           | 18        | 0.26%   |
| Razer               | 16        | 0.23%   |
| Positivo            | 16        | 0.23%   |
| Schenker            | 13        | 0.19%   |
| Packard Bell        | 13        | 0.19%   |
| Huanan              | 13        | 0.19%   |
| HONOR               | 13        | 0.19%   |
| LG Electronics      | 12        | 0.17%   |
| Foxconn             | 12        | 0.17%   |
| Chuwi               | 11        | 0.16%   |
| BESSTAR Tech        | 10        | 0.14%   |
| System76            | 9         | 0.13%   |
| ZOTAC               | 7         | 0.1%    |
| TrekStor            | 7         | 0.1%    |
| Panasonic           | 7         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 73        | 1.04%   |
| Unknown                             | 58        | 0.83%   |
| MSI MS-7C37                         | 32        | 0.46%   |
| MSI MS-7C02                         | 28        | 0.4%    |
| Gigabyte B450M DS3H                 | 28        | 0.4%    |
| ASUS TUF Gaming X570-PLUS           | 24        | 0.34%   |
| HP Notebook                         | 22        | 0.31%   |
| MSI MS-7C91                         | 20        | 0.29%   |
| ASUS PRIME A320M-K                  | 20        | 0.29%   |
| MSI MS-7B86                         | 17        | 0.24%   |
| Gigabyte X570 AORUS ELITE           | 16        | 0.23%   |
| ASRock B450M Pro4                   | 16        | 0.23%   |
| MSI MS-7B79                         | 15        | 0.21%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 15        | 0.21%   |
| ASUS ROG STRIX B450-F GAMING        | 15        | 0.21%   |
| ASUS ROG STRIX B550-F GAMING        | 14        | 0.2%    |
| MSI MS-7A38                         | 13        | 0.19%   |
| Lenovo Legion 5 15ARH05 82B5        | 13        | 0.19%   |
| Dell XPS 15 9500                    | 13        | 0.19%   |
| Dell XPS 13 9310                    | 13        | 0.19%   |
| Dell OptiPlex 9020                  | 13        | 0.19%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 12        | 0.17%   |
| HP Pavilion Notebook                | 12        | 0.17%   |
| ASUS TUF Gaming B550M-PLUS          | 12        | 0.17%   |
| ASUS PRIME B450M-A                  | 12        | 0.17%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 11        | 0.16%   |
| Gigabyte B450 AORUS M               | 11        | 0.16%   |
| Gigabyte B450 AORUS ELITE           | 11        | 0.16%   |
| Gigabyte 970A-DS3P                  | 11        | 0.16%   |
| Dell OptiPlex 7010                  | 11        | 0.16%   |
| Dell Inspiron 3542                  | 11        | 0.16%   |
| ASUS PRIME B350-PLUS                | 11        | 0.16%   |
| MSI MS-7B89                         | 10        | 0.14%   |
| MSI MS-7693                         | 10        | 0.14%   |
| HP Pavilion dv7                     | 10        | 0.14%   |
| HP Laptop 15-bs0xx                  | 10        | 0.14%   |
| Gigabyte X570 AORUS MASTER          | 10        | 0.14%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 10        | 0.14%   |
| Dell XPS 15 7590                    | 10        | 0.14%   |
| ASUS ROG STRIX X570-E GAMING        | 10        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 465       | 6.66%   |
| Lenovo IdeaPad     | 268       | 3.84%   |
| ASUS ROG           | 219       | 3.13%   |
| Acer Aspire        | 219       | 3.13%   |
| Dell Inspiron      | 211       | 3.02%   |
| HP Pavilion        | 171       | 2.45%   |
| ASUS PRIME         | 168       | 2.4%    |
| Dell Latitude      | 157       | 2.25%   |
| Dell XPS           | 122       | 1.75%   |
| ASUS TUF           | 118       | 1.69%   |
| HP EliteBook       | 106       | 1.52%   |
| HP ProBook         | 105       | 1.5%    |
| HP Laptop          | 105       | 1.5%    |
| Dell OptiPlex      | 89        | 1.27%   |
| ASUS VivoBook      | 86        | 1.23%   |
| Lenovo Legion      | 79        | 1.13%   |
| HP ENVY            | 73        | 1.04%   |
| ASUS All           | 73        | 1.04%   |
| Dell Precision     | 68        | 0.97%   |
| Unknown            | 58        | 0.83%   |
| Toshiba Satellite  | 57        | 0.82%   |
| HP Compaq          | 57        | 0.82%   |
| Lenovo Yoga        | 56        | 0.8%    |
| Gigabyte X570      | 51        | 0.73%   |
| Dell Vostro        | 46        | 0.66%   |
| Gigabyte B450M     | 45        | 0.64%   |
| HP OMEN            | 39        | 0.56%   |
| ASUS ZenBook       | 38        | 0.54%   |
| Acer Swift         | 38        | 0.54%   |
| Gigabyte B450      | 37        | 0.53%   |
| Acer Nitro         | 35        | 0.5%    |
| MSI MS-7C37        | 32        | 0.46%   |
| Lenovo ThinkCentre | 30        | 0.43%   |
| MSI MS-7C02        | 28        | 0.4%    |
| Fujitsu LIFEBOOK   | 28        | 0.4%    |
| Lenovo ThinkBook   | 27        | 0.39%   |
| ASUS ASUS          | 27        | 0.39%   |
| ASRock B450M       | 26        | 0.37%   |
| HP EliteDesk       | 23        | 0.33%   |
| Gigabyte B550      | 23        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 917       | 13.13%  |
| 2020    | 882       | 12.63%  |
| 2018    | 879       | 12.58%  |
| 2017    | 575       | 8.23%   |
| 2021    | 536       | 7.67%   |
| 2012    | 507       | 7.26%   |
| 2013    | 408       | 5.84%   |
| 2014    | 392       | 5.61%   |
| 2011    | 354       | 5.07%   |
| 2015    | 346       | 4.95%   |
| 2016    | 342       | 4.9%    |
| 2022    | 226       | 3.24%   |
| 2010    | 210       | 3.01%   |
| 2009    | 142       | 2.03%   |
| 2008    | 126       | 1.8%    |
| 2007    | 73        | 1.04%   |
| 2023    | 39        | 0.56%   |
| 2006    | 21        | 0.3%    |
| Unknown | 6         | 0.09%   |
| 2005    | 5         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3872      | 55.43%  |
| Desktop     | 2671      | 38.23%  |
| Convertible | 252       | 3.61%   |
| Mini pc     | 85        | 1.22%   |
| All in one  | 51        | 0.73%   |
| Tablet      | 46        | 0.66%   |
| Server      | 8         | 0.11%   |
| Phone       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6982      | 99.9%   |
| Enabled  | 7         | 0.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6934      | 99.26%  |
| Yes  | 52        | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1902      | 26.84%  |
| 4.01-8.0        | 1557      | 21.97%  |
| 8.01-16.0       | 1403      | 19.8%   |
| 32.01-64.0      | 921       | 13%     |
| 3.01-4.0        | 790       | 11.15%  |
| 64.01-256.0     | 198       | 2.79%   |
| 24.01-32.0      | 170       | 2.4%    |
| 1.01-2.0        | 107       | 1.51%   |
| 2.01-3.0        | 35        | 0.49%   |
| More than 256.0 | 2         | 0.03%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 1984      | 25.42%  |
| 1.01-2.0        | 1822      | 23.34%  |
| 4.01-8.0        | 1787      | 22.89%  |
| 3.01-4.0        | 1333      | 17.08%  |
| 8.01-16.0       | 535       | 6.85%   |
| 0.51-1.0        | 221       | 2.83%   |
| 16.01-24.0      | 70        | 0.9%    |
| 24.01-32.0      | 21        | 0.27%   |
| 0.01-0.5        | 20        | 0.26%   |
| 32.01-64.0      | 11        | 0.14%   |
| More than 256.0 | 1         | 0.01%   |
| 64.01-256.0     | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3657      | 50.74%  |
| 2      | 2051      | 28.46%  |
| 3      | 716       | 9.93%   |
| 4      | 385       | 5.34%   |
| 5      | 211       | 2.93%   |
| 6      | 80        | 1.11%   |
| 7      | 38        | 0.53%   |
| 0      | 31        | 0.43%   |
| 8      | 17        | 0.24%   |
| 9      | 10        | 0.14%   |
| 11     | 5         | 0.07%   |
| 10     | 3         | 0.04%   |
| 12     | 2         | 0.03%   |
| 20     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5120      | 72.63%  |
| Yes       | 1929      | 27.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5825      | 83.21%  |
| No        | 1175      | 16.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5524      | 78.56%  |
| No        | 1508      | 21.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4722      | 66.85%  |
| No        | 2342      | 33.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1186      | 16.85%  |
| Germany      | 830       | 11.79%  |
| Russia       | 623       | 8.85%   |
| Brazil       | 417       | 5.92%   |
| France       | 265       | 3.76%   |
| UK           | 252       | 3.58%   |
| Italy        | 231       | 3.28%   |
| Canada       | 225       | 3.2%    |
| Poland       | 204       | 2.9%    |
| Spain        | 202       | 2.87%   |
| Netherlands  | 163       | 2.32%   |
| Ukraine      | 147       | 2.09%   |
| India        | 131       | 1.86%   |
| Australia    | 103       | 1.46%   |
| Mexico       | 99        | 1.41%   |
| Austria      | 97        | 1.38%   |
| Sweden       | 96        | 1.36%   |
| China        | 73        | 1.04%   |
| Switzerland  | 72        | 1.02%   |
| Turkey       | 64        | 0.91%   |
| Belgium      | 63        | 0.9%    |
| Finland      | 62        | 0.88%   |
| Romania      | 61        | 0.87%   |
| Hungary      | 56        | 0.8%    |
| Czechia      | 56        | 0.8%    |
| Argentina    | 56        | 0.8%    |
| Portugal     | 55        | 0.78%   |
| Greece       | 50        | 0.71%   |
| Bulgaria     | 50        | 0.71%   |
| Indonesia    | 49        | 0.7%    |
| Norway       | 48        | 0.68%   |
| Belarus      | 43        | 0.61%   |
| Denmark      | 40        | 0.57%   |
| Colombia     | 33        | 0.47%   |
| Chile        | 32        | 0.45%   |
| Taiwan       | 30        | 0.43%   |
| Bangladesh   | 30        | 0.43%   |
| South Africa | 28        | 0.4%    |
| Israel       | 28        | 0.4%    |
| Japan        | 26        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 148       | 1.99%   |
| St Petersburg     | 84        | 1.13%   |
| Vienna            | 58        | 0.78%   |
| Berlin            | 58        | 0.78%   |
| Paris             | 52        | 0.7%    |
| Sao Paulo         | 46        | 0.62%   |
| Warsaw            | 44        | 0.59%   |
| Kyiv              | 43        | 0.58%   |
| Amsterdam         | 43        | 0.58%   |
| Frankfurt am Main | 36        | 0.48%   |
| Toronto           | 34        | 0.46%   |
| Milan             | 34        | 0.46%   |
| Madrid            | 32        | 0.43%   |
| Hamburg           | 32        | 0.43%   |
| Rome              | 30        | 0.4%    |
| Munich            | 29        | 0.39%   |
| Helsinki          | 29        | 0.39%   |
| Melbourne         | 28        | 0.38%   |
| Stockholm         | 27        | 0.36%   |
| Istanbul          | 26        | 0.35%   |
| Athens            | 26        | 0.35%   |
| Minsk             | 25        | 0.34%   |
| Novosibirsk       | 24        | 0.32%   |
| London            | 24        | 0.32%   |
| Bucharest         | 24        | 0.32%   |
| Bengaluru         | 24        | 0.32%   |
| Barcelona         | 24        | 0.32%   |
| Sydney            | 23        | 0.31%   |
| Sofia             | 22        | 0.3%    |
| Rio de Janeiro    | 22        | 0.3%    |
| Mexico City       | 22        | 0.3%    |
| Cologne           | 22        | 0.3%    |
| Budapest          | 22        | 0.3%    |
| Seattle           | 21        | 0.28%   |
| Prague            | 21        | 0.28%   |
| Krakow            | 21        | 0.28%   |
| Yekaterinburg     | 20        | 0.27%   |
| Dhaka             | 20        | 0.27%   |
| Stuttgart         | 19        | 0.26%   |
| Montreal          | 19        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2004      | 3093   | 17.38%  |
| WDC                         | 1611      | 2452   | 13.97%  |
| Seagate                     | 1539      | 2334   | 13.35%  |
| Toshiba                     | 727       | 907    | 6.3%    |
| SanDisk                     | 705       | 921    | 6.11%   |
| Kingston                    | 659       | 860    | 5.71%   |
| Crucial                     | 488       | 687    | 4.23%   |
| Unknown                     | 353       | 466    | 3.06%   |
| SK hynix                    | 329       | 396    | 2.85%   |
| Intel                       | 321       | 425    | 2.78%   |
| Hitachi                     | 233       | 309    | 2.02%   |
| HGST                        | 221       | 287    | 1.92%   |
| Micron Technology           | 184       | 231    | 1.6%    |
| A-DATA Technology           | 152       | 209    | 1.32%   |
| Phison                      | 132       | 181    | 1.14%   |
| China                       | 112       | 147    | 0.97%   |
| Silicon Motion              | 83        | 110    | 0.72%   |
| Micron/Crucial Technology   | 81        | 100    | 0.7%    |
| KIOXIA                      | 81        | 96     | 0.7%    |
| Apple                       | 81        | 101    | 0.7%    |
| Phison Electronics          | 75        | 85     | 0.65%   |
| Transcend                   | 58        | 64     | 0.5%    |
| PNY                         | 57        | 85     | 0.49%   |
| SPCC                        | 53        | 62     | 0.46%   |
| Intenso                     | 50        | 69     | 0.43%   |
| OCZ                         | 49        | 69     | 0.42%   |
| Patriot                     | 47        | 59     | 0.41%   |
| GOODRAM                     | 47        | 74     | 0.41%   |
| JMicron Technology          | 45        | 53     | 0.39%   |
| XPG                         | 43        | 54     | 0.37%   |
| Kingston Technology Company | 39        | 42     | 0.34%   |
| Plextor                     | 36        | 48     | 0.31%   |
| Corsair                     | 35        | 46     | 0.3%    |
| LITEON                      | 34        | 41     | 0.29%   |
| Realtek Semiconductor       | 33        | 41     | 0.29%   |
| LITEONIT                    | 33        | 42     | 0.29%   |
| ADATA Technology            | 27        | 34     | 0.23%   |
| Team                        | 25        | 32     | 0.22%   |
| Lexar                       | 25        | 28     | 0.22%   |
| Apacer                      | 22        | 24     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 139       | 1.07%   |
| Kingston SA400S37240G 240GB SSD                     | 134       | 1.04%   |
| Samsung SSD 860 EVO 500GB                           | 117       | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                      | 111       | 0.86%   |
| Samsung SSD 850 EVO 500GB                           | 94        | 0.73%   |
| Samsung NVMe SSD Drive 512GB                        | 86        | 0.66%   |
| Samsung NVMe SSD Drive 500GB                        | 83        | 0.64%   |
| Samsung SSD 850 EVO 250GB                           | 82        | 0.63%   |
| Samsung NVMe SSD Drive 1TB                          | 82        | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB                      | 81        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 81        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                     | 80        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 80        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                      | 78        | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 72        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB                         | 70        | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 69        | 0.53%   |
| Samsung SSD 860 EVO 1TB                             | 67        | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 66        | 0.51%   |
| HGST HTS721010A9E630 1TB                            | 66        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 61        | 0.47%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 61        | 0.47%   |
| Toshiba DT01ACA100 1TB                              | 60        | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 59        | 0.46%   |
| Samsung SSD 860 EVO 250GB                           | 59        | 0.46%   |
| Crucial CT240BX500SSD1 240GB                        | 58        | 0.45%   |
| SK hynix NVMe SSD Drive 512GB                       | 55        | 0.43%   |
| Seagate Expansion 1TB                               | 55        | 0.43%   |
| Unknown MMC Card  64GB                              | 52        | 0.4%    |
| SanDisk NVMe SSD Drive 512GB                        | 52        | 0.4%    |
| Unknown SD/MMC/MS PRO 128GB                         | 48        | 0.37%   |
| Toshiba MQ01ABF050 500GB                            | 46        | 0.36%   |
| Seagate ST500DM002-1BD142 500GB                     | 45        | 0.35%   |
| SanDisk NVMe SSD Drive 500GB                        | 45        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB                      | 44        | 0.34%   |
| Intel NVMe SSD Drive 512GB                          | 44        | 0.34%   |
| Unknown MMC Card  32GB                              | 42        | 0.32%   |
| Seagate ST2000DM006-2DM164 2TB                      | 42        | 0.32%   |
| SanDisk NVMe SSD Drive 1TB                          | 42        | 0.32%   |
| Kingston SV300S37A120G 120GB SSD                    | 41        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1501      | 2262   | 36.53%  |
| WDC                 | 1282      | 1943   | 31.2%   |
| Toshiba             | 533       | 666    | 12.97%  |
| Hitachi             | 233       | 309    | 5.67%   |
| HGST                | 220       | 286    | 5.35%   |
| Samsung Electronics | 157       | 238    | 3.82%   |
| Unknown             | 54        | 66     | 1.31%   |
| Fujitsu             | 20        | 26     | 0.49%   |
| Apple               | 17        | 22     | 0.41%   |
| SABRENT             | 14        | 14     | 0.34%   |
| Maxtor              | 14        | 16     | 0.34%   |
| USB3.0              | 8         | 8      | 0.19%   |
| Intenso             | 8         | 13     | 0.19%   |
| External            | 6         | 8      | 0.15%   |
| ASMT                | 6         | 12     | 0.15%   |
| JMicron Technology  | 5         | 9      | 0.12%   |
| Hewlett-Packard     | 4         | 4      | 0.1%    |
| USB                 | 3         | 3      | 0.07%   |
| MaxDigital          | 3         | 3      | 0.07%   |
| HGST HTS            | 3         | 3      | 0.07%   |
| SSK                 | 2         | 3      | 0.05%   |
| Maxone              | 2         | 3      | 0.05%   |
| ASMedia             | 2         | 2      | 0.05%   |
| Apricorn            | 2         | 2      | 0.05%   |
| QNAP                | 1         | 1      | 0.02%   |
| Pioneer             | 1         | 3      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| Lenovo              | 1         | 1      | 0.02%   |
| KESU                | 1         | 1      | 0.02%   |
| Initio              | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 1      | 0.02%   |
| IB-377U3            | 1         | 1      | 0.02%   |
| ACASIS              | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 973       | 1385   | 24.85%  |
| Kingston            | 527       | 677    | 13.46%  |
| Crucial             | 447       | 637    | 11.41%  |
| SanDisk             | 325       | 425    | 8.3%    |
| WDC                 | 242       | 319    | 6.18%   |
| A-DATA Technology   | 123       | 170    | 3.14%   |
| China               | 111       | 146    | 2.83%   |
| Intel               | 99        | 125    | 2.53%   |
| Micron Technology   | 74        | 92     | 1.89%   |
| SK hynix            | 63        | 74     | 1.61%   |
| Toshiba             | 57        | 73     | 1.46%   |
| Transcend           | 51        | 56     | 1.3%    |
| PNY                 | 51        | 79     | 1.3%    |
| OCZ                 | 49        | 69     | 1.25%   |
| Apple               | 46        | 52     | 1.17%   |
| GOODRAM             | 45        | 72     | 1.15%   |
| Patriot             | 44        | 56     | 1.12%   |
| SPCC                | 42        | 50     | 1.07%   |
| Intenso             | 34        | 46     | 0.87%   |
| Plextor             | 33        | 45     | 0.84%   |
| LITEONIT            | 33        | 42     | 0.84%   |
| LITEON              | 28        | 35     | 0.72%   |
| Lexar               | 24        | 27     | 0.61%   |
| Corsair             | 24        | 33     | 0.61%   |
| Team                | 21        | 28     | 0.54%   |
| Apacer              | 21        | 23     | 0.54%   |
| JMicron Technology  | 20        | 21     | 0.51%   |
| Seagate             | 17        | 24     | 0.43%   |
| KingSpec            | 17        | 20     | 0.43%   |
| Gigabyte Technology | 15        | 21     | 0.38%   |
| Netac               | 14        | 21     | 0.36%   |
| Leven               | 12        | 13     | 0.31%   |
| KingDian            | 11        | 11     | 0.28%   |
| Unknown             | 11        | 14     | 0.28%   |
| ASMT                | 10        | 14     | 0.26%   |
| TO Exter            | 9         | 12     | 0.23%   |
| Hewlett-Packard     | 9         | 13     | 0.23%   |
| NGFF                | 7         | 7      | 0.18%   |
| Mushkin             | 7         | 9      | 0.18%   |
| Hoodisk             | 6         | 6      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3329      | 5933   | 33%     |
| SSD     | 3297      | 5257   | 32.68%  |
| NVMe    | 3023      | 4357   | 29.96%  |
| MMC     | 273       | 348    | 2.71%   |
| Unknown | 167       | 222    | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5010      | 10708  | 57.02%  |
| NVMe | 3022      | 4343   | 34.4%   |
| SAS  | 481       | 718    | 5.47%   |
| MMC  | 273       | 348    | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3628      | 5990   | 51.19%  |
| 0.51-1.0   | 2298      | 3395   | 32.43%  |
| 1.01-2.0   | 650       | 943    | 9.17%   |
| 3.01-4.0   | 198       | 325    | 2.79%   |
| 4.01-10.0  | 149       | 276    | 2.1%    |
| 2.01-3.0   | 144       | 225    | 2.03%   |
| 10.01-20.0 | 20        | 36     | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1678      | 22.91%  |
| 251-500        | 1625      | 22.19%  |
| 501-1000       | 1179      | 16.1%   |
| 1001-2000      | 839       | 11.46%  |
| More than 3000 | 501       | 6.84%   |
| Unknown        | 431       | 5.89%   |
| 51-100         | 379       | 5.18%   |
| 2001-3000      | 322       | 4.4%    |
| 1-20           | 202       | 2.76%   |
| 21-50          | 167       | 2.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1506      | 19.66%  |
| 21-50          | 1243      | 16.23%  |
| 101-250        | 1241      | 16.2%   |
| 51-100         | 1031      | 13.46%  |
| 251-500        | 844       | 11.02%  |
| 501-1000       | 651       | 8.5%    |
| Unknown        | 431       | 5.63%   |
| 1001-2000      | 381       | 4.97%   |
| More than 3000 | 189       | 2.47%   |
| 2001-3000      | 137       | 1.79%   |
| 0              | 5         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 11        | 12     | 1.89%   |
| HGST HTS721010A9E630 1TB                            | 10        | 10     | 1.72%   |
| HGST HTS545050A7E680 500GB                          | 10        | 10     | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 8      | 1.37%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 9      | 1.2%    |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 9      | 1.2%    |
| HGST HTS545050A7E380 500GB                          | 7         | 7      | 1.2%    |
| WDC WD5000AAKX-001CA0 500GB                         | 6         | 8      | 1.03%   |
| Toshiba MQ01ABD050 500GB                            | 6         | 6      | 1.03%   |
| Seagate ST500LT012-9WS142 500GB                     | 6         | 23     | 1.03%   |
| WDC WD10EARS-00Y5B1 1TB                             | 5         | 5      | 0.86%   |
| Seagate ST9320325AS 320GB                           | 5         | 6      | 0.86%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 5         | 5      | 0.86%   |
| Samsung Electronics HD103SJ 1TB                     | 5         | 5      | 0.86%   |
| Hitachi HDS721010CLA332 1TB                         | 5         | 5      | 0.86%   |
| HGST HTS725050A7E630 500GB                          | 5         | 5      | 0.86%   |
| Crucial CT525MX300SSD1 528GB                        | 5         | 5      | 0.86%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 4         | 4      | 0.69%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 4      | 0.69%   |
| Seagate ST9500325AS 500GB                           | 4         | 5      | 0.69%   |
| Seagate ST3500413AS 500GB                           | 4         | 5      | 0.69%   |
| Seagate ST1000DX001-1CM162 1TB                      | 4         | 6      | 0.69%   |
| Seagate ST1000DM003-9YN162 1TB                      | 4         | 5      | 0.69%   |
| Samsung Electronics SSD 960 EVO 250GB               | 4         | 5      | 0.69%   |
| Samsung Electronics HD103UJ 1TB                     | 4         | 6      | 0.69%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 4      | 0.69%   |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 0.69%   |
| WDC WD20EARS-00MVWB0 2TB                            | 3         | 3      | 0.52%   |
| WDC WD15EARS-00MVWB0 1TB                            | 3         | 3      | 0.52%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 0.52%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 3         | 3      | 0.52%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3         | 3      | 0.52%   |
| WDC WD10EARX-00N0YB0 1TB                            | 3         | 4      | 0.52%   |
| Seagate ST9750420AS 752GB                           | 3         | 3      | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 0.52%   |
| Seagate ST4000DM000-1F2168 4TB                      | 3         | 11     | 0.52%   |
| Seagate ST31000524AS 1TB                            | 3         | 5      | 0.52%   |
| Seagate ST2000DX001-1CM164 2TB                      | 3         | 3      | 0.52%   |
| Seagate ST2000DM001-1CH164 2TB                      | 3         | 3      | 0.52%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 3         | 3      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 151       | 220    | 26.63%  |
| WDC                   | 132       | 153    | 23.28%  |
| HGST                  | 43        | 43     | 7.58%   |
| Samsung Electronics   | 42        | 49     | 7.41%   |
| Hitachi               | 38        | 41     | 6.7%    |
| Toshiba               | 37        | 44     | 6.53%   |
| Crucial               | 17        | 20     | 3%      |
| SanDisk               | 15        | 18     | 2.65%   |
| Kingston              | 15        | 15     | 2.65%   |
| Intel                 | 15        | 17     | 2.65%   |
| SK hynix              | 11        | 16     | 1.94%   |
| A-DATA Technology     | 8         | 9      | 1.41%   |
| Micron Technology     | 7         | 9      | 1.23%   |
| LITEON                | 3         | 3      | 0.53%   |
| Transcend             | 2         | 2      | 0.35%   |
| OCZ                   | 2         | 2      | 0.35%   |
| KingSpec              | 2         | 3      | 0.35%   |
| Corsair               | 2         | 6      | 0.35%   |
| ASMT                  | 2         | 6      | 0.35%   |
| Apacer                | 2         | 2      | 0.35%   |
| TwinMOS               | 1         | 1      | 0.18%   |
| SPCC                  | 1         | 1      | 0.18%   |
| Realtek Semiconductor | 1         | 1      | 0.18%   |
| Realtek               | 1         | 1      | 0.18%   |
| Phison                | 1         | 2      | 0.18%   |
| Patriot               | 1         | 1      | 0.18%   |
| Netac                 | 1         | 1      | 0.18%   |
| Maxtor                | 1         | 1      | 0.18%   |
| MaxDigital            | 1         | 1      | 0.18%   |
| MARSHAL               | 1         | 1      | 0.18%   |
| LITEONIT              | 1         | 1      | 0.18%   |
| JMicron Technology    | 1         | 1      | 0.18%   |
| Intenso               | 1         | 4      | 0.18%   |
| IM3D                  | 1         | 1      | 0.18%   |
| Hewlett-Packard       | 1         | 1      | 0.18%   |
| Fujitsu               | 1         | 1      | 0.18%   |
| Faspeed               | 1         | 1      | 0.18%   |
| Drevo                 | 1         | 1      | 0.18%   |
| China                 | 1         | 1      | 0.18%   |
| Apple                 | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 150       | 217    | 35.97%  |
| WDC                 | 129       | 150    | 30.94%  |
| HGST                | 43        | 43     | 10.31%  |
| Hitachi             | 38        | 41     | 9.11%   |
| Toshiba             | 33        | 40     | 7.91%   |
| Samsung Electronics | 20        | 25     | 4.8%    |
| Maxtor              | 1         | 1      | 0.24%   |
| MaxDigital          | 1         | 1      | 0.24%   |
| MARSHAL             | 1         | 1      | 0.24%   |
| Fujitsu             | 1         | 1      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 396       | 520    | 72.93%  |
| SSD  | 121       | 154    | 22.28%  |
| NVMe | 26        | 29     | 4.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4510      | 10023  | 58.29%  |
| Works    | 2688      | 5375   | 34.74%  |
| Malfunc  | 524       | 703    | 6.77%   |
| Failed   | 15        | 16     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4132      | 43.22%  |
| AMD                              | 1868      | 19.54%  |
| Samsung Electronics              | 1112      | 11.63%  |
| SanDisk                          | 519       | 5.43%   |
| SK hynix                         | 263       | 2.75%   |
| Phison Electronics               | 221       | 2.31%   |
| Kingston Technology Company      | 176       | 1.84%   |
| ASMedia Technology               | 175       | 1.83%   |
| Toshiba America Info Systems     | 133       | 1.39%   |
| Micron/Crucial Technology        | 123       | 1.29%   |
| Micron Technology                | 109       | 1.14%   |
| Silicon Motion                   | 101       | 1.06%   |
| KIOXIA                           | 93        | 0.97%   |
| Marvell Technology Group         | 80        | 0.84%   |
| ADATA Technology                 | 80        | 0.84%   |
| JMicron Technology               | 66        | 0.69%   |
| Nvidia                           | 62        | 0.65%   |
| Realtek Semiconductor            | 47        | 0.49%   |
| Union Memory (Shenzhen)          | 32        | 0.33%   |
| Solid State Storage Technology   | 22        | 0.23%   |
| Lite-On Technology               | 18        | 0.19%   |
| Apple                            | 18        | 0.19%   |
| Seagate Technology               | 16        | 0.17%   |
| Shenzhen Longsys Electronics     | 13        | 0.14%   |
| LSI Logic / Symbios Logic        | 10        | 0.1%    |
| VIA Technologies                 | 8         | 0.08%   |
| Lenovo                           | 7         | 0.07%   |
| Silicon Image                    | 6         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.06%   |
| Broadcom / LSI                   | 6         | 0.06%   |
| Yangtze Memory Technologies      | 5         | 0.05%   |
| Biwin Storage Technology         | 5         | 0.05%   |
| INNOGRIT                         | 4         | 0.04%   |
| Adaptec                          | 4         | 0.04%   |
| Transcend                        | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Unknown                          | 3         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.02%   |
| Netac Technology                 | 2         | 0.02%   |
| HighPoint Technologies           | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1400      | 12.94%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 606       | 5.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 389       | 3.59%   |
| AMD 400 Series Chipset SATA Controller                                         | 359       | 3.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 283       | 2.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 276       | 2.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 248       | 2.29%   |
| Samsung NVMe SSD Controller 980                                                | 183       | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 174       | 1.61%   |
| AMD 500 Series Chipset SATA Controller                                         | 174       | 1.61%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 172       | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 167       | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 166       | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 150       | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 147       | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 145       | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 141       | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 138       | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 136       | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 135       | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 135       | 1.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 130       | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 120       | 1.11%   |
| Intel SSD 660P Series                                                          | 119       | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 114       | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 109       | 1.01%   |
| Phison E12 NVMe Controller                                                     | 102       | 0.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 98        | 0.91%   |
| Intel SATA Controller [RAID mode]                                              | 97        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 95        | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                         | 89        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 88        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 83        | 0.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 78        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 73        | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 72        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 72        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 64        | 0.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 64        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 63        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5297      | 56.45%  |
| NVMe | 3027      | 32.26%  |
| RAID | 524       | 5.58%   |
| IDE  | 511       | 5.45%   |
| SAS  | 21        | 0.22%   |
| SCSI | 3         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4710      | 67.41%  |
| AMD    | 2276      | 32.57%  |
| ARM    | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 138       | 1.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 98        | 1.4%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 85        | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 82        | 1.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 78        | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 76        | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 76        | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 73        | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 71        | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 70        | 1%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 70        | 1%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 67        | 0.96%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 66        | 0.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 65        | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 62        | 0.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 56        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 55        | 0.78%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 55        | 0.78%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 54        | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 50        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 50        | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 48        | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 45        | 0.64%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 45        | 0.64%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 44        | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 43        | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 0.61%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 42        | 0.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 41        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.57%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 40        | 0.57%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 36        | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 36        | 0.51%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 36        | 0.51%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 35        | 0.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.47%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 32        | 0.46%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 32        | 0.46%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 30        | 0.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1552      | 22.16%  |
| Intel Core i7           | 1452      | 20.73%  |
| AMD Ryzen 5             | 753       | 10.75%  |
| AMD Ryzen 7             | 627       | 8.95%   |
| Intel Core i3           | 414       | 5.91%   |
| Other                   | 413       | 5.9%    |
| Intel Celeron           | 231       | 3.3%    |
| AMD Ryzen 9             | 176       | 2.51%   |
| Intel Core 2 Duo        | 147       | 2.1%    |
| Intel Xeon              | 135       | 1.93%   |
| Intel Pentium           | 126       | 1.8%    |
| AMD FX                  | 123       | 1.76%   |
| AMD Ryzen 3             | 107       | 1.53%   |
| Intel Core i9           | 50        | 0.71%   |
| Intel Atom              | 48        | 0.69%   |
| AMD Ryzen 7 PRO         | 45        | 0.64%   |
| AMD A10                 | 45        | 0.64%   |
| Intel Pentium Dual-Core | 44        | 0.63%   |
| AMD A8                  | 42        | 0.6%    |
| AMD A4                  | 36        | 0.51%   |
| Intel Core 2 Quad       | 30        | 0.43%   |
| AMD Ryzen Threadripper  | 30        | 0.43%   |
| AMD A6                  | 30        | 0.43%   |
| AMD Phenom II X4        | 29        | 0.41%   |
| Intel Pentium Silver    | 26        | 0.37%   |
| Intel Core 2            | 23        | 0.33%   |
| AMD Athlon              | 22        | 0.31%   |
| AMD E1                  | 21        | 0.3%    |
| AMD Athlon II X2        | 21        | 0.3%    |
| AMD E                   | 19        | 0.27%   |
| AMD Ryzen 5 PRO         | 18        | 0.26%   |
| AMD Phenom II X6        | 13        | 0.19%   |
| AMD Athlon 64 X2        | 13        | 0.19%   |
| Intel Pentium Gold      | 10        | 0.14%   |
| AMD E2                  | 10        | 0.14%   |
| Intel Pentium Dual      | 9         | 0.13%   |
| Intel Genuine           | 9         | 0.13%   |
| AMD Athlon X4           | 9         | 0.13%   |
| AMD Athlon II X4        | 9         | 0.13%   |
| Intel Core m3           | 7         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2545      | 36.36%  |
| 2       | 2156      | 30.8%   |
| 6       | 1062      | 15.17%  |
| 8       | 809       | 11.56%  |
| 12      | 148       | 2.11%   |
| 16      | 83        | 1.19%   |
| 3       | 53        | 0.76%   |
| 1       | 45        | 0.64%   |
| 14      | 41        | 0.59%   |
| 10      | 39        | 0.56%   |
| 24      | 8         | 0.11%   |
| 32      | 5         | 0.07%   |
| Unknown | 3         | 0.04%   |
| 20      | 2         | 0.03%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 6962      | 99.66%  |
| 2      | 23        | 0.33%   |
| 4      | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5337      | 76.28%  |
| 1       | 1657      | 23.68%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6890      | 98.53%  |
| Unknown        | 102       | 1.46%   |
| 64-bit         | 1         | 0.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3598      | 49.76%  |
| 0x306a9    | 220       | 3.04%   |
| 0x906ea    | 185       | 2.56%   |
| 0x306c3    | 170       | 2.35%   |
| 0x206a7    | 146       | 2.02%   |
| 0x08701021 | 143       | 1.98%   |
| 0x806ea    | 135       | 1.87%   |
| 0x806ec    | 128       | 1.77%   |
| 0x806c1    | 117       | 1.62%   |
| 0x0800820d | 105       | 1.45%   |
| 0x806e9    | 98        | 1.36%   |
| 0x906e9    | 87        | 1.2%    |
| 0x406e3    | 85        | 1.18%   |
| 0x506e3    | 82        | 1.13%   |
| 0x40651    | 79        | 1.09%   |
| 0x08701013 | 78        | 1.08%   |
| 0x0a50000c | 75        | 1.04%   |
| 0x08600106 | 75        | 1.04%   |
| 0x08108102 | 72        | 1%      |
| 0x1067a    | 69        | 0.95%   |
| 0x08108109 | 68        | 0.94%   |
| 0x306d4    | 63        | 0.87%   |
| 0x706e5    | 51        | 0.71%   |
| 0x06000852 | 51        | 0.71%   |
| 0x08600103 | 48        | 0.66%   |
| 0xa0652    | 47        | 0.65%   |
| 0x08600104 | 47        | 0.65%   |
| 0x806eb    | 45        | 0.62%   |
| 0x08608103 | 45        | 0.62%   |
| 0x20655    | 34        | 0.47%   |
| 0x08001138 | 32        | 0.44%   |
| 0x906a3    | 31        | 0.43%   |
| 0x010000c8 | 28        | 0.39%   |
| 0x0a201016 | 26        | 0.36%   |
| 0x0810100b | 26        | 0.36%   |
| 0x906ed    | 24        | 0.33%   |
| 0x406c4    | 24        | 0.33%   |
| 0x0a50000d | 24        | 0.33%   |
| 0x506c9    | 23        | 0.32%   |
| 0x306f2    | 23        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1337      | 19.09%  |
| Zen 2            | 636       | 9.08%   |
| Haswell          | 594       | 8.48%   |
| IvyBridge        | 453       | 6.47%   |
| Zen+             | 441       | 6.3%    |
| SandyBridge      | 386       | 5.51%   |
| Skylake          | 364       | 5.2%    |
| Zen 3            | 329       | 4.7%    |
| Unknown          | 279       | 3.98%   |
| Zen              | 220       | 3.14%   |
| TigerLake        | 204       | 2.91%   |
| Penryn           | 199       | 2.84%   |
| Broadwell        | 176       | 2.51%   |
| CometLake        | 162       | 2.31%   |
| Piledriver       | 155       | 2.21%   |
| Westmere         | 133       | 1.9%    |
| Silvermont       | 119       | 1.7%    |
| IceLake          | 115       | 1.64%   |
| K10              | 95        | 1.36%   |
| Goldmont plus    | 91        | 1.3%    |
| Core             | 82        | 1.17%   |
| Excavator        | 70        | 1%      |
| Alderlake Hybrid | 66        | 0.94%   |
| Goldmont         | 49        | 0.7%    |
| Nehalem          | 45        | 0.64%   |
| Steamroller      | 32        | 0.46%   |
| Bobcat           | 32        | 0.46%   |
| Puma             | 26        | 0.37%   |
| K8 Hammer        | 24        | 0.34%   |
| Jaguar           | 24        | 0.34%   |
| Bulldozer        | 19        | 0.27%   |
| K10 Llano        | 14        | 0.2%    |
| Bonnell          | 13        | 0.19%   |
| Tremont          | 7         | 0.1%    |
| NetBurst         | 6         | 0.09%   |
| K8 & K10 hybrid  | 5         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3613      | 42.18%  |
| Nvidia                     | 2752      | 32.13%  |
| AMD                        | 2191      | 25.58%  |
| ASPEED Technology          | 5         | 0.06%   |
| ATI Technologies           | 3         | 0.04%   |
| Matrox Electronics Systems | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 274       | 3.12%   |
| AMD Renoir                                                                               | 267       | 3.04%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 246       | 2.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 236       | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 228       | 2.6%    |
| Intel UHD Graphics 620                                                                   | 220       | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 210       | 2.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 180       | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 178       | 2.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 178       | 2.03%   |
| Intel HD Graphics 620                                                                    | 160       | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 158       | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 138       | 1.57%   |
| Intel HD Graphics 5500                                                                   | 136       | 1.55%   |
| Intel HD Graphics 630                                                                    | 126       | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 125       | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 107       | 1.22%   |
| Intel HD Graphics 530                                                                    | 102       | 1.16%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 100       | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 93        | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 93        | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 93        | 1.06%   |
| AMD Lucienne                                                                             | 88        | 1%      |
| Intel Core Processor Integrated Graphics Controller                                      | 77        | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 75        | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 74        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 74        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 72        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 71        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 70        | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 64        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 63        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 60        | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 57        | 0.65%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 56        | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 55        | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 53        | 0.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 51        | 0.58%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 49        | 0.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 48        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2298      | 32.64%  |
| 1 x AMD            | 1707      | 24.24%  |
| 1 x Nvidia         | 1410      | 20.03%  |
| Intel + Nvidia     | 1087      | 15.44%  |
| AMD + Nvidia       | 225       | 3.2%    |
| Intel + AMD        | 148       | 2.1%    |
| 2 x AMD            | 121       | 1.72%   |
| 2 x Nvidia         | 29        | 0.41%   |
| Other              | 4         | 0.06%   |
| 1 x ASPEED         | 4         | 0.06%   |
| 2 x Intel          | 3         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.01%   |
| 1 x Matrox         | 1         | 0.01%   |
| Intel + 2 x AMD    | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5130      | 72.59%  |
| Proprietary | 1922      | 27.2%   |
| Unknown     | 15        | 0.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4467      | 62.58%  |
| 1.01-2.0   | 589       | 8.25%   |
| 7.01-8.0   | 455       | 6.37%   |
| 0.01-0.5   | 451       | 6.32%   |
| 3.01-4.0   | 415       | 5.81%   |
| 0.51-1.0   | 291       | 4.08%   |
| 5.01-6.0   | 249       | 3.49%   |
| 8.01-16.0  | 134       | 1.88%   |
| 2.01-3.0   | 64        | 0.9%    |
| 16.01-24.0 | 21        | 0.29%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 909       | 11.04%  |
| AU Optronics            | 845       | 10.26%  |
| BOE                     | 759       | 9.22%   |
| Chimei Innolux          | 722       | 8.77%   |
| LG Display              | 718       | 8.72%   |
| Goldstar                | 474       | 5.76%   |
| Dell                    | 440       | 5.34%   |
| Acer                    | 307       | 3.73%   |
| AOC                     | 249       | 3.02%   |
| BenQ                    | 232       | 2.82%   |
| Ancor Communications    | 226       | 2.74%   |
| Hewlett-Packard         | 218       | 2.65%   |
| Philips                 | 182       | 2.21%   |
| Sharp                   | 167       | 2.03%   |
| Lenovo                  | 132       | 1.6%    |
| Apple                   | 122       | 1.48%   |
| LG Electronics          | 110       | 1.34%   |
| ViewSonic               | 101       | 1.23%   |
| PANDA                   | 101       | 1.23%   |
| ASUSTek Computer        | 90        | 1.09%   |
| Chi Mei Optoelectronics | 84        | 1.02%   |
| Iiyama                  | 65        | 0.79%   |
| Unknown                 | 53        | 0.64%   |
| Unknown                 | 47        | 0.57%   |
| InfoVision              | 46        | 0.56%   |
| Sony                    | 45        | 0.55%   |
| CSO                     | 32        | 0.39%   |
| Panasonic               | 29        | 0.35%   |
| MSI                     | 27        | 0.33%   |
| Vizio                   | 25        | 0.3%    |
| Fujitsu Siemens         | 24        | 0.29%   |
| Eizo                    | 24        | 0.29%   |
| NEC Computers           | 23        | 0.28%   |
| TMX                     | 22        | 0.27%   |
| Gigabyte Technology     | 22        | 0.27%   |
| Sceptre Tech            | 21        | 0.25%   |
| Toshiba                 | 18        | 0.22%   |
| LGD                     | 17        | 0.21%   |
| LG Philips              | 17        | 0.21%   |
| AUS                     | 17        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 48        | 0.56%   |
| Unknown                                                                  | 47        | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 46        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 42        | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 35        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 31        | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 30        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 25        | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 23        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 22        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 22        | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 21        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 20        | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 18        | 0.21%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 18        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 17        | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 17        | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.19%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 15        | 0.17%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 15        | 0.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 14        | 0.16%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 13        | 0.15%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 13        | 0.15%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch                 | 13        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.15%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                           | 13        | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.14%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.14%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 12        | 0.14%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 12        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3723      | 47.51%  |
| 1366x768 (WXGA)    | 1127      | 14.38%  |
| 3840x2160 (4K)     | 539       | 6.88%   |
| 2560x1440 (QHD)    | 467       | 5.96%   |
| 1600x900 (HD+)     | 215       | 2.74%   |
| Unknown            | 205       | 2.62%   |
| 1920x1200 (WUXGA)  | 173       | 2.21%   |
| 1680x1050 (WSXGA+) | 164       | 2.09%   |
| 1280x1024 (SXGA)   | 148       | 1.89%   |
| 1440x900 (WXGA+)   | 140       | 1.79%   |
| 3440x1440          | 106       | 1.35%   |
| 2560x1080          | 105       | 1.34%   |
| 1280x800 (WXGA)    | 94        | 1.2%    |
| 3840x1080          | 82        | 1.05%   |
| 2560x1600          | 73        | 0.93%   |
| 2880x1800          | 45        | 0.57%   |
| 1360x768           | 42        | 0.54%   |
| 2160x1440          | 29        | 0.37%   |
| 3840x2400          | 26        | 0.33%   |
| 1920x540           | 18        | 0.23%   |
| 5120x1440          | 14        | 0.18%   |
| 4480x1440          | 13        | 0.17%   |
| 3840x1600          | 13        | 0.17%   |
| 3200x1800 (QHD+)   | 13        | 0.17%   |
| 1280x720 (HD)      | 12        | 0.15%   |
| 3456x2160          | 11        | 0.14%   |
| 2256x1504          | 11        | 0.14%   |
| 1024x768 (XGA)     | 11        | 0.14%   |
| 5760x1080          | 10        | 0.13%   |
| 3200x2000          | 10        | 0.13%   |
| 2736x1824          | 9         | 0.11%   |
| 1600x1200          | 9         | 0.11%   |
| 5760x2160          | 8         | 0.1%    |
| 1920x1280          | 8         | 0.1%    |
| 3840x1200          | 7         | 0.09%   |
| 3600x1080          | 7         | 0.09%   |
| 3286x1080          | 7         | 0.09%   |
| 3000x2000          | 6         | 0.08%   |
| 2880x1920          | 6         | 0.08%   |
| 2520x1680          | 6         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2012      | 24.88%  |
| 13      | 772       | 9.55%   |
| Unknown | 640       | 7.91%   |
| 14      | 639       | 7.9%    |
| 27      | 629       | 7.78%   |
| 24      | 609       | 7.53%   |
| 23      | 496       | 6.13%   |
| 21      | 417       | 5.16%   |
| 17      | 355       | 4.39%   |
| 31      | 194       | 2.4%    |
| 34      | 165       | 2.04%   |
| 19      | 163       | 2.02%   |
| 12      | 113       | 1.4%    |
| 22      | 109       | 1.35%   |
| 18      | 102       | 1.26%   |
| 20      | 83        | 1.03%   |
| 16      | 71        | 0.88%   |
| 11      | 66        | 0.82%   |
| 84      | 52        | 0.64%   |
| 40      | 37        | 0.46%   |
| 32      | 35        | 0.43%   |
| 72      | 31        | 0.38%   |
| 54      | 31        | 0.38%   |
| 25      | 26        | 0.32%   |
| 28      | 21        | 0.26%   |
| 26      | 21        | 0.26%   |
| 65      | 17        | 0.21%   |
| 48      | 16        | 0.2%    |
| 37      | 16        | 0.2%    |
| 33      | 14        | 0.17%   |
| 49      | 13        | 0.16%   |
| 42      | 11        | 0.14%   |
| 29      | 11        | 0.14%   |
| 43      | 9         | 0.11%   |
| 52      | 8         | 0.1%    |
| 35      | 8         | 0.1%    |
| 46      | 7         | 0.09%   |
| 39      | 7         | 0.09%   |
| 36      | 7         | 0.09%   |
| 10      | 7         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3096      | 39.13%  |
| 501-600        | 1571      | 19.86%  |
| 401-500        | 770       | 9.73%   |
| Unknown        | 640       | 8.09%   |
| 201-300        | 571       | 7.22%   |
| 351-400        | 447       | 5.65%   |
| 601-700        | 289       | 3.65%   |
| 701-800        | 220       | 2.78%   |
| 1001-1500      | 109       | 1.38%   |
| 1501-2000      | 97        | 1.23%   |
| 801-900        | 73        | 0.92%   |
| 901-1000       | 21        | 0.27%   |
| 101-200        | 5         | 0.06%   |
| 1-100          | 2         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5357      | 74.4%   |
| 16/10   | 732       | 10.17%  |
| Unknown | 591       | 8.21%   |
| 21/9    | 189       | 2.63%   |
| 5/4     | 139       | 1.93%   |
| 3/2     | 104       | 1.44%   |
| 4/3     | 40        | 0.56%   |
| 32/9    | 21        | 0.29%   |
| 6/5     | 6         | 0.08%   |
| 0.56    | 5         | 0.07%   |
| 0.62    | 3         | 0.04%   |
| 3.40    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 1.00    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2011      | 25.12%  |
| 201-250        | 1315      | 16.43%  |
| 81-90          | 1100      | 13.74%  |
| 301-350        | 642       | 8.02%   |
| Unknown        | 640       | 8%      |
| 351-500        | 439       | 5.48%   |
| 151-200        | 342       | 4.27%   |
| 71-80          | 312       | 3.9%    |
| 121-130        | 256       | 3.2%    |
| 251-300        | 205       | 2.56%   |
| More than 1000 | 181       | 2.26%   |
| 141-150        | 137       | 1.71%   |
| 501-1000       | 115       | 1.44%   |
| 61-70          | 97        | 1.21%   |
| 51-60          | 69        | 0.86%   |
| 111-120        | 62        | 0.77%   |
| 131-140        | 45        | 0.56%   |
| 91-100         | 23        | 0.29%   |
| 1-40           | 7         | 0.09%   |
| 41-50          | 6         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2271      | 29.25%  |
| 51-100        | 2240      | 28.85%  |
| 101-120       | 1736      | 22.36%  |
| Unknown       | 640       | 8.24%   |
| 161-240       | 514       | 6.62%   |
| More than 240 | 214       | 2.76%   |
| 1-50          | 149       | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5507      | 77.18%  |
| 2     | 1385      | 19.41%  |
| 3     | 168       | 2.35%   |
| 0     | 59        | 0.83%   |
| 4     | 16        | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3964      | 37.74%  |
| Intel                             | 3617      | 34.44%  |
| Qualcomm Atheros                  | 1033      | 9.84%   |
| Broadcom                          | 421       | 4.01%   |
| MediaTek                          | 168       | 1.6%    |
| TP-Link                           | 134       | 1.28%   |
| Ralink Technology                 | 132       | 1.26%   |
| Broadcom Limited                  | 97        | 0.92%   |
| Ralink                            | 76        | 0.72%   |
| Marvell Technology Group          | 61        | 0.58%   |
| Microsoft                         | 50        | 0.48%   |
| Samsung Electronics               | 48        | 0.46%   |
| Xiaomi                            | 45        | 0.43%   |
| ASIX Electronics                  | 45        | 0.43%   |
| Nvidia                            | 44        | 0.42%   |
| Sierra Wireless                   | 36        | 0.34%   |
| Qualcomm Atheros Communications   | 32        | 0.3%    |
| Aquantia                          | 32        | 0.3%    |
| Huawei Technologies               | 29        | 0.28%   |
| ASUSTek Computer                  | 29        | 0.28%   |
| Lenovo                            | 28        | 0.27%   |
| DisplayLink                       | 27        | 0.26%   |
| NetGear                           | 25        | 0.24%   |
| Qualcomm                          | 24        | 0.23%   |
| D-Link                            | 24        | 0.23%   |
| Dell                              | 22        | 0.21%   |
| Linksys                           | 19        | 0.18%   |
| JMicron Technology                | 17        | 0.16%   |
| Hewlett-Packard                   | 16        | 0.15%   |
| Edimax Technology                 | 14        | 0.13%   |
| Ericsson Business Mobile Networks | 12        | 0.11%   |
| Google                            | 11        | 0.1%    |
| D-Link System                     | 10        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 9         | 0.09%   |
| Microchip Technology              | 9         | 0.09%   |
| Motorola PCS                      | 8         | 0.08%   |
| Mellanox Technologies             | 8         | 0.08%   |
| Fibocom                           | 8         | 0.08%   |
| Apple                             | 7         | 0.07%   |
| ZyXEL Communications              | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2772      | 22.47%  |
| Intel Wi-Fi 6 AX200                                               | 528       | 4.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 364       | 2.95%   |
| Intel I211 Gigabit Network Connection                             | 294       | 2.38%   |
| Intel Wireless 8265 / 8275                                        | 250       | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 211       | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 209       | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 201       | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 194       | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 190       | 1.54%   |
| Intel Wireless 7265                                               | 177       | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 157       | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 155       | 1.26%   |
| Intel Wireless 7260                                               | 152       | 1.23%   |
| Intel Wi-Fi 6 AX201                                               | 147       | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 132       | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 128       | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 128       | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 116       | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 112       | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 110       | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 107       | 0.87%   |
| Intel Wireless 8260                                               | 107       | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 104       | 0.84%   |
| Intel Ethernet Controller I225-V                                  | 100       | 0.81%   |
| Intel Wireless 3165                                               | 99        | 0.8%    |
| Intel Wireless-AC 9260                                            | 97        | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 96        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 93        | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 82        | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 82        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 79        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 75        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 70        | 0.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 67        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 64        | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 61        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 57        | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 53        | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2840      | 48.51%  |
| Realtek Semiconductor                 | 1010      | 17.25%  |
| Qualcomm Atheros                      | 809       | 13.82%  |
| Broadcom                              | 308       | 5.26%   |
| MediaTek                              | 154       | 2.63%   |
| Ralink Technology                     | 132       | 2.25%   |
| TP-Link                               | 127       | 2.17%   |
| Ralink                                | 76        | 1.3%    |
| Broadcom Limited                      | 71        | 1.21%   |
| Microsoft                             | 47        | 0.8%    |
| Sierra Wireless                       | 36        | 0.61%   |
| Qualcomm Atheros Communications       | 32        | 0.55%   |
| ASUSTek Computer                      | 27        | 0.46%   |
| NetGear                               | 25        | 0.43%   |
| D-Link                                | 24        | 0.41%   |
| Linksys                               | 18        | 0.31%   |
| Dell                                  | 16        | 0.27%   |
| Marvell Technology Group              | 15        | 0.26%   |
| Edimax Technology                     | 14        | 0.24%   |
| Qualcomm                              | 13        | 0.22%   |
| Fibocom                               | 8         | 0.14%   |
| D-Link System                         | 7         | 0.12%   |
| ZyXEL Communications                  | 6         | 0.1%    |
| Hewlett-Packard                       | 5         | 0.09%   |
| Belkin Components                     | 4         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| ZyDAS                                 | 3         | 0.05%   |
| Quectel Wireless Solutions            | 3         | 0.05%   |
| Mercucys                              | 3         | 0.05%   |
| IMC Networks                          | 3         | 0.05%   |
| AVM                                   | 3         | 0.05%   |
| Xiaomi                                | 2         | 0.03%   |
| Tenda                                 | 2         | 0.03%   |
| Samsung Electronics                   | 2         | 0.03%   |
| Wacom                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 528       | 8.94%   |
| Intel Wireless 8265 / 8275                                     | 250       | 4.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 201       | 3.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 190       | 3.22%   |
| Intel Wireless 7265                                            | 177       | 3%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 157       | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 155       | 2.63%   |
| Intel Wireless 7260                                            | 152       | 2.57%   |
| Intel Wi-Fi 6 AX201                                            | 147       | 2.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 132       | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 128       | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 116       | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 112       | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 110       | 1.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 107       | 1.81%   |
| Intel Wireless 8260                                            | 107       | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 104       | 1.76%   |
| Intel Wireless 3165                                            | 99        | 1.68%   |
| Intel Wireless-AC 9260                                         | 97        | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 96        | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 93        | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 82        | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 79        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 75        | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 70        | 1.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 67        | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 57        | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 49        | 0.83%   |
| Intel Wireless 3160                                            | 49        | 0.83%   |
| Realtek 802.11ac NIC                                           | 46        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 46        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 45        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 44        | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 44        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 43        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 43        | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 42        | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 41        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                  | 40        | 0.68%   |
| Intel Centrino Wireless-N 2230                                 | 38        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3550      | 57.37%  |
| Intel                                  | 1664      | 26.89%  |
| Qualcomm Atheros                       | 309       | 4.99%   |
| Broadcom                               | 171       | 2.76%   |
| Samsung Electronics                    | 46        | 0.74%   |
| Marvell Technology Group               | 46        | 0.74%   |
| ASIX Electronics                       | 45        | 0.73%   |
| Nvidia                                 | 44        | 0.71%   |
| Xiaomi                                 | 42        | 0.68%   |
| Aquantia                               | 32        | 0.52%   |
| Broadcom Limited                       | 29        | 0.47%   |
| Lenovo                                 | 28        | 0.45%   |
| DisplayLink                            | 27        | 0.44%   |
| Huawei Technologies                    | 19        | 0.31%   |
| JMicron Technology                     | 17        | 0.27%   |
| MediaTek                               | 11        | 0.18%   |
| Qualcomm                               | 10        | 0.16%   |
| Google                                 | 10        | 0.16%   |
| Mellanox Technologies                  | 8         | 0.13%   |
| TP-Link                                | 7         | 0.11%   |
| OPPO Electronics                       | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)          | 6         | 0.1%    |
| Apple                                  | 6         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 5         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.08%   |
| Motorola PCS                           | 5         | 0.08%   |
| ICS Advent                             | 4         | 0.06%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| Microsoft                              | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link System                          | 3         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| National Semiconductor                 | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Foxconn / Hon Hai                      | 2         | 0.03%   |
| Attansic Technology                    | 2         | 0.03%   |
| ASUSTek Computer                       | 2         | 0.03%   |
| VIA Technologies                       | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2772      | 43.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 364       | 5.74%   |
| Intel I211 Gigabit Network Connection                             | 294       | 4.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 211       | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 209       | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 194       | 3.06%   |
| Intel Ethernet Connection (2) I219-V                              | 128       | 2.02%   |
| Intel Ethernet Controller I225-V                                  | 100       | 1.58%   |
| Intel Ethernet Connection I217-LM                                 | 82        | 1.29%   |
| Intel Ethernet Connection (7) I219-V                              | 64        | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 61        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 53        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 50        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 47        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 44        | 0.69%   |
| Intel Ethernet Connection (2) I218-V                              | 44        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 42        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 37        | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 36        | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 35        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 33        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 32        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 29        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 29        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 28        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 28        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 23        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 0.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.36%   |
| Intel Ethernet Connection I219-V                                  | 22        | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5812      | 50.88%  |
| WiFi     | 5525      | 48.36%  |
| Modem    | 75        | 0.66%   |
| Unknown  | 12        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4326      | 59.14%  |
| Ethernet | 2988      | 40.85%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3676      | 52.39%  |
| 1     | 3078      | 43.87%  |
| 3     | 166       | 2.37%   |
| 0     | 76        | 1.08%   |
| 4     | 10        | 0.14%   |
| 5     | 8         | 0.11%   |
| 8     | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5854      | 82.33%  |
| Yes  | 1256      | 17.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2430      | 50.69%  |
| Realtek Semiconductor           | 519       | 10.83%  |
| Cambridge Silicon Radio         | 365       | 7.61%   |
| Qualcomm Atheros Communications | 349       | 7.28%   |
| IMC Networks                    | 201       | 4.19%   |
| Broadcom                        | 157       | 3.27%   |
| Lite-On Technology              | 154       | 3.21%   |
| Apple                           | 119       | 2.48%   |
| ASUSTek Computer                | 114       | 2.38%   |
| Foxconn / Hon Hai               | 107       | 2.23%   |
| Realtek                         | 49        | 1.02%   |
| MediaTek                        | 30        | 0.63%   |
| Ralink                          | 26        | 0.54%   |
| Dell                            | 24        | 0.5%    |
| Hewlett-Packard                 | 23        | 0.48%   |
| TP-Link                         | 19        | 0.4%    |
| Toshiba                         | 15        | 0.31%   |
| Marvell Semiconductor           | 12        | 0.25%   |
| Opticis                         | 9         | 0.19%   |
| Foxconn International           | 9         | 0.19%   |
| Edimax Technology               | 9         | 0.19%   |
| Dynex                           | 7         | 0.15%   |
| Ralink Technology               | 6         | 0.13%   |
| Alps Electric                   | 6         | 0.13%   |
| HTC (High Tech Computer)        | 5         | 0.1%    |
| Belkin Components               | 5         | 0.1%    |
| SINO WEALTH                     | 4         | 0.08%   |
| Conwise Technology              | 4         | 0.08%   |
| Askey Computer                  | 4         | 0.08%   |
| USI                             | 3         | 0.06%   |
| Integrated System Solution      | 3         | 0.06%   |
| Fujitsu                         | 2         | 0.04%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 787       | 16.39%  |
| Intel AX200 Bluetooth                               | 501       | 10.44%  |
| Intel AX201 Bluetooth                               | 367       | 7.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 365       | 7.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 354       | 7.37%   |
| Realtek Bluetooth Radio                             | 337       | 7.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 177       | 3.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 133       | 2.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 112       | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 91        | 1.9%    |
| IMC Networks Bluetooth Radio                        | 80        | 1.67%   |
| Intel AX210 Bluetooth                               | 76        | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 65        | 1.35%   |
| Intel Bluetooth Device                              | 64        | 1.33%   |
| Apple Bluetooth Host Controller                     | 57        | 1.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 51        | 1.06%   |
| Realtek Bluetooth Radio                             | 49        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 1%      |
| Lite-On Bluetooth Device                            | 45        | 0.94%   |
| IMC Networks Wireless_Device                        | 45        | 0.94%   |
| IMC Networks Bluetooth Device                       | 45        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 41        | 0.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 41        | 0.85%   |
| Apple Bluetooth USB Host Controller                 | 41        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 39        | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 39        | 0.81%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 39        | 0.81%   |
| MediaTek Wireless_Device                            | 28        | 0.58%   |
| Ralink RT3290 Bluetooth                             | 26        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 22        | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 21        | 0.44%   |
| ASUS ASUS USB-BT500                                 | 20        | 0.42%   |
| TP-Link UB5A Adapter                                | 19        | 0.4%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.4%    |
| Lite-On Wireless_Device                             | 18        | 0.37%   |
| ASUS Bluetooth Radio                                | 18        | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 17        | 0.35%   |
| Realtek RTL8821A Bluetooth                          | 17        | 0.35%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4601      | 43.77%  |
| AMD                                  | 2585      | 24.59%  |
| Nvidia                               | 1883      | 17.91%  |
| C-Media Electronics                  | 239       | 2.27%   |
| Logitech                             | 101       | 0.96%   |
| Creative Labs                        | 71        | 0.68%   |
| Kingston Technology                  | 66        | 0.63%   |
| JMTek                                | 59        | 0.56%   |
| Texas Instruments                    | 53        | 0.5%    |
| SteelSeries ApS                      | 42        | 0.4%    |
| Focusrite-Novation                   | 41        | 0.39%   |
| Realtek Semiconductor                | 38        | 0.36%   |
| Corsair                              | 38        | 0.36%   |
| Razer USA                            | 37        | 0.35%   |
| Creative Technology                  | 37        | 0.35%   |
| Generalplus Technology               | 36        | 0.34%   |
| ASUSTek Computer                     | 35        | 0.33%   |
| Lenovo                               | 29        | 0.28%   |
| GN Netcom                            | 29        | 0.28%   |
| Blue Microphones                     | 28        | 0.27%   |
| Plantronics                          | 27        | 0.26%   |
| BEHRINGER International              | 23        | 0.22%   |
| Sony                                 | 17        | 0.16%   |
| GYROCOM C&C                          | 17        | 0.16%   |
| Apple                                | 14        | 0.13%   |
| Samson Technologies                  | 13        | 0.12%   |
| Sennheiser Communications            | 12        | 0.11%   |
| RODE Microphones                     | 11        | 0.1%    |
| M-Audio                              | 11        | 0.1%    |
| VIA Technologies                     | 10        | 0.1%    |
| XMOS                                 | 9         | 0.09%   |
| Turtle Beach                         | 9         | 0.09%   |
| SAVITECH                             | 9         | 0.09%   |
| Micro Star International             | 9         | 0.09%   |
| Giga-Byte Technology                 | 9         | 0.09%   |
| Audio-Technica                       | 9         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 8         | 0.08%   |
| Microsoft                            | 8         | 0.08%   |
| Dell                                 | 8         | 0.08%   |
| DCMT Technology                      | 8         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 940       | 7.4%    |
| Intel Sunrise Point-LP HD Audio                                            | 573       | 4.51%   |
| AMD Starship/Matisse HD Audio Controller                                   | 473       | 3.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 464       | 3.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 441       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 349       | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 338       | 2.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 314       | 2.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 311       | 2.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 282       | 2.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 250       | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 215       | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 204       | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 203       | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 198       | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 185       | 1.46%   |
| Intel 8 Series HD Audio Controller                                         | 183       | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 182       | 1.43%   |
| AMD FCH Azalia Controller                                                  | 162       | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 160       | 1.26%   |
| Intel Broadwell-U Audio Controller                                         | 160       | 1.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 159       | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                              | 157       | 1.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 145       | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 144       | 1.13%   |
| Intel 200 Series PCH HD Audio                                              | 144       | 1.13%   |
| Nvidia GP104 High Definition Audio Controller                              | 143       | 1.13%   |
| AMD Navi 10 HDMI Audio                                                     | 126       | 0.99%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 112       | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 111       | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 109       | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 108       | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 107       | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 106       | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 102       | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 94        | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 93        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 91        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 91        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 88        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1104      | 22.83%  |
| SK hynix                     | 725       | 14.99%  |
| Kingston                     | 577       | 11.93%  |
| Micron Technology            | 497       | 10.28%  |
| Corsair                      | 362       | 7.49%   |
| Crucial                      | 315       | 6.51%   |
| Unknown                      | 311       | 6.43%   |
| G.Skill                      | 268       | 5.54%   |
| A-DATA Technology            | 111       | 2.3%    |
| Ramaxel Technology           | 75        | 1.55%   |
| Elpida                       | 61        | 1.26%   |
| Team                         | 55        | 1.14%   |
| Patriot                      | 47        | 0.97%   |
| Nanya Technology             | 43        | 0.89%   |
| Unknown (ABCD)               | 33        | 0.68%   |
| GOODRAM                      | 28        | 0.58%   |
| Smart                        | 22        | 0.46%   |
| Unknown                      | 21        | 0.43%   |
| Transcend                    | 20        | 0.41%   |
| AMD                          | 11        | 0.23%   |
| Apacer                       | 10        | 0.21%   |
| Silicon Power                | 7         | 0.14%   |
| Kllisre                      | 7         | 0.14%   |
| ASint Technology             | 7         | 0.14%   |
| PNY                          | 5         | 0.1%    |
| Neo Forza                    | 5         | 0.1%    |
| GeIL                         | 5         | 0.1%    |
| Teikon                       | 4         | 0.08%   |
| Smart Brazil                 | 4         | 0.08%   |
| Qumo                         | 4         | 0.08%   |
| Kingmax                      | 4         | 0.08%   |
| Goldkey                      | 4         | 0.08%   |
| Avant                        | 4         | 0.08%   |
| Atermiter                    | 4         | 0.08%   |
| Timetec                      | 3         | 0.06%   |
| SHARETRONIC                  | 3         | 0.06%   |
| Patriot Memory (PDP Systems) | 3         | 0.06%   |
| CSX                          | 3         | 0.06%   |
| Unknown (08C8)               | 2         | 0.04%   |
| TwinMOS                      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 60        | 1.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 58        | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 49        | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 46        | 0.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 45        | 0.87%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 42        | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 37        | 0.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 34        | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 34        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 30        | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 27        | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 26        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.46%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 22        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 21        | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 21        | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 21        | 0.41%   |
| Unknown                                                          | 21        | 0.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 20        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 20        | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.35%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 18        | 0.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 17        | 0.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.33%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 17        | 0.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 17        | 0.33%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 17        | 0.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.31%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2363      | 56.61%  |
| DDR3    | 1155      | 27.67%  |
| LPDDR4  | 177       | 4.24%   |
| LPDDR3  | 129       | 3.09%   |
| Unknown | 87        | 2.08%   |
| DDR2    | 78        | 1.87%   |
| SDRAM   | 77        | 1.84%   |
| DDR5    | 64        | 1.53%   |
| LPDDR5  | 26        | 0.62%   |
| DDR     | 13        | 0.31%   |
| DRAM    | 5         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2264      | 54.32%  |
| DIMM         | 1481      | 35.53%  |
| Row Of Chips | 381       | 9.14%   |
| Chip         | 22        | 0.53%   |
| Unknown      | 14        | 0.34%   |
| RIMM         | 3         | 0.07%   |
| FB-DIMM      | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2033      | 44.84%  |
| 4096  | 1161      | 25.61%  |
| 16384 | 723       | 15.95%  |
| 2048  | 362       | 7.98%   |
| 32768 | 177       | 3.9%    |
| 1024  | 70        | 1.54%   |
| 512   | 5         | 0.11%   |
| 65536 | 1         | 0.02%   |
| 12288 | 1         | 0.02%   |
| 3072  | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 797       | 17.46%  |
| 1600    | 797       | 17.46%  |
| 2667    | 768       | 16.82%  |
| 2400    | 338       | 7.4%    |
| 2133    | 245       | 5.37%   |
| 1333    | 208       | 4.56%   |
| 3600    | 188       | 4.12%   |
| 1334    | 105       | 2.3%    |
| 1867    | 104       | 2.28%   |
| 4267    | 76        | 1.66%   |
| 3266    | 75        | 1.64%   |
| 800     | 59        | 1.29%   |
| 3400    | 54        | 1.18%   |
| 3000    | 54        | 1.18%   |
| 667     | 50        | 1.1%    |
| 4800    | 43        | 0.94%   |
| Unknown | 39        | 0.85%   |
| 3733    | 36        | 0.79%   |
| 1866    | 36        | 0.79%   |
| 3533    | 35        | 0.77%   |
| 3800    | 34        | 0.74%   |
| 1067    | 33        | 0.72%   |
| 3866    | 29        | 0.64%   |
| 6400    | 27        | 0.59%   |
| 4199    | 26        | 0.57%   |
| 3466    | 26        | 0.57%   |
| 1800    | 25        | 0.55%   |
| 2933    | 24        | 0.53%   |
| 1066    | 22        | 0.48%   |
| 4266    | 19        | 0.42%   |
| 2666    | 17        | 0.37%   |
| 2800    | 16        | 0.35%   |
| 3666    | 12        | 0.26%   |
| 2048    | 12        | 0.26%   |
| 975     | 9         | 0.2%    |
| 6000    | 8         | 0.18%   |
| 3534    | 8         | 0.18%   |
| 8400    | 7         | 0.15%   |
| 5200    | 7         | 0.15%   |
| 333     | 7         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 59        | 38.31%  |
| Brother Industries    | 28        | 18.18%  |
| Canon                 | 21        | 13.64%  |
| Seiko Epson           | 14        | 9.09%   |
| Samsung Electronics   | 9         | 5.84%   |
| Pantum                | 3         | 1.95%   |
| Apple                 | 3         | 1.95%   |
| Xerox                 | 2         | 1.3%    |
| Ricoh                 | 2         | 1.3%    |
| Prolific Technology   | 2         | 1.3%    |
| Dymo-CoStar           | 2         | 1.3%    |
| Zebra                 | 1         | 0.65%   |
| Xiaomi                | 1         | 0.65%   |
| STMicroelectronics    | 1         | 0.65%   |
| Sagem                 | 1         | 0.65%   |
| QinHeng Electronics   | 1         | 0.65%   |
| Oki Data              | 1         | 0.65%   |
| Lexmark International | 1         | 0.65%   |
| Kyocera               | 1         | 0.65%   |
| Graphtec America      | 1         | 0.65%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                                  | 4         | 2.58%   |
| HP LaserJet 1300                                          | 3         | 1.94%   |
| HP ENVY 4520 series                                       | 3         | 1.94%   |
| Apple Gamesir-T1s 2.0b                                    | 3         | 1.94%   |
| Xerox Phaser 3020                                         | 2         | 1.29%   |
| Seiko Epson L120 Series                                   | 2         | 1.29%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 1.29%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.29%   |
| HP Officejet 2620 series                                  | 2         | 1.29%   |
| HP DeskJet 4530 series                                    | 2         | 1.29%   |
| HP DeskJet 3630 series                                    | 2         | 1.29%   |
| HP DeskJet 2700 series                                    | 2         | 1.29%   |
| HP DeskJet 2600 series                                    | 2         | 1.29%   |
| HP DeskJet 2130 series                                    | 2         | 1.29%   |
| HP Color LaserJet Pro M453-4                              | 2         | 1.29%   |
| Canon PIXMA MX340                                         | 2         | 1.29%   |
| Canon PIXMA MG2500 Series                                 | 2         | 1.29%   |
| Canon MG5700 series                                       | 2         | 1.29%   |
| Canon G3010 series                                        | 2         | 1.29%   |
| Brother MFC-L2710DW series                                | 2         | 1.29%   |
| Brother HL-L2300D series                                  | 2         | 1.29%   |
| Brother HL-5370DW series                                  | 2         | 1.29%   |
| Brother HL-1110 series                                    | 2         | 1.29%   |
| Brother DCP-7040                                          | 2         | 1.29%   |
| Zebra ZTC ZC100                                           | 1         | 0.65%   |
| Xiaomi MiMouse 2                                          | 1         | 0.65%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.65%   |
| Seiko Epson XP-4100 Series                                | 1         | 0.65%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.65%   |
| Seiko Epson Printer                                       | 1         | 0.65%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.65%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.65%   |
| Seiko Epson L805 Series                                   | 1         | 0.65%   |
| Seiko Epson L365 Series                                   | 1         | 0.65%   |
| Seiko Epson L355 Series                                   | 1         | 0.65%   |
| Seiko Epson ET-4760 Series                                | 1         | 0.65%   |
| Seiko Epson ET-3850 Series                                | 1         | 0.65%   |
| Seiko Epson ET-2850 Series                                | 1         | 0.65%   |
| Seiko Epson ET-2810 Series                                | 1         | 0.65%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 21        | 63.64%  |
| Seiko Epson        | 6         | 18.18%  |
| Hewlett-Packard    | 2         | 6.06%   |
| Visioneer          | 1         | 3.03%   |
| Ultima Electronics | 1         | 3.03%   |
| Mustek Systems     | 1         | 3.03%   |
| AGFA-Gevaert NV    | 1         | 3.03%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 5         | 15.15%  |
| Canon CanoScan LiDE 110                                                               | 5         | 15.15%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 6.06%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 2         | 6.06%   |
| Canon CanoScan LIDE 25                                                                | 2         | 6.06%   |
| Canon CanoScan LiDE 210                                                               | 2         | 6.06%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 3.03%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 3.03%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 3.03%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 3.03%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 3.03%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 3.03%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 3.03%   |
| HP ScanJet 3500c                                                                      | 1         | 3.03%   |
| HP ScanJet 3400cse                                                                    | 1         | 3.03%   |
| Canon CanoScan LiDE 90                                                                | 1         | 3.03%   |
| Canon CanoScan LiDE 500F                                                              | 1         | 3.03%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 3.03%   |
| Canon CanoScan LiDE 200                                                               | 1         | 3.03%   |
| Canon CanoScan LiDE 120                                                               | 1         | 3.03%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 3.03%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 913       | 20.21%  |
| IMC Networks                           | 524       | 11.6%   |
| Microdia                               | 349       | 7.73%   |
| Realtek Semiconductor                  | 332       | 7.35%   |
| Logitech                               | 323       | 7.15%   |
| Quanta                                 | 251       | 5.56%   |
| Bison Electronics                      | 230       | 5.09%   |
| Sunplus Innovation Technology          | 197       | 4.36%   |
| Cheng Uei Precision Industry (Foxlink) | 154       | 3.41%   |
| Syntek                                 | 125       | 2.77%   |
| Lite-On Technology                     | 119       | 2.63%   |
| Acer                                   | 105       | 2.32%   |
| Apple                                  | 99        | 2.19%   |
| Suyin                                  | 95        | 2.1%    |
| Microsoft                              | 71        | 1.57%   |
| Luxvisions Innotech Limited            | 63        | 1.39%   |
| Silicon Motion                         | 59        | 1.31%   |
| Alcor Micro                            | 52        | 1.15%   |
| Samsung Electronics                    | 51        | 1.13%   |
| Z-Star Microelectronics                | 26        | 0.58%   |
| Sonix Technology                       | 23        | 0.51%   |
| Ricoh                                  | 21        | 0.46%   |
| Creative Technology                    | 15        | 0.33%   |
| MacroSilicon                           | 14        | 0.31%   |
| Lenovo                                 | 14        | 0.31%   |
| SunplusIT                              | 13        | 0.29%   |
| Importek                               | 13        | 0.29%   |
| GEMBIRD                                | 13        | 0.29%   |
| Generalplus Technology                 | 11        | 0.24%   |
| Genesys Logic                          | 10        | 0.22%   |
| ARC International                      | 10        | 0.22%   |
| Primax Electronics                     | 9         | 0.2%    |
| LG Electronics                         | 9         | 0.2%    |
| KYE Systems (Mouse Systems)            | 9         | 0.2%    |
| Cubeternet                             | 9         | 0.2%    |
| Google                                 | 8         | 0.18%   |
| webcamvendor                           | 7         | 0.15%   |
| DigiTech                               | 7         | 0.15%   |
| ALi                                    | 7         | 0.15%   |
| icSpring                               | 6         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 233       | 5.12%   |
| IMC Networks Integrated Camera                      | 175       | 3.84%   |
| Microdia Integrated_Webcam_HD                       | 151       | 3.32%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 132       | 2.9%    |
| Realtek Integrated_Webcam_HD                        | 124       | 2.72%   |
| Syntek Integrated Camera                            | 85        | 1.87%   |
| Chicony HD WebCam                                   | 84        | 1.85%   |
| Bison Integrated Camera                             | 84        | 1.85%   |
| Logitech Webcam C270                                | 75        | 1.65%   |
| Logitech HD Pro Webcam C920                         | 72        | 1.58%   |
| Sunplus Integrated_Webcam_HD                        | 70        | 1.54%   |
| Samsung Galaxy series, misc. (MTP mode)             | 51        | 1.12%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 49        | 1.08%   |
| Quanta HD User Facing                               | 41        | 0.9%    |
| Lite-On Integrated Camera                           | 41        | 0.9%    |
| Chicony HP Wide Vision HD Camera                    | 40        | 0.88%   |
| Bison HD Webcam                                     | 37        | 0.81%   |
| Quanta HP TrueVision HD Camera                      | 36        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 34        | 0.75%   |
| Chicony USB2.0 Camera                               | 32        | 0.7%    |
| Chicony HP HD Camera                                | 32        | 0.7%    |
| Acer Integrated Camera                              | 29        | 0.64%   |
| Chicony HD User Facing                              | 28        | 0.62%   |
| Quanta HP Wide Vision HD Camera                     | 26        | 0.57%   |
| Microsoft LifeCam HD-3000                           | 26        | 0.57%   |
| Microdia Webcam Vitade AF                           | 26        | 0.57%   |
| Microdia USB 2.0 Camera                             | 26        | 0.57%   |
| Microdia Integrated Webcam                          | 26        | 0.57%   |
| Logitech C922 Pro Stream Webcam                     | 26        | 0.57%   |
| Lite-On HP HD Camera                                | 26        | 0.57%   |
| Quanta HD Webcam                                    | 25        | 0.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 25        | 0.55%   |
| Chicony USB2.0 HD UVC WebCam                        | 25        | 0.55%   |
| Chicony HP TrueVision HD Camera                     | 25        | 0.55%   |
| Chicony EasyCamera                                  | 25        | 0.55%   |
| Bison SunplusIT Integrated Camera                   | 25        | 0.55%   |
| Realtek USB Camera                                  | 24        | 0.53%   |
| Chicony Lenovo EasyCamera                           | 24        | 0.53%   |
| IMC Networks HD Camera                              | 23        | 0.51%   |
| Chicony HP Truevision HD                            | 23        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 286       | 31.02%  |
| Validity Sensors                   | 268       | 29.07%  |
| Shenzhen Goodix Technology         | 189       | 20.5%   |
| Elan Microelectronics              | 67        | 7.27%   |
| LighTuning Technology              | 37        | 4.01%   |
| Upek                               | 27        | 2.93%   |
| AuthenTec                          | 23        | 2.49%   |
| STMicroelectronics                 | 8         | 0.87%   |
| Samsung Electronics                | 6         | 0.65%   |
| Focal-systems.Corp                 | 4         | 0.43%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.22%   |
| DigitalPersona                     | 2         | 0.22%   |
| HOLTEK                             | 1         | 0.11%   |
| Futronic Technology                | 1         | 0.11%   |
| Dell                               | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 93        | 10.09%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 69        | 7.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 67        | 7.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 55        | 5.97%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 40        | 4.34%   |
| Synaptics UWP WBDI                                                         | 37        | 4.01%   |
| Elan ELAN:Fingerprint                                                      | 33        | 3.58%   |
| Validity Sensors Synaptics WBDI                                            | 32        | 3.47%   |
| Synaptics WBDI                                                             | 31        | 3.36%   |
| Shenzhen Goodix FingerPrint                                                | 29        | 3.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 3.04%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 2.6%    |
| Synaptics Fingerprint reader [HP G6]                                       | 24        | 2.6%    |
| Synaptics  WBDI                                                            | 23        | 2.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 2.49%   |
| Elan ELAN:ARM-M4                                                           | 22        | 2.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.06%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 2.06%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 1.95%   |
| Validity Sensors VFS491                                                    | 18        | 1.95%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.63%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 15        | 1.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.41%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.41%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 11        | 1.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 0.98%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.87%   |
| Elan WBF Fingerprint Sensor                                                | 8         | 0.87%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.87%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.76%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 0.65%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.54%   |
| Synaptics WBDI Device                                                      | 5         | 0.54%   |
| AuthenTec AES2810                                                          | 5         | 0.54%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.43%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 4         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 100       | 34.97%  |
| Broadcom                          | 96        | 33.57%  |
| Upek                              | 18        | 6.29%   |
| O2 Micro                          | 18        | 6.29%   |
| Lenovo                            | 16        | 5.59%   |
| Yubico.com                        | 9         | 3.15%   |
| Gemalto (was Gemplus)             | 9         | 3.15%   |
| VASCO Data Security International | 4         | 1.4%    |
| Realtek Semiconductor             | 4         | 1.4%    |
| OmniKey                           | 3         | 1.05%   |
| SCM Microsystems                  | 1         | 0.35%   |
| Reiner SCT Kartensysteme          | 1         | 0.35%   |
| Hewlett-Packard                   | 1         | 0.35%   |
| Clay Logic                        | 1         | 0.35%   |
| Cherry                            | 1         | 0.35%   |
| C3PO                              | 1         | 0.35%   |
| BIT4ID                            | 1         | 0.35%   |
| Aladdin Knowledge Systems         | 1         | 0.35%   |
| Advanced Card Systems             | 1         | 0.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 99        | 34.62%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 12.24%  |
| Broadcom 5880                                                                | 28        | 9.79%   |
| Broadcom 58200                                                               | 21        | 7.34%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 6.29%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 5.94%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 4.2%    |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.45%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 2.1%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 1.4%    |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 1.05%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.7%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.7%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.7%    |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.35%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.35%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.35%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.35%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.35%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.35%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.35%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.35%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.35%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.35%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.35%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.35%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.35%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4971      | 69.78%  |
| 1     | 1755      | 24.64%  |
| 2     | 365       | 5.12%   |
| 3     | 29        | 0.41%   |
| 4     | 4         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 905       | 36.06%  |
| Graphics card            | 432       | 17.21%  |
| Net/wireless             | 325       | 12.95%  |
| Chipcard                 | 252       | 10.04%  |
| Multimedia controller    | 204       | 8.13%   |
| Camera                   | 86        | 3.43%   |
| Net/ethernet             | 64        | 2.55%   |
| Unassigned class         | 59        | 2.35%   |
| Bluetooth                | 49        | 1.95%   |
| Sound                    | 27        | 1.08%   |
| Communication controller | 25        | 1%      |
| Storage                  | 21        | 0.84%   |
| Card reader              | 17        | 0.68%   |
| Dvb card                 | 14        | 0.56%   |
| Network                  | 10        | 0.4%    |
| Storage/raid             | 7         | 0.28%   |
| Modem                    | 5         | 0.2%    |
| Video                    | 2         | 0.08%   |
| Storage/nvme             | 2         | 0.08%   |
| Storage/ide              | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

