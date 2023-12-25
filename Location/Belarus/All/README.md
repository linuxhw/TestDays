Linux in Belarus - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belarus/Desktop/README.md) and [notebooks](/Location/Belarus/Notebook/README.md).

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

Total: 1733

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | System XPS L702X            | Notebook    | [d69355a342](https://linux-hardware.org/?probe=d69355a342) | Dec 23, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [82a8bc3c6e](https://linux-hardware.org/?probe=82a8bc3c6e) | Dec 21, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [4aeb75b734](https://linux-hardware.org/?probe=4aeb75b734) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [812cd1effd](https://linux-hardware.org/?probe=812cd1effd) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [8fc6a74916](https://linux-hardware.org/?probe=8fc6a74916) | Dec 15, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [885e6000e2](https://linux-hardware.org/?probe=885e6000e2) | Dec 12, 2023 |
| ASUSTek       | X550VB                      | Notebook    | [cfc8172838](https://linux-hardware.org/?probe=cfc8172838) | Dec 11, 2023 |
| HP            | ProBook 4535s               | Notebook    | [9005c587a8](https://linux-hardware.org/?probe=9005c587a8) | Dec 10, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [f87c61387d](https://linux-hardware.org/?probe=f87c61387d) | Dec 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4d14243cb9](https://linux-hardware.org/?probe=4d14243cb9) | Dec 05, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [376ffad1f1](https://linux-hardware.org/?probe=376ffad1f1) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L7001SM... | Notebook    | [da99e083aa](https://linux-hardware.org/?probe=da99e083aa) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [deba3c2073](https://linux-hardware.org/?probe=deba3c2073) | Nov 30, 2023 |
| Dell          | 0PGMR1 A00                  | All in one  | [aaca525c1a](https://linux-hardware.org/?probe=aaca525c1a) | Nov 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [184a3ca616](https://linux-hardware.org/?probe=184a3ca616) | Nov 28, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [b74cd41faf](https://linux-hardware.org/?probe=b74cd41faf) | Nov 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7084bb6ef8](https://linux-hardware.org/?probe=7084bb6ef8) | Nov 26, 2023 |
| HP            | ProBook 6460b               | Notebook    | [d489496b9f](https://linux-hardware.org/?probe=d489496b9f) | Nov 26, 2023 |
| Biostar       | H61MLV2                     | Desktop     | [1e2b4c3878](https://linux-hardware.org/?probe=1e2b4c3878) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b84a63677](https://linux-hardware.org/?probe=2b84a63677) | Nov 26, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1bb4c56d2b](https://linux-hardware.org/?probe=1bb4c56d2b) | Nov 24, 2023 |
| HP            | ProBook 6460b               | Notebook    | [0d13c42c84](https://linux-hardware.org/?probe=0d13c42c84) | Nov 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [93c68a0d33](https://linux-hardware.org/?probe=93c68a0d33) | Nov 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [743037d313](https://linux-hardware.org/?probe=743037d313) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cd775f0d29](https://linux-hardware.org/?probe=cd775f0d29) | Nov 18, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [a6742c43a4](https://linux-hardware.org/?probe=a6742c43a4) | Nov 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6461e4f7af](https://linux-hardware.org/?probe=6461e4f7af) | Nov 16, 2023 |
| HP            | ProBook 6460b               | Notebook    | [b0795caa4c](https://linux-hardware.org/?probe=b0795caa4c) | Nov 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [06cd45bab5](https://linux-hardware.org/?probe=06cd45bab5) | Nov 15, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [1cffd5036c](https://linux-hardware.org/?probe=1cffd5036c) | Nov 14, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [4d8ebb0232](https://linux-hardware.org/?probe=4d8ebb0232) | Nov 13, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [c648b2a80e](https://linux-hardware.org/?probe=c648b2a80e) | Nov 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c34342b820](https://linux-hardware.org/?probe=c34342b820) | Nov 10, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [5fb8105768](https://linux-hardware.org/?probe=5fb8105768) | Nov 10, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d0570de821](https://linux-hardware.org/?probe=d0570de821) | Nov 06, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29f3c0c25f](https://linux-hardware.org/?probe=29f3c0c25f) | Nov 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Khadas        | VIM3                        | Soc         | [701bf2eba1](https://linux-hardware.org/?probe=701bf2eba1) | Oct 31, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [c35ab1031d](https://linux-hardware.org/?probe=c35ab1031d) | Oct 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [265d52a042](https://linux-hardware.org/?probe=265d52a042) | Oct 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [ee5373bbe1](https://linux-hardware.org/?probe=ee5373bbe1) | Oct 28, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8432e79c8](https://linux-hardware.org/?probe=e8432e79c8) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [47d1cb500e](https://linux-hardware.org/?probe=47d1cb500e) | Oct 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA            | Notebook    | [f321493adb](https://linux-hardware.org/?probe=f321493adb) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| Timi          | TM1701                      | Notebook    | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bd850cfed3](https://linux-hardware.org/?probe=bd850cfed3) | Oct 24, 2023 |
| Dell          | Latitude D830               | Notebook    | [53cbc541d2](https://linux-hardware.org/?probe=53cbc541d2) | Oct 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | Notebook    | [36c49585ba](https://linux-hardware.org/?probe=36c49585ba) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [6827d26220](https://linux-hardware.org/?probe=6827d26220) | Oct 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [cf096a11b6](https://linux-hardware.org/?probe=cf096a11b6) | Oct 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [908a750a93](https://linux-hardware.org/?probe=908a750a93) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [10b2d6465f](https://linux-hardware.org/?probe=10b2d6465f) | Oct 10, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [01bfe733f2](https://linux-hardware.org/?probe=01bfe733f2) | Oct 10, 2023 |
| HP            | 650                         | Notebook    | [1339361633](https://linux-hardware.org/?probe=1339361633) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [c237b78f41](https://linux-hardware.org/?probe=c237b78f41) | Oct 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [76449d7977](https://linux-hardware.org/?probe=76449d7977) | Oct 06, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [1a20748a43](https://linux-hardware.org/?probe=1a20748a43) | Oct 06, 2023 |
| HP            | EliteBook 1050 G1           | Notebook    | [d5d3dd5136](https://linux-hardware.org/?probe=d5d3dd5136) | Oct 05, 2023 |
| Biostar       | H510MHP                     | Desktop     | [f562c8f7d7](https://linux-hardware.org/?probe=f562c8f7d7) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [46e4809bfe](https://linux-hardware.org/?probe=46e4809bfe) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [db7fa034a7](https://linux-hardware.org/?probe=db7fa034a7) | Oct 03, 2023 |
| HP            | 650                         | Notebook    | [f652e189f9](https://linux-hardware.org/?probe=f652e189f9) | Oct 03, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [5967be8309](https://linux-hardware.org/?probe=5967be8309) | Oct 03, 2023 |
| HP            | Compaq 610                  | Notebook    | [9570db13af](https://linux-hardware.org/?probe=9570db13af) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| Google        | Eve                         | Convertible | [b3c890ec7a](https://linux-hardware.org/?probe=b3c890ec7a) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| Google        | Eve                         | Convertible | [eccabb6bc2](https://linux-hardware.org/?probe=eccabb6bc2) | Sep 24, 2023 |
| Olimex        | A20-OLinuXino-LIME2         | Soc         | [b2c0e79757](https://linux-hardware.org/?probe=b2c0e79757) | Sep 22, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [6dfb722e45](https://linux-hardware.org/?probe=6dfb722e45) | Sep 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [2e715ca7b2](https://linux-hardware.org/?probe=2e715ca7b2) | Sep 22, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [63bebc9690](https://linux-hardware.org/?probe=63bebc9690) | Sep 20, 2023 |
| ASUSTek       | K72Dr                       | Notebook    | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [8d0117a5f3](https://linux-hardware.org/?probe=8d0117a5f3) | Sep 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [418eee8ea7](https://linux-hardware.org/?probe=418eee8ea7) | Sep 13, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [cdeced49b1](https://linux-hardware.org/?probe=cdeced49b1) | Sep 12, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [f588051436](https://linux-hardware.org/?probe=f588051436) | Sep 11, 2023 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [c83c0f03aa](https://linux-hardware.org/?probe=c83c0f03aa) | Sep 11, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8717619604](https://linux-hardware.org/?probe=8717619604) | Sep 11, 2023 |
| ECS           | A960M-M3                    | Desktop     | [70ee5683a4](https://linux-hardware.org/?probe=70ee5683a4) | Sep 11, 2023 |
| Dell          | Latitude 3410               | Notebook    | [c1c98adb51](https://linux-hardware.org/?probe=c1c98adb51) | Sep 10, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [f096164a16](https://linux-hardware.org/?probe=f096164a16) | Sep 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [63dae39236](https://linux-hardware.org/?probe=63dae39236) | Sep 08, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [3fb594ab96](https://linux-hardware.org/?probe=3fb594ab96) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [f2df6b2c70](https://linux-hardware.org/?probe=f2df6b2c70) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [63fd300645](https://linux-hardware.org/?probe=63fd300645) | Sep 07, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [d630819b59](https://linux-hardware.org/?probe=d630819b59) | Sep 05, 2023 |
| Gigabyte      | P55M-UD4                    | Desktop     | [d04a4aef90](https://linux-hardware.org/?probe=d04a4aef90) | Sep 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e04761c470](https://linux-hardware.org/?probe=e04761c470) | Sep 03, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d714ef63c2](https://linux-hardware.org/?probe=d714ef63c2) | Sep 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [f6996b2905](https://linux-hardware.org/?probe=f6996b2905) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [4e753f77c7](https://linux-hardware.org/?probe=4e753f77c7) | Sep 01, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [04492867e2](https://linux-hardware.org/?probe=04492867e2) | Aug 31, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e3eb4b9ef5](https://linux-hardware.org/?probe=e3eb4b9ef5) | Aug 31, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f8906dfb9c](https://linux-hardware.org/?probe=f8906dfb9c) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [8ed8031a41](https://linux-hardware.org/?probe=8ed8031a41) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [3d2effa8c5](https://linux-hardware.org/?probe=3d2effa8c5) | Aug 27, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c326205a9b](https://linux-hardware.org/?probe=c326205a9b) | Aug 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1538d66b38](https://linux-hardware.org/?probe=1538d66b38) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dd9b3b469e](https://linux-hardware.org/?probe=dd9b3b469e) | Aug 15, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [878209b83a](https://linux-hardware.org/?probe=878209b83a) | Aug 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [0482630783](https://linux-hardware.org/?probe=0482630783) | Aug 05, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [2a54f1c8ce](https://linux-hardware.org/?probe=2a54f1c8ce) | Aug 04, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| ASUSTek       | GL503VD                     | Notebook    | [4c3516813b](https://linux-hardware.org/?probe=4c3516813b) | Jul 28, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [cf57b5785a](https://linux-hardware.org/?probe=cf57b5785a) | Jul 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| HP            | ProBook 4545s               | Notebook    | [cf43675118](https://linux-hardware.org/?probe=cf43675118) | Jul 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [7e6c1d1018](https://linux-hardware.org/?probe=7e6c1d1018) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [584f2a2ac4](https://linux-hardware.org/?probe=584f2a2ac4) | Jul 13, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [6456f7b16f](https://linux-hardware.org/?probe=6456f7b16f) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [33a8b4ab02](https://linux-hardware.org/?probe=33a8b4ab02) | Jul 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [dfb0bd07f1](https://linux-hardware.org/?probe=dfb0bd07f1) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [d33df8d1a0](https://linux-hardware.org/?probe=d33df8d1a0) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [5b11b41272](https://linux-hardware.org/?probe=5b11b41272) | Jul 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [37239831de](https://linux-hardware.org/?probe=37239831de) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| HP            | 255 G1                      | Notebook    | [f09174c096](https://linux-hardware.org/?probe=f09174c096) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e26b3e6d58](https://linux-hardware.org/?probe=e26b3e6d58) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [0b6bb0a043](https://linux-hardware.org/?probe=0b6bb0a043) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [50626f77d7](https://linux-hardware.org/?probe=50626f77d7) | Jun 18, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| Sony          | SVF1521L1RB                 | Notebook    | [b0dfbb64d0](https://linux-hardware.org/?probe=b0dfbb64d0) | Jun 17, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c7460aff4f](https://linux-hardware.org/?probe=c7460aff4f) | Jun 16, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [129574e8dc](https://linux-hardware.org/?probe=129574e8dc) | Jun 14, 2023 |
| HP            | 255 G1                      | Notebook    | [a8c4597ccd](https://linux-hardware.org/?probe=a8c4597ccd) | Jun 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [704cc1c02b](https://linux-hardware.org/?probe=704cc1c02b) | Jun 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c8ca6e8787](https://linux-hardware.org/?probe=c8ca6e8787) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [320e5bee32](https://linux-hardware.org/?probe=320e5bee32) | Jun 04, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1e23f3e627](https://linux-hardware.org/?probe=1e23f3e627) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [960ddf4eaf](https://linux-hardware.org/?probe=960ddf4eaf) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [eb644c96f3](https://linux-hardware.org/?probe=eb644c96f3) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [94c7ddea69](https://linux-hardware.org/?probe=94c7ddea69) | May 21, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [653f6e9a8e](https://linux-hardware.org/?probe=653f6e9a8e) | May 20, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [04dac52364](https://linux-hardware.org/?probe=04dac52364) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| MSI           | GE72 7RE                    | Notebook    | [15a31e188f](https://linux-hardware.org/?probe=15a31e188f) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6e519b78e9](https://linux-hardware.org/?probe=6e519b78e9) | May 17, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [03b576ccc8](https://linux-hardware.org/?probe=03b576ccc8) | May 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5a28a0c505](https://linux-hardware.org/?probe=5a28a0c505) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [32b3c782ff](https://linux-hardware.org/?probe=32b3c782ff) | May 11, 2023 |
| Dell          | 0Y958C A00                  | Desktop     | [fb1b987ad5](https://linux-hardware.org/?probe=fb1b987ad5) | May 10, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [169b0a5bc0](https://linux-hardware.org/?probe=169b0a5bc0) | May 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fe4b074a5c](https://linux-hardware.org/?probe=fe4b074a5c) | May 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [5a21b5acb8](https://linux-hardware.org/?probe=5a21b5acb8) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [c11c9964fa](https://linux-hardware.org/?probe=c11c9964fa) | Apr 27, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [8bca3fa04b](https://linux-hardware.org/?probe=8bca3fa04b) | Apr 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [94bd5fe556](https://linux-hardware.org/?probe=94bd5fe556) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [50c44b15eb](https://linux-hardware.org/?probe=50c44b15eb) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [9cb44b75f5](https://linux-hardware.org/?probe=9cb44b75f5) | Apr 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9f5fa03bfd](https://linux-hardware.org/?probe=9f5fa03bfd) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [f87a34e474](https://linux-hardware.org/?probe=f87a34e474) | Apr 19, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [84dbb8ae74](https://linux-hardware.org/?probe=84dbb8ae74) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [9cacd6f238](https://linux-hardware.org/?probe=9cacd6f238) | Apr 19, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [733d7d5584](https://linux-hardware.org/?probe=733d7d5584) | Apr 18, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [a02f8565dd](https://linux-hardware.org/?probe=a02f8565dd) | Apr 14, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [5ecb1bb650](https://linux-hardware.org/?probe=5ecb1bb650) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [5c23d1d7f7](https://linux-hardware.org/?probe=5c23d1d7f7) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [be2a3d30f2](https://linux-hardware.org/?probe=be2a3d30f2) | Apr 08, 2023 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [71c25d2dce](https://linux-hardware.org/?probe=71c25d2dce) | Apr 07, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [ca3f0771ce](https://linux-hardware.org/?probe=ca3f0771ce) | Apr 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [24ac3864d2](https://linux-hardware.org/?probe=24ac3864d2) | Apr 04, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [1789a17694](https://linux-hardware.org/?probe=1789a17694) | Apr 03, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [cc5feeb3eb](https://linux-hardware.org/?probe=cc5feeb3eb) | Apr 03, 2023 |
| Biostar       | B365MHC                     | Desktop     | [95107f0e65](https://linux-hardware.org/?probe=95107f0e65) | Apr 02, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [6dafdf20a5](https://linux-hardware.org/?probe=6dafdf20a5) | Apr 02, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [f811a203a0](https://linux-hardware.org/?probe=f811a203a0) | Apr 02, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [51f6d77f50](https://linux-hardware.org/?probe=51f6d77f50) | Mar 30, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [e5433e75fb](https://linux-hardware.org/?probe=e5433e75fb) | Mar 29, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | Desktop     | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| Dell          | System XPS L702X            | Notebook    | [2c8aed8334](https://linux-hardware.org/?probe=2c8aed8334) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| HP            | Notebook                    | Notebook    | [f18d14ac70](https://linux-hardware.org/?probe=f18d14ac70) | Mar 28, 2023 |
| HP            | 250 G1                      | Notebook    | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [4c0751aa89](https://linux-hardware.org/?probe=4c0751aa89) | Mar 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6ae381093b](https://linux-hardware.org/?probe=6ae381093b) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| Getac         | B300-H                      | Notebook    | [28a9b0b0c7](https://linux-hardware.org/?probe=28a9b0b0c7) | Mar 25, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c4b7067187](https://linux-hardware.org/?probe=c4b7067187) | Mar 24, 2023 |
| Iskratel, ... | IN6011AX                    | Desktop     | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [8023b22765](https://linux-hardware.org/?probe=8023b22765) | Mar 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [5e9cf8fb44](https://linux-hardware.org/?probe=5e9cf8fb44) | Mar 22, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [7d8950b25b](https://linux-hardware.org/?probe=7d8950b25b) | Mar 21, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [c58012d73d](https://linux-hardware.org/?probe=c58012d73d) | Mar 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [43940eb778](https://linux-hardware.org/?probe=43940eb778) | Mar 20, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d42628a0e9](https://linux-hardware.org/?probe=d42628a0e9) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b5746d500d](https://linux-hardware.org/?probe=b5746d500d) | Mar 13, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [0e89d9279d](https://linux-hardware.org/?probe=0e89d9279d) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [8541575b10](https://linux-hardware.org/?probe=8541575b10) | Mar 12, 2023 |
| Intel         | JSL MRD                     | Desktop     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [249f986099](https://linux-hardware.org/?probe=249f986099) | Mar 09, 2023 |
| HP            | Compaq 610                  | Notebook    | [3f5ffc0582](https://linux-hardware.org/?probe=3f5ffc0582) | Mar 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [48dc89b146](https://linux-hardware.org/?probe=48dc89b146) | Mar 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [546d7b3f27](https://linux-hardware.org/?probe=546d7b3f27) | Mar 07, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [efd6fd1985](https://linux-hardware.org/?probe=efd6fd1985) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e682158c7f](https://linux-hardware.org/?probe=e682158c7f) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [268e27cc20](https://linux-hardware.org/?probe=268e27cc20) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [e8325b5ff1](https://linux-hardware.org/?probe=e8325b5ff1) | Mar 03, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [9cd0a2ea25](https://linux-hardware.org/?probe=9cd0a2ea25) | Mar 01, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [630c0e41b1](https://linux-hardware.org/?probe=630c0e41b1) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c85bd630f0](https://linux-hardware.org/?probe=c85bd630f0) | Feb 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [5b524ddbb0](https://linux-hardware.org/?probe=5b524ddbb0) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [9b00bf7704](https://linux-hardware.org/?probe=9b00bf7704) | Feb 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dc6a6f7872](https://linux-hardware.org/?probe=dc6a6f7872) | Feb 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [788044d53c](https://linux-hardware.org/?probe=788044d53c) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Partner       | S1-J1900                    | Desktop     | [0dd4327553](https://linux-hardware.org/?probe=0dd4327553) | Feb 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [faa600d8e5](https://linux-hardware.org/?probe=faa600d8e5) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dfa8cae135](https://linux-hardware.org/?probe=dfa8cae135) | Feb 17, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [3faff8d320](https://linux-hardware.org/?probe=3faff8d320) | Feb 17, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [44e18a0f72](https://linux-hardware.org/?probe=44e18a0f72) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [0da8e9ac4c](https://linux-hardware.org/?probe=0da8e9ac4c) | Feb 14, 2023 |
| Intel         | NUC7i3BNB J22859-316        | Mini pc     | [fc5fbe9d48](https://linux-hardware.org/?probe=fc5fbe9d48) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [5644272d9e](https://linux-hardware.org/?probe=5644272d9e) | Feb 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [a1549a7701](https://linux-hardware.org/?probe=a1549a7701) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Intel         | SKYBAY                      | Desktop     | [7f8e95e496](https://linux-hardware.org/?probe=7f8e95e496) | Feb 02, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASUSTek       | Z170M-E D3                  | Desktop     | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f94175d8c](https://linux-hardware.org/?probe=6f94175d8c) | Jan 28, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [add8440e16](https://linux-hardware.org/?probe=add8440e16) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f4e06ff0b2](https://linux-hardware.org/?probe=f4e06ff0b2) | Jan 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | Notebook    | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [7c116ff037](https://linux-hardware.org/?probe=7c116ff037) | Jan 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [4606ff1dab](https://linux-hardware.org/?probe=4606ff1dab) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [18654d5f58](https://linux-hardware.org/?probe=18654d5f58) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [43e346516e](https://linux-hardware.org/?probe=43e346516e) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [325952460c](https://linux-hardware.org/?probe=325952460c) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [ac63fca6cb](https://linux-hardware.org/?probe=ac63fca6cb) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d23fb14f2e](https://linux-hardware.org/?probe=d23fb14f2e) | Jan 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| MSI           | MS-7519                     | Desktop     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6f0f984312](https://linux-hardware.org/?probe=6f0f984312) | Dec 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d196b92cff](https://linux-hardware.org/?probe=d196b92cff) | Dec 27, 2022 |
| ASRock        | Brazos                      | Desktop     | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | Notebook    | [9f1751d2e5](https://linux-hardware.org/?probe=9f1751d2e5) | Dec 22, 2022 |
| Pegatron      | A17                         | Notebook    | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [077f863ca3](https://linux-hardware.org/?probe=077f863ca3) | Dec 15, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a096df53ed](https://linux-hardware.org/?probe=a096df53ed) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [fcd4a2d840](https://linux-hardware.org/?probe=fcd4a2d840) | Dec 11, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b463c25c4d](https://linux-hardware.org/?probe=b463c25c4d) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1c80b48ea0](https://linux-hardware.org/?probe=1c80b48ea0) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ad6dc99c8a](https://linux-hardware.org/?probe=ad6dc99c8a) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| HP            | 550                         | Notebook    | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c3f0c49c7c](https://linux-hardware.org/?probe=c3f0c49c7c) | Dec 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cb93839085](https://linux-hardware.org/?probe=cb93839085) | Dec 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2de79b83d5](https://linux-hardware.org/?probe=2de79b83d5) | Nov 28, 2022 |
| ASUSTek       | K70AB                       | Notebook    | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [09c253d548](https://linux-hardware.org/?probe=09c253d548) | Nov 07, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [9d1fda5ecb](https://linux-hardware.org/?probe=9d1fda5ecb) | Nov 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [77bdbb310f](https://linux-hardware.org/?probe=77bdbb310f) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [25003181f1](https://linux-hardware.org/?probe=25003181f1) | Oct 27, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2481764903](https://linux-hardware.org/?probe=2481764903) | Oct 27, 2022 |
| HP            | Compaq 610                  | Notebook    | [5adc7e0aba](https://linux-hardware.org/?probe=5adc7e0aba) | Oct 26, 2022 |
| HP            | Compaq 610                  | Notebook    | [9a584886fe](https://linux-hardware.org/?probe=9a584886fe) | Oct 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6e83c73646](https://linux-hardware.org/?probe=6e83c73646) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| ASUSTek       | T101MT                      | Notebook    | [d0fc7c3dae](https://linux-hardware.org/?probe=d0fc7c3dae) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [25e3064dd2](https://linux-hardware.org/?probe=25e3064dd2) | Sep 29, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [2935c5bedd](https://linux-hardware.org/?probe=2935c5bedd) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [372160583e](https://linux-hardware.org/?probe=372160583e) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a861ca9999](https://linux-hardware.org/?probe=a861ca9999) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [69cce160a1](https://linux-hardware.org/?probe=69cce160a1) | Sep 16, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8b8ba6c7f9](https://linux-hardware.org/?probe=8b8ba6c7f9) | Sep 05, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| HP            | Compaq 610                  | Notebook    | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | Notebook    | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Compaq 610                  | Notebook    | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [3decfcd64a](https://linux-hardware.org/?probe=3decfcd64a) | Aug 14, 2022 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Sony          | SVF1521L1RW                 | Notebook    | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [4b4e4d693e](https://linux-hardware.org/?probe=4b4e4d693e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [c8562d4bac](https://linux-hardware.org/?probe=c8562d4bac) | Jul 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e899f43a3f](https://linux-hardware.org/?probe=e899f43a3f) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [4e757278be](https://linux-hardware.org/?probe=4e757278be) | Jul 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [1ee2492f24](https://linux-hardware.org/?probe=1ee2492f24) | Jul 23, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [2d2a17094e](https://linux-hardware.org/?probe=2d2a17094e) | Jul 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [7142849ed0](https://linux-hardware.org/?probe=7142849ed0) | Jul 17, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [3f20ad2267](https://linux-hardware.org/?probe=3f20ad2267) | Jul 11, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [b7adccb849](https://linux-hardware.org/?probe=b7adccb849) | Jul 09, 2022 |
| Samsung       | 535U3C                      | Notebook    | [80b2b79e75](https://linux-hardware.org/?probe=80b2b79e75) | Jul 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| HP            | Compaq 610                  | Notebook    | [62287cff21](https://linux-hardware.org/?probe=62287cff21) | Jul 06, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [26cbd669e4](https://linux-hardware.org/?probe=26cbd669e4) | Jul 05, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [2fb330049e](https://linux-hardware.org/?probe=2fb330049e) | Jul 04, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [2b31833bfe](https://linux-hardware.org/?probe=2b31833bfe) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [06d4d79742](https://linux-hardware.org/?probe=06d4d79742) | Jul 01, 2022 |
| Biostar       | TA790GX 128M                | Desktop     | [c7021e0b8c](https://linux-hardware.org/?probe=c7021e0b8c) | Jul 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| Prestigio     | Multipad Visconte V         | Notebook    | [fd38a70070](https://linux-hardware.org/?probe=fd38a70070) | Jun 29, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [8cb88942e3](https://linux-hardware.org/?probe=8cb88942e3) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [e52ad13385](https://linux-hardware.org/?probe=e52ad13385) | Jun 25, 2022 |
| Getac         | B300-H                      | Notebook    | [ff8382e269](https://linux-hardware.org/?probe=ff8382e269) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Getac         | B300-H                      | Notebook    | [d0b0703736](https://linux-hardware.org/?probe=d0b0703736) | Jun 23, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [6dd752fab5](https://linux-hardware.org/?probe=6dd752fab5) | Jun 23, 2022 |
| Dell          | 0PGMR1 A00                  | All in one  | [bf057e65d8](https://linux-hardware.org/?probe=bf057e65d8) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [8e7a43f724](https://linux-hardware.org/?probe=8e7a43f724) | Jun 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [595e4c8656](https://linux-hardware.org/?probe=595e4c8656) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [0ee020dd5a](https://linux-hardware.org/?probe=0ee020dd5a) | Jun 09, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [e057e3b6d8](https://linux-hardware.org/?probe=e057e3b6d8) | Jun 07, 2022 |
| HP            | Mini 110-4100               | Notebook    | [62932d62d5](https://linux-hardware.org/?probe=62932d62d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd317d92a3](https://linux-hardware.org/?probe=dd317d92a3) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| ECS           | IC780M-A2                   | Desktop     | [135f0a4328](https://linux-hardware.org/?probe=135f0a4328) | May 21, 2022 |
| MSI           | MS-7309                     | Desktop     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2a916e3eb5](https://linux-hardware.org/?probe=2a916e3eb5) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [8926d96550](https://linux-hardware.org/?probe=8926d96550) | May 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [7fb6e94bab](https://linux-hardware.org/?probe=7fb6e94bab) | Apr 27, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ff5ff260a0](https://linux-hardware.org/?probe=ff5ff260a0) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | Desktop     | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ab464ae6a9](https://linux-hardware.org/?probe=ab464ae6a9) | Apr 15, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| ASUSTek       | X541NC                      | Notebook    | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [803a20d0cb](https://linux-hardware.org/?probe=803a20d0cb) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [ef7133f14a](https://linux-hardware.org/?probe=ef7133f14a) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [06883f214a](https://linux-hardware.org/?probe=06883f214a) | Mar 25, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a8e8d6dd5e](https://linux-hardware.org/?probe=a8e8d6dd5e) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [db687b8693](https://linux-hardware.org/?probe=db687b8693) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| ASRock        | FM2A55M-VG3                 | Desktop     | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [517ef58b87](https://linux-hardware.org/?probe=517ef58b87) | Mar 11, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [69fd2b147f](https://linux-hardware.org/?probe=69fd2b147f) | Mar 11, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [55ce4f1460](https://linux-hardware.org/?probe=55ce4f1460) | Mar 11, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [a6fc7b9f12](https://linux-hardware.org/?probe=a6fc7b9f12) | Mar 10, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [800bc08dbd](https://linux-hardware.org/?probe=800bc08dbd) | Mar 09, 2022 |
| HP            | Mini 110-4100               | Notebook    | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| HP            | 635                         | Notebook    | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [bdba90c583](https://linux-hardware.org/?probe=bdba90c583) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [39389b9ddf](https://linux-hardware.org/?probe=39389b9ddf) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| ASUSTek       | K50C                        | Notebook    | [01079b722b](https://linux-hardware.org/?probe=01079b722b) | Feb 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [8bb8c751f8](https://linux-hardware.org/?probe=8bb8c751f8) | Feb 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [601f46e5a4](https://linux-hardware.org/?probe=601f46e5a4) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a32dfea06a](https://linux-hardware.org/?probe=a32dfea06a) | Feb 07, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [583a1313c8](https://linux-hardware.org/?probe=583a1313c8) | Feb 01, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [0bcf18e1fc](https://linux-hardware.org/?probe=0bcf18e1fc) | Feb 01, 2022 |
| HP            | Compaq 8710w (GC124EA#AC... | Notebook    | [b21e187792](https://linux-hardware.org/?probe=b21e187792) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [ed633ddd09](https://linux-hardware.org/?probe=ed633ddd09) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [607ade73d0](https://linux-hardware.org/?probe=607ade73d0) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | H87M-E35                    | Desktop     | [0cfdd2b772](https://linux-hardware.org/?probe=0cfdd2b772) | Jan 28, 2022 |
| HP            | Presario CQ57               | Notebook    | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [abed2f64a1](https://linux-hardware.org/?probe=abed2f64a1) | Jan 26, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [84bd3ccecf](https://linux-hardware.org/?probe=84bd3ccecf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e00760f649](https://linux-hardware.org/?probe=e00760f649) | Jan 21, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [de22d479a4](https://linux-hardware.org/?probe=de22d479a4) | Jan 20, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [291a3e234b](https://linux-hardware.org/?probe=291a3e234b) | Jan 14, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [8f9c010abb](https://linux-hardware.org/?probe=8f9c010abb) | Jan 10, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [239547a419](https://linux-hardware.org/?probe=239547a419) | Jan 09, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | G7 7700                     | Notebook    | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| MSI           | GT75 Titan 8RG              | Notebook    | [77e24243cf](https://linux-hardware.org/?probe=77e24243cf) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| MSI           | MS-7922                     | Desktop     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003KRT     | Notebook    | [62e3c3073b](https://linux-hardware.org/?probe=62e3c3073b) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| Gigabyte      | M61SME-S2                   | Desktop     | [be9f6cac13](https://linux-hardware.org/?probe=be9f6cac13) | Dec 20, 2021 |
| ASUSTek       | X540UA                      | Notebook    | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HONOR         | BMH-WCX9                    | Notebook    | [46395a1450](https://linux-hardware.org/?probe=46395a1450) | Dec 19, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [7f0853c09e](https://linux-hardware.org/?probe=7f0853c09e) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| MSI           | GL63 9SC                    | Notebook    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| BenQ          | Joybook R56                 | Notebook    | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [a2e037ba0e](https://linux-hardware.org/?probe=a2e037ba0e) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f9ada169fd](https://linux-hardware.org/?probe=f9ada169fd) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d39826b60](https://linux-hardware.org/?probe=7d39826b60) | Dec 09, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| LG Electro... | R510                        | Notebook    | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [00c297540d](https://linux-hardware.org/?probe=00c297540d) | Nov 27, 2021 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [488cdb831c](https://linux-hardware.org/?probe=488cdb831c) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [8cf8f98a53](https://linux-hardware.org/?probe=8cf8f98a53) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [696ee320dd](https://linux-hardware.org/?probe=696ee320dd) | Nov 11, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [039315b907](https://linux-hardware.org/?probe=039315b907) | Nov 10, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [e290db920f](https://linux-hardware.org/?probe=e290db920f) | Nov 08, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| ASUSTek       | V241EA                      | All in one  | [ffb4ed2207](https://linux-hardware.org/?probe=ffb4ed2207) | Nov 02, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [04c5f1689d](https://linux-hardware.org/?probe=04c5f1689d) | Oct 27, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [0f23350175](https://linux-hardware.org/?probe=0f23350175) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a56c0a6b4d](https://linux-hardware.org/?probe=a56c0a6b4d) | Oct 26, 2021 |
| Samsung       | R508                        | Notebook    | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| HP            | Notebook                    | Notebook    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [8061e7314a](https://linux-hardware.org/?probe=8061e7314a) | Oct 23, 2021 |
| HP            | 86F0 11000                  | All in one  | [75738404ae](https://linux-hardware.org/?probe=75738404ae) | Oct 21, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | Notebook    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f874da9f03](https://linux-hardware.org/?probe=f874da9f03) | Oct 12, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9fd17a6579](https://linux-hardware.org/?probe=9fd17a6579) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9b4b3c9f77](https://linux-hardware.org/?probe=9b4b3c9f77) | Oct 09, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [b99c6d022e](https://linux-hardware.org/?probe=b99c6d022e) | Oct 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0d6bbd5c75](https://linux-hardware.org/?probe=0d6bbd5c75) | Oct 05, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [264badf289](https://linux-hardware.org/?probe=264badf289) | Oct 01, 2021 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [fdc2b74a29](https://linux-hardware.org/?probe=fdc2b74a29) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | Notebook    | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| Intel         | H61M-S1                     | Desktop     | [ba0b4c102b](https://linux-hardware.org/?probe=ba0b4c102b) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| HP            | 86F0 11000                  | All in one  | [d94d1dcab2](https://linux-hardware.org/?probe=d94d1dcab2) | Sep 29, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [bea6762fb6](https://linux-hardware.org/?probe=bea6762fb6) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [f21200b164](https://linux-hardware.org/?probe=f21200b164) | Sep 23, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [80b6244981](https://linux-hardware.org/?probe=80b6244981) | Sep 21, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [bc0974da01](https://linux-hardware.org/?probe=bc0974da01) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9cf1061bcb](https://linux-hardware.org/?probe=9cf1061bcb) | Sep 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f8bb575441](https://linux-hardware.org/?probe=f8bb575441) | Sep 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [a64387b07d](https://linux-hardware.org/?probe=a64387b07d) | Sep 15, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [01cd639b37](https://linux-hardware.org/?probe=01cd639b37) | Sep 11, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| HP            | ProBook 4515s               | Notebook    | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | Notebook    | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [248b63572e](https://linux-hardware.org/?probe=248b63572e) | Sep 08, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| Samsung       | R508                        | Notebook    | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| HP            | Compaq 610                  | Notebook    | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [11fce4275a](https://linux-hardware.org/?probe=11fce4275a) | Sep 01, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [989a6f27be](https://linux-hardware.org/?probe=989a6f27be) | Aug 29, 2021 |
| Biostar       | A960D+V3                    | Desktop     | [f65660cdbe](https://linux-hardware.org/?probe=f65660cdbe) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [46407e3bfe](https://linux-hardware.org/?probe=46407e3bfe) | Aug 24, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [d74e3d1835](https://linux-hardware.org/?probe=d74e3d1835) | Aug 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [240d31631f](https://linux-hardware.org/?probe=240d31631f) | Aug 19, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6bcc5abfa7](https://linux-hardware.org/?probe=6bcc5abfa7) | Aug 18, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [735e9cba22](https://linux-hardware.org/?probe=735e9cba22) | Aug 18, 2021 |
| Biostar       | Hi-Fi A75S3                 | Desktop     | [f75bdb68fa](https://linux-hardware.org/?probe=f75bdb68fa) | Aug 14, 2021 |
| Acer          | Veriton N4660G              | Desktop     | [7ee989172f](https://linux-hardware.org/?probe=7ee989172f) | Aug 13, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [21914d4123](https://linux-hardware.org/?probe=21914d4123) | Aug 11, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [52a8d13536](https://linux-hardware.org/?probe=52a8d13536) | Aug 08, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [11621d5877](https://linux-hardware.org/?probe=11621d5877) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [94d76843e6](https://linux-hardware.org/?probe=94d76843e6) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EQS33800     | Notebook    | [2e1468bf31](https://linux-hardware.org/?probe=2e1468bf31) | Aug 02, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [6d45e5794a](https://linux-hardware.org/?probe=6d45e5794a) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c90b5a2e7d](https://linux-hardware.org/?probe=c90b5a2e7d) | Jul 28, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [92c5d52e50](https://linux-hardware.org/?probe=92c5d52e50) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [960c966e4b](https://linux-hardware.org/?probe=960c966e4b) | Jul 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [af87c52a43](https://linux-hardware.org/?probe=af87c52a43) | Jul 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ab8b0d224b](https://linux-hardware.org/?probe=ab8b0d224b) | Jul 16, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [30dd6fa596](https://linux-hardware.org/?probe=30dd6fa596) | Jul 14, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [ce3b5ecb17](https://linux-hardware.org/?probe=ce3b5ecb17) | Jul 13, 2021 |
| MSI           | MS-7369                     | Desktop     | [caf783ce91](https://linux-hardware.org/?probe=caf783ce91) | Jul 10, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [a9b1ac4bdb](https://linux-hardware.org/?probe=a9b1ac4bdb) | Jul 07, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Sony          | SVE1512N1RW                 | Notebook    | [9cfa353121](https://linux-hardware.org/?probe=9cfa353121) | Jul 05, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [09ee8c08c7](https://linux-hardware.org/?probe=09ee8c08c7) | Jul 05, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a0792e787d](https://linux-hardware.org/?probe=a0792e787d) | Jun 30, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [945132609d](https://linux-hardware.org/?probe=945132609d) | Jun 30, 2021 |
| Intel         | H61M-S1                     | Desktop     | [10ef09acce](https://linux-hardware.org/?probe=10ef09acce) | Jun 28, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [48f732d759](https://linux-hardware.org/?probe=48f732d759) | Jun 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b34ddd69c9](https://linux-hardware.org/?probe=b34ddd69c9) | Jun 21, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7fe08a233a](https://linux-hardware.org/?probe=7fe08a233a) | Jun 20, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [f6436bedb8](https://linux-hardware.org/?probe=f6436bedb8) | Jun 16, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ec0c189e56](https://linux-hardware.org/?probe=ec0c189e56) | Jun 15, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0c5e09b00c](https://linux-hardware.org/?probe=0c5e09b00c) | Jun 14, 2021 |
| MSI           | MS-7369                     | Desktop     | [9852368309](https://linux-hardware.org/?probe=9852368309) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8380ef5fcb](https://linux-hardware.org/?probe=8380ef5fcb) | Jun 11, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [8bdfad6e5a](https://linux-hardware.org/?probe=8bdfad6e5a) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| ASUSTek       | X541UJ                      | Notebook    | [22f4d0228f](https://linux-hardware.org/?probe=22f4d0228f) | May 16, 2021 |
| Timi          | TM1703                      | Notebook    | [a8c47ad7f6](https://linux-hardware.org/?probe=a8c47ad7f6) | May 15, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ECS           | Livermore8                  | Desktop     | [fba5a0dbb7](https://linux-hardware.org/?probe=fba5a0dbb7) | May 12, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3eefcf4b58](https://linux-hardware.org/?probe=3eefcf4b58) | May 11, 2021 |
| Lenovo        | Z710 20250                  | Notebook    | [f3d7663214](https://linux-hardware.org/?probe=f3d7663214) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [06af60abdc](https://linux-hardware.org/?probe=06af60abdc) | May 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b71c62e752](https://linux-hardware.org/?probe=b71c62e752) | May 09, 2021 |
| Biostar       | H81MLC                      | Desktop     | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ec9321bd41](https://linux-hardware.org/?probe=ec9321bd41) | May 08, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [06558373ef](https://linux-hardware.org/?probe=06558373ef) | May 07, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [46872b4b26](https://linux-hardware.org/?probe=46872b4b26) | May 02, 2021 |
| HP            | ProBook 4525s               | Notebook    | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| Dell          | 0CRH6C A02                  | Desktop     | [69cbbfec14](https://linux-hardware.org/?probe=69cbbfec14) | Apr 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [fb5b8d0021](https://linux-hardware.org/?probe=fb5b8d0021) | Apr 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [7ec9efef18](https://linux-hardware.org/?probe=7ec9efef18) | Apr 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [3f2270faad](https://linux-hardware.org/?probe=3f2270faad) | Apr 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [36129cbfda](https://linux-hardware.org/?probe=36129cbfda) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [644dd10952](https://linux-hardware.org/?probe=644dd10952) | Apr 22, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [1832412dab](https://linux-hardware.org/?probe=1832412dab) | Apr 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b60d916c33](https://linux-hardware.org/?probe=b60d916c33) | Apr 19, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [309d8603b2](https://linux-hardware.org/?probe=309d8603b2) | Apr 15, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d945be0db8](https://linux-hardware.org/?probe=d945be0db8) | Apr 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [d6c3e7cb89](https://linux-hardware.org/?probe=d6c3e7cb89) | Apr 15, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [1e11286470](https://linux-hardware.org/?probe=1e11286470) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| HP            | ProBook 445 G6              | Notebook    | [520083c016](https://linux-hardware.org/?probe=520083c016) | Apr 14, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [15bd22b48d](https://linux-hardware.org/?probe=15bd22b48d) | Apr 11, 2021 |
| HP            | 304Ah                       | Desktop     | [66228ce4df](https://linux-hardware.org/?probe=66228ce4df) | Apr 09, 2021 |
| HP            | 304Ah                       | Desktop     | [5d8e8d559a](https://linux-hardware.org/?probe=5d8e8d559a) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8de936a2ca](https://linux-hardware.org/?probe=8de936a2ca) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ebd6174247](https://linux-hardware.org/?probe=ebd6174247) | Apr 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [0362943e9e](https://linux-hardware.org/?probe=0362943e9e) | Apr 02, 2021 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [a3e8c4ecb4](https://linux-hardware.org/?probe=a3e8c4ecb4) | Mar 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [3228126df8](https://linux-hardware.org/?probe=3228126df8) | Mar 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [1dc07212db](https://linux-hardware.org/?probe=1dc07212db) | Mar 28, 2021 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [eeeb3a5b5d](https://linux-hardware.org/?probe=eeeb3a5b5d) | Mar 27, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [35964432d7](https://linux-hardware.org/?probe=35964432d7) | Mar 26, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | Notebook    | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [02a403c967](https://linux-hardware.org/?probe=02a403c967) | Mar 24, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [3157cd3bfe](https://linux-hardware.org/?probe=3157cd3bfe) | Mar 23, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [97df6a4a9a](https://linux-hardware.org/?probe=97df6a4a9a) | Mar 23, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d2e63cfaa6](https://linux-hardware.org/?probe=d2e63cfaa6) | Mar 22, 2021 |
| Dell          | 0P4T42 A01                  | All in one  | [2f14bf6c71](https://linux-hardware.org/?probe=2f14bf6c71) | Mar 22, 2021 |
| ASUSTek       | P5B                         | Desktop     | [a24c9c6d6a](https://linux-hardware.org/?probe=a24c9c6d6a) | Mar 22, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c947af2b99](https://linux-hardware.org/?probe=c947af2b99) | Mar 21, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [c6506a0289](https://linux-hardware.org/?probe=c6506a0289) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [18d693f712](https://linux-hardware.org/?probe=18d693f712) | Mar 21, 2021 |
| ASUSTek       | N752VX                      | Notebook    | [48cb617015](https://linux-hardware.org/?probe=48cb617015) | Mar 20, 2021 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [3e2336037f](https://linux-hardware.org/?probe=3e2336037f) | Mar 20, 2021 |
| Acer          | Aspire 5551G                | Notebook    | [1002c3efd0](https://linux-hardware.org/?probe=1002c3efd0) | Mar 19, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [c63de512e5](https://linux-hardware.org/?probe=c63de512e5) | Mar 18, 2021 |
| HP            | 250 G1                      | Notebook    | [7b14b4e7e5](https://linux-hardware.org/?probe=7b14b4e7e5) | Mar 18, 2021 |
| HP            | ProBook 4525s               | Notebook    | [f9830feb98](https://linux-hardware.org/?probe=f9830feb98) | Mar 17, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [d2dde464de](https://linux-hardware.org/?probe=d2dde464de) | Mar 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [12eebe7515](https://linux-hardware.org/?probe=12eebe7515) | Mar 17, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [e688898ed8](https://linux-hardware.org/?probe=e688898ed8) | Mar 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [658c4e0d17](https://linux-hardware.org/?probe=658c4e0d17) | Mar 17, 2021 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [1b6cfd046e](https://linux-hardware.org/?probe=1b6cfd046e) | Mar 17, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [82f601055a](https://linux-hardware.org/?probe=82f601055a) | Mar 17, 2021 |
| ASRock        | 990FX Extreme4              | Desktop     | [d1536bcdfa](https://linux-hardware.org/?probe=d1536bcdfa) | Mar 17, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [863c6c5d68](https://linux-hardware.org/?probe=863c6c5d68) | Mar 17, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [51bf91aae7](https://linux-hardware.org/?probe=51bf91aae7) | Mar 14, 2021 |
| HP            | Mini 210-4000               | Notebook    | [9301f9c8ef](https://linux-hardware.org/?probe=9301f9c8ef) | Mar 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [72f398fcff](https://linux-hardware.org/?probe=72f398fcff) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [83f50b266f](https://linux-hardware.org/?probe=83f50b266f) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [ed293423f3](https://linux-hardware.org/?probe=ed293423f3) | Mar 11, 2021 |
| HP            | ProBook 4525s               | Notebook    | [912c2f075f](https://linux-hardware.org/?probe=912c2f075f) | Mar 09, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f63d1b8f0b](https://linux-hardware.org/?probe=f63d1b8f0b) | Mar 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [28a8889148](https://linux-hardware.org/?probe=28a8889148) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1df473b11e](https://linux-hardware.org/?probe=1df473b11e) | Mar 03, 2021 |
| Dell          | System XPS L702X            | Notebook    | [1cce147fd2](https://linux-hardware.org/?probe=1cce147fd2) | Feb 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [902d3d474e](https://linux-hardware.org/?probe=902d3d474e) | Feb 25, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [390003cc95](https://linux-hardware.org/?probe=390003cc95) | Feb 24, 2021 |
| MSI           | MS-7250                     | Desktop     | [bd7bbadaad](https://linux-hardware.org/?probe=bd7bbadaad) | Feb 23, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [77748ba0e4](https://linux-hardware.org/?probe=77748ba0e4) | Feb 22, 2021 |
| ASUSTek       | K50C                        | Notebook    | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [8d2b36f7c1](https://linux-hardware.org/?probe=8d2b36f7c1) | Feb 20, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [80cea1a03a](https://linux-hardware.org/?probe=80cea1a03a) | Feb 19, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | Notebook    | [0f4f85b4c1](https://linux-hardware.org/?probe=0f4f85b4c1) | Feb 19, 2021 |
| Packard Be... | EasyNote TM86               | Notebook    | [f548aa653a](https://linux-hardware.org/?probe=f548aa653a) | Feb 18, 2021 |
| Acer          | Extensa 5230                | Notebook    | [b128a06266](https://linux-hardware.org/?probe=b128a06266) | Feb 17, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [1a52fb16f9](https://linux-hardware.org/?probe=1a52fb16f9) | Feb 16, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [8bb7ec1035](https://linux-hardware.org/?probe=8bb7ec1035) | Feb 15, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [c5877ecd52](https://linux-hardware.org/?probe=c5877ecd52) | Feb 14, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [c500f1eff8](https://linux-hardware.org/?probe=c500f1eff8) | Feb 14, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [76e29e229d](https://linux-hardware.org/?probe=76e29e229d) | Feb 13, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [6262cc3afd](https://linux-hardware.org/?probe=6262cc3afd) | Feb 13, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6969353956](https://linux-hardware.org/?probe=6969353956) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | Notebook    | [3a64cfa43e](https://linux-hardware.org/?probe=3a64cfa43e) | Feb 13, 2021 |
| HP            | Mini 210-4000               | Notebook    | [966136f01f](https://linux-hardware.org/?probe=966136f01f) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | Notebook    | [2e31ed1ec6](https://linux-hardware.org/?probe=2e31ed1ec6) | Feb 13, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [bbc60c2820](https://linux-hardware.org/?probe=bbc60c2820) | Feb 13, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8f8fd2975a](https://linux-hardware.org/?probe=8f8fd2975a) | Feb 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [440af1645f](https://linux-hardware.org/?probe=440af1645f) | Feb 13, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [02fd7c81f6](https://linux-hardware.org/?probe=02fd7c81f6) | Feb 11, 2021 |
| Acer          | Extensa 7630EZ              | Notebook    | [9a0378eb4d](https://linux-hardware.org/?probe=9a0378eb4d) | Feb 11, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [bbd0961627](https://linux-hardware.org/?probe=bbd0961627) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [6487d4bd7c](https://linux-hardware.org/?probe=6487d4bd7c) | Feb 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8c35b025b2](https://linux-hardware.org/?probe=8c35b025b2) | Feb 08, 2021 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [cbd3e60242](https://linux-hardware.org/?probe=cbd3e60242) | Feb 07, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [d9218caa35](https://linux-hardware.org/?probe=d9218caa35) | Feb 05, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [f4611ac89e](https://linux-hardware.org/?probe=f4611ac89e) | Feb 04, 2021 |
| HP            | 635                         | Notebook    | [e83d58e706](https://linux-hardware.org/?probe=e83d58e706) | Feb 03, 2021 |
| Acer          | Aspire 5551G                | Notebook    | [811535132b](https://linux-hardware.org/?probe=811535132b) | Feb 02, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [e86c3d781d](https://linux-hardware.org/?probe=e86c3d781d) | Jan 31, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [6f78493e97](https://linux-hardware.org/?probe=6f78493e97) | Jan 29, 2021 |
| Lenovo        | ThinkPad T410 2537V28       | Notebook    | [126c75190e](https://linux-hardware.org/?probe=126c75190e) | Jan 22, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [e04d0e066e](https://linux-hardware.org/?probe=e04d0e066e) | Jan 22, 2021 |
| HP            | 255 G2                      | Notebook    | [3ebc0a9b9b](https://linux-hardware.org/?probe=3ebc0a9b9b) | Jan 21, 2021 |
| MSI           | 760GM-P33                   | Desktop     | [f7dbe6391b](https://linux-hardware.org/?probe=f7dbe6391b) | Jan 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14022d5350](https://linux-hardware.org/?probe=14022d5350) | Jan 20, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [48644938e9](https://linux-hardware.org/?probe=48644938e9) | Jan 17, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [b3bfbdace0](https://linux-hardware.org/?probe=b3bfbdace0) | Jan 10, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [f12a646f8b](https://linux-hardware.org/?probe=f12a646f8b) | Jan 09, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [ca3628282a](https://linux-hardware.org/?probe=ca3628282a) | Jan 06, 2021 |
| HP            | Mini 5102                   | Notebook    | [76f0b2193f](https://linux-hardware.org/?probe=76f0b2193f) | Jan 06, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [76f271acf1](https://linux-hardware.org/?probe=76f271acf1) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b005d0780d](https://linux-hardware.org/?probe=b005d0780d) | Jan 04, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Samsung       | SR58P                       | Notebook    | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| MSI           | 760GM-P33                   | Desktop     | [9af10be990](https://linux-hardware.org/?probe=9af10be990) | Jan 03, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [f49ba1df9c](https://linux-hardware.org/?probe=f49ba1df9c) | Jan 01, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [997fd6a726](https://linux-hardware.org/?probe=997fd6a726) | Dec 30, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [8eb79a3a10](https://linux-hardware.org/?probe=8eb79a3a10) | Dec 29, 2020 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [1b0941ddec](https://linux-hardware.org/?probe=1b0941ddec) | Dec 26, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| Gigabyte      | P35-S3G                     | Desktop     | [be95d225fe](https://linux-hardware.org/?probe=be95d225fe) | Dec 22, 2020 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [cf0c42c323](https://linux-hardware.org/?probe=cf0c42c323) | Dec 18, 2020 |
| HP            | 81BA                        | All in one  | [00a2be4ed1](https://linux-hardware.org/?probe=00a2be4ed1) | Dec 18, 2020 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [43c86b0f1e](https://linux-hardware.org/?probe=43c86b0f1e) | Dec 18, 2020 |
| HP            | 81BA                        | All in one  | [1c8a356387](https://linux-hardware.org/?probe=1c8a356387) | Dec 17, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [f4ae75d77c](https://linux-hardware.org/?probe=f4ae75d77c) | Dec 16, 2020 |
| Dell          | Inspiron 5748               | Notebook    | [091c74353b](https://linux-hardware.org/?probe=091c74353b) | Dec 16, 2020 |
| Lenovo        | B5400 20278                 | Notebook    | [56ea17c80b](https://linux-hardware.org/?probe=56ea17c80b) | Dec 15, 2020 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [5e1b23e45c](https://linux-hardware.org/?probe=5e1b23e45c) | Dec 14, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [b987e4cc7c](https://linux-hardware.org/?probe=b987e4cc7c) | Dec 11, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [f6e40ea1a0](https://linux-hardware.org/?probe=f6e40ea1a0) | Dec 11, 2020 |
| Samsung       | R530/R730                   | Notebook    | [eaf1fed190](https://linux-hardware.org/?probe=eaf1fed190) | Dec 11, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d0d9126db4](https://linux-hardware.org/?probe=d0d9126db4) | Dec 08, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [c6b4560c3e](https://linux-hardware.org/?probe=c6b4560c3e) | Dec 07, 2020 |
| Prestigio     | PSB141C03                   | Notebook    | [4087902d18](https://linux-hardware.org/?probe=4087902d18) | Dec 07, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [a566f76ca4](https://linux-hardware.org/?probe=a566f76ca4) | Dec 07, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [27a4e636f6](https://linux-hardware.org/?probe=27a4e636f6) | Dec 02, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [54886a9cc0](https://linux-hardware.org/?probe=54886a9cc0) | Nov 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [91ff5fdd53](https://linux-hardware.org/?probe=91ff5fdd53) | Nov 28, 2020 |
| ASUSTek       | P5K WS                      | Desktop     | [89a2e1b515](https://linux-hardware.org/?probe=89a2e1b515) | Nov 28, 2020 |
| ASUSTek       | K52N                        | Notebook    | [94f1b7362b](https://linux-hardware.org/?probe=94f1b7362b) | Nov 25, 2020 |
| Acer          | Aspire E1-530               | Notebook    | [e343493113](https://linux-hardware.org/?probe=e343493113) | Nov 25, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | Notebook    | [b265ff82a7](https://linux-hardware.org/?probe=b265ff82a7) | Nov 21, 2020 |
| Lenovo        | ThinkPad E15 20RD0014RT     | Notebook    | [81de71766f](https://linux-hardware.org/?probe=81de71766f) | Nov 21, 2020 |
| Prestigio     | PSB141C02                   | Notebook    | [08aa1ee2ff](https://linux-hardware.org/?probe=08aa1ee2ff) | Nov 20, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [bada67f585](https://linux-hardware.org/?probe=bada67f585) | Nov 20, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [05314304a4](https://linux-hardware.org/?probe=05314304a4) | Nov 19, 2020 |
| ASUSTek       | V200IB                      | Desktop     | [910d5a3bfd](https://linux-hardware.org/?probe=910d5a3bfd) | Nov 19, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9687208571](https://linux-hardware.org/?probe=9687208571) | Nov 19, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [c914110be9](https://linux-hardware.org/?probe=c914110be9) | Nov 19, 2020 |
| Acer          | Aspire E1-532G              | Notebook    | [dd90b2f3e2](https://linux-hardware.org/?probe=dd90b2f3e2) | Nov 18, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6abee99a84](https://linux-hardware.org/?probe=6abee99a84) | Nov 18, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [72f585d3fd](https://linux-hardware.org/?probe=72f585d3fd) | Nov 18, 2020 |
| ASUSTek       | V200IB                      | All in one  | [e20ac63341](https://linux-hardware.org/?probe=e20ac63341) | Nov 18, 2020 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [f8de57d305](https://linux-hardware.org/?probe=f8de57d305) | Nov 16, 2020 |
| Samsung       | R508                        | Notebook    | [937a0199e0](https://linux-hardware.org/?probe=937a0199e0) | Nov 16, 2020 |
| ASUSTek       | K52N                        | Notebook    | [a96cd62a24](https://linux-hardware.org/?probe=a96cd62a24) | Nov 14, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [225c61e941](https://linux-hardware.org/?probe=225c61e941) | Nov 13, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [4eefad2a8b](https://linux-hardware.org/?probe=4eefad2a8b) | Nov 13, 2020 |
| Dell          | Inspiron 5521               | Notebook    | [1080310f19](https://linux-hardware.org/?probe=1080310f19) | Nov 11, 2020 |
| Intel         | SharkBay Platform           | Notebook    | [21647cb222](https://linux-hardware.org/?probe=21647cb222) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [091af6961a](https://linux-hardware.org/?probe=091af6961a) | Nov 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [5da1ec78a0](https://linux-hardware.org/?probe=5da1ec78a0) | Nov 07, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [df41815a21](https://linux-hardware.org/?probe=df41815a21) | Nov 06, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | Notebook    | [412e6eca38](https://linux-hardware.org/?probe=412e6eca38) | Nov 05, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | Notebook    | [6fb42db6e5](https://linux-hardware.org/?probe=6fb42db6e5) | Nov 05, 2020 |
| ASRock        | Z370M Pro4                  | Desktop     | [85e45a95e0](https://linux-hardware.org/?probe=85e45a95e0) | Nov 04, 2020 |
| Intel         | SharkBay Platform           | Notebook    | [dcd49fdf3b](https://linux-hardware.org/?probe=dcd49fdf3b) | Nov 04, 2020 |
| Samsung       | R508                        | Notebook    | [7915a99545](https://linux-hardware.org/?probe=7915a99545) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [45666ff7af](https://linux-hardware.org/?probe=45666ff7af) | Nov 01, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [830c1ed47a](https://linux-hardware.org/?probe=830c1ed47a) | Nov 01, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f5328a95d5](https://linux-hardware.org/?probe=f5328a95d5) | Oct 31, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [557aca340e](https://linux-hardware.org/?probe=557aca340e) | Oct 27, 2020 |
| Olimex        | A20-OLinuXino-LIME2         | Soc         | [5a543f3e3e](https://linux-hardware.org/?probe=5a543f3e3e) | Oct 26, 2020 |
| MSI           | 760GM-P33                   | Desktop     | [c611e5bbe5](https://linux-hardware.org/?probe=c611e5bbe5) | Oct 26, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7ae3293c6d](https://linux-hardware.org/?probe=7ae3293c6d) | Oct 26, 2020 |
| Timi          | TM1701                      | Notebook    | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [92fa11d82d](https://linux-hardware.org/?probe=92fa11d82d) | Oct 25, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [6a18afe215](https://linux-hardware.org/?probe=6a18afe215) | Oct 25, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [e149fb7dc2](https://linux-hardware.org/?probe=e149fb7dc2) | Oct 23, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b0e3f9ed28](https://linux-hardware.org/?probe=b0e3f9ed28) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [f21f5a008c](https://linux-hardware.org/?probe=f21f5a008c) | Oct 21, 2020 |
| Gigabyte      | Z390 D                      | Desktop     | [1610651aa5](https://linux-hardware.org/?probe=1610651aa5) | Oct 21, 2020 |
| HP            | 250 G2                      | Notebook    | [164b391add](https://linux-hardware.org/?probe=164b391add) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [50cb6d53ef](https://linux-hardware.org/?probe=50cb6d53ef) | Oct 18, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [0e1b75fc55](https://linux-hardware.org/?probe=0e1b75fc55) | Oct 18, 2020 |
| Acer          | Unknown                     | Notebook    | [5dc51268a1](https://linux-hardware.org/?probe=5dc51268a1) | Oct 17, 2020 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [2fa1f3048b](https://linux-hardware.org/?probe=2fa1f3048b) | Oct 13, 2020 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [ee0649427b](https://linux-hardware.org/?probe=ee0649427b) | Oct 12, 2020 |
| Prestigio     | PSB141C03                   | Notebook    | [eb6b709b25](https://linux-hardware.org/?probe=eb6b709b25) | Oct 12, 2020 |
| Lenovo        | ThinkPad T400 7417CTO       | Notebook    | [41f5d8bbb1](https://linux-hardware.org/?probe=41f5d8bbb1) | Oct 12, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [479a1ad655](https://linux-hardware.org/?probe=479a1ad655) | Oct 11, 2020 |
| MSI           | MS-7250                     | Desktop     | [c4ef765de1](https://linux-hardware.org/?probe=c4ef765de1) | Oct 10, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [eefad2dd0f](https://linux-hardware.org/?probe=eefad2dd0f) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [1d6ca8e5fc](https://linux-hardware.org/?probe=1d6ca8e5fc) | Oct 09, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b0244dd7f4](https://linux-hardware.org/?probe=b0244dd7f4) | Oct 08, 2020 |
| ASUSTek       | H61M-K                      | Desktop     | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| Dell          | G5 5587                     | Notebook    | [7ec299e574](https://linux-hardware.org/?probe=7ec299e574) | Oct 03, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [4308201e9f](https://linux-hardware.org/?probe=4308201e9f) | Sep 28, 2020 |
| ASRock        | 970 Pro3                    | Desktop     | [c4459c622c](https://linux-hardware.org/?probe=c4459c622c) | Sep 27, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belarus/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 123       | 9.96%   |
| ROSA R11                     | 106       | 8.58%   |
| ROSA R8.1                    | 81        | 6.56%   |
| Ubuntu 20.04                 | 64        | 5.18%   |
| ROSA R9                      | 49        | 3.97%   |
| ROSA R11.1                   | 48        | 3.89%   |
| Ubuntu 18.04                 | 39        | 3.16%   |
| ROSA R8                      | 37        | 3%      |
| ROSA 12.2                    | 31        | 2.51%   |
| Ubuntu 22.04                 | 29        | 2.35%   |
| ROSA 12.4                    | 25        | 2.02%   |
| OpenMandriva 4.2             | 24        | 1.94%   |
| Fedora 38                    | 22        | 1.78%   |
| ROSA 12.3                    | 21        | 1.7%    |
| Manjaro                      | 19        | 1.54%   |
| Arch Rolling                 | 17        | 1.38%   |
| Debian 11                    | 16        | 1.3%    |
| Fedora 36                    | 15        | 1.21%   |
| OpenMandriva 4.3             | 13        | 1.05%   |
| Linux Mint 19.3              | 13        | 1.05%   |
| Linux Mint 20.3              | 12        | 0.97%   |
| KDE neon 20.04               | 12        | 0.97%   |
| Fedora 35                    | 12        | 0.97%   |
| Linux Mint 21.1              | 11        | 0.89%   |
| Arch                         | 11        | 0.89%   |
| Fedora 34                    | 10        | 0.81%   |
| Kubuntu 20.04                | 9         | 0.73%   |
| Fedora 37                    | 9         | 0.73%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.65%   |
| OpenMandriva 23.03           | 8         | 0.65%   |
| Debian 12                    | 8         | 0.65%   |
| Ubuntu 22.10                 | 7         | 0.57%   |
| Linux Mint 21.2              | 7         | 0.57%   |
| Fedora 39                    | 7         | 0.57%   |
| Fedora 32                    | 6         | 0.49%   |
| Fedora 31                    | 6         | 0.49%   |
| Debian 10                    | 6         | 0.49%   |
| Xubuntu 22.04                | 5         | 0.4%    |
| Xubuntu 20.04                | 5         | 0.4%    |
| Ubuntu 23.04                 | 5         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ROSA             | 443       | 40.94%  |
| Ubuntu           | 157       | 14.51%  |
| Linux Mint       | 71        | 6.56%   |
| Fedora           | 68        | 6.28%   |
| OpenMandriva     | 56        | 5.18%   |
| Manjaro          | 46        | 4.25%   |
| Endless          | 38        | 3.51%   |
| Debian           | 35        | 3.23%   |
| Arch             | 27        | 2.5%    |
| KDE neon         | 17        | 1.57%   |
| Kubuntu          | 16        | 1.48%   |
| Xubuntu          | 13        | 1.2%    |
| Gentoo           | 11        | 1.02%   |
| openSUSE         | 9         | 0.83%   |
| Pop!_OS          | 7         | 0.65%   |
| LMDE             | 7         | 0.65%   |
| Elementary       | 7         | 0.65%   |
| Kali             | 5         | 0.46%   |
| Zorin            | 4         | 0.37%   |
| Lubuntu          | 4         | 0.37%   |
| Ubuntu MATE      | 3         | 0.28%   |
| MX               | 3         | 0.28%   |
| Clear Linux      | 3         | 0.28%   |
| CentOS           | 3         | 0.28%   |
| BlackPanther     | 3         | 0.28%   |
| ArcoLinux        | 3         | 0.28%   |
| ALT Linux        | 3         | 0.28%   |
| Ubuntu Unity     | 2         | 0.18%   |
| SteamOS          | 2         | 0.18%   |
| Xero             | 1         | 0.09%   |
| Ubuntu Budgie    | 1         | 0.09%   |
| Trisquel         | 1         | 0.09%   |
| Solus            | 1         | 0.09%   |
| RHEL             | 1         | 0.09%   |
| Q4OS             | 1         | 0.09%   |
| Peppermint       | 1         | 0.09%   |
| Parrot           | 1         | 0.09%   |
| org.kde.Platform | 1         | 0.09%   |
| Nobara           | 1         | 0.09%   |
| Mageia           | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 60        | 4.34%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 42        | 3.03%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 39        | 2.82%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 32        | 2.31%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 27        | 1.95%   |
| 5.10.14-desktop-1omv4002            | 23        | 1.66%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 20        | 1.45%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 19        | 1.37%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 18        | 1.3%    |
| 5.4.83-generic-2rosa-x86_64         | 16        | 1.16%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 16        | 1.16%   |
| 4.15.0-desktop-45.1rosa-i586        | 15        | 1.08%   |
| 5.4.0-42-generic                    | 13        | 0.94%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 13        | 0.94%   |
| 5.16.7-desktop-1omv4003             | 12        | 0.87%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 12        | 0.87%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 11        | 0.79%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 11        | 0.79%   |
| 5.15.0-56-generic                   | 11        | 0.79%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 11        | 0.79%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 10        | 0.72%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 10        | 0.72%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 9         | 0.65%   |
| 5.4.32-generic-2rosa-x86_64         | 8         | 0.58%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 8         | 0.58%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 7         | 0.51%   |
| 4.9.155-nrj-laptop-1rosa-x86_64     | 7         | 0.51%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 7         | 0.51%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 7         | 0.51%   |
| 6.2.6-desktop-1omv2390              | 6         | 0.43%   |
| 5.9.16-1-MANJARO                    | 6         | 0.43%   |
| 5.8.0-14-generic                    | 6         | 0.43%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 6         | 0.43%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 6         | 0.43%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 6         | 0.43%   |
| 6.4.11-desktop-1omv2390             | 5         | 0.36%   |
| 6.2.0-26-generic                    | 5         | 0.36%   |
| 5.4.0-58-generic                    | 5         | 0.36%   |
| 5.4.0-48-generic                    | 5         | 0.36%   |
| 5.3.0-28-generic                    | 5         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 139       | 10.35%  |
| 5.4.0   | 83        | 6.18%   |
| 4.9.60  | 71        | 5.29%   |
| 4.9.20  | 49        | 3.65%   |
| 5.15.0  | 46        | 3.43%   |
| 4.9.124 | 33        | 2.46%   |
| 5.10.74 | 32        | 2.38%   |
| 5.8.0   | 31        | 2.31%   |
| 4.9.155 | 27        | 2.01%   |
| 4.1.38  | 27        | 2.01%   |
| 5.10.0  | 26        | 1.94%   |
| 5.11.0  | 25        | 1.86%   |
| 4.1.34  | 25        | 1.86%   |
| 5.10.14 | 23        | 1.71%   |
| 5.0.0   | 23        | 1.71%   |
| 4.9.9   | 22        | 1.64%   |
| 4.9.76  | 22        | 1.64%   |
| 5.13.0  | 21        | 1.56%   |
| 5.4.83  | 20        | 1.49%   |
| 5.3.0   | 20        | 1.49%   |
| 5.19.0  | 20        | 1.49%   |
| 6.2.0   | 15        | 1.12%   |
| 4.9.41  | 14        | 1.04%   |
| 4.18.0  | 13        | 0.97%   |
| 5.16.7  | 12        | 0.89%   |
| 5.15.75 | 12        | 0.89%   |
| 6.1.20  | 11        | 0.82%   |
| 6.1.0   | 11        | 0.82%   |
| 5.4.32  | 9         | 0.67%   |
| 4.19.0  | 9         | 0.67%   |
| 4.13.0  | 9         | 0.67%   |
| 5.9.16  | 8         | 0.6%    |
| 5.15.79 | 7         | 0.52%   |
| 4.9.95  | 7         | 0.52%   |
| 6.4.11  | 6         | 0.45%   |
| 6.2.6   | 6         | 0.45%   |
| 4.9.87  | 6         | 0.45%   |
| 4.9.111 | 6         | 0.45%   |
| 6.6.2   | 5         | 0.37%   |
| 6.1.1   | 5         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 215       | 17.27%  |
| 4.15    | 139       | 11.16%  |
| 5.4     | 128       | 10.28%  |
| 5.10    | 100       | 8.03%   |
| 5.15    | 91        | 7.31%   |
| 4.1     | 55        | 4.42%   |
| 6.1     | 48        | 3.86%   |
| 5.8     | 39        | 3.13%   |
| 6.2     | 37        | 2.97%   |
| 5.11    | 35        | 2.81%   |
| 5.19    | 30        | 2.41%   |
| 5.13    | 30        | 2.41%   |
| 5.3     | 29        | 2.33%   |
| 5.0     | 24        | 1.93%   |
| 6.5     | 19        | 1.53%   |
| 5.9     | 19        | 1.53%   |
| 5.16    | 19        | 1.53%   |
| 6.4     | 18        | 1.45%   |
| 4.18    | 16        | 1.29%   |
| 6.0     | 15        | 1.2%    |
| 4.19    | 15        | 1.2%    |
| 5.18    | 14        | 1.12%   |
| 5.14    | 13        | 1.04%   |
| 6.6     | 11        | 0.88%   |
| 5.6     | 11        | 0.88%   |
| 5.17    | 10        | 0.8%    |
| 6.3     | 9         | 0.72%   |
| 4.13    | 9         | 0.72%   |
| 5.12    | 8         | 0.64%   |
| 4.8     | 8         | 0.64%   |
| 5.7     | 5         | 0.4%    |
| 4.4     | 5         | 0.4%    |
| 4.14    | 5         | 0.4%    |
| 5.5     | 4         | 0.32%   |
| 4.17    | 3         | 0.24%   |
| 4.16    | 3         | 0.24%   |
| 4.10    | 2         | 0.16%   |
| 5.1     | 1         | 0.08%   |
| 4.20    | 1         | 0.08%   |
| 4.12    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 953       | 91.2%   |
| i686    | 89        | 8.52%   |
| armv7l  | 2         | 0.19%   |
| aarch64 | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 283       | 25.25%  |
| KDE4          | 279       | 24.89%  |
| GNOME         | 278       | 24.8%   |
| Unknown       | 80        | 7.14%   |
| XFCE          | 57        | 5.08%   |
| X-Cinnamon    | 47        | 4.19%   |
| LXQt          | 27        | 2.41%   |
| MATE          | 19        | 1.69%   |
| KDE           | 15        | 1.34%   |
| Cinnamon      | 11        | 0.98%   |
| Pantheon      | 6         | 0.54%   |
| LXDE          | 5         | 0.45%   |
| Unity         | 2         | 0.18%   |
| i3            | 2         | 0.18%   |
| Deepin        | 2         | 0.18%   |
| Trinity       | 1         | 0.09%   |
| sway          | 1         | 0.09%   |
| Openbox       | 1         | 0.09%   |
| KDE6          | 1         | 0.09%   |
| Endless:GNOME | 1         | 0.09%   |
| chadwm        | 1         | 0.09%   |
| Budgie        | 1         | 0.09%   |
| bspwm         | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 835       | 77.89%  |
| Wayland | 184       | 17.16%  |
| Unknown | 40        | 3.73%   |
| Tty     | 12        | 1.12%   |
| Web     | 1         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 283       | 25.47%  |
| KDM     | 281       | 25.29%  |
| Unknown | 266       | 23.94%  |
| GDM     | 127       | 11.43%  |
| LightDM | 65        | 5.85%   |
| GDM3    | 56        | 5.04%   |
| TDM     | 29        | 2.61%   |
| MDM     | 2         | 0.18%   |
| SLiM    | 1         | 0.09%   |
| GREETD  | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 417       | 38.75%  |
| ru_RU       | 397       | 36.9%   |
| en_US       | 206       | 19.14%  |
| be_BY       | 18        | 1.67%   |
| C           | 12        | 1.12%   |
| en_GB       | 11        | 1.02%   |
| ru_RU.UTF_8 | 6         | 0.56%   |
| ru_UA       | 4         | 0.37%   |
| ru_BY       | 2         | 0.19%   |
| cv_RU       | 2         | 0.19%   |
| en_CA       | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 595       | 55.87%  |
| EFI  | 470       | 44.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 696       | 62.65%  |
| Unknown | 242       | 21.78%  |
| Btrfs   | 93        | 8.37%   |
| Overlay | 56        | 5.04%   |
| Tmpfs   | 9         | 0.81%   |
| Xfs     | 5         | 0.45%   |
| Ext3    | 4         | 0.36%   |
| F2fs    | 2         | 0.18%   |
| Ext2    | 2         | 0.18%   |
| Zfs     | 1         | 0.09%   |
| SAMSUNG | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 385       | 34.84%  |
| Unknown | 363       | 32.85%  |
| MBR     | 357       | 32.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 927       | 86.31%  |
| Yes       | 147       | 13.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 722       | 66.36%  |
| Yes       | 366       | 33.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 231       | 22.36%  |
| Lenovo              | 136       | 13.17%  |
| Hewlett-Packard     | 135       | 13.07%  |
| Gigabyte Technology | 104       | 10.07%  |
| Acer                | 77        | 7.45%   |
| ASRock              | 76        | 7.36%   |
| MSI                 | 54        | 5.23%   |
| Dell                | 49        | 4.74%   |
| Samsung Electronics | 36        | 3.48%   |
| Biostar             | 14        | 1.36%   |
| Intel               | 13        | 1.26%   |
| Toshiba             | 10        | 0.97%   |
| Timi                | 10        | 0.97%   |
| Sony                | 7         | 0.68%   |
| HONOR               | 6         | 0.58%   |
| Prestigio           | 5         | 0.48%   |
| Packard Bell        | 5         | 0.48%   |
| HUAWEI              | 5         | 0.48%   |
| Apple               | 5         | 0.48%   |
| Unknown             | 5         | 0.48%   |
| Fujitsu             | 4         | 0.39%   |
| ECS                 | 4         | 0.39%   |
| Fujitsu Siemens     | 3         | 0.29%   |
| Valve               | 2         | 0.19%   |
| Nvidia              | 2         | 0.19%   |
| EPoX Computer       | 2         | 0.19%   |
| Chuwi               | 2         | 0.19%   |
| BenQ                | 2         | 0.19%   |
| ZOTAC               | 1         | 0.1%    |
| ViewSonic           | 1         | 0.1%    |
| VIA Technologies    | 1         | 0.1%    |
| TECNO               | 1         | 0.1%    |
| Supermicro          | 1         | 0.1%    |
| Quanta              | 1         | 0.1%    |
| Pegatron            | 1         | 0.1%    |
| Partner             | 1         | 0.1%    |
| Olimex              | 1         | 0.1%    |
| Notebook            | 1         | 0.1%    |
| Microsoft           | 1         | 0.1%    |
| LTD Delovoy Office  | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo G50-30 80G0                      | 7         | 0.68%   |
| Unknown                                 | 7         | 0.68%   |
| HP Notebook                             | 6         | 0.58%   |
| Timi TM1701                             | 5         | 0.48%   |
| ASRock N68C-GS FX                       | 5         | 0.48%   |
| Acer Extensa 5220                       | 5         | 0.48%   |
| Samsung RV413/RV513                     | 4         | 0.39%   |
| MSI MS-7369                             | 4         | 0.39%   |
| Lenovo IdeaPad 320-15IAP 80XR           | 4         | 0.39%   |
| HP ProBook 455 G1                       | 4         | 0.39%   |
| HP ProBook 450 G5                       | 4         | 0.39%   |
| HP Pavilion g6                          | 4         | 0.39%   |
| HP Laptop 15s-eq2xxx                    | 4         | 0.39%   |
| Gigabyte 970A-DS3P                      | 4         | 0.39%   |
| ASUS X540NV                             | 4         | 0.39%   |
| ASUS All Series                         | 4         | 0.39%   |
| ASRock N68-VS3 UCC                      | 4         | 0.39%   |
| Acer Aspire E1-571G                     | 4         | 0.39%   |
| MSI MS-7309                             | 3         | 0.29%   |
| Lenovo IdeaPad Z570 HuronRiver Platform | 3         | 0.29%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 3         | 0.29%   |
| Lenovo IdeaPad 3 15IML05 81WB           | 3         | 0.29%   |
| Lenovo IdeaPad 100-15IBY 80MJ           | 3         | 0.29%   |
| Lenovo G570 20079                       | 3         | 0.29%   |
| Lenovo G500 20236                       | 3         | 0.29%   |
| Lenovo B590 20206                       | 3         | 0.29%   |
| Lenovo B50-30 20382                     | 3         | 0.29%   |
| HONOR NBR-WAX9                          | 3         | 0.29%   |
| HP Victus by Laptop 16-e0xxx            | 3         | 0.29%   |
| HP Pavilion dv6                         | 3         | 0.29%   |
| HP Pavilion 15                          | 3         | 0.29%   |
| HP 635                                  | 3         | 0.29%   |
| Gigabyte M61SME-S2                      | 3         | 0.29%   |
| Gigabyte H81M-S2H                       | 3         | 0.29%   |
| Gigabyte GA-MA74GM-S2H                  | 3         | 0.29%   |
| Gigabyte GA-780T-D3L                    | 3         | 0.29%   |
| Gigabyte B450M S2H                      | 3         | 0.29%   |
| Gigabyte B450M DS3H                     | 3         | 0.29%   |
| Dell Inspiron 7577                      | 3         | 0.29%   |
| ASUS ZenBook UX431DA_UM431DA            | 3         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 50        | 4.84%   |
| Lenovo IdeaPad        | 46        | 4.45%   |
| HP ProBook            | 38        | 3.68%   |
| Lenovo ThinkPad       | 30        | 2.9%    |
| HP Pavilion           | 28        | 2.71%   |
| Dell Inspiron         | 28        | 2.71%   |
| ASUS VivoBook         | 26        | 2.52%   |
| Acer Extensa          | 13        | 1.26%   |
| HP Laptop             | 12        | 1.16%   |
| ASUS PRIME            | 12        | 1.16%   |
| ASUS ROG              | 10        | 0.97%   |
| ASUS ZenBook          | 9         | 0.87%   |
| Toshiba Satellite     | 8         | 0.77%   |
| HP EliteBook          | 8         | 0.77%   |
| Lenovo G50-30         | 7         | 0.68%   |
| Gigabyte B450M        | 7         | 0.68%   |
| ASUS ASUS             | 7         | 0.68%   |
| Unknown               | 7         | 0.68%   |
| HP Notebook           | 6         | 0.58%   |
| HP Compaq             | 6         | 0.58%   |
| Timi TM1701           | 5         | 0.48%   |
| Lenovo Legion         | 5         | 0.48%   |
| HP 250                | 5         | 0.48%   |
| Dell XPS              | 5         | 0.48%   |
| Dell Vostro           | 5         | 0.48%   |
| ASUS TUF              | 5         | 0.48%   |
| ASRock N68C-GS        | 5         | 0.48%   |
| ASRock N68-VS3        | 5         | 0.48%   |
| Samsung RV413         | 4         | 0.39%   |
| MSI MS-7369           | 4         | 0.39%   |
| Lenovo G580           | 4         | 0.39%   |
| HP 255                | 4         | 0.39%   |
| Gigabyte Z390         | 4         | 0.39%   |
| Gigabyte 970A-DS3P    | 4         | 0.39%   |
| Dell Latitude         | 4         | 0.39%   |
| ASUS X540NV           | 4         | 0.39%   |
| ASUS P8H77-V          | 4         | 0.39%   |
| ASUS All              | 4         | 0.39%   |
| Acer TravelMate       | 4         | 0.39%   |
| Packard Bell EasyNote | 3         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 105       | 10.16%  |
| 2013    | 101       | 9.78%   |
| 2011    | 100       | 9.68%   |
| 2018    | 95        | 9.2%    |
| 2020    | 69        | 6.68%   |
| 2017    | 68        | 6.58%   |
| 2010    | 63        | 6.1%    |
| 2014    | 53        | 5.13%   |
| 2021    | 52        | 5.03%   |
| 2009    | 52        | 5.03%   |
| 2019    | 50        | 4.84%   |
| 2007    | 50        | 4.84%   |
| 2015    | 46        | 4.45%   |
| 2008    | 43        | 4.16%   |
| 2016    | 33        | 3.19%   |
| 2022    | 21        | 2.03%   |
| 2006    | 19        | 1.84%   |
| 2005    | 7         | 0.68%   |
| Unknown | 3         | 0.29%   |
| 2023    | 2         | 0.19%   |
| 2003    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 652       | 63.12%  |
| Desktop        | 352       | 34.08%  |
| Convertible    | 8         | 0.77%   |
| All in one     | 8         | 0.77%   |
| Mini pc        | 4         | 0.39%   |
| Tablet         | 3         | 0.29%   |
| Server         | 3         | 0.29%   |
| System on chip | 2         | 0.19%   |
| Phone          | 1         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 989       | 95.37%  |
| Enabled  | 48        | 4.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1032      | 99.9%   |
| Yes  | 1         | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 280       | 26.32%  |
| 4.01-8.0    | 247       | 23.21%  |
| 8.01-16.0   | 169       | 15.88%  |
| 16.01-24.0  | 147       | 13.82%  |
| 1.01-2.0    | 90        | 8.46%   |
| 32.01-64.0  | 56        | 5.26%   |
| 2.01-3.0    | 41        | 3.85%   |
| 0.51-1.0    | 20        | 1.88%   |
| 24.01-32.0  | 7         | 0.66%   |
| 64.01-256.0 | 6         | 0.56%   |
| 0.01-0.5    | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 410       | 34.42%  |
| 0.51-1.0   | 264       | 22.17%  |
| 2.01-3.0   | 222       | 18.64%  |
| 4.01-8.0   | 128       | 10.75%  |
| 3.01-4.0   | 106       | 8.9%    |
| 8.01-16.0  | 30        | 2.52%   |
| 0.01-0.5   | 22        | 1.85%   |
| 16.01-24.0 | 5         | 0.42%   |
| 24.01-32.0 | 2         | 0.17%   |
| 32.01-64.0 | 1         | 0.08%   |
| Unknown    | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 680       | 63.2%   |
| 2      | 275       | 25.56%  |
| 3      | 82        | 7.62%   |
| 4      | 20        | 1.86%   |
| 5      | 10        | 0.93%   |
| 0      | 6         | 0.56%   |
| 9      | 2         | 0.19%   |
| 6      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 612       | 58.56%  |
| Yes       | 433       | 41.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 898       | 86.85%  |
| No        | 136       | 13.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 769       | 74.16%  |
| No        | 268       | 25.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 583       | 55.52%  |
| No        | 467       | 44.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belarus | 1033      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Minsk        | 496       | 43.62%  |
| Vitebsk      | 115       | 10.11%  |
| Gomel        | 105       | 9.23%   |
| Mogilev      | 63        | 5.54%   |
| Hrodna       | 60        | 5.28%   |
| Brest        | 60        | 5.28%   |
| Babruysk     | 22        | 1.93%   |
| Orsha        | 18        | 1.58%   |
| Polatsk      | 17        | 1.5%    |
| Borisov      | 12        | 1.06%   |
| Mazyr        | 10        | 0.88%   |
| Lida         | 9         | 0.79%   |
| Baranovichi  | 9         | 0.79%   |
| Zhlobin      | 8         | 0.7%    |
| Slutsk       | 7         | 0.62%   |
| Bogushevichi | 7         | 0.62%   |
| Zhodzina     | 6         | 0.53%   |
| Pinsk        | 6         | 0.53%   |
| Vawkavysk    | 5         | 0.44%   |
| Navapolatsk  | 5         | 0.44%   |
| Klyetsk      | 5         | 0.44%   |
| Salihorsk    | 4         | 0.35%   |
| Drahichyn    | 4         | 0.35%   |
| Syanno       | 3         | 0.26%   |
| Smalyavichy  | 3         | 0.26%   |
| Slonim       | 3         | 0.26%   |
| Rahachow     | 3         | 0.26%   |
| Fedorovka    | 3         | 0.26%   |
| Dubovka      | 3         | 0.26%   |
| Baran'       | 3         | 0.26%   |
| Aleksandrovo | 3         | 0.26%   |
| Svyetlahorsk | 2         | 0.18%   |
| Snitovo      | 2         | 0.18%   |
| Rechytsa     | 2         | 0.18%   |
| Pruzhany     | 2         | 0.18%   |
| Ogorodniki   | 2         | 0.18%   |
| Murava       | 2         | 0.18%   |
| Masty        | 2         | 0.18%   |
| Maladzyechna | 2         | 0.18%   |
| Lyepyel'     | 2         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 233       | 375    | 15.88%  |
| Seagate                     | 231       | 364    | 15.75%  |
| Samsung Electronics         | 202       | 286    | 13.77%  |
| Toshiba                     | 145       | 228    | 9.88%   |
| Kingston                    | 99        | 136    | 6.75%   |
| Hitachi                     | 92        | 120    | 6.27%   |
| HGST                        | 55        | 87     | 3.75%   |
| SK hynix                    | 38        | 45     | 2.59%   |
| Intel                       | 36        | 66     | 2.45%   |
| Crucial                     | 29        | 37     | 1.98%   |
| Unknown                     | 28        | 36     | 1.91%   |
| SanDisk                     | 28        | 36     | 1.91%   |
| Patriot                     | 20        | 26     | 1.36%   |
| Gigabyte Technology         | 14        | 16     | 0.95%   |
| A-DATA Technology           | 14        | 17     | 0.95%   |
| Micron Technology           | 13        | 20     | 0.89%   |
| OCZ                         | 12        | 13     | 0.82%   |
| Fujitsu                     | 12        | 19     | 0.82%   |
| KingSpec                    | 10        | 18     | 0.68%   |
| GOODRAM                     | 10        | 11     | 0.68%   |
| SPCC                        | 9         | 14     | 0.61%   |
| Netac                       | 9         | 11     | 0.61%   |
| China                       | 9         | 12     | 0.61%   |
| Transcend                   | 7         | 9      | 0.48%   |
| KIOXIA                      | 7         | 27     | 0.48%   |
| Apacer                      | 7         | 8      | 0.48%   |
| Silicon Motion              | 6         | 7      | 0.41%   |
| Plextor                     | 6         | 7      | 0.41%   |
| Maxtor                      | 4         | 4      | 0.27%   |
| Kingston Technology Company | 4         | 4      | 0.27%   |
| JMicron Technology          | 4         | 4      | 0.27%   |
| XrayDisk                    | 3         | 3      | 0.2%    |
| XPG                         | 3         | 3      | 0.2%    |
| Smartbuy                    | 3         | 4      | 0.2%    |
| Phison Electronics          | 3         | 3      | 0.2%    |
| Lenovo                      | 3         | 6      | 0.2%    |
| KingDian                    | 3         | 5      | 0.2%    |
| Apple                       | 3         | 3      | 0.2%    |
| WD MediaMax                 | 2         | 2      | 0.14%   |
| TO Exter                    | 2         | 3      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                            | 27        | 1.7%    |
| Toshiba DT01ACA050 500GB                            | 23        | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB                      | 21        | 1.33%   |
| Seagate ST500LT012-1DG142 500GB                     | 19        | 1.2%    |
| Kingston SA400S37120G 120GB SSD                     | 19        | 1.2%    |
| Toshiba DT01ACA100 1TB                              | 17        | 1.07%   |
| Samsung SSD 860 EVO 500GB                           | 17        | 1.07%   |
| Samsung SSD 860 EVO 250GB                           | 17        | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 0.88%   |
| Kingston SA400S37240G 240GB SSD                     | 13        | 0.82%   |
| Toshiba DT01ACA200 2TB                              | 12        | 0.76%   |
| HGST HTS545050A7E680 500GB                          | 12        | 0.76%   |
| Seagate ST9320325AS 320GB                           | 10        | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 10        | 0.63%   |
| Crucial CT120BX500SSD1 120GB                        | 10        | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 9         | 0.57%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 9         | 0.57%   |
| HGST HTS721010A9E630 1TB                            | 9         | 0.57%   |
| Toshiba MQ04ABF100 1TB                              | 8         | 0.51%   |
| Toshiba MQ01ABD100 1TB                              | 8         | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                       | 8         | 0.51%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 0.51%   |
| Hitachi HTS543232A7A384 320GB                       | 8         | 0.51%   |
| Toshiba MQ01ABD032 320GB                            | 7         | 0.44%   |
| Seagate ST9500325AS 500GB                           | 7         | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB                      | 7         | 0.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 0.44%   |
| Kingston SUV400S37120G 120GB SSD                    | 7         | 0.44%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 0.44%   |
| HGST HTS541010A9E680 1TB                            | 7         | 0.44%   |
| Toshiba MQ01ABD075 752GB                            | 6         | 0.38%   |
| Seagate ST9250315AS 250GB                           | 6         | 0.38%   |
| Patriot Burst 120GB SSD                             | 6         | 0.38%   |
| OCZ VERTEX4 128GB SSD                               | 6         | 0.38%   |
| Hitachi HTS547575A9E384 752GB                       | 6         | 0.38%   |
| Hitachi HTS547550A9E384 500GB                       | 6         | 0.38%   |
| Hitachi HDS721010CLA330 1TB                         | 6         | 0.38%   |
| HGST HTS541010B7E610 1TB                            | 6         | 0.38%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                | 6         | 0.38%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 5         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 230       | 362    | 28.64%  |
| WDC                 | 213       | 324    | 26.53%  |
| Toshiba             | 136       | 215    | 16.94%  |
| Hitachi             | 92        | 120    | 11.46%  |
| HGST                | 55        | 87     | 6.85%   |
| Samsung Electronics | 50        | 78     | 6.23%   |
| Fujitsu             | 12        | 19     | 1.49%   |
| Maxtor              | 4         | 4      | 0.5%    |
| WD MediaMax         | 2         | 2      | 0.25%   |
| TO Exter            | 2         | 3      | 0.25%   |
| External            | 2         | 2      | 0.25%   |
| USB3.0              | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |
| SINTECHI            | 1         | 1      | 0.12%   |
| SAGE                | 1         | 1      | 0.12%   |
| Apple               | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 81        | 113    | 20.61%  |
| Kingston            | 73        | 103    | 18.58%  |
| Crucial             | 27        | 35     | 6.87%   |
| Patriot             | 18        | 24     | 4.58%   |
| SanDisk             | 14        | 22     | 3.56%   |
| WDC                 | 13        | 36     | 3.31%   |
| OCZ                 | 12        | 13     | 3.05%   |
| Intel               | 11        | 12     | 2.8%    |
| Gigabyte Technology | 11        | 13     | 2.8%    |
| KingSpec            | 10        | 18     | 2.54%   |
| A-DATA Technology   | 10        | 12     | 2.54%   |
| SPCC                | 9         | 14     | 2.29%   |
| GOODRAM             | 9         | 10     | 2.29%   |
| China               | 9         | 12     | 2.29%   |
| SK hynix            | 8         | 10     | 2.04%   |
| Transcend           | 7         | 9      | 1.78%   |
| Apacer              | 7         | 8      | 1.78%   |
| Plextor             | 6         | 7      | 1.53%   |
| Netac               | 6         | 8      | 1.53%   |
| JMicron Technology  | 4         | 4      | 1.02%   |
| XrayDisk            | 3         | 3      | 0.76%   |
| Unknown             | 3         | 3      | 0.76%   |
| Toshiba             | 3         | 3      | 0.76%   |
| Smartbuy            | 3         | 4      | 0.76%   |
| KingDian            | 3         | 5      | 0.76%   |
| Team                | 2         | 2      | 0.51%   |
| Seagate             | 2         | 2      | 0.51%   |
| Micron Technology   | 2         | 2      | 0.51%   |
| LITEONIT            | 2         | 2      | 0.51%   |
| Lexar               | 2         | 2      | 0.51%   |
| Corsair             | 2         | 8      | 0.51%   |
| Zheino              | 1         | 2      | 0.25%   |
| Union Memory        | 1         | 1      | 0.25%   |
| PNY                 | 1         | 5      | 0.25%   |
| OSCOO               | 1         | 1      | 0.25%   |
| OCZ-VERTEX3         | 1         | 3      | 0.25%   |
| OCZ-VERTEX          | 1         | 1      | 0.25%   |
| MSS4FV-MP           | 1         | 1      | 0.25%   |
| MicroFrom           | 1         | 1      | 0.25%   |
| M500                | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 698       | 1221   | 52.52%  |
| SSD     | 358       | 551    | 26.94%  |
| NVMe    | 241       | 349    | 18.13%  |
| MMC     | 26        | 36     | 1.96%   |
| Unknown | 6         | 6      | 0.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 848       | 1754   | 74.65%  |
| NVMe | 241       | 348    | 21.21%  |
| MMC  | 26        | 36     | 2.29%   |
| SAS  | 21        | 25     | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 696       | 1189   | 66.41%  |
| 0.51-1.0   | 270       | 417    | 25.76%  |
| 1.01-2.0   | 50        | 104    | 4.77%   |
| 2.01-3.0   | 11        | 21     | 1.05%   |
| 3.01-4.0   | 10        | 12     | 0.95%   |
| 4.01-10.0  | 8         | 25     | 0.76%   |
| 10.01-20.0 | 3         | 4      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 285       | 24.74%  |
| 251-500        | 274       | 23.78%  |
| 501-1000       | 156       | 13.54%  |
| 1-20           | 114       | 9.9%    |
| 51-100         | 106       | 9.2%    |
| 1001-2000      | 80        | 6.94%   |
| 21-50          | 75        | 6.51%   |
| Unknown        | 25        | 2.17%   |
| More than 3000 | 23        | 2%      |
| 2001-3000      | 14        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 513       | 43.59%  |
| 21-50          | 182       | 15.46%  |
| 101-250        | 132       | 11.21%  |
| 51-100         | 128       | 10.88%  |
| 251-500        | 95        | 8.07%   |
| 501-1000       | 60        | 5.1%    |
| Unknown        | 25        | 2.12%   |
| 1001-2000      | 22        | 1.87%   |
| 2001-3000      | 10        | 0.85%   |
| More than 3000 | 9         | 0.76%   |
| 0              | 1         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 8         | 10     | 2.81%   |
| HGST HTS545050A7E680 500GB         | 7         | 9      | 2.46%   |
| Seagate ST9320325AS 320GB          | 6         | 7      | 2.11%   |
| Seagate ST9500325AS 500GB          | 5         | 7      | 1.75%   |
| Toshiba MQ01ABF050 500GB           | 4         | 5      | 1.4%    |
| Toshiba DT01ACA100 1TB             | 4         | 5      | 1.4%    |
| Seagate ST9250315AS 250GB          | 4         | 4      | 1.4%    |
| Seagate ST500LT012-9WS142 500GB    | 4         | 4      | 1.4%    |
| Seagate ST500DM002-1BD142 500GB    | 4         | 11     | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 1.4%    |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 1.4%    |
| Hitachi HDS721010CLA330 1TB        | 4         | 5      | 1.4%    |
| Hitachi HDP725050GLA360 500GB      | 4         | 8      | 1.4%    |
| WDC WD20EARS-00MVWB0 2TB           | 3         | 6      | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB           | 3         | 3      | 1.05%   |
| Toshiba MQ01ABD032 320GB           | 3         | 3      | 1.05%   |
| Toshiba DT01ACA200 2TB             | 3         | 5      | 1.05%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 1.05%   |
| Samsung Electronics HD160JJ/ 160GB | 3         | 3      | 1.05%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 1.05%   |
| WDC WD5000AAKS-00A7B0 500GB        | 2         | 2      | 0.7%    |
| WDC WD3200BPVT-35ZEST0 320GB       | 2         | 6      | 0.7%    |
| WDC WD3200BEKT-60F3T1 320GB        | 2         | 2      | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB           | 2         | 3      | 0.7%    |
| Toshiba MK3259GSXP 320GB           | 2         | 3      | 0.7%    |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.7%    |
| Seagate ST9120822AS 120GB          | 2         | 3      | 0.7%    |
| Seagate ST3500320AS 500GB          | 2         | 3      | 0.7%    |
| Seagate ST340016A 40GB             | 2         | 3      | 0.7%    |
| Seagate ST3250820AS 250GB          | 2         | 2      | 0.7%    |
| Seagate ST3160812A 160GB           | 2         | 4      | 0.7%    |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 2      | 0.7%    |
| Samsung Electronics SP0802N 80GB   | 2         | 2      | 0.7%    |
| Samsung Electronics HD161HJ 160GB  | 2         | 3      | 0.7%    |
| Samsung Electronics HD103SJ 1TB    | 2         | 2      | 0.7%    |
| OCZ VERTEX460A 120GB SSD           | 2         | 2      | 0.7%    |
| OCZ VERTEX4 128GB SSD              | 2         | 2      | 0.7%    |
| Hitachi HTS722010K9SA00 100GB      | 2         | 2      | 0.7%    |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 0.7%    |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 69        | 93     | 24.91%  |
| WDC                 | 62        | 79     | 22.38%  |
| Hitachi             | 49        | 62     | 17.69%  |
| Toshiba             | 24        | 33     | 8.66%   |
| Samsung Electronics | 22        | 32     | 7.94%   |
| HGST                | 14        | 16     | 5.05%   |
| Fujitsu             | 6         | 8      | 2.17%   |
| OCZ                 | 5         | 5      | 1.81%   |
| Kingston            | 5         | 5      | 1.81%   |
| SK hynix            | 3         | 3      | 1.08%   |
| Crucial             | 3         | 3      | 1.08%   |
| WD MediaMax         | 2         | 2      | 0.72%   |
| Maxtor              | 2         | 2      | 0.72%   |
| SanDisk             | 1         | 1      | 0.36%   |
| PNY                 | 1         | 4      | 0.36%   |
| OCZ-VERTEX3         | 1         | 3      | 0.36%   |
| Micron Technology   | 1         | 1      | 0.36%   |
| LITEONIT            | 1         | 1      | 0.36%   |
| KingSpec            | 1         | 6      | 0.36%   |
| Intel               | 1         | 1      | 0.36%   |
| Corsair             | 1         | 4      | 0.36%   |
| Apacer              | 1         | 1      | 0.36%   |
| A-DATA Technology   | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 69        | 93     | 27.82%  |
| WDC                 | 62        | 79     | 25%     |
| Hitachi             | 49        | 62     | 19.76%  |
| Toshiba             | 24        | 33     | 9.68%   |
| Samsung Electronics | 20        | 30     | 8.06%   |
| HGST                | 14        | 16     | 5.65%   |
| Fujitsu             | 6         | 8      | 2.42%   |
| WD MediaMax         | 2         | 2      | 0.81%   |
| Maxtor              | 2         | 2      | 0.81%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 227       | 325    | 88.67%  |
| SSD  | 26        | 39     | 10.16%  |
| NVMe | 3         | 3      | 1.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-80HXZT3 500GB        | 1         | 1      | 10%     |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 10%     |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 10%     |
| Samsung Electronics SP0802N 80GB    | 1         | 1      | 10%     |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 10%     |
| Samsung Electronics HD252HJ 250GB   | 1         | 1      | 10%     |
| Maxtor STM380211AS 80GB             | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 10%     |
| HGST HTS545050B7E660 500GB          | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| Seagate             | 2         | 2      | 20%     |
| Maxtor              | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 609       | 1205   | 51.05%  |
| Detected | 321       | 581    | 26.91%  |
| Malfunc  | 253       | 367    | 21.21%  |
| Failed   | 10        | 10     | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 679       | 54.98%  |
| AMD                              | 224       | 18.14%  |
| Samsung Electronics              | 80        | 6.48%   |
| Nvidia                           | 51        | 4.13%   |
| Kingston Technology Company      | 30        | 2.43%   |
| SK hynix                         | 29        | 2.35%   |
| SanDisk                          | 25        | 2.02%   |
| JMicron Technology               | 21        | 1.7%    |
| Micron Technology                | 12        | 0.97%   |
| Marvell Technology Group         | 11        | 0.89%   |
| Silicon Motion                   | 10        | 0.81%   |
| Phison Electronics               | 10        | 0.81%   |
| ASMedia Technology               | 9         | 0.73%   |
| Toshiba America Info Systems     | 8         | 0.65%   |
| KIOXIA                           | 7         | 0.57%   |
| VIA Technologies                 | 5         | 0.4%    |
| Silicon Integrated Systems [SiS] | 4         | 0.32%   |
| Realtek Semiconductor            | 3         | 0.24%   |
| Netac Technology                 | 3         | 0.24%   |
| Lenovo                           | 3         | 0.24%   |
| ADATA Technology                 | 3         | 0.24%   |
| Synopsys                         | 1         | 0.08%   |
| Solid State Storage Technology   | 1         | 0.08%   |
| Silicon Image                    | 1         | 0.08%   |
| O2 Micro                         | 1         | 0.08%   |
| Micron/Crucial Technology        | 1         | 0.08%   |
| Integrated Technology Express    | 1         | 0.08%   |
| Broadcom / LSI                   | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 113       | 7.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 69        | 4.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 50        | 3.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 48        | 3.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 47        | 3.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 36        | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 35        | 2.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 34        | 2.28%   |
| Nvidia MCP61 SATA Controller                                                            | 33        | 2.21%   |
| Nvidia MCP61 IDE                                                                        | 33        | 2.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 33        | 2.21%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 27        | 1.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26        | 1.74%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 24        | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 24        | 1.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 22        | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 21        | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 20        | 1.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 18        | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 15        | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15        | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 15        | 1%      |
| Intel SSD 660P Series                                                                   | 14        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 13        | 0.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 12        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 0.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 0.8%    |
| AMD FCH IDE Controller                                                                  | 12        | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 11        | 0.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 11        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 767       | 59.27%  |
| NVMe | 242       | 18.7%   |
| IDE  | 240       | 18.55%  |
| RAID | 44        | 3.4%    |
| SCSI | 1         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 729       | 70.57%  |
| AMD    | 301       | 29.14%  |
| ARM    | 3         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 15        | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.96%   |
| AMD E-450 APU with Radeon HD Graphics         | 10        | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.77%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 0.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.67%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.58%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 6         | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 0.58%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 0.58%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 0.58%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 0.58%   |
| AMD Athlon II X2 240 Processor                | 6         | 0.58%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+    | 6         | 0.58%   |
| AMD A4-4300M APU with Radeon HD Graphics      | 6         | 0.58%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 0.48%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.48%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 5         | 0.48%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.48%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.48%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 5         | 0.48%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.48%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 5         | 0.48%   |
| Intel Celeron CPU B820 @ 1.70GHz              | 5         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 168       | 16.2%   |
| Intel Core i7           | 113       | 10.9%   |
| Intel Celeron           | 91        | 8.78%   |
| Intel Core i3           | 84        | 8.1%    |
| Intel Pentium           | 62        | 5.98%   |
| AMD Ryzen 5             | 58        | 5.59%   |
| Other                   | 52        | 5.01%   |
| Intel Core 2 Duo        | 46        | 4.44%   |
| Intel Atom              | 37        | 3.57%   |
| AMD Athlon 64 X2        | 24        | 2.31%   |
| AMD Ryzen 7             | 23        | 2.22%   |
| AMD Athlon II X2        | 22        | 2.12%   |
| AMD FX                  | 21        | 2.03%   |
| Intel Pentium Dual-Core | 16        | 1.54%   |
| Intel Xeon              | 14        | 1.35%   |
| AMD Ryzen 3             | 14        | 1.35%   |
| AMD A4                  | 14        | 1.35%   |
| AMD E                   | 13        | 1.25%   |
| AMD A6                  | 11        | 1.06%   |
| AMD Athlon II X3        | 10        | 0.96%   |
| AMD Phenom II X4        | 9         | 0.87%   |
| AMD E1                  | 9         | 0.87%   |
| Intel Pentium Dual      | 8         | 0.77%   |
| AMD A8                  | 8         | 0.77%   |
| AMD A10                 | 8         | 0.77%   |
| Intel Pentium Silver    | 7         | 0.68%   |
| AMD Athlon              | 7         | 0.68%   |
| Intel Genuine           | 6         | 0.58%   |
| Intel Core i9           | 6         | 0.58%   |
| Intel Pentium 4         | 5         | 0.48%   |
| Intel Celeron Dual-Core | 5         | 0.48%   |
| AMD Athlon X4           | 5         | 0.48%   |
| AMD Athlon II           | 5         | 0.48%   |
| AMD Turion II           | 4         | 0.39%   |
| AMD E2                  | 4         | 0.39%   |
| AMD Athlon II X4        | 4         | 0.39%   |
| Intel Core 2 Solo       | 3         | 0.29%   |
| Intel Core 2 Quad       | 3         | 0.29%   |
| Intel Core 2            | 3         | 0.29%   |
| AMD Ryzen 9             | 3         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 509       | 48.57%  |
| 4       | 291       | 27.77%  |
| 6       | 83        | 7.92%   |
| 1       | 55        | 5.25%   |
| 8       | 43        | 4.1%    |
| Unknown | 35        | 3.34%   |
| 3       | 17        | 1.62%   |
| 12      | 6         | 0.57%   |
| 10      | 6         | 0.57%   |
| 14      | 3         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1030      | 99.71%  |
| 2      | 3         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 542       | 51.62%  |
| 1       | 473       | 45.05%  |
| Unknown | 35        | 3.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 997       | 96.33%  |
| Unknown        | 21        | 2.03%   |
| 32-bit         | 17        | 1.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 193       | 18.02%  |
| 0x206a7    | 76        | 7.1%    |
| 0x306a9    | 64        | 5.98%   |
| 0x1067a    | 47        | 4.39%   |
| 0x010000c8 | 39        | 3.64%   |
| 0x306c3    | 38        | 3.55%   |
| 0x806ea    | 27        | 2.52%   |
| 0x806c1    | 24        | 2.24%   |
| 0x30678    | 22        | 2.05%   |
| 0x906ea    | 21        | 1.96%   |
| 0x806ec    | 18        | 1.68%   |
| 0x06001119 | 18        | 1.68%   |
| 0x40651    | 17        | 1.59%   |
| 0x106ca    | 17        | 1.59%   |
| 0x6fd      | 16        | 1.49%   |
| 0x406e3    | 16        | 1.49%   |
| 0x05000119 | 14        | 1.31%   |
| 0x906e9    | 13        | 1.21%   |
| 0x010000c7 | 13        | 1.21%   |
| 0x506e3    | 12        | 1.12%   |
| 0x506c9    | 12        | 1.12%   |
| 0x306d4    | 12        | 1.12%   |
| 0x806e9    | 11        | 1.03%   |
| 0x706a1    | 10        | 0.93%   |
| 0x10676    | 10        | 0.93%   |
| 0x0a50000c | 10        | 0.93%   |
| 0x08108102 | 10        | 0.93%   |
| 0x06000852 | 10        | 0.93%   |
| 0x10661    | 9         | 0.84%   |
| 0x08608103 | 9         | 0.84%   |
| 0x0800820d | 9         | 0.84%   |
| 0x20652    | 8         | 0.75%   |
| 0x106c2    | 8         | 0.75%   |
| 0x08600106 | 8         | 0.75%   |
| 0x03000027 | 8         | 0.75%   |
| 0x706e5    | 7         | 0.65%   |
| 0x6fb      | 7         | 0.65%   |
| 0x406c4    | 7         | 0.65%   |
| 0x406c3    | 7         | 0.65%   |
| 0x20655    | 7         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 138       | 13.29%  |
| SandyBridge      | 83        | 8%      |
| IvyBridge        | 79        | 7.61%   |
| K10              | 67        | 6.45%   |
| Haswell          | 66        | 6.36%   |
| Penryn           | 65        | 6.26%   |
| Core             | 43        | 4.14%   |
| Silvermont       | 40        | 3.85%   |
| Piledriver       | 38        | 3.66%   |
| Skylake          | 35        | 3.37%   |
| K8 Hammer        | 31        | 2.99%   |
| Bonnell          | 30        | 2.89%   |
| Unknown          | 28        | 2.7%    |
| Zen+             | 27        | 2.6%    |
| Zen 2            | 26        | 2.5%    |
| TigerLake        | 26        | 2.5%    |
| Zen              | 20        | 1.93%   |
| Zen 3            | 19        | 1.83%   |
| Goldmont plus    | 18        | 1.73%   |
| Bobcat           | 18        | 1.73%   |
| Westmere         | 16        | 1.54%   |
| Icelake          | 16        | 1.54%   |
| Goldmont         | 15        | 1.45%   |
| Broadwell        | 14        | 1.35%   |
| CometLake        | 12        | 1.16%   |
| K10 Llano        | 10        | 0.96%   |
| Excavator        | 9         | 0.87%   |
| Alderlake Hybrid | 9         | 0.87%   |
| NetBurst         | 7         | 0.67%   |
| Puma             | 6         | 0.58%   |
| Nehalem          | 6         | 0.58%   |
| Jaguar           | 6         | 0.58%   |
| P6               | 5         | 0.48%   |
| Bulldozer        | 4         | 0.39%   |
| Steamroller      | 3         | 0.29%   |
| Tremont          | 2         | 0.19%   |
| K8 & K10 hybrid  | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 563       | 44.19%  |
| Nvidia                           | 419       | 32.89%  |
| AMD                              | 285       | 22.37%  |
| Silicon Integrated Systems [SiS] | 3         | 0.24%   |
| ASPEED Technology                | 2         | 0.16%   |
| Matrox Electronics Systems       | 1         | 0.08%   |
| ATI Technologies                 | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 65        | 4.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 52        | 3.89%   |
| Intel UHD Graphics 620                                                                   | 32        | 2.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 1.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 1.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 1.42%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 19        | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 1.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 16        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.12%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 1.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 0.97%   |
| Intel HD Graphics 620                                                                    | 13        | 0.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.97%   |
| AMD Lucienne                                                                             | 13        | 0.97%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 0.9%    |
| Intel HD Graphics 630                                                                    | 12        | 0.9%    |
| Intel HD Graphics 5500                                                                   | 12        | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 0.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.82%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 10        | 0.75%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 10        | 0.75%   |
| Intel HD Graphics 500                                                                    | 10        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.67%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 9         | 0.67%   |
| Nvidia GM108M [GeForce MX110]                                                            | 8         | 0.6%    |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 338       | 32.59%  |
| 1 x Nvidia      | 230       | 22.18%  |
| 1 x AMD         | 197       | 19%     |
| Intel + Nvidia  | 172       | 16.59%  |
| Intel + AMD     | 45        | 4.34%   |
| 2 x AMD         | 31        | 2.99%   |
| AMD + Nvidia    | 13        | 1.25%   |
| Other           | 3         | 0.29%   |
| 1 x SiS         | 3         | 0.29%   |
| 2 x Nvidia      | 1         | 0.1%    |
| 2 x Intel       | 1         | 0.1%    |
| Nvidia + ASPEED | 1         | 0.1%    |
| 1 x Matrox      | 1         | 0.1%    |
| 1 x ASPEED      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 837       | 78.59%  |
| Proprietary | 181       | 17%     |
| Unknown     | 47        | 4.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 393       | 36.39%  |
| 1.01-2.0   | 249       | 23.06%  |
| 0.01-0.5   | 227       | 21.02%  |
| 0.51-1.0   | 104       | 9.63%   |
| 3.01-4.0   | 65        | 6.02%   |
| 7.01-8.0   | 17        | 1.57%   |
| 5.01-6.0   | 15        | 1.39%   |
| 2.01-3.0   | 5         | 0.46%   |
| 8.01-16.0  | 4         | 0.37%   |
| 4.01-5.0   | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 172       | 16.09%  |
| AU Optronics            | 143       | 13.38%  |
| Goldstar                | 105       | 9.82%   |
| BOE                     | 102       | 9.54%   |
| Chimei Innolux          | 92        | 8.61%   |
| LG Display              | 88        | 8.23%   |
| Chi Mei Optoelectronics | 50        | 4.68%   |
| Philips                 | 42        | 3.93%   |
| Dell                    | 40        | 3.74%   |
| BenQ                    | 28        | 2.62%   |
| AOC                     | 26        | 2.43%   |
| ViewSonic               | 18        | 1.68%   |
| PANDA                   | 17        | 1.59%   |
| Lenovo                  | 12        | 1.12%   |
| Hewlett-Packard         | 12        | 1.12%   |
| LG Philips              | 10        | 0.94%   |
| HannStar                | 9         | 0.84%   |
| CPT                     | 9         | 0.84%   |
| Acer                    | 9         | 0.84%   |
| Ancor Communications    | 8         | 0.75%   |
| Unknown                 | 7         | 0.65%   |
| Sharp                   | 7         | 0.65%   |
| NEC Computers           | 7         | 0.65%   |
| Sony                    | 6         | 0.56%   |
| Iiyama                  | 6         | 0.56%   |
| Apple                   | 6         | 0.56%   |
| LG Electronics          | 5         | 0.47%   |
| XYK                     | 3         | 0.28%   |
| ASUSTek Computer        | 3         | 0.28%   |
| Valve                   | 2         | 0.19%   |
| Plain Tree Systems      | 2         | 0.19%   |
| LGD                     | 2         | 0.19%   |
| Toshiba                 | 1         | 0.09%   |
| SKK                     | 1         | 0.09%   |
| Seiko/Epson             | 1         | 0.09%   |
| RGT                     | 1         | 0.09%   |
| Quanta Display          | 1         | 0.09%   |
| PCL                     | 1         | 0.09%   |
| Packard Bell            | 1         | 0.09%   |
| MStar                   | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 14        | 1.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 12        | 1.11%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 10        | 0.92%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 8         | 0.74%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.74%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.65%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 7         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.55%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.55%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                     | 6         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.55%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 6         | 0.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.55%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 330x210mm 15.4-inch     | 5         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 5         | 0.46%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 5         | 0.46%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                    | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.46%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 4         | 0.37%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch     | 4         | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.37%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 4         | 0.37%   |
| Goldstar L1919S GSM4AF2 1280x1024 380x300mm 19.1-inch                    | 4         | 0.37%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 4         | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 4         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 4         | 0.37%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 4         | 0.37%   |
| XYK DVI XYK2360 1920x1080 477x268mm 21.5-inch                            | 3         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 422       | 40.46%  |
| 1366x768 (WXGA)    | 266       | 25.5%   |
| 1280x1024 (SXGA)   | 61        | 5.85%   |
| 1600x900 (HD+)     | 49        | 4.7%    |
| 3840x2160 (4K)     | 38        | 3.64%   |
| 1440x900 (WXGA+)   | 32        | 3.07%   |
| 2560x1440 (QHD)    | 30        | 2.88%   |
| 1680x1050 (WSXGA+) | 29        | 2.78%   |
| 1280x800 (WXGA)    | 28        | 2.68%   |
| 1024x600           | 20        | 1.92%   |
| 2560x1080          | 10        | 0.96%   |
| 1920x1200 (WUXGA)  | 10        | 0.96%   |
| 2560x1600          | 5         | 0.48%   |
| 1360x768           | 5         | 0.48%   |
| 1024x768 (XGA)     | 5         | 0.48%   |
| 2288x1287          | 4         | 0.38%   |
| 3440x1440          | 3         | 0.29%   |
| 2880x1800          | 3         | 0.29%   |
| 800x1280           | 2         | 0.19%   |
| 3840x2400          | 2         | 0.19%   |
| 2160x1440          | 2         | 0.19%   |
| 1600x1200          | 2         | 0.19%   |
| 1152x864           | 2         | 0.19%   |
| Unknown            | 2         | 0.19%   |
| 4480x1200          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 3072x1920          | 1         | 0.1%    |
| 2736x1824          | 1         | 0.1%    |
| 2400x1600          | 1         | 0.1%    |
| 2240x1400          | 1         | 0.1%    |
| 2048x1536          | 1         | 0.1%    |
| 1920x540           | 1         | 0.1%    |
| 1920x1440          | 1         | 0.1%    |
| 1680x945           | 1         | 0.1%    |
| 1400x1050          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 407       | 38.04%  |
| 17      | 93        | 8.69%   |
| 21      | 79        | 7.38%   |
| 23      | 75        | 7.01%   |
| 13      | 55        | 5.14%   |
| 19      | 54        | 5.05%   |
| 24      | 47        | 4.39%   |
| 14      | 47        | 4.39%   |
| 27      | 35        | 3.27%   |
| Unknown | 26        | 2.43%   |
| 18      | 21        | 1.96%   |
| 10      | 20        | 1.87%   |
| 22      | 18        | 1.68%   |
| 16      | 14        | 1.31%   |
| 20      | 13        | 1.21%   |
| 34      | 12        | 1.12%   |
| 31      | 11        | 1.03%   |
| 40      | 7         | 0.65%   |
| 11      | 6         | 0.56%   |
| 12      | 5         | 0.47%   |
| 142     | 4         | 0.37%   |
| 72      | 4         | 0.37%   |
| 54      | 4         | 0.37%   |
| 84      | 2         | 0.19%   |
| 52      | 2         | 0.19%   |
| 46      | 2         | 0.19%   |
| 7       | 2         | 0.19%   |
| 55      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |
| 9       | 1         | 0.09%   |
| 8       | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 510       | 48.25%  |
| 401-500        | 148       | 14%     |
| 501-600        | 145       | 13.72%  |
| 351-400        | 112       | 10.6%   |
| 201-300        | 58        | 5.49%   |
| Unknown        | 26        | 2.46%   |
| 601-700        | 15        | 1.42%   |
| 701-800        | 12        | 1.14%   |
| 1001-1500      | 9         | 0.85%   |
| 801-900        | 7         | 0.66%   |
| 1501-2000      | 6         | 0.57%   |
| More than 2000 | 4         | 0.38%   |
| 101-200        | 2         | 0.19%   |
| 1-100          | 2         | 0.19%   |
| 901-1000       | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 773       | 76.84%  |
| 16/10   | 110       | 10.93%  |
| 5/4     | 59        | 5.86%   |
| Unknown | 24        | 2.39%   |
| 4/3     | 14        | 1.39%   |
| 21/9    | 12        | 1.19%   |
| 3/2     | 7         | 0.7%    |
| 1.00    | 5         | 0.5%    |
| 0.67    | 2         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 412       | 38.69%  |
| 201-250        | 182       | 17.09%  |
| 151-200        | 86        | 8.08%   |
| 81-90          | 78        | 7.32%   |
| 121-130        | 52        | 4.88%   |
| 141-150        | 45        | 4.23%   |
| 301-350        | 36        | 3.38%   |
| Unknown        | 26        | 2.44%   |
| 351-500        | 23        | 2.16%   |
| 71-80          | 22        | 2.07%   |
| 41-50          | 21        | 1.97%   |
| More than 1000 | 17        | 1.6%    |
| 251-300        | 16        | 1.5%    |
| 131-140        | 15        | 1.41%   |
| 501-1000       | 10        | 0.94%   |
| 111-120        | 8         | 0.75%   |
| 51-60          | 6         | 0.56%   |
| 61-70          | 5         | 0.47%   |
| 1-40           | 3         | 0.28%   |
| 91-100         | 2         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 354       | 34.04%  |
| 101-120       | 346       | 33.27%  |
| 121-160       | 245       | 23.56%  |
| 161-240       | 31        | 2.98%   |
| Unknown       | 26        | 2.5%    |
| 1-50          | 22        | 2.12%   |
| More than 240 | 16        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 906       | 86.45%  |
| 2     | 100       | 9.54%   |
| 0     | 37        | 3.53%   |
| 3     | 5         | 0.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 632       | 41.01%  |
| Intel                                  | 279       | 18.11%  |
| Qualcomm Atheros                       | 274       | 17.78%  |
| Broadcom                               | 109       | 7.07%   |
| Nvidia                                 | 38        | 2.47%   |
| Marvell Technology Group               | 32        | 2.08%   |
| Ralink                                 | 24        | 1.56%   |
| TP-Link                                | 22        | 1.43%   |
| Ralink Technology                      | 22        | 1.43%   |
| Broadcom Limited                       | 17        | 1.1%    |
| MediaTek                               | 12        | 0.78%   |
| Huawei Technologies                    | 8         | 0.52%   |
| D-Link                                 | 8         | 0.52%   |
| Xiaomi                                 | 5         | 0.32%   |
| VIA Technologies                       | 5         | 0.32%   |
| Qualcomm Atheros Communications        | 4         | 0.26%   |
| Qualcomm                               | 4         | 0.26%   |
| JMicron Technology                     | 4         | 0.26%   |
| D-Link System                          | 4         | 0.26%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.19%   |
| Sierra Wireless                        | 3         | 0.19%   |
| Fibocom                                | 3         | 0.19%   |
| Attansic Technology                    | 3         | 0.19%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.13%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.13%   |
| IMC Networks                           | 2         | 0.13%   |
| Hewlett-Packard                        | 2         | 0.13%   |
| ASIX Electronics                       | 2         | 0.13%   |
| Aquantia                               | 2         | 0.13%   |
| Texas Instruments                      | 1         | 0.06%   |
| STMicroelectronics                     | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Samsung Electronics                    | 1         | 0.06%   |
| Philips (or NXP)                       | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| Mercucys                               | 1         | 0.06%   |
| Lenovo                                 | 1         | 0.06%   |
| HTC (High Tech Computer)               | 1         | 0.06%   |
| HMD Global                             | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 451       | 25.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 110       | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 55        | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 41        | 2.33%   |
| Intel Wireless 8265 / 8275                                              | 41        | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 1.59%   |
| Nvidia MCP61 Ethernet                                                   | 26        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 1.08%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 0.97%   |
| Ralink MT7601U Wireless Adapter                                         | 16        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 14        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 13        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 12        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 11        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.63%   |
| Intel Wireless 7265                                                     | 11        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 10        | 0.57%   |
| Intel Wireless 7260                                                     | 10        | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.51%   |
| Intel I211 Gigabit Network Connection                                   | 9         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                    | 9         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 8         | 0.45%   |
| Intel WiFi Link 5100                                                    | 8         | 0.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                       | 7         | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 238       | 29.49%  |
| Qualcomm Atheros                  | 218       | 27.01%  |
| Realtek Semiconductor             | 154       | 19.08%  |
| Broadcom                          | 80        | 9.91%   |
| Ralink                            | 24        | 2.97%   |
| Ralink Technology                 | 22        | 2.73%   |
| TP-Link                           | 19        | 2.35%   |
| MediaTek                          | 12        | 1.49%   |
| Broadcom Limited                  | 10        | 1.24%   |
| D-Link                            | 8         | 0.99%   |
| Qualcomm Atheros Communications   | 4         | 0.5%    |
| Sierra Wireless                   | 3         | 0.37%   |
| Fibocom                           | 3         | 0.37%   |
| Qualcomm                          | 2         | 0.25%   |
| IMC Networks                      | 2         | 0.25%   |
| Texas Instruments                 | 1         | 0.12%   |
| Philips (or NXP)                  | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Mercucys                          | 1         | 0.12%   |
| Marvell Technology Group          | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |
| D-Link System                     | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 55        | 6.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 5.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 41        | 5.06%   |
| Intel Wireless 8265 / 8275                                              | 41        | 5.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 33        | 4.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 2.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 2.59%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 2.34%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 2.1%    |
| Ralink MT7601U Wireless Adapter                                         | 16        | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.36%   |
| Intel Wireless 7265                                                     | 11        | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 1.23%   |
| Intel Wireless 7260                                                     | 10        | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.99%   |
| Intel WiFi Link 5100                                                    | 8         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.86%   |
| Intel Wireless 8260                                                     | 7         | 0.86%   |
| Intel Wireless 3165                                                     | 7         | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.62%   |
| Intel Centrino Wireless-N 130                                           | 5         | 0.62%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 588       | 63.16%  |
| Qualcomm Atheros                       | 89        | 9.56%   |
| Intel                                  | 87        | 9.34%   |
| Broadcom                               | 42        | 4.51%   |
| Nvidia                                 | 38        | 4.08%   |
| Marvell Technology Group               | 31        | 3.33%   |
| Broadcom Limited                       | 7         | 0.75%   |
| Xiaomi                                 | 5         | 0.54%   |
| VIA Technologies                       | 5         | 0.54%   |
| Huawei Technologies                    | 5         | 0.54%   |
| JMicron Technology                     | 4         | 0.43%   |
| TP-Link                                | 3         | 0.32%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.32%   |
| D-Link System                          | 3         | 0.32%   |
| Attansic Technology                    | 3         | 0.32%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.21%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.21%   |
| Qualcomm                               | 2         | 0.21%   |
| ASIX Electronics                       | 2         | 0.21%   |
| Aquantia                               | 2         | 0.21%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| Samsung Electronics                    | 1         | 0.11%   |
| Motorola PCS                           | 1         | 0.11%   |
| Lenovo                                 | 1         | 0.11%   |
| HTC (High Tech Computer)               | 1         | 0.11%   |
| HMD Global                             | 1         | 0.11%   |
| Davicom Semiconductor                  | 1         | 0.11%   |
| Apple                                  | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 451       | 47.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 110       | 11.66%  |
| Nvidia MCP61 Ethernet                                                          | 26        | 2.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 14        | 1.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 13        | 1.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 11        | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 10        | 1.06%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                           | 9         | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 0.74%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.74%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.64%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 6         | 0.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 5         | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 0.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 0.53%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 4         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.42%   |
| Nvidia MCP65 Ethernet                                                          | 4         | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.42%   |
| Intel Ethernet Connection (14) I219-V                                          | 4         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.42%   |
| Huawei MAR-LX1M                                                                | 4         | 0.42%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.42%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 3         | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.32%   |
| Nvidia MCP55 Ethernet                                                          | 3         | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 3         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 896       | 53.62%  |
| WiFi     | 769       | 46.02%  |
| Modem    | 5         | 0.3%    |
| Unknown  | 1         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 650       | 60.19%  |
| Ethernet | 430       | 39.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 592       | 57.2%   |
| 1     | 420       | 40.58%  |
| 0     | 15        | 1.45%   |
| 3     | 7         | 0.68%   |
| 4     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1022      | 98.36%  |
| Yes  | 17        | 1.64%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 195       | 33.05%  |
| Realtek Semiconductor           | 85        | 14.41%  |
| Qualcomm Atheros Communications | 68        | 11.53%  |
| IMC Networks                    | 42        | 7.12%   |
| Broadcom                        | 35        | 5.93%   |
| Lite-On Technology              | 29        | 4.92%   |
| Cambridge Silicon Radio         | 29        | 4.92%   |
| Foxconn / Hon Hai               | 25        | 4.24%   |
| Ralink                          | 15        | 2.54%   |
| ASUSTek Computer                | 15        | 2.54%   |
| Foxconn International           | 10        | 1.69%   |
| Hewlett-Packard                 | 8         | 1.36%   |
| Toshiba                         | 7         | 1.19%   |
| Apple                           | 4         | 0.68%   |
| Realtek                         | 3         | 0.51%   |
| Ralink Technology               | 3         | 0.51%   |
| Dell                            | 3         | 0.51%   |
| Taiyo Yuden                     | 2         | 0.34%   |
| Qcom                            | 2         | 0.34%   |
| MediaTek                        | 2         | 0.34%   |
| Integrated System Solution      | 2         | 0.34%   |
| USI                             | 1         | 0.17%   |
| TP-Link                         | 1         | 0.17%   |
| Micro Star International        | 1         | 0.17%   |
| Marvell Semiconductor           | 1         | 0.17%   |
| Chicony Electronics             | 1         | 0.17%   |
| Alps Electric                   | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 80        | 13.54%  |
| Realtek Bluetooth Radio                             | 56        | 9.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 43        | 7.28%   |
| Intel AX201 Bluetooth                               | 33        | 5.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29        | 4.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 3.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 20        | 3.38%   |
| Intel AX200 Bluetooth                               | 17        | 2.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 2.71%   |
| Ralink RT3290 Bluetooth                             | 15        | 2.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 2.2%    |
| IMC Networks Bluetooth Radio                        | 13        | 2.2%    |
| Lite-On Bluetooth Device                            | 11        | 1.86%   |
| Realtek 802.11ac WLAN Adapter                       | 10        | 1.69%   |
| Foxconn International BCM43142A0 Bluetooth module   | 10        | 1.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 1.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 1.52%   |
| IMC Networks Bluetooth Device                       | 8         | 1.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 8         | 1.35%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.18%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.18%   |
| Broadcom BCM2070 Bluetooth Device                   | 7         | 1.18%   |
| Qualcomm Atheros Bluetooth                          | 6         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.02%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.02%   |
| IMC Networks Wireless_Device                        | 6         | 1.02%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.68%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.68%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.68%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.51%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.51%   |
| Intel Bluetooth Device                              | 3         | 0.51%   |
| IMC Networks Bluetooth USB Host Controller          | 3         | 0.51%   |
| Foxconn / Hon Hai BCM43142A0                        | 3         | 0.51%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.51%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.51%   |
| ASUS BT-270 Bluetooth Adapter                       | 3         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 706       | 52.26%  |
| AMD                              | 297       | 21.98%  |
| Nvidia                           | 253       | 18.73%  |
| C-Media Electronics              | 18        | 1.33%   |
| Creative Labs                    | 11        | 0.81%   |
| Logitech                         | 10        | 0.74%   |
| JMTek                            | 7         | 0.52%   |
| Texas Instruments                | 6         | 0.44%   |
| Silicon Integrated Systems [SiS] | 4         | 0.3%    |
| Generalplus Technology           | 3         | 0.22%   |
| Conexant Systems                 | 3         | 0.22%   |
| Tenx Technology                  | 2         | 0.15%   |
| SteelSeries ApS                  | 2         | 0.15%   |
| M-Audio                          | 2         | 0.15%   |
| Kingston Technology              | 2         | 0.15%   |
| GYROCOM C&C                      | 2         | 0.15%   |
| ESS Technology                   | 2         | 0.15%   |
| Yamaha                           | 1         | 0.07%   |
| VIA Technologies                 | 1         | 0.07%   |
| ROCCAT                           | 1         | 0.07%   |
| Realtek Semiconductor            | 1         | 0.07%   |
| Plantronics                      | 1         | 0.07%   |
| Pixart Imaging                   | 1         | 0.07%   |
| NXP Semiconductors               | 1         | 0.07%   |
| JBL                              | 1         | 0.07%   |
| iCreate Technologies             | 1         | 0.07%   |
| Huawei Technologies              | 1         | 0.07%   |
| GN Netcom                        | 1         | 0.07%   |
| FIFINE Microphones               | 1         | 0.07%   |
| Edifier Technology               | 1         | 0.07%   |
| Creative Technology              | 1         | 0.07%   |
| BR25                             | 1         | 0.07%   |
| BEHRINGER International          | 1         | 0.07%   |
| ATI Technologies                 | 1         | 0.07%   |
| ASUSTek Computer                 | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| A4Tech                           | 1         | 0.07%   |
| Unknown                          | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 92        | 5.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 86        | 5.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 76        | 4.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 66        | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 63        | 3.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 52        | 3.24%   |
| AMD FCH Azalia Controller                                                                         | 51        | 3.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 2.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 38        | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 37        | 2.31%   |
| Nvidia MCP61 High Definition Audio                                                                | 32        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 32        | 1.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 30        | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 30        | 1.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 1.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 24        | 1.5%    |
| Intel 8 Series HD Audio Controller                                                                | 24        | 1.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 23        | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 23        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 1.18%   |
| Nvidia High Definition Audio Controller                                                           | 18        | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 18        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 1.06%   |
| AMD Trinity HDMI Audio Controller                                                                 | 17        | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 0.87%   |
| AMD Wrestler HDMI Audio                                                                           | 14        | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 14        | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 13        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 13        | 0.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 0.81%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.75%   |
| Intel 200 Series PCH HD Audio                                                                     | 12        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 189       | 20.32%  |
| Samsung Electronics   | 173       | 18.6%   |
| SK hynix              | 137       | 14.73%  |
| Kingston              | 122       | 13.12%  |
| Micron Technology     | 70        | 7.53%   |
| Crucial               | 58        | 6.24%   |
| Elpida                | 26        | 2.8%    |
| Ramaxel Technology    | 17        | 1.83%   |
| Nanya Technology      | 16        | 1.72%   |
| Patriot               | 15        | 1.61%   |
| A-DATA Technology     | 14        | 1.51%   |
| G.Skill               | 13        | 1.4%    |
| Corsair               | 11        | 1.18%   |
| Transcend             | 7         | 0.75%   |
| Silicon Power         | 7         | 0.75%   |
| GOODRAM               | 7         | 0.75%   |
| ASint Technology      | 7         | 0.75%   |
| GeIL                  | 5         | 0.54%   |
| Team                  | 4         | 0.43%   |
| Apacer                | 4         | 0.43%   |
| 48spaces              | 4         | 0.43%   |
| Unknown               | 4         | 0.43%   |
| Unknown (ABCD)        | 3         | 0.32%   |
| TakeMS                | 2         | 0.22%   |
| Qumo                  | 2         | 0.22%   |
| Kllisre               | 2         | 0.22%   |
| Kingmax               | 2         | 0.22%   |
| Wilk Elektronik       | 1         | 0.11%   |
| Wilk                  | 1         | 0.11%   |
| Unknown (89F7)        | 1         | 0.11%   |
| SHARETRONIC           | 1         | 0.11%   |
| Qimonda               | 1         | 0.11%   |
| PNY                   | 1         | 0.11%   |
| Kingmax Semiconductor | 1         | 0.11%   |
| Goldkey               | 1         | 0.11%   |
| AMD                   | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 12        | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 11        | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 9         | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 9         | 0.88%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 7         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 7         | 0.69%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 7         | 0.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 7         | 0.69%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s  | 7         | 0.69%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 6         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 6         | 0.59%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 6         | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 6         | 0.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s     | 6         | 0.59%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s    | 6         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 5         | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 5         | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 5         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 5         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 5         | 0.49%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 3200MT/s | 5         | 0.49%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 5         | 0.49%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s    | 5         | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 5         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 5         | 0.49%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s     | 5         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 4         | 0.39%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s              | 4         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s             | 4         | 0.39%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                    | 4         | 0.39%   |
| Unknown RAM Module 1024MB DIMM DDR2                       | 4         | 0.39%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                    | 4         | 0.39%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 4         | 0.39%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 4         | 0.39%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s           | 4         | 0.39%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 4         | 0.39%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s     | 4         | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s  | 4         | 0.39%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 4         | 0.39%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 4         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 330       | 41.41%  |
| DDR4    | 230       | 28.86%  |
| DDR2    | 76        | 9.54%   |
| Unknown | 75        | 9.41%   |
| SDRAM   | 50        | 6.27%   |
| LPDDR4  | 16        | 2.01%   |
| DDR     | 9         | 1.13%   |
| DRAM    | 4         | 0.5%    |
| LPDDR5  | 3         | 0.38%   |
| LPDDR3  | 2         | 0.25%   |
| DDR5    | 2         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 475       | 60.43%  |
| DIMM         | 287       | 36.51%  |
| Row Of Chips | 24        | 3.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 314       | 34.32%  |
| 2048  | 226       | 24.7%   |
| 8192  | 198       | 21.64%  |
| 16384 | 83        | 9.07%   |
| 1024  | 68        | 7.43%   |
| 512   | 14        | 1.53%   |
| 32768 | 9         | 0.98%   |
| 256   | 2         | 0.22%   |
| 16    | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 221       | 25.46%  |
| 3200    | 86        | 9.91%   |
| 2667    | 75        | 8.64%   |
| 1333    | 67        | 7.72%   |
| 2400    | 54        | 6.22%   |
| 800     | 48        | 5.53%   |
| Unknown | 45        | 5.18%   |
| 667     | 44        | 5.07%   |
| 1334    | 42        | 4.84%   |
| 2133    | 17        | 1.96%   |
| 4199    | 14        | 1.61%   |
| 1066    | 13        | 1.5%    |
| 1067    | 12        | 1.38%   |
| 533     | 12        | 1.38%   |
| 400     | 12        | 1.38%   |
| 3600    | 11        | 1.27%   |
| 1867    | 10        | 1.15%   |
| 3266    | 9         | 1.04%   |
| 2048    | 9         | 1.04%   |
| 3466    | 6         | 0.69%   |
| 1866    | 6         | 0.69%   |
| 333     | 6         | 0.69%   |
| 4267    | 5         | 0.58%   |
| 3733    | 4         | 0.46%   |
| 6400    | 3         | 0.35%   |
| 3000    | 3         | 0.35%   |
| 49926   | 2         | 0.23%   |
| 8400    | 2         | 0.23%   |
| 4800    | 2         | 0.23%   |
| 4266    | 2         | 0.23%   |
| 3400    | 2         | 0.23%   |
| 2933    | 2         | 0.23%   |
| 2666    | 2         | 0.23%   |
| 1800    | 2         | 0.23%   |
| 1639    | 2         | 0.23%   |
| 266     | 2         | 0.23%   |
| 65535   | 1         | 0.12%   |
| 3866    | 1         | 0.12%   |
| 3800    | 1         | 0.12%   |
| 3533    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Canon                 | 7         | 28%     |
| Hewlett-Packard       | 6         | 24%     |
| Seiko Epson           | 5         | 20%     |
| Samsung Electronics   | 3         | 12%     |
| Ricoh                 | 1         | 4%      |
| QinHeng Electronics   | 1         | 4%      |
| Lexmark International | 1         | 4%      |
| Kyocera               | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6030w/6018w              | 2         | 7.69%   |
| Canon LBP6020                     | 2         | 7.69%   |
| Seiko Epson M100 Series           | 1         | 3.85%   |
| Seiko Epson L805 Series           | 1         | 3.85%   |
| Seiko Epson L365 Series           | 1         | 3.85%   |
| Seiko Epson L360 Series           | 1         | 3.85%   |
| Seiko Epson ET-1810 Series        | 1         | 3.85%   |
| Samsung SCX-4300 Series           | 1         | 3.85%   |
| Samsung SCX-4200 series           | 1         | 3.85%   |
| Samsung Laser Printer             | 1         | 3.85%   |
| Ricoh SP 211SU                    | 1         | 3.85%   |
| QinHeng CH340S                    | 1         | 3.85%   |
| Lexmark International Z35 Printer | 1         | 3.85%   |
| Kyocera FS-1125MFP                | 1         | 3.85%   |
| HP LaserJet P2055 series          | 1         | 3.85%   |
| HP LaserJet P1006                 | 1         | 3.85%   |
| HP LaserJet P1005                 | 1         | 3.85%   |
| HP LaserJet 1300                  | 1         | 3.85%   |
| HP LaserJet 1010                  | 1         | 3.85%   |
| HP DeskJet 840c                   | 1         | 3.85%   |
| Canon MF4410                      | 1         | 3.85%   |
| Canon MF4010 series               | 1         | 3.85%   |
| Canon MF3010                      | 1         | 3.85%   |
| Canon G1000 series                | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 66.67%  |
| Ultima Electronics | 1         | 16.67%  |
| Seiko Epson        | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 16.67%  |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 16.67%  |
| Canon CanoScan LiDE 600F                                                              | 1         | 16.67%  |
| Canon CanoScan LiDE 60                                                                | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                                                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 152       | 21.97%  |
| IMC Networks                           | 96        | 13.87%  |
| Realtek Semiconductor                  | 41        | 5.92%   |
| Bison Electronics                      | 40        | 5.78%   |
| Quanta                                 | 39        | 5.64%   |
| Logitech                               | 37        | 5.35%   |
| Suyin                                  | 31        | 4.48%   |
| Sunplus Innovation Technology          | 30        | 4.34%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.76%   |
| Syntek                                 | 25        | 3.61%   |
| Microdia                               | 25        | 3.61%   |
| Z-Star Microelectronics                | 24        | 3.47%   |
| Silicon Motion                         | 22        | 3.18%   |
| Lite-On Technology                     | 19        | 2.75%   |
| Alcor Micro                            | 11        | 1.59%   |
| Apple                                  | 10        | 1.45%   |
| Luxvisions Innotech Limited            | 7         | 1.01%   |
| Acer                                   | 5         | 0.72%   |
| Samsung Electronics                    | 4         | 0.58%   |
| Primax Electronics                     | 4         | 0.58%   |
| Sonix Technology                       | 3         | 0.43%   |
| Microsoft                              | 3         | 0.43%   |
| lihappe8                               | 3         | 0.43%   |
| Lenovo                                 | 3         | 0.43%   |
| Importek                               | 3         | 0.43%   |
| DigiTech                               | 3         | 0.43%   |
| Cubeternet                             | 3         | 0.43%   |
| Aveo Technology                        | 3         | 0.43%   |
| SunplusIT                              | 2         | 0.29%   |
| Ricoh                                  | 2         | 0.29%   |
| Arkmicro Technologies                  | 2         | 0.29%   |
| Y Media                                | 1         | 0.14%   |
| Shine-optics                           | 1         | 0.14%   |
| Razer USA                              | 1         | 0.14%   |
| Pixart Imaging                         | 1         | 0.14%   |
| Nokia Mobile Phones                    | 1         | 0.14%   |
| Linux Foundation                       | 1         | 0.14%   |
| KYE Systems (Mouse Systems)            | 1         | 0.14%   |
| Intel                                  | 1         | 0.14%   |
| Goodong                                | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam   | 30        | 4.32%   |
| Chicony Integrated Camera            | 17        | 2.45%   |
| Logitech Webcam C270                 | 16        | 2.31%   |
| IMC Networks USB2.0 HD UVC WebCam    | 16        | 2.31%   |
| Realtek Integrated_Webcam_HD         | 13        | 1.87%   |
| IMC Networks Integrated Camera       | 12        | 1.73%   |
| Chicony USB2.0 VGA UVC WebCam        | 12        | 1.73%   |
| Chicony HD WebCam                    | 12        | 1.73%   |
| Bison Lenovo Integrated Webcam       | 12        | 1.73%   |
| Bison Lenovo EasyCamera              | 11        | 1.59%   |
| Syntek Integrated Camera             | 10        | 1.44%   |
| Sunplus HD WebCam                    | 10        | 1.44%   |
| Chicony Lenovo EasyCamera            | 10        | 1.44%   |
| IMC Networks USB2.0 UVC HD Webcam    | 8         | 1.15%   |
| Syntek EasyCamera                    | 7         | 1.01%   |
| Quanta HP HD Camera                  | 7         | 1.01%   |
| Chicony USB2.0 HD UVC WebCam         | 7         | 1.01%   |
| Chicony EasyCamera                   | 7         | 1.01%   |
| Bison Integrated Camera              | 7         | 1.01%   |
| Syntek Lenovo EasyCamera             | 6         | 0.86%   |
| Sunplus Integrated_Webcam_HD         | 6         | 0.86%   |
| Microdia Integrated_Webcam_HD        | 6         | 0.86%   |
| Logitech Webcam C310                 | 6         | 0.86%   |
| IMC Networks Integrated Webcam       | 6         | 0.86%   |
| Chicony HP HD Camera                 | 6         | 0.86%   |
| Z-Star A4 TECH USB2.0 PC Camera J    | 5         | 0.72%   |
| Suyin HP TrueVision HD               | 5         | 0.72%   |
| Silicon Motion WebCam SC-0311139N    | 5         | 0.72%   |
| Realtek USB Camera                   | 5         | 0.72%   |
| Quanta HP TrueVision HD Camera       | 5         | 0.72%   |
| Quanta HD Webcam                     | 5         | 0.72%   |
| Microdia Camera                      | 5         | 0.72%   |
| Lite-On Integrated Camera            | 5         | 0.72%   |
| Lite-On HP HD Camera                 | 5         | 0.72%   |
| IMC Networks UVC VGA Webcam          | 5         | 0.72%   |
| Chicony HP TrueVision HD Camera      | 5         | 0.72%   |
| Alcor Micro USB 2.0 Camera           | 5         | 0.72%   |
| Z-Star Venus USB2.0 Camera           | 4         | 0.58%   |
| Suyin HD Video WebCam                | 4         | 0.58%   |
| Silicon Motion WebCam SC-03FFL11939N | 4         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 28.4%   |
| Synaptics                  | 17        | 20.99%  |
| Shenzhen Goodix Technology | 14        | 17.28%  |
| Elan Microelectronics      | 14        | 17.28%  |
| AuthenTec                  | 6         | 7.41%   |
| STMicroelectronics         | 3         | 3.7%    |
| Upek                       | 2         | 2.47%   |
| LighTuning Technology      | 2         | 2.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 10        | 12.35%  |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 8.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 7.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 4.94%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 4.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 4.94%   |
| Elan ELAN:ARM-M4                                                           | 4         | 4.94%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.7%    |
| STMicroelectronics Fingerprint Reader                                      | 3         | 3.7%    |
| Validity Sensors VFS491                                                    | 2         | 2.47%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.47%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.47%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.47%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.47%   |
| Synaptics  WBDI                                                            | 2         | 2.47%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 2.47%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.23%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.23%   |
| Synaptics UWP WBDI                                                         | 1         | 1.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.23%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.23%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.23%   |
| AuthenTec AES2810                                                          | 1         | 1.23%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.23%   |
| AuthenTec AES1600                                                          | 1         | 1.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 8         | 47.06%  |
| Lenovo                | 4         | 23.53%  |
| Broadcom              | 2         | 11.76%  |
| Upek                  | 1         | 5.88%   |
| O2 Micro              | 1         | 5.88%   |
| Advanced Card Systems | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 47.06%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 23.53%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.88%   |
| Broadcom 58200                                                               | 1         | 5.88%   |
| Advanced Card Systems ACR39U                                                 | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 795       | 74.93%  |
| 1     | 221       | 20.83%  |
| 2     | 37        | 3.49%   |
| 3     | 7         | 0.66%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 117       | 38.87%  |
| Fingerprint reader       | 79        | 26.25%  |
| Net/wireless             | 23        | 7.64%   |
| Bluetooth                | 18        | 5.98%   |
| Multimedia controller    | 16        | 5.32%   |
| Chipcard                 | 13        | 4.32%   |
| Communication controller | 12        | 3.99%   |
| Camera                   | 10        | 3.32%   |
| Storage                  | 4         | 1.33%   |
| Sound                    | 3         | 1%      |
| Card reader              | 2         | 0.66%   |
| Unassigned class         | 1         | 0.33%   |
| Net/ethernet             | 1         | 0.33%   |
| Modem                    | 1         | 0.33%   |
| Flash memory             | 1         | 0.33%   |

