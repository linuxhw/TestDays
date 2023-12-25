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

Total: 138

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| BigLinux                  | 19        | 18.45%  |
| BigLinux 20.04            | 11        | 10.68%  |
| BigLinux 23.0.0           | 7         | 6.8%    |
| BigLinux 22.0.0           | 6         | 5.83%   |
| BigLinux 19.04            | 5         | 4.85%   |
| BigLinux 22.1.0           | 4         | 3.88%   |
| BigLinux 22.0.4           | 4         | 3.88%   |
| BigLinux 23.1.0           | 3         | 2.91%   |
| BigLinux 21.3.7           | 3         | 2.91%   |
| BigLinux 21.3.5           | 3         | 2.91%   |
| BigLinux 23.02.20         | 2         | 1.94%   |
| BigLinux 23.0.3           | 2         | 1.94%   |
| BigLinux 23.0.1           | 2         | 1.94%   |
| BigLinux 2023-12-01_05-13 | 2         | 1.94%   |
| BigLinux 2023-06-30_08-01 | 2         | 1.94%   |
| BigLinux 23.02.24         | 1         | 0.97%   |
| BigLinux 23.02.07         | 1         | 0.97%   |
| BigLinux 23.01.30         | 1         | 0.97%   |
| BigLinux 23.01.06         | 1         | 0.97%   |
| BigLinux 23.0.4           | 1         | 0.97%   |
| BigLinux 22.12.24         | 1         | 0.97%   |
| BigLinux 22.11.19         | 1         | 0.97%   |
| BigLinux 22.11.14         | 1         | 0.97%   |
| BigLinux 22.10.28         | 1         | 0.97%   |
| BigLinux 22.10.06         | 1         | 0.97%   |
| BigLinux 22.1.1           | 1         | 0.97%   |
| BigLinux 22.09.09         | 1         | 0.97%   |
| BigLinux 22.0.5           | 1         | 0.97%   |
| BigLinux 22.0.2           | 1         | 0.97%   |
| BigLinux 21.3.6           | 1         | 0.97%   |
| BigLinux 21.1.2           | 1         | 0.97%   |
| BigLinux 2023-11-24_05-13 | 1         | 0.97%   |
| BigLinux 2023-11-21_03-11 | 1         | 0.97%   |
| BigLinux 2023-11-17_05-13 | 1         | 0.97%   |
| BigLinux 2023-11-13_03-10 | 1         | 0.97%   |
| BigLinux 2023-11-07_19-34 | 1         | 0.97%   |
| BigLinux 2023-10-14_01-04 | 1         | 0.97%   |
| BigLinux 2023-08-04_06-17 | 1         | 0.97%   |
| BigLinux 2023-06-23_06-21 | 1         | 0.97%   |
| BigLinux 2023-06-07_06-02 | 1         | 0.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| BigLinux | 98        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 6.1.55-1-MANJARO           | 7         | 6.54%   |
| 6.1.64-1-MANJARO           | 5         | 4.67%   |
| 6.5.5-1-MANJARO            | 4         | 3.74%   |
| 6.1.62-1-MANJARO           | 4         | 3.74%   |
| 6.1.31-2-MANJARO           | 4         | 3.74%   |
| 6.1.12-1-MANJARO           | 4         | 3.74%   |
| 6.6.3-1-MANJARO            | 3         | 2.8%    |
| 6.1.23-1-MANJARO           | 3         | 2.8%    |
| 5.15.94-1-MANJARO          | 3         | 2.8%    |
| 5.15.85-1-MANJARO          | 3         | 2.8%    |
| 5.15.60-1-MANJARO          | 3         | 2.8%    |
| 6.5.11-1-MANJARO           | 2         | 1.87%   |
| 6.4.12-1-MANJARO           | 2         | 1.87%   |
| 6.2.12-1-MANJARO           | 2         | 1.87%   |
| 6.1.51-1-MANJARO           | 2         | 1.87%   |
| 6.0.8-1-MANJARO            | 2         | 1.87%   |
| 5.8.0-43-generic           | 2         | 1.87%   |
| 5.4.0-37-generic           | 2         | 1.87%   |
| 5.2.8-xanmod8              | 2         | 1.87%   |
| 5.15.78-1-MANJARO          | 2         | 1.87%   |
| 5.15.71-1-MANJARO          | 2         | 1.87%   |
| 5.15.102-1-MANJARO         | 2         | 1.87%   |
| 6.6.5-x64v2-xanmod1-1      | 1         | 0.93%   |
| 6.6.1-1-MANJARO            | 1         | 0.93%   |
| 6.5.10-x64v2-xanmod1-1     | 1         | 0.93%   |
| 6.4.6-1-MANJARO            | 1         | 0.93%   |
| 6.3.5-2-MANJARO            | 1         | 0.93%   |
| 6.3.5-1-MANJARO            | 1         | 0.93%   |
| 6.3.13-1-MANJARO           | 1         | 0.93%   |
| 6.1.9-x64v1-xanmod1-1      | 1         | 0.93%   |
| 6.1.9-1-MANJARO            | 1         | 0.93%   |
| 6.1.64-x64v2-xanmod1-1-lts | 1         | 0.93%   |
| 6.1.63-1-MANJARO           | 1         | 0.93%   |
| 6.1.62-x64v2-xanmod1-1-lts | 1         | 0.93%   |
| 6.1.60-1-MANJARO           | 1         | 0.93%   |
| 6.1.57-x64v2-xanmod1-1-lts | 1         | 0.93%   |
| 6.1.49-1-MANJARO           | 1         | 0.93%   |
| 6.1.26-1-MANJARO           | 1         | 0.93%   |
| 6.1.1-1-MANJARO            | 1         | 0.93%   |
| 5.9.3-xanmod1              | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.55   | 7         | 6.6%    |
| 6.1.64   | 6         | 5.66%   |
| 6.1.62   | 5         | 4.72%   |
| 6.5.5    | 4         | 3.77%   |
| 6.1.31   | 4         | 3.77%   |
| 6.1.12   | 4         | 3.77%   |
| 5.8.0    | 4         | 3.77%   |
| 5.4.0    | 4         | 3.77%   |
| 6.6.3    | 3         | 2.83%   |
| 6.1.23   | 3         | 2.83%   |
| 5.15.94  | 3         | 2.83%   |
| 5.15.85  | 3         | 2.83%   |
| 5.15.60  | 3         | 2.83%   |
| 6.5.11   | 2         | 1.89%   |
| 6.4.12   | 2         | 1.89%   |
| 6.3.5    | 2         | 1.89%   |
| 6.2.12   | 2         | 1.89%   |
| 6.1.9    | 2         | 1.89%   |
| 6.1.51   | 2         | 1.89%   |
| 6.0.8    | 2         | 1.89%   |
| 5.2.8    | 2         | 1.89%   |
| 5.15.78  | 2         | 1.89%   |
| 5.15.71  | 2         | 1.89%   |
| 5.15.102 | 2         | 1.89%   |
| 6.6.5    | 1         | 0.94%   |
| 6.6.1    | 1         | 0.94%   |
| 6.5.10   | 1         | 0.94%   |
| 6.4.6    | 1         | 0.94%   |
| 6.3.13   | 1         | 0.94%   |
| 6.1.63   | 1         | 0.94%   |
| 6.1.60   | 1         | 0.94%   |
| 6.1.57   | 1         | 0.94%   |
| 6.1.49   | 1         | 0.94%   |
| 6.1.26   | 1         | 0.94%   |
| 6.1.1    | 1         | 0.94%   |
| 5.9.3    | 1         | 0.94%   |
| 5.7.9    | 1         | 0.94%   |
| 5.6.6    | 1         | 0.94%   |
| 5.6.10   | 1         | 0.94%   |
| 5.3.6    | 1         | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 38        | 38%     |
| 5.15    | 18        | 18%     |
| 6.5     | 7         | 7%      |
| 6.6     | 5         | 5%      |
| 5.8     | 4         | 4%      |
| 5.4     | 4         | 4%      |
| 5.10    | 4         | 4%      |
| 6.4     | 3         | 3%      |
| 6.3     | 3         | 3%      |
| 5.2     | 3         | 3%      |
| 6.2     | 2         | 2%      |
| 6.0     | 2         | 2%      |
| 5.9     | 1         | 1%      |
| 5.7     | 1         | 1%      |
| 5.6     | 1         | 1%      |
| 5.3     | 1         | 1%      |
| 5.19    | 1         | 1%      |
| 5.17    | 1         | 1%      |
| 5.16    | 1         | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 98        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 89        | 90.82%  |
| KDE      | 6         | 6.12%   |
| Unknown  | 2         | 2.04%   |
| Cinnamon | 1         | 1.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 95        | 95.96%  |
| Wayland | 3         | 3.03%   |
| Unknown | 1         | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 70        | 70.71%  |
| Unknown | 26        | 26.26%  |
| LightDM | 2         | 2.02%   |
| LXDM    | 1         | 1.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| pt_BR   | 60        | 61.22%  |
| en_US   | 14        | 14.29%  |
| es_MX   | 4         | 4.08%   |
| de_DE   | 3         | 3.06%   |
| pt_PT   | 2         | 2.04%   |
| pl_PL   | 2         | 2.04%   |
| en_GB   | 2         | 2.04%   |
| Unknown | 2         | 2.04%   |
| fr_FR   | 1         | 1.02%   |
| fr_BE   | 1         | 1.02%   |
| fi_FI   | 1         | 1.02%   |
| es_ES   | 1         | 1.02%   |
| es_CR   | 1         | 1.02%   |
| es_CO   | 1         | 1.02%   |
| es_AR   | 1         | 1.02%   |
| el_GR   | 1         | 1.02%   |
| de_AT   | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 59        | 59%     |
| BIOS | 41        | 41%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 87        | 88.78%  |
| Ext4    | 8         | 8.16%   |
| Overlay | 2         | 2.04%   |
| Unknown | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 51        | 50.5%   |
| Unknown | 28        | 27.72%  |
| MBR     | 22        | 21.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 95.96%  |
| Yes       | 4         | 4.04%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 58.59%  |
| Yes       | 41        | 41.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 14        | 14.29%  |
| Lenovo                 | 11        | 11.22%  |
| Gigabyte Technology    | 10        | 10.2%   |
| Acer                   | 10        | 10.2%   |
| Intel                  | 8         | 8.16%   |
| Hewlett-Packard        | 8         | 8.16%   |
| Dell                   | 8         | 8.16%   |
| Positivo               | 5         | 5.1%    |
| Semp Toshiba           | 2         | 2.04%   |
| PCWare                 | 2         | 2.04%   |
| MSI                    | 2         | 2.04%   |
| ASRock                 | 2         | 2.04%   |
| Toshiba                | 1         | 1.02%   |
| Sony                   | 1         | 1.02%   |
| Samsung Electronics    | 1         | 1.02%   |
| OEM                    | 1         | 1.02%   |
| Multilaser             | 1         | 1.02%   |
| Microsoft              | 1         | 1.02%   |
| eMachines              | 1         | 1.02%   |
| ECS                    | 1         | 1.02%   |
| Daten Tecnologia       | 1         | 1.02%   |
| Clevo                  | 1         | 1.02%   |
| Biostar                | 1         | 1.02%   |
| BESSTAR Tech           | 1         | 1.02%   |
| Avell High Performance | 1         | 1.02%   |
| Apple                  | 1         | 1.02%   |
| Alienware              | 1         | 1.02%   |
| Unknown                | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                         | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel H61                                                    | 3         | 3.06%   |
| Positivo C41TF                                               | 2         | 2.04%   |
| HP Compaq 8200 Elite SFF PC                                  | 2         | 2.04%   |
| ASRock 775Dual-VSTA                                          | 2         | 2.04%   |
| Toshiba Satellite S55-A                                      | 1         | 1.02%   |
| Sony VGN-NR230AE                                             | 1         | 1.02%   |
| Semp Toshiba STI                                             | 1         | 1.02%   |
| Semp Toshiba IS 1412                                         | 1         | 1.02%   |
| Samsung 300E5M/300E5L                                        | 1         | 1.02%   |
| Positivo Q464B                                               | 1         | 1.02%   |
| Positivo POS-EIH61CQ                                         | 1         | 1.02%   |
| Positivo C14RV01                                             | 1         | 1.02%   |
| PCWare IPX1800E2                                             | 1         | 1.02%   |
| PCWare IPMH81G1                                              | 1         | 1.02%   |
| OEM B75                                                      | 1         | 1.02%   |
| Multilaser MLSH1H LINUX                                      | 1         | 1.02%   |
| MSI MS-7C95                                                  | 1         | 1.02%   |
| MSI MS-7C91                                                  | 1         | 1.02%   |
| Microsoft Surface Pro                                        | 1         | 1.02%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                              | 1         | 1.02%   |
| Lenovo Yoga 520-14IKB 80YM                                   | 1         | 1.02%   |
| Lenovo ThinkPad T480s 20L70028US                             | 1         | 1.02%   |
| Lenovo ThinkPad T410 25379N2                                 | 1         | 1.02%   |
| Lenovo ThinkCentre M93p 10AB0010US                           | 1         | 1.02%   |
| Lenovo ThinkCentre M710s 10M8SBAT00                          | 1         | 1.02%   |
| Lenovo IdeaPad Z470                                          | 1         | 1.02%   |
| Lenovo IdeaPad S400 VIUS3                                    | 1         | 1.02%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                             | 1         | 1.02%   |
| Lenovo IdeaPad 300-15ISK 80RS                                | 1         | 1.02%   |
| Lenovo 63 90AT0002BR                                         | 1         | 1.02%   |
| Intel X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V307 | 1         | 1.02%   |
| Intel NUC11BTMi7                                             | 1         | 1.02%   |
| Intel H55                                                    | 1         | 1.02%   |
| Intel DH61WW AAG23116-203                                    | 1         | 1.02%   |
| Intel B75                                                    | 1         | 1.02%   |
| HP ZBook 15 G3                                               | 1         | 1.02%   |
| HP Pavilion g4                                               | 1         | 1.02%   |
| HP EliteBook 8760w                                           | 1         | 1.02%   |
| HP Compaq Elite 8300 SFF                                     | 1         | 1.02%   |
| HP 255 G7 Notebook PC                                        | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 5         | 5.1%    |
| Lenovo IdeaPad       | 4         | 4.08%   |
| Intel H61            | 3         | 3.06%   |
| HP Compaq            | 3         | 3.06%   |
| Dell Inspiron        | 3         | 3.06%   |
| ASUS VivoBook        | 3         | 3.06%   |
| ASUS TUF             | 3         | 3.06%   |
| Acer Nitro           | 3         | 3.06%   |
| Positivo C41TF       | 2         | 2.04%   |
| Lenovo Yoga          | 2         | 2.04%   |
| Lenovo ThinkPad      | 2         | 2.04%   |
| Lenovo ThinkCentre   | 2         | 2.04%   |
| HP 255               | 2         | 2.04%   |
| Dell System          | 2         | 2.04%   |
| ASRock 775Dual-VSTA  | 2         | 2.04%   |
| Toshiba Satellite    | 1         | 1.02%   |
| Sony VGN-NR230AE     | 1         | 1.02%   |
| Semp Toshiba STI     | 1         | 1.02%   |
| Semp Toshiba IS      | 1         | 1.02%   |
| Samsung 300E5M       | 1         | 1.02%   |
| Positivo Q464B       | 1         | 1.02%   |
| Positivo POS-EIH61CQ | 1         | 1.02%   |
| Positivo C14RV01     | 1         | 1.02%   |
| PCWare IPX1800E2     | 1         | 1.02%   |
| PCWare IPMH81G1      | 1         | 1.02%   |
| OEM B75              | 1         | 1.02%   |
| Multilaser MLSH1H    | 1         | 1.02%   |
| MSI MS-7C95          | 1         | 1.02%   |
| MSI MS-7C91          | 1         | 1.02%   |
| Microsoft Surface    | 1         | 1.02%   |
| Lenovo 63            | 1         | 1.02%   |
| Intel X79            | 1         | 1.02%   |
| Intel NUC11BTMi7     | 1         | 1.02%   |
| Intel H55            | 1         | 1.02%   |
| Intel DH61WW         | 1         | 1.02%   |
| Intel B75            | 1         | 1.02%   |
| HP ZBook             | 1         | 1.02%   |
| HP Pavilion          | 1         | 1.02%   |
| HP EliteBook         | 1         | 1.02%   |
| Gigabyte Z87X-UD4H   | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 11        | 11.22%  |
| 2021 | 10        | 10.2%   |
| 2011 | 9         | 9.18%   |
| 2020 | 8         | 8.16%   |
| 2018 | 8         | 8.16%   |
| 2013 | 8         | 8.16%   |
| 2012 | 7         | 7.14%   |
| 2022 | 6         | 6.12%   |
| 2016 | 5         | 5.1%    |
| 2014 | 5         | 5.1%    |
| 2019 | 4         | 4.08%   |
| 2010 | 4         | 4.08%   |
| 2009 | 4         | 4.08%   |
| 2015 | 3         | 3.06%   |
| 2023 | 2         | 2.04%   |
| 2006 | 2         | 2.04%   |
| 2008 | 1         | 1.02%   |
| 2007 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 49        | 50%     |
| Desktop     | 46        | 46.94%  |
| Tablet      | 1         | 1.02%   |
| Convertible | 1         | 1.02%   |
| Mini pc     | 1         | 1.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 97        | 98.98%  |
| Enabled  | 1         | 1.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 22        | 22.22%  |
| 8.01-16.0   | 18        | 18.18%  |
| 4.01-8.0    | 17        | 17.17%  |
| 16.01-24.0  | 16        | 16.16%  |
| 32.01-64.0  | 15        | 15.15%  |
| 2.01-3.0    | 4         | 4.04%   |
| 24.01-32.0  | 3         | 3.03%   |
| 1.01-2.0    | 3         | 3.03%   |
| 64.01-256.0 | 1         | 1.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 37        | 35.58%  |
| 1.01-2.0   | 34        | 32.69%  |
| 4.01-8.0   | 10        | 9.62%   |
| 3.01-4.0   | 10        | 9.62%   |
| 0.51-1.0   | 6         | 5.77%   |
| 8.01-16.0  | 5         | 4.81%   |
| 24.01-32.0 | 1         | 0.96%   |
| 0.01-0.5   | 1         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 48%     |
| 2      | 25        | 25%     |
| 3      | 16        | 16%     |
| 4      | 7         | 7%      |
| 6      | 3         | 3%      |
| 0      | 1         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 64.65%  |
| Yes       | 35        | 35.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 90.82%  |
| No        | 9         | 9.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 74.49%  |
| No        | 25        | 25.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 61.22%  |
| No        | 38        | 38.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Brazil     | 64        | 65.31%  |
| USA        | 8         | 8.16%   |
| Mexico     | 4         | 4.08%   |
| UK         | 3         | 3.06%   |
| Greece     | 3         | 3.06%   |
| Germany    | 3         | 3.06%   |
| Portugal   | 2         | 2.04%   |
| Poland     | 2         | 2.04%   |
| Spain      | 1         | 1.02%   |
| Japan      | 1         | 1.02%   |
| France     | 1         | 1.02%   |
| Finland    | 1         | 1.02%   |
| Costa Rica | 1         | 1.02%   |
| Colombia   | 1         | 1.02%   |
| Belgium    | 1         | 1.02%   |
| Austria    | 1         | 1.02%   |
| Argentina  | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Sao Paulo              | 6         | 5.94%   |
| Rio de Janeiro         | 4         | 3.96%   |
| Brasília              | 4         | 3.96%   |
| Belo Horizonte         | 3         | 2.97%   |
| Thessaloniki           | 2         | 1.98%   |
| Sao Domingos do Capim  | 2         | 1.98%   |
| Maringá               | 2         | 1.98%   |
| Fortaleza              | 2         | 1.98%   |
| Curitiba               | 2         | 1.98%   |
| Castanhal              | 2         | 1.98%   |
| Caratinga              | 2         | 1.98%   |
| Campo Grande           | 2         | 1.98%   |
| Wiener Neustadt        | 1         | 0.99%   |
| Vitória da Conquista  | 1         | 0.99%   |
| Villa Bosch            | 1         | 0.99%   |
| Vila Velha             | 1         | 0.99%   |
| Vila Nova de Famalicao | 1         | 0.99%   |
| Tokyo                  | 1         | 0.99%   |
| Tlajomulco de Zuniga   | 1         | 0.99%   |
| The Villages           | 1         | 0.99%   |
| Texarkana              | 1         | 0.99%   |
| Stralsund              | 1         | 0.99%   |
| Sao Jose do Rio Preto  | 1         | 0.99%   |
| Sao Joaquim da Barra   | 1         | 0.99%   |
| Santo André           | 1         | 0.99%   |
| Santiago de Cali       | 1         | 0.99%   |
| Santa Cruz de Tenerife | 1         | 0.99%   |
| San José              | 1         | 0.99%   |
| Salvador               | 1         | 0.99%   |
| Ribeirao Grande        | 1         | 0.99%   |
| Rennes                 | 1         | 0.99%   |
| Queimados              | 1         | 0.99%   |
| Piracicaba             | 1         | 0.99%   |
| Osasco                 | 1         | 0.99%   |
| Olsztyn                | 1         | 0.99%   |
| Oklahoma City          | 1         | 0.99%   |
| Niterói               | 1         | 0.99%   |
| Mirassol               | 1         | 0.99%   |
| Minneapolis            | 1         | 0.99%   |
| Metepec                | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 29        | 40     | 17.58%  |
| Seagate                     | 24        | 36     | 14.55%  |
| Samsung Electronics         | 13        | 16     | 7.88%   |
| Kingston                    | 11        | 15     | 6.67%   |
| Toshiba                     | 8         | 9      | 4.85%   |
| China                       | 8         | 10     | 4.85%   |
| Hitachi                     | 7         | 10     | 4.24%   |
| Sandisk                     | 6         | 6      | 3.64%   |
| KingSpec                    | 6         | 6      | 3.64%   |
| Crucial                     | 6         | 6      | 3.64%   |
| Unknown                     | 4         | 4      | 2.42%   |
| ADATA Technology            | 4         | 4      | 2.42%   |
| PNY                         | 3         | 4      | 1.82%   |
| Micron/Crucial Technology   | 3         | 3      | 1.82%   |
| A-DATA Technology           | 3         | 4      | 1.82%   |
| XrayDisk                    | 2         | 2      | 1.21%   |
| SK hynix                    | 2         | 2      | 1.21%   |
| Silicon Motion              | 2         | 2      | 1.21%   |
| Netac                       | 2         | 3      | 1.21%   |
| Micron Technology           | 2         | 2      | 1.21%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 1.21%   |
| LITEON                      | 2         | 3      | 1.21%   |
| Kingston Technology Company | 2         | 2      | 1.21%   |
| JMicron Technology          | 2         | 2      | 1.21%   |
| HGST                        | 2         | 2      | 1.21%   |
| WALRAM                      | 1         | 1      | 0.61%   |
| Plextor                     | 1         | 1      | 0.61%   |
| NT-1TB                      | 1         | 1      | 0.61%   |
| Intel                       | 1         | 1      | 0.61%   |
| GOODRAM                     | 1         | 2      | 0.61%   |
| EYOTA                       | 1         | 1      | 0.61%   |
| BHT                         | 1         | 1      | 0.61%   |
| ASMedia                     | 1         | 1      | 0.61%   |
| Apacer                      | 1         | 1      | 0.61%   |
| Unknown                     | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 2.81%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 2.81%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 4         | 2.25%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 1.69%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 1.69%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 1.69%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 2         | 1.12%   |
| Unknown MMC Card  64GB                              | 2         | 1.12%   |
| Toshiba MQ01ABD050V -63 500GB                       | 2         | 1.12%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 1.12%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 1.12%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 1.12%   |
| Micron/Crucial CT500P5SSD8 500GB                    | 2         | 1.12%   |
| Kingston SV300S37A240G 240GB SSD                    | 2         | 1.12%   |
| KingSpec P3-512 512GB SSD                           | 2         | 1.12%   |
| JMicron Tech 250GB                                  | 2         | 1.12%   |
| Hitachi HDS721050DLE630 500GB                       | 2         | 1.12%   |
| Crucial CT480BX500SSD1 480GB                        | 2         | 1.12%   |
| China SSD 120GB                                     | 2         | 1.12%   |
| XrayDisk 512GB SSD                                  | 1         | 0.56%   |
| XrayDisk 120GB                                      | 1         | 0.56%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.56%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 1         | 0.56%   |
| WDC WD800BD-22MRA1 80GB                             | 1         | 0.56%   |
| WDC WD800AAJS-75M0A0 80GB                           | 1         | 0.56%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 0.56%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.56%   |
| WDC WD5000LPVT-08G33T1 500GB                        | 1         | 0.56%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.56%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 0.56%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 0.56%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 0.56%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1         | 0.56%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.56%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 0.56%   |
| WDC WD3200AAKS-75L9A0 320GB                         | 1         | 0.56%   |
| WDC WD3200AAJS-56M0A0 320GB                         | 1         | 0.56%   |
| WDC WD30EFAX-68JH4N0 3TB                            | 1         | 0.56%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 0.56%   |
| WDC WD1200BEVT-75ZCT2 120GB                         | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 38     | 38.57%  |
| Seagate             | 24        | 36     | 34.29%  |
| Toshiba             | 7         | 8      | 10%     |
| Hitachi             | 7         | 10     | 10%     |
| Samsung Electronics | 2         | 4      | 2.86%   |
| HGST                | 2         | 2      | 2.86%   |
| Unknown             | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 14     | 18.03%  |
| China               | 8         | 10     | 13.11%  |
| KingSpec            | 6         | 6      | 9.84%   |
| Crucial             | 6         | 6      | 9.84%   |
| Samsung Electronics | 5         | 6      | 8.2%    |
| SanDisk             | 4         | 4      | 6.56%   |
| PNY                 | 3         | 4      | 4.92%   |
| A-DATA Technology   | 3         | 4      | 4.92%   |
| WDC                 | 2         | 2      | 3.28%   |
| Micron Technology   | 2         | 2      | 3.28%   |
| LITEON              | 2         | 3      | 3.28%   |
| XrayDisk            | 1         | 1      | 1.64%   |
| Toshiba             | 1         | 1      | 1.64%   |
| Plextor             | 1         | 1      | 1.64%   |
| NT-1TB              | 1         | 1      | 1.64%   |
| GOODRAM             | 1         | 2      | 1.64%   |
| BHT                 | 1         | 1      | 1.64%   |
| ASMedia             | 1         | 1      | 1.64%   |
| Apacer              | 1         | 1      | 1.64%   |
| Unknown             | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 58        | 99     | 40.85%  |
| SSD     | 51        | 71     | 35.92%  |
| NVMe    | 25        | 28     | 17.61%  |
| Unknown | 5         | 5      | 3.52%   |
| MMC     | 3         | 3      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 168    | 71.07%  |
| NVMe | 25        | 28     | 20.66%  |
| SAS  | 7         | 7      | 5.79%   |
| MMC  | 3         | 3      | 2.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 95     | 55.75%  |
| 0.51-1.0   | 38        | 57     | 33.63%  |
| 1.01-2.0   | 7         | 8      | 6.19%   |
| 3.01-4.0   | 3         | 7      | 2.65%   |
| 2.01-3.0   | 1         | 1      | 0.88%   |
| 4.01-10.0  | 1         | 2      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 24        | 24.24%  |
| 2001-3000      | 21        | 21.21%  |
| 251-500        | 16        | 16.16%  |
| More than 3000 | 12        | 12.12%  |
| 101-250        | 12        | 12.12%  |
| 501-1000       | 11        | 11.11%  |
| 1-20           | 2         | 2.02%   |
| 51-100         | 1         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 27        | 26.21%  |
| 51-100         | 25        | 24.27%  |
| 251-500        | 15        | 14.56%  |
| 101-250        | 13        | 12.62%  |
| 501-1000       | 11        | 10.68%  |
| 1-20           | 8         | 7.77%   |
| 2001-3000      | 2         | 1.94%   |
| More than 3000 | 1         | 0.97%   |
| 1001-2000      | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 40%     |
| WDC     | 5         | 8      | 33.33%  |
| Hitachi | 3         | 3      | 20%     |
| Toshiba | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 19     | 76.47%  |
| SSD  | 3         | 3      | 17.65%  |
| NVMe | 1         | 1      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 60        | 113    | 52.17%  |
| Works    | 38        | 69     | 33.04%  |
| Malfunc  | 16        | 23     | 13.91%  |
| Failed   | 1         | 1      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 70        | 58.82%  |
| AMD                         | 16        | 13.45%  |
| Samsung Electronics         | 5         | 4.2%    |
| ADATA Technology            | 4         | 3.36%   |
| Micron/Crucial Technology   | 3         | 2.52%   |
| Kingston Technology Company | 3         | 2.52%   |
| VIA Technologies            | 2         | 1.68%   |
| SK hynix                    | 2         | 1.68%   |
| Silicon Motion              | 2         | 1.68%   |
| SanDisk                     | 2         | 1.68%   |
| Netac Technology            | 2         | 1.68%   |
| MAXIO Technology (Hangzhou) | 2         | 1.68%   |
| Marvell Technology Group    | 2         | 1.68%   |
| Phison Electronics          | 1         | 0.84%   |
| Nvidia                      | 1         | 0.84%   |
| Lite-On IT Corp. / Plextor  | 1         | 0.84%   |
| JMicron Technology          | 1         | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 8.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 5.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 3.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 3.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 4         | 3.01%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 3.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 2.26%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2         | 1.5%    |
| VIA VT8237A SATA 2-Port Controller                                             | 2         | 1.5%    |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 2         | 1.5%    |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 1.5%    |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.5%    |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.75%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 0.75%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.75%   |
| Samsung NVMe SSD SM0032L                                                       | 1         | 0.75%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.75%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.75%   |
| Netac PCIe 4 NVMe SSD (DRAM-less)                                              | 1         | 0.75%   |
| Netac PCIe 4 INNOGRIT based NVMe SSD                                           | 1         | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602                                   | 1         | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 0.75%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1         | 0.75%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 0.75%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]              | 1         | 0.75%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 75        | 64.1%   |
| NVMe | 24        | 20.51%  |
| IDE  | 11        | 9.4%    |
| RAID | 7         | 5.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 78        | 79.59%  |
| AMD    | 20        | 20.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 3.06%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 3.06%   |
| Intel Pentium D CPU 3.00GHz                 | 2         | 2.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 2.04%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2         | 2.04%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2         | 2.04%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 2.04%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 2.04%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2         | 2.04%   |
| Intel Xeon CPU E5-2603 v3 @ 1.60GHz         | 1         | 1.02%   |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz         | 1         | 1.02%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.02%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.02%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 1         | 1.02%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.02%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.02%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 1.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.02%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.02%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.02%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 1.02%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.02%   |
| Intel Core i7 CPU S 860 @ 2.53GHz           | 1         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.02%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.02%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.02%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.02%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1         | 1.02%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1.02%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 1.02%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.02%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 28        | 28.57%  |
| Intel Core i7           | 15        | 15.31%  |
| Intel Core i3           | 11        | 11.22%  |
| AMD Ryzen 5             | 8         | 8.16%   |
| Other                   | 6         | 6.12%   |
| Intel Celeron           | 6         | 6.12%   |
| AMD Ryzen 7             | 5         | 5.1%    |
| Intel Pentium Dual-Core | 3         | 3.06%   |
| Intel Xeon              | 2         | 2.04%   |
| Intel Pentium D         | 2         | 2.04%   |
| Intel Pentium Silver    | 1         | 1.02%   |
| Intel Pentium Dual      | 1         | 1.02%   |
| Intel Pentium           | 1         | 1.02%   |
| Intel Core 2 Quad       | 1         | 1.02%   |
| Intel Core 2 Duo        | 1         | 1.02%   |
| Intel Atom              | 1         | 1.02%   |
| AMD Ryzen Threadripper  | 1         | 1.02%   |
| AMD Ryzen 9             | 1         | 1.02%   |
| AMD Phenom II X6        | 1         | 1.02%   |
| AMD C-70                | 1         | 1.02%   |
| AMD C-60                | 1         | 1.02%   |
| AMD Athlon              | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 42.86%  |
| 4      | 33        | 33.67%  |
| 6      | 12        | 12.24%  |
| 8      | 6         | 6.12%   |
| 12     | 3         | 3.06%   |
| 14     | 1         | 1.02%   |
| 1      | 1         | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 97        | 98.98%  |
| 2      | 1         | 1.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 61        | 62.24%  |
| 1      | 37        | 37.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 97        | 98.98%  |
| Unknown        | 1         | 1.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 20.41%  |
| 0x206a7    | 12        | 12.24%  |
| 0x806e9    | 6         | 6.12%   |
| 0x306c3    | 6         | 6.12%   |
| 0x306a9    | 6         | 6.12%   |
| 0x506e3    | 4         | 4.08%   |
| 0x1067a    | 3         | 3.06%   |
| 0x0800820d | 3         | 3.06%   |
| 0xf64      | 2         | 2.04%   |
| 0x906a3    | 2         | 2.04%   |
| 0x806d1    | 2         | 2.04%   |
| 0x706a8    | 2         | 2.04%   |
| 0x08108109 | 2         | 2.04%   |
| 0x05000119 | 2         | 2.04%   |
| 0xa0671    | 1         | 1.02%   |
| 0x906ed    | 1         | 1.02%   |
| 0x906c0    | 1         | 1.02%   |
| 0x806ec    | 1         | 1.02%   |
| 0x806ea    | 1         | 1.02%   |
| 0x706e5    | 1         | 1.02%   |
| 0x6fd      | 1         | 1.02%   |
| 0x6fb      | 1         | 1.02%   |
| 0x406e3    | 1         | 1.02%   |
| 0x406c4    | 1         | 1.02%   |
| 0x306f2    | 1         | 1.02%   |
| 0x306e4    | 1         | 1.02%   |
| 0x30678    | 1         | 1.02%   |
| 0x20655    | 1         | 1.02%   |
| 0x20652    | 1         | 1.02%   |
| 0x0a601201 | 1         | 1.02%   |
| 0x0a50000d | 1         | 1.02%   |
| 0x0a404102 | 1         | 1.02%   |
| 0x0a20120a | 1         | 1.02%   |
| 0x0a201025 | 1         | 1.02%   |
| 0x08701021 | 1         | 1.02%   |
| 0x08600106 | 1         | 1.02%   |
| 0x0810100b | 1         | 1.02%   |
| 0x08001137 | 1         | 1.02%   |
| 0x06006705 | 1         | 1.02%   |
| 0x010000dc | 1         | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 16        | 16.33%  |
| KabyLake         | 14        | 14.29%  |
| Haswell          | 9         | 9.18%   |
| IvyBridge        | 8         | 8.16%   |
| Skylake          | 6         | 6.12%   |
| Zen+             | 5         | 5.1%    |
| Penryn           | 4         | 4.08%   |
| Icelake          | 4         | 4.08%   |
| Zen 3            | 3         | 3.06%   |
| Zen 2            | 3         | 3.06%   |
| Goldmont plus    | 3         | 3.06%   |
| Unknown          | 3         | 3.06%   |
| Zen              | 2         | 2.04%   |
| Westmere         | 2         | 2.04%   |
| Silvermont       | 2         | 2.04%   |
| NetBurst         | 2         | 2.04%   |
| Core             | 2         | 2.04%   |
| Bobcat           | 2         | 2.04%   |
| Alderlake Hybrid | 2         | 2.04%   |
| Tremont          | 1         | 1.02%   |
| Nehalem          | 1         | 1.02%   |
| K8 Hammer        | 1         | 1.02%   |
| K10              | 1         | 1.02%   |
| Excavator        | 1         | 1.02%   |
| CometLake        | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 49.57%  |
| Nvidia | 33        | 28.21%  |
| AMD    | 26        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11        | 9.17%   |
| Intel HD Graphics 620                                                       | 8         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 3.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.5%    |
| Nvidia GM108M [GeForce 940MX]                                               | 2         | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.67%   |
| Intel HD Graphics 630                                                       | 2         | 1.67%   |
| Intel HD Graphics 530                                                       | 2         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.67%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 2         | 1.67%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2         | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.67%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 1.67%   |
| AMD Caicos PRO [Radeon HD 7450]                                             | 2         | 1.67%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2         | 1.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 0.83%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.83%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1         | 0.83%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.83%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 0.83%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.83%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                    | 1         | 0.83%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1         | 0.83%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.83%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 0.83%   |
| Nvidia GM108M [GeForce 920MX]                                               | 1         | 0.83%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 1         | 0.83%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1         | 0.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.83%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.83%   |
| Nvidia GK106M [GeForce GTX 770M]                                            | 1         | 0.83%   |
| Nvidia GF116M [GeForce GT 560M]                                             | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 38.38%  |
| 1 x AMD        | 22        | 22.22%  |
| 1 x Nvidia     | 18        | 18.18%  |
| Intel + Nvidia | 14        | 14.14%  |
| 2 x Intel      | 2         | 2.02%   |
| 2 x AMD        | 2         | 2.02%   |
| Intel + AMD    | 2         | 2.02%   |
| AMD + Nvidia   | 1         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 72        | 73.47%  |
| Proprietary | 24        | 24.49%  |
| Unknown     | 2         | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 55.1%   |
| 1.01-2.0   | 16        | 16.33%  |
| 0.01-0.5   | 8         | 8.16%   |
| 7.01-8.0   | 6         | 6.12%   |
| 3.01-4.0   | 5         | 5.1%    |
| 0.51-1.0   | 5         | 5.1%    |
| 5.01-6.0   | 2         | 2.04%   |
| 2.01-3.0   | 1         | 1.02%   |
| 8.01-16.0  | 1         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 17.27%  |
| LG Display              | 11        | 10%     |
| AU Optronics            | 11        | 10%     |
| Chimei Innolux          | 10        | 9.09%   |
| BOE                     | 10        | 9.09%   |
| Goldstar                | 9         | 8.18%   |
| AOC                     | 6         | 5.45%   |
| Dell                    | 4         | 3.64%   |
| Philips                 | 3         | 2.73%   |
| Unknown (XXX)           | 2         | 1.82%   |
| Sony                    | 2         | 1.82%   |
| Positivo                | 2         | 1.82%   |
| Panasonic               | 2         | 1.82%   |
| Hewlett-Packard         | 2         | 1.82%   |
| GDH                     | 2         | 1.82%   |
| Chi Mei Optoelectronics | 2         | 1.82%   |
| VIZ                     | 1         | 0.91%   |
| Philco                  | 1         | 0.91%   |
| NEC Computers           | 1         | 0.91%   |
| MTD                     | 1         | 0.91%   |
| LRX                     | 1         | 0.91%   |
| LG Electronics          | 1         | 0.91%   |
| Lenovo                  | 1         | 0.91%   |
| ITE                     | 1         | 0.91%   |
| Denver                  | 1         | 0.91%   |
| CSO                     | 1         | 0.91%   |
| BenQ                    | 1         | 0.91%   |
| ASUSTek Computer        | 1         | 0.91%   |
| Apple                   | 1         | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch           | 3         | 2.63%   |
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch    | 2         | 1.75%   |
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                       | 2         | 1.75%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 2         | 1.75%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 1.75%   |
| GDH Smart TV GDH0030 1920x1080 708x398mm 32.0-inch                      | 2         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 1.75%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                        | 2         | 1.75%   |
| VIZ LCD Monitor M190VA 1360x768                                         | 1         | 0.88%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 0.88%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1         | 0.88%   |
| Sony TV SNY7E02 1920x1080                                               | 1         | 0.88%   |
| Sony TV SNY1A02 1920x1080                                               | 1         | 0.88%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch       | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch     | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch     | 1         | 0.88%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch     | 1         | 0.88%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch    | 1         | 0.88%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1         | 0.88%   |
| Samsung Electronics S19B300 SAM08A5 1366x768 410x230mm 18.5-inch        | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM0E33 1920x1080 1210x680mm 54.6-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 886x498mm 40.0-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM02C9 1360x768 885x498mm 40.0-inch    | 1         | 0.88%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                       | 1         | 0.88%   |
| Positivo UNION NON1500 1360x768 344x194mm 15.5-inch                     | 1         | 0.88%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                    | 1         | 0.88%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                 | 1         | 0.88%   |
| Philips 24M1N3200ZA PHLC276 1920x1080 527x296mm 23.8-inch               | 1         | 0.88%   |
| Philips 237E4 PHLC0AD 1920x1080 509x286mm 23.0-inch                     | 1         | 0.88%   |
| Philco TV PLC0003 1440x900 708x398mm 32.0-inch                          | 1         | 0.88%   |
| NEC Computers LCD1770VX NEC6697 1280x960 338x270mm 17.0-inch            | 1         | 0.88%   |
| MTD LCD Monitor MTD0001 1280x800 303x190mm 14.1-inch                    | 1         | 0.88%   |
| LRX '' LRX2281 1600x900                                                 | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 32.73%  |
| 1366x768 (WXGA)    | 31        | 28.18%  |
| 3840x2160 (4K)     | 7         | 6.36%   |
| 2560x1080          | 6         | 5.45%   |
| 1360x768           | 6         | 5.45%   |
| 1600x900 (HD+)     | 5         | 4.55%   |
| 1920x540           | 3         | 2.73%   |
| 1440x900 (WXGA+)   | 3         | 2.73%   |
| 1280x800 (WXGA)    | 3         | 2.73%   |
| 1680x1050 (WSXGA+) | 2         | 1.82%   |
| 3200x1080          | 1         | 0.91%   |
| 2880x1800          | 1         | 0.91%   |
| 2736x1824          | 1         | 0.91%   |
| 2560x1440 (QHD)    | 1         | 0.91%   |
| 1920x1200 (WUXGA)  | 1         | 0.91%   |
| 1280x960           | 1         | 0.91%   |
| 1280x1024 (SXGA)   | 1         | 0.91%   |
| Unknown            | 1         | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 21.62%  |
| 14      | 11        | 9.91%   |
| 13      | 10        | 9.01%   |
| 17      | 9         | 8.11%   |
| 23      | 8         | 7.21%   |
| 18      | 8         | 7.21%   |
| Unknown | 5         | 4.5%    |
| 27      | 4         | 3.6%    |
| 54      | 3         | 2.7%    |
| 34      | 3         | 2.7%    |
| 31      | 3         | 2.7%    |
| 24      | 3         | 2.7%    |
| 21      | 3         | 2.7%    |
| 20      | 3         | 2.7%    |
| 72      | 2         | 1.8%    |
| 52      | 2         | 1.8%    |
| 40      | 2         | 1.8%    |
| 19      | 2         | 1.8%    |
| 84      | 1         | 0.9%    |
| 32      | 1         | 0.9%    |
| 29      | 1         | 0.9%    |
| 28      | 1         | 0.9%    |
| 25      | 1         | 0.9%    |
| 12      | 1         | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 40.91%  |
| 401-500     | 16        | 14.55%  |
| 501-600     | 14        | 12.73%  |
| 351-400     | 8         | 7.27%   |
| 601-700     | 6         | 5.45%   |
| 1001-1500   | 5         | 4.55%   |
| Unknown     | 5         | 4.55%   |
| 701-800     | 4         | 3.64%   |
| 1501-2000   | 3         | 2.73%   |
| 801-900     | 2         | 1.82%   |
| 201-300     | 2         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 75.51%  |
| 16/10   | 10        | 10.2%   |
| 21/9    | 6         | 6.12%   |
| Unknown | 4         | 4.08%   |
| 5/4     | 3         | 3.06%   |
| 3/2     | 1         | 1.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 21.82%  |
| 81-90          | 21        | 19.09%  |
| 201-250        | 12        | 10.91%  |
| 141-150        | 9         | 8.18%   |
| More than 1000 | 8         | 7.27%   |
| 351-500        | 7         | 6.36%   |
| 151-200        | 6         | 5.45%   |
| 121-130        | 6         | 5.45%   |
| 301-350        | 5         | 4.55%   |
| Unknown        | 5         | 4.55%   |
| 251-300        | 3         | 2.73%   |
| 501-1000       | 2         | 1.82%   |
| 71-80          | 1         | 0.91%   |
| 131-140        | 1         | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 39        | 37.14%  |
| 101-120       | 33        | 31.43%  |
| 121-160       | 18        | 17.14%  |
| 1-50          | 8         | 7.62%   |
| Unknown       | 5         | 4.76%   |
| More than 240 | 1         | 0.95%   |
| 161-240       | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 72        | 72.73%  |
| 2     | 24        | 24.24%  |
| 0     | 3         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 45.39%  |
| Intel                    | 32        | 21.05%  |
| Qualcomm Atheros         | 22        | 14.47%  |
| Broadcom                 | 5         | 3.29%   |
| Ralink Technology        | 4         | 2.63%   |
| TP-Link                  | 3         | 1.97%   |
| MediaTek                 | 3         | 1.97%   |
| VIA Technologies         | 2         | 1.32%   |
| Marvell Technology Group | 2         | 1.32%   |
| D-Link System            | 2         | 1.32%   |
| Samsung Electronics      | 1         | 0.66%   |
| Ralink                   | 1         | 0.66%   |
| Prolific Technology      | 1         | 0.66%   |
| JMicron Technology       | 1         | 0.66%   |
| Edimax Technology        | 1         | 0.66%   |
| D-Link                   | 1         | 0.66%   |
| Belkin Components        | 1         | 0.66%   |
| ASIX Electronics         | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 21.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 8.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 4.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 1.68%   |
| Realtek 802.11ac NIC                                              | 3         | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.68%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.12%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 1.12%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.12%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.12%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.12%   |
| Intel Wireless 8265 / 8275                                        | 2         | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.12%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 1.12%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.12%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.56%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.56%   |
| Realtek RTL8192SE Wireless LAN Controller                         | 1         | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.56%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.56%   |
| Ralink RT3072 Wireless Adapter                                    | 1         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 29.11%  |
| Realtek Semiconductor    | 19        | 24.05%  |
| Qualcomm Atheros         | 17        | 21.52%  |
| Broadcom                 | 5         | 6.33%   |
| Ralink Technology        | 4         | 5.06%   |
| TP-Link                  | 3         | 3.8%    |
| MediaTek                 | 3         | 3.8%    |
| Ralink                   | 1         | 1.27%   |
| Marvell Technology Group | 1         | 1.27%   |
| Edimax Technology        | 1         | 1.27%   |
| D-Link                   | 1         | 1.27%   |
| Belkin Components        | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 10%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 3         | 3.75%   |
| Realtek 802.11ac NIC                                                                  | 3         | 3.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 3         | 3.75%   |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 3.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3         | 3.75%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 2         | 2.5%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2         | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 2.5%    |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 2         | 2.5%    |
| Intel Wireless 8265 / 8275                                                            | 2         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 2         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 2.5%    |
| TP-Link Archer T4U ver.3                                                              | 1         | 1.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1         | 1.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 1.25%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1         | 1.25%   |
| Realtek RTL8192SE Wireless LAN Controller                                             | 1         | 1.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 1.25%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 1.25%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 1.25%   |
| Ralink RT3072 Wireless Adapter                                                        | 1         | 1.25%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.25%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.25%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 1.25%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                     | 1         | 1.25%   |
| Intel Wireless 8260                                                                   | 1         | 1.25%   |
| Intel Wireless 7265                                                                   | 1         | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1         | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1         | 1.25%   |
| Intel Centrino Wireless-N 105                                                         | 1         | 1.25%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 64.89%  |
| Intel                    | 18        | 19.15%  |
| Qualcomm Atheros         | 6         | 6.38%   |
| VIA Technologies         | 2         | 2.13%   |
| D-Link System            | 2         | 2.13%   |
| Samsung Electronics      | 1         | 1.06%   |
| Marvell Technology Group | 1         | 1.06%   |
| JMicron Technology       | 1         | 1.06%   |
| Broadcom                 | 1         | 1.06%   |
| ASIX Electronics         | 1         | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 39.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 15.31%  |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.1%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.04%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.04%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.04%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 2.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.02%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 1.02%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.02%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.02%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 89        | 54.6%   |
| WiFi     | 73        | 44.79%  |
| Modem    | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 51.49%  |
| Ethernet | 49        | 48.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 53        | 54.08%  |
| 1     | 39        | 39.8%   |
| 0     | 3         | 3.06%   |
| 3     | 2         | 2.04%   |
| 5     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 55.1%   |
| Yes  | 44        | 44.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 33.33%  |
| Cambridge Silicon Radio         | 9         | 15%     |
| Qualcomm Atheros Communications | 6         | 10%     |
| Lite-On Technology              | 6         | 10%     |
| Realtek Semiconductor           | 4         | 6.67%   |
| IMC Networks                    | 3         | 5%      |
| MediaTek                        | 2         | 3.33%   |
| Foxconn / Hon Hai               | 2         | 3.33%   |
| Broadcom                        | 2         | 3.33%   |
| Marvell Semiconductor           | 1         | 1.67%   |
| Hewlett-Packard                 | 1         | 1.67%   |
| Dell                            | 1         | 1.67%   |
| Apple                           | 1         | 1.67%   |
| Actions                         | 1         | 1.67%   |
| AboCom Systems                  | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 15%     |
| Intel Bluetooth wireless interface                  | 5         | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 6.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 5%      |
| Intel AX201 Bluetooth                               | 3         | 5%      |
| Intel AX200 Bluetooth                               | 3         | 5%      |
| Realtek Bluetooth 5.1 Radio                         | 2         | 3.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 3.33%   |
| MediaTek Wireless_Device                            | 2         | 3.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.67%   |
| Realtek Bluetooth Radio                             | 1         | 1.67%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.67%   |
| Lite-On Bluetooth Device                            | 1         | 1.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.67%   |
| Intel AX210 Bluetooth                               | 1         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.67%   |
| IMC Networks Bluetooth Device                       | 1         | 1.67%   |
| IMC Networks BCM20702A0                             | 1         | 1.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.67%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.67%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.67%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.67%   |
| Actions general adapter                             | 1         | 1.67%   |
| AboCom Systems AboCom Bluetooth Device              | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 74        | 52.11%  |
| AMD                    | 29        | 20.42%  |
| Nvidia                 | 27        | 19.01%  |
| C-Media Electronics    | 3         | 2.11%   |
| Generalplus Technology | 2         | 1.41%   |
| Creative Labs          | 2         | 1.41%   |
| VIA Technologies       | 1         | 0.7%    |
| Roland                 | 1         | 0.7%    |
| Realtek Semiconductor  | 1         | 0.7%    |
| Razer USA              | 1         | 0.7%    |
| DCMT Technology        | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 15        | 9.2%    |
| Intel Sunrise Point-LP HD Audio                                                   | 10        | 6.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 5.52%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8         | 4.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6         | 3.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 3.07%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 3.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 2.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 2.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 2.45%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3         | 1.84%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 1.84%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 1.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 1.84%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 1.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.84%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.23%   |
| Nvidia GM206 High Definition Audio Controller                                     | 2         | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.23%   |
| Nvidia Audio device                                                               | 2         | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.23%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 1.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 1.23%   |
| Generalplus Technology USB Audio Device                                           | 2         | 1.23%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2         | 1.23%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.23%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 2         | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 1.23%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 2         | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 1.23%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2         | 1.23%   |
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

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


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

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 3         | 3.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 2         | 2.33%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s                 | 2         | 2.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 2.33%   |
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
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.16%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.16%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.16%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s            | 1         | 1.16%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                 | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


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

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 48.48%  |
| DIMM         | 31        | 46.97%  |
| Row Of Chips | 3         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


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

![Memory Speed](./images/pie_chart/memory_speed.svg)


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

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


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

![Camera Model](./images/pie_chart/camera_model.svg)


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
| Sunplus HP HD Webcam [Fixed]                        | 1         | 1.92%   |
| Sunplus FHD Camera Microphone                       | 1         | 1.92%   |
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

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader       | 1         | 33.33%  |
| Synaptics  WBDI                                  | 1         | 33.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Giesecke & Devrient | 1         | 50%     |
| Broadcom            | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Giesecke & Devrient StarSign CUT               | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 79        | 80.61%  |
| 1     | 16        | 16.33%  |
| 2     | 3         | 3.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


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

