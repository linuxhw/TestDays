BigLinux - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for BigLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/BigLinux/Desktop/README.md) and [notebooks](/Dist/BigLinux/Notebook/README.md).

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

Total: 141

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Samsung       | 550XCJ/550XCR               | Notebook    | [daf43e4658](https://linux-hardware.org/?probe=daf43e4658) | Jan 02, 2024 |
| Lenovo        | ThinkCentre M91p 7005A21    | Desktop     | [043bcfc503](https://linux-hardware.org/?probe=043bcfc503) | Dec 31, 2023 |
| Lenovo        | ThinkCentre M91p 7005A21    | Desktop     | [e783d0ce11](https://linux-hardware.org/?probe=e783d0ce11) | Dec 31, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [4117a986c8](https://linux-hardware.org/?probe=4117a986c8) | Dec 16, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [de83793263](https://linux-hardware.org/?probe=de83793263) | Dec 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [a960a2a5b7](https://linux-hardware.org/?probe=a960a2a5b7) | Dec 10, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [e04ad23cd3](https://linux-hardware.org/?probe=e04ad23cd3) | Dec 10, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b5f0453a4b](https://linux-hardware.org/?probe=b5f0453a4b) | Dec 09, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [b5f3fbe4c5](https://linux-hardware.org/?probe=b5f3fbe4c5) | Dec 09, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b4efc55410](https://linux-hardware.org/?probe=b4efc55410) | Dec 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [15d4dc2fe9](https://linux-hardware.org/?probe=15d4dc2fe9) | Dec 05, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [b71e5d49a4](https://linux-hardware.org/?probe=b71e5d49a4) | Dec 04, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [638021e67d](https://linux-hardware.org/?probe=638021e67d) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [626135b546](https://linux-hardware.org/?probe=626135b546) | Dec 04, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [c4839c409c](https://linux-hardware.org/?probe=c4839c409c) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [0dc4701502](https://linux-hardware.org/?probe=0dc4701502) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [561cad738d](https://linux-hardware.org/?probe=561cad738d) | Dec 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [ecae393240](https://linux-hardware.org/?probe=ecae393240) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [c5dd65037d](https://linux-hardware.org/?probe=c5dd65037d) | Nov 29, 2023 |
| Positivo      | POS-EIH61CQ POSITIVO        | Desktop     | [bed32da0ed](https://linux-hardware.org/?probe=bed32da0ed) | Nov 26, 2023 |
| Positivo      | C41TF                       | Notebook    | [09be1cbd3a](https://linux-hardware.org/?probe=09be1cbd3a) | Nov 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c24820ad94](https://linux-hardware.org/?probe=c24820ad94) | Nov 24, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [688d81c63c](https://linux-hardware.org/?probe=688d81c63c) | Nov 22, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [713583bc52](https://linux-hardware.org/?probe=713583bc52) | Nov 22, 2023 |
| Intel         | B75                         | Desktop     | [0620da2ddb](https://linux-hardware.org/?probe=0620da2ddb) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d6c8994c15](https://linux-hardware.org/?probe=d6c8994c15) | Nov 20, 2023 |
| HP            | 1495                        | Desktop     | [c03adda1fa](https://linux-hardware.org/?probe=c03adda1fa) | Nov 20, 2023 |
| HP            | Pavilion g4                 | Notebook    | [37d7289eb6](https://linux-hardware.org/?probe=37d7289eb6) | Nov 16, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [fd1be084ac](https://linux-hardware.org/?probe=fd1be084ac) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [3113cdd229](https://linux-hardware.org/?probe=3113cdd229) | Nov 11, 2023 |
| Positivo      | C41TF                       | Notebook    | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [f6db4cc5a7](https://linux-hardware.org/?probe=f6db4cc5a7) | Oct 31, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [35fabc6811](https://linux-hardware.org/?probe=35fabc6811) | Oct 31, 2023 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [439b0a3497](https://linux-hardware.org/?probe=439b0a3497) | Oct 28, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [65494c95ec](https://linux-hardware.org/?probe=65494c95ec) | Oct 23, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [f904697713](https://linux-hardware.org/?probe=f904697713) | Oct 23, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [be03ed57d8](https://linux-hardware.org/?probe=be03ed57d8) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [e648a8c32a](https://linux-hardware.org/?probe=e648a8c32a) | Oct 20, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [50aa4fc1e1](https://linux-hardware.org/?probe=50aa4fc1e1) | Oct 18, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [952772fde5](https://linux-hardware.org/?probe=952772fde5) | Oct 14, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [673113259c](https://linux-hardware.org/?probe=673113259c) | Oct 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [d45a6f5bf2](https://linux-hardware.org/?probe=d45a6f5bf2) | Oct 14, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [0592faaf34](https://linux-hardware.org/?probe=0592faaf34) | Oct 12, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [cd9071e2ad](https://linux-hardware.org/?probe=cd9071e2ad) | Oct 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7508b7cf4f](https://linux-hardware.org/?probe=7508b7cf4f) | Oct 10, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [45a4c0fbe0](https://linux-hardware.org/?probe=45a4c0fbe0) | Oct 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [90883fd019](https://linux-hardware.org/?probe=90883fd019) | Oct 02, 2023 |
| Intel         | H61                         | Desktop     | [5dd60be36a](https://linux-hardware.org/?probe=5dd60be36a) | Sep 14, 2023 |
| PCWare        | IPMH81G1                    | Desktop     | [181367c2db](https://linux-hardware.org/?probe=181367c2db) | Sep 12, 2023 |
| Biostar       | G31M+                       | Desktop     | [24eb0eb2db](https://linux-hardware.org/?probe=24eb0eb2db) | Sep 06, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [73e3b8ef8a](https://linux-hardware.org/?probe=73e3b8ef8a) | Sep 04, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [332e78dfba](https://linux-hardware.org/?probe=332e78dfba) | Sep 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9cf292357b](https://linux-hardware.org/?probe=9cf292357b) | Aug 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [30ea6db008](https://linux-hardware.org/?probe=30ea6db008) | Jul 23, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e699ffe719](https://linux-hardware.org/?probe=e699ffe719) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [a2487119a6](https://linux-hardware.org/?probe=a2487119a6) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [f9a1d993b2](https://linux-hardware.org/?probe=f9a1d993b2) | Jul 07, 2023 |
| ASUSTek       | VX7SX                       | Notebook    | [2ef4295d22](https://linux-hardware.org/?probe=2ef4295d22) | Jul 05, 2023 |
| Positivo      | Q464B                       | Notebook    | [9dad5f0aa1](https://linux-hardware.org/?probe=9dad5f0aa1) | Jul 02, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [5223ed2efd](https://linux-hardware.org/?probe=5223ed2efd) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e25224b362](https://linux-hardware.org/?probe=e25224b362) | Jun 13, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [613d703a17](https://linux-hardware.org/?probe=613d703a17) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [91d11f8da1](https://linux-hardware.org/?probe=91d11f8da1) | Jun 04, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| LG Electro... | V720                        | All in one  | [686e013b62](https://linux-hardware.org/?probe=686e013b62) | May 25, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| Dell          | G15 5520                    | Notebook    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| HP            | 1495                        | Desktop     | [96283c0a09](https://linux-hardware.org/?probe=96283c0a09) | Apr 01, 2023 |
| HP            | 1495                        | Desktop     | [f25125625a](https://linux-hardware.org/?probe=f25125625a) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| Clevo         | W340EU                      | Notebook    | [fb9df7f581](https://linux-hardware.org/?probe=fb9df7f581) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [176b7d75bf](https://linux-hardware.org/?probe=176b7d75bf) | Mar 18, 2023 |
| Avell High... | STORM TWO                   | Notebook    | [e6b20084b5](https://linux-hardware.org/?probe=e6b20084b5) | Mar 16, 2023 |
| HP            | 3397                        | Desktop     | [0b74e11cdd](https://linux-hardware.org/?probe=0b74e11cdd) | Mar 12, 2023 |
| HP            | 1495                        | Desktop     | [058beaa7d1](https://linux-hardware.org/?probe=058beaa7d1) | Mar 12, 2023 |
| HP            | 1495                        | Desktop     | [517a7a6401](https://linux-hardware.org/?probe=517a7a6401) | Mar 12, 2023 |
| Lenovo        | NOK                         | Desktop     | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| Intel         | H61                         | Desktop     | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [7c6973f1fa](https://linux-hardware.org/?probe=7c6973f1fa) | Feb 21, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4bcfe32668](https://linux-hardware.org/?probe=4bcfe32668) | Feb 12, 2023 |
| Intel         | H61                         | Desktop     | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| Intel         | H55                         | Desktop     | [4fdea85eec](https://linux-hardware.org/?probe=4fdea85eec) | Jan 14, 2023 |
| Intel         | H55                         | Desktop     | [d875a18037](https://linux-hardware.org/?probe=d875a18037) | Jan 14, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b1a7adefab](https://linux-hardware.org/?probe=b1a7adefab) | Jan 09, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| eMachines     | EMCP61M                     | Desktop     | [711594c5b4](https://linux-hardware.org/?probe=711594c5b4) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| ASUSTek       | X45U                        | Notebook    | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| Positivo      | C14RV01                     | Notebook    | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| Sony          | VGN-NR230AE                 | Notebook    | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [0efc94e34d](https://linux-hardware.org/?probe=0efc94e34d) | Jul 24, 2022 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [cfd6e87e09](https://linux-hardware.org/?probe=cfd6e87e09) | Jul 23, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [2f8b49e4f8](https://linux-hardware.org/?probe=2f8b49e4f8) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [c30806c628](https://linux-hardware.org/?probe=c30806c628) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [b805fa0cd8](https://linux-hardware.org/?probe=b805fa0cd8) | Jul 23, 2022 |
| Positivo      | C14RV01                     | Notebook    | [fc6fa07b38](https://linux-hardware.org/?probe=fc6fa07b38) | Sep 10, 2021 |
| Acer          | Predator G9-793             | Notebook    | [6004b8b462](https://linux-hardware.org/?probe=6004b8b462) | Jun 24, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [e58da0d3ca](https://linux-hardware.org/?probe=e58da0d3ca) | Jun 23, 2021 |
| Acer          | Predator G9-793             | Notebook    | [ae4824f52e](https://linux-hardware.org/?probe=ae4824f52e) | Jun 20, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [41512cfc6a](https://linux-hardware.org/?probe=41512cfc6a) | Jun 20, 2021 |
| ECS           | H67H2-M2                    | Desktop     | [d82e4c4eb4](https://linux-hardware.org/?probe=d82e4c4eb4) | Apr 10, 2021 |
| Positivo      | C14RV01                     | Notebook    | [36efae3128](https://linux-hardware.org/?probe=36efae3128) | Feb 03, 2021 |
| Acer          | A315-41                     | Notebook    | [021dc9110e](https://linux-hardware.org/?probe=021dc9110e) | Nov 11, 2020 |
| Lenovo        | ThinkPad T410 25379N2       | Notebook    | [ed777f25b7](https://linux-hardware.org/?probe=ed777f25b7) | Nov 09, 2020 |
| Dell          | Inspiron 3480               | Notebook    | [1f0823c074](https://linux-hardware.org/?probe=1f0823c074) | Oct 13, 2020 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [0c4cd978f2](https://linux-hardware.org/?probe=0c4cd978f2) | Jul 24, 2020 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [3cef63e59d](https://linux-hardware.org/?probe=3cef63e59d) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [8b89f99351](https://linux-hardware.org/?probe=8b89f99351) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [07fb6950a2](https://linux-hardware.org/?probe=07fb6950a2) | Jul 11, 2020 |
| PCWare        | IPX1800E2                   | Desktop     | [0990462881](https://linux-hardware.org/?probe=0990462881) | Jun 21, 2020 |
| PCWare        | IPX1800E2                   | Desktop     | [93916c17f2](https://linux-hardware.org/?probe=93916c17f2) | Jun 21, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [3a8f141df4](https://linux-hardware.org/?probe=3a8f141df4) | Mar 28, 2020 |
| Alienware     | 17                          | Notebook    | [14abe97f88](https://linux-hardware.org/?probe=14abe97f88) | Oct 23, 2019 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [419565138f](https://linux-hardware.org/?probe=419565138f) | Aug 30, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| BigLinux                  | 21        | 20%     |
| BigLinux 20.04            | 11        | 10.48%  |
| BigLinux 23.0.0           | 7         | 6.67%   |
| BigLinux 22.0.0           | 6         | 5.71%   |
| BigLinux 19.04            | 5         | 4.76%   |
| BigLinux 22.1.0           | 4         | 3.81%   |
| BigLinux 22.0.4           | 4         | 3.81%   |
| BigLinux 23.1.0           | 3         | 2.86%   |
| BigLinux 21.3.7           | 3         | 2.86%   |
| BigLinux 21.3.5           | 3         | 2.86%   |
| BigLinux 23.02.20         | 2         | 1.9%    |
| BigLinux 23.0.3           | 2         | 1.9%    |
| BigLinux 23.0.1           | 2         | 1.9%    |
| BigLinux 2023-12-01_05-13 | 2         | 1.9%    |
| BigLinux 2023-06-30_08-01 | 2         | 1.9%    |
| BigLinux 23.02.24         | 1         | 0.95%   |
| BigLinux 23.02.07         | 1         | 0.95%   |
| BigLinux 23.01.30         | 1         | 0.95%   |
| BigLinux 23.01.06         | 1         | 0.95%   |
| BigLinux 23.0.4           | 1         | 0.95%   |
| BigLinux 22.12.24         | 1         | 0.95%   |
| BigLinux 22.11.19         | 1         | 0.95%   |
| BigLinux 22.11.14         | 1         | 0.95%   |
| BigLinux 22.10.28         | 1         | 0.95%   |
| BigLinux 22.10.06         | 1         | 0.95%   |
| BigLinux 22.1.1           | 1         | 0.95%   |
| BigLinux 22.09.09         | 1         | 0.95%   |
| BigLinux 22.0.5           | 1         | 0.95%   |
| BigLinux 22.0.2           | 1         | 0.95%   |
| BigLinux 21.3.6           | 1         | 0.95%   |
| BigLinux 21.1.2           | 1         | 0.95%   |
| BigLinux 2023-11-24_05-13 | 1         | 0.95%   |
| BigLinux 2023-11-21_03-11 | 1         | 0.95%   |
| BigLinux 2023-11-17_05-13 | 1         | 0.95%   |
| BigLinux 2023-11-13_03-10 | 1         | 0.95%   |
| BigLinux 2023-11-07_19-34 | 1         | 0.95%   |
| BigLinux 2023-10-14_01-04 | 1         | 0.95%   |
| BigLinux 2023-08-04_06-17 | 1         | 0.95%   |
| BigLinux 2023-06-23_06-21 | 1         | 0.95%   |
| BigLinux 2023-06-07_06-02 | 1         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| BigLinux | 100       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 6.1.55-1-MANJARO           | 7         | 6.42%   |
| 6.1.64-1-MANJARO           | 5         | 4.59%   |
| 6.5.5-1-MANJARO            | 4         | 3.67%   |
| 6.1.62-1-MANJARO           | 4         | 3.67%   |
| 6.1.31-2-MANJARO           | 4         | 3.67%   |
| 6.1.12-1-MANJARO           | 4         | 3.67%   |
| 6.6.3-1-MANJARO            | 3         | 2.75%   |
| 6.1.23-1-MANJARO           | 3         | 2.75%   |
| 5.15.94-1-MANJARO          | 3         | 2.75%   |
| 5.15.85-1-MANJARO          | 3         | 2.75%   |
| 5.15.60-1-MANJARO          | 3         | 2.75%   |
| 6.5.11-1-MANJARO           | 2         | 1.83%   |
| 6.4.12-1-MANJARO           | 2         | 1.83%   |
| 6.2.12-1-MANJARO           | 2         | 1.83%   |
| 6.1.51-1-MANJARO           | 2         | 1.83%   |
| 6.0.8-1-MANJARO            | 2         | 1.83%   |
| 5.8.0-43-generic           | 2         | 1.83%   |
| 5.4.0-37-generic           | 2         | 1.83%   |
| 5.2.8-xanmod8              | 2         | 1.83%   |
| 5.15.78-1-MANJARO          | 2         | 1.83%   |
| 5.15.71-1-MANJARO          | 2         | 1.83%   |
| 5.15.102-1-MANJARO         | 2         | 1.83%   |
| 6.7.0-4-MANJARO            | 1         | 0.92%   |
| 6.6.5-x64v2-xanmod1-1      | 1         | 0.92%   |
| 6.6.1-1-MANJARO            | 1         | 0.92%   |
| 6.5.10-x64v2-xanmod1-1     | 1         | 0.92%   |
| 6.4.6-1-MANJARO            | 1         | 0.92%   |
| 6.3.5-2-MANJARO            | 1         | 0.92%   |
| 6.3.5-1-MANJARO            | 1         | 0.92%   |
| 6.3.13-1-MANJARO           | 1         | 0.92%   |
| 6.1.9-x64v1-xanmod1-1      | 1         | 0.92%   |
| 6.1.9-1-MANJARO            | 1         | 0.92%   |
| 6.1.69-1-MANJARO           | 1         | 0.92%   |
| 6.1.64-x64v2-xanmod1-1-lts | 1         | 0.92%   |
| 6.1.63-1-MANJARO           | 1         | 0.92%   |
| 6.1.62-x64v2-xanmod1-1-lts | 1         | 0.92%   |
| 6.1.60-1-MANJARO           | 1         | 0.92%   |
| 6.1.57-x64v2-xanmod1-1-lts | 1         | 0.92%   |
| 6.1.49-1-MANJARO           | 1         | 0.92%   |
| 6.1.26-1-MANJARO           | 1         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.55   | 7         | 6.48%   |
| 6.1.64   | 6         | 5.56%   |
| 6.1.62   | 5         | 4.63%   |
| 6.5.5    | 4         | 3.7%    |
| 6.1.31   | 4         | 3.7%    |
| 6.1.12   | 4         | 3.7%    |
| 5.8.0    | 4         | 3.7%    |
| 5.4.0    | 4         | 3.7%    |
| 6.6.3    | 3         | 2.78%   |
| 6.1.23   | 3         | 2.78%   |
| 5.15.94  | 3         | 2.78%   |
| 5.15.85  | 3         | 2.78%   |
| 5.15.60  | 3         | 2.78%   |
| 6.5.11   | 2         | 1.85%   |
| 6.4.12   | 2         | 1.85%   |
| 6.3.5    | 2         | 1.85%   |
| 6.2.12   | 2         | 1.85%   |
| 6.1.9    | 2         | 1.85%   |
| 6.1.51   | 2         | 1.85%   |
| 6.0.8    | 2         | 1.85%   |
| 5.2.8    | 2         | 1.85%   |
| 5.15.78  | 2         | 1.85%   |
| 5.15.71  | 2         | 1.85%   |
| 5.15.102 | 2         | 1.85%   |
| 6.7.0    | 1         | 0.93%   |
| 6.6.5    | 1         | 0.93%   |
| 6.6.1    | 1         | 0.93%   |
| 6.5.10   | 1         | 0.93%   |
| 6.4.6    | 1         | 0.93%   |
| 6.3.13   | 1         | 0.93%   |
| 6.1.69   | 1         | 0.93%   |
| 6.1.63   | 1         | 0.93%   |
| 6.1.60   | 1         | 0.93%   |
| 6.1.57   | 1         | 0.93%   |
| 6.1.49   | 1         | 0.93%   |
| 6.1.26   | 1         | 0.93%   |
| 6.1.1    | 1         | 0.93%   |
| 5.9.3    | 1         | 0.93%   |
| 5.7.9    | 1         | 0.93%   |
| 5.6.6    | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 39        | 38.24%  |
| 5.15    | 18        | 17.65%  |
| 6.5     | 7         | 6.86%   |
| 6.6     | 5         | 4.9%    |
| 5.8     | 4         | 3.92%   |
| 5.4     | 4         | 3.92%   |
| 5.10    | 4         | 3.92%   |
| 6.4     | 3         | 2.94%   |
| 6.3     | 3         | 2.94%   |
| 5.2     | 3         | 2.94%   |
| 6.2     | 2         | 1.96%   |
| 6.0     | 2         | 1.96%   |
| 6.7     | 1         | 0.98%   |
| 5.9     | 1         | 0.98%   |
| 5.7     | 1         | 0.98%   |
| 5.6     | 1         | 0.98%   |
| 5.3     | 1         | 0.98%   |
| 5.19    | 1         | 0.98%   |
| 5.17    | 1         | 0.98%   |
| 5.16    | 1         | 0.98%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 91        | 91%     |
| KDE      | 6         | 6%      |
| Unknown  | 2         | 2%      |
| Cinnamon | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 97        | 96.04%  |
| Wayland | 3         | 2.97%   |
| Unknown | 1         | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 70        | 69.31%  |
| Unknown | 28        | 27.72%  |
| LightDM | 2         | 1.98%   |
| LXDM    | 1         | 0.99%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| pt_BR   | 61        | 61%     |
| en_US   | 14        | 14%     |
| es_MX   | 4         | 4%      |
| pl_PL   | 3         | 3%      |
| de_DE   | 3         | 3%      |
| pt_PT   | 2         | 2%      |
| en_GB   | 2         | 2%      |
| Unknown | 2         | 2%      |
| fr_FR   | 1         | 1%      |
| fr_BE   | 1         | 1%      |
| fi_FI   | 1         | 1%      |
| es_ES   | 1         | 1%      |
| es_CR   | 1         | 1%      |
| es_CO   | 1         | 1%      |
| es_AR   | 1         | 1%      |
| el_GR   | 1         | 1%      |
| de_AT   | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 60        | 58.82%  |
| BIOS | 42        | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 89        | 89%     |
| Ext4    | 8         | 8%      |
| Overlay | 2         | 2%      |
| Unknown | 1         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 51        | 49.51%  |
| Unknown | 30        | 29.13%  |
| MBR     | 22        | 21.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 96.04%  |
| Yes       | 4         | 3.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 59.41%  |
| Yes       | 41        | 40.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 14        | 14%     |
| Lenovo                 | 12        | 12%     |
| Gigabyte Technology    | 10        | 10%     |
| Acer                   | 10        | 10%     |
| Intel                  | 8         | 8%      |
| Hewlett-Packard        | 8         | 8%      |
| Dell                   | 8         | 8%      |
| Positivo               | 5         | 5%      |
| Semp Toshiba           | 2         | 2%      |
| Samsung Electronics    | 2         | 2%      |
| PCWare                 | 2         | 2%      |
| MSI                    | 2         | 2%      |
| ASRock                 | 2         | 2%      |
| Toshiba                | 1         | 1%      |
| Sony                   | 1         | 1%      |
| OEM                    | 1         | 1%      |
| Multilaser             | 1         | 1%      |
| Microsoft              | 1         | 1%      |
| eMachines              | 1         | 1%      |
| ECS                    | 1         | 1%      |
| Daten Tecnologia       | 1         | 1%      |
| Clevo                  | 1         | 1%      |
| Biostar                | 1         | 1%      |
| BESSTAR Tech           | 1         | 1%      |
| Avell High Performance | 1         | 1%      |
| Apple                  | 1         | 1%      |
| Alienware              | 1         | 1%      |
| Unknown                | 1         | 1%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                         | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel H61                                                    | 3         | 3%      |
| Positivo C41TF                                               | 2         | 2%      |
| HP Compaq 8200 Elite SFF PC                                  | 2         | 2%      |
| ASRock 775Dual-VSTA                                          | 2         | 2%      |
| Toshiba Satellite S55-A                                      | 1         | 1%      |
| Sony VGN-NR230AE                                             | 1         | 1%      |
| Semp Toshiba STI                                             | 1         | 1%      |
| Semp Toshiba IS 1412                                         | 1         | 1%      |
| Samsung 550XCJ/550XCR                                        | 1         | 1%      |
| Samsung 300E5M/300E5L                                        | 1         | 1%      |
| Positivo Q464B                                               | 1         | 1%      |
| Positivo POS-EIH61CQ                                         | 1         | 1%      |
| Positivo C14RV01                                             | 1         | 1%      |
| PCWare IPX1800E2                                             | 1         | 1%      |
| PCWare IPMH81G1                                              | 1         | 1%      |
| OEM B75                                                      | 1         | 1%      |
| Multilaser MLSH1H LINUX                                      | 1         | 1%      |
| MSI MS-7C95                                                  | 1         | 1%      |
| MSI MS-7C91                                                  | 1         | 1%      |
| Microsoft Surface Pro                                        | 1         | 1%      |
| Lenovo Yoga Slim 7 14ARE05 82A2                              | 1         | 1%      |
| Lenovo Yoga 520-14IKB 80YM                                   | 1         | 1%      |
| Lenovo ThinkPad T480s 20L70028US                             | 1         | 1%      |
| Lenovo ThinkPad T410 25379N2                                 | 1         | 1%      |
| Lenovo ThinkCentre M93p 10AB0010US                           | 1         | 1%      |
| Lenovo ThinkCentre M91p 7005A21                              | 1         | 1%      |
| Lenovo ThinkCentre M710s 10M8SBAT00                          | 1         | 1%      |
| Lenovo IdeaPad Z470                                          | 1         | 1%      |
| Lenovo IdeaPad S400 VIUS3                                    | 1         | 1%      |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                             | 1         | 1%      |
| Lenovo IdeaPad 300-15ISK 80RS                                | 1         | 1%      |
| Lenovo 63 90AT0002BR                                         | 1         | 1%      |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V307 | 1         | 1%      |
| Intel NUC11BTMi7                                             | 1         | 1%      |
| Intel H55                                                    | 1         | 1%      |
| Intel DH61WW AAG23116-203                                    | 1         | 1%      |
| Intel B75                                                    | 1         | 1%      |
| HP ZBook 15 G3                                               | 1         | 1%      |
| HP Pavilion g4                                               | 1         | 1%      |
| HP EliteBook 8760w                                           | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 5         | 5%      |
| Lenovo IdeaPad       | 4         | 4%      |
| Lenovo ThinkCentre   | 3         | 3%      |
| Intel H61            | 3         | 3%      |
| HP Compaq            | 3         | 3%      |
| Dell Inspiron        | 3         | 3%      |
| ASUS VivoBook        | 3         | 3%      |
| ASUS TUF             | 3         | 3%      |
| Acer Nitro           | 3         | 3%      |
| Positivo C41TF       | 2         | 2%      |
| Lenovo Yoga          | 2         | 2%      |
| Lenovo ThinkPad      | 2         | 2%      |
| HP 255               | 2         | 2%      |
| Dell System          | 2         | 2%      |
| ASRock 775Dual-VSTA  | 2         | 2%      |
| Toshiba Satellite    | 1         | 1%      |
| Sony VGN-NR230AE     | 1         | 1%      |
| Semp Toshiba STI     | 1         | 1%      |
| Semp Toshiba IS      | 1         | 1%      |
| Samsung 550XCJ       | 1         | 1%      |
| Samsung 300E5M       | 1         | 1%      |
| Positivo Q464B       | 1         | 1%      |
| Positivo POS-EIH61CQ | 1         | 1%      |
| Positivo C14RV01     | 1         | 1%      |
| PCWare IPX1800E2     | 1         | 1%      |
| PCWare IPMH81G1      | 1         | 1%      |
| OEM B75              | 1         | 1%      |
| Multilaser MLSH1H    | 1         | 1%      |
| MSI MS-7C95          | 1         | 1%      |
| MSI MS-7C91          | 1         | 1%      |
| Microsoft Surface    | 1         | 1%      |
| Lenovo 63            | 1         | 1%      |
| Intel X79            | 1         | 1%      |
| Intel NUC11BTMi7     | 1         | 1%      |
| Intel H55            | 1         | 1%      |
| Intel DH61WW         | 1         | 1%      |
| Intel B75            | 1         | 1%      |
| HP ZBook             | 1         | 1%      |
| HP Pavilion          | 1         | 1%      |
| HP EliteBook         | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 11        | 11%     |
| 2021 | 10        | 10%     |
| 2011 | 10        | 10%     |
| 2020 | 8         | 8%      |
| 2018 | 8         | 8%      |
| 2013 | 8         | 8%      |
| 2022 | 7         | 7%      |
| 2012 | 7         | 7%      |
| 2016 | 5         | 5%      |
| 2014 | 5         | 5%      |
| 2019 | 4         | 4%      |
| 2010 | 4         | 4%      |
| 2009 | 4         | 4%      |
| 2015 | 3         | 3%      |
| 2023 | 2         | 2%      |
| 2006 | 2         | 2%      |
| 2008 | 1         | 1%      |
| 2007 | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 50        | 50%     |
| Desktop     | 47        | 47%     |
| Tablet      | 1         | 1%      |
| Convertible | 1         | 1%      |
| Mini pc     | 1         | 1%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 99        | 99%     |
| Enabled  | 1         | 1%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 22        | 21.78%  |
| 8.01-16.0   | 19        | 18.81%  |
| 4.01-8.0    | 17        | 16.83%  |
| 32.01-64.0  | 16        | 15.84%  |
| 16.01-24.0  | 16        | 15.84%  |
| 2.01-3.0    | 4         | 3.96%   |
| 24.01-32.0  | 3         | 2.97%   |
| 1.01-2.0    | 3         | 2.97%   |
| 64.01-256.0 | 1         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 37        | 34.91%  |
| 1.01-2.0   | 35        | 33.02%  |
| 3.01-4.0   | 11        | 10.38%  |
| 4.01-8.0   | 10        | 9.43%   |
| 0.51-1.0   | 6         | 5.66%   |
| 8.01-16.0  | 5         | 4.72%   |
| 24.01-32.0 | 1         | 0.94%   |
| 0.01-0.5   | 1         | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 48.04%  |
| 2      | 26        | 25.49%  |
| 3      | 16        | 15.69%  |
| 4      | 7         | 6.86%   |
| 6      | 3         | 2.94%   |
| 0      | 1         | 0.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 66.34%  |
| Yes       | 34        | 33.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 91%     |
| No        | 9         | 9%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 74%     |
| No        | 26        | 26%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 62%     |
| No        | 38        | 38%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Brazil     | 65        | 65%     |
| USA        | 8         | 8%      |
| Mexico     | 4         | 4%      |
| UK         | 3         | 3%      |
| Poland     | 3         | 3%      |
| Greece     | 3         | 3%      |
| Germany    | 3         | 3%      |
| Portugal   | 2         | 2%      |
| Spain      | 1         | 1%      |
| Japan      | 1         | 1%      |
| France     | 1         | 1%      |
| Finland    | 1         | 1%      |
| Costa Rica | 1         | 1%      |
| Colombia   | 1         | 1%      |
| Belgium    | 1         | 1%      |
| Austria    | 1         | 1%      |
| Argentina  | 1         | 1%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Sao Paulo              | 6         | 5.83%   |
| Rio de Janeiro         | 4         | 3.88%   |
| Brasília              | 4         | 3.88%   |
| Belo Horizonte         | 3         | 2.91%   |
| Thessaloniki           | 2         | 1.94%   |
| Sao Domingos do Capim  | 2         | 1.94%   |
| Maringá               | 2         | 1.94%   |
| Fortaleza              | 2         | 1.94%   |
| Curitiba               | 2         | 1.94%   |
| Castanhal              | 2         | 1.94%   |
| Caratinga              | 2         | 1.94%   |
| Campo Grande           | 2         | 1.94%   |
| Wiener Neustadt        | 1         | 0.97%   |
| Vitória da Conquista  | 1         | 0.97%   |
| Villa Bosch            | 1         | 0.97%   |
| Vila Velha             | 1         | 0.97%   |
| Vila Nova de Famalicao | 1         | 0.97%   |
| Tychy                  | 1         | 0.97%   |
| Tokyo                  | 1         | 0.97%   |
| Tlajomulco de Zuniga   | 1         | 0.97%   |
| The Villages           | 1         | 0.97%   |
| Texarkana              | 1         | 0.97%   |
| Stralsund              | 1         | 0.97%   |
| Serafina Correa        | 1         | 0.97%   |
| Sao Jose do Rio Preto  | 1         | 0.97%   |
| Sao Joaquim da Barra   | 1         | 0.97%   |
| Santo André           | 1         | 0.97%   |
| Santiago de Cali       | 1         | 0.97%   |
| Santa Cruz de Tenerife | 1         | 0.97%   |
| San José              | 1         | 0.97%   |
| Salvador               | 1         | 0.97%   |
| Ribeirao Grande        | 1         | 0.97%   |
| Rennes                 | 1         | 0.97%   |
| Queimados              | 1         | 0.97%   |
| Piracicaba             | 1         | 0.97%   |
| Osasco                 | 1         | 0.97%   |
| Olsztyn                | 1         | 0.97%   |
| Oklahoma City          | 1         | 0.97%   |
| Niterói               | 1         | 0.97%   |
| Mirassol               | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 29        | 40     | 17.26%  |
| Seagate                     | 25        | 37     | 14.88%  |
| Samsung Electronics         | 13        | 16     | 7.74%   |
| Kingston                    | 11        | 15     | 6.55%   |
| Toshiba                     | 8         | 9      | 4.76%   |
| China                       | 8         | 10     | 4.76%   |
| Hitachi                     | 7         | 10     | 4.17%   |
| Crucial                     | 7         | 7      | 4.17%   |
| SanDisk                     | 6         | 6      | 3.57%   |
| KingSpec                    | 6         | 6      | 3.57%   |
| Unknown                     | 4         | 4      | 2.38%   |
| ADATA Technology            | 4         | 4      | 2.38%   |
| PNY                         | 3         | 4      | 1.79%   |
| Micron/Crucial Technology   | 3         | 3      | 1.79%   |
| A-DATA Technology           | 3         | 4      | 1.79%   |
| XrayDisk                    | 2         | 2      | 1.19%   |
| SK hynix                    | 2         | 2      | 1.19%   |
| Silicon Motion              | 2         | 2      | 1.19%   |
| Netac                       | 2         | 3      | 1.19%   |
| Micron Technology           | 2         | 2      | 1.19%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 1.19%   |
| LITEON                      | 2         | 3      | 1.19%   |
| Kingston Technology Company | 2         | 2      | 1.19%   |
| JMicron Technology          | 2         | 2      | 1.19%   |
| HGST                        | 2         | 2      | 1.19%   |
| WALRAM                      | 1         | 1      | 0.6%    |
| Realtek Semiconductor       | 1         | 1      | 0.6%    |
| Plextor                     | 1         | 1      | 0.6%    |
| NT-1TB                      | 1         | 1      | 0.6%    |
| Intel                       | 1         | 1      | 0.6%    |
| GOODRAM                     | 1         | 2      | 0.6%    |
| EYOTA                       | 1         | 1      | 0.6%    |
| BHT                         | 1         | 1      | 0.6%    |
| ASMedia                     | 1         | 1      | 0.6%    |
| Apacer                      | 1         | 1      | 0.6%    |
| Unknown                     | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 5         | 2.76%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 2.76%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 4         | 2.21%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 1.66%   |
| Seagate ST500DM002-1BD142 500GB                     | 3         | 1.66%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 1.66%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 1.66%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 2         | 1.1%    |
| Unknown MMC Card  64GB                              | 2         | 1.1%    |
| Toshiba MQ01ABD050V -63 500GB                       | 2         | 1.1%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 1.1%    |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 1.1%    |
| Micron/Crucial CT500P5SSD8 500GB                    | 2         | 1.1%    |
| Kingston SV300S37A240G 240GB SSD                    | 2         | 1.1%    |
| KingSpec P3-512 512GB SSD                           | 2         | 1.1%    |
| JMicron Tech 250GB                                  | 2         | 1.1%    |
| Hitachi HDS721050DLE630 500GB                       | 2         | 1.1%    |
| Crucial CT480BX500SSD1 480GB                        | 2         | 1.1%    |
| China SSD 120GB                                     | 2         | 1.1%    |
| XrayDisk 512GB SSD                                  | 1         | 0.55%   |
| XrayDisk 120GB                                      | 1         | 0.55%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.55%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 1         | 0.55%   |
| WDC WD800BD-22MRA1 80GB                             | 1         | 0.55%   |
| WDC WD800AAJS-75M0A0 80GB                           | 1         | 0.55%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 0.55%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.55%   |
| WDC WD5000LPVT-08G33T1 500GB                        | 1         | 0.55%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.55%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 0.55%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 0.55%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 0.55%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1         | 0.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.55%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 0.55%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1         | 0.55%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 1         | 0.55%   |
| WDC WD30EFAX-68JH4N0 3TB                            | 1         | 0.55%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 0.55%   |
| WDC WD1200BEVT-75ZCT2 120GB                         | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 38     | 38.03%  |
| Seagate             | 25        | 37     | 35.21%  |
| Toshiba             | 7         | 8      | 9.86%   |
| Hitachi             | 7         | 10     | 9.86%   |
| Samsung Electronics | 2         | 4      | 2.82%   |
| HGST                | 2         | 2      | 2.82%   |
| Unknown             | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 14     | 17.74%  |
| China               | 8         | 10     | 12.9%   |
| Crucial             | 7         | 7      | 11.29%  |
| KingSpec            | 6         | 6      | 9.68%   |
| Samsung Electronics | 5         | 6      | 8.06%   |
| SanDisk             | 4         | 4      | 6.45%   |
| PNY                 | 3         | 4      | 4.84%   |
| A-DATA Technology   | 3         | 4      | 4.84%   |
| WDC                 | 2         | 2      | 3.23%   |
| Micron Technology   | 2         | 2      | 3.23%   |
| LITEON              | 2         | 3      | 3.23%   |
| XrayDisk            | 1         | 1      | 1.61%   |
| Toshiba             | 1         | 1      | 1.61%   |
| Plextor             | 1         | 1      | 1.61%   |
| NT-1TB              | 1         | 1      | 1.61%   |
| GOODRAM             | 1         | 2      | 1.61%   |
| BHT                 | 1         | 1      | 1.61%   |
| ASMedia             | 1         | 1      | 1.61%   |
| Apacer              | 1         | 1      | 1.61%   |
| Unknown             | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 59        | 100    | 40.69%  |
| SSD     | 52        | 72     | 35.86%  |
| NVMe    | 26        | 29     | 17.93%  |
| Unknown | 5         | 5      | 3.45%   |
| MMC     | 3         | 3      | 2.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 170    | 70.97%  |
| NVMe | 26        | 29     | 20.97%  |
| SAS  | 7         | 7      | 5.65%   |
| MMC  | 3         | 3      | 2.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 97     | 56.14%  |
| 0.51-1.0   | 39        | 57     | 34.21%  |
| 1.01-2.0   | 6         | 8      | 5.26%   |
| 3.01-4.0   | 3         | 7      | 2.63%   |
| 2.01-3.0   | 1         | 1      | 0.88%   |
| 4.01-10.0  | 1         | 2      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 25        | 24.75%  |
| 2001-3000      | 22        | 21.78%  |
| 251-500        | 16        | 15.84%  |
| More than 3000 | 12        | 11.88%  |
| 101-250        | 12        | 11.88%  |
| 501-1000       | 11        | 10.89%  |
| 1-20           | 2         | 1.98%   |
| 51-100         | 1         | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 27        | 25.71%  |
| 51-100         | 26        | 24.76%  |
| 251-500        | 15        | 14.29%  |
| 101-250        | 14        | 13.33%  |
| 501-1000       | 11        | 10.48%  |
| 1-20           | 8         | 7.62%   |
| 2001-3000      | 2         | 1.9%    |
| More than 3000 | 1         | 0.95%   |
| 1001-2000      | 1         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                  | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-75M0A0 80GB              | 1         | 1      | 5.26%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 1         | 1      | 5.26%   |
| WDC WD5000AAKX-08U6AA0 500GB           | 1         | 1      | 5.26%   |
| WDC WD3200BPVT-00JJ5T0 320GB           | 1         | 3      | 5.26%   |
| WDC WD1001FALS-41Y6A1 1TB              | 1         | 2      | 5.26%   |
| Toshiba MQ01ABD050V -63 500GB          | 1         | 1      | 5.26%   |
| Seagate ST9250410AS 250GB              | 1         | 1      | 5.26%   |
| Seagate ST9100824AS 100GB              | 1         | 1      | 5.26%   |
| Seagate ST8000AS0002-1NA17Z 8TB        | 1         | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB        | 1         | 2      | 5.26%   |
| Seagate ST3320613AS 320GB              | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1      | 5.26%   |
| Hitachi HTS727575A9E364 752GB          | 1         | 1      | 5.26%   |
| Hitachi HTS545032A7E380 320GB          | 1         | 1      | 5.26%   |
| Hitachi HDS721050DLE630 500GB          | 1         | 1      | 5.26%   |
| Crucial CT500MX200SSD3 500GB           | 1         | 1      | 5.26%   |
| China SATA SSD 240GB                   | 1         | 1      | 5.26%   |
| ADATA Technology SM2P32A8-512GC1 512GB | 1         | 1      | 5.26%   |
| A-DATA Technology SU630 240GB SSD      | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 7      | 31.58%  |
| WDC               | 5         | 8      | 26.32%  |
| Hitachi           | 3         | 3      | 15.79%  |
| Toshiba           | 1         | 1      | 5.26%   |
| Crucial           | 1         | 1      | 5.26%   |
| China             | 1         | 1      | 5.26%   |
| ADATA Technology  | 1         | 1      | 5.26%   |
| A-DATA Technology | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 40%     |
| WDC     | 5         | 8      | 33.33%  |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 19     | 76.47%  |
| SSD  | 3         | 3      | 17.65%  |
| NVMe | 1         | 1      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 62        | 116    | 52.99%  |
| Works    | 38        | 69     | 32.48%  |
| Malfunc  | 16        | 23     | 13.68%  |
| Failed   | 1         | 1      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 72        | 59.02%  |
| AMD                         | 16        | 13.11%  |
| Samsung Electronics         | 5         | 4.1%    |
| ADATA Technology            | 4         | 3.28%   |
| Micron/Crucial Technology   | 3         | 2.46%   |
| Kingston Technology Company | 3         | 2.46%   |
| VIA Technologies            | 2         | 1.64%   |
| SK hynix                    | 2         | 1.64%   |
| Silicon Motion              | 2         | 1.64%   |
| SanDisk                     | 2         | 1.64%   |
| Netac Technology            | 2         | 1.64%   |
| MAXIO Technology (Hangzhou) | 2         | 1.64%   |
| Marvell Technology Group    | 2         | 1.64%   |
| Realtek Semiconductor       | 1         | 0.82%   |
| Phison Electronics          | 1         | 0.82%   |
| Nvidia                      | 1         | 0.82%   |
| Lite-On IT Corp. / Plextor  | 1         | 0.82%   |
| JMicron Technology          | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 7.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 5.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 5.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 3.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 2.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 4         | 2.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 2.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 2.17%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 1.45%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 2         | 1.45%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                                | 2         | 1.45%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 2         | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.45%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 1         | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1         | 0.72%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1         | 0.72%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1         | 0.72%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 1         | 0.72%   |
| Samsung NVMe SSD SM0032L                                                                | 1         | 0.72%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1         | 0.72%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.72%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.72%   |
| Netac PCIe 4 NVMe SSD (DRAM-less)                                                       | 1         | 0.72%   |
| Netac PCIe 4 INNOGRIT based NVMe SSD                                                    | 1         | 0.72%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1         | 0.72%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602                                            | 1         | 0.72%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 1         | 0.72%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 77        | 63.64%  |
| NVMe | 25        | 20.66%  |
| IDE  | 12        | 9.92%   |
| RAID | 7         | 5.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 80        | 80%     |
| AMD    | 20        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 4         | 4%      |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 3%      |
| Intel Pentium D CPU 3.00GHz                 | 2         | 2%      |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 2%      |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2         | 2%      |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2         | 2%      |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 2%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2%      |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 2%      |
| AMD Ryzen 5 5600 6-Core Processor           | 2         | 2%      |
| Intel Xeon CPU E5-2603 v3 @ 1.60GHz         | 1         | 1%      |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz         | 1         | 1%      |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1%      |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1%      |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1%      |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 1         | 1%      |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1%      |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1%      |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1%      |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1%      |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1%      |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1%      |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1%      |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1%      |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1%      |
| Intel Core i7 CPU S 860 @ 2.53GHz           | 1         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1%      |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1%      |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1%      |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1%      |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1         | 1%      |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1%      |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 1%      |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1%      |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 30        | 30%     |
| Intel Core i7           | 15        | 15%     |
| Intel Core i3           | 11        | 11%     |
| AMD Ryzen 5             | 8         | 8%      |
| Other                   | 6         | 6%      |
| Intel Celeron           | 6         | 6%      |
| AMD Ryzen 7             | 5         | 5%      |
| Intel Pentium Dual-Core | 3         | 3%      |
| Intel Xeon              | 2         | 2%      |
| Intel Pentium D         | 2         | 2%      |
| Intel Pentium Silver    | 1         | 1%      |
| Intel Pentium Dual      | 1         | 1%      |
| Intel Pentium           | 1         | 1%      |
| Intel Core 2 Quad       | 1         | 1%      |
| Intel Core 2 Duo        | 1         | 1%      |
| Intel Atom              | 1         | 1%      |
| AMD Ryzen Threadripper  | 1         | 1%      |
| AMD Ryzen 9             | 1         | 1%      |
| AMD Phenom II X6        | 1         | 1%      |
| AMD C-70                | 1         | 1%      |
| AMD C-60                | 1         | 1%      |
| AMD Athlon              | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 42%     |
| 4      | 35        | 35%     |
| 6      | 12        | 12%     |
| 8      | 6         | 6%      |
| 12     | 3         | 3%      |
| 14     | 1         | 1%      |
| 1      | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 99        | 99%     |
| 2      | 1         | 1%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 62        | 62%     |
| 1      | 38        | 38%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 99%     |
| Unknown        | 1         | 1%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 21%     |
| 0x206a7    | 12        | 12%     |
| 0x806e9    | 6         | 6%      |
| 0x306c3    | 6         | 6%      |
| 0x306a9    | 6         | 6%      |
| 0x506e3    | 4         | 4%      |
| 0x1067a    | 3         | 3%      |
| 0x0800820d | 3         | 3%      |
| 0xf64      | 2         | 2%      |
| 0x906a3    | 2         | 2%      |
| 0x806d1    | 2         | 2%      |
| 0x706a8    | 2         | 2%      |
| 0x08108109 | 2         | 2%      |
| 0x05000119 | 2         | 2%      |
| 0xa0671    | 1         | 1%      |
| 0xa0660    | 1         | 1%      |
| 0x906ed    | 1         | 1%      |
| 0x906c0    | 1         | 1%      |
| 0x806ec    | 1         | 1%      |
| 0x806ea    | 1         | 1%      |
| 0x706e5    | 1         | 1%      |
| 0x6fd      | 1         | 1%      |
| 0x6fb      | 1         | 1%      |
| 0x406e3    | 1         | 1%      |
| 0x406c4    | 1         | 1%      |
| 0x306f2    | 1         | 1%      |
| 0x306e4    | 1         | 1%      |
| 0x30678    | 1         | 1%      |
| 0x20655    | 1         | 1%      |
| 0x20652    | 1         | 1%      |
| 0x0a601201 | 1         | 1%      |
| 0x0a50000d | 1         | 1%      |
| 0x0a404102 | 1         | 1%      |
| 0x0a20120a | 1         | 1%      |
| 0x0a201025 | 1         | 1%      |
| 0x08701021 | 1         | 1%      |
| 0x08600106 | 1         | 1%      |
| 0x0810100b | 1         | 1%      |
| 0x08001137 | 1         | 1%      |
| 0x06006705 | 1         | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 17        | 17%     |
| KabyLake         | 14        | 14%     |
| Haswell          | 9         | 9%      |
| IvyBridge        | 8         | 8%      |
| Skylake          | 6         | 6%      |
| Zen+             | 5         | 5%      |
| Penryn           | 4         | 4%      |
| IceLake          | 4         | 4%      |
| Zen 3            | 3         | 3%      |
| Zen 2            | 3         | 3%      |
| Goldmont plus    | 3         | 3%      |
| Unknown          | 3         | 3%      |
| Zen              | 2         | 2%      |
| Westmere         | 2         | 2%      |
| Silvermont       | 2         | 2%      |
| NetBurst         | 2         | 2%      |
| Core             | 2         | 2%      |
| CometLake        | 2         | 2%      |
| Bobcat           | 2         | 2%      |
| Alderlake Hybrid | 2         | 2%      |
| Tremont          | 1         | 1%      |
| Nehalem          | 1         | 1%      |
| K8 Hammer        | 1         | 1%      |
| K10              | 1         | 1%      |
| Excavator        | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 60        | 50.42%  |
| Nvidia | 33        | 27.73%  |
| AMD    | 26        | 21.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 9.84%   |
| Intel HD Graphics 620                                                       | 8         | 6.56%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 3.28%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.46%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.46%   |
| Nvidia GM108M [GeForce 940MX]                                               | 2         | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.64%   |
| Intel HD Graphics 630                                                       | 2         | 1.64%   |
| Intel HD Graphics 530                                                       | 2         | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 2         | 1.64%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 1.64%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2         | 1.64%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.82%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.82%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.82%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1         | 0.82%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.82%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 0.82%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.82%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                    | 1         | 0.82%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1         | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.82%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 0.82%   |
| Nvidia GM108M [GeForce 920MX]                                               | 1         | 0.82%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 1         | 0.82%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 0.82%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.82%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.82%   |
| Nvidia GK106M [GeForce GTX 770M]                                            | 1         | 0.82%   |
| Nvidia GF116M [GeForce GT 560M]                                             | 1         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 40        | 39.6%   |
| 1 x AMD        | 22        | 21.78%  |
| 1 x Nvidia     | 18        | 17.82%  |
| Intel + Nvidia | 14        | 13.86%  |
| 2 x Intel      | 2         | 1.98%   |
| 2 x AMD        | 2         | 1.98%   |
| Intel + AMD    | 2         | 1.98%   |
| AMD + Nvidia   | 1         | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 74        | 74%     |
| Proprietary | 24        | 24%     |
| Unknown     | 2         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 56%     |
| 1.01-2.0   | 16        | 16%     |
| 0.01-0.5   | 8         | 8%      |
| 7.01-8.0   | 6         | 6%      |
| 3.01-4.0   | 5         | 5%      |
| 0.51-1.0   | 5         | 5%      |
| 5.01-6.0   | 2         | 2%      |
| 2.01-3.0   | 1         | 1%      |
| 8.01-16.0  | 1         | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 20        | 17.86%  |
| LG Display              | 11        | 9.82%   |
| BOE                     | 11        | 9.82%   |
| AU Optronics            | 11        | 9.82%   |
| Chimei Innolux          | 10        | 8.93%   |
| Goldstar                | 9         | 8.04%   |
| AOC                     | 6         | 5.36%   |
| Dell                    | 4         | 3.57%   |
| Philips                 | 3         | 2.68%   |
| Unknown (XXX)           | 2         | 1.79%   |
| Sony                    | 2         | 1.79%   |
| Positivo                | 2         | 1.79%   |
| Panasonic               | 2         | 1.79%   |
| Hewlett-Packard         | 2         | 1.79%   |
| GDH                     | 2         | 1.79%   |
| Chi Mei Optoelectronics | 2         | 1.79%   |
| VIZ                     | 1         | 0.89%   |
| Philco                  | 1         | 0.89%   |
| NEC Computers           | 1         | 0.89%   |
| MTD                     | 1         | 0.89%   |
| LRX                     | 1         | 0.89%   |
| LG Electronics          | 1         | 0.89%   |
| Lenovo                  | 1         | 0.89%   |
| ITE                     | 1         | 0.89%   |
| Denver                  | 1         | 0.89%   |
| CSO                     | 1         | 0.89%   |
| BenQ                    | 1         | 0.89%   |
| ASUSTek Computer        | 1         | 0.89%   |
| Apple                   | 1         | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 3         | 2.59%   |
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch   | 2         | 1.72%   |
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                      | 2         | 1.72%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch            | 2         | 1.72%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2         | 1.72%   |
| GDH Smart TV GDH0030 1920x1080 708x398mm 32.0-inch                     | 2         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 1.72%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 2         | 1.72%   |
| VIZ LCD Monitor M190VA 1360x768                                        | 1         | 0.86%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 0.86%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch         | 1         | 0.86%   |
| Sony TV SNY7E02 1920x1080                                              | 1         | 0.86%   |
| Sony TV SNY1A02 1920x1080                                              | 1         | 0.86%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 1         | 0.86%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch   | 1         | 0.86%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch    | 1         | 0.86%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch    | 1         | 0.86%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch    | 1         | 0.86%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch    | 1         | 0.86%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch   | 1         | 0.86%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch      | 1         | 0.86%   |
| Samsung Electronics S19B300 SAM08A5 1366x768 410x230mm 18.5-inch       | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch   | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 950x540mm 43.0-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM0E33 1920x1080 1210x680mm 54.6-inch | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 890x500mm 40.2-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM04DB 1280x1024 886x498mm 40.0-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM02C9 1360x768 885x498mm 40.0-inch   | 1         | 0.86%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                      | 1         | 0.86%   |
| Positivo UNION NON1500 1360x768 344x194mm 15.5-inch                    | 1         | 0.86%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                   | 1         | 0.86%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                | 1         | 0.86%   |
| Philips 24M1N3200ZA PHLC276 1920x1080 527x296mm 23.8-inch              | 1         | 0.86%   |
| Philips 237E4 PHLC0AD 1920x1080 509x286mm 23.0-inch                    | 1         | 0.86%   |
| Philco TV PLC0003 1440x900 708x398mm 32.0-inch                         | 1         | 0.86%   |
| NEC Computers LCD1770VX NEC6697 1280x960 338x270mm 17.0-inch           | 1         | 0.86%   |
| MTD LCD Monitor MTD0001 1280x800 303x190mm 14.1-inch                   | 1         | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 33.04%  |
| 1366x768 (WXGA)    | 31        | 27.68%  |
| 3840x2160 (4K)     | 7         | 6.25%   |
| 2560x1080          | 6         | 5.36%   |
| 1360x768           | 6         | 5.36%   |
| 1600x900 (HD+)     | 5         | 4.46%   |
| 1920x540           | 3         | 2.68%   |
| 1440x900 (WXGA+)   | 3         | 2.68%   |
| 1280x800 (WXGA)    | 3         | 2.68%   |
| 1680x1050 (WSXGA+) | 2         | 1.79%   |
| 1280x1024 (SXGA)   | 2         | 1.79%   |
| 3200x1080          | 1         | 0.89%   |
| 2880x1800          | 1         | 0.89%   |
| 2736x1824          | 1         | 0.89%   |
| 2560x1440 (QHD)    | 1         | 0.89%   |
| 1920x1200 (WUXGA)  | 1         | 0.89%   |
| 1280x960           | 1         | 0.89%   |
| Unknown            | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 22.12%  |
| 14      | 11        | 9.73%   |
| 13      | 10        | 8.85%   |
| 17      | 9         | 7.96%   |
| 23      | 8         | 7.08%   |
| 18      | 8         | 7.08%   |
| Unknown | 5         | 4.42%   |
| 27      | 4         | 3.54%   |
| 54      | 3         | 2.65%   |
| 40      | 3         | 2.65%   |
| 34      | 3         | 2.65%   |
| 31      | 3         | 2.65%   |
| 24      | 3         | 2.65%   |
| 21      | 3         | 2.65%   |
| 20      | 3         | 2.65%   |
| 72      | 2         | 1.77%   |
| 52      | 2         | 1.77%   |
| 19      | 2         | 1.77%   |
| 84      | 1         | 0.88%   |
| 32      | 1         | 0.88%   |
| 29      | 1         | 0.88%   |
| 28      | 1         | 0.88%   |
| 25      | 1         | 0.88%   |
| 12      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 41.07%  |
| 401-500     | 16        | 14.29%  |
| 501-600     | 14        | 12.5%   |
| 351-400     | 8         | 7.14%   |
| 601-700     | 6         | 5.36%   |
| 1001-1500   | 5         | 4.46%   |
| Unknown     | 5         | 4.46%   |
| 701-800     | 4         | 3.57%   |
| 801-900     | 3         | 2.68%   |
| 1501-2000   | 3         | 2.68%   |
| 201-300     | 2         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 76        | 76%     |
| 16/10   | 10        | 10%     |
| 21/9    | 6         | 6%      |
| Unknown | 4         | 4%      |
| 5/4     | 3         | 3%      |
| 3/2     | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 22.32%  |
| 81-90          | 21        | 18.75%  |
| 201-250        | 12        | 10.71%  |
| 141-150        | 9         | 8.04%   |
| More than 1000 | 8         | 7.14%   |
| 351-500        | 7         | 6.25%   |
| 151-200        | 6         | 5.36%   |
| 121-130        | 6         | 5.36%   |
| 301-350        | 5         | 4.46%   |
| Unknown        | 5         | 4.46%   |
| 251-300        | 3         | 2.68%   |
| 501-1000       | 3         | 2.68%   |
| 71-80          | 1         | 0.89%   |
| 131-140        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 39        | 36.45%  |
| 101-120       | 33        | 30.84%  |
| 121-160       | 19        | 17.76%  |
| 1-50          | 9         | 8.41%   |
| Unknown       | 5         | 4.67%   |
| More than 240 | 1         | 0.93%   |
| 161-240       | 1         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 74        | 73.27%  |
| 2     | 24        | 23.76%  |
| 0     | 3         | 2.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 70        | 45.16%  |
| Intel                    | 34        | 21.94%  |
| Qualcomm Atheros         | 22        | 14.19%  |
| Broadcom                 | 5         | 3.23%   |
| Ralink Technology        | 4         | 2.58%   |
| TP-Link                  | 3         | 1.94%   |
| MediaTek                 | 3         | 1.94%   |
| VIA Technologies         | 2         | 1.29%   |
| Marvell Technology Group | 2         | 1.29%   |
| D-Link System            | 2         | 1.29%   |
| Samsung Electronics      | 1         | 0.65%   |
| Ralink                   | 1         | 0.65%   |
| Prolific Technology      | 1         | 0.65%   |
| JMicron Technology       | 1         | 0.65%   |
| Edimax Technology        | 1         | 0.65%   |
| D-Link                   | 1         | 0.65%   |
| Belkin Components        | 1         | 0.65%   |
| ASIX Electronics         | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 21.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 8.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 4.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 1.65%   |
| Realtek 802.11ac NIC                                              | 3         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.65%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.1%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 1.1%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.1%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.1%    |
| Ralink RT5370 Wireless Adapter                                    | 2         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.1%    |
| Intel Wireless 8265 / 8275                                        | 2         | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.1%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.1%    |
| TP-Link Archer T4U ver.3                                          | 1         | 0.55%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.55%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.55%   |
| Realtek RTL8192SE Wireless LAN Controller                         | 1         | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.55%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.55%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.55%   |
| Ralink RT3072 Wireless Adapter                                    | 1         | 0.55%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 24        | 30%     |
| Realtek Semiconductor    | 19        | 23.75%  |
| Qualcomm Atheros         | 17        | 21.25%  |
| Broadcom                 | 5         | 6.25%   |
| Ralink Technology        | 4         | 5%      |
| TP-Link                  | 3         | 3.75%   |
| MediaTek                 | 3         | 3.75%   |
| Ralink                   | 1         | 1.25%   |
| Marvell Technology Group | 1         | 1.25%   |
| Edimax Technology        | 1         | 1.25%   |
| D-Link                   | 1         | 1.25%   |
| Belkin Components        | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 9.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 3         | 3.7%    |
| Realtek 802.11ac NIC                                                                  | 3         | 3.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3         | 3.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 2         | 2.47%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2         | 2.47%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 2.47%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 2.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 2         | 2.47%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 2.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 2         | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.47%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 1.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1         | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 1.23%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1         | 1.23%   |
| Realtek RTL8192SE Wireless LAN Controller                                             | 1         | 1.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.23%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 1.23%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 1.23%   |
| Ralink RT3072 Wireless Adapter                                                        | 1         | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.23%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.23%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 1.23%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                     | 1         | 1.23%   |
| Intel Wireless 8260                                                                   | 1         | 1.23%   |
| Intel Wireless 7265                                                                   | 1         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 1.23%   |
| Intel Centrino Wireless-N 105                                                         | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 62        | 64.58%  |
| Intel                    | 19        | 19.79%  |
| Qualcomm Atheros         | 6         | 6.25%   |
| VIA Technologies         | 2         | 2.08%   |
| D-Link System            | 2         | 2.08%   |
| Samsung Electronics      | 1         | 1.04%   |
| Marvell Technology Group | 1         | 1.04%   |
| JMicron Technology       | 1         | 1.04%   |
| Broadcom                 | 1         | 1.04%   |
| ASIX Electronics         | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 15%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6%      |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 2         | 2%      |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2%      |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 2%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1%      |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1%      |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1%      |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1%      |
| Intel I211 Gigabit Network Connection                             | 1         | 1%      |
| Intel Ethernet Controller I225-V                                  | 1         | 1%      |
| Intel Ethernet Controller I225-LM                                 | 1         | 1%      |
| Intel Ethernet Connection I217-V                                  | 1         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1%      |
| Intel 82579V Gigabit Network Connection                           | 1         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 91        | 54.82%  |
| WiFi     | 74        | 44.58%  |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 51.46%  |
| Ethernet | 50        | 48.54%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 54        | 54%     |
| 1     | 40        | 40%     |
| 0     | 3         | 3%      |
| 3     | 2         | 2%      |
| 5     | 1         | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 56%     |
| Yes  | 44        | 44%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 33.87%  |
| Cambridge Silicon Radio         | 10        | 16.13%  |
| Qualcomm Atheros Communications | 6         | 9.68%   |
| Lite-On Technology              | 6         | 9.68%   |
| Realtek Semiconductor           | 4         | 6.45%   |
| IMC Networks                    | 3         | 4.84%   |
| MediaTek                        | 2         | 3.23%   |
| Foxconn / Hon Hai               | 2         | 3.23%   |
| Broadcom                        | 2         | 3.23%   |
| Marvell Semiconductor           | 1         | 1.61%   |
| Hewlett-Packard                 | 1         | 1.61%   |
| Dell                            | 1         | 1.61%   |
| Apple                           | 1         | 1.61%   |
| Actions                         | 1         | 1.61%   |
| AboCom Systems                  | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 16.13%  |
| Intel Bluetooth wireless interface                  | 5         | 8.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 6.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 6.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4.84%   |
| Intel Bluetooth Device                              | 3         | 4.84%   |
| Intel AX200 Bluetooth                               | 3         | 4.84%   |
| Realtek Bluetooth 5.1 Radio                         | 2         | 3.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 3.23%   |
| MediaTek Wireless_Device                            | 2         | 3.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.61%   |
| Realtek Bluetooth Radio                             | 1         | 1.61%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.61%   |
| Lite-On Bluetooth Device                            | 1         | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.61%   |
| Intel AX210 Bluetooth                               | 1         | 1.61%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.61%   |
| IMC Networks Bluetooth Device                       | 1         | 1.61%   |
| IMC Networks BCM20702A0                             | 1         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.61%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.61%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.61%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.61%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.61%   |
| Actions general adapter                             | 1         | 1.61%   |
| AboCom Systems AboCom Bluetooth Device              | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 76        | 52.78%  |
| AMD                    | 29        | 20.14%  |
| Nvidia                 | 27        | 18.75%  |
| C-Media Electronics    | 3         | 2.08%   |
| Generalplus Technology | 2         | 1.39%   |
| Creative Labs          | 2         | 1.39%   |
| VIA Technologies       | 1         | 0.69%   |
| Roland                 | 1         | 0.69%   |
| Realtek Semiconductor  | 1         | 0.69%   |
| Razer USA              | 1         | 0.69%   |
| DCMT Technology        | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 16        | 9.7%    |
| Intel Sunrise Point-LP HD Audio                                                   | 10        | 6.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 5.45%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8         | 4.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6         | 3.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 3.03%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 3.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 2.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 2.42%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3         | 1.82%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 1.82%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 1.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.82%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.21%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2         | 1.21%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.21%   |
| Nvidia Audio device                                                               | 2         | 1.21%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.21%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 1.21%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 1.21%   |
| Generalplus Technology USB Audio Device                                           | 2         | 1.21%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2         | 1.21%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.21%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 2         | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 1.21%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 2         | 1.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 1.21%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2         | 1.21%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 1         | 0.61%   |
| Roland QUAD-CAPTURE                                                               | 1         | 0.61%   |
| Realtek Semiconductor USB Audio                                                   | 1         | 0.61%   |
| Razer USA Razer Leviathan V2                                                      | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.61%   |
| Nvidia TU102 High Definition Audio Controller                                     | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 12        | 15%     |
| Unknown             | 11        | 13.75%  |
| Samsung Electronics | 11        | 13.75%  |
| Smart               | 7         | 8.75%   |
| SK hynix            | 7         | 8.75%   |
| Micron Technology   | 6         | 7.5%    |
| Corsair             | 6         | 7.5%    |
| Crucial             | 3         | 3.75%   |
| Unknown             | 3         | 3.75%   |
| Teikon              | 2         | 2.5%    |
| Ramaxel Technology  | 2         | 2.5%    |
| G.Skill             | 2         | 2.5%    |
| A-DATA Technology   | 2         | 2.5%    |
| Walton Chaintech    | 1         | 1.25%   |
| Unknown (8A6B)      | 1         | 1.25%   |
| PLEXHD              | 1         | 1.25%   |
| Nanya Technology    | 1         | 1.25%   |
| Kllisre             | 1         | 1.25%   |
| Kembona             | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 3         | 3.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 2         | 2.33%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s                 | 2         | 2.33%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 2.33%   |
| Walton Chaintech RAM AS2G732-800P005 2GB SODIMM DDR2 800MT/s        | 1         | 1.16%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.16%   |
| Unknown RAM Module 8GB DIMM SDRAM                                   | 1         | 1.16%   |
| Unknown RAM Module 512MB SODIMM DDR2                                | 1         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                         | 1         | 1.16%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 1         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 1.16%   |
| Unknown RAM Module 2GB DIMM DDR2 266MT/s                            | 1         | 1.16%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 1         | 1.16%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                          | 1         | 1.16%   |
| Unknown (8A6B) RAM BL.9BWWA.221 8GB DIMM DDR4 2667MT/s              | 1         | 1.16%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s              | 1         | 1.16%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s              | 1         | 1.16%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s               | 1         | 1.16%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s               | 1         | 1.16%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s               | 1         | 1.16%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s               | 1         | 1.16%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s               | 1         | 1.16%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                        | 1         | 1.16%   |
| SK hynix RAM MMXIV 4096MB SODIMM DDR3 1333MT/s                      | 1         | 1.16%   |
| SK hynix RAM MD4512NSE-CB3M2 00 4096MB DIMM DDR4 2400MT/s           | 1         | 1.16%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s               | 1         | 1.16%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s                | 1         | 1.16%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s               | 1         | 1.16%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.16%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1600MT/s                 | 1         | 1.16%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                    | 1         | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.16%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.16%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.16%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s            | 1         | 1.16%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                 | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 42.42%  |
| DDR4    | 23        | 34.85%  |
| SDRAM   | 4         | 6.06%   |
| DDR5    | 4         | 6.06%   |
| DDR2    | 3         | 4.55%   |
| LPDDR3  | 2         | 3.03%   |
| LPDDR4  | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 48.48%  |
| DIMM         | 31        | 46.97%  |
| Row Of Chips | 3         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 36.84%  |
| 4096  | 20        | 26.32%  |
| 2048  | 14        | 18.42%  |
| 16384 | 10        | 13.16%  |
| 32768 | 2         | 2.63%   |
| 1024  | 1         | 1.32%   |
| 512   | 1         | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 19        | 25%     |
| 1333    | 10        | 13.16%  |
| 2400    | 7         | 9.21%   |
| 3200    | 6         | 7.89%   |
| 2667    | 6         | 7.89%   |
| 4800    | 4         | 5.26%   |
| 2133    | 4         | 5.26%   |
| 1334    | 4         | 5.26%   |
| Unknown | 4         | 5.26%   |
| 1867    | 2         | 2.63%   |
| 4266    | 1         | 1.32%   |
| 3866    | 1         | 1.32%   |
| 3800    | 1         | 1.32%   |
| 3733    | 1         | 1.32%   |
| 2200    | 1         | 1.32%   |
| 1067    | 1         | 1.32%   |
| 1066    | 1         | 1.32%   |
| 975     | 1         | 1.32%   |
| 800     | 1         | 1.32%   |
| 266     | 1         | 1.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L382 Series  | 1         | 33.33%  |
| HP Officejet 4620 series | 1         | 33.33%  |
| Brother DCP-T500W        | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Quanta                                 | 8         | 15.38%  |
| Chicony Electronics                    | 7         | 13.46%  |
| Sunplus Innovation Technology          | 5         | 9.62%   |
| Realtek Semiconductor                  | 3         | 5.77%   |
| Microdia                               | 3         | 5.77%   |
| Bison Electronics                      | 3         | 5.77%   |
| Alcor Micro                            | 3         | 5.77%   |
| SunplusIT                              | 2         | 3.85%   |
| Lenovo                                 | 2         | 3.85%   |
| IMC Networks                           | 2         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.85%   |
| Y Media                                | 1         | 1.92%   |
| USB Camera CS                          | 1         | 1.92%   |
| Sonix Technology                       | 1         | 1.92%   |
| Silicon Motion                         | 1         | 1.92%   |
| Samsung Electronics                    | 1         | 1.92%   |
| Microsoft                              | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| Jieli Technology                       | 1         | 1.92%   |
| Generalplus Technology                 | 1         | 1.92%   |
| GEMBIRD                                | 1         | 1.92%   |
| Apple                                  | 1         | 1.92%   |
| Acer                                   | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Quanta VGA WebCam                                   | 3         | 5.77%   |
| SunplusIT MTD camera                                | 2         | 3.85%   |
| Quanta HD Webcam                                    | 2         | 3.85%   |
| Microdia Integrated_Webcam_HD                       | 2         | 3.85%   |
| Chicony HD WebCam                                   | 2         | 3.85%   |
| Y Media USB Camera                                  | 1         | 1.92%   |
| USB Camera CS USB Camera CS                         | 1         | 1.92%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.92%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.92%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 1.92%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.92%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 1.92%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.92%   |
| Silicon Motion Web Camera                           | 1         | 1.92%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.92%   |
| Realtek USB Camera                                  | 1         | 1.92%   |
| Realtek HP Webcam                                   | 1         | 1.92%   |
| Realtek HD WebCam                                   | 1         | 1.92%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 1.92%   |
| Quanta HD User Facing                               | 1         | 1.92%   |
| Quanta ACER HD User Facing                          | 1         | 1.92%   |
| Microsoft LifeCam VX-2000                           | 1         | 1.92%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.92%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.92%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.92%   |
| Lenovo FHD Webcam                                   | 1         | 1.92%   |
| Jieli USB PHY 2.0                                   | 1         | 1.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.92%   |
| IMC Networks Integrated Camera                      | 1         | 1.92%   |
| Generalplus 808 Camera #9 (web-cam mode)            | 1         | 1.92%   |
| GEMBIRD USB2.0 PC CAMERA                            | 1         | 1.92%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.92%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.92%   |
| Chicony Integrated Camera                           | 1         | 1.92%   |
| Chicony FHD Webcam                                  | 1         | 1.92%   |
| Chicony 2.0M UVC WebCam                             | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.92%   |
| Bison Lenovo EasyCamera                             | 1         | 1.92%   |
| Bison HD Webcam                                     | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader       | 1         | 33.33%  |
| Synaptics  WBDI                                  | 1         | 33.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Giesecke & Devrient | 1         | 50%     |
| Broadcom            | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Giesecke & Devrient StarSign CUT               | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 81        | 81%     |
| 1     | 16        | 16%     |
| 2     | 3         | 3%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 8         | 34.78%  |
| Graphics card      | 6         | 26.09%  |
| Fingerprint reader | 3         | 13.04%  |
| Chipcard           | 2         | 8.7%    |
| Unassigned class   | 1         | 4.35%   |
| Storage            | 1         | 4.35%   |
| Network            | 1         | 4.35%   |
| Bluetooth          | 1         | 4.35%   |

