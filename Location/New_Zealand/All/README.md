Linux in New Zealand - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in New Zealand.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/New_Zealand/Desktop/README.md) and [notebooks](/Location/New_Zealand/Notebook/README.md).

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

Total: 1590

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Precision 3571              | Notebook    | [95b1b27d71](https://linux-hardware.org/?probe=95b1b27d71) | Jan 06, 2025 |
| HP            | EliteBook 8460p             | Notebook    | [0a8d680cf0](https://linux-hardware.org/?probe=0a8d680cf0) | Jan 05, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [ec0eaf35ef](https://linux-hardware.org/?probe=ec0eaf35ef) | Jan 03, 2025 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [a4c7be2f1a](https://linux-hardware.org/?probe=a4c7be2f1a) | Jan 03, 2025 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [5d9f2b4584](https://linux-hardware.org/?probe=5d9f2b4584) | Jan 03, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [68304adc38](https://linux-hardware.org/?probe=68304adc38) | Jan 02, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ae6fbefd79](https://linux-hardware.org/?probe=ae6fbefd79) | Jan 01, 2025 |
| HP            | ENVY Notebook               | Notebook    | [b6d4605e3e](https://linux-hardware.org/?probe=b6d4605e3e) | Jan 01, 2025 |
| HP            | 1494                        | Desktop     | [9c53750126](https://linux-hardware.org/?probe=9c53750126) | Jan 01, 2025 |
| HP            | 1494                        | Desktop     | [a0f989d505](https://linux-hardware.org/?probe=a0f989d505) | Dec 31, 2024 |
| Dell          | Latitude E6420              | Notebook    | [46c2760e4e](https://linux-hardware.org/?probe=46c2760e4e) | Dec 31, 2024 |
| HP            | 83F2                        | Desktop     | [28232611f8](https://linux-hardware.org/?probe=28232611f8) | Dec 27, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [fc2486e691](https://linux-hardware.org/?probe=fc2486e691) | Dec 26, 2024 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [244ba13e5e](https://linux-hardware.org/?probe=244ba13e5e) | Dec 25, 2024 |
| ASRock        | B760M Pro-A WiFi            | Desktop     | [8323aa21ad](https://linux-hardware.org/?probe=8323aa21ad) | Dec 24, 2024 |
| ASRock        | B760M Pro-A WiFi            | Desktop     | [3946d0bb57](https://linux-hardware.org/?probe=3946d0bb57) | Dec 20, 2024 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [0ae519bf73](https://linux-hardware.org/?probe=0ae519bf73) | Dec 18, 2024 |
| ASRock        | B760M Pro RS/D4 WiFi        | Desktop     | [34bf804bd1](https://linux-hardware.org/?probe=34bf804bd1) | Dec 17, 2024 |
| MAXSUN        | MS-Challenger B450M         | Desktop     | [32a2c0a5bf](https://linux-hardware.org/?probe=32a2c0a5bf) | Dec 17, 2024 |
| HP            | 1495                        | Desktop     | [81994e4b0e](https://linux-hardware.org/?probe=81994e4b0e) | Dec 17, 2024 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [8eeff9db9d](https://linux-hardware.org/?probe=8eeff9db9d) | Dec 14, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [42b3bd140f](https://linux-hardware.org/?probe=42b3bd140f) | Dec 13, 2024 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [8b53c864fe](https://linux-hardware.org/?probe=8b53c864fe) | Dec 13, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [c7e8137b9c](https://linux-hardware.org/?probe=c7e8137b9c) | Dec 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [659017d09e](https://linux-hardware.org/?probe=659017d09e) | Dec 06, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [48d351ced9](https://linux-hardware.org/?probe=48d351ced9) | Dec 01, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [d290ab5d70](https://linux-hardware.org/?probe=d290ab5d70) | Dec 01, 2024 |
| HP            | EliteBook 850 G5            | Notebook    | [39d29e9e31](https://linux-hardware.org/?probe=39d29e9e31) | Nov 30, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | Notebook    | [453f972762](https://linux-hardware.org/?probe=453f972762) | Nov 26, 2024 |
| ECS           | H55H-I                      | Desktop     | [30ab02e0cf](https://linux-hardware.org/?probe=30ab02e0cf) | Nov 24, 2024 |
| ECS           | H55H-I                      | Desktop     | [e15c44d10c](https://linux-hardware.org/?probe=e15c44d10c) | Nov 24, 2024 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [e9bbed01d3](https://linux-hardware.org/?probe=e9bbed01d3) | Nov 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [9f933e3704](https://linux-hardware.org/?probe=9f933e3704) | Nov 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [412e0842bc](https://linux-hardware.org/?probe=412e0842bc) | Nov 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6cd8e82a85](https://linux-hardware.org/?probe=6cd8e82a85) | Nov 21, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [121531eee4](https://linux-hardware.org/?probe=121531eee4) | Nov 19, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [3f6a95ad11](https://linux-hardware.org/?probe=3f6a95ad11) | Nov 18, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [cb5b5c8c93](https://linux-hardware.org/?probe=cb5b5c8c93) | Nov 16, 2024 |
| Dell          | Latitude 7420               | Notebook    | [5c3fe4e30f](https://linux-hardware.org/?probe=5c3fe4e30f) | Nov 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [cc545ad6f0](https://linux-hardware.org/?probe=cc545ad6f0) | Nov 15, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [7965f306a8](https://linux-hardware.org/?probe=7965f306a8) | Nov 11, 2024 |
| Gigabyte      | H97-HD3                     | Desktop     | [c231e924ef](https://linux-hardware.org/?probe=c231e924ef) | Nov 11, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [40ba7bc623](https://linux-hardware.org/?probe=40ba7bc623) | Nov 10, 2024 |
| Acer          | E1-510                      | Notebook    | [0d4221de7e](https://linux-hardware.org/?probe=0d4221de7e) | Nov 09, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [a41e7684ba](https://linux-hardware.org/?probe=a41e7684ba) | Nov 09, 2024 |
| Dell          | 0WMJ54 A00                  | Desktop     | [7ad5566418](https://linux-hardware.org/?probe=7ad5566418) | Nov 08, 2024 |
| Toshiba       | Satellite L850              | Notebook    | [21b8f6ffc6](https://linux-hardware.org/?probe=21b8f6ffc6) | Nov 07, 2024 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [7646d56938](https://linux-hardware.org/?probe=7646d56938) | Nov 06, 2024 |
| ASRock        | B650 LiveMixer              | Desktop     | [312b0972f7](https://linux-hardware.org/?probe=312b0972f7) | Nov 06, 2024 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [2dcd2cd367](https://linux-hardware.org/?probe=2dcd2cd367) | Nov 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [04191e06b0](https://linux-hardware.org/?probe=04191e06b0) | Nov 04, 2024 |
| Toshiba       | Satellite L850              | Notebook    | [fc40c7d71c](https://linux-hardware.org/?probe=fc40c7d71c) | Nov 03, 2024 |
| Acer          | Veriton X6610G              | Desktop     | [3d2a3caadd](https://linux-hardware.org/?probe=3d2a3caadd) | Oct 31, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [71425bff17](https://linux-hardware.org/?probe=71425bff17) | Oct 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [721a42e36b](https://linux-hardware.org/?probe=721a42e36b) | Oct 28, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f57dd2c60b](https://linux-hardware.org/?probe=f57dd2c60b) | Oct 27, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e8ca6f09e7](https://linux-hardware.org/?probe=e8ca6f09e7) | Oct 26, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1668591553](https://linux-hardware.org/?probe=1668591553) | Oct 26, 2024 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [171bf9a6b1](https://linux-hardware.org/?probe=171bf9a6b1) | Oct 23, 2024 |
| Alienware     | m15 R7                      | Notebook    | [2a1872a750](https://linux-hardware.org/?probe=2a1872a750) | Oct 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a777da34f0](https://linux-hardware.org/?probe=a777da34f0) | Oct 18, 2024 |
| Samsung       | Galaxy Book 12              | Tablet      | [f27dfbbbfb](https://linux-hardware.org/?probe=f27dfbbbfb) | Oct 17, 2024 |
| AMD           | Brazos Platform             | Notebook    | [9dd03dc5dc](https://linux-hardware.org/?probe=9dd03dc5dc) | Oct 14, 2024 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [3dc2166f97](https://linux-hardware.org/?probe=3dc2166f97) | Oct 13, 2024 |
| Gigabyte      | H510M DS2V                  | Desktop     | [aa0a212212](https://linux-hardware.org/?probe=aa0a212212) | Oct 13, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | Desktop     | [cbe00ef6b2](https://linux-hardware.org/?probe=cbe00ef6b2) | Oct 13, 2024 |
| Dell          | Studio 1747                 | Notebook    | [1159e24f15](https://linux-hardware.org/?probe=1159e24f15) | Oct 12, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [20a7878d28](https://linux-hardware.org/?probe=20a7878d28) | Oct 12, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d284464df1](https://linux-hardware.org/?probe=d284464df1) | Oct 11, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4747b9f85b](https://linux-hardware.org/?probe=4747b9f85b) | Oct 10, 2024 |
| Gigabyte      | H510M S2H V2                | Desktop     | [23da41cb81](https://linux-hardware.org/?probe=23da41cb81) | Oct 09, 2024 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [63f829198f](https://linux-hardware.org/?probe=63f829198f) | Oct 08, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5ffe9c3801](https://linux-hardware.org/?probe=5ffe9c3801) | Oct 08, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5124f0d14b](https://linux-hardware.org/?probe=5124f0d14b) | Oct 08, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [92563424c0](https://linux-hardware.org/?probe=92563424c0) | Oct 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [daf78aa588](https://linux-hardware.org/?probe=daf78aa588) | Oct 06, 2024 |
| Fujitsu       | LIFEBOOK U729               | Notebook    | [15f399627a](https://linux-hardware.org/?probe=15f399627a) | Oct 06, 2024 |
| Acer          | Swift SF314-41              | Notebook    | [5049b3c066](https://linux-hardware.org/?probe=5049b3c066) | Oct 06, 2024 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [d1f81806d0](https://linux-hardware.org/?probe=d1f81806d0) | Oct 06, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [3763589c8a](https://linux-hardware.org/?probe=3763589c8a) | Oct 04, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [e844095b68](https://linux-hardware.org/?probe=e844095b68) | Oct 04, 2024 |
| Gigabyte      | A620M H                     | Desktop     | [b144a036c9](https://linux-hardware.org/?probe=b144a036c9) | Oct 03, 2024 |
| Supermicro    | X10SL7-F                    | Server      | [ea13c0439b](https://linux-hardware.org/?probe=ea13c0439b) | Oct 02, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [86809fd683](https://linux-hardware.org/?probe=86809fd683) | Oct 01, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [0b4d1355de](https://linux-hardware.org/?probe=0b4d1355de) | Sep 29, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [a0c44a617b](https://linux-hardware.org/?probe=a0c44a617b) | Sep 28, 2024 |
| Acer          | Aspire A315-51              | Notebook    | [603e00f852](https://linux-hardware.org/?probe=603e00f852) | Sep 28, 2024 |
| Dell          | Inspiron 5565               | Notebook    | [665b2cc68c](https://linux-hardware.org/?probe=665b2cc68c) | Sep 25, 2024 |
| Dell          | Inspiron 5565               | Notebook    | [3763aeacb5](https://linux-hardware.org/?probe=3763aeacb5) | Sep 25, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [3750216f3e](https://linux-hardware.org/?probe=3750216f3e) | Sep 25, 2024 |
| Dell          | 051FJ8 A00                  | Desktop     | [60e4b8e20b](https://linux-hardware.org/?probe=60e4b8e20b) | Sep 25, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [bbeaba4670](https://linux-hardware.org/?probe=bbeaba4670) | Sep 24, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [b3dbaa175d](https://linux-hardware.org/?probe=b3dbaa175d) | Sep 21, 2024 |
| HP            | 83F2                        | Desktop     | [e77b1d8784](https://linux-hardware.org/?probe=e77b1d8784) | Sep 20, 2024 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c5a9c6334d](https://linux-hardware.org/?probe=c5a9c6334d) | Sep 20, 2024 |
| HP            | Pavilion dv6500             | Notebook    | [f9af2fb181](https://linux-hardware.org/?probe=f9af2fb181) | Sep 19, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [9e0c589148](https://linux-hardware.org/?probe=9e0c589148) | Sep 18, 2024 |
| Fujitsu       | LIFEBOOK U729               | Notebook    | [94bef52ce4](https://linux-hardware.org/?probe=94bef52ce4) | Sep 15, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [fc5fb22b68](https://linux-hardware.org/?probe=fc5fb22b68) | Sep 15, 2024 |
| Dell          | 0X2MKR A00                  | All in one  | [48fc1b98f3](https://linux-hardware.org/?probe=48fc1b98f3) | Sep 12, 2024 |
| Toshiba       | Satellite S40-B             | Notebook    | [5568883cd6](https://linux-hardware.org/?probe=5568883cd6) | Sep 10, 2024 |
| HP            | Boma                        | Desktop     | [933386dfca](https://linux-hardware.org/?probe=933386dfca) | Sep 10, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [f41e3827ec](https://linux-hardware.org/?probe=f41e3827ec) | Sep 06, 2024 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [64739c4c52](https://linux-hardware.org/?probe=64739c4c52) | Sep 03, 2024 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [2f6b2386f3](https://linux-hardware.org/?probe=2f6b2386f3) | Sep 03, 2024 |
| Lenovo        | ThinkPad X131e 33681Q1      | Notebook    | [f3e3569ea0](https://linux-hardware.org/?probe=f3e3569ea0) | Sep 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [27d62581b6](https://linux-hardware.org/?probe=27d62581b6) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [264b39ca1e](https://linux-hardware.org/?probe=264b39ca1e) | Sep 02, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [a25c9ccdaf](https://linux-hardware.org/?probe=a25c9ccdaf) | Sep 02, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [f251a3d3a0](https://linux-hardware.org/?probe=f251a3d3a0) | Sep 02, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c3cf874ba0](https://linux-hardware.org/?probe=c3cf874ba0) | Sep 02, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [0a47a5ee51](https://linux-hardware.org/?probe=0a47a5ee51) | Aug 31, 2024 |
| GPD           | G1617-01                    | Notebook    | [a594a51f8f](https://linux-hardware.org/?probe=a594a51f8f) | Aug 31, 2024 |
| Acer          | TravelMate P414-52          | Notebook    | [53e032dfc4](https://linux-hardware.org/?probe=53e032dfc4) | Aug 30, 2024 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [0aad5ee06f](https://linux-hardware.org/?probe=0aad5ee06f) | Aug 29, 2024 |
| Lenovo        | ThinkPad P53 20QQS3831V     | Notebook    | [7011c28a17](https://linux-hardware.org/?probe=7011c28a17) | Aug 28, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [1ef6676af1](https://linux-hardware.org/?probe=1ef6676af1) | Aug 27, 2024 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [f769341be7](https://linux-hardware.org/?probe=f769341be7) | Aug 26, 2024 |
| Acer          | TravelMate P414-52          | Notebook    | [f1a981cb7c](https://linux-hardware.org/?probe=f1a981cb7c) | Aug 25, 2024 |
| MSI           | B550M PRO-VDH               | Desktop     | [77b92070ec](https://linux-hardware.org/?probe=77b92070ec) | Aug 24, 2024 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [52d8c6427c](https://linux-hardware.org/?probe=52d8c6427c) | Aug 24, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [4e9962f90c](https://linux-hardware.org/?probe=4e9962f90c) | Aug 22, 2024 |
| Dell          | 0PU052                      | Desktop     | [95f1504d6a](https://linux-hardware.org/?probe=95f1504d6a) | Aug 22, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [19d17bf64f](https://linux-hardware.org/?probe=19d17bf64f) | Aug 21, 2024 |
| HP            | ENVY 15                     | Notebook    | [49f2ac2a2f](https://linux-hardware.org/?probe=49f2ac2a2f) | Aug 21, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [e78c7f9776](https://linux-hardware.org/?probe=e78c7f9776) | Aug 21, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [5c9e84e6b3](https://linux-hardware.org/?probe=5c9e84e6b3) | Aug 19, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [412b73e5d1](https://linux-hardware.org/?probe=412b73e5d1) | Aug 19, 2024 |
| Fujitsu       | LIFEBOOK U729               | Notebook    | [84c5ee6ec3](https://linux-hardware.org/?probe=84c5ee6ec3) | Aug 18, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [abcd3ebd0f](https://linux-hardware.org/?probe=abcd3ebd0f) | Aug 18, 2024 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [027e15deb2](https://linux-hardware.org/?probe=027e15deb2) | Aug 18, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [db12103f69](https://linux-hardware.org/?probe=db12103f69) | Aug 18, 2024 |
| Gigabyte      | H81M-HD3                    | Desktop     | [f85c6f494e](https://linux-hardware.org/?probe=f85c6f494e) | Aug 17, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0314b6aefb](https://linux-hardware.org/?probe=0314b6aefb) | Aug 16, 2024 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [1d014a5085](https://linux-hardware.org/?probe=1d014a5085) | Aug 15, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [5ae88f75d1](https://linux-hardware.org/?probe=5ae88f75d1) | Aug 15, 2024 |
| ASUSTek       | P5GC-MX/GBL                 | Desktop     | [ce7187e567](https://linux-hardware.org/?probe=ce7187e567) | Aug 15, 2024 |
| HP            | ProBook 4740s               | Notebook    | [d515f60fdf](https://linux-hardware.org/?probe=d515f60fdf) | Aug 14, 2024 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [c6e46b55fe](https://linux-hardware.org/?probe=c6e46b55fe) | Aug 14, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [48e265111e](https://linux-hardware.org/?probe=48e265111e) | Aug 13, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [948de2035b](https://linux-hardware.org/?probe=948de2035b) | Aug 13, 2024 |
| Gigabyte      | H81M-HD3                    | Desktop     | [10ecc6c6c4](https://linux-hardware.org/?probe=10ecc6c6c4) | Aug 12, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7d1d61fa3f](https://linux-hardware.org/?probe=7d1d61fa3f) | Aug 12, 2024 |
| Acer          | Aspire A314-31              | Notebook    | [baab264ab4](https://linux-hardware.org/?probe=baab264ab4) | Aug 12, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [e9bf3f35c2](https://linux-hardware.org/?probe=e9bf3f35c2) | Aug 12, 2024 |
| Dell          | Inspiron 5565               | Notebook    | [f3a59f4478](https://linux-hardware.org/?probe=f3a59f4478) | Aug 11, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [a6f4b3ba0b](https://linux-hardware.org/?probe=a6f4b3ba0b) | Aug 10, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [52ca97fd84](https://linux-hardware.org/?probe=52ca97fd84) | Aug 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [0d1b4d0ac4](https://linux-hardware.org/?probe=0d1b4d0ac4) | Aug 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [8561a6bc16](https://linux-hardware.org/?probe=8561a6bc16) | Aug 09, 2024 |
| Gigabyte      | H81M-HD3                    | Desktop     | [4d52a37c95](https://linux-hardware.org/?probe=4d52a37c95) | Aug 08, 2024 |
| Toshiba       | Satellite L850              | Notebook    | [80bf318b30](https://linux-hardware.org/?probe=80bf318b30) | Aug 08, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [4477497a2d](https://linux-hardware.org/?probe=4477497a2d) | Aug 07, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [a9786d615f](https://linux-hardware.org/?probe=a9786d615f) | Aug 07, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [7d1f67623f](https://linux-hardware.org/?probe=7d1f67623f) | Aug 04, 2024 |
| HP            | 83F3                        | Desktop     | [8b1a108704](https://linux-hardware.org/?probe=8b1a108704) | Aug 03, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [c0e5b2a4dc](https://linux-hardware.org/?probe=c0e5b2a4dc) | Aug 03, 2024 |
| Lenovo        | ThinkPad Edge 0302CTO       | Notebook    | [3e723d09c8](https://linux-hardware.org/?probe=3e723d09c8) | Aug 02, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [c9e614ecd6](https://linux-hardware.org/?probe=c9e614ecd6) | Aug 01, 2024 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [8dbc443fe5](https://linux-hardware.org/?probe=8dbc443fe5) | Jul 31, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0b5449d2f](https://linux-hardware.org/?probe=c0b5449d2f) | Jul 30, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [4e23524711](https://linux-hardware.org/?probe=4e23524711) | Jul 29, 2024 |
| Micro Comp... | V3                          | Tablet      | [307637007f](https://linux-hardware.org/?probe=307637007f) | Jul 26, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [28bdd7232a](https://linux-hardware.org/?probe=28bdd7232a) | Jul 25, 2024 |
| Pegatron      | 2AB5                        | Desktop     | [c94576fefd](https://linux-hardware.org/?probe=c94576fefd) | Jul 24, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [46748aee2e](https://linux-hardware.org/?probe=46748aee2e) | Jul 23, 2024 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [95c63d73b5](https://linux-hardware.org/?probe=95c63d73b5) | Jul 22, 2024 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [e09f0b94e8](https://linux-hardware.org/?probe=e09f0b94e8) | Jul 21, 2024 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [85d4956501](https://linux-hardware.org/?probe=85d4956501) | Jul 21, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [cb2c5a3de3](https://linux-hardware.org/?probe=cb2c5a3de3) | Jul 20, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [9a81359405](https://linux-hardware.org/?probe=9a81359405) | Jul 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b1df4c5f37](https://linux-hardware.org/?probe=b1df4c5f37) | Jul 19, 2024 |
| HP            | 83F2                        | Desktop     | [d30af24b31](https://linux-hardware.org/?probe=d30af24b31) | Jul 18, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [5a90fa26da](https://linux-hardware.org/?probe=5a90fa26da) | Jul 17, 2024 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [83f7dc4e07](https://linux-hardware.org/?probe=83f7dc4e07) | Jul 15, 2024 |
| Samsung       | 300E5E/300E4E/300E5V/300... | Notebook    | [ca43efc3a4](https://linux-hardware.org/?probe=ca43efc3a4) | Jul 14, 2024 |
| HP            | ProLiant DL360p Gen8        | Server      | [974e5055c1](https://linux-hardware.org/?probe=974e5055c1) | Jul 14, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [7ecc2be56e](https://linux-hardware.org/?probe=7ecc2be56e) | Jul 12, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [c2f3d5573c](https://linux-hardware.org/?probe=c2f3d5573c) | Jul 11, 2024 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [e3507bd66f](https://linux-hardware.org/?probe=e3507bd66f) | Jul 08, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [bd15491297](https://linux-hardware.org/?probe=bd15491297) | Jul 07, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [155337b9a0](https://linux-hardware.org/?probe=155337b9a0) | Jul 07, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [475903534b](https://linux-hardware.org/?probe=475903534b) | Jul 07, 2024 |
| Acer          | Aspire Z3-605               | All in one  | [d434ee71a5](https://linux-hardware.org/?probe=d434ee71a5) | Jul 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [9fb2474a87](https://linux-hardware.org/?probe=9fb2474a87) | Jul 06, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5a22e3b0f6](https://linux-hardware.org/?probe=5a22e3b0f6) | Jul 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3f94cf54c9](https://linux-hardware.org/?probe=3f94cf54c9) | Jul 03, 2024 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [a4b671dbdc](https://linux-hardware.org/?probe=a4b671dbdc) | Jun 30, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [6c7bcd021d](https://linux-hardware.org/?probe=6c7bcd021d) | Jun 29, 2024 |
| Acer          | Predator PT315-52           | Notebook    | [abaf6fae75](https://linux-hardware.org/?probe=abaf6fae75) | Jun 28, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [de32ab8e14](https://linux-hardware.org/?probe=de32ab8e14) | Jun 28, 2024 |
| HP            | EliteBook 2740p             | Notebook    | [a477c0789c](https://linux-hardware.org/?probe=a477c0789c) | Jun 27, 2024 |
| ASRock        | N100DC-ITX                  | Desktop     | [b1f1c48f11](https://linux-hardware.org/?probe=b1f1c48f11) | Jun 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e028ca3815](https://linux-hardware.org/?probe=e028ca3815) | Jun 27, 2024 |
| Pegatron      | 2AB6                        | Desktop     | [af3bbc9d2e](https://linux-hardware.org/?probe=af3bbc9d2e) | Jun 26, 2024 |
| Panasonic     | CF53-4                      | Notebook    | [b1bd272cb9](https://linux-hardware.org/?probe=b1bd272cb9) | Jun 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [11bcad49f7](https://linux-hardware.org/?probe=11bcad49f7) | Jun 22, 2024 |
| Dell          | 0NC2VH A01                  | Desktop     | [973408b607](https://linux-hardware.org/?probe=973408b607) | Jun 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [918b7fe620](https://linux-hardware.org/?probe=918b7fe620) | Jun 19, 2024 |
| Gigabyte      | B760M H DDR4                | Desktop     | [8d6956f9a6](https://linux-hardware.org/?probe=8d6956f9a6) | Jun 17, 2024 |
| Gigabyte      | B760M H DDR4                | Desktop     | [3e87b834d6](https://linux-hardware.org/?probe=3e87b834d6) | Jun 17, 2024 |
| Gigabyte      | B550 AORUS PRO AX           | Desktop     | [626f9ea78b](https://linux-hardware.org/?probe=626f9ea78b) | Jun 12, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [4ad840ce96](https://linux-hardware.org/?probe=4ad840ce96) | Jun 11, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [f5c79b2b42](https://linux-hardware.org/?probe=f5c79b2b42) | Jun 10, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [7e1173c163](https://linux-hardware.org/?probe=7e1173c163) | Jun 06, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [dc0057e34a](https://linux-hardware.org/?probe=dc0057e34a) | Jun 04, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [1a21e7c4d0](https://linux-hardware.org/?probe=1a21e7c4d0) | May 30, 2024 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [bad70d9b7d](https://linux-hardware.org/?probe=bad70d9b7d) | May 30, 2024 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [f886465cab](https://linux-hardware.org/?probe=f886465cab) | May 29, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [fae7db37eb](https://linux-hardware.org/?probe=fae7db37eb) | May 29, 2024 |
| Valve         | Galileo                     | Notebook    | [66613e5eb2](https://linux-hardware.org/?probe=66613e5eb2) | May 27, 2024 |
| HP            | EliteBook x360 1020 G2      | Convertible | [908c41d6a3](https://linux-hardware.org/?probe=908c41d6a3) | May 26, 2024 |
| Lenovo        | G580 20157                  | Notebook    | [618ba27996](https://linux-hardware.org/?probe=618ba27996) | May 26, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [9e6346f767](https://linux-hardware.org/?probe=9e6346f767) | May 26, 2024 |
| Lenovo        | ThinkPad E15 20RDS0RD00     | Notebook    | [ff1961961a](https://linux-hardware.org/?probe=ff1961961a) | May 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [f3cac40a5a](https://linux-hardware.org/?probe=f3cac40a5a) | May 25, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [8a20646e0c](https://linux-hardware.org/?probe=8a20646e0c) | May 24, 2024 |
| HP            | ProBook 430 G7              | Notebook    | [8cce8b33d0](https://linux-hardware.org/?probe=8cce8b33d0) | May 24, 2024 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [b762f1c709](https://linux-hardware.org/?probe=b762f1c709) | May 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8c61738c77](https://linux-hardware.org/?probe=8c61738c77) | May 20, 2024 |
| Acer          | Aspire A114-33              | Notebook    | [a72ff8e182](https://linux-hardware.org/?probe=a72ff8e182) | May 19, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [b68d9ac21d](https://linux-hardware.org/?probe=b68d9ac21d) | May 18, 2024 |
| Pegatron      | 2AC3                        | Desktop     | [90916e3259](https://linux-hardware.org/?probe=90916e3259) | May 18, 2024 |
| HP            | EliteBook 850 G5            | Notebook    | [cabfe742c9](https://linux-hardware.org/?probe=cabfe742c9) | May 15, 2024 |
| Dell          | 03015M A03                  | Server      | [c6fe3be3cd](https://linux-hardware.org/?probe=c6fe3be3cd) | May 12, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [aa1981e8c1](https://linux-hardware.org/?probe=aa1981e8c1) | May 12, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [182ebd66c7](https://linux-hardware.org/?probe=182ebd66c7) | May 12, 2024 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [7691c4fa1d](https://linux-hardware.org/?probe=7691c4fa1d) | May 10, 2024 |
| Dell          | System XPS L702X            | Notebook    | [fec4b7f7ff](https://linux-hardware.org/?probe=fec4b7f7ff) | May 06, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [41e3014295](https://linux-hardware.org/?probe=41e3014295) | May 04, 2024 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [7411eab31d](https://linux-hardware.org/?probe=7411eab31d) | May 04, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [b44b5a5556](https://linux-hardware.org/?probe=b44b5a5556) | May 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [cee4dd63f5](https://linux-hardware.org/?probe=cee4dd63f5) | Apr 30, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [4d9e58a6de](https://linux-hardware.org/?probe=4d9e58a6de) | Apr 30, 2024 |
| Dell          | 0F3KHR A01                  | Desktop     | [fdcd93e140](https://linux-hardware.org/?probe=fdcd93e140) | Apr 28, 2024 |
| Lenovo        | ThinkPad T510 4349RW1       | Notebook    | [afaac362f7](https://linux-hardware.org/?probe=afaac362f7) | Apr 28, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [055d3d55a1](https://linux-hardware.org/?probe=055d3d55a1) | Apr 28, 2024 |
| Dell          | 0F3KHR A01                  | Desktop     | [d83354002b](https://linux-hardware.org/?probe=d83354002b) | Apr 27, 2024 |
| Acer          | Nitro AN715-51              | Notebook    | [0056e3f773](https://linux-hardware.org/?probe=0056e3f773) | Apr 27, 2024 |
| Lenovo        | ThinkPad T460s 20FAS21A0... | Notebook    | [f8c5a44d3d](https://linux-hardware.org/?probe=f8c5a44d3d) | Apr 27, 2024 |
| HP            | EliteBook 850 G5            | Notebook    | [366a6a7aaf](https://linux-hardware.org/?probe=366a6a7aaf) | Apr 26, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [b6aa6b2262](https://linux-hardware.org/?probe=b6aa6b2262) | Apr 22, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e403e1c979](https://linux-hardware.org/?probe=e403e1c979) | Apr 19, 2024 |
| HP            | Pavilion x2 Detachable      | Notebook    | [9e5556a266](https://linux-hardware.org/?probe=9e5556a266) | Apr 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [639a73dd7e](https://linux-hardware.org/?probe=639a73dd7e) | Apr 14, 2024 |
| HP            | 2B42 100                    | All in one  | [c565b251cb](https://linux-hardware.org/?probe=c565b251cb) | Apr 14, 2024 |
| HP            | EliteBook 8740w             | Notebook    | [39d5987bd0](https://linux-hardware.org/?probe=39d5987bd0) | Apr 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [552cd13a50](https://linux-hardware.org/?probe=552cd13a50) | Apr 12, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c12fc6f65e](https://linux-hardware.org/?probe=c12fc6f65e) | Apr 10, 2024 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [e236ba52be](https://linux-hardware.org/?probe=e236ba52be) | Apr 10, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a50be3e60f](https://linux-hardware.org/?probe=a50be3e60f) | Apr 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [43618657fd](https://linux-hardware.org/?probe=43618657fd) | Apr 09, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [33dd11bc5b](https://linux-hardware.org/?probe=33dd11bc5b) | Apr 07, 2024 |
| Dell          | Latitude 5330               | Notebook    | [3327ec32e4](https://linux-hardware.org/?probe=3327ec32e4) | Apr 06, 2024 |
| Acer          | Nitro AN715-51              | Notebook    | [8f37d9426f](https://linux-hardware.org/?probe=8f37d9426f) | Apr 05, 2024 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [5158b23532](https://linux-hardware.org/?probe=5158b23532) | Apr 04, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [9f0fc743f7](https://linux-hardware.org/?probe=9f0fc743f7) | Apr 03, 2024 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [26bfbd7911](https://linux-hardware.org/?probe=26bfbd7911) | Apr 03, 2024 |
| Apple         | Mac-F2208EC8                | Mini pc     | [2120742c95](https://linux-hardware.org/?probe=2120742c95) | Mar 27, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Notebook    | [1120862001](https://linux-hardware.org/?probe=1120862001) | Mar 24, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [deb5d7b1ca](https://linux-hardware.org/?probe=deb5d7b1ca) | Mar 23, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [d6dfd879ee](https://linux-hardware.org/?probe=d6dfd879ee) | Mar 20, 2024 |
| Apple         | MacBookAir3,2               | Notebook    | [1e9279f941](https://linux-hardware.org/?probe=1e9279f941) | Mar 18, 2024 |
| HP            | 2B38                        | Desktop     | [b0457c0f4a](https://linux-hardware.org/?probe=b0457c0f4a) | Mar 17, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [3c068136de](https://linux-hardware.org/?probe=3c068136de) | Mar 17, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [3828683188](https://linux-hardware.org/?probe=3828683188) | Mar 17, 2024 |
| Lenovo        | ThinkPad T470 20HES23B0U    | Notebook    | [6b7342964b](https://linux-hardware.org/?probe=6b7342964b) | Mar 16, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c8aa89bb80](https://linux-hardware.org/?probe=c8aa89bb80) | Mar 13, 2024 |
| Lenovo        | Yoga 9 2-in-1 14IMH9 83A... | Convertible | [c219da3b38](https://linux-hardware.org/?probe=c219da3b38) | Mar 13, 2024 |
| Intel         | X99H V1.x                   | Desktop     | [9da589fefc](https://linux-hardware.org/?probe=9da589fefc) | Mar 11, 2024 |
| MSI           | Alpha 15 A3DD               | Notebook    | [4410e98550](https://linux-hardware.org/?probe=4410e98550) | Mar 11, 2024 |
| Dell          | Latitude 7490               | Notebook    | [93e3272d83](https://linux-hardware.org/?probe=93e3272d83) | Mar 10, 2024 |
| Dell          | Latitude 7490               | Notebook    | [d8c5dd5832](https://linux-hardware.org/?probe=d8c5dd5832) | Mar 09, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [203f82333d](https://linux-hardware.org/?probe=203f82333d) | Mar 07, 2024 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [cd72ba8c02](https://linux-hardware.org/?probe=cd72ba8c02) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [e4944abc1f](https://linux-hardware.org/?probe=e4944abc1f) | Mar 03, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [d7d8cc5cc7](https://linux-hardware.org/?probe=d7d8cc5cc7) | Mar 02, 2024 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [9953ba3b51](https://linux-hardware.org/?probe=9953ba3b51) | Mar 01, 2024 |
| Gigabyte      | H310M S2H                   | Desktop     | [482a7100d8](https://linux-hardware.org/?probe=482a7100d8) | Feb 27, 2024 |
| HP            | Spectre Notebook            | Notebook    | [3530672860](https://linux-hardware.org/?probe=3530672860) | Feb 26, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [b166351cca](https://linux-hardware.org/?probe=b166351cca) | Feb 24, 2024 |
| HP            | Elite x2 1012 G2            | Tablet      | [e89027d9d7](https://linux-hardware.org/?probe=e89027d9d7) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [63b1269b5c](https://linux-hardware.org/?probe=63b1269b5c) | Feb 19, 2024 |
| Gigabyte      | B560 HD3                    | Desktop     | [471e56fa2c](https://linux-hardware.org/?probe=471e56fa2c) | Feb 16, 2024 |
| HP            | 18E5                        | Desktop     | [3e90471e97](https://linux-hardware.org/?probe=3e90471e97) | Feb 09, 2024 |
| HP            | 18E5                        | Desktop     | [9ae685a4cb](https://linux-hardware.org/?probe=9ae685a4cb) | Feb 09, 2024 |
| Gigabyte      | H310M S2H                   | Desktop     | [87512d7e7e](https://linux-hardware.org/?probe=87512d7e7e) | Feb 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2b98b922fe](https://linux-hardware.org/?probe=2b98b922fe) | Feb 03, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [9ed6c67efe](https://linux-hardware.org/?probe=9ed6c67efe) | Feb 02, 2024 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [32200add92](https://linux-hardware.org/?probe=32200add92) | Jan 31, 2024 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [38cafaade5](https://linux-hardware.org/?probe=38cafaade5) | Jan 31, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [646a977cdd](https://linux-hardware.org/?probe=646a977cdd) | Jan 30, 2024 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [40e2ad53e8](https://linux-hardware.org/?probe=40e2ad53e8) | Jan 29, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [99e90d2b89](https://linux-hardware.org/?probe=99e90d2b89) | Jan 29, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [1b5bfa9bcb](https://linux-hardware.org/?probe=1b5bfa9bcb) | Jan 28, 2024 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [185a90aec7](https://linux-hardware.org/?probe=185a90aec7) | Jan 28, 2024 |
| ASUSTek       | P8B75-M                     | Desktop     | [ad1a5f6757](https://linux-hardware.org/?probe=ad1a5f6757) | Jan 28, 2024 |
| HP            | 2AAC                        | Desktop     | [d397b1b3b3](https://linux-hardware.org/?probe=d397b1b3b3) | Jan 26, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [abc0872688](https://linux-hardware.org/?probe=abc0872688) | Jan 24, 2024 |
| Intel         | Unknown                     | Desktop     | [e4094a3abf](https://linux-hardware.org/?probe=e4094a3abf) | Jan 23, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [4f202be1d5](https://linux-hardware.org/?probe=4f202be1d5) | Jan 20, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a1e7338a13](https://linux-hardware.org/?probe=a1e7338a13) | Jan 19, 2024 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [6565fd5500](https://linux-hardware.org/?probe=6565fd5500) | Jan 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [122b72e9f2](https://linux-hardware.org/?probe=122b72e9f2) | Jan 15, 2024 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0ab95fc3f5](https://linux-hardware.org/?probe=0ab95fc3f5) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3d7fcea179](https://linux-hardware.org/?probe=3d7fcea179) | Jan 11, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [4a1bc29322](https://linux-hardware.org/?probe=4a1bc29322) | Jan 06, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [7b663d0c10](https://linux-hardware.org/?probe=7b663d0c10) | Jan 05, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [d80a5355a3](https://linux-hardware.org/?probe=d80a5355a3) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b1484cba42](https://linux-hardware.org/?probe=b1484cba42) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cb3946a0b0](https://linux-hardware.org/?probe=cb3946a0b0) | Jan 04, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [db656f3905](https://linux-hardware.org/?probe=db656f3905) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [251b877f2f](https://linux-hardware.org/?probe=251b877f2f) | Jan 03, 2024 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [24166c136e](https://linux-hardware.org/?probe=24166c136e) | Jan 02, 2024 |
| Dell          | 0D28YY A01                  | Desktop     | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [942c025f11](https://linux-hardware.org/?probe=942c025f11) | Dec 31, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [a9dd36da25](https://linux-hardware.org/?probe=a9dd36da25) | Dec 29, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [690962312c](https://linux-hardware.org/?probe=690962312c) | Dec 29, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | Notebook    | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [8f2f7cd8c9](https://linux-hardware.org/?probe=8f2f7cd8c9) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [19e33f2ead](https://linux-hardware.org/?probe=19e33f2ead) | Dec 23, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [476915f215](https://linux-hardware.org/?probe=476915f215) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [ae7d12ef06](https://linux-hardware.org/?probe=ae7d12ef06) | Dec 17, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ee8ea2b093](https://linux-hardware.org/?probe=ee8ea2b093) | Dec 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [f91ead8a19](https://linux-hardware.org/?probe=f91ead8a19) | Dec 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [cedb8ab2b7](https://linux-hardware.org/?probe=cedb8ab2b7) | Dec 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6d5beb948](https://linux-hardware.org/?probe=e6d5beb948) | Dec 01, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8b68261a59](https://linux-hardware.org/?probe=8b68261a59) | Nov 30, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [8a91691d0b](https://linux-hardware.org/?probe=8a91691d0b) | Nov 30, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [a680e370dc](https://linux-hardware.org/?probe=a680e370dc) | Nov 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [71c73a255e](https://linux-hardware.org/?probe=71c73a255e) | Nov 29, 2023 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [c3d0a3a34c](https://linux-hardware.org/?probe=c3d0a3a34c) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [1192e07984](https://linux-hardware.org/?probe=1192e07984) | Nov 24, 2023 |
| HP            | 85A2                        | All in one  | [80b79f2bed](https://linux-hardware.org/?probe=80b79f2bed) | Nov 24, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a4f7b1d9d3](https://linux-hardware.org/?probe=a4f7b1d9d3) | Nov 20, 2023 |
| Acer          | Aspire X3400                | Desktop     | [26cedbdbde](https://linux-hardware.org/?probe=26cedbdbde) | Nov 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a7d065988a](https://linux-hardware.org/?probe=a7d065988a) | Nov 19, 2023 |
| Acer          | Aspire X3400                | Desktop     | [83890ec21c](https://linux-hardware.org/?probe=83890ec21c) | Nov 19, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [a9d9ea53da](https://linux-hardware.org/?probe=a9d9ea53da) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [ad44d7ebae](https://linux-hardware.org/?probe=ad44d7ebae) | Nov 15, 2023 |
| Google        | Magolor                     | Notebook    | [375ff87615](https://linux-hardware.org/?probe=375ff87615) | Nov 14, 2023 |
| Google        | Magolor                     | Notebook    | [f287edf382](https://linux-hardware.org/?probe=f287edf382) | Nov 14, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [a88696f0e2](https://linux-hardware.org/?probe=a88696f0e2) | Nov 13, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [0483e390e3](https://linux-hardware.org/?probe=0483e390e3) | Nov 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [14ae5dbe92](https://linux-hardware.org/?probe=14ae5dbe92) | Nov 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [bc514556b3](https://linux-hardware.org/?probe=bc514556b3) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [e00099e8c5](https://linux-hardware.org/?probe=e00099e8c5) | Nov 08, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [c88dde8f18](https://linux-hardware.org/?probe=c88dde8f18) | Nov 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1801a9c841](https://linux-hardware.org/?probe=1801a9c841) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [52a36f5268](https://linux-hardware.org/?probe=52a36f5268) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | Desktop     | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| HP            | 829A                        | Mini pc     | [d0735e46db](https://linux-hardware.org/?probe=d0735e46db) | Nov 01, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| HP            | 1998                        | Desktop     | [4701148920](https://linux-hardware.org/?probe=4701148920) | Oct 26, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [d1c293b080](https://linux-hardware.org/?probe=d1c293b080) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| HP            | 2B3B                        | All in one  | [b2dac4adaa](https://linux-hardware.org/?probe=b2dac4adaa) | Oct 25, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [2ad6656255](https://linux-hardware.org/?probe=2ad6656255) | Oct 21, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [4aaa66c7bc](https://linux-hardware.org/?probe=4aaa66c7bc) | Oct 20, 2023 |
| HP            | 85A2                        | All in one  | [67234a41ca](https://linux-hardware.org/?probe=67234a41ca) | Oct 18, 2023 |
| HP            | 14                          | Notebook    | [3d65da2b45](https://linux-hardware.org/?probe=3d65da2b45) | Oct 08, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [67df4157ef](https://linux-hardware.org/?probe=67df4157ef) | Oct 06, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [058c6a0ee6](https://linux-hardware.org/?probe=058c6a0ee6) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [bdfa072267](https://linux-hardware.org/?probe=bdfa072267) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d3e6e2aa83](https://linux-hardware.org/?probe=d3e6e2aa83) | Oct 03, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [34d3a3bd47](https://linux-hardware.org/?probe=34d3a3bd47) | Oct 03, 2023 |
| Supermicro    | H8DM8-2                     | Desktop     | [5386350e20](https://linux-hardware.org/?probe=5386350e20) | Oct 03, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [4c34ba59ba](https://linux-hardware.org/?probe=4c34ba59ba) | Oct 02, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e87fdc15ed](https://linux-hardware.org/?probe=e87fdc15ed) | Sep 29, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [b1333a2976](https://linux-hardware.org/?probe=b1333a2976) | Sep 29, 2023 |
| Gigabyte      | P35V3                       | Notebook    | [573f9ea2f5](https://linux-hardware.org/?probe=573f9ea2f5) | Sep 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [c4387fc499](https://linux-hardware.org/?probe=c4387fc499) | Sep 24, 2023 |
| HP            | 8714                        | Desktop     | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| HP            | 1998                        | Desktop     | [27c06c8617](https://linux-hardware.org/?probe=27c06c8617) | Sep 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [e098daf3a4](https://linux-hardware.org/?probe=e098daf3a4) | Sep 20, 2023 |
| Lenovo        | 3190 SDK0T76530 WIN 3556... | Mini pc     | [2179b0b458](https://linux-hardware.org/?probe=2179b0b458) | Sep 19, 2023 |
| HP            | 1998                        | Desktop     | [d65f099f06](https://linux-hardware.org/?probe=d65f099f06) | Sep 19, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [def911de73](https://linux-hardware.org/?probe=def911de73) | Sep 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [22a0210f8f](https://linux-hardware.org/?probe=22a0210f8f) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [4c56913d07](https://linux-hardware.org/?probe=4c56913d07) | Sep 13, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [a6d8eedc84](https://linux-hardware.org/?probe=a6d8eedc84) | Sep 11, 2023 |
| HP            | Notebook                    | Notebook    | [5a36d2a3bf](https://linux-hardware.org/?probe=5a36d2a3bf) | Sep 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [a9db40cece](https://linux-hardware.org/?probe=a9db40cece) | Sep 08, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [fc63e4f764](https://linux-hardware.org/?probe=fc63e4f764) | Sep 08, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [04e5805a67](https://linux-hardware.org/?probe=04e5805a67) | Sep 06, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [bc3d42d633](https://linux-hardware.org/?probe=bc3d42d633) | Sep 06, 2023 |
| MSI           | X79A-GD65                   | Desktop     | [5efb1e3e55](https://linux-hardware.org/?probe=5efb1e3e55) | Sep 06, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [29e55d4d72](https://linux-hardware.org/?probe=29e55d4d72) | Sep 04, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [5dac4ae656](https://linux-hardware.org/?probe=5dac4ae656) | Sep 03, 2023 |
| Intel         | NUC7i3BNB J22859-310        | Mini pc     | [cd552285b0](https://linux-hardware.org/?probe=cd552285b0) | Sep 01, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| Acer          | Aspire X3400                | Desktop     | [62a78b2a16](https://linux-hardware.org/?probe=62a78b2a16) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | Notebook    | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [9d05ea660f](https://linux-hardware.org/?probe=9d05ea660f) | Aug 31, 2023 |
| Dell          | 0HD5W2 A00                  | Notebook    | [492d08445d](https://linux-hardware.org/?probe=492d08445d) | Aug 28, 2023 |
| Sony          | VPCEB43FG                   | Notebook    | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [1330f2ac2a](https://linux-hardware.org/?probe=1330f2ac2a) | Aug 24, 2023 |
| HP            | ProBook 4740s               | Notebook    | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fed21c9b13](https://linux-hardware.org/?probe=fed21c9b13) | Aug 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c58a917e49](https://linux-hardware.org/?probe=c58a917e49) | Aug 23, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [76c16d7ffe](https://linux-hardware.org/?probe=76c16d7ffe) | Aug 22, 2023 |
| HP            | 18E5                        | Desktop     | [c17629e422](https://linux-hardware.org/?probe=c17629e422) | Aug 22, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [0383dad714](https://linux-hardware.org/?probe=0383dad714) | Aug 18, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| Dell          | 0NKW6Y A00                  | Notebook    | [c48afaf5bd](https://linux-hardware.org/?probe=c48afaf5bd) | Aug 15, 2023 |
| Dell          | 0NKW6Y A00                  | Notebook    | [774306b244](https://linux-hardware.org/?probe=774306b244) | Aug 15, 2023 |
| Dell          | 0NKW6Y A00                  | Notebook    | [14deab8375](https://linux-hardware.org/?probe=14deab8375) | Aug 15, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9e03b48bf3](https://linux-hardware.org/?probe=9e03b48bf3) | Aug 15, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [df9fab1b5b](https://linux-hardware.org/?probe=df9fab1b5b) | Aug 13, 2023 |
| Alienware     | 15                          | Notebook    | [d6c9c4f931](https://linux-hardware.org/?probe=d6c9c4f931) | Aug 12, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [60de8d6d38](https://linux-hardware.org/?probe=60de8d6d38) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | Notebook    | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0638b1c2dd](https://linux-hardware.org/?probe=0638b1c2dd) | Aug 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [ff98e5f807](https://linux-hardware.org/?probe=ff98e5f807) | Aug 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1099f63384](https://linux-hardware.org/?probe=1099f63384) | Jul 30, 2023 |
| HP            | Beats 15                    | Notebook    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | Notebook    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| Acer          | E1-510                      | Notebook    | [2a83ad14c0](https://linux-hardware.org/?probe=2a83ad14c0) | Jul 27, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [823eca937c](https://linux-hardware.org/?probe=823eca937c) | Jul 24, 2023 |
| HP            | Notebook                    | Notebook    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [8d9ea8214d](https://linux-hardware.org/?probe=8d9ea8214d) | Jul 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [0e18492205](https://linux-hardware.org/?probe=0e18492205) | Jul 20, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [61c153902b](https://linux-hardware.org/?probe=61c153902b) | Jul 19, 2023 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [d2b1eef8ac](https://linux-hardware.org/?probe=d2b1eef8ac) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [2c05f1a964](https://linux-hardware.org/?probe=2c05f1a964) | Jul 16, 2023 |
| Unknown       | EMB-BT1                     | Desktop     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [b048c3ee50](https://linux-hardware.org/?probe=b048c3ee50) | Jul 15, 2023 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [f1a7e1dbb3](https://linux-hardware.org/?probe=f1a7e1dbb3) | Jul 15, 2023 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [773d5ee9aa](https://linux-hardware.org/?probe=773d5ee9aa) | Jul 13, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| Dell          | Inspiron 7591 2n1           | Convertible | [dd19d99ba1](https://linux-hardware.org/?probe=dd19d99ba1) | Jul 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [8086d33203](https://linux-hardware.org/?probe=8086d33203) | Jun 29, 2023 |
| Acer          | EG43M                       | Desktop     | [e6d28dd1e5](https://linux-hardware.org/?probe=e6d28dd1e5) | Jun 28, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [15e9b561e3](https://linux-hardware.org/?probe=15e9b561e3) | Jun 27, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [34cf8e17a2](https://linux-hardware.org/?probe=34cf8e17a2) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [ef8876640e](https://linux-hardware.org/?probe=ef8876640e) | Jun 22, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [ea1fabfdc3](https://linux-hardware.org/?probe=ea1fabfdc3) | Jun 17, 2023 |
| Toshiba       | Satellite C50D-C            | Notebook    | [207d5f5dbd](https://linux-hardware.org/?probe=207d5f5dbd) | Jun 17, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1b97aa6745](https://linux-hardware.org/?probe=1b97aa6745) | Jun 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6fcdcaa48c](https://linux-hardware.org/?probe=6fcdcaa48c) | Jun 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [744c44deca](https://linux-hardware.org/?probe=744c44deca) | Jun 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [5b35735d26](https://linux-hardware.org/?probe=5b35735d26) | Jun 04, 2023 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [267010517a](https://linux-hardware.org/?probe=267010517a) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [c0f64d3436](https://linux-hardware.org/?probe=c0f64d3436) | Jun 03, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7a83a98e37](https://linux-hardware.org/?probe=7a83a98e37) | Jun 02, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a78aee5f7f](https://linux-hardware.org/?probe=a78aee5f7f) | Jun 02, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [19043cab25](https://linux-hardware.org/?probe=19043cab25) | Jun 01, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [acc54fe70f](https://linux-hardware.org/?probe=acc54fe70f) | Jun 01, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [e643aa0f5d](https://linux-hardware.org/?probe=e643aa0f5d) | May 30, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4a54b4e82c](https://linux-hardware.org/?probe=4a54b4e82c) | May 28, 2023 |
| HP            | ProBook 4740s               | Notebook    | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [53d45d0d79](https://linux-hardware.org/?probe=53d45d0d79) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [8d7ce86449](https://linux-hardware.org/?probe=8d7ce86449) | May 26, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [406014a766](https://linux-hardware.org/?probe=406014a766) | May 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcb29a1ec2](https://linux-hardware.org/?probe=dcb29a1ec2) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| Unknown       | T100                        | Desktop     | [c4a7218b7b](https://linux-hardware.org/?probe=c4a7218b7b) | May 18, 2023 |
| HP            | 8055                        | Desktop     | [0efb5c8b5d](https://linux-hardware.org/?probe=0efb5c8b5d) | May 17, 2023 |
| HP            | 8055                        | Desktop     | [d660088965](https://linux-hardware.org/?probe=d660088965) | May 17, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [1b444989b5](https://linux-hardware.org/?probe=1b444989b5) | May 16, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Unknown       | T100                        | Desktop     | [977cdddeb1](https://linux-hardware.org/?probe=977cdddeb1) | May 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| Acer          | Aspire E1-521               | Notebook    | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [80b16a8567](https://linux-hardware.org/?probe=80b16a8567) | May 08, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| HP            | 81BB                        | All in one  | [8c50716d55](https://linux-hardware.org/?probe=8c50716d55) | May 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [c7308f11ce](https://linux-hardware.org/?probe=c7308f11ce) | May 06, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [088deaf386](https://linux-hardware.org/?probe=088deaf386) | May 04, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [057eeed322](https://linux-hardware.org/?probe=057eeed322) | May 03, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [69d95c7c30](https://linux-hardware.org/?probe=69d95c7c30) | May 02, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [864b1a4325](https://linux-hardware.org/?probe=864b1a4325) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | Notebook    | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| HP            | 1489                        | All in one  | [ebd3760355](https://linux-hardware.org/?probe=ebd3760355) | Apr 26, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a8bd7a401e](https://linux-hardware.org/?probe=a8bd7a401e) | Apr 26, 2023 |
| HP            | 1489                        | All in one  | [1058adaefd](https://linux-hardware.org/?probe=1058adaefd) | Apr 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5ecd3ed1bd](https://linux-hardware.org/?probe=5ecd3ed1bd) | Apr 23, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [eeed9900b0](https://linux-hardware.org/?probe=eeed9900b0) | Apr 23, 2023 |
| Dell          | Inspiron 7591 2n1           | Convertible | [9896e8b804](https://linux-hardware.org/?probe=9896e8b804) | Apr 22, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [e915245bfd](https://linux-hardware.org/?probe=e915245bfd) | Apr 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [78c8b8578f](https://linux-hardware.org/?probe=78c8b8578f) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [41e83eedd0](https://linux-hardware.org/?probe=41e83eedd0) | Apr 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ec36fe087a](https://linux-hardware.org/?probe=ec36fe087a) | Apr 17, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [094563419e](https://linux-hardware.org/?probe=094563419e) | Apr 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | Notebook    | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [e84598d67c](https://linux-hardware.org/?probe=e84598d67c) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [488dc3a686](https://linux-hardware.org/?probe=488dc3a686) | Mar 31, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [bf1af4af46](https://linux-hardware.org/?probe=bf1af4af46) | Mar 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c239e06998](https://linux-hardware.org/?probe=c239e06998) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| Pegatron      | Maureen                     | Desktop     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Google        | Swanky                      | Notebook    | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [7f46837f94](https://linux-hardware.org/?probe=7f46837f94) | Mar 28, 2023 |
| HP            | ProBook 6550b               | Notebook    | [4629264a10](https://linux-hardware.org/?probe=4629264a10) | Mar 27, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8ddc916615](https://linux-hardware.org/?probe=8ddc916615) | Mar 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [7dc2dc172d](https://linux-hardware.org/?probe=7dc2dc172d) | Mar 18, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [67d6333f85](https://linux-hardware.org/?probe=67d6333f85) | Mar 15, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [a1fd7807c6](https://linux-hardware.org/?probe=a1fd7807c6) | Mar 15, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [0185de4fa6](https://linux-hardware.org/?probe=0185de4fa6) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [bde56e1cc3](https://linux-hardware.org/?probe=bde56e1cc3) | Mar 11, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7e668b89fa](https://linux-hardware.org/?probe=7e668b89fa) | Mar 07, 2023 |
| HP            | Notebook                    | Notebook    | [06e805be3d](https://linux-hardware.org/?probe=06e805be3d) | Mar 06, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [bd9c4997b0](https://linux-hardware.org/?probe=bd9c4997b0) | Mar 06, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [b2b79c4b50](https://linux-hardware.org/?probe=b2b79c4b50) | Mar 06, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [b0b2b55298](https://linux-hardware.org/?probe=b0b2b55298) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [da5eea6a75](https://linux-hardware.org/?probe=da5eea6a75) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [64b2c8d5b9](https://linux-hardware.org/?probe=64b2c8d5b9) | Feb 28, 2023 |
| HP            | 158A                        | Desktop     | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ce2bc0c00d](https://linux-hardware.org/?probe=ce2bc0c00d) | Feb 27, 2023 |
| Dell          | 08HPGT A02                  | Desktop     | [69288a8011](https://linux-hardware.org/?probe=69288a8011) | Feb 24, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8ce6b54b09](https://linux-hardware.org/?probe=8ce6b54b09) | Feb 24, 2023 |
| MSI           | GE63VR 7RF                  | Notebook    | [b9aeb1ce18](https://linux-hardware.org/?probe=b9aeb1ce18) | Feb 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d9fc10c008](https://linux-hardware.org/?probe=d9fc10c008) | Feb 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a6ebba79c9](https://linux-hardware.org/?probe=a6ebba79c9) | Feb 17, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [f9cfe6d485](https://linux-hardware.org/?probe=f9cfe6d485) | Feb 13, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [23a79acb25](https://linux-hardware.org/?probe=23a79acb25) | Feb 13, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [d1c4626fd3](https://linux-hardware.org/?probe=d1c4626fd3) | Feb 13, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [dfb8064df6](https://linux-hardware.org/?probe=dfb8064df6) | Feb 12, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [deff8d7055](https://linux-hardware.org/?probe=deff8d7055) | Feb 11, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [b11ab46e6e](https://linux-hardware.org/?probe=b11ab46e6e) | Feb 10, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [f0b972d056](https://linux-hardware.org/?probe=f0b972d056) | Feb 10, 2023 |
| Dell          | System XPS L702X            | Notebook    | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [0677b143ac](https://linux-hardware.org/?probe=0677b143ac) | Feb 07, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [93c3d6c151](https://linux-hardware.org/?probe=93c3d6c151) | Feb 06, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [1614d002e0](https://linux-hardware.org/?probe=1614d002e0) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [adb2f19fcd](https://linux-hardware.org/?probe=adb2f19fcd) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb4687961f](https://linux-hardware.org/?probe=eb4687961f) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| Lenovo        | ThinkPad T480 20L5001KAU    | Notebook    | [4b7046e26c](https://linux-hardware.org/?probe=4b7046e26c) | Jan 30, 2023 |
| Acer          | E1-510                      | Notebook    | [659bb96537](https://linux-hardware.org/?probe=659bb96537) | Jan 29, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [93020dd688](https://linux-hardware.org/?probe=93020dd688) | Jan 28, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ec43ef5c17](https://linux-hardware.org/?probe=ec43ef5c17) | Jan 25, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [9d0f65f90f](https://linux-hardware.org/?probe=9d0f65f90f) | Jan 24, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [3e7a2dabb5](https://linux-hardware.org/?probe=3e7a2dabb5) | Jan 24, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d27e517254](https://linux-hardware.org/?probe=d27e517254) | Jan 21, 2023 |
| Lenovo        | ThinkPad T420 4180AQ3       | Notebook    | [567ae7f5ba](https://linux-hardware.org/?probe=567ae7f5ba) | Jan 21, 2023 |
| DFI           | CR101-CST                   | Desktop     | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| Toshiba       | PORTEGE M780                | Notebook    | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [e8d037a152](https://linux-hardware.org/?probe=e8d037a152) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [02089f3393](https://linux-hardware.org/?probe=02089f3393) | Jan 20, 2023 |
| HP            | ProBook 4740s               | Notebook    | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dae35d1c18](https://linux-hardware.org/?probe=dae35d1c18) | Jan 19, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4afba6f67d](https://linux-hardware.org/?probe=4afba6f67d) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bcae5d5664](https://linux-hardware.org/?probe=bcae5d5664) | Jan 18, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ea58101334](https://linux-hardware.org/?probe=ea58101334) | Jan 17, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [983230429d](https://linux-hardware.org/?probe=983230429d) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | Notebook    | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [bcb3fca0a2](https://linux-hardware.org/?probe=bcb3fca0a2) | Jan 10, 2023 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [20bfe72df5](https://linux-hardware.org/?probe=20bfe72df5) | Jan 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444G... | Notebook    | [29331861b5](https://linux-hardware.org/?probe=29331861b5) | Jan 09, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [aaf51b3c3b](https://linux-hardware.org/?probe=aaf51b3c3b) | Jan 09, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [a5638d3bf2](https://linux-hardware.org/?probe=a5638d3bf2) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [ad72a0fad1](https://linux-hardware.org/?probe=ad72a0fad1) | Jan 08, 2023 |
| Sony          | VGN-Z16GN_B                 | Notebook    | [63bb6c7c43](https://linux-hardware.org/?probe=63bb6c7c43) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [45c8b096c5](https://linux-hardware.org/?probe=45c8b096c5) | Jan 08, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [aa8715fc5c](https://linux-hardware.org/?probe=aa8715fc5c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [8a7807ff8c](https://linux-hardware.org/?probe=8a7807ff8c) | Jan 03, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1b66a8a1a8](https://linux-hardware.org/?probe=1b66a8a1a8) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| Dell          | Precision 7740              | Notebook    | [952da37737](https://linux-hardware.org/?probe=952da37737) | Jan 02, 2023 |
| HP            | 81BB                        | All in one  | [151d8bcaf3](https://linux-hardware.org/?probe=151d8bcaf3) | Jan 02, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [3f2b642eb0](https://linux-hardware.org/?probe=3f2b642eb0) | Jan 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | 17E2                        | Mini pc     | [8460664f2a](https://linux-hardware.org/?probe=8460664f2a) | Dec 28, 2022 |
| HP            | 3648h                       | Desktop     | [5b3a2d7e48](https://linux-hardware.org/?probe=5b3a2d7e48) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [03c35b7588](https://linux-hardware.org/?probe=03c35b7588) | Dec 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [b88840bfdf](https://linux-hardware.org/?probe=b88840bfdf) | Dec 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe5df748b0](https://linux-hardware.org/?probe=fe5df748b0) | Dec 23, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [534f769938](https://linux-hardware.org/?probe=534f769938) | Dec 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [56781f9824](https://linux-hardware.org/?probe=56781f9824) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [39bac65c16](https://linux-hardware.org/?probe=39bac65c16) | Dec 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Google        | Laser14                     | Notebook    | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [b333e1030f](https://linux-hardware.org/?probe=b333e1030f) | Dec 16, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d6d4bd4dcd](https://linux-hardware.org/?probe=d6d4bd4dcd) | Dec 14, 2022 |
| HP            | Pavilion dv6                | Notebook    | [2472ce95cb](https://linux-hardware.org/?probe=2472ce95cb) | Dec 14, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [e2ecbddf15](https://linux-hardware.org/?probe=e2ecbddf15) | Dec 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [3eb157838e](https://linux-hardware.org/?probe=3eb157838e) | Dec 13, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [d9cc4844ac](https://linux-hardware.org/?probe=d9cc4844ac) | Dec 12, 2022 |
| HP            | 81BB                        | All in one  | [7efed40466](https://linux-hardware.org/?probe=7efed40466) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [967204fede](https://linux-hardware.org/?probe=967204fede) | Dec 09, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [5a6ebebd51](https://linux-hardware.org/?probe=5a6ebebd51) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [68004f52cd](https://linux-hardware.org/?probe=68004f52cd) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [3912675c64](https://linux-hardware.org/?probe=3912675c64) | Dec 06, 2022 |
| HP            | 81BB                        | All in one  | [0cc2f0b745](https://linux-hardware.org/?probe=0cc2f0b745) | Dec 06, 2022 |
| HP            | 81BB                        | All in one  | [7d64b102e1](https://linux-hardware.org/?probe=7d64b102e1) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [037216f966](https://linux-hardware.org/?probe=037216f966) | Dec 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [1c27bd3d06](https://linux-hardware.org/?probe=1c27bd3d06) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| HP            | 1495                        | Desktop     | [138b5bb823](https://linux-hardware.org/?probe=138b5bb823) | Dec 01, 2022 |
| Acer          | E1-510                      | Notebook    | [8aadf699f9](https://linux-hardware.org/?probe=8aadf699f9) | Nov 30, 2022 |
| Dell          | G7 7700                     | Notebook    | [16407c6485](https://linux-hardware.org/?probe=16407c6485) | Nov 27, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [81a2eaf6e4](https://linux-hardware.org/?probe=81a2eaf6e4) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [dd85fb5c80](https://linux-hardware.org/?probe=dd85fb5c80) | Nov 22, 2022 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [462cb0ce56](https://linux-hardware.org/?probe=462cb0ce56) | Nov 21, 2022 |
| Google        | Swanky                      | Notebook    | [1a0a358398](https://linux-hardware.org/?probe=1a0a358398) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| HP            | 339A                        | Desktop     | [c995f831b8](https://linux-hardware.org/?probe=c995f831b8) | Nov 13, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2382574dbd](https://linux-hardware.org/?probe=2382574dbd) | Nov 12, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b414369067](https://linux-hardware.org/?probe=b414369067) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a41cabb3d6](https://linux-hardware.org/?probe=a41cabb3d6) | Nov 04, 2022 |
| Dell          | 0UW816 A00                  | Server      | [a9a5e01e23](https://linux-hardware.org/?probe=a9a5e01e23) | Nov 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [27bc8e172c](https://linux-hardware.org/?probe=27bc8e172c) | Nov 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6702cb2ca7](https://linux-hardware.org/?probe=6702cb2ca7) | Oct 25, 2022 |
| Dell          | 0GXH08 A01                  | Server      | [f3c7a026b6](https://linux-hardware.org/?probe=f3c7a026b6) | Oct 24, 2022 |
| Google        | Swanky                      | Notebook    | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Google        | Swanky                      | Notebook    | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [d5b2d74cd8](https://linux-hardware.org/?probe=d5b2d74cd8) | Oct 21, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [e39bc1af0b](https://linux-hardware.org/?probe=e39bc1af0b) | Oct 20, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [e939a5f236](https://linux-hardware.org/?probe=e939a5f236) | Oct 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Toshiba       | Satellite L750              | Notebook    | [9998a32d98](https://linux-hardware.org/?probe=9998a32d98) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Dell          | Precision 3570              | Notebook    | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9b3c73c104](https://linux-hardware.org/?probe=9b3c73c104) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4cdcef3ebd](https://linux-hardware.org/?probe=4cdcef3ebd) | Sep 28, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| HP            | 15                          | Notebook    | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HP            | 15                          | Notebook    | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| Dell          | 0UW816 A00                  | Server      | [bd29b42f73](https://linux-hardware.org/?probe=bd29b42f73) | Sep 17, 2022 |
| Dell          | 0UW816 A00                  | Server      | [9959a5f63d](https://linux-hardware.org/?probe=9959a5f63d) | Sep 17, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c5474e5fe3](https://linux-hardware.org/?probe=c5474e5fe3) | Sep 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9bfc1472d1](https://linux-hardware.org/?probe=9bfc1472d1) | Sep 16, 2022 |
| Google        | Snappy                      | Notebook    | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [4db3f9151e](https://linux-hardware.org/?probe=4db3f9151e) | Sep 11, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [5877abaab3](https://linux-hardware.org/?probe=5877abaab3) | Sep 07, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [a353883ee2](https://linux-hardware.org/?probe=a353883ee2) | Sep 07, 2022 |
| MSI           | MS-98H3                     | Desktop     | [41ad960dd6](https://linux-hardware.org/?probe=41ad960dd6) | Sep 06, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0e3f950f3f](https://linux-hardware.org/?probe=0e3f950f3f) | Sep 02, 2022 |
| The Wareho... | E2037                       | Notebook    | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | Latitude 5420               | Notebook    | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8f8107b683](https://linux-hardware.org/?probe=8f8107b683) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [e3b89ab2db](https://linux-hardware.org/?probe=e3b89ab2db) | Aug 27, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| ASUSTek       | P81IJ                       | Notebook    | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [b41e0fcad5](https://linux-hardware.org/?probe=b41e0fcad5) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | Notebook    | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Acer          | Aspire M5-581TG             | Notebook    | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d7dee32799](https://linux-hardware.org/?probe=d7dee32799) | Aug 23, 2022 |
| Google        | Galtic                      | Notebook    | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | Latitude E6500              | Notebook    | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [51f5d50d85](https://linux-hardware.org/?probe=51f5d50d85) | Aug 22, 2022 |
| ASRock        | 890GM Pro3                  | Desktop     | [002a0c3f5a](https://linux-hardware.org/?probe=002a0c3f5a) | Aug 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [92525ee03c](https://linux-hardware.org/?probe=92525ee03c) | Aug 17, 2022 |
| Lenovo        | 3190 SDK0T76530 WIN 3556... | Mini pc     | [766a8b38a6](https://linux-hardware.org/?probe=766a8b38a6) | Aug 16, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [4ff9f1893d](https://linux-hardware.org/?probe=4ff9f1893d) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [c9e9691195](https://linux-hardware.org/?probe=c9e9691195) | Aug 10, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [91438d7bdd](https://linux-hardware.org/?probe=91438d7bdd) | Aug 06, 2022 |
| Acer          | Spin SP513-51               | Convertible | [7531ebdab5](https://linux-hardware.org/?probe=7531ebdab5) | Aug 05, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [4956d72048](https://linux-hardware.org/?probe=4956d72048) | Aug 01, 2022 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [827883d38c](https://linux-hardware.org/?probe=827883d38c) | Aug 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [163affcbb8](https://linux-hardware.org/?probe=163affcbb8) | Aug 01, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| Intel         | NUC5i7RYB H73774-104        | Mini pc     | [773e4afb47](https://linux-hardware.org/?probe=773e4afb47) | Jul 30, 2022 |
| HP            | 2000                        | Notebook    | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| HP            | 8054                        | Desktop     | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| HP            | Notebook                    | Notebook    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| Intel         | STK1AW32SC H91596-307       | Desktop     | [78225ba5b9](https://linux-hardware.org/?probe=78225ba5b9) | Jul 21, 2022 |
| HP            | 3397                        | Desktop     | [83bdaea8fc](https://linux-hardware.org/?probe=83bdaea8fc) | Jul 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | Notebook    | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| Intel         | NUC8i5INB K29935-402        | Mini pc     | [27d189d77f](https://linux-hardware.org/?probe=27d189d77f) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Lenovo        | 14w 81MQ0013AU              | Notebook    | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6d6b4c9d06](https://linux-hardware.org/?probe=6d6b4c9d06) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| Gigabyte      | B460M D3H                   | Desktop     | [d620225518](https://linux-hardware.org/?probe=d620225518) | Jun 30, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [3c8656100a](https://linux-hardware.org/?probe=3c8656100a) | Jun 29, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [97b8d855bd](https://linux-hardware.org/?probe=97b8d855bd) | Jun 28, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [9d9ae107c9](https://linux-hardware.org/?probe=9d9ae107c9) | Jun 25, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [788acf13f2](https://linux-hardware.org/?probe=788acf13f2) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [d11995947a](https://linux-hardware.org/?probe=d11995947a) | Jun 23, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [656f558626](https://linux-hardware.org/?probe=656f558626) | Jun 23, 2022 |
| HP            | 18E7                        | Desktop     | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [36fdd87ff3](https://linux-hardware.org/?probe=36fdd87ff3) | Jun 21, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| HP            | 550                         | Notebook    | [1db816d0b2](https://linux-hardware.org/?probe=1db816d0b2) | Jun 19, 2022 |
| Dell          | Precision 3571              | Notebook    | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | Notebook    | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [874c85b694](https://linux-hardware.org/?probe=874c85b694) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [38bf9d2a7b](https://linux-hardware.org/?probe=38bf9d2a7b) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [f7d3ee91c6](https://linux-hardware.org/?probe=f7d3ee91c6) | Jun 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [4347d50981](https://linux-hardware.org/?probe=4347d50981) | Jun 12, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bee7f3506c](https://linux-hardware.org/?probe=bee7f3506c) | May 29, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [512d3f18ce](https://linux-hardware.org/?probe=512d3f18ce) | May 28, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [af7e6249f0](https://linux-hardware.org/?probe=af7e6249f0) | May 27, 2022 |
| Intel         | NUC9i7QNB K49245-403        | Mini pc     | [44ceac3592](https://linux-hardware.org/?probe=44ceac3592) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Toshiba       | Satellite Pro C665          | Notebook    | [23fd853a45](https://linux-hardware.org/?probe=23fd853a45) | May 24, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | Notebook    | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | Notebook    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | Notebook    | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [60d56e6b15](https://linux-hardware.org/?probe=60d56e6b15) | May 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| Alienware     | x17 R2                      | Notebook    | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| HP            | 1998                        | Desktop     | [b717b34f5b](https://linux-hardware.org/?probe=b717b34f5b) | May 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bd6e42ac60](https://linux-hardware.org/?probe=bd6e42ac60) | May 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6693954f79](https://linux-hardware.org/?probe=6693954f79) | May 07, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [2b4d9cbd0c](https://linux-hardware.org/?probe=2b4d9cbd0c) | May 03, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [c994128afd](https://linux-hardware.org/?probe=c994128afd) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7e84138ea1](https://linux-hardware.org/?probe=7e84138ea1) | Apr 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [c3bb583347](https://linux-hardware.org/?probe=c3bb583347) | Apr 24, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [35cf0f09e4](https://linux-hardware.org/?probe=35cf0f09e4) | Apr 22, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [8888cb88d3](https://linux-hardware.org/?probe=8888cb88d3) | Apr 22, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [021cd80ac4](https://linux-hardware.org/?probe=021cd80ac4) | Apr 14, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [ff5563e261](https://linux-hardware.org/?probe=ff5563e261) | Apr 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5ec598483e](https://linux-hardware.org/?probe=5ec598483e) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4295c9a47](https://linux-hardware.org/?probe=d4295c9a47) | Apr 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [5ad4aa0994](https://linux-hardware.org/?probe=5ad4aa0994) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3ddf8a6825](https://linux-hardware.org/?probe=3ddf8a6825) | Apr 11, 2022 |
| Dell          | Inspiron 7405 2n1           | Convertible | [9fa115228c](https://linux-hardware.org/?probe=9fa115228c) | Apr 11, 2022 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [1a7b7179f7](https://linux-hardware.org/?probe=1a7b7179f7) | Apr 10, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| HP            | 1790                        | Desktop     | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [a7ee814f3a](https://linux-hardware.org/?probe=a7ee814f3a) | Apr 02, 2022 |
| Dell          | Latitude 7480               | Notebook    | [ccc8107d39](https://linux-hardware.org/?probe=ccc8107d39) | Apr 01, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| eMachines     | eM350                       | Notebook    | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [9b194b03b4](https://linux-hardware.org/?probe=9b194b03b4) | Mar 25, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [c05eaeb499](https://linux-hardware.org/?probe=c05eaeb499) | Mar 24, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [cf9c727b0d](https://linux-hardware.org/?probe=cf9c727b0d) | Mar 24, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e12f0f1eed](https://linux-hardware.org/?probe=e12f0f1eed) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [24d5a323cc](https://linux-hardware.org/?probe=24d5a323cc) | Mar 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [4673f4edd8](https://linux-hardware.org/?probe=4673f4edd8) | Mar 21, 2022 |
| ASUSTek       | P5E                         | Desktop     | [ec2b80980d](https://linux-hardware.org/?probe=ec2b80980d) | Mar 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [08dc6f6fe3](https://linux-hardware.org/?probe=08dc6f6fe3) | Mar 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33980f3303](https://linux-hardware.org/?probe=33980f3303) | Mar 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5b83093837](https://linux-hardware.org/?probe=5b83093837) | Mar 15, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [fc12718113](https://linux-hardware.org/?probe=fc12718113) | Mar 13, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [8a7c1daf70](https://linux-hardware.org/?probe=8a7c1daf70) | Mar 13, 2022 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [64f278889f](https://linux-hardware.org/?probe=64f278889f) | Mar 13, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [c39fe1a3e3](https://linux-hardware.org/?probe=c39fe1a3e3) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [5c169a1d32](https://linux-hardware.org/?probe=5c169a1d32) | Feb 25, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [dfebbb508b](https://linux-hardware.org/?probe=dfebbb508b) | Feb 24, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [26729d3227](https://linux-hardware.org/?probe=26729d3227) | Feb 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96aa797713](https://linux-hardware.org/?probe=96aa797713) | Feb 21, 2022 |
| HP            | 2AF7                        | Desktop     | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [c7a12417f1](https://linux-hardware.org/?probe=c7a12417f1) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [cc2c71140b](https://linux-hardware.org/?probe=cc2c71140b) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [4d1d42c8cc](https://linux-hardware.org/?probe=4d1d42c8cc) | Feb 20, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [024513d4a8](https://linux-hardware.org/?probe=024513d4a8) | Feb 18, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [9bc33ce91e](https://linux-hardware.org/?probe=9bc33ce91e) | Feb 16, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [d185900f87](https://linux-hardware.org/?probe=d185900f87) | Feb 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc420f69ce](https://linux-hardware.org/?probe=cc420f69ce) | Feb 16, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [3324e66890](https://linux-hardware.org/?probe=3324e66890) | Feb 15, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [bf684bced7](https://linux-hardware.org/?probe=bf684bced7) | Feb 14, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [c2bd021f7e](https://linux-hardware.org/?probe=c2bd021f7e) | Feb 13, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [caf1721ebe](https://linux-hardware.org/?probe=caf1721ebe) | Feb 12, 2022 |
| ASUSTek       | K55A                        | Notebook    | [e88dba3a7e](https://linux-hardware.org/?probe=e88dba3a7e) | Feb 12, 2022 |
| System76      | Lemur Pro                   | Notebook    | [a0e5f04131](https://linux-hardware.org/?probe=a0e5f04131) | Feb 12, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [e534d71dc2](https://linux-hardware.org/?probe=e534d71dc2) | Feb 12, 2022 |
| Lenovo        | ThinkPad T470 20HES23B0U    | Notebook    | [c080812ddb](https://linux-hardware.org/?probe=c080812ddb) | Feb 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [24bd4956b6](https://linux-hardware.org/?probe=24bd4956b6) | Feb 05, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [f9c872ec0c](https://linux-hardware.org/?probe=f9c872ec0c) | Jan 30, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | Notebook    | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d8ec503f66](https://linux-hardware.org/?probe=d8ec503f66) | Jan 21, 2022 |
| Supermicro    | X11DPG-QTA                  | Server      | [b714fa4c7f](https://linux-hardware.org/?probe=b714fa4c7f) | Jan 21, 2022 |
| Toshiba       | PORTEGE R930                | Notebook    | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| MediaVue      | MV-890GX V1.2               | Desktop     | [201163da2f](https://linux-hardware.org/?probe=201163da2f) | Jan 16, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [11bf29bdd1](https://linux-hardware.org/?probe=11bf29bdd1) | Jan 16, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [bf909a21dd](https://linux-hardware.org/?probe=bf909a21dd) | Jan 15, 2022 |
| Star Labs     | LabTop                      | Notebook    | [c7cc8bae59](https://linux-hardware.org/?probe=c7cc8bae59) | Jan 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b05f843820](https://linux-hardware.org/?probe=b05f843820) | Jan 06, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [2e7edfda25](https://linux-hardware.org/?probe=2e7edfda25) | Jan 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [d7b4fd099d](https://linux-hardware.org/?probe=d7b4fd099d) | Jan 01, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| Apple         | Mac-F2218FC8                | All in one  | [7f5484cd91](https://linux-hardware.org/?probe=7f5484cd91) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [51f97b7e46](https://linux-hardware.org/?probe=51f97b7e46) | Dec 25, 2021 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Google        | Kip                         | Notebook    | [8c60d949d0](https://linux-hardware.org/?probe=8c60d949d0) | Dec 20, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [3962478b0f](https://linux-hardware.org/?probe=3962478b0f) | Dec 19, 2021 |
| Colorful T... | BATTLE-AX B450M-G DELUXE... | Desktop     | [52614e9f8d](https://linux-hardware.org/?probe=52614e9f8d) | Dec 19, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [8421d8ab8c](https://linux-hardware.org/?probe=8421d8ab8c) | Dec 19, 2021 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [a6ddae1f31](https://linux-hardware.org/?probe=a6ddae1f31) | Dec 15, 2021 |
| Intel         | DQ87PG AAG74154-403         | Desktop     | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [71f69762fe](https://linux-hardware.org/?probe=71f69762fe) | Dec 08, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [572b9da8d1](https://linux-hardware.org/?probe=572b9da8d1) | Dec 06, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [01a565720c](https://linux-hardware.org/?probe=01a565720c) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Dell          | System XPS L702X            | Notebook    | [805619ba8c](https://linux-hardware.org/?probe=805619ba8c) | Nov 25, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [939cd87ee7](https://linux-hardware.org/?probe=939cd87ee7) | Nov 22, 2021 |
| Intel         | NUC7i5DNB J57626-504        | Mini pc     | [d2625c256e](https://linux-hardware.org/?probe=d2625c256e) | Nov 22, 2021 |
| Intel         | NUC7i5DNB J57626-504        | Mini pc     | [12c79d3e71](https://linux-hardware.org/?probe=12c79d3e71) | Nov 21, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2bb3dc142](https://linux-hardware.org/?probe=e2bb3dc142) | Nov 21, 2021 |
| HP            | 3396                        | Desktop     | [db69ec8696](https://linux-hardware.org/?probe=db69ec8696) | Nov 17, 2021 |
| HP            | 3396                        | Desktop     | [70fc3e699a](https://linux-hardware.org/?probe=70fc3e699a) | Nov 17, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [0c64127bf0](https://linux-hardware.org/?probe=0c64127bf0) | Nov 13, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9fc484d01e](https://linux-hardware.org/?probe=9fc484d01e) | Nov 11, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [edc363bc59](https://linux-hardware.org/?probe=edc363bc59) | Nov 11, 2021 |
| Timi          | A30                         | Notebook    | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | Notebook    | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | Notebook    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [95e40c6343](https://linux-hardware.org/?probe=95e40c6343) | Oct 30, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [b6966ebc42](https://linux-hardware.org/?probe=b6966ebc42) | Oct 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [94e0e3f047](https://linux-hardware.org/?probe=94e0e3f047) | Oct 27, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [f2ce1a8260](https://linux-hardware.org/?probe=f2ce1a8260) | Oct 26, 2021 |
| HP            | Spectre x2 Detachable       | Notebook    | [d20c059f3d](https://linux-hardware.org/?probe=d20c059f3d) | Oct 24, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [97bd114229](https://linux-hardware.org/?probe=97bd114229) | Oct 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [01ca7ca744](https://linux-hardware.org/?probe=01ca7ca744) | Oct 23, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [74c2c9d725](https://linux-hardware.org/?probe=74c2c9d725) | Oct 22, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [cfffe6aa63](https://linux-hardware.org/?probe=cfffe6aa63) | Oct 18, 2021 |
| Dell          | Latitude 7490               | Notebook    | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| IBM           | 81Y7071 SVT-R               | Desktop     | [033203aade](https://linux-hardware.org/?probe=033203aade) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | Notebook    | [1410381a3d](https://linux-hardware.org/?probe=1410381a3d) | Oct 16, 2021 |
| HP            | Pavilion tx2500             | Notebook    | [e420777c94](https://linux-hardware.org/?probe=e420777c94) | Oct 16, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [26e0d9a3d9](https://linux-hardware.org/?probe=26e0d9a3d9) | Oct 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [8e878489d3](https://linux-hardware.org/?probe=8e878489d3) | Oct 15, 2021 |
| HP            | 2B42                        | All in one  | [42d66aed80](https://linux-hardware.org/?probe=42d66aed80) | Oct 14, 2021 |
| Dell          | Latitude 7285               | Notebook    | [5097e0f8c8](https://linux-hardware.org/?probe=5097e0f8c8) | Oct 14, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [530994c225](https://linux-hardware.org/?probe=530994c225) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| Acer          | Aspire VN7-593G             | Notebook    | [d9f2adbdfc](https://linux-hardware.org/?probe=d9f2adbdfc) | Oct 11, 2021 |
| MSI           | 2AE0                        | Desktop     | [e5ede0905a](https://linux-hardware.org/?probe=e5ede0905a) | Oct 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7b579629bb](https://linux-hardware.org/?probe=7b579629bb) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [55620348e7](https://linux-hardware.org/?probe=55620348e7) | Oct 08, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [636ef76e1e](https://linux-hardware.org/?probe=636ef76e1e) | Oct 05, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [ca8c02f319](https://linux-hardware.org/?probe=ca8c02f319) | Sep 29, 2021 |
| JGINYUE       | H97I PLUS V2.0              | Desktop     | [2e66de23a2](https://linux-hardware.org/?probe=2e66de23a2) | Sep 28, 2021 |
| Dell          | 0D6H9T A02                  | Desktop     | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | Notebook    | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [fb59bae064](https://linux-hardware.org/?probe=fb59bae064) | Sep 23, 2021 |
| Lenovo        | Aptio CRB SDK0J40700 WIN... | Mini pc     | [9fc0fe4a5f](https://linux-hardware.org/?probe=9fc0fe4a5f) | Sep 22, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [85b5f14102](https://linux-hardware.org/?probe=85b5f14102) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [2b8efc01ba](https://linux-hardware.org/?probe=2b8efc01ba) | Sep 22, 2021 |
| HP            | 3398                        | Desktop     | [18b064d0d6](https://linux-hardware.org/?probe=18b064d0d6) | Sep 22, 2021 |
| HP            | 1905                        | Desktop     | [56945cef9c](https://linux-hardware.org/?probe=56945cef9c) | Sep 19, 2021 |
| MSI           | GE66 Raider 10SF            | Notebook    | [9d11ef435a](https://linux-hardware.org/?probe=9d11ef435a) | Sep 16, 2021 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [8f19930d07](https://linux-hardware.org/?probe=8f19930d07) | Sep 15, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d172a59c18](https://linux-hardware.org/?probe=d172a59c18) | Sep 14, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [eb8b4b37a4](https://linux-hardware.org/?probe=eb8b4b37a4) | Sep 13, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [a0376eeefc](https://linux-hardware.org/?probe=a0376eeefc) | Sep 13, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [83bf40cb1d](https://linux-hardware.org/?probe=83bf40cb1d) | Sep 12, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [65102530f5](https://linux-hardware.org/?probe=65102530f5) | Sep 12, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/New_Zealand/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 85        | 7.52%   |
| Ubuntu 22.04                 | 73        | 6.46%   |
| Ubuntu 18.04                 | 49        | 4.34%   |
| Pop!_OS 22.04                | 40        | 3.54%   |
| Arch Rolling                 | 37        | 3.27%   |
| Zorin 16                     | 26        | 2.3%    |
| Debian 11                    | 25        | 2.21%   |
| Debian 12                    | 23        | 2.04%   |
| Ubuntu 24.04                 | 22        | 1.95%   |
| Pop!_OS 20.04                | 17        | 1.5%    |
| OpenMandriva 4.3             | 16        | 1.42%   |
| Fedora 40                    | 15        | 1.33%   |
| Ubuntu 20.10                 | 14        | 1.24%   |
| Pop!_OS 20.10                | 14        | 1.24%   |
| Zorin 17                     | 13        | 1.15%   |
| Zorin 15                     | 13        | 1.15%   |
| Manjaro                      | 13        | 1.15%   |
| OpenMandriva 4.2             | 12        | 1.06%   |
| Linux Mint 21.1              | 12        | 1.06%   |
| Linux Mint 20.3              | 12        | 1.06%   |
| Fedora 36                    | 12        | 1.06%   |
| Arch                         | 12        | 1.06%   |
| Ubuntu 21.04                 | 11        | 0.97%   |
| Linux Mint 20.2              | 11        | 0.97%   |
| Fedora 39                    | 11        | 0.97%   |
| Fedora 37                    | 11        | 0.97%   |
| Fedora 34                    | 11        | 0.97%   |
| Fedora 33                    | 11        | 0.97%   |
| Debian 10                    | 11        | 0.97%   |
| Pop!_OS 21.04                | 10        | 0.88%   |
| OpenMandriva 24.12           | 10        | 0.88%   |
| Linux Mint 20.1              | 10        | 0.88%   |
| KDE neon 22.04               | 10        | 0.88%   |
| Fedora 31                    | 10        | 0.88%   |
| Ubuntu 21.10                 | 9         | 0.8%    |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 0.8%    |
| OpenMandriva 23.01           | 9         | 0.8%    |
| Linux Mint 21.2              | 9         | 0.8%    |
| Kubuntu 22.04                | 9         | 0.8%    |
| Fedora 38                    | 9         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 290       | 27.67%  |
| Fedora           | 94        | 8.97%   |
| Linux Mint       | 92        | 8.78%   |
| Pop!_OS          | 84        | 8.02%   |
| OpenMandriva     | 68        | 6.49%   |
| Debian           | 64        | 6.11%   |
| Zorin            | 51        | 4.87%   |
| Arch             | 48        | 4.58%   |
| Manjaro          | 27        | 2.58%   |
| Kubuntu          | 25        | 2.39%   |
| KDE neon         | 21        | 2%      |
| Endless          | 16        | 1.53%   |
| Xubuntu          | 11        | 1.05%   |
| Nobara           | 11        | 1.05%   |
| Elementary       | 11        | 1.05%   |
| ArcoLinux        | 10        | 0.95%   |
| openSUSE         | 9         | 0.86%   |
| Kali             | 9         | 0.86%   |
| MX               | 8         | 0.76%   |
| EndeavourOS      | 7         | 0.67%   |
| Ubuntu Unity     | 6         | 0.57%   |
| LMDE             | 6         | 0.57%   |
| SteamOS          | 5         | 0.48%   |
| ROSA             | 5         | 0.48%   |
| Lubuntu          | 5         | 0.48%   |
| Gentoo           | 5         | 0.48%   |
| Ubuntu MATE      | 4         | 0.38%   |
| Peppermint       | 4         | 0.38%   |
| org.kde.Platform | 4         | 0.38%   |
| Bazzite          | 4         | 0.38%   |
| Solus            | 3         | 0.29%   |
| RHEL             | 3         | 0.29%   |
| Devuan           | 3         | 0.29%   |
| Clear Linux      | 3         | 0.29%   |
| Vanilla          | 2         | 0.19%   |
| Ubuntu Budgie    | 2         | 0.19%   |
| Rocky Linux      | 2         | 0.19%   |
| Parrot           | 2         | 0.19%   |
| NixOS            | 2         | 0.19%   |
| Garuda Linux     | 2         | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 22        | 1.73%   |
| 5.16.7-desktop-1omv4003  | 14        | 1.1%    |
| 5.15.0-46-generic        | 13        | 1.02%   |
| 6.8.0-40-generic         | 12        | 0.94%   |
| 5.10.14-desktop-1omv4002 | 12        | 0.94%   |
| 6.9.3-76060903-generic   | 10        | 0.78%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.71%   |
| 5.15.0-60-generic        | 8         | 0.63%   |
| 6.6.2-desktop-1omv2390   | 7         | 0.55%   |
| 6.12.1-desktop-1omv2490  | 7         | 0.55%   |
| 6.0.12-76060006-generic  | 7         | 0.55%   |
| 5.4.0-7634-generic       | 7         | 0.55%   |
| 5.4.0-65-generic         | 7         | 0.55%   |
| 5.15.0-58-generic        | 7         | 0.55%   |
| 5.15.0-56-generic        | 7         | 0.55%   |
| 6.8.0-41-generic         | 6         | 0.47%   |
| 6.5.0-35-generic         | 6         | 0.47%   |
| 6.2.6-desktop-1omv2390   | 6         | 0.47%   |
| 5.4.0-48-generic         | 6         | 0.47%   |
| 5.3.0-46-generic         | 6         | 0.47%   |
| 5.3.0-40-generic         | 6         | 0.47%   |
| 5.13.0-30-generic        | 6         | 0.47%   |
| 5.11.0-7620-generic      | 6         | 0.47%   |
| 5.11.0-37-generic        | 6         | 0.47%   |
| 5.10.0-16-amd64          | 6         | 0.47%   |
| 5.0.0-37-generic         | 6         | 0.47%   |
| 6.8.0-45-generic         | 5         | 0.39%   |
| 6.8.0-38-generic         | 5         | 0.39%   |
| 6.5.6-76060506-generic   | 5         | 0.39%   |
| 6.5.0-41-generic         | 5         | 0.39%   |
| 6.4.11-desktop-1omv2390  | 5         | 0.39%   |
| 6.2.0-39-generic         | 5         | 0.39%   |
| 6.2.0-20-generic         | 5         | 0.39%   |
| 6.10.0-desktop-1omv2490  | 5         | 0.39%   |
| 5.8.0-43-generic         | 5         | 0.39%   |
| 5.4.0-7642-generic       | 5         | 0.39%   |
| 5.4.0-74-generic         | 5         | 0.39%   |
| 5.4.0-52-generic         | 5         | 0.39%   |
| 5.4.0-45-generic         | 5         | 0.39%   |
| 5.3.16-300.fc31.x86_64   | 5         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 122       | 10.22%  |
| 5.15.0  | 95        | 7.96%   |
| 5.11.0  | 45        | 3.77%   |
| 5.13.0  | 44        | 3.69%   |
| 5.8.0   | 43        | 3.6%    |
| 6.8.0   | 42        | 3.52%   |
| 4.15.0  | 41        | 3.43%   |
| 6.5.0   | 38        | 3.18%   |
| 5.3.0   | 36        | 3.02%   |
| 5.19.0  | 33        | 2.76%   |
| 6.1.0   | 32        | 2.68%   |
| 6.2.0   | 29        | 2.43%   |
| 5.10.0  | 27        | 2.26%   |
| 5.0.0   | 20        | 1.68%   |
| 4.18.0  | 20        | 1.68%   |
| 5.16.7  | 14        | 1.17%   |
| 5.10.14 | 13        | 1.09%   |
| 6.9.3   | 11        | 0.92%   |
| 6.1.1   | 11        | 0.92%   |
| 6.2.6   | 9         | 0.75%   |
| 6.12.1  | 9         | 0.75%   |
| 4.19.0  | 9         | 0.75%   |
| 6.4.11  | 8         | 0.67%   |
| 6.0.12  | 8         | 0.67%   |
| 6.6.2   | 7         | 0.59%   |
| 6.5.6   | 7         | 0.59%   |
| 6.8.11  | 5         | 0.42%   |
| 6.10.0  | 5         | 0.42%   |
| 5.3.16  | 5         | 0.42%   |
| 5.17.5  | 5         | 0.42%   |
| 5.14.0  | 5         | 0.42%   |
| 6.9.12  | 4         | 0.34%   |
| 6.8.8   | 4         | 0.34%   |
| 6.8.12  | 4         | 0.34%   |
| 6.7.7   | 4         | 0.34%   |
| 6.4.10  | 4         | 0.34%   |
| 6.11.0  | 4         | 0.34%   |
| 6.10.9  | 4         | 0.34%   |
| 6.1.52  | 4         | 0.34%   |
| 6.0.0   | 4         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 130       | 11.1%   |
| 5.15    | 125       | 10.67%  |
| 6.1     | 71        | 6.06%   |
| 6.8     | 65        | 5.55%   |
| 5.11    | 57        | 4.87%   |
| 5.8     | 53        | 4.53%   |
| 6.5     | 52        | 4.44%   |
| 5.13    | 52        | 4.44%   |
| 5.10    | 51        | 4.36%   |
| 6.2     | 47        | 4.01%   |
| 5.3     | 43        | 3.67%   |
| 5.19    | 42        | 3.59%   |
| 4.15    | 41        | 3.5%    |
| 5.16    | 26        | 2.22%   |
| 6.10    | 24        | 2.05%   |
| 6.0     | 22        | 1.88%   |
| 6.6     | 21        | 1.79%   |
| 5.0     | 21        | 1.79%   |
| 4.18    | 21        | 1.79%   |
| 6.9     | 20        | 1.71%   |
| 6.4     | 20        | 1.71%   |
| 5.18    | 17        | 1.45%   |
| 6.11    | 15        | 1.28%   |
| 5.14    | 15        | 1.28%   |
| 6.12    | 14        | 1.2%    |
| 5.17    | 14        | 1.2%    |
| 6.7     | 13        | 1.11%   |
| 5.9     | 12        | 1.02%   |
| 5.6     | 12        | 1.02%   |
| 6.3     | 11        | 0.94%   |
| 5.7     | 11        | 0.94%   |
| 4.19    | 10        | 0.85%   |
| 5.12    | 7         | 0.6%    |
| 5.5     | 4         | 0.34%   |
| 4.9     | 4         | 0.34%   |
| 5.2     | 2         | 0.17%   |
| 4.20    | 2         | 0.17%   |
| 4.4     | 1         | 0.09%   |
| 4.14    | 1         | 0.09%   |
| 4.13    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 981       | 98.2%   |
| i686    | 10        | 1%      |
| aarch64 | 5         | 0.5%    |
| armv7l  | 2         | 0.2%    |
| i586    | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 494       | 46.78%  |
| KDE5             | 150       | 14.2%   |
| Unknown          | 124       | 11.74%  |
| X-Cinnamon       | 81        | 7.67%   |
| XFCE             | 60        | 5.68%   |
| MATE             | 24        | 2.27%   |
| KDE6             | 24        | 2.27%   |
| KDE              | 23        | 2.18%   |
| LXQt             | 12        | 1.14%   |
| Pantheon         | 11        | 1.04%   |
| Cinnamon         | 9         | 0.85%   |
| LXDE             | 7         | 0.66%   |
| Unity            | 6         | 0.57%   |
| i3               | 5         | 0.47%   |
| Hyprland         | 4         | 0.38%   |
| Deepin           | 4         | 0.38%   |
| Budgie           | 4         | 0.38%   |
| sway             | 2         | 0.19%   |
| icewm            | 2         | 0.19%   |
| i3-with-shmlog   | 2         | 0.19%   |
| xsession         | 1         | 0.09%   |
| Openbox          | 1         | 0.09%   |
| NONE             | 1         | 0.09%   |
| lightdm-xsession | 1         | 0.09%   |
| KDE4             | 1         | 0.09%   |
| fluxbox          | 1         | 0.09%   |
| Enlightenment    | 1         | 0.09%   |
| Endless:GNOME    | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 690       | 66.35%  |
| Wayland | 267       | 25.67%  |
| Unknown | 54        | 5.19%   |
| Tty     | 29        | 2.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 526       | 50.33%  |
| SDDM    | 152       | 14.55%  |
| GDM3    | 131       | 12.54%  |
| LightDM | 114       | 10.91%  |
| GDM     | 86        | 8.23%   |
| TDM     | 25        | 2.39%   |
| SLiM    | 4         | 0.38%   |
| Ly      | 2         | 0.19%   |
| LXDM    | 2         | 0.19%   |
| XDM     | 1         | 0.1%    |
| SLIMSKI | 1         | 0.1%    |
| KDM     | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_NZ   | 613       | 58.1%   |
| en_US   | 233       | 22.09%  |
| Unknown | 87        | 8.25%   |
| en_GB   | 52        | 4.93%   |
| C       | 36        | 3.41%   |
| en_AU   | 23        | 2.18%   |
| zh_CN   | 4         | 0.38%   |
| mi_NZ   | 2         | 0.19%   |
| de_DE   | 2         | 0.19%   |
| pt_BR   | 1         | 0.09%   |
| fr_FR   | 1         | 0.09%   |
| C.UTF8  | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 518       | 50.59%  |
| EFI  | 506       | 49.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 744       | 71.68%  |
| Btrfs   | 125       | 12.04%  |
| Overlay | 70        | 6.74%   |
| Tmpfs   | 42        | 4.05%   |
| Unknown | 29        | 2.79%   |
| Xfs     | 11        | 1.06%   |
| Zfs     | 9         | 0.87%   |
| Ext2    | 4         | 0.39%   |
| Ext3    | 2         | 0.19%   |
| XXXXXXX | 1         | 0.1%    |
| F2fs    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 512       | 50.05%  |
| GPT     | 421       | 41.15%  |
| MBR     | 90        | 8.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 876       | 85.38%  |
| Yes       | 150       | 14.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 765       | 75.15%  |
| Yes       | 253       | 24.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 215       | 21.52%  |
| ASUSTek Computer                     | 162       | 16.22%  |
| Gigabyte Technology                  | 114       | 11.41%  |
| Lenovo                               | 105       | 10.51%  |
| Dell                                 | 105       | 10.51%  |
| Acer                                 | 49        | 4.9%    |
| MSI                                  | 37        | 3.7%    |
| Intel                                | 32        | 3.2%    |
| Apple                                | 30        | 3%      |
| ASRock                               | 28        | 2.8%    |
| Toshiba                              | 25        | 2.5%    |
| Unknown                              | 9         | 0.9%    |
| Supermicro                           | 8         | 0.8%    |
| Google                               | 7         | 0.7%    |
| Sony                                 | 6         | 0.6%    |
| Valve                                | 5         | 0.5%    |
| Samsung Electronics                  | 5         | 0.5%    |
| Raspberry Pi Foundation              | 5         | 0.5%    |
| Pegatron                             | 5         | 0.5%    |
| System76                             | 4         | 0.4%    |
| IBM                                  | 4         | 0.4%    |
| Alienware                            | 4         | 0.4%    |
| Microsoft                            | 2         | 0.2%    |
| Kogan                                | 2         | 0.2%    |
| HUAWEI                               | 2         | 0.2%    |
| AMI                                  | 2         | 0.2%    |
| YJKC                                 | 1         | 0.1%    |
| TWG                                  | 1         | 0.1%    |
| Timi                                 | 1         | 0.1%    |
| The Warehouse Group                  | 1         | 0.1%    |
| Star Labs                            | 1         | 0.1%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.1%    |
| ReachingTech                         | 1         | 0.1%    |
| Qualcomm Technologies                | 1         | 0.1%    |
| Panasonic                            | 1         | 0.1%    |
| OEM                                  | 1         | 0.1%    |
| Micro Computer (HK) Tech Limited     | 1         | 0.1%    |
| Metabox                              | 1         | 0.1%    |
| Medion                               | 1         | 0.1%    |
| MediaVue                             | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 11        | 1.1%    |
| ASUS All Series                      | 10        | 1%      |
| Dell XPS 13 9360                     | 7         | 0.7%    |
| Gigabyte H77M-D3H                    | 6         | 0.6%    |
| HP Notebook                          | 5         | 0.5%    |
| HP EliteBook 840 G5                  | 5         | 0.5%    |
| ASUS TUF Gaming X570-PLUS            | 5         | 0.5%    |
| ASUS PRIME B450M-A                   | 5         | 0.5%    |
| Valve Jupiter                        | 4         | 0.4%    |
| MSI MS-7C95                          | 4         | 0.4%    |
| HP ProBook 6550b                     | 4         | 0.4%    |
| HP Pavilion dv6                      | 4         | 0.4%    |
| HP Pavilion 15                       | 4         | 0.4%    |
| HP EliteDesk 800 G1 SFF              | 4         | 0.4%    |
| HP EliteBook 850 G5                  | 4         | 0.4%    |
| HP Compaq 8200 Elite SFF PC          | 4         | 0.4%    |
| Toshiba Satellite L750               | 3         | 0.3%    |
| MSI MS-7C02                          | 3         | 0.3%    |
| MSI MS-7B89                          | 3         | 0.3%    |
| HP ProBook 4540s                     | 3         | 0.3%    |
| HP Pavilion Laptop 15-cw1xxx         | 3         | 0.3%    |
| HP EliteBook 8560p                   | 3         | 0.3%    |
| Gigabyte X670 AORUS ELITE AX         | 3         | 0.3%    |
| Gigabyte B75M-D3H                    | 3         | 0.3%    |
| Gigabyte B550M DS3H AC               | 3         | 0.3%    |
| Gigabyte B450M S2H                   | 3         | 0.3%    |
| Gigabyte 970A-D3P                    | 3         | 0.3%    |
| Dell XPS 15 9500                     | 3         | 0.3%    |
| Dell OptiPlex 3010                   | 3         | 0.3%    |
| Dell Latitude E6430                  | 3         | 0.3%    |
| Dell Latitude 7490                   | 3         | 0.3%    |
| ASUS P8B75-M                         | 3         | 0.3%    |
| ASUS ASUS EXPERTBOOK P2451FA_P2451FA | 3         | 0.3%    |
| ASRock B450M Steel Legend            | 3         | 0.3%    |
| ASRock 970 Pro3 R2.0                 | 3         | 0.3%    |
| Apple MacBookPro11,3                 | 3         | 0.3%    |
| Acer Swift SF314-41                  | 3         | 0.3%    |
| Acer Aspire F5-573G                  | 3         | 0.3%    |
| Toshiba TECRA Z50-A                  | 2         | 0.2%    |
| Toshiba Satellite L850               | 2         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 57        | 5.71%   |
| HP EliteBook       | 41        | 4.1%    |
| ASUS ROG           | 36        | 3.6%    |
| HP ProBook         | 31        | 3.1%    |
| Acer Aspire        | 31        | 3.1%    |
| HP Pavilion        | 26        | 2.6%    |
| Dell Latitude      | 25        | 2.5%    |
| HP Compaq          | 23        | 2.3%    |
| Dell OptiPlex      | 21        | 2.1%    |
| ASUS PRIME         | 21        | 2.1%    |
| Toshiba Satellite  | 18        | 1.8%    |
| Dell XPS           | 17        | 1.7%    |
| Dell Inspiron      | 16        | 1.6%    |
| ASUS TUF           | 15        | 1.5%    |
| Dell Precision     | 12        | 1.2%    |
| ASUS VivoBook      | 12        | 1.2%    |
| Lenovo ThinkCentre | 11        | 1.1%    |
| HP EliteDesk       | 11        | 1.1%    |
| Unknown            | 11        | 1.1%    |
| ASUS ASUS          | 10        | 1%      |
| ASUS All           | 10        | 1%      |
| HP ZBook           | 9         | 0.9%    |
| HP Laptop          | 9         | 0.9%    |
| Lenovo Yoga        | 7         | 0.7%    |
| HP ProLiant        | 7         | 0.7%    |
| HP ENVY            | 7         | 0.7%    |
| HP Spectre         | 6         | 0.6%    |
| Gigabyte H77M-D3H  | 6         | 0.6%    |
| RPi Raspberry      | 5         | 0.5%    |
| Lenovo IdeaPad     | 5         | 0.5%    |
| HP ProDesk         | 5         | 0.5%    |
| HP Notebook        | 5         | 0.5%    |
| Gigabyte B550M     | 5         | 0.5%    |
| Gigabyte B550      | 5         | 0.5%    |
| Acer TravelMate    | 5         | 0.5%    |
| Valve Jupiter      | 4         | 0.4%    |
| Toshiba PORTEGE    | 4         | 0.4%    |
| MSI MS-7C95        | 4         | 0.4%    |
| Gigabyte Z690      | 4         | 0.4%    |
| Dell PowerEdge     | 4         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 116       | 11.61%  |
| 2018    | 93        | 9.31%   |
| 2020    | 80        | 8.01%   |
| 2019    | 79        | 7.91%   |
| 2011    | 76        | 7.61%   |
| 2021    | 63        | 6.31%   |
| 2017    | 61        | 6.11%   |
| 2013    | 59        | 5.91%   |
| 2014    | 56        | 5.61%   |
| 2022    | 54        | 5.41%   |
| 2016    | 46        | 4.6%    |
| 2010    | 45        | 4.5%    |
| 2015    | 43        | 4.3%    |
| 2023    | 36        | 3.6%    |
| 2009    | 33        | 3.3%    |
| 2008    | 29        | 2.9%    |
| 2007    | 10        | 1%      |
| 2024    | 7         | 0.7%    |
| Unknown | 7         | 0.7%    |
| 2005    | 3         | 0.3%    |
| 2006    | 2         | 0.2%    |
| 2004    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 483       | 48.35%  |
| Desktop        | 410       | 41.04%  |
| Mini pc        | 34        | 3.4%    |
| Convertible    | 29        | 2.9%    |
| All in one     | 18        | 1.8%    |
| Server         | 14        | 1.4%    |
| System on chip | 6         | 0.6%    |
| Tablet         | 5         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 924       | 91.58%  |
| Enabled  | 85        | 8.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 986       | 98.7%   |
| Yes  | 13        | 1.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 223       | 21.78%  |
| 4.01-8.0        | 221       | 21.58%  |
| 8.01-16.0       | 188       | 18.36%  |
| 32.01-64.0      | 145       | 14.16%  |
| 3.01-4.0        | 141       | 13.77%  |
| 64.01-256.0     | 47        | 4.59%   |
| 24.01-32.0      | 28        | 2.73%   |
| 1.01-2.0        | 19        | 1.86%   |
| 2.01-3.0        | 6         | 0.59%   |
| 0.51-1.0        | 4         | 0.39%   |
| More than 256.0 | 1         | 0.1%    |
| 0.01-0.5        | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 335       | 29.41%  |
| 2.01-3.0   | 302       | 26.51%  |
| 4.01-8.0   | 194       | 17.03%  |
| 3.01-4.0   | 158       | 13.87%  |
| 8.01-16.0  | 63        | 5.53%   |
| 0.51-1.0   | 56        | 4.92%   |
| 16.01-24.0 | 15        | 1.32%   |
| 0.01-0.5   | 10        | 0.88%   |
| 24.01-32.0 | 4         | 0.35%   |
| 32.01-64.0 | 2         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 590       | 56.41%  |
| 2       | 254       | 24.28%  |
| 3       | 98        | 9.37%   |
| 4       | 55        | 5.26%   |
| 5       | 16        | 1.53%   |
| 6       | 15        | 1.43%   |
| 0       | 6         | 0.57%   |
| 7       | 5         | 0.48%   |
| 8       | 2         | 0.19%   |
| Unknown | 2         | 0.19%   |
| 410     | 1         | 0.1%    |
| 20      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 640       | 63.3%   |
| Yes       | 371       | 36.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 880       | 87.56%  |
| No        | 125       | 12.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 765       | 76.04%  |
| No        | 241       | 23.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 633       | 62.55%  |
| No        | 379       | 37.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| New Zealand | 999       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Auckland         | 476       | 44.99%  |
| Wellington       | 129       | 12.19%  |
| Christchurch     | 121       | 11.44%  |
| Hamilton         | 60        | 5.67%   |
| Tauranga         | 37        | 3.5%    |
| Dunedin          | 32        | 3.02%   |
| Palmerston North | 23        | 2.17%   |
| Cambridge        | 18        | 1.7%    |
| Whangarei        | 16        | 1.51%   |
| Nelson           | 16        | 1.51%   |
| Napier City      | 15        | 1.42%   |
| Lower Hutt       | 11        | 1.04%   |
| Whanganui        | 10        | 0.95%   |
| New Plymouth     | 9         | 0.85%   |
| Invercargill     | 8         | 0.76%   |
| Hastings         | 8         | 0.76%   |
| Rotorua          | 7         | 0.66%   |
| Timaru           | 5         | 0.47%   |
| Ashburton        | 5         | 0.47%   |
| Masterton        | 3         | 0.28%   |
| Levin            | 3         | 0.28%   |
| Grafton          | 3         | 0.28%   |
| Waikanae         | 2         | 0.19%   |
| Queenstown       | 2         | 0.19%   |
| Otaki            | 2         | 0.19%   |
| Blenheim         | 2         | 0.19%   |
| Whatawhata       | 1         | 0.09%   |
| Westport         | 1         | 0.09%   |
| Wellsford        | 1         | 0.09%   |
| Waikato          | 1         | 0.09%   |
| Waihi            | 1         | 0.09%   |
| Tutukaka         | 1         | 0.09%   |
| Te Puke          | 1         | 0.09%   |
| Te Awamutu       | 1         | 0.09%   |
| Taupo            | 1         | 0.09%   |
| Stratford        | 1         | 0.09%   |
| Saint Andrews    | 1         | 0.09%   |
| Porirua          | 1         | 0.09%   |
| Paraparaumu      | 1         | 0.09%   |
| Pakuranga        | 1         | 0.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 285       | 514    | 19.09%  |
| Seagate                     | 246       | 428    | 16.48%  |
| WDC                         | 215       | 365    | 14.4%   |
| Crucial                     | 89        | 139    | 5.96%   |
| Toshiba                     | 76        | 95     | 5.09%   |
| SanDisk                     | 61        | 70     | 4.09%   |
| Kingston                    | 61        | 88     | 4.09%   |
| Intel                       | 52        | 69     | 3.48%   |
| Unknown                     | 48        | 69     | 3.22%   |
| SK hynix                    | 41        | 55     | 2.75%   |
| Hitachi                     | 30        | 41     | 2.01%   |
| Micron Technology           | 29        | 35     | 1.94%   |
| A-DATA Technology           | 23        | 29     | 1.54%   |
| HGST                        | 22        | 26     | 1.47%   |
| Micron/Crucial Technology   | 20        | 26     | 1.34%   |
| Apple                       | 13        | 14     | 0.87%   |
| Kingston Technology Company | 12        | 12     | 0.8%    |
| Team                        | 11        | 12     | 0.74%   |
| LITEON                      | 10        | 10     | 0.67%   |
| China                       | 9         | 11     | 0.6%    |
| KIOXIA                      | 8         | 11     | 0.54%   |
| Hewlett-Packard             | 8         | 12     | 0.54%   |
| Lexar                       | 7         | 13     | 0.47%   |
| ASMT                        | 7         | 8      | 0.47%   |
| OCZ                         | 6         | 7      | 0.4%    |
| KingSpec                    | 6         | 6      | 0.4%    |
| Apacer                      | 6         | 7      | 0.4%    |
| TO Exter                    | 5         | 5      | 0.33%   |
| Gigabyte Technology         | 5         | 6      | 0.33%   |
| External                    | 5         | 6      | 0.33%   |
| XPG                         | 4         | 4      | 0.27%   |
| Transcend                   | 4         | 4      | 0.27%   |
| Silicon Motion              | 4         | 6      | 0.27%   |
| Phison Electronics          | 4         | 11     | 0.27%   |
| MAXIO Technology (Hangzhou) | 4         | 6      | 0.27%   |
| JMicron Technology          | 4         | 4      | 0.27%   |
| T-FORCE                     | 3         | 3      | 0.2%    |
| Phison                      | 3         | 3      | 0.2%    |
| Netac                       | 3         | 3      | 0.2%    |
| Fujitsu                     | 3         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 26        | 1.51%   |
| Samsung SSD 860 EVO 500GB                            | 18        | 1.05%   |
| Samsung SSD 850 EVO 500GB                            | 18        | 1.05%   |
| Seagate Expansion 1TB                                | 16        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB                       | 15        | 0.87%   |
| Samsung SSD 980 1TB                                  | 15        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 14        | 0.81%   |
| Seagate Expansion Desk 5TB                           | 13        | 0.76%   |
| Crucial CT240BX500SSD1 240GB                         | 12        | 0.7%    |
| Samsung SSD 870 EVO 1TB                              | 11        | 0.64%   |
| Samsung SSD 850 EVO 250GB                            | 11        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                         | 11        | 0.64%   |
| Seagate ST500LT012-1DG142 500GB                      | 10        | 0.58%   |
| Seagate ST500DM002-1BD142 500GB                      | 10        | 0.58%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 10        | 0.58%   |
| Seagate ST31000528AS 1TB                             | 9         | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB                       | 9         | 0.52%   |
| Samsung SSD 870 EVO 500GB                            | 9         | 0.52%   |
| Samsung SSD 860 EVO 250GB                            | 9         | 0.52%   |
| Samsung NVMe SSD Drive 500GB                         | 9         | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 9         | 0.52%   |
| Seagate ST2000DM006-2DM164 2TB                       | 8         | 0.47%   |
| Seagate ST2000DM001-1CH164 2TB                       | 8         | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB                       | 8         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB                       | 8         | 0.47%   |
| Samsung NVMe SSD Drive 512GB                         | 8         | 0.47%   |
| Kingston SV300S37A240G 240GB SSD                     | 8         | 0.47%   |
| Kingston SA400S37240G 240GB SSD                      | 8         | 0.47%   |
| Crucial CT480BX500SSD1 480GB                         | 8         | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 7         | 0.41%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 7         | 0.41%   |
| Unknown MMC Card  64GB                               | 7         | 0.41%   |
| Seagate ST9500325AS 500GB                            | 7         | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 7         | 0.41%   |
| Samsung SSD 980 PRO 1TB                              | 7         | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                         | 7         | 0.41%   |
| Kingston SV300S37A120G 120GB SSD                     | 7         | 0.41%   |
| Intel NVMe SSD Drive 512GB                           | 7         | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                          | 7         | 0.41%   |
| Crucial CT1000BX500SSD1 1TB                          | 7         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 237       | 408    | 41.95%  |
| WDC                 | 186       | 304    | 32.92%  |
| Toshiba             | 40        | 53     | 7.08%   |
| Hitachi             | 30        | 41     | 5.31%   |
| HGST                | 22        | 26     | 3.89%   |
| Samsung Electronics | 7         | 9      | 1.24%   |
| Apple               | 6         | 6      | 1.06%   |
| Unknown             | 5         | 9      | 0.88%   |
| TO Exter            | 5         | 5      | 0.88%   |
| External            | 5         | 6      | 0.88%   |
| JMicron Technology  | 4         | 4      | 0.71%   |
| Hewlett-Packard     | 4         | 5      | 0.71%   |
| ASMT                | 4         | 4      | 0.71%   |
| Fujitsu             | 3         | 3      | 0.53%   |
| USB3.0              | 1         | 1      | 0.18%   |
| USB                 | 1         | 2      | 0.18%   |
| Unknown (CF)        | 1         | 1      | 0.18%   |
| StoreJet            | 1         | 1      | 0.18%   |
| QUANTUM             | 1         | 1      | 0.18%   |
| HGST HTS            | 1         | 1      | 0.18%   |
| Ext Hard            | 1         | 2      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 141       | 208    | 29.31%  |
| Crucial             | 78        | 121    | 16.22%  |
| Kingston            | 41        | 58     | 8.52%   |
| SanDisk             | 34        | 40     | 7.07%   |
| Intel               | 23        | 33     | 4.78%   |
| WDC                 | 21        | 40     | 4.37%   |
| A-DATA Technology   | 19        | 24     | 3.95%   |
| Micron Technology   | 15        | 19     | 3.12%   |
| Team                | 11        | 12     | 2.29%   |
| Toshiba             | 9         | 10     | 1.87%   |
| China               | 9         | 11     | 1.87%   |
| LITEON              | 8         | 8      | 1.66%   |
| Apple               | 7         | 8      | 1.46%   |
| Seagate             | 6         | 9      | 1.25%   |
| OCZ                 | 6         | 7      | 1.25%   |
| KingSpec            | 6         | 6      | 1.25%   |
| Apacer              | 6         | 7      | 1.25%   |
| Lexar               | 5         | 10     | 1.04%   |
| SK hynix            | 4         | 4      | 0.83%   |
| Gigabyte Technology | 4         | 4      | 0.83%   |
| Transcend           | 3         | 3      | 0.62%   |
| T-FORCE             | 3         | 3      | 0.62%   |
| Hewlett-Packard     | 3         | 6      | 0.62%   |
| Corsair             | 3         | 5      | 0.62%   |
| Netac               | 2         | 2      | 0.42%   |
| Timetec             | 1         | 1      | 0.21%   |
| PNY                 | 1         | 2      | 0.21%   |
| OWC                 | 1         | 1      | 0.21%   |
| OCZ-VERTEX3         | 1         | 1      | 0.21%   |
| OASDX               | 1         | 1      | 0.21%   |
| LITEONIT            | 1         | 3      | 0.21%   |
| Innodisk            | 1         | 1      | 0.21%   |
| GAMER               | 1         | 1      | 0.21%   |
| FreeNAS             | 1         | 36     | 0.21%   |
| FreeBSD             | 1         | 372    | 0.21%   |
| Dogfish             | 1         | 1      | 0.21%   |
| Dell                | 1         | 1      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 468       | 892    | 34.95%  |
| SSD     | 425       | 1081   | 31.74%  |
| NVMe    | 389       | 646    | 29.05%  |
| MMC     | 43        | 54     | 3.21%   |
| Unknown | 14        | 19     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 711       | 1866   | 57.95%  |
| NVMe | 389       | 643    | 31.7%   |
| SAS  | 84        | 129    | 6.85%   |
| MMC  | 43        | 54     | 3.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 528       | 1240   | 53.17%  |
| 0.51-1.0   | 281       | 442    | 28.3%   |
| 1.01-2.0   | 105       | 171    | 10.57%  |
| 3.01-4.0   | 33        | 55     | 3.32%   |
| 4.01-10.0  | 24        | 33     | 2.42%   |
| 2.01-3.0   | 16        | 19     | 1.61%   |
| 10.01-20.0 | 5         | 10     | 0.5%    |
| 20.01-50.0 | 1         | 3      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 245       | 22.83%  |
| 251-500        | 214       | 19.94%  |
| 501-1000       | 166       | 15.47%  |
| 1001-2000      | 107       | 9.97%   |
| 1-20           | 88        | 8.2%    |
| More than 3000 | 83        | 7.74%   |
| 2001-3000      | 55        | 5.13%   |
| 51-100         | 52        | 4.85%   |
| 21-50          | 32        | 2.98%   |
| Unknown        | 31        | 2.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 397       | 35.26%  |
| 21-50          | 188       | 16.7%   |
| 101-250        | 127       | 11.28%  |
| 51-100         | 121       | 10.75%  |
| 501-1000       | 84        | 7.46%   |
| 251-500        | 81        | 7.19%   |
| 1001-2000      | 45        | 4%      |
| Unknown        | 31        | 2.75%   |
| More than 3000 | 28        | 2.49%   |
| 2001-3000      | 24        | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB                    | 3         | 3      | 2.97%   |
| WDC WD7500BPKX-00HPJT0 752GB                | 2         | 2      | 1.98%   |
| WDC WD5000AAKX-001CA0 500GB                 | 2         | 3      | 1.98%   |
| WDC WD3200AAKS-00L9A0 320GB                 | 2         | 2      | 1.98%   |
| WDC WD20EZRZ-00Z5HB0 2TB                    | 2         | 2      | 1.98%   |
| WDC WD20EARX-00PASB0 2TB                    | 2         | 3      | 1.98%   |
| Seagate ST3500418AS 500GB                   | 2         | 3      | 1.98%   |
| Seagate ST31000524AS 1TB                    | 2         | 2      | 1.98%   |
| Samsung Electronics SSD 980 1TB             | 2         | 3      | 1.98%   |
| Samsung Electronics SSD 870 EVO 1TB         | 2         | 2      | 1.98%   |
| HGST HTS545050A7E380 500GB                  | 2         | 2      | 1.98%   |
| WDC WDS480G2G0A-00JH30 480GB SSD            | 1         | 1      | 0.99%   |
| WDC WD40EFAX-68JH4N0 4TB                    | 1         | 1      | 0.99%   |
| WDC WD3200AAKS-00UU3A0 320GB                | 1         | 1      | 0.99%   |
| WDC WD2003FZEX-00Z4SA0 2TB                  | 1         | 1      | 0.99%   |
| WDC WD15EARS-00S0XB0 1TB                    | 1         | 1      | 0.99%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 1      | 0.99%   |
| WDC WD10EFRX-68FYTN0 1TB                    | 1         | 3      | 0.99%   |
| WDC WD10EARS-00Y5B1 1TB                     | 1         | 1      | 0.99%   |
| WDC WD10EARS-003BB1 1TB                     | 1         | 1      | 0.99%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 2      | 0.99%   |
| USB3.0 Extemal HDD 2TB                      | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD075 752GB                    | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD050 500GB                    | 1         | 1      | 0.99%   |
| Toshiba MK5076GSX 500GB                     | 1         | 1      | 0.99%   |
| Toshiba MK5065GSXF 500GB                    | 1         | 1      | 0.99%   |
| Toshiba MK3261GSYN 320GB                    | 1         | 1      | 0.99%   |
| Toshiba MK3256GSY 320GB                     | 1         | 1      | 0.99%   |
| SK hynix SC308 SATA 128GB SSD               | 1         | 1      | 0.99%   |
| SK hynix HFS256G32MND-2900A 256GB SSD       | 1         | 1      | 0.99%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 3      | 0.99%   |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB     | 1         | 1      | 0.99%   |
| ShiJi 512GB M.2-NVMe                        | 1         | 1      | 0.99%   |
| Seagate ST9500420ASG 500GB                  | 1         | 1      | 0.99%   |
| Seagate ST9500420AS 500GB                   | 1         | 1      | 0.99%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 0.99%   |
| Seagate ST8000VN0022-2EL112 8TB             | 1         | 3      | 0.99%   |
| Seagate ST500NM0011 500GB                   | 1         | 2      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 26     | 21.88%  |
| Seagate             | 21        | 29     | 21.88%  |
| HGST                | 8         | 9      | 8.33%   |
| Toshiba             | 7         | 7      | 7.29%   |
| Samsung Electronics | 6         | 7      | 6.25%   |
| Crucial             | 6         | 7      | 6.25%   |
| Intel               | 5         | 7      | 5.21%   |
| SanDisk             | 4         | 4      | 4.17%   |
| SK hynix            | 3         | 6      | 3.13%   |
| Hitachi             | 3         | 3      | 3.13%   |
| Micron Technology   | 2         | 2      | 2.08%   |
| ASMT                | 2         | 2      | 2.08%   |
| USB3.0              | 1         | 1      | 1.04%   |
| ShiJi               | 1         | 1      | 1.04%   |
| OCZ                 | 1         | 1      | 1.04%   |
| Kingston            | 1         | 1      | 1.04%   |
| Innodisk            | 1         | 1      | 1.04%   |
| HGST HTS            | 1         | 1      | 1.04%   |
| Apple               | 1         | 1      | 1.04%   |
| A-DATA Technology   | 1         | 3      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 21        | 29     | 32.81%  |
| WDC      | 20        | 25     | 31.25%  |
| HGST     | 8         | 9      | 12.5%   |
| Toshiba  | 7         | 7      | 10.94%  |
| Hitachi  | 3         | 3      | 4.69%   |
| ASMT     | 2         | 2      | 3.13%   |
| USB3.0   | 1         | 1      | 1.56%   |
| HGST HTS | 1         | 1      | 1.56%   |
| Apple    | 1         | 1      | 1.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 78     | 65.96%  |
| SSD  | 23        | 28     | 24.47%  |
| NVMe | 9         | 13     | 9.57%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD20EARS-00S8B1 2TB         | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 606       | 1361   | 55.14%  |
| Works    | 399       | 1209   | 36.31%  |
| Malfunc  | 91        | 119    | 8.28%   |
| Failed   | 2         | 2      | 0.18%   |
| Limited  | 1         | 1      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 629       | 47.19%  |
| AMD                          | 207       | 15.53%  |
| Samsung Electronics          | 176       | 13.2%   |
| SanDisk                      | 39        | 2.93%   |
| SK hynix                     | 37        | 2.78%   |
| Kingston Technology Company  | 31        | 2.33%   |
| Micron/Crucial Technology    | 30        | 2.25%   |
| Toshiba America Info Systems | 28        | 2.1%    |
| Nvidia                       | 23        | 1.73%   |
| JMicron Technology           | 18        | 1.35%   |
| Micron Technology            | 16        | 1.2%    |
| ASMedia Technology           | 16        | 1.2%    |
| Marvell Technology Group     | 13        | 0.98%   |
| Phison Electronics           | 10        | 0.75%   |
| LSI Logic / Symbios Logic    | 7         | 0.53%   |
| KIOXIA                       | 7         | 0.53%   |
| Silicon Motion               | 6         | 0.45%   |
| Seagate Technology           | 6         | 0.45%   |
| ADATA Technology             | 6         | 0.45%   |
| Shenzhen Longsys Electronics | 4         | 0.3%    |
| MAXIO Technology (Hangzhou)  | 4         | 0.3%    |
| Hewlett-Packard              | 4         | 0.3%    |
| Broadcom / LSI               | 4         | 0.3%    |
| Realtek Semiconductor        | 2         | 0.15%   |
| O2 Micro                     | 2         | 0.15%   |
| Lite-On Technology           | 2         | 0.15%   |
| VIA Technologies             | 1         | 0.08%   |
| Union Memory (Shenzhen)      | 1         | 0.08%   |
| Solidigm                     | 1         | 0.08%   |
| Silicon Image                | 1         | 0.08%   |
| OCZ Technology Group         | 1         | 0.08%   |
| Netac Technology             | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 120       | 7.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 76        | 4.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 46        | 3%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 44        | 2.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 39        | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 39        | 2.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 37        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 34        | 2.22%   |
| AMD 400 Series Chipset SATA Controller                                           | 30        | 1.96%   |
| AMD 500 Series Chipset SATA Controller                                           | 26        | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 25        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 24        | 1.57%   |
| Intel SATA Controller [RAID mode]                                                | 23        | 1.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 23        | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 22        | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                              | 22        | 1.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 22        | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 21        | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                            | 20        | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 19        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 17        | 1.11%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 16        | 1.04%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 15        | 0.98%   |
| AMD 600 Series Chipset SATA Controller                                           | 15        | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 14        | 0.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 13        | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 12        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 0.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 0.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 11        | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 10        | 0.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 0.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 10        | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 10        | 0.65%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 9         | 0.59%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 9         | 0.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 9         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 727       | 54.54%  |
| NVMe | 392       | 29.41%  |
| IDE  | 122       | 9.15%   |
| RAID | 85        | 6.38%   |
| SAS  | 5         | 0.38%   |
| SCSI | 2         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 734       | 73.47%  |
| AMD      | 258       | 25.83%  |
| ARM      | 6         | 0.6%    |
| QUALCOMM | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 12        | 1.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 11        | 1.1%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 1%      |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.9%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 0.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 7         | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 6         | 0.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.6%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 6         | 0.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 6         | 0.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz              | 5         | 0.5%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 5         | 0.5%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.5%    |
| Intel Core i5-4570 CPU @ 3.20GHz              | 5         | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.5%    |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 5         | 0.5%    |
| Intel Core i3-3227U CPU @ 1.90GHz             | 5         | 0.5%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 5         | 0.5%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 0.5%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 5         | 0.5%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 5         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 237       | 23.72%  |
| Intel Core i7           | 215       | 21.52%  |
| Other                   | 79        | 7.91%   |
| AMD Ryzen 5             | 56        | 5.61%   |
| Intel Core i3           | 52        | 5.21%   |
| AMD Ryzen 7             | 50        | 5.01%   |
| Intel Core 2 Duo        | 40        | 4%      |
| Intel Celeron           | 34        | 3.4%    |
| Intel Xeon              | 33        | 3.3%    |
| AMD Ryzen 9             | 29        | 2.9%    |
| AMD FX                  | 19        | 1.9%    |
| Intel Pentium           | 15        | 1.5%    |
| AMD A6                  | 12        | 1.2%    |
| Intel Core 2 Quad       | 11        | 1.1%    |
| Intel Atom              | 10        | 1%      |
| AMD Ryzen 5 PRO         | 10        | 1%      |
| AMD A8                  | 9         | 0.9%    |
| AMD Ryzen 3             | 8         | 0.8%    |
| Intel Core i9           | 7         | 0.7%    |
| AMD A4                  | 7         | 0.7%    |
| AMD Ryzen Threadripper  | 5         | 0.5%    |
| AMD E2                  | 5         | 0.5%    |
| AMD Athlon II X2        | 5         | 0.5%    |
| AMD Athlon 64 X2        | 5         | 0.5%    |
| Intel Pentium Dual-Core | 3         | 0.3%    |
| AMD Ryzen 7 PRO         | 3         | 0.3%    |
| AMD Phenom II X6        | 3         | 0.3%    |
| Intel Pentium Silver    | 2         | 0.2%    |
| Intel Pentium M         | 2         | 0.2%    |
| Intel Core              | 2         | 0.2%    |
| AMD Phenom II X4        | 2         | 0.2%    |
| AMD Opteron             | 2         | 0.2%    |
| AMD G                   | 2         | 0.2%    |
| AMD E1                  | 2         | 0.2%    |
| AMD E                   | 2         | 0.2%    |
| AMD Athlon II X4        | 2         | 0.2%    |
| AMD A12                 | 2         | 0.2%    |
| AMD A10                 | 2         | 0.2%    |
| QUALCOMM AArch64        | 1         | 0.1%    |
| Intel Xeon Silver       | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 374       | 37.33%  |
| 2      | 323       | 32.24%  |
| 6      | 115       | 11.48%  |
| 8      | 86        | 8.58%   |
| 12     | 35        | 3.49%   |
| 10     | 14        | 1.4%    |
| 16     | 13        | 1.3%    |
| 1      | 12        | 1.2%    |
| 14     | 11        | 1.1%    |
| 24     | 6         | 0.6%    |
| 20     | 6         | 0.6%    |
| 3      | 6         | 0.6%    |
| 64     | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 984       | 98.5%   |
| 2      | 14        | 1.4%    |
| 3      | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 698       | 69.66%  |
| 1      | 303       | 30.24%  |
| 8      | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 984       | 97.72%  |
| Unknown        | 19        | 1.89%   |
| 32-bit         | 4         | 0.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 441       | 42.08%  |
| 0x306a9    | 52        | 4.96%   |
| 0x206a7    | 49        | 4.68%   |
| 0x306c3    | 30        | 2.86%   |
| 0x1067a    | 25        | 2.39%   |
| 0x806ea    | 19        | 1.81%   |
| 0x806e9    | 18        | 1.72%   |
| 0x806ec    | 17        | 1.62%   |
| 0x406e3    | 17        | 1.62%   |
| 0x906e9    | 15        | 1.43%   |
| 0x08701021 | 15        | 1.43%   |
| 0x40651    | 12        | 1.15%   |
| 0x20655    | 12        | 1.15%   |
| 0x506e3    | 11        | 1.05%   |
| 0x06000852 | 10        | 0.95%   |
| 0xa0652    | 9         | 0.86%   |
| 0x906ea    | 9         | 0.86%   |
| 0x30678    | 9         | 0.86%   |
| 0x106e5    | 9         | 0.86%   |
| 0x0a50000d | 9         | 0.86%   |
| 0x0a50000c | 9         | 0.86%   |
| 0x07030105 | 9         | 0.86%   |
| 0x10676    | 8         | 0.76%   |
| 0x0800820d | 8         | 0.76%   |
| 0x506c9    | 7         | 0.67%   |
| 0x306d4    | 7         | 0.67%   |
| 0x08108109 | 7         | 0.67%   |
| 0xa0655    | 6         | 0.57%   |
| 0x906a4    | 6         | 0.57%   |
| 0x806c1    | 6         | 0.57%   |
| 0x0a601203 | 6         | 0.57%   |
| 0x06001119 | 6         | 0.57%   |
| 0x906a3    | 5         | 0.48%   |
| 0x806eb    | 5         | 0.48%   |
| 0x6fb      | 5         | 0.48%   |
| 0x106a5    | 5         | 0.48%   |
| 0x08600106 | 5         | 0.48%   |
| 0x08001137 | 5         | 0.48%   |
| 0x906ed    | 4         | 0.38%   |
| 0x6fd      | 4         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 156       | 15.58%  |
| IvyBridge         | 85        | 8.49%   |
| Haswell           | 83        | 8.29%   |
| SandyBridge       | 80        | 7.99%   |
| Unknown           | 67        | 6.69%   |
| Skylake           | 48        | 4.8%    |
| Penryn            | 48        | 4.8%    |
| Zen 3             | 46        | 4.6%    |
| Zen 2             | 41        | 4.1%    |
| CometLake         | 35        | 3.5%    |
| Zen+              | 28        | 2.8%    |
| Silvermont        | 27        | 2.7%    |
| Alderlake Hybrid  | 27        | 2.7%    |
| Westmere          | 24        | 2.4%    |
| Piledriver        | 24        | 2.4%    |
| Nehalem           | 19        | 1.9%    |
| Zen               | 15        | 1.5%    |
| K10               | 15        | 1.5%    |
| TigerLake         | 14        | 1.4%    |
| Puma              | 14        | 1.4%    |
| Excavator         | 14        | 1.4%    |
| Core              | 13        | 1.3%    |
| Broadwell         | 13        | 1.3%    |
| IceLake           | 11        | 1.1%    |
| Goldmont          | 9         | 0.9%    |
| K8 Hammer         | 6         | 0.6%    |
| Jaguar            | 6         | 0.6%    |
| Goldmont plus     | 6         | 0.6%    |
| Bulldozer         | 5         | 0.5%    |
| Bonnell           | 5         | 0.5%    |
| Bobcat            | 5         | 0.5%    |
| Tremont           | 3         | 0.3%    |
| P6                | 2         | 0.2%    |
| Meteorlake Hybrid | 2         | 0.2%    |
| NetBurst          | 1         | 0.1%    |
| K8 & K10 hybrid   | 1         | 0.1%    |
| K10 Llano         | 1         | 0.1%    |
| Gracemont         | 1         | 0.1%    |
| Geode             | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 541       | 46.04%  |
| Nvidia                     | 313       | 26.64%  |
| AMD                        | 303       | 25.79%  |
| Matrox Electronics Systems | 13        | 1.11%   |
| ASPEED Technology          | 5         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 57        | 4.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 3.19%   |
| Intel UHD Graphics 620                                                                   | 28        | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 22        | 1.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 22        | 1.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 1.72%   |
| Intel HD Graphics 620                                                                    | 21        | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 1.63%   |
| Intel HD Graphics 630                                                                    | 19        | 1.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.23%   |
| Intel HD Graphics 530                                                                    | 14        | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13        | 1.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 0.98%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 0.98%   |
| AMD Raphael                                                                              | 12        | 0.98%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.9%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 11        | 0.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 0.82%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 10        | 0.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.74%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 9         | 0.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 0.74%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 8         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 0.65%   |
| Intel HD Graphics 5500                                                                   | 8         | 0.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.65%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 8         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.57%   |
| Intel HD Graphics 500                                                                    | 7         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 387       | 38.39%  |
| 1 x AMD                 | 217       | 21.53%  |
| 1 x Nvidia              | 181       | 17.96%  |
| Intel + Nvidia          | 101       | 10.02%  |
| Intel + AMD             | 37        | 3.67%   |
| 2 x AMD                 | 30        | 2.98%   |
| AMD + Nvidia            | 19        | 1.88%   |
| 1 x Matrox              | 11        | 1.09%   |
| Other                   | 9         | 0.89%   |
| 2 x Nvidia              | 6         | 0.6%    |
| 2 x Intel               | 2         | 0.2%    |
| Nvidia + ASPEED         | 2         | 0.2%    |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.1%    |
| Nvidia + Matrox         | 1         | 0.1%    |
| 1 x ASPEED              | 1         | 0.1%    |
| AMD + 2 x Nvidia        | 1         | 0.1%    |
| AMD + Matrox            | 1         | 0.1%    |
| AMD + ASPEED            | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 795       | 78.25%  |
| Proprietary | 179       | 17.62%  |
| Unknown     | 42        | 4.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 620       | 59.85%  |
| 0.01-0.5   | 94        | 9.07%   |
| 1.01-2.0   | 93        | 8.98%   |
| 0.51-1.0   | 67        | 6.47%   |
| 3.01-4.0   | 58        | 5.6%    |
| 7.01-8.0   | 47        | 4.54%   |
| 5.01-6.0   | 25        | 2.41%   |
| 8.01-16.0  | 23        | 2.22%   |
| 2.01-3.0   | 6         | 0.58%   |
| 16.01-24.0 | 2         | 0.19%   |
| 32.01-64.0 | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 149       | 12.91%  |
| AU Optronics            | 105       | 9.1%    |
| Dell                    | 92        | 7.97%   |
| LG Display              | 84        | 7.28%   |
| Goldstar                | 82        | 7.11%   |
| Chimei Innolux          | 79        | 6.85%   |
| AOC                     | 78        | 6.76%   |
| BOE                     | 67        | 5.81%   |
| Philips                 | 47        | 4.07%   |
| Hewlett-Packard         | 38        | 3.29%   |
| ViewSonic               | 33        | 2.86%   |
| Apple                   | 24        | 2.08%   |
| Sharp                   | 20        | 1.73%   |
| Lenovo                  | 20        | 1.73%   |
| Chi Mei Optoelectronics | 19        | 1.65%   |
| Acer                    | 19        | 1.65%   |
| Sony                    | 18        | 1.56%   |
| Panasonic               | 18        | 1.56%   |
| BenQ                    | 16        | 1.39%   |
| Ancor Communications    | 13        | 1.13%   |
| Denver                  | 12        | 1.04%   |
| PANDA                   | 10        | 0.87%   |
| MiTAC                   | 10        | 0.87%   |
| InfoVision              | 9         | 0.78%   |
| Gigabyte Technology     | 7         | 0.61%   |
| ASUSTek Computer        | 7         | 0.61%   |
| Valve                   | 4         | 0.35%   |
| LG Electronics          | 4         | 0.35%   |
| Unknown                 | 3         | 0.26%   |
| TMX                     | 3         | 0.26%   |
| MSI                     | 3         | 0.26%   |
| InnoLux Display         | 3         | 0.26%   |
| Unknown                 | 3         | 0.26%   |
| Yamaha                  | 2         | 0.17%   |
| Unknown (AAA)           | 2         | 0.17%   |
| Toshiba                 | 2         | 0.17%   |
| SANYO                   | 2         | 0.17%   |
| Quanta Display          | 2         | 0.17%   |
| PRISM+                  | 2         | 0.17%   |
| Mi                      | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.73%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                       | 8         | 0.65%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 7         | 0.57%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 0.57%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                       | 7         | 0.57%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 6         | 0.49%   |
| MiTAC MStar Demo SZM0030 3840x2160 708x398mm 32.0-inch                   | 6         | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 6         | 0.49%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 5         | 0.41%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 5         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.41%   |
| ViewSonic VA2248 SERIES VSC0E28 1920x1080 477x268mm 21.5-inch            | 4         | 0.33%   |
| Sony TV SNYEE01 1920x1080                                                | 4         | 0.33%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 4         | 0.33%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                  | 4         | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.33%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                   | 4         | 0.33%   |
| Denver UWQHD-100-C LHC3400 3440x1440 795x334mm 33.9-inch                 | 4         | 0.33%   |
| Denver M27-QHD-144-C LHC2700 2560x1440 597x336mm 27.0-inch               | 4         | 0.33%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                        | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 0.33%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                         | 4         | 0.33%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 4         | 0.33%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.24%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 3         | 0.24%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch        | 3         | 0.24%   |
| Samsung Electronics LS27AG32x SAM71DC 1920x1080 597x336mm 27.0-inch      | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.24%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 3         | 0.24%   |
| LG Display LCD Monitor LGD056E 1920x1080 344x194mm 15.5-inch             | 3         | 0.24%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 3         | 0.24%   |
| Hewlett-Packard P221 HWP3057 1920x1080 476x268mm 21.5-inch               | 3         | 0.24%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 3         | 0.24%   |
| Dell P2416D DELA0C3 2560x1440 527x296mm 23.8-inch                        | 3         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 3         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 466       | 41.98%  |
| 1366x768 (WXGA)    | 146       | 13.15%  |
| 3840x2160 (4K)     | 123       | 11.08%  |
| 2560x1440 (QHD)    | 59        | 5.32%   |
| 1600x900 (HD+)     | 44        | 3.96%   |
| 1680x1050 (WSXGA+) | 39        | 3.51%   |
| 1280x1024 (SXGA)   | 30        | 2.7%    |
| 1440x900 (WXGA+)   | 28        | 2.52%   |
| 1920x1200 (WUXGA)  | 27        | 2.43%   |
| 3440x1440          | 24        | 2.16%   |
| 1280x800 (WXGA)    | 21        | 1.89%   |
| Unknown            | 16        | 1.44%   |
| 3840x1080          | 10        | 0.9%    |
| 2880x1800          | 8         | 0.72%   |
| 2560x1600          | 7         | 0.63%   |
| 2560x1080          | 6         | 0.54%   |
| 1360x768           | 6         | 0.54%   |
| 3200x1800 (QHD+)   | 5         | 0.45%   |
| 800x1280           | 4         | 0.36%   |
| 1920x540           | 4         | 0.36%   |
| 1024x600           | 4         | 0.36%   |
| 3840x1600          | 3         | 0.27%   |
| 3456x2160          | 3         | 0.27%   |
| 1600x1200          | 3         | 0.27%   |
| 3840x2400          | 2         | 0.18%   |
| 3200x2000          | 2         | 0.18%   |
| 2880x1920          | 2         | 0.18%   |
| 2288x1287          | 2         | 0.18%   |
| 1024x768 (XGA)     | 2         | 0.18%   |
| 7680x1080          | 1         | 0.09%   |
| 6720x1080          | 1         | 0.09%   |
| 5760x1080          | 1         | 0.09%   |
| 5120x1080          | 1         | 0.09%   |
| 3840x1200          | 1         | 0.09%   |
| 3360x1080          | 1         | 0.09%   |
| 3040x1050          | 1         | 0.09%   |
| 2960x1050          | 1         | 0.09%   |
| 2800x1752          | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |
| 2560x1024          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 225       | 19.45%  |
| 27      | 109       | 9.42%   |
| 13      | 90        | 7.78%   |
| 14      | 86        | 7.43%   |
| 23      | 84        | 7.26%   |
| 24      | 82        | 7.09%   |
| 21      | 73        | 6.31%   |
| 17      | 58        | 5.01%   |
| 31      | 53        | 4.58%   |
| Unknown | 48        | 4.15%   |
| 22      | 30        | 2.59%   |
| 19      | 28        | 2.42%   |
| 20      | 21        | 1.82%   |
| 34      | 19        | 1.64%   |
| 84      | 16        | 1.38%   |
| 72      | 14        | 1.21%   |
| 16      | 13        | 1.12%   |
| 12      | 12        | 1.04%   |
| 18      | 10        | 0.86%   |
| 32      | 9         | 0.78%   |
| 11      | 9         | 0.78%   |
| 40      | 6         | 0.52%   |
| 10      | 6         | 0.52%   |
| 46      | 5         | 0.43%   |
| 35      | 5         | 0.43%   |
| 7       | 5         | 0.43%   |
| 52      | 4         | 0.35%   |
| 37      | 4         | 0.35%   |
| 26      | 4         | 0.35%   |
| 29      | 3         | 0.26%   |
| 28      | 3         | 0.26%   |
| 142     | 2         | 0.17%   |
| 54      | 2         | 0.17%   |
| 36      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |
| 25      | 2         | 0.17%   |
| 95      | 1         | 0.09%   |
| 67      | 1         | 0.09%   |
| 65      | 1         | 0.09%   |
| 64      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 378       | 33.42%  |
| 501-600        | 246       | 21.75%  |
| 401-500        | 147       | 13%     |
| 601-700        | 78        | 6.9%    |
| 201-300        | 70        | 6.19%   |
| 351-400        | 60        | 5.31%   |
| Unknown        | 48        | 4.24%   |
| 701-800        | 33        | 2.92%   |
| 1501-2000      | 28        | 2.48%   |
| 801-900        | 17        | 1.5%    |
| 1001-1500      | 17        | 1.5%    |
| 1-100          | 4         | 0.35%   |
| More than 2000 | 2         | 0.18%   |
| 901-1000       | 2         | 0.18%   |
| 101-200        | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 742       | 73.83%  |
| 16/10   | 139       | 13.83%  |
| Unknown | 40        | 3.98%   |
| 21/9    | 29        | 2.89%   |
| 5/4     | 28        | 2.79%   |
| 4/3     | 7         | 0.7%    |
| 3/2     | 6         | 0.6%    |
| 32/9    | 5         | 0.5%    |
| 0.67    | 3         | 0.3%    |
| 6/5     | 2         | 0.2%    |
| 1.00    | 2         | 0.2%    |
| 0.62    | 1         | 0.1%    |
| 0.45    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 222       | 19.54%  |
| 201-250        | 219       | 19.28%  |
| 81-90          | 140       | 12.32%  |
| 301-350        | 111       | 9.77%   |
| 351-500        | 94        | 8.27%   |
| 151-200        | 68        | 5.99%   |
| Unknown        | 48        | 4.23%   |
| 121-130        | 40        | 3.52%   |
| More than 1000 | 39        | 3.43%   |
| 71-80          | 36        | 3.17%   |
| 251-300        | 25        | 2.2%    |
| 501-1000       | 23        | 2.02%   |
| 141-150        | 22        | 1.94%   |
| 111-120        | 13        | 1.14%   |
| 61-70          | 11        | 0.97%   |
| 51-60          | 9         | 0.79%   |
| 41-50          | 6         | 0.53%   |
| 1-40           | 5         | 0.44%   |
| 131-140        | 4         | 0.35%   |
| 91-100         | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 381       | 34.29%  |
| 101-120       | 276       | 24.84%  |
| 121-160       | 270       | 24.3%   |
| 161-240       | 71        | 6.39%   |
| Unknown       | 48        | 4.32%   |
| 1-50          | 36        | 3.24%   |
| More than 240 | 29        | 2.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 762       | 73.13%  |
| 2     | 205       | 19.67%  |
| 0     | 43        | 4.13%   |
| 3     | 27        | 2.59%   |
| 4     | 4         | 0.38%   |
| 5     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 548       | 35.38%  |
| Realtek Semiconductor           | 510       | 32.92%  |
| Qualcomm Atheros                | 127       | 8.2%    |
| Broadcom                        | 85        | 5.49%   |
| MediaTek                        | 42        | 2.71%   |
| TP-Link                         | 29        | 1.87%   |
| Ralink                          | 21        | 1.36%   |
| Nvidia                          | 18        | 1.16%   |
| Broadcom Limited                | 17        | 1.1%    |
| Ralink Technology               | 15        | 0.97%   |
| Marvell Technology Group        | 12        | 0.77%   |
| Hewlett-Packard                 | 8         | 0.52%   |
| ASIX Electronics                | 8         | 0.52%   |
| NetGear                         | 7         | 0.45%   |
| Microsoft                       | 7         | 0.45%   |
| Aquantia                        | 7         | 0.45%   |
| Samsung Electronics             | 6         | 0.39%   |
| OPPO Electronics                | 6         | 0.39%   |
| DisplayLink                     | 6         | 0.39%   |
| Qualcomm Atheros Communications | 5         | 0.32%   |
| Sierra Wireless                 | 4         | 0.26%   |
| Qualcomm                        | 3         | 0.19%   |
| Microchip Technology            | 3         | 0.19%   |
| Lenovo                          | 3         | 0.19%   |
| IBM                             | 3         | 0.19%   |
| Edimax Technology               | 3         | 0.19%   |
| Dell                            | 3         | 0.19%   |
| D-Link                          | 3         | 0.19%   |
| U-Blox                          | 2         | 0.13%   |
| QinHeng Electronics             | 2         | 0.13%   |
| Mellanox Technologies           | 2         | 0.13%   |
| MCS                             | 2         | 0.13%   |
| JMicron Technology              | 2         | 0.13%   |
| ASUSTek Computer                | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.06%   |
| Xiaomi                          | 1         | 0.06%   |
| Wilocity                        | 1         | 0.06%   |
| Wacom                           | 1         | 0.06%   |
| vivo                            | 1         | 0.06%   |
| VIA Technologies                | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 340       | 18.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 55        | 3.03%   |
| Intel Wi-Fi 6 AX200                                                    | 50        | 2.75%   |
| Realtek RTL8125 2.5GbE Controller                                      | 45        | 2.48%   |
| Intel Wireless 8265 / 8275                                             | 44        | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 35        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 31        | 1.71%   |
| Intel I211 Gigabit Network Connection                                  | 25        | 1.38%   |
| Intel Wireless 8260                                                    | 23        | 1.27%   |
| Intel Wireless 7260                                                    | 21        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 18        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 18        | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 17        | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 17        | 0.94%   |
| Intel Wireless 7265                                                    | 16        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 0.83%   |
| Intel Wireless 3165                                                    | 15        | 0.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 15        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 15        | 0.83%   |
| Intel Ethernet Controller I225-V                                       | 14        | 0.77%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 14        | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 14        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 13        | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                   | 12        | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                   | 12        | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 12        | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 11        | 0.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 11        | 0.61%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                         | 11        | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 10        | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 10        | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 399       | 49.02%  |
| Qualcomm Atheros                      | 101       | 12.41%  |
| Realtek Semiconductor                 | 96        | 11.79%  |
| Broadcom                              | 57        | 7%      |
| MediaTek                              | 33        | 4.05%   |
| TP-Link                               | 28        | 3.44%   |
| Ralink                                | 21        | 2.58%   |
| Ralink Technology                     | 15        | 1.84%   |
| Broadcom Limited                      | 15        | 1.84%   |
| NetGear                               | 7         | 0.86%   |
| Microsoft                             | 6         | 0.74%   |
| Qualcomm Atheros Communications       | 5         | 0.61%   |
| Sierra Wireless                       | 4         | 0.49%   |
| Qualcomm                              | 3         | 0.37%   |
| Hewlett-Packard                       | 3         | 0.37%   |
| Edimax Technology                     | 3         | 0.37%   |
| Dell                                  | 3         | 0.37%   |
| D-Link                                | 3         | 0.37%   |
| ASUSTek Computer                      | 2         | 0.25%   |
| Wilocity                              | 1         | 0.12%   |
| Wacom                                 | 1         | 0.12%   |
| Samsung Electronics                   | 1         | 0.12%   |
| Realtek                               | 1         | 0.12%   |
| Qualcomm Technologies                 | 1         | 0.12%   |
| Marvell Technology Group              | 1         | 0.12%   |
| Lite-On Technology                    | 1         | 0.12%   |
| Fibocom                               | 1         | 0.12%   |
| Belkin Components                     | 1         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 50        | 6.08%   |
| Intel Wireless 8265 / 8275                                     | 44        | 5.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 31        | 3.77%   |
| Intel Wireless 8260                                            | 23        | 2.8%    |
| Intel Wireless 7260                                            | 21        | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18        | 2.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 2.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 17        | 2.07%   |
| Intel Wireless 7265                                            | 16        | 1.95%   |
| Intel Wireless 3165                                            | 15        | 1.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 15        | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 14        | 1.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 14        | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 1.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 13        | 1.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 1.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12        | 1.46%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 11        | 1.34%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 1.34%   |
| Intel Centrino Ultimate-N 6300                                 | 11        | 1.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 10        | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 9         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 1.09%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 8         | 0.97%   |
| Intel Centrino Advanced-N 6200                                 | 8         | 0.97%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 8         | 0.97%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 7         | 0.85%   |
| Intel Centrino Wireless-N 2230                                 | 7         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 0.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6         | 0.73%   |
| Intel Wireless 3160                                            | 6         | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 468       | 49.37%  |
| Intel                      | 305       | 32.17%  |
| Qualcomm Atheros           | 42        | 4.43%   |
| Broadcom                   | 41        | 4.32%   |
| Nvidia                     | 18        | 1.9%    |
| Marvell Technology Group   | 11        | 1.16%   |
| MediaTek                   | 8         | 0.84%   |
| ASIX Electronics           | 8         | 0.84%   |
| Aquantia                   | 7         | 0.74%   |
| OPPO Electronics           | 6         | 0.63%   |
| DisplayLink                | 6         | 0.63%   |
| Samsung Electronics        | 3         | 0.32%   |
| Lenovo                     | 3         | 0.32%   |
| IBM                        | 3         | 0.32%   |
| JMicron Technology         | 2         | 0.21%   |
| Broadcom Limited           | 2         | 0.21%   |
| ZTE WCDMA Technologies MSM | 1         | 0.11%   |
| Xiaomi                     | 1         | 0.11%   |
| vivo                       | 1         | 0.11%   |
| VIA Technologies           | 1         | 0.11%   |
| TP-Link                    | 1         | 0.11%   |
| QinHeng Electronics        | 1         | 0.11%   |
| Microsoft                  | 1         | 0.11%   |
| Microchip Technology       | 1         | 0.11%   |
| Mellanox Technologies      | 1         | 0.11%   |
| Insyde Software            | 1         | 0.11%   |
| ICS Advent                 | 1         | 0.11%   |
| Huawei Technologies        | 1         | 0.11%   |
| Attansic Technology        | 1         | 0.11%   |
| Apple                      | 1         | 0.11%   |
| 3Com                       | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 340       | 35.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 55        | 5.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 45        | 4.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 38        | 3.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 35        | 3.62%   |
| Intel I211 Gigabit Network Connection                                  | 25        | 2.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 1.55%   |
| Intel Ethernet Controller I225-V                                       | 14        | 1.45%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                   | 12        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                                   | 12        | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 1.03%   |
| Nvidia MCP79 Ethernet                                                  | 9         | 0.93%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.93%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.93%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 9         | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                   | 8         | 0.83%   |
| Intel I210 Gigabit Network Connection                                  | 7         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 7         | 0.72%   |
| Intel Ethernet Connection (2) I218-V                                   | 7         | 0.72%   |
| Intel 82574L Gigabit Network Connection                                | 7         | 0.72%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.62%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 6         | 0.62%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 5         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 5         | 0.52%   |
| Intel Ethernet Connection (10) I219-V                                  | 5         | 0.52%   |
| Intel 82577LC Gigabit Network Connection                               | 5         | 0.52%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 4         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.41%   |
| OPPO OnePlus Nord 4                                                    | 4         | 0.41%   |
| Nvidia MCP61 Ethernet                                                  | 4         | 0.41%   |
| Intel Ethernet Controller I226-V                                       | 4         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 878       | 52.57%  |
| WiFi     | 765       | 45.81%  |
| Modem    | 24        | 1.44%   |
| Unknown  | 3         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 570       | 53.67%  |
| Ethernet | 491       | 46.23%  |
| Modem    | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 551       | 54.88%  |
| 1     | 398       | 39.64%  |
| 3     | 36        | 3.59%   |
| 0     | 11        | 1.1%    |
| 4     | 5         | 0.5%    |
| 6     | 2         | 0.2%    |
| 8     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 838       | 81.68%  |
| Yes  | 188       | 18.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 336       | 52.26%  |
| Qualcomm Atheros Communications | 40        | 6.22%   |
| Broadcom                        | 34        | 5.29%   |
| Cambridge Silicon Radio         | 33        | 5.13%   |
| Realtek Semiconductor           | 31        | 4.82%   |
| IMC Networks                    | 28        | 4.35%   |
| Apple                           | 28        | 4.35%   |
| Foxconn / Hon Hai               | 23        | 3.58%   |
| Lite-On Technology              | 21        | 3.27%   |
| Hewlett-Packard                 | 16        | 2.49%   |
| MediaTek                        | 10        | 1.56%   |
| ASUSTek Computer                | 10        | 1.56%   |
| Toshiba                         | 6         | 0.93%   |
| Edimax Technology               | 5         | 0.78%   |
| Ralink                          | 4         | 0.62%   |
| Dell                            | 4         | 0.62%   |
| Ralink Technology               | 3         | 0.47%   |
| TP-Link                         | 2         | 0.31%   |
| Realtek                         | 2         | 0.31%   |
| Alps Electric                   | 2         | 0.31%   |
| USI                             | 1         | 0.16%   |
| Marvell Semiconductor           | 1         | 0.16%   |
| Integrated System Solution      | 1         | 0.16%   |
| HTC (High Tech Computer)        | 1         | 0.16%   |
| Creative Technology             | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 121       | 18.73%  |
| Intel AX201 Bluetooth                               | 51        | 7.89%   |
| Intel AX200 Bluetooth                               | 46        | 7.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 36        | 5.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 33        | 5.11%   |
| Intel AX211 Bluetooth                               | 23        | 3.56%   |
| Realtek Bluetooth Radio                             | 18        | 2.79%   |
| IMC Networks Wireless_Device                        | 16        | 2.48%   |
| Apple Bluetooth Host Controller                     | 16        | 2.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 2.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 2.32%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 2.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 13        | 2.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.86%   |
| Intel AX210 Bluetooth                               | 12        | 1.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 1.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.55%   |
| MediaTek Wireless_Device                            | 10        | 1.55%   |
| IMC Networks Bluetooth Radio                        | 10        | 1.55%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.55%   |
| Lite-On Bluetooth Device                            | 8         | 1.24%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.77%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.77%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.62%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.62%   |
| Edimax Bluetooth Adapter                            | 4         | 0.62%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.62%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.62%   |
| Broadcom BCM20702A0                                 | 4         | 0.62%   |
| Foxconn / Hon Hai Acer Module                       | 3         | 0.46%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.46%   |
| ASUS Bluetooth Radio                                | 3         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 699       | 48.01%  |
| AMD                                          | 327       | 22.46%  |
| Nvidia                                       | 253       | 17.38%  |
| Logitech                                     | 23        | 1.58%   |
| C-Media Electronics                          | 22        | 1.51%   |
| Hewlett-Packard                              | 11        | 0.76%   |
| SteelSeries ApS                              | 8         | 0.55%   |
| Realtek Semiconductor                        | 7         | 0.48%   |
| Plantronics                                  | 6         | 0.41%   |
| Kingston Technology                          | 6         | 0.41%   |
| Generalplus Technology                       | 6         | 0.41%   |
| Lenovo                                       | 5         | 0.34%   |
| JMTek                                        | 5         | 0.34%   |
| Razer USA                                    | 4         | 0.27%   |
| GN Netcom                                    | 4         | 0.27%   |
| FiiO Electronics Technology                  | 4         | 0.27%   |
| Dell                                         | 4         | 0.27%   |
| Microsoft                                    | 3         | 0.21%   |
| GYROCOM C&C                                  | 3         | 0.21%   |
| Creative Technology                          | 3         | 0.21%   |
| ASUSTek Computer                             | 3         | 0.21%   |
| XMOS                                         | 2         | 0.14%   |
| Texas Instruments                            | 2         | 0.14%   |
| Micro Star International                     | 2         | 0.14%   |
| Focusrite-Novation                           | 2         | 0.14%   |
| Creative Labs                                | 2         | 0.14%   |
| Audio-Technica                               | 2         | 0.14%   |
| AKAI Professional M.I.                       | 2         | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.07%   |
| VIA Technologies                             | 1         | 0.07%   |
| Trust International                          | 1         | 0.07%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.07%   |
| Tenx Technology                              | 1         | 0.07%   |
| Sony                                         | 1         | 0.07%   |
| Sennheiser Communications                    | 1         | 0.07%   |
| Samson Technologies                          | 1         | 0.07%   |
| RODE Microphones                             | 1         | 0.07%   |
| RME                                          | 1         | 0.07%   |
| Numark                                       | 1         | 0.07%   |
| Nordic Semiconductor ASA                     | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 84        | 4.87%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 83        | 4.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 78        | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 69        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                   | 49        | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 44        | 2.55%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 42        | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 36        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 1.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 32        | 1.86%   |
| AMD FCH Azalia Controller                                                  | 32        | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 30        | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28        | 1.62%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 28        | 1.62%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 25        | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 24        | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 22        | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                   | 22        | 1.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22        | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 21        | 1.22%   |
| Intel Comet Lake PCH cAVS                                                  | 21        | 1.22%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 21        | 1.22%   |
| Intel 8 Series HD Audio Controller                                         | 21        | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 18        | 1.04%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 16        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16        | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                              | 16        | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 0.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 14        | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14        | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 14        | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 13        | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 12        | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12        | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                              | 12        | 0.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 0.7%    |
| Intel Broadwell-U Audio Controller                                         | 12        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 134       | 21.65%  |
| SK hynix            | 118       | 19.06%  |
| Micron Technology   | 66        | 10.66%  |
| Kingston            | 65        | 10.5%   |
| Crucial             | 50        | 8.08%   |
| G.Skill             | 45        | 7.27%   |
| Unknown             | 34        | 5.49%   |
| A-DATA Technology   | 22        | 3.55%   |
| Corsair             | 20        | 3.23%   |
| Team                | 12        | 1.94%   |
| Elpida              | 8         | 1.29%   |
| Transcend           | 6         | 0.97%   |
| Strontium           | 6         | 0.97%   |
| Ramaxel Technology  | 5         | 0.81%   |
| Hewlett-Packard     | 4         | 0.65%   |
| Unknown (ABCD)      | 2         | 0.32%   |
| Shenzhen Mic        | 2         | 0.32%   |
| PNY                 | 2         | 0.32%   |
| Neo Forza           | 2         | 0.32%   |
| Nanya Technology    | 2         | 0.32%   |
| Apacer              | 2         | 0.32%   |
| Unknown (D386)      | 1         | 0.16%   |
| Unknown (0x8783)    | 1         | 0.16%   |
| Unknown (0x0080)    | 1         | 0.16%   |
| Super Talent        | 1         | 0.16%   |
| pqi                 | 1         | 0.16%   |
| OCZ                 | 1         | 0.16%   |
| Netac               | 1         | 0.16%   |
| Innodisk            | 1         | 0.16%   |
| Hyundai lnc         | 1         | 0.16%   |
| fef5                | 1         | 0.16%   |
| Atermiter           | 1         | 0.16%   |
| Unknown             | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 9         | 1.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 7         | 1.07%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 6         | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 6         | 0.91%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s   | 5         | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 5         | 0.76%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 4         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 4         | 0.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 4         | 0.61%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 4         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 4         | 0.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 4         | 0.61%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 0.61%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s     | 4         | 0.61%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s    | 4         | 0.61%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s       | 3         | 0.46%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s             | 3         | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 3         | 0.46%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s              | 3         | 0.46%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s    | 3         | 0.46%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s    | 3         | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 3         | 0.46%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 3         | 0.46%   |
| G.Skill RAM F4-2666C15-8GVR 8GB DIMM DDR4 2800MT/s        | 3         | 0.46%   |
| G.Skill RAM F3-1600C9-4GAB 4GB DIMM DDR3 1600MT/s         | 3         | 0.46%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s   | 3         | 0.46%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s  | 3         | 0.46%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                      | 2         | 0.3%    |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 2         | 0.3%    |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2         | 0.3%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 2         | 0.3%    |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s     | 2         | 0.3%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 2         | 0.3%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s              | 2         | 0.3%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 2         | 0.3%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s              | 2         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 240       | 46.33%  |
| DDR3    | 177       | 34.17%  |
| DDR5    | 25        | 4.83%   |
| DDR2    | 15        | 2.9%    |
| LPDDR3  | 14        | 2.7%    |
| SDRAM   | 13        | 2.51%   |
| Unknown | 13        | 2.51%   |
| LPDDR5  | 10        | 1.93%   |
| LPDDR4  | 10        | 1.93%   |
| DDR     | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 289       | 56.01%  |
| DIMM         | 186       | 36.05%  |
| Row Of Chips | 31        | 6.01%   |
| Unknown      | 5         | 0.97%   |
| Chip         | 4         | 0.78%   |
| FB-DIMM      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 203       | 36.64%  |
| 4096  | 144       | 25.99%  |
| 16384 | 115       | 20.76%  |
| 2048  | 54        | 9.75%   |
| 32768 | 31        | 5.6%    |
| 1024  | 6         | 1.08%   |
| 65536 | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 125       | 22.12%  |
| 3200    | 87        | 15.4%   |
| 2667    | 57        | 10.09%  |
| 2400    | 40        | 7.08%   |
| 1333    | 33        | 5.84%   |
| 2133    | 24        | 4.25%   |
| 3600    | 22        | 3.89%   |
| 1334    | 20        | 3.54%   |
| 1867    | 16        | 2.83%   |
| 4800    | 14        | 2.48%   |
| 1067    | 11        | 1.95%   |
| 800     | 10        | 1.77%   |
| 3733    | 9         | 1.59%   |
| 6400    | 8         | 1.42%   |
| 667     | 8         | 1.42%   |
| 3800    | 7         | 1.24%   |
| Unknown | 6         | 1.06%   |
| 8400    | 4         | 0.71%   |
| 6000    | 4         | 0.71%   |
| 5600    | 4         | 0.71%   |
| 4267    | 4         | 0.71%   |
| 3866    | 4         | 0.71%   |
| 2800    | 4         | 0.71%   |
| 2666    | 4         | 0.71%   |
| 7500    | 3         | 0.53%   |
| 4199    | 3         | 0.53%   |
| 3466    | 3         | 0.53%   |
| 2048    | 3         | 0.53%   |
| 1866    | 3         | 0.53%   |
| 1800    | 3         | 0.53%   |
| 1066    | 3         | 0.53%   |
| 12800   | 2         | 0.35%   |
| 3400    | 2         | 0.35%   |
| 3000    | 2         | 0.35%   |
| 975     | 2         | 0.35%   |
| 7467    | 1         | 0.18%   |
| 3534    | 1         | 0.18%   |
| 3266    | 1         | 0.18%   |
| 3151    | 1         | 0.18%   |
| 2933    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 32.14%  |
| Brother Industries  | 9         | 32.14%  |
| Canon               | 5         | 17.86%  |
| Sato                | 1         | 3.57%   |
| Samsung Electronics | 1         | 3.57%   |
| Prolific Technology | 1         | 3.57%   |
| Fuji Xerox          | 1         | 3.57%   |
| Dymo-CoStar         | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| HP Officejet 4630 series         | 2         | 7.14%   |
| Brother Printer                  | 2         | 7.14%   |
| Sato WS408 SBPL                  | 1         | 3.57%   |
| Samsung SCX-4100 Scanner         | 1         | 3.57%   |
| Prolific PL2305 Parallel Port    | 1         | 3.57%   |
| HP OfficeJet Pro 9010 series     | 1         | 3.57%   |
| HP OfficeJet 8010 series         | 1         | 3.57%   |
| HP LaserJet Professional P1102w  | 1         | 3.57%   |
| HP ENVY 6400 series              | 1         | 3.57%   |
| HP ENVY 4520 series              | 1         | 3.57%   |
| HP DeskJet 2300 series           | 1         | 3.57%   |
| HP DeskJet 2130 series           | 1         | 3.57%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 3.57%   |
| Dymo-CoStar LabelWriter 450      | 1         | 3.57%   |
| Canon TS3100 series              | 1         | 3.57%   |
| Canon MB5300 series              | 1         | 3.57%   |
| Canon LBP6000                    | 1         | 3.57%   |
| Canon i950                       | 1         | 3.57%   |
| Canon G3010 series               | 1         | 3.57%   |
| Brother MFC-J430W                | 1         | 3.57%   |
| Brother MFC-9140CDN              | 1         | 3.57%   |
| Brother MFC-9120CN               | 1         | 3.57%   |
| Brother MFC-7340                 | 1         | 3.57%   |
| Brother HL-L3230CDW series       | 1         | 3.57%   |
| Brother HL-2270DW Laser Printer  | 1         | 3.57%   |
| Brother HL-1430 Laser Printer    | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 5         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110            | 2         | 40%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan LiDE 500F           | 1         | 20%     |
| Canon CanoScan LIDE 25             | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 143       | 24.87%  |
| Logitech                               | 55        | 9.57%   |
| IMC Networks                           | 42        | 7.3%    |
| Realtek Semiconductor                  | 39        | 6.78%   |
| Microdia                               | 37        | 6.43%   |
| Sunplus Innovation Technology          | 33        | 5.74%   |
| Quanta                                 | 31        | 5.39%   |
| Apple                                  | 24        | 4.17%   |
| Bison Electronics                      | 22        | 3.83%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.13%   |
| Lite-On Technology                     | 16        | 2.78%   |
| Luxvisions Innotech Limited            | 13        | 2.26%   |
| Suyin                                  | 12        | 2.09%   |
| Samsung Electronics                    | 10        | 1.74%   |
| Syntek                                 | 9         | 1.57%   |
| Acer                                   | 6         | 1.04%   |
| Sonix Technology                       | 5         | 0.87%   |
| Silicon Motion                         | 4         | 0.7%    |
| Ricoh                                  | 4         | 0.7%    |
| Primax Electronics                     | 4         | 0.7%    |
| Microsoft                              | 4         | 0.7%    |
| GEMBIRD                                | 4         | 0.7%    |
| Alcor Micro                            | 4         | 0.7%    |
| Z-Star Microelectronics                | 3         | 0.52%   |
| ARC International                      | 3         | 0.52%   |
| ShineTech                              | 2         | 0.35%   |
| Lenovo                                 | 2         | 0.35%   |
| KYE Systems (Mouse Systems)            | 2         | 0.35%   |
| Importek                               | 2         | 0.35%   |
| ALi                                    | 2         | 0.35%   |
| Yealink Network Technology             | 1         | 0.17%   |
| Xiongmai                               | 1         | 0.17%   |
| XHT-220428-ZW                          | 1         | 0.17%   |
| ValueHD                                | 1         | 0.17%   |
| UltraSemi                              | 1         | 0.17%   |
| SunplusIT                              | 1         | 0.17%   |
| Speed Tech                             | 1         | 0.17%   |
| OPPO Electronics                       | 1         | 0.17%   |
| Novatek Microelectronics               | 1         | 0.17%   |
| MacroSilicon                           | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 25        | 4.32%   |
| IMC Networks USB2.0 HD UVC WebCam             | 19        | 3.28%   |
| Chicony HP HD Camera                          | 18        | 3.11%   |
| Realtek Integrated_Webcam_HD                  | 14        | 2.42%   |
| IMC Networks Integrated Camera                | 14        | 2.42%   |
| Chicony HD WebCam                             | 13        | 2.25%   |
| Logitech HD Pro Webcam C920                   | 11        | 1.9%    |
| Samsung Galaxy series, misc. (MTP mode)       | 10        | 1.73%   |
| Microdia Integrated_Webcam_HD                 | 10        | 1.73%   |
| Logitech Webcam C270                          | 10        | 1.73%   |
| Apple Built-in iSight                         | 9         | 1.55%   |
| Chicony TOSHIBA Web Camera - HD               | 8         | 1.38%   |
| Chicony HP HD Webcam                          | 8         | 1.38%   |
| Sunplus Integrated_Webcam_HD                  | 7         | 1.21%   |
| Sunplus HP HD Webcam [Fixed]                  | 7         | 1.21%   |
| Microdia Integrated Webcam HD                 | 7         | 1.21%   |
| Bison Integrated Camera                       | 7         | 1.21%   |
| Realtek HP Truevision HD                      | 6         | 1.04%   |
| Quanta HP HD Camera                           | 6         | 1.04%   |
| Logitech Webcam C170                          | 6         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 6         | 1.04%   |
| Syntek Integrated Camera                      | 5         | 0.86%   |
| Chicony VGA WebCam                            | 5         | 0.86%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 5         | 0.86%   |
| Apple FaceTime HD Camera (Built-in)           | 5         | 0.86%   |
| Sunplus HD WebCam                             | 4         | 0.69%   |
| Sonix USB2.0 HD UVC WebCam                    | 4         | 0.69%   |
| Quanta HP TrueVision HD Camera                | 4         | 0.69%   |
| Quanta HD User Facing                         | 4         | 0.69%   |
| Luxvisions Innotech Limited HP HD Camera      | 4         | 0.69%   |
| Lite-On Integrated Camera                     | 4         | 0.69%   |
| Chicony HP Wide Vision HD Camera              | 4         | 0.69%   |
| Chicony HP Truevision HD                      | 4         | 0.69%   |
| Bison HD Webcam                               | 4         | 0.69%   |
| Realtek Integrated Webcam HD                  | 3         | 0.52%   |
| Quanta Laptop_Integrated_Webcam_2HDM          | 3         | 0.52%   |
| Microsoft LifeCam HD-3000                     | 3         | 0.52%   |
| Luxvisions Innotech Limited HP 5MP Camera     | 3         | 0.52%   |
| Logitech QuickCam Pro 9000                    | 3         | 0.52%   |
| Logitech Logitech Webcam C925e                | 3         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 71        | 47.97%  |
| Synaptics                  | 46        | 31.08%  |
| Shenzhen Goodix Technology | 8         | 5.41%   |
| AuthenTec                  | 8         | 5.41%   |
| Upek                       | 6         | 4.05%   |
| Elan Microelectronics      | 6         | 4.05%   |
| LighTuning Technology      | 2         | 1.35%   |
| STMicroelectronics         | 1         | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 9.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 8.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 7.43%   |
| Validity Sensors VFS491                                                    | 8         | 5.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 4.73%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 4.73%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 4.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 4.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.05%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 4.05%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.38%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 3.38%   |
| Synaptics UWP WBDI                                                         | 4         | 2.7%    |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 2.7%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 2.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.03%   |
| Synaptics WBDI                                                             | 3         | 2.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.03%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.03%   |
| Elan WBF Fingerprint Sensor                                                | 3         | 2.03%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 2.03%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 1.35%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.35%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.35%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.68%   |
| Synaptics  WBDI                                                            | 1         | 0.68%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.68%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.68%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.68%   |
| AuthenTec AES2810                                                          | 1         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.68%   |
| AuthenTec AES1600                                                          | 1         | 0.68%   |
| Unknown                                                                    | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 68.97%  |
| Alcor Micro | 4         | 13.79%  |
| Lenovo      | 3         | 10.34%  |
| Upek        | 1         | 3.45%   |
| O2 Micro    | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 27.59%  |
| Broadcom 58200                                                               | 6         | 20.69%  |
| Broadcom 5880                                                                | 4         | 13.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 13.79%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 693       | 66.89%  |
| 1     | 281       | 27.12%  |
| 2     | 52        | 5.02%   |
| 3     | 5         | 0.48%   |
| 6     | 2         | 0.19%   |
| 5     | 2         | 0.19%   |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 146       | 36.14%  |
| Graphics card            | 79        | 19.55%  |
| Net/wireless             | 60        | 14.85%  |
| Chipcard                 | 28        | 6.93%   |
| Multimedia controller    | 24        | 5.94%   |
| Communication controller | 10        | 2.48%   |
| Camera                   | 10        | 2.48%   |
| Bluetooth                | 9         | 2.23%   |
| Unassigned class         | 6         | 1.49%   |
| Sound                    | 6         | 1.49%   |
| Storage                  | 4         | 0.99%   |
| Network                  | 4         | 0.99%   |
| Net/ethernet             | 4         | 0.99%   |
| Modem                    | 3         | 0.74%   |
| Dvb card                 | 3         | 0.74%   |
| Storage/ide              | 2         | 0.5%    |
| Firewire controller      | 2         | 0.5%    |
| Card reader              | 2         | 0.5%    |
| Storage/raid             | 1         | 0.25%   |
| Flash memory             | 1         | 0.25%   |

