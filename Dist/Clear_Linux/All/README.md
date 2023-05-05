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

Total: 1369

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| MSI           | Z370 GAMING PLUS            | Desktop     | [b3ae454f4d](https://linux-hardware.org/?probe=b3ae454f4d) | Jun 07, 2020 |
| Lenovo        | ThinkPad W520 4284V21       | Notebook    | [6c0368dfeb](https://linux-hardware.org/?probe=6c0368dfeb) | Jun 03, 2020 |
| Lenovo        | ThinkPad W520 4284V21       | Notebook    | [3c335f539d](https://linux-hardware.org/?probe=3c335f539d) | Jun 03, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | Desktop     | [0bd408c7b1](https://linux-hardware.org/?probe=0bd408c7b1) | Jun 03, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [51258219c2](https://linux-hardware.org/?probe=51258219c2) | Jun 03, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [52d3f1eccd](https://linux-hardware.org/?probe=52d3f1eccd) | Jun 03, 2020 |
| ASUSTek       | X550VX                      | Notebook    | [a651714cc1](https://linux-hardware.org/?probe=a651714cc1) | Jun 03, 2020 |
| Sony          | SVF14N25CXB                 | Notebook    | [2fdd1fc4d3](https://linux-hardware.org/?probe=2fdd1fc4d3) | Jun 02, 2020 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [4d40264618](https://linux-hardware.org/?probe=4d40264618) | Jun 01, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [5d042bc26a](https://linux-hardware.org/?probe=5d042bc26a) | May 31, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [5c70b2f02d](https://linux-hardware.org/?probe=5c70b2f02d) | May 31, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [99de8c34ef](https://linux-hardware.org/?probe=99de8c34ef) | May 29, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [3b6f1169ca](https://linux-hardware.org/?probe=3b6f1169ca) | May 29, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [fcb77c0b07](https://linux-hardware.org/?probe=fcb77c0b07) | May 29, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [e814c4f10a](https://linux-hardware.org/?probe=e814c4f10a) | May 28, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2c62f7166b](https://linux-hardware.org/?probe=2c62f7166b) | May 28, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3a6891795b](https://linux-hardware.org/?probe=3a6891795b) | May 28, 2020 |
| Lenovo        | ThinkPad W550s 20E1S0L50... | Notebook    | [f4657ce6c7](https://linux-hardware.org/?probe=f4657ce6c7) | May 27, 2020 |
| ASUSTek       | UX390UAK                    | Notebook    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [429d0e0895](https://linux-hardware.org/?probe=429d0e0895) | May 25, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [a83a3c451a](https://linux-hardware.org/?probe=a83a3c451a) | May 25, 2020 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [5c77a503d6](https://linux-hardware.org/?probe=5c77a503d6) | May 25, 2020 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [579d40537e](https://linux-hardware.org/?probe=579d40537e) | May 25, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [2732c1d769](https://linux-hardware.org/?probe=2732c1d769) | May 22, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [4fb4f4b3c3](https://linux-hardware.org/?probe=4fb4f4b3c3) | May 21, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [3da0141f0b](https://linux-hardware.org/?probe=3da0141f0b) | May 20, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [db8887bb7a](https://linux-hardware.org/?probe=db8887bb7a) | May 13, 2020 |
| Intel         | X79 V2.4E                   | Desktop     | [c95d31e867](https://linux-hardware.org/?probe=c95d31e867) | May 12, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [de237bc9f1](https://linux-hardware.org/?probe=de237bc9f1) | May 12, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [e5966e4342](https://linux-hardware.org/?probe=e5966e4342) | May 12, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [11c9e11a07](https://linux-hardware.org/?probe=11c9e11a07) | May 09, 2020 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [f5152b2ec1](https://linux-hardware.org/?probe=f5152b2ec1) | May 07, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| Toshiba       | Satellite P50-C             | Notebook    | [c8bdff05b8](https://linux-hardware.org/?probe=c8bdff05b8) | May 07, 2020 |
| Toshiba       | Satellite P50-C             | Notebook    | [477e156d9b](https://linux-hardware.org/?probe=477e156d9b) | May 07, 2020 |
| Toshiba       | Satellite P50-C             | Notebook    | [84d5d6098e](https://linux-hardware.org/?probe=84d5d6098e) | May 07, 2020 |
| HP            | 84EF 00100                  | All in one  | [6917c1729b](https://linux-hardware.org/?probe=6917c1729b) | May 06, 2020 |
| HP            | ProLiant DL360e Gen8        | Server      | [0de2cd5337](https://linux-hardware.org/?probe=0de2cd5337) | May 06, 2020 |
| HP            | ProLiant DL360e Gen8        | Server      | [aa3029d253](https://linux-hardware.org/?probe=aa3029d253) | May 06, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [0297320c60](https://linux-hardware.org/?probe=0297320c60) | May 06, 2020 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [9ef1c24681](https://linux-hardware.org/?probe=9ef1c24681) | May 06, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [4b9f8bab81](https://linux-hardware.org/?probe=4b9f8bab81) | May 05, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [58254b6315](https://linux-hardware.org/?probe=58254b6315) | May 05, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [902e3ec116](https://linux-hardware.org/?probe=902e3ec116) | May 05, 2020 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [1bce8d72b4](https://linux-hardware.org/?probe=1bce8d72b4) | May 04, 2020 |
| Hampoo        | I1D6_C189A                  | Tablet      | [4ac6dd88aa](https://linux-hardware.org/?probe=4ac6dd88aa) | May 04, 2020 |
| Alienware     | M14xR2                      | Notebook    | [737a2771cd](https://linux-hardware.org/?probe=737a2771cd) | May 04, 2020 |
| HP            | 15 Notebook PC              | Notebook    | [a3a2e124bf](https://linux-hardware.org/?probe=a3a2e124bf) | May 04, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [48e17c097d](https://linux-hardware.org/?probe=48e17c097d) | May 03, 2020 |
| HP            | EliteBook 2540p             | Notebook    | [8758004d49](https://linux-hardware.org/?probe=8758004d49) | May 03, 2020 |
| ASUSTek       | P8P67 LE                    | Desktop     | [2701a098f7](https://linux-hardware.org/?probe=2701a098f7) | May 02, 2020 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [17a22f880b](https://linux-hardware.org/?probe=17a22f880b) | May 02, 2020 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [862fddb03f](https://linux-hardware.org/?probe=862fddb03f) | May 02, 2020 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [f2de5c3a83](https://linux-hardware.org/?probe=f2de5c3a83) | May 02, 2020 |
| HP            | 0AECh D                     | Desktop     | [a1b7a080a8](https://linux-hardware.org/?probe=a1b7a080a8) | May 02, 2020 |
| HP            | 0AECh D                     | Desktop     | [80d5a1434e](https://linux-hardware.org/?probe=80d5a1434e) | May 01, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [37cb5d2749](https://linux-hardware.org/?probe=37cb5d2749) | May 01, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [6939bb943e](https://linux-hardware.org/?probe=6939bb943e) | May 01, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [d11ba9afbf](https://linux-hardware.org/?probe=d11ba9afbf) | Apr 30, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [20f69deb0d](https://linux-hardware.org/?probe=20f69deb0d) | Apr 30, 2020 |
| Sony          | SVP132190X                  | Notebook    | [7bfb045386](https://linux-hardware.org/?probe=7bfb045386) | Apr 30, 2020 |
| Sony          | SVP132190X                  | Notebook    | [ea803349ac](https://linux-hardware.org/?probe=ea803349ac) | Apr 30, 2020 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [66b75d7bff](https://linux-hardware.org/?probe=66b75d7bff) | Apr 28, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [25ca6c8b7f](https://linux-hardware.org/?probe=25ca6c8b7f) | Apr 28, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [4c47863388](https://linux-hardware.org/?probe=4c47863388) | Apr 28, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [7dfa763f99](https://linux-hardware.org/?probe=7dfa763f99) | Apr 28, 2020 |
| Samsung       | 270E5G/270E5U               | Notebook    | [845ed80d48](https://linux-hardware.org/?probe=845ed80d48) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [2d4ce1513b](https://linux-hardware.org/?probe=2d4ce1513b) | Apr 25, 2020 |
| ASUSTek       | UX360CAK                    | Convertible | [905bc0c0bc](https://linux-hardware.org/?probe=905bc0c0bc) | Apr 23, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [45dfee483e](https://linux-hardware.org/?probe=45dfee483e) | Apr 22, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [685d0ad4e2](https://linux-hardware.org/?probe=685d0ad4e2) | Apr 22, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ad2959d25b](https://linux-hardware.org/?probe=ad2959d25b) | Apr 20, 2020 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [1ba348dd3d](https://linux-hardware.org/?probe=1ba348dd3d) | Apr 18, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [48248ea6f6](https://linux-hardware.org/?probe=48248ea6f6) | Apr 17, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [261bb9de80](https://linux-hardware.org/?probe=261bb9de80) | Apr 16, 2020 |
| HP            | 15 Notebook PC              | Notebook    | [3a8175d360](https://linux-hardware.org/?probe=3a8175d360) | Apr 16, 2020 |
| HP            | 15 Notebook PC              | Notebook    | [0712cec075](https://linux-hardware.org/?probe=0712cec075) | Apr 16, 2020 |
| Dell          | 0Y5DDC A00                  | Desktop     | [a607ebd7d9](https://linux-hardware.org/?probe=a607ebd7d9) | Apr 15, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [cf98b2c860](https://linux-hardware.org/?probe=cf98b2c860) | Apr 13, 2020 |
| HP            | 8459                        | Desktop     | [c241c2fa75](https://linux-hardware.org/?probe=c241c2fa75) | Apr 13, 2020 |
| Dell          | Precision M4500             | Notebook    | [919212e67c](https://linux-hardware.org/?probe=919212e67c) | Apr 13, 2020 |
| Acer          | Aspire A314-31              | Notebook    | [3f2fcfaa0f](https://linux-hardware.org/?probe=3f2fcfaa0f) | Apr 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5a14f08bcc](https://linux-hardware.org/?probe=5a14f08bcc) | Apr 09, 2020 |
| Microsoft     | Surface Pro 2               | Tablet      | [279f85d33d](https://linux-hardware.org/?probe=279f85d33d) | Apr 09, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [cb3baf1d22](https://linux-hardware.org/?probe=cb3baf1d22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [bc59639878](https://linux-hardware.org/?probe=bc59639878) | Apr 07, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [6943c28c65](https://linux-hardware.org/?probe=6943c28c65) | Apr 07, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [ad5a70ea5b](https://linux-hardware.org/?probe=ad5a70ea5b) | Apr 07, 2020 |
| Kanji         | KJ-HANA                     | Notebook    | [a9135d6bb0](https://linux-hardware.org/?probe=a9135d6bb0) | Apr 07, 2020 |
| Kanji         | KJ-HANA                     | Notebook    | [a207a4c9bc](https://linux-hardware.org/?probe=a207a4c9bc) | Apr 07, 2020 |
| Kanji         | KJ-HANA                     | Notebook    | [e400ea0d44](https://linux-hardware.org/?probe=e400ea0d44) | Apr 07, 2020 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [de0d4452e5](https://linux-hardware.org/?probe=de0d4452e5) | Apr 06, 2020 |
| ASRock        | Q1900M                      | Desktop     | [11c1c6b498](https://linux-hardware.org/?probe=11c1c6b498) | Apr 06, 2020 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [1013dc1d5f](https://linux-hardware.org/?probe=1013dc1d5f) | Apr 06, 2020 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [3c115dc0b0](https://linux-hardware.org/?probe=3c115dc0b0) | Apr 06, 2020 |
| Toshiba       | Satellite L55-C             | Notebook    | [c6f3bbf3dd](https://linux-hardware.org/?probe=c6f3bbf3dd) | Apr 06, 2020 |
| HP            | Notebook                    | Notebook    | [a104da67d3](https://linux-hardware.org/?probe=a104da67d3) | Apr 05, 2020 |
| Acer          | Spin SP513-51               | Convertible | [383e8ce104](https://linux-hardware.org/?probe=383e8ce104) | Apr 04, 2020 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [47f06299cb](https://linux-hardware.org/?probe=47f06299cb) | Apr 04, 2020 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [03662c05b2](https://linux-hardware.org/?probe=03662c05b2) | Apr 04, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [1986440abc](https://linux-hardware.org/?probe=1986440abc) | Apr 03, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [b10c1bd149](https://linux-hardware.org/?probe=b10c1bd149) | Apr 03, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [e7703e79d9](https://linux-hardware.org/?probe=e7703e79d9) | Mar 31, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [0dbe97d54b](https://linux-hardware.org/?probe=0dbe97d54b) | Mar 30, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [cc3bde6b84](https://linux-hardware.org/?probe=cc3bde6b84) | Mar 30, 2020 |
| Microsoft     | Surface Pro 3               | Tablet      | [5502c0f704](https://linux-hardware.org/?probe=5502c0f704) | Mar 29, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [15fe758593](https://linux-hardware.org/?probe=15fe758593) | Mar 29, 2020 |
| AXIOO         | Mybook Lite                 | Notebook    | [0ec3e1d33f](https://linux-hardware.org/?probe=0ec3e1d33f) | Mar 28, 2020 |
| AXIOO         | Mybook Lite                 | Notebook    | [539bf6ca99](https://linux-hardware.org/?probe=539bf6ca99) | Mar 28, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [982599d139](https://linux-hardware.org/?probe=982599d139) | Mar 27, 2020 |
| Acer          | Aspire S7-391               | Notebook    | [6456153797](https://linux-hardware.org/?probe=6456153797) | Mar 27, 2020 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [a0dc23c790](https://linux-hardware.org/?probe=a0dc23c790) | Mar 26, 2020 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | Notebook    | [7dbae378fe](https://linux-hardware.org/?probe=7dbae378fe) | Mar 26, 2020 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [581217af06](https://linux-hardware.org/?probe=581217af06) | Mar 26, 2020 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e9424adfcc](https://linux-hardware.org/?probe=e9424adfcc) | Mar 26, 2020 |
| Lenovo        | ThinkPad X250 20CM0048US    | Notebook    | [62c976c563](https://linux-hardware.org/?probe=62c976c563) | Mar 25, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [edd441d5a3](https://linux-hardware.org/?probe=edd441d5a3) | Mar 25, 2020 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [1fd7bb6bcc](https://linux-hardware.org/?probe=1fd7bb6bcc) | Mar 24, 2020 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [7449a84a25](https://linux-hardware.org/?probe=7449a84a25) | Mar 24, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [0b821be62a](https://linux-hardware.org/?probe=0b821be62a) | Mar 23, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f08c6424b7](https://linux-hardware.org/?probe=f08c6424b7) | Mar 22, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [9fe1bc84d4](https://linux-hardware.org/?probe=9fe1bc84d4) | Mar 22, 2020 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [b5cbaaf3b1](https://linux-hardware.org/?probe=b5cbaaf3b1) | Mar 20, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f2eec9742e](https://linux-hardware.org/?probe=f2eec9742e) | Mar 20, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | Notebook    | [92148d6858](https://linux-hardware.org/?probe=92148d6858) | Mar 19, 2020 |

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
| Clear Linux 36010 | 33        | 3.41%   |
| Clear Linux 35000 | 29        | 3%      |
| Clear Linux 32480 | 19        | 1.96%   |
| Clear Linux 34930 | 15        | 1.55%   |
| Clear Linux 32270 | 15        | 1.55%   |
| Clear Linux 32760 | 13        | 1.34%   |
| Clear Linux 34820 | 12        | 1.24%   |
| Clear Linux 33590 | 12        | 1.24%   |
| Clear Linux 32380 | 11        | 1.14%   |
| Clear Linux 34860 | 10        | 1.03%   |
| Clear Linux 32330 | 10        | 1.03%   |
| Clear Linux 34500 | 9         | 0.93%   |
| Clear Linux 33010 | 9         | 0.93%   |
| Clear Linux 35110 | 8         | 0.83%   |
| Clear Linux 33660 | 8         | 0.83%   |
| Clear Linux 32910 | 8         | 0.83%   |
| Clear Linux 34290 | 7         | 0.72%   |
| Clear Linux 37000 | 6         | 0.62%   |
| Clear Linux 36250 | 6         | 0.62%   |
| Clear Linux 36070 | 6         | 0.62%   |
| Clear Linux 34700 | 6         | 0.62%   |
| Clear Linux 34670 | 6         | 0.62%   |
| Clear Linux 34350 | 6         | 0.62%   |
| Clear Linux 34250 | 6         | 0.62%   |
| Clear Linux 33980 | 6         | 0.62%   |
| Clear Linux 33460 | 6         | 0.62%   |
| Clear Linux 33440 | 6         | 0.62%   |
| Clear Linux 32600 | 6         | 0.62%   |
| Clear Linux 32390 | 6         | 0.62%   |
| Clear Linux       | 6         | 0.62%   |
| Clear Linux 38280 | 5         | 0.52%   |
| Clear Linux 36640 | 5         | 0.52%   |
| Clear Linux 35550 | 5         | 0.52%   |
| Clear Linux 35470 | 5         | 0.52%   |
| Clear Linux 35250 | 5         | 0.52%   |
| Clear Linux 35090 | 5         | 0.52%   |
| Clear Linux 34640 | 5         | 0.52%   |
| Clear Linux 34560 | 5         | 0.52%   |
| Clear Linux 34150 | 5         | 0.52%   |
| Clear Linux 34130 | 5         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Clear Linux | 837       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.16.13-1132.native | 55        | 5.75%   |
| 5.13.13-1070.native | 49        | 5.12%   |
| 5.10.19-1032.native | 30        | 3.13%   |
| 5.5.6-914.native    | 27        | 2.82%   |
| 5.7.13-975.native   | 23        | 2.4%    |
| 5.4.18-902.native   | 23        | 2.4%    |
| 5.12.14-1051.native | 18        | 1.88%   |
| 5.13.8-1065.native  | 13        | 1.36%   |
| 5.5.5-911.native    | 12        | 1.25%   |
| 5.5.15-930.native   | 12        | 1.25%   |
| 5.9.12-1004.native  | 11        | 1.15%   |
| 5.6.6-942.native    | 9         | 0.94%   |
| 5.5.3-908.native    | 9         | 0.94%   |
| 5.12.8-1045.native  | 9         | 0.94%   |
| 5.9.8-1000.native   | 8         | 0.84%   |
| 5.7.7-967.native    | 8         | 0.84%   |
| 5.7.6-966.native    | 8         | 0.84%   |
| 5.5.9-918.native    | 8         | 0.84%   |
| 5.10.17-1026.native | 8         | 0.84%   |
| 5.7.2-962.native    | 7         | 0.73%   |
| 5.6.8-945.native    | 7         | 0.73%   |
| 5.5.4-909.native    | 7         | 0.73%   |
| 5.12.5-1041.native  | 7         | 0.73%   |
| 5.5.8-917.native    | 6         | 0.63%   |
| 5.3.9-863.native    | 6         | 0.63%   |
| 5.3.8-854.native    | 6         | 0.63%   |
| 5.3.5-847.native    | 6         | 0.63%   |
| 5.18.16-1165.native | 6         | 0.63%   |
| 5.16.17-1136.native | 6         | 0.63%   |
| 5.12.16-1054.native | 6         | 0.63%   |
| 5.10.18-1027.native | 6         | 0.63%   |
| 5.10.10-1017.native | 6         | 0.63%   |
| 5.1.5-770.native    | 6         | 0.63%   |
| 5.0.18-767.native   | 6         | 0.63%   |
| 5.9.1-992.native    | 5         | 0.52%   |
| 5.8.14-991.native   | 5         | 0.52%   |
| 5.7.11-973.native   | 5         | 0.52%   |
| 5.6.16-958.native   | 5         | 0.52%   |
| 5.6.15-957.native   | 5         | 0.52%   |
| 5.6.10-947.native   | 5         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.13 | 55        | 5.75%   |
| 5.13.13 | 49        | 5.12%   |
| 5.10.19 | 30        | 3.13%   |
| 5.5.6   | 27        | 2.82%   |
| 5.7.13  | 23        | 2.4%    |
| 5.4.18  | 23        | 2.4%    |
| 5.12.14 | 18        | 1.88%   |
| 5.5.3   | 13        | 1.36%   |
| 5.13.8  | 13        | 1.36%   |
| 5.5.5   | 12        | 1.25%   |
| 5.5.15  | 12        | 1.25%   |
| 5.9.12  | 11        | 1.15%   |
| 5.5.4   | 11        | 1.15%   |
| 5.6.8   | 10        | 1.04%   |
| 5.6.6   | 9         | 0.94%   |
| 5.5.9   | 9         | 0.94%   |
| 5.12.8  | 9         | 0.94%   |
| 5.9.8   | 8         | 0.84%   |
| 5.7.7   | 8         | 0.84%   |
| 5.7.6   | 8         | 0.84%   |
| 5.10.17 | 8         | 0.84%   |
| 5.7.2   | 7         | 0.73%   |
| 5.17.9  | 7         | 0.73%   |
| 5.16.18 | 7         | 0.73%   |
| 5.12.5  | 7         | 0.73%   |
| 5.6.15  | 6         | 0.63%   |
| 5.5.8   | 6         | 0.63%   |
| 5.5.13  | 6         | 0.63%   |
| 5.3.9   | 6         | 0.63%   |
| 5.3.8   | 6         | 0.63%   |
| 5.3.5   | 6         | 0.63%   |
| 5.18.16 | 6         | 0.63%   |
| 5.16.17 | 6         | 0.63%   |
| 5.12.16 | 6         | 0.63%   |
| 5.10.18 | 6         | 0.63%   |
| 5.10.10 | 6         | 0.63%   |
| 5.1.5   | 6         | 0.63%   |
| 5.0.18  | 6         | 0.63%   |
| 5.9.1   | 5         | 0.52%   |
| 5.8.14  | 5         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.5     | 105       | 11.4%   |
| 5.10    | 91        | 9.88%   |
| 5.16    | 84        | 9.12%   |
| 5.13    | 72        | 7.82%   |
| 5.4     | 67        | 7.27%   |
| 5.7     | 66        | 7.17%   |
| 5.6     | 59        | 6.41%   |
| 5.12    | 53        | 5.75%   |
| 5.9     | 42        | 4.56%   |
| 5.3     | 37        | 4.02%   |
| 5.18    | 25        | 2.71%   |
| 6.0     | 22        | 2.39%   |
| 5.2     | 22        | 2.39%   |
| 5.15    | 22        | 2.39%   |
| 6.1     | 21        | 2.28%   |
| 5.8     | 21        | 2.28%   |
| 5.0     | 21        | 2.28%   |
| 5.17    | 19        | 2.06%   |
| 5.1     | 18        | 1.95%   |
| 5.14    | 17        | 1.85%   |
| 6.2     | 14        | 1.52%   |
| 5.19    | 12        | 1.3%    |
| 4.19    | 11        | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 837       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 700       | 81.49%  |
| Unknown         | 98        | 11.41%  |
| KDE             | 20        | 2.33%   |
| GNOME Flashback | 18        | 2.1%    |
| KDE5            | 12        | 1.4%    |
| XFCE            | 8         | 0.93%   |
| GNOME-Flashback | 2         | 0.23%   |
| awesome         | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 773       | 91.37%  |
| Wayland | 62        | 7.33%   |
| Tty     | 9         | 1.06%   |
| Unknown | 2         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 826       | 98.57%  |
| GDM     | 11        | 1.31%   |
| SDDM    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 538       | 63.22%  |
| Unknown    | 90        | 10.58%  |
| ru_RU      | 42        | 4.94%   |
| es_MX      | 28        | 3.29%   |
| de_DE      | 27        | 3.17%   |
| it_IT      | 17        | 2%      |
| fr_FR      | 16        | 1.88%   |
| en_GB      | 16        | 1.88%   |
| pt_BR      | 13        | 1.53%   |
| pl_PL      | 10        | 1.18%   |
| es_ES      | 9         | 1.06%   |
| zh_CN      | 8         | 0.94%   |
| C          | 7         | 0.82%   |
| en_AU      | 4         | 0.47%   |
| tr_TR      | 3         | 0.35%   |
| pt_PT      | 3         | 0.35%   |
| bg_BG      | 3         | 0.35%   |
| zh_TW      | 2         | 0.24%   |
| nl_BE      | 2         | 0.24%   |
| fi_FI      | 2         | 0.24%   |
| en_ZA      | 2         | 0.24%   |
| sv_SE      | 1         | 0.12%   |
| nl_NL      | 1         | 0.12%   |
| ka_GE      | 1         | 0.12%   |
| hu_HU      | 1         | 0.12%   |
| en_US.UTF8 | 1         | 0.12%   |
| en_IN      | 1         | 0.12%   |
| de_AT      | 1         | 0.12%   |
| da_DK      | 1         | 0.12%   |
| ar_SA      | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 837       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 729       | 85.76%  |
| Unknown | 100       | 11.76%  |
| Btrfs   | 11        | 1.29%   |
| Xfs     | 10        | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 819       | 97.38%  |
| GPT     | 22        | 2.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 834       | 99.64%  |
| Yes       | 3         | 0.36%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 830       | 99.05%  |
| Yes       | 8         | 0.95%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 131       | 15.65%  |
| Dell                | 115       | 13.74%  |
| Hewlett-Packard     | 106       | 12.66%  |
| Lenovo              | 101       | 12.07%  |
| Gigabyte Technology | 58        | 6.93%   |
| Acer                | 46        | 5.5%    |
| Intel               | 41        | 4.9%    |
| MSI                 | 40        | 4.78%   |
| ASRock              | 31        | 3.7%    |
| Apple               | 27        | 3.23%   |
| Unknown             | 13        | 1.55%   |
| Google              | 11        | 1.31%   |
| Samsung Electronics | 10        | 1.19%   |
| Microsoft           | 8         | 0.96%   |
| Toshiba             | 7         | 0.84%   |
| Sony                | 5         | 0.6%    |
| HUAWEI              | 5         | 0.6%    |
| Fujitsu             | 5         | 0.6%    |
| Supermicro          | 4         | 0.48%   |
| Hampoo              | 4         | 0.48%   |
| Chuwi               | 4         | 0.48%   |
| Medion              | 3         | 0.36%   |
| Complet             | 3         | 0.36%   |
| Biostar             | 3         | 0.36%   |
| Alienware           | 3         | 0.36%   |
| Teclast             | 2         | 0.24%   |
| Shuttle             | 2         | 0.24%   |
| Positivo            | 2         | 0.24%   |
| Pegatron            | 2         | 0.24%   |
| Panasonic           | 2         | 0.24%   |
| Notebook            | 2         | 0.24%   |
| MOTILE              | 2         | 0.24%   |
| Huanan              | 2         | 0.24%   |
| Foxconn             | 2         | 0.24%   |
| AMI                 | 2         | 0.24%   |
| TrekStor            | 1         | 0.12%   |
| TODOS INDUSTRIAL    | 1         | 0.12%   |
| Timi                | 1         | 0.12%   |
| SYS                 | 1         | 0.12%   |
| Razer               | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 16        | 1.91%   |
| ASUS All Series                            | 12        | 1.43%   |
| Dell XPS 15 9560                           | 5         | 0.6%    |
| Dell OptiPlex 9020                         | 5         | 0.6%    |
| Intel NUC8i7BEH                            | 4         | 0.48%   |
| Intel DN2820FYB H24582-205                 | 4         | 0.48%   |
| HP Notebook                                | 4         | 0.48%   |
| Dell OptiPlex 7010                         | 4         | 0.48%   |
| Apple MacBookPro11,5                       | 4         | 0.48%   |
| MSI MS-7C60                                | 3         | 0.36%   |
| MSI MS-7C02                                | 3         | 0.36%   |
| Microsoft Surface Book 2                   | 3         | 0.36%   |
| Lenovo MIIX 310-10ICR 80SG                 | 3         | 0.36%   |
| Lenovo G500 20236                          | 3         | 0.36%   |
| HP Pavilion Notebook                       | 3         | 0.36%   |
| HP Pavilion 15                             | 3         | 0.36%   |
| HP EliteBook 8460p                         | 3         | 0.36%   |
| HP EliteBook 840 G1                        | 3         | 0.36%   |
| Dell XPS 13 9360                           | 3         | 0.36%   |
| Dell Inspiron 5570                         | 3         | 0.36%   |
| Dell Inspiron 3537                         | 3         | 0.36%   |
| Complet MY8312                             | 3         | 0.36%   |
| ASUS VivoBook_ASUSLaptop X515DA_M515DA     | 3         | 0.36%   |
| ASRock TRX40 Creator                       | 3         | 0.36%   |
| Apple MacBookPro9,2                        | 3         | 0.36%   |
| Apple MacBookPro8,1                        | 3         | 0.36%   |
| Apple MacBookPro10,1                       | 3         | 0.36%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D | 2         | 0.24%   |
| MSI MS-7C95                                | 2         | 0.24%   |
| MSI GS43VR 7RE                             | 2         | 0.24%   |
| MOTILE M141                                | 2         | 0.24%   |
| Lenovo IdeaPad 110-15ACL 80TJ              | 2         | 0.24%   |
| Lenovo G50-70 20351                        | 2         | 0.24%   |
| Intel NUC8i7HVK                            | 2         | 0.24%   |
| Intel NUC8i5BEK                            | 2         | 0.24%   |
| Intel NUC6CAYB J23203-403                  | 2         | 0.24%   |
| Intel NUC5PPYB H76558-109                  | 2         | 0.24%   |
| Intel NUC10i7FNH                           | 2         | 0.24%   |
| HUAWEI NBLB-WAX9N                          | 2         | 0.24%   |
| HP Z420 Workstation                        | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 39        | 4.66%   |
| Acer Aspire        | 38        | 4.54%   |
| Dell Inspiron      | 30        | 3.58%   |
| Dell XPS           | 26        | 3.11%   |
| Dell Latitude      | 26        | 3.11%   |
| HP Pavilion        | 23        | 2.75%   |
| Lenovo IdeaPad     | 22        | 2.63%   |
| ASUS ROG           | 21        | 2.51%   |
| ASUS PRIME         | 20        | 2.39%   |
| Dell OptiPlex      | 17        | 2.03%   |
| Unknown            | 16        | 1.91%   |
| HP EliteBook       | 15        | 1.79%   |
| ASUS VivoBook      | 15        | 1.79%   |
| ASUS All           | 12        | 1.43%   |
| Dell Precision     | 9         | 1.08%   |
| ASUS TUF           | 9         | 1.08%   |
| Microsoft Surface  | 8         | 0.96%   |
| HP Laptop          | 8         | 0.96%   |
| HP ENVY            | 8         | 0.96%   |
| HP Compaq          | 8         | 0.96%   |
| Toshiba Satellite  | 6         | 0.72%   |
| Lenovo ThinkCentre | 6         | 0.72%   |
| HP Stream          | 6         | 0.72%   |
| Gigabyte X570      | 5         | 0.6%    |
| ASUS ZenBook       | 5         | 0.6%    |
| Apple MacBookPro8  | 5         | 0.6%    |
| Apple MacBookPro11 | 5         | 0.6%    |
| Lenovo Yoga        | 4         | 0.48%   |
| Lenovo MIIX        | 4         | 0.48%   |
| Intel NUC8i7BEH    | 4         | 0.48%   |
| Intel DN2820FYB    | 4         | 0.48%   |
| HP Notebook        | 4         | 0.48%   |
| Dell Vostro        | 4         | 0.48%   |
| ASRock TRX40       | 4         | 0.48%   |
| MSI MS-7C60        | 3         | 0.36%   |
| MSI MS-7C02        | 3         | 0.36%   |
| Lenovo ThinkBook   | 3         | 0.36%   |
| Lenovo G500        | 3         | 0.36%   |
| HP ZBook           | 3         | 0.36%   |
| HP ProBook         | 3         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 119       | 14.22%  |
| 2019 | 114       | 13.62%  |
| 2020 | 82        | 9.8%    |
| 2012 | 74        | 8.84%   |
| 2017 | 72        | 8.6%    |
| 2015 | 69        | 8.24%   |
| 2013 | 69        | 8.24%   |
| 2016 | 67        | 8%      |
| 2014 | 65        | 7.77%   |
| 2011 | 43        | 5.14%   |
| 2021 | 36        | 4.3%    |
| 2022 | 13        | 1.55%   |
| 2010 | 11        | 1.31%   |
| 2009 | 2         | 0.24%   |
| 2008 | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 439       | 52.45%  |
| Desktop     | 301       | 35.96%  |
| Mini pc     | 39        | 4.66%   |
| Convertible | 23        | 2.75%   |
| Tablet      | 21        | 2.51%   |
| Server      | 8         | 0.96%   |
| All in one  | 6         | 0.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 837       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 826       | 98.69%  |
| Yes  | 11        | 1.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 212       | 25%     |
| 4.01-8.0        | 185       | 21.82%  |
| 8.01-16.0       | 157       | 18.51%  |
| 3.01-4.0        | 137       | 16.16%  |
| 32.01-64.0      | 83        | 9.79%   |
| 64.01-256.0     | 40        | 4.72%   |
| 24.01-32.0      | 16        | 1.89%   |
| 1.01-2.0        | 13        | 1.53%   |
| More than 256.0 | 3         | 0.35%   |
| 2.01-3.0        | 2         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 335       | 36.98%  |
| 2.01-3.0    | 291       | 32.12%  |
| 3.01-4.0    | 126       | 13.91%  |
| 4.01-8.0    | 106       | 11.7%   |
| 8.01-16.0   | 27        | 2.98%   |
| 0.51-1.0    | 17        | 1.88%   |
| 16.01-24.0  | 2         | 0.22%   |
| 32.01-64.0  | 1         | 0.11%   |
| 64.01-256.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 507       | 59.02%  |
| 2      | 213       | 24.8%   |
| 3      | 74        | 8.61%   |
| 4      | 35        | 4.07%   |
| 5      | 16        | 1.86%   |
| 6      | 6         | 0.7%    |
| 7      | 4         | 0.47%   |
| 0      | 4         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 622       | 74.14%  |
| Yes       | 217       | 25.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 684       | 81.43%  |
| No        | 156       | 18.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 656       | 77.82%  |
| No        | 187       | 22.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 571       | 67.57%  |
| No        | 274       | 32.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 209       | 24.88%  |
| Russia       | 61        | 7.26%   |
| Germany      | 48        | 5.71%   |
| UK           | 45        | 5.36%   |
| Italy        | 38        | 4.52%   |
| Brazil       | 36        | 4.29%   |
| Canada       | 28        | 3.33%   |
| Australia    | 24        | 2.86%   |
| India        | 22        | 2.62%   |
| Poland       | 21        | 2.5%    |
| Netherlands  | 20        | 2.38%   |
| France       | 19        | 2.26%   |
| Spain        | 16        | 1.9%    |
| Romania      | 14        | 1.67%   |
| Mexico       | 14        | 1.67%   |
| Bulgaria     | 12        | 1.43%   |
| Argentina    | 11        | 1.31%   |
| Ukraine      | 10        | 1.19%   |
| Sweden       | 10        | 1.19%   |
| Switzerland  | 9         | 1.07%   |
| Turkey       | 8         | 0.95%   |
| South Africa | 8         | 0.95%   |
| Norway       | 8         | 0.95%   |
| Indonesia    | 8         | 0.95%   |
| China        | 8         | 0.95%   |
| Portugal     | 7         | 0.83%   |
| Hong Kong    | 6         | 0.71%   |
| Finland      | 6         | 0.71%   |
| Austria      | 6         | 0.71%   |
| Vietnam      | 5         | 0.6%    |
| Thailand     | 5         | 0.6%    |
| Chile        | 5         | 0.6%    |
| Belgium      | 5         | 0.6%    |
| Serbia       | 4         | 0.48%   |
| Hungary      | 4         | 0.48%   |
| Denmark      | 4         | 0.48%   |
| Taiwan       | 3         | 0.36%   |
| Saudi Arabia | 3         | 0.36%   |
| New Zealand  | 3         | 0.36%   |
| Israel       | 3         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 16        | 1.82%   |
| Sydney            | 9         | 1.02%   |
| St Petersburg     | 9         | 1.02%   |
| Rome              | 9         | 1.02%   |
| Berlin            | 7         | 0.8%    |
| Brisbane          | 6         | 0.68%   |
| Zurich            | 5         | 0.57%   |
| Tucson            | 5         | 0.57%   |
| Toronto           | 5         | 0.57%   |
| Sofia             | 5         | 0.57%   |
| Sao Paulo         | 5         | 0.57%   |
| Portland          | 5         | 0.57%   |
| Houston           | 5         | 0.57%   |
| Chicago           | 5         | 0.57%   |
| Seattle           | 4         | 0.46%   |
| San Francisco     | 4         | 0.46%   |
| Mexico City       | 4         | 0.46%   |
| Johannesburg      | 4         | 0.46%   |
| Fort Worth        | 4         | 0.46%   |
| Wroclaw           | 3         | 0.34%   |
| Warsaw            | 3         | 0.34%   |
| Vigneux-sur-Seine | 3         | 0.34%   |
| Thunder Bay       | 3         | 0.34%   |
| Springfield       | 3         | 0.34%   |
| Shelbyville       | 3         | 0.34%   |
| San Jose          | 3         | 0.34%   |
| Rho               | 3         | 0.34%   |
| Pune              | 3         | 0.34%   |
| Palermo           | 3         | 0.34%   |
| Mumbai            | 3         | 0.34%   |
| Minsk             | 3         | 0.34%   |
| Milan             | 3         | 0.34%   |
| Melbourne         | 3         | 0.34%   |
| Las Vegas         | 3         | 0.34%   |
| Las Condes        | 3         | 0.34%   |
| Kyiv              | 3         | 0.34%   |
| Ho Chi Minh City  | 3         | 0.34%   |
| Glasgow           | 3         | 0.34%   |
| Dresden           | 3         | 0.34%   |
| Dallas            | 3         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 194       | 296    | 15.53%  |
| Seagate                   | 159       | 221    | 12.73%  |
| WDC                       | 118       | 150    | 9.45%   |
| Toshiba                   | 100       | 121    | 8.01%   |
| Unknown                   | 88        | 117    | 7.05%   |
| SanDisk                   | 78        | 89     | 6.24%   |
| Kingston                  | 66        | 80     | 5.28%   |
| Intel                     | 38        | 44     | 3.04%   |
| SK hynix                  | 37        | 43     | 2.96%   |
| Crucial                   | 37        | 46     | 2.96%   |
| HGST                      | 27        | 35     | 2.16%   |
| Phison                    | 23        | 32     | 1.84%   |
| Hitachi                   | 23        | 26     | 1.84%   |
| A-DATA Technology         | 21        | 23     | 1.68%   |
| Apple                     | 17        | 18     | 1.36%   |
| Micron Technology         | 15        | 19     | 1.2%    |
| SPCC                      | 12        | 13     | 0.96%   |
| JMicron Technology        | 12        | 12     | 0.96%   |
| Silicon Motion            | 11        | 13     | 0.88%   |
| Transcend                 | 10        | 10     | 0.8%    |
| Patriot                   | 8         | 9      | 0.64%   |
| LITEONIT                  | 8         | 15     | 0.64%   |
| PNY                       | 7         | 11     | 0.56%   |
| Micron/Crucial Technology | 7         | 10     | 0.56%   |
| KIOXIA                    | 7         | 14     | 0.56%   |
| China                     | 7         | 27     | 0.56%   |
| XPG                       | 6         | 6      | 0.48%   |
| LITEON                    | 6         | 7      | 0.48%   |
| Phison Electronics        | 5         | 5      | 0.4%    |
| KingSpec                  | 5         | 6      | 0.4%    |
| Corsair                   | 5         | 9      | 0.4%    |
| ADATA Technology          | 5         | 5      | 0.4%    |
| Team                      | 4         | 4      | 0.32%   |
| Netac                     | 4         | 4      | 0.32%   |
| Hewlett-Packard           | 4         | 4      | 0.32%   |
| Fujitsu                   | 4         | 5      | 0.32%   |
| FORESEE                   | 4         | 4      | 0.32%   |
| Apacer                    | 4         | 5      | 0.32%   |
| Teclast                   | 3         | 3      | 0.24%   |
| Plextor                   | 3         | 3      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 500GB           | 25        | 1.84%   |
| Unknown MMC Card  32GB                 | 24        | 1.76%   |
| Unknown MMC Card  64GB                 | 22        | 1.62%   |
| Samsung SSD 850 EVO 250GB              | 17        | 1.25%   |
| Samsung NVMe SSD Drive 1TB             | 15        | 1.1%    |
| Samsung NVMe SSD Drive 256GB           | 14        | 1.03%   |
| Kingston SA400S37240G 240GB SSD        | 13        | 0.96%   |
| Unknown MMC Card  128GB                | 12        | 0.88%   |
| Seagate ST1000LM035-1RK172 970GB       | 12        | 0.88%   |
| Unknown SD/MMC/MS PRO 249GB            | 11        | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 11        | 0.81%   |
| HGST HTS721010A9E630 1TB               | 11        | 0.81%   |
| Toshiba NVMe SSD Drive 512GB           | 10        | 0.73%   |
| Toshiba MQ01ABF050 500GB               | 10        | 0.73%   |
| SanDisk NVMe SSD Drive 256GB           | 10        | 0.73%   |
| Samsung NVMe SSD Drive 1024GB          | 10        | 0.73%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 9         | 0.66%   |
| Crucial CT500MX500SSD1 500GB           | 9         | 0.66%   |
| Toshiba NVMe SSD Drive 256GB           | 8         | 0.59%   |
| Toshiba MQ01ABD100 1TB                 | 8         | 0.59%   |
| Toshiba DT01ACA100 1TB                 | 8         | 0.59%   |
| Seagate ST500LT012-1DG142 500GB        | 8         | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB         | 8         | 0.59%   |
| Samsung NVMe SSD Drive 512GB           | 8         | 0.59%   |
| JMicron Tech 250GB                     | 8         | 0.59%   |
| Intel NVMe SSD Drive 512GB             | 8         | 0.59%   |
| SK hynix NVMe SSD Drive 512GB          | 7         | 0.51%   |
| SK hynix NVMe SSD Drive 256GB          | 7         | 0.51%   |
| SanDisk NVMe SSD Drive 512GB           | 7         | 0.51%   |
| Samsung SSD 860 EVO 500GB              | 7         | 0.51%   |
| Kingston SA400S37120G 120GB SSD        | 7         | 0.51%   |
| Intel NVMe SSD Drive 1024GB            | 7         | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB               | 6         | 0.44%   |
| Toshiba DT01ACA050 500GB               | 6         | 0.44%   |
| Samsung SSD 860 EVO 250GB              | 6         | 0.44%   |
| Samsung SSD 850 PRO 256GB              | 6         | 0.44%   |
| Phison NVMe SSD Drive 1TB              | 6         | 0.44%   |
| Toshiba HDWD110 1TB                    | 5         | 0.37%   |
| Seagate ST500DM002-1BD142 500GB        | 5         | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB         | 5         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 207    | 38.1%   |
| WDC                 | 97        | 121    | 24.31%  |
| Toshiba             | 62        | 81     | 15.54%  |
| HGST                | 27        | 35     | 6.77%   |
| Hitachi             | 23        | 26     | 5.76%   |
| Unknown             | 11        | 12     | 2.76%   |
| Samsung Electronics | 10        | 10     | 2.51%   |
| JMicron Technology  | 4         | 4      | 1%      |
| Fujitsu             | 3         | 4      | 0.75%   |
| Apple               | 3         | 3      | 0.75%   |
| Maxtor              | 2         | 2      | 0.5%    |
| USB3.0              | 1         | 1      | 0.25%   |
| MARVELL             | 1         | 1      | 0.25%   |
| HPE                 | 1         | 1      | 0.25%   |
| H/W                 | 1         | 2      | 0.25%   |
| ASMT                | 1         | 2      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 114       | 161    | 23.31%  |
| Kingston            | 57        | 66     | 11.66%  |
| SanDisk             | 42        | 45     | 8.59%   |
| Crucial             | 37        | 46     | 7.57%   |
| WDC                 | 24        | 29     | 4.91%   |
| A-DATA Technology   | 21        | 23     | 4.29%   |
| SK hynix            | 17        | 21     | 3.48%   |
| Toshiba             | 13        | 14     | 2.66%   |
| Intel               | 13        | 14     | 2.66%   |
| Apple               | 13        | 14     | 2.66%   |
| SPCC                | 12        | 13     | 2.45%   |
| Micron Technology   | 11        | 12     | 2.25%   |
| Transcend           | 10        | 10     | 2.04%   |
| Patriot             | 8         | 9      | 1.64%   |
| LITEONIT            | 8         | 15     | 1.64%   |
| PNY                 | 7         | 11     | 1.43%   |
| China               | 7         | 27     | 1.43%   |
| LITEON              | 6         | 7      | 1.23%   |
| KingSpec            | 5         | 6      | 1.02%   |
| Team                | 4         | 4      | 0.82%   |
| Hewlett-Packard     | 4         | 4      | 0.82%   |
| FORESEE             | 4         | 4      | 0.82%   |
| Corsair             | 4         | 8      | 0.82%   |
| Apacer              | 4         | 5      | 0.82%   |
| Teclast             | 3         | 3      | 0.61%   |
| Plextor             | 3         | 3      | 0.61%   |
| OCZ                 | 3         | 5      | 0.61%   |
| Netac               | 3         | 3      | 0.61%   |
| KingDian            | 3         | 5      | 0.61%   |
| Seagate             | 2         | 2      | 0.41%   |
| Intenso             | 2         | 2      | 0.41%   |
| Hikvision           | 2         | 2      | 0.41%   |
| GOODRAM             | 2         | 2      | 0.41%   |
| WDC WDS2            | 1         | 1      | 0.2%    |
| WDC WDS1            | 1         | 1      | 0.2%    |
| W800S               | 1         | 1      | 0.2%    |
| Verbatim            | 1         | 2      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |
| TO Exter            | 1         | 1      | 0.2%    |
| Smart               | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 431       | 619    | 37.35%  |
| HDD     | 356       | 512    | 30.85%  |
| NVMe    | 273       | 377    | 23.66%  |
| MMC     | 68        | 95     | 5.89%   |
| Unknown | 26        | 32     | 2.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 641       | 1103   | 62.11%  |
| NVMe | 272       | 376    | 26.36%  |
| MMC  | 68        | 95     | 6.59%   |
| SAS  | 51        | 61     | 4.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 481       | 726    | 60.73%  |
| 0.51-1.0   | 207       | 273    | 26.14%  |
| 1.01-2.0   | 53        | 66     | 6.69%   |
| 4.01-10.0  | 19        | 25     | 2.4%    |
| 3.01-4.0   | 14        | 19     | 1.77%   |
| 2.01-3.0   | 10        | 10     | 1.26%   |
| 10.01-20.0 | 8         | 12     | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 314       | 36.05%  |
| 251-500        | 178       | 20.44%  |
| 501-1000       | 119       | 13.66%  |
| 51-100         | 66        | 7.58%   |
| Unknown        | 62        | 7.12%   |
| 21-50          | 50        | 5.74%   |
| 1001-2000      | 44        | 5.05%   |
| More than 3000 | 21        | 2.41%   |
| 2001-3000      | 13        | 1.49%   |
| 1-20           | 4         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 417       | 46.54%  |
| 21-50          | 206       | 22.99%  |
| 51-100         | 71        | 7.92%   |
| 101-250        | 64        | 7.14%   |
| Unknown        | 62        | 6.92%   |
| 251-500        | 32        | 3.57%   |
| 501-1000       | 20        | 2.23%   |
| 1001-2000      | 11        | 1.23%   |
| More than 3000 | 10        | 1.12%   |
| 2001-3000      | 3         | 0.33%   |

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
| Detected | 820       | 1600   | 97.74%  |
| Works    | 16        | 32     | 1.91%   |
| Malfunc  | 3         | 3      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 618       | 58.63%  |
| AMD                          | 116       | 11.01%  |
| Samsung Electronics          | 107       | 10.15%  |
| SanDisk                      | 35        | 3.32%   |
| Phison Electronics           | 26        | 2.47%   |
| Toshiba America Info Systems | 25        | 2.37%   |
| SK hynix                     | 20        | 1.9%    |
| ASMedia Technology           | 20        | 1.9%    |
| ADATA Technology             | 12        | 1.14%   |
| Silicon Motion               | 11        | 1.04%   |
| Kingston Technology Company  | 11        | 1.04%   |
| Marvell Technology Group     | 10        | 0.95%   |
| KIOXIA                       | 8         | 0.76%   |
| Micron/Crucial Technology    | 7         | 0.66%   |
| Broadcom / LSI               | 5         | 0.47%   |
| Seagate Technology           | 4         | 0.38%   |
| Micron Technology            | 4         | 0.38%   |
| Realtek Semiconductor        | 3         | 0.28%   |
| LSI Logic / Symbios Logic    | 3         | 0.28%   |
| Yangtze Memory Technologies  | 2         | 0.19%   |
| Shenzhen Longsys Electronics | 2         | 0.19%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.09%   |
| Lite-On Technology           | 1         | 0.09%   |
| Hewlett-Packard              | 1         | 0.09%   |
| Biwin Storage Technology     | 1         | 0.09%   |
| Apple                        | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 97        | 8.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 60        | 5.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 58        | 5.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 56        | 4.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 45        | 3.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 38        | 3.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 29        | 2.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 28        | 2.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 25        | 2.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 2.08%   |
| Intel SATA Controller [RAID mode]                                              | 23        | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 22        | 1.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21        | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 20        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 1.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 1.65%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 19        | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 18        | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 18        | 1.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 18        | 1.56%   |
| AMD 400 Series Chipset SATA Controller                                         | 17        | 1.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 16        | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 15        | 1.3%    |
| Intel SSD 660P Series                                                          | 12        | 1.04%   |
| Phison E12 NVMe Controller                                                     | 11        | 0.95%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 10        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 0.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 10        | 0.87%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 10        | 0.87%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 0.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 8         | 0.69%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 8         | 0.69%   |
| Samsung Electronics SATA controller                                            | 8         | 0.69%   |
| Phison E16 PCIe4 NVMe Controller                                               | 8         | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 8         | 0.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 0.61%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 7         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 658       | 62.55%  |
| NVMe | 277       | 26.33%  |
| RAID | 80        | 7.6%    |
| IDE  | 29        | 2.76%   |
| SAS  | 7         | 0.67%   |
| SCSI | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 712       | 85.07%  |
| AMD    | 125       | 14.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz              | 18        | 2.15%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 11        | 1.31%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 10        | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 10        | 1.19%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 10        | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 9         | 1.07%   |
| Intel Core i5-4200U CPU @ 1.60GHz              | 9         | 1.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 9         | 1.07%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 9         | 1.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 8         | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 8         | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 8         | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz              | 8         | 0.95%   |
| Intel Celeron CPU N3350 @ 1.10GHz              | 8         | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 7         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 7         | 0.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 7         | 0.84%   |
| Intel Celeron CPU N2830 @ 2.16GHz              | 7         | 0.84%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 7         | 0.84%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 6         | 0.72%   |
| Intel Core i7-8559U CPU @ 2.70GHz              | 6         | 0.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 6         | 0.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 6         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 6         | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 6         | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor              | 6         | 0.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 6         | 0.72%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 5         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz              | 5         | 0.6%    |
| Intel Core i7-8700K CPU @ 3.70GHz              | 5         | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz               | 5         | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz              | 5         | 0.6%    |
| Intel Core i7-4870HQ CPU @ 2.50GHz             | 5         | 0.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz              | 5         | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz               | 5         | 0.6%    |
| Intel Core i5-3337U CPU @ 1.80GHz              | 5         | 0.6%    |
| Intel Core i5-3317U CPU @ 1.70GHz              | 5         | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz             | 5         | 0.6%    |
| Intel Celeron N4000 CPU @ 1.10GHz              | 5         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz              | 4         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 249       | 29.75%  |
| Intel Core i7          | 198       | 23.66%  |
| Intel Celeron          | 78        | 9.32%   |
| Intel Core i3          | 61        | 7.29%   |
| Other                  | 33        | 3.94%   |
| AMD Ryzen 5            | 33        | 3.94%   |
| Intel Xeon             | 30        | 3.58%   |
| Intel Pentium          | 24        | 2.87%   |
| AMD Ryzen 7            | 21        | 2.51%   |
| Intel Atom             | 14        | 1.67%   |
| AMD Ryzen Threadripper | 13        | 1.55%   |
| AMD Ryzen 3            | 13        | 1.55%   |
| Intel Core i9          | 10        | 1.19%   |
| AMD Ryzen 9            | 10        | 1.19%   |
| AMD FX                 | 8         | 0.96%   |
| Intel Pentium Silver   | 7         | 0.84%   |
| AMD A8                 | 6         | 0.72%   |
| AMD A10                | 5         | 0.6%    |
| AMD A6                 | 4         | 0.48%   |
| AMD Athlon             | 3         | 0.36%   |
| Intel Core m5          | 2         | 0.24%   |
| Intel Core m3          | 2         | 0.24%   |
| AMD E1                 | 2         | 0.24%   |
| AMD A4                 | 2         | 0.24%   |
| Intel Xeon Platinum    | 1         | 0.12%   |
| Intel Pentium Gold     | 1         | 0.12%   |
| Intel Genuine          | 1         | 0.12%   |
| Intel Core M           | 1         | 0.12%   |
| AMD Ryzen 7 PRO        | 1         | 0.12%   |
| AMD Ryzen 5 PRO        | 1         | 0.12%   |
| AMD Opteron            | 1         | 0.12%   |
| AMD E2                 | 1         | 0.12%   |
| AMD A12                | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 358       | 42.77%  |
| 2      | 303       | 36.2%   |
| 6      | 88        | 10.51%  |
| 8      | 38        | 4.54%   |
| 12     | 15        | 1.79%   |
| 24     | 9         | 1.08%   |
| 16     | 7         | 0.84%   |
| 10     | 6         | 0.72%   |
| 64     | 3         | 0.36%   |
| 32     | 3         | 0.36%   |
| 1      | 3         | 0.36%   |
| 36     | 1         | 0.12%   |
| 28     | 1         | 0.12%   |
| 20     | 1         | 0.12%   |
| 14     | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 828       | 98.92%  |
| 2      | 8         | 0.96%   |
| 4      | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 592       | 70.64%  |
| 1      | 246       | 29.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 762       | 90.28%  |
| Unknown        | 82        | 9.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 788       | 93.59%  |
| 0x906ea    | 5         | 0.59%   |
| 0x806ea    | 5         | 0.59%   |
| 0x506e3    | 5         | 0.59%   |
| 0x40651    | 5         | 0.59%   |
| 0x306a9    | 5         | 0.59%   |
| 0x906e9    | 4         | 0.48%   |
| 0x306c3    | 4         | 0.48%   |
| 0x30678    | 4         | 0.48%   |
| 0x706a1    | 3         | 0.36%   |
| 0x406c4    | 2         | 0.24%   |
| 0x306d4    | 2         | 0.24%   |
| 0x206a7    | 2         | 0.24%   |
| 0x806ec    | 1         | 0.12%   |
| 0x806eb    | 1         | 0.12%   |
| 0x806e9    | 1         | 0.12%   |
| 0x706a8    | 1         | 0.12%   |
| 0x506c9    | 1         | 0.12%   |
| 0x406c3    | 1         | 0.12%   |
| 0x40671    | 1         | 0.12%   |
| 0x08108109 | 1         | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 199       | 23.78%  |
| Haswell       | 100       | 11.95%  |
| IvyBridge     | 89        | 10.63%  |
| Skylake       | 61        | 7.29%   |
| SandyBridge   | 58        | 6.93%   |
| Silvermont    | 50        | 5.97%   |
| Zen 2         | 34        | 4.06%   |
| Zen+          | 33        | 3.94%   |
| Broadwell     | 33        | 3.94%   |
| Goldmont plus | 29        | 3.46%   |
| Unknown       | 21        | 2.51%   |
| CometLake     | 20        | 2.39%   |
| Goldmont      | 18        | 2.15%   |
| Zen           | 15        | 1.79%   |
| TigerLake     | 15        | 1.79%   |
| Piledriver    | 14        | 1.67%   |
| Westmere      | 13        | 1.55%   |
| Zen 3         | 11        | 1.31%   |
| IceLake       | 7         | 0.84%   |
| Puma          | 6         | 0.72%   |
| Excavator     | 6         | 0.72%   |
| Jaguar        | 2         | 0.24%   |
| Bulldozer     | 2         | 0.24%   |
| Steamroller   | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 569       | 55.3%   |
| Nvidia                     | 293       | 28.47%  |
| AMD                        | 164       | 15.94%  |
| Matrox Electronics Systems | 2         | 0.19%   |
| ASPEED Technology          | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 53        | 5.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 41        | 3.94%   |
| Intel UHD Graphics 620                                                                   | 33        | 3.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 2.79%   |
| Intel HD Graphics 630                                                                    | 27        | 2.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 2.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 25        | 2.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 2.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 2.02%   |
| Intel HD Graphics 620                                                                    | 20        | 1.92%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.92%   |
| Intel HD Graphics 530                                                                    | 20        | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.25%   |
| Intel HD Graphics 500                                                                    | 13        | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 1.06%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 10        | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 0.96%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 10        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 8         | 0.77%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8         | 0.77%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 7         | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7         | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.67%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 7         | 0.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.58%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6         | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 6         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 389       | 46.14%  |
| 1 x Nvidia               | 153       | 18.15%  |
| Intel + Nvidia           | 131       | 15.54%  |
| 1 x AMD                  | 122       | 14.47%  |
| Intel + AMD              | 29        | 3.44%   |
| 2 x AMD                  | 6         | 0.71%   |
| AMD + Nvidia             | 4         | 0.47%   |
| Other                    | 2         | 0.24%   |
| 2 x Nvidia               | 2         | 0.24%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.12%   |
| Nvidia + Matrox          | 1         | 0.12%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.12%   |
| 1 x ASPEED               | 1         | 0.12%   |
| AMD + Matrox             | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 807       | 96.19%  |
| Proprietary | 29        | 3.46%   |
| Unknown     | 3         | 0.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 801       | 95.36%  |
| 3.01-4.0   | 10        | 1.19%   |
| 1.01-2.0   | 9         | 1.07%   |
| 7.01-8.0   | 7         | 0.83%   |
| 0.51-1.0   | 5         | 0.6%    |
| 5.01-6.0   | 4         | 0.48%   |
| 8.01-16.0  | 2         | 0.24%   |
| 2.01-3.0   | 1         | 0.12%   |
| 16.01-24.0 | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 127       | 14%     |
| AU Optronics            | 112       | 12.35%  |
| BOE                     | 80        | 8.82%   |
| LG Display              | 73        | 8.05%   |
| Chimei Innolux          | 67        | 7.39%   |
| Dell                    | 56        | 6.17%   |
| Goldstar                | 47        | 5.18%   |
| Sharp                   | 35        | 3.86%   |
| Hewlett-Packard         | 27        | 2.98%   |
| Apple                   | 25        | 2.76%   |
| AOC                     | 25        | 2.76%   |
| BenQ                    | 24        | 2.65%   |
| Acer                    | 22        | 2.43%   |
| Ancor Communications    | 18        | 1.98%   |
| PANDA                   | 17        | 1.87%   |
| ViewSonic               | 15        | 1.65%   |
| Philips                 | 15        | 1.65%   |
| Lenovo                  | 10        | 1.1%    |
| MSI                     | 8         | 0.88%   |
| Chi Mei Optoelectronics | 7         | 0.77%   |
| ASUSTek Computer        | 7         | 0.77%   |
| Sony                    | 6         | 0.66%   |
| Hitachi                 | 6         | 0.66%   |
| Panasonic               | 5         | 0.55%   |
| Iiyama                  | 5         | 0.55%   |
| Vizio                   | 4         | 0.44%   |
| Toshiba                 | 4         | 0.44%   |
| LG Electronics          | 4         | 0.44%   |
| InfoVision              | 4         | 0.44%   |
| Unknown                 | 3         | 0.33%   |
| Medion                  | 3         | 0.33%   |
| Sceptre Tech            | 2         | 0.22%   |
| RTK                     | 2         | 0.22%   |
| NEC Computers           | 2         | 0.22%   |
| MiTAC                   | 2         | 0.22%   |
| Insignia                | 2         | 0.22%   |
| Fujitsu Siemens         | 2         | 0.22%   |
| CSO                     | 2         | 0.22%   |
| Arnos Instruments       | 2         | 0.22%   |
| ZTR                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.65%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 6         | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.65%   |
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch             | 5         | 0.54%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                       | 5         | 0.54%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 5         | 0.54%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 5         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 4         | 0.43%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 4         | 0.43%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                  | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.43%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                    | 4         | 0.43%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 3         | 0.32%   |
| Samsung Electronics U28E510 SAM0D63 3840x2160 607x345mm 27.5-inch        | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch    | 3         | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.32%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 3         | 0.32%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.32%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.32%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch                 | 3         | 0.32%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 677x290mm 29.0-inch                 | 3         | 0.32%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 3         | 0.32%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 3         | 0.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 3         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.32%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 3         | 0.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.32%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO42EC 1366x768 344x193mm 15.5-inch            | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 3         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 406       | 45.88%  |
| 1366x768 (WXGA)    | 172       | 19.44%  |
| 3840x2160 (4K)     | 81        | 9.15%   |
| 2560x1440 (QHD)    | 28        | 3.16%   |
| 1600x900 (HD+)     | 24        | 2.71%   |
| 1920x1200 (WUXGA)  | 18        | 2.03%   |
| 1680x1050 (WSXGA+) | 18        | 2.03%   |
| 1280x1024 (SXGA)   | 17        | 1.92%   |
| 3440x1440          | 14        | 1.58%   |
| 2560x1080          | 14        | 1.58%   |
| 1440x900 (WXGA+)   | 12        | 1.36%   |
| 2880x1800          | 9         | 1.02%   |
| 1360x768           | 9         | 1.02%   |
| 1280x800 (WXGA)    | 9         | 1.02%   |
| 3200x1800 (QHD+)   | 6         | 0.68%   |
| Unknown            | 5         | 0.56%   |
| 3840x1080          | 4         | 0.45%   |
| 2560x1600          | 4         | 0.45%   |
| 2160x1440          | 4         | 0.45%   |
| 3840x2400          | 3         | 0.34%   |
| 1920x540           | 3         | 0.34%   |
| 1024x768 (XGA)     | 3         | 0.34%   |
| 5760x2160          | 2         | 0.23%   |
| 3840x1600          | 2         | 0.23%   |
| 2880x1920          | 2         | 0.23%   |
| 2736x1824          | 2         | 0.23%   |
| 4480x1440          | 1         | 0.11%   |
| 4093x4093          | 1         | 0.11%   |
| 3840x1100          | 1         | 0.11%   |
| 3600x1080          | 1         | 0.11%   |
| 3360x1050          | 1         | 0.11%   |
| 2400x1600          | 1         | 0.11%   |
| 2256x1504          | 1         | 0.11%   |
| 2160x1350          | 1         | 0.11%   |
| 2160x1200          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |
| 1920x1280          | 1         | 0.11%   |
| 1800x1200          | 1         | 0.11%   |
| 1600x1200          | 1         | 0.11%   |
| 1280x720 (HD)      | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 230       | 25.39%  |
| 13      | 95        | 10.49%  |
| 27      | 75        | 8.28%   |
| 24      | 71        | 7.84%   |
| 14      | 56        | 6.18%   |
| 23      | 51        | 5.63%   |
| 21      | 48        | 5.3%    |
| 17      | 40        | 4.42%   |
| 11      | 23        | 2.54%   |
| Unknown | 23        | 2.54%   |
| 34      | 21        | 2.32%   |
| 12      | 21        | 2.32%   |
| 84      | 16        | 1.77%   |
| 31      | 15        | 1.66%   |
| 22      | 15        | 1.66%   |
| 18      | 14        | 1.55%   |
| 19      | 13        | 1.43%   |
| 20      | 11        | 1.21%   |
| 54      | 7         | 0.77%   |
| 72      | 6         | 0.66%   |
| 48      | 5         | 0.55%   |
| 40      | 5         | 0.55%   |
| 37      | 5         | 0.55%   |
| 25      | 5         | 0.55%   |
| 35      | 4         | 0.44%   |
| 32      | 4         | 0.44%   |
| 26      | 4         | 0.44%   |
| 52      | 3         | 0.33%   |
| 16      | 3         | 0.33%   |
| 55      | 2         | 0.22%   |
| 49      | 2         | 0.22%   |
| 46      | 2         | 0.22%   |
| 29      | 2         | 0.22%   |
| 10      | 2         | 0.22%   |
| 65      | 1         | 0.11%   |
| 57      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 42      | 1         | 0.11%   |
| 36      | 1         | 0.11%   |
| 33      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 330       | 37.04%  |
| 501-600     | 180       | 20.2%   |
| 201-300     | 102       | 11.45%  |
| 401-500     | 91        | 10.21%  |
| 351-400     | 44        | 4.94%   |
| 601-700     | 33        | 3.7%    |
| 701-800     | 28        | 3.14%   |
| Unknown     | 23        | 2.58%   |
| 1501-2000   | 22        | 2.47%   |
| 1001-1500   | 22        | 2.47%   |
| 801-900     | 14        | 1.57%   |
| 901-1000    | 2         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 677       | 80.12%  |
| 16/10   | 76        | 8.99%   |
| 21/9    | 29        | 3.43%   |
| Unknown | 18        | 2.13%   |
| 5/4     | 17        | 2.01%   |
| 3/2     | 11        | 1.3%    |
| 4/3     | 8         | 0.95%   |
| 32/9    | 5         | 0.59%   |
| 3.40    | 1         | 0.12%   |
| 1.96    | 1         | 0.12%   |
| 1.00    | 1         | 0.12%   |
| 0.56    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 230       | 25.56%  |
| 201-250        | 150       | 16.67%  |
| 81-90          | 103       | 11.44%  |
| 301-350        | 78        | 8.67%   |
| 71-80          | 48        | 5.33%   |
| 351-500        | 45        | 5%      |
| More than 1000 | 37        | 4.11%   |
| 151-200        | 37        | 4.11%   |
| 121-130        | 29        | 3.22%   |
| 251-300        | 26        | 2.89%   |
| 51-60          | 24        | 2.67%   |
| Unknown        | 23        | 2.56%   |
| 141-150        | 22        | 2.44%   |
| 501-1000       | 21        | 2.33%   |
| 61-70          | 20        | 2.22%   |
| 111-120        | 4         | 0.44%   |
| 41-50          | 2         | 0.22%   |
| 131-140        | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 259       | 29.53%  |
| 121-160       | 240       | 27.37%  |
| 101-120       | 232       | 26.45%  |
| 161-240       | 63        | 7.18%   |
| More than 240 | 31        | 3.53%   |
| 1-50          | 29        | 3.31%   |
| Unknown       | 23        | 2.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 726       | 86.22%  |
| 2     | 101       | 12%     |
| 3     | 9         | 1.07%   |
| 0     | 6         | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 450       | 37.13%  |
| Realtek Semiconductor             | 408       | 33.66%  |
| Qualcomm Atheros                  | 155       | 12.79%  |
| Broadcom                          | 58        | 4.79%   |
| Broadcom Limited                  | 22        | 1.82%   |
| Ralink Technology                 | 15        | 1.24%   |
| TP-Link                           | 9         | 0.74%   |
| Aquantia                          | 9         | 0.74%   |
| Ralink                            | 7         | 0.58%   |
| Microsoft                         | 7         | 0.58%   |
| Marvell Technology Group          | 6         | 0.5%    |
| Dell                              | 6         | 0.5%    |
| ASUSTek Computer                  | 6         | 0.5%    |
| ASIX Electronics                  | 5         | 0.41%   |
| Samsung Electronics               | 4         | 0.33%   |
| Qualcomm Atheros Communications   | 4         | 0.33%   |
| Xiaomi                            | 3         | 0.25%   |
| Motorola PCS                      | 3         | 0.25%   |
| Huawei Technologies               | 3         | 0.25%   |
| Hewlett-Packard                   | 3         | 0.25%   |
| Edimax Technology                 | 3         | 0.25%   |
| DisplayLink                       | 3         | 0.25%   |
| Apple                             | 3         | 0.25%   |
| Microchip Technology              | 2         | 0.17%   |
| MediaTek                          | 2         | 0.17%   |
| HMD Global                        | 2         | 0.17%   |
| D-Link                            | 2         | 0.17%   |
| Sierra Wireless                   | 1         | 0.08%   |
| QinHeng Electronics               | 1         | 0.08%   |
| Nordic Semiconductor ASA          | 1         | 0.08%   |
| Micro Star International          | 1         | 0.08%   |
| LeafLabs                          | 1         | 0.08%   |
| JMicron Technology                | 1         | 0.08%   |
| ICS Advent                        | 1         | 0.08%   |
| Google                            | 1         | 0.08%   |
| Ericsson Business Mobile Networks | 1         | 0.08%   |
| Digital Equipment                 | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |
| AVM                               | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 282       | 19.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51        | 3.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 2.95%   |
| Intel Wi-Fi 6 AX200                                               | 34        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 32        | 2.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 1.99%   |
| Intel Wireless 8265 / 8275                                        | 26        | 1.79%   |
| Intel I211 Gigabit Network Connection                             | 26        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 24        | 1.65%   |
| Intel Wireless 3165                                               | 24        | 1.65%   |
| Intel Wireless 7265                                               | 22        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 22        | 1.51%   |
| Intel Wireless 8260                                               | 21        | 1.44%   |
| Intel Wireless 7260                                               | 20        | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 18        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 1.17%   |
| Intel Ethernet Controller I225-V                                  | 16        | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 1.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 14        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 14        | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 12        | 0.82%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 11        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 10        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.69%   |
| Intel Wireless 3160                                               | 9         | 0.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.62%   |
| Intel Centrino Wireless-N 2230                                    | 9         | 0.62%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 9         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 342       | 48.86%  |
| Qualcomm Atheros                | 128       | 18.29%  |
| Realtek Semiconductor           | 103       | 14.71%  |
| Broadcom                        | 45        | 6.43%   |
| Broadcom Limited                | 18        | 2.57%   |
| Ralink Technology               | 15        | 2.14%   |
| TP-Link                         | 7         | 1%      |
| Ralink                          | 7         | 1%      |
| ASUSTek Computer                | 6         | 0.86%   |
| Microsoft                       | 5         | 0.71%   |
| Marvell Technology Group        | 5         | 0.71%   |
| Dell                            | 5         | 0.71%   |
| Qualcomm Atheros Communications | 4         | 0.57%   |
| Edimax Technology               | 3         | 0.43%   |
| D-Link                          | 2         | 0.29%   |
| Sierra Wireless                 | 1         | 0.14%   |
| Micro Star International        | 1         | 0.14%   |
| MediaTek                        | 1         | 0.14%   |
| D-Link System                   | 1         | 0.14%   |
| AVM                             | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 34        | 4.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 32        | 4.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 4.11%   |
| Intel Wireless 8265 / 8275                                     | 26        | 3.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 3.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24        | 3.4%    |
| Intel Wireless 3165                                            | 24        | 3.4%    |
| Intel Wireless 7265                                            | 22        | 3.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 3.12%   |
| Intel Wireless 8260                                            | 21        | 2.98%   |
| Intel Wireless 7260                                            | 20        | 2.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 18        | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17        | 2.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 2.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 14        | 1.99%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 1.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 12        | 1.7%    |
| Intel Wi-Fi 6 AX201                                            | 12        | 1.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 1.42%   |
| Intel Wireless 3160                                            | 9         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.28%   |
| Intel Centrino Wireless-N 2230                                 | 9         | 1.28%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 8         | 1.13%   |
| Intel Wireless-AC 9260                                         | 7         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 0.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 5         | 0.71%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.71%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 5         | 0.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 4         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 364       | 50.84%  |
| Intel                    | 242       | 33.8%   |
| Qualcomm Atheros         | 41        | 5.73%   |
| Broadcom                 | 25        | 3.49%   |
| Aquantia                 | 9         | 1.26%   |
| ASIX Electronics         | 5         | 0.7%    |
| Broadcom Limited         | 4         | 0.56%   |
| Xiaomi                   | 3         | 0.42%   |
| Samsung Electronics      | 3         | 0.42%   |
| DisplayLink              | 3         | 0.42%   |
| Apple                    | 3         | 0.42%   |
| TP-Link                  | 2         | 0.28%   |
| Microsoft                | 2         | 0.28%   |
| HMD Global               | 2         | 0.28%   |
| QinHeng Electronics      | 1         | 0.14%   |
| MediaTek                 | 1         | 0.14%   |
| Marvell Technology Group | 1         | 0.14%   |
| JMicron Technology       | 1         | 0.14%   |
| ICS Advent               | 1         | 0.14%   |
| Huawei Technologies      | 1         | 0.14%   |
| Hewlett-Packard          | 1         | 0.14%   |
| Google                   | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 282       | 38.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 51        | 6.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 5.84%   |
| Intel I211 Gigabit Network Connection                             | 26        | 3.53%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 2.58%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 2.58%   |
| Intel Ethernet Controller I225-V                                  | 16        | 2.17%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 1.77%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 1.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 1.36%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9         | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.54%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.54%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 4         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.41%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.41%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 684       | 50.48%  |
| WiFi     | 656       | 48.41%  |
| Modem    | 10        | 0.74%   |
| Unknown  | 5         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 477       | 55.27%  |
| Ethernet | 386       | 44.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 443       | 52.68%  |
| 1     | 341       | 40.55%  |
| 3     | 30        | 3.57%   |
| 0     | 20        | 2.38%   |
| 4     | 4         | 0.48%   |
| 5     | 3         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 722       | 85.75%  |
| Yes  | 120       | 14.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 300       | 52.08%  |
| Qualcomm Atheros Communications | 59        | 10.24%  |
| Realtek Semiconductor           | 51        | 8.85%   |
| Cambridge Silicon Radio         | 29        | 5.03%   |
| Apple                           | 27        | 4.69%   |
| Broadcom                        | 24        | 4.17%   |
| Lite-On Technology              | 20        | 3.47%   |
| IMC Networks                    | 18        | 3.13%   |
| Foxconn / Hon Hai               | 14        | 2.43%   |
| ASUSTek Computer                | 7         | 1.22%   |
| Marvell Semiconductor           | 6         | 1.04%   |
| Realtek                         | 3         | 0.52%   |
| Hewlett-Packard                 | 3         | 0.52%   |
| Foxconn International           | 3         | 0.52%   |
| Toshiba                         | 2         | 0.35%   |
| Ralink                          | 2         | 0.35%   |
| HTC (High Tech Computer)        | 2         | 0.35%   |
| TP-Link                         | 1         | 0.17%   |
| Micro Star International        | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |
| Creative Technology             | 1         | 0.17%   |
| Belkin Components               | 1         | 0.17%   |
| Alps Electric                   | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 126       | 21.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 61        | 10.59%  |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 6.94%   |
| Intel AX201 Bluetooth                               | 39        | 6.77%   |
| Intel AX200 Bluetooth                               | 33        | 5.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29        | 5.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 3.99%   |
| Realtek Bluetooth Radio                             | 23        | 3.99%   |
| Apple Bluetooth Host Controller                     | 16        | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 2.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 1.91%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.56%   |
| Apple Bluetooth USB Host Controller                 | 9         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 1.39%   |
| Intel AX210 Bluetooth                               | 7         | 1.22%   |
| IMC Networks Bluetooth Device                       | 7         | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.04%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.87%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.69%   |
| Marvell Bluetooth and Wireless LAN Composite        | 4         | 0.69%   |
| Lite-On Bluetooth Device                            | 4         | 0.69%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.69%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.52%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 3         | 0.52%   |
| Broadcom BCM20702A0                                 | 3         | 0.52%   |
| Toshiba BCM43142A0                                  | 2         | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.35%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.35%   |
| Realtek Bluetooth Radio                             | 2         | 0.35%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.35%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.35%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 685       | 58.95%  |
| Nvidia                               | 199       | 17.13%  |
| AMD                                  | 174       | 14.97%  |
| C-Media Electronics                  | 16        | 1.38%   |
| Logitech                             | 9         | 0.77%   |
| ASUSTek Computer                     | 9         | 0.77%   |
| SteelSeries ApS                      | 4         | 0.34%   |
| JMTek                                | 4         | 0.34%   |
| Creative Technology                  | 4         | 0.34%   |
| ASRock                               | 4         | 0.34%   |
| Micro Star International             | 3         | 0.26%   |
| KORG                                 | 3         | 0.26%   |
| Creative Labs                        | 3         | 0.26%   |
| Corsair                              | 3         | 0.26%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.17%   |
| Sennheiser Communications            | 2         | 0.17%   |
| Realtek Semiconductor                | 2         | 0.17%   |
| Plantronics                          | 2         | 0.17%   |
| JBL                                  | 2         | 0.17%   |
| Generalplus Technology               | 2         | 0.17%   |
| Blue Microphones                     | 2         | 0.17%   |
| Yamaha                               | 1         | 0.09%   |
| VIA Technologies                     | 1         | 0.09%   |
| Turtle Beach                         | 1         | 0.09%   |
| Texas Instruments                    | 1         | 0.09%   |
| TEAC                                 | 1         | 0.09%   |
| Schiit Audio                         | 1         | 0.09%   |
| Samsung Electronics                  | 1         | 0.09%   |
| PreSonus Audio Electronics           | 1         | 0.09%   |
| MAG Technology                       | 1         | 0.09%   |
| Kingston Technology                  | 1         | 0.09%   |
| HECATE G30 GAMING HEADSET            | 1         | 0.09%   |
| GYROCOM C&C                          | 1         | 0.09%   |
| Guillemot                            | 1         | 0.09%   |
| GN Netcom                            | 1         | 0.09%   |
| Giga-Byte Technology                 | 1         | 0.09%   |
| Focusrite-Novation                   | 1         | 0.09%   |
| Dell                                 | 1         | 0.09%   |
| Cooler Master                        | 1         | 0.09%   |
| Conexant Systems                     | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 88        | 6.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 86        | 6.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 54        | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 49        | 3.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 45        | 3.35%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 2.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 39        | 2.91%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 36        | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 34        | 2.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 30        | 2.24%   |
| Intel Broadwell-U Audio Controller                                                                | 30        | 2.24%   |
| Intel 8 Series HD Audio Controller                                                                | 30        | 2.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 29        | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 26        | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 1.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 24        | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 1.71%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 22        | 1.64%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 21        | 1.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 20        | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 1.42%   |
| Intel CM238 HD Audio Controller                                                                   | 19        | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 18        | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 17        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 17        | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 13        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 11        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 10        | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 10        | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 0.6%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 8         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 8         | 26.67%  |
| Samsung Electronics | 5         | 16.67%  |
| Corsair             | 5         | 16.67%  |
| Unknown             | 4         | 13.33%  |
| Micron Technology   | 2         | 6.67%   |
| Goldkey             | 2         | 6.67%   |
| Crucial             | 2         | 6.67%   |
| Kingston            | 1         | 3.33%   |
| A-DATA Technology   | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Goldkey RAM GKH400SO51208-1333 4GB DIMM DDR3 1333MT/s            | 2         | 6.45%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 3.23%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                   | 1         | 3.23%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 3.23%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s        | 1         | 3.23%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 3.23%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 3.23%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 3.23%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 3.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 3.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 3.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 3.23%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.23%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 3.23%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 3.23%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 1         | 3.23%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 3.23%   |
| Samsung RAM M471A2G44AM0-CTD 16GB Row Of Chips DDR4 2667MT/s     | 1         | 3.23%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 3.23%   |
| Micron RAM MT53E512M32D2NP 1GB LPDDR4 3733MT/s                   | 1         | 3.23%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1         | 3.23%   |
| Kingston RAM 99U5428-101.A00LF 8GB DIMM DDR3 1600MT/s            | 1         | 3.23%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s            | 1         | 3.23%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2667MT/s        | 1         | 3.23%   |
| Corsair RAM CMY32GX3M4A1600C9 8192MB DIMM DDR3 1600MT/s          | 1         | 3.23%   |
| Corsair RAM CMSX16GX4M1A2400C16 16GB SODIMM DDR4 2400MT/s        | 1         | 3.23%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 1         | 3.23%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s            | 1         | 3.23%   |
| Corsair RAM CM4X16GC3000C15K4 16GB DIMM DDR4 3000MT/s            | 1         | 3.23%   |
| A-DATA RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 42.86%  |
| DDR3   | 12        | 42.86%  |
| LPDDR3 | 2         | 7.14%   |
| SDRAM  | 1         | 3.57%   |
| LPDDR4 | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 48.15%  |
| DIMM         | 10        | 37.04%  |
| Row Of Chips | 3         | 11.11%  |
| Unknown      | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 35.71%  |
| 4096  | 10        | 35.71%  |
| 16384 | 6         | 21.43%  |
| 2048  | 2         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 8         | 26.67%  |
| 2667  | 5         | 16.67%  |
| 2400  | 3         | 10%     |
| 1333  | 3         | 10%     |
| 4199  | 1         | 3.33%   |
| 3733  | 1         | 3.33%   |
| 3466  | 1         | 3.33%   |
| 3200  | 1         | 3.33%   |
| 3000  | 1         | 3.33%   |
| 2933  | 1         | 3.33%   |
| 2800  | 1         | 3.33%   |
| 2133  | 1         | 3.33%   |
| 1867  | 1         | 3.33%   |
| 1800  | 1         | 3.33%   |
| 1334  | 1         | 3.33%   |

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
| Seiko Epson L222 Series              | 2         | 7.14%   |
| Seiko Epson L355 Series              | 1         | 3.57%   |
| Seiko Epson L3150 Series             | 1         | 3.57%   |
| Samsung SCX-4216F Scanner            | 1         | 3.57%   |
| Samsung SCX-4200 series              | 1         | 3.57%   |
| Samsung ML-1640 Series Laser Printer | 1         | 3.57%   |
| Ricoh Printing Support               | 1         | 3.57%   |
| MIIIW MW Keyboard Air Mini           | 1         | 3.57%   |
| Kyocera FS-1030D printer             | 1         | 3.57%   |
| HP LaserJet 1200                     | 1         | 3.57%   |
| HP Laser 107w                        | 1         | 3.57%   |
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
| Chicony Electronics                    | 107       | 22.29%  |
| Realtek Semiconductor                  | 47        | 9.79%   |
| Microdia                               | 43        | 8.96%   |
| IMC Networks                           | 38        | 7.92%   |
| Sunplus Innovation Technology          | 29        | 6.04%   |
| Acer                                   | 24        | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 21        | 4.38%   |
| Apple                                  | 20        | 4.17%   |
| Quanta                                 | 19        | 3.96%   |
| Logitech                               | 19        | 3.96%   |
| Bison Electronics                      | 14        | 2.92%   |
| Suyin                                  | 13        | 2.71%   |
| Silicon Motion                         | 10        | 2.08%   |
| Alcor Micro                            | 10        | 2.08%   |
| Syntek                                 | 9         | 1.88%   |
| Microsoft                              | 9         | 1.88%   |
| Lite-On Technology                     | 6         | 1.25%   |
| Samsung Electronics                    | 5         | 1.04%   |
| Luxvisions Innotech Limited            | 3         | 0.63%   |
| KYE Systems (Mouse Systems)            | 3         | 0.63%   |
| ARC International                      | 3         | 0.63%   |
| Z-Star Microelectronics                | 2         | 0.42%   |
| Unknown                                | 2         | 0.42%   |
| Ricoh                                  | 2         | 0.42%   |
| Hewlett-Packard                        | 2         | 0.42%   |
| Creative Technology                    | 2         | 0.42%   |
| YGTek                                  | 1         | 0.21%   |
| Y Media                                | 1         | 0.21%   |
| Xiaomi                                 | 1         | 0.21%   |
| Tobii Technology AB                    | 1         | 0.21%   |
| Spreadtrum Communications              | 1         | 0.21%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| Magic Control Technology               | 1         | 0.21%   |
| Lenovo                                 | 1         | 0.21%   |
| Importek                               | 1         | 0.21%   |
| icSpring                               | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| Foxconn / Hon Hai                      | 1         | 0.21%   |
| Denron                                 | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 25        | 5.13%   |
| Chicony HD WebCam                                | 17        | 3.49%   |
| Chicony Integrated Camera                        | 16        | 3.29%   |
| Realtek Integrated_Webcam_HD                     | 14        | 2.87%   |
| IMC Networks USB2.0 HD UVC WebCam                | 11        | 2.26%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 10        | 2.05%   |
| Sunplus HD WebCam                                | 8         | 1.64%   |
| Apple FaceTime HD Camera                         | 8         | 1.64%   |
| Logitech Webcam C270                             | 7         | 1.44%   |
| Chicony USB2.0 VGA UVC WebCam                    | 7         | 1.44%   |
| Apple FaceTime HD Camera (Built-in)              | 7         | 1.44%   |
| Suyin HP TrueVision HD                           | 5         | 1.03%   |
| Samsung Galaxy series, misc. (MTP mode)          | 5         | 1.03%   |
| Realtek Lenovo EasyCamera                        | 5         | 1.03%   |
| Quanta HD Webcam                                 | 5         | 1.03%   |
| Chicony VGA Webcam                               | 5         | 1.03%   |
| Chicony Lenovo EasyCamera                        | 5         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 5         | 1.03%   |
| Bison Integrated Camera                          | 5         | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 5         | 1.03%   |
| Alcor Micro SHUNCCM2MP                           | 5         | 1.03%   |
| Acer HD Webcam                                   | 5         | 1.03%   |
| Acer EasyCamera                                  | 5         | 1.03%   |
| Syntek EasyCamera                                | 4         | 0.82%   |
| Sunplus Integrated_Webcam_HD                     | 4         | 0.82%   |
| Microdia Laptop_Integrated_Webcam_HD             | 4         | 0.82%   |
| Logitech HD Pro Webcam C920                      | 4         | 0.82%   |
| Lite-On Integrated Camera                        | 4         | 0.82%   |
| IMC Networks Integrated Camera                   | 4         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam                     | 4         | 0.82%   |
| Chicony USB 2.0 Camera                           | 4         | 0.82%   |
| Alcor Micro USB 2.0 PC Camera                    | 4         | 0.82%   |
| Acer Lenovo EasyCamera                           | 4         | 0.82%   |
| Suyin HD WebCam                                  | 3         | 0.62%   |
| Realtek USB2.0 HD UVC WebCam                     | 3         | 0.62%   |
| Realtek HD WebCam                                | 3         | 0.62%   |
| Realtek Front Camera                             | 3         | 0.62%   |
| Quanta USB2.0 VGA UVC WebCam                     | 3         | 0.62%   |
| Microdia Integrated Webcam HD                    | 3         | 0.62%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 22        | 37.29%  |
| Synaptics                  | 12        | 20.34%  |
| Elan Microelectronics      | 6         | 10.17%  |
| Shenzhen Goodix Technology | 5         | 8.47%   |
| AuthenTec                  | 5         | 8.47%   |
| LighTuning Technology      | 4         | 6.78%   |
| Upek                       | 3         | 5.08%   |
| Samsung Electronics        | 2         | 3.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 10.17%  |
| Elan ELAN:Fingerprint                                                      | 6         | 10.17%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 8.47%   |
| Synaptics UWP WBDI                                                         | 4         | 6.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 5.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 5.08%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 5.08%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 5.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.39%   |
| Validity Sensors VFS491                                                    | 2         | 3.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.39%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 3.39%   |
| Samsung Fingerprint Device                                                 | 2         | 3.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.39%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.69%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.69%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.69%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 1.69%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.69%   |
| Synaptics  WBDI                                                            | 1         | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.69%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.69%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.69%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 12        | 48%     |
| Upek                       | 4         | 16%     |
| Alcor Micro                | 4         | 16%     |
| Lenovo                     | 1         | 4%      |
| Gemalto (was Gemplus)      | 1         | 4%      |
| Athena Smartcard Solutions | 1         | 4%      |
| Aladdin Knowledge Systems  | 1         | 4%      |
| Advanced Card Systems      | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 24%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 16%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 16%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8%      |
| Broadcom 5880                                                                | 2         | 8%      |
| Broadcom 58200                                                               | 2         | 8%      |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 4%      |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 4%      |
| Aladdin Knowledge Systems Token JC                                           | 1         | 4%      |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 556       | 65.26%  |
| 1     | 243       | 28.52%  |
| 2     | 47        | 5.52%   |
| 3     | 6         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 64        | 17.88%  |
| Net/wireless             | 62        | 17.32%  |
| Fingerprint reader       | 59        | 16.48%  |
| Multimedia controller    | 37        | 10.34%  |
| Firewire controller      | 34        | 9.5%    |
| Chipcard                 | 25        | 6.98%   |
| Net/ethernet             | 14        | 3.91%   |
| Unassigned class         | 11        | 3.07%   |
| Sound                    | 11        | 3.07%   |
| Camera                   | 10        | 2.79%   |
| Storage/ide              | 9         | 2.51%   |
| Communication controller | 8         | 2.23%   |
| Bluetooth                | 4         | 1.12%   |
| Network                  | 3         | 0.84%   |
| Storage/nvme             | 2         | 0.56%   |
| Storage                  | 2         | 0.56%   |
| Modem                    | 2         | 0.56%   |
| Card reader              | 1         | 0.28%   |

