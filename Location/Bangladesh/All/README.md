Linux in Bangladesh - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Bangladesh.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bangladesh/Desktop/README.md) and [notebooks](/Location/Bangladesh/Notebook/README.md).

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

Total: 398

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [47db699ed6](https://linux-hardware.org/?probe=47db699ed6) | Feb 18, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c1e5226b6e](https://linux-hardware.org/?probe=c1e5226b6e) | Feb 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [6cda8724a4](https://linux-hardware.org/?probe=6cda8724a4) | Feb 14, 2023 |
| Toshiba       | Satellite Pro L510          | Notebook    | [c8dc3a76e5](https://linux-hardware.org/?probe=c8dc3a76e5) | Feb 06, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [63143e2bf5](https://linux-hardware.org/?probe=63143e2bf5) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f8630776ca](https://linux-hardware.org/?probe=f8630776ca) | Jan 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cf6bdca9c4](https://linux-hardware.org/?probe=cf6bdca9c4) | Jan 23, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c3f150a8f4](https://linux-hardware.org/?probe=c3f150a8f4) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [d2ac110bfb](https://linux-hardware.org/?probe=d2ac110bfb) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [ad5c9e7f6a](https://linux-hardware.org/?probe=ad5c9e7f6a) | Jan 18, 2023 |
| HP            | Notebook                    | Notebook    | [fbdf174a63](https://linux-hardware.org/?probe=fbdf174a63) | Jan 16, 2023 |
| Dell          | Latitude 5300               | Notebook    | [8149377926](https://linux-hardware.org/?probe=8149377926) | Jan 15, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [bddd00febc](https://linux-hardware.org/?probe=bddd00febc) | Jan 15, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [e5773ce5f8](https://linux-hardware.org/?probe=e5773ce5f8) | Jan 11, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [53043b7d75](https://linux-hardware.org/?probe=53043b7d75) | Jan 10, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [3566221932](https://linux-hardware.org/?probe=3566221932) | Jan 06, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3a505870ba](https://linux-hardware.org/?probe=3a505870ba) | Dec 22, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [7c8e3bbb6a](https://linux-hardware.org/?probe=7c8e3bbb6a) | Dec 21, 2022 |
| HP            | 15                          | Notebook    | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [4b44d6e506](https://linux-hardware.org/?probe=4b44d6e506) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | Desktop     | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [3e9c2f0201](https://linux-hardware.org/?probe=3e9c2f0201) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | Notebook    | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9836f71cb7](https://linux-hardware.org/?probe=9836f71cb7) | Nov 24, 2022 |
| Lenovo        | G40-70 20369                | Notebook    | [aafdfb20ff](https://linux-hardware.org/?probe=aafdfb20ff) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9b9a13f34f](https://linux-hardware.org/?probe=9b9a13f34f) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [4efc557c1b](https://linux-hardware.org/?probe=4efc557c1b) | Nov 24, 2022 |
| HP            | 15                          | Notebook    | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| Dell          | G7 7700                     | Notebook    | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [2c342fa72f](https://linux-hardware.org/?probe=2c342fa72f) | Nov 14, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b5080a1102](https://linux-hardware.org/?probe=b5080a1102) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2548bcefe0](https://linux-hardware.org/?probe=2548bcefe0) | Nov 04, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [fbe835b8ef](https://linux-hardware.org/?probe=fbe835b8ef) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [e1a32857ba](https://linux-hardware.org/?probe=e1a32857ba) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [9357d641ef](https://linux-hardware.org/?probe=9357d641ef) | Oct 18, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [068a780cce](https://linux-hardware.org/?probe=068a780cce) | Oct 17, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [d4c5e9f853](https://linux-hardware.org/?probe=d4c5e9f853) | Oct 16, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [5dd9f2cda4](https://linux-hardware.org/?probe=5dd9f2cda4) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ee4c1a5f66](https://linux-hardware.org/?probe=ee4c1a5f66) | Oct 03, 2022 |
| Biostar       | G41D3C                      | Desktop     | [97ee103719](https://linux-hardware.org/?probe=97ee103719) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8f28254d53](https://linux-hardware.org/?probe=8f28254d53) | Sep 20, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [e92b56817a](https://linux-hardware.org/?probe=e92b56817a) | Sep 14, 2022 |
| Biostar       | G41D3C                      | Desktop     | [280212d494](https://linux-hardware.org/?probe=280212d494) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6d15a54350](https://linux-hardware.org/?probe=6d15a54350) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [09d42cd406](https://linux-hardware.org/?probe=09d42cd406) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [c45809d681](https://linux-hardware.org/?probe=c45809d681) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [aa1cd85ea9](https://linux-hardware.org/?probe=aa1cd85ea9) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Toshiba       | Satellite L645              | Notebook    | [642a6f7602](https://linux-hardware.org/?probe=642a6f7602) | Sep 03, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| HP            | Pavilion x360 m3 Convert... | Convertible | [bde621edc4](https://linux-hardware.org/?probe=bde621edc4) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [ae85f68d58](https://linux-hardware.org/?probe=ae85f68d58) | Aug 15, 2022 |
| Acer          | Aspire M5-581T              | Notebook    | [7efdb0e467](https://linux-hardware.org/?probe=7efdb0e467) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [41f0d0b264](https://linux-hardware.org/?probe=41f0d0b264) | Aug 02, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [2dc0ffa0d1](https://linux-hardware.org/?probe=2dc0ffa0d1) | Jul 26, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| HP            | 14                          | Notebook    | [816a62dde0](https://linux-hardware.org/?probe=816a62dde0) | Jul 07, 2022 |
| Timi          | Mi NoteBook Pro             | Notebook    | [046a18dc14](https://linux-hardware.org/?probe=046a18dc14) | Jul 03, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [9a35c1249b](https://linux-hardware.org/?probe=9a35c1249b) | Jun 30, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c8f0217b26](https://linux-hardware.org/?probe=c8f0217b26) | Jun 29, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d3af5b938a](https://linux-hardware.org/?probe=d3af5b938a) | Jun 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [4b202c1285](https://linux-hardware.org/?probe=4b202c1285) | Jun 22, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [7b8cc6556b](https://linux-hardware.org/?probe=7b8cc6556b) | Jun 12, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b85af00b16](https://linux-hardware.org/?probe=b85af00b16) | May 18, 2022 |
| Dell          | Latitude 5580               | Notebook    | [18cefe0718](https://linux-hardware.org/?probe=18cefe0718) | May 17, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [c1353ba170](https://linux-hardware.org/?probe=c1353ba170) | May 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [71e0ef1fc9](https://linux-hardware.org/?probe=71e0ef1fc9) | May 07, 2022 |
| HP            | 240 G3                      | Notebook    | [7062083e69](https://linux-hardware.org/?probe=7062083e69) | May 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3055b0e95f](https://linux-hardware.org/?probe=3055b0e95f) | May 05, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e993bc145](https://linux-hardware.org/?probe=6e993bc145) | Apr 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [5db5bac582](https://linux-hardware.org/?probe=5db5bac582) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [cb949f34eb](https://linux-hardware.org/?probe=cb949f34eb) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd9e66788c](https://linux-hardware.org/?probe=fd9e66788c) | Mar 17, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [d7a873bf3d](https://linux-hardware.org/?probe=d7a873bf3d) | Feb 27, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [87f30f494f](https://linux-hardware.org/?probe=87f30f494f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [62c028a881](https://linux-hardware.org/?probe=62c028a881) | Feb 16, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [42647bc4b3](https://linux-hardware.org/?probe=42647bc4b3) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [6f8e63bfb0](https://linux-hardware.org/?probe=6f8e63bfb0) | Feb 11, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [8e73dc39ab](https://linux-hardware.org/?probe=8e73dc39ab) | Feb 09, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [42e37d6172](https://linux-hardware.org/?probe=42e37d6172) | Feb 07, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [47c47a0121](https://linux-hardware.org/?probe=47c47a0121) | Feb 02, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [d7431ab69e](https://linux-hardware.org/?probe=d7431ab69e) | Jan 31, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [76d17811e3](https://linux-hardware.org/?probe=76d17811e3) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [caca9680a9](https://linux-hardware.org/?probe=caca9680a9) | Jan 25, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1e89749691](https://linux-hardware.org/?probe=1e89749691) | Jan 22, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [ac35b74090](https://linux-hardware.org/?probe=ac35b74090) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [2fb0411785](https://linux-hardware.org/?probe=2fb0411785) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [692274162f](https://linux-hardware.org/?probe=692274162f) | Jan 04, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e6a4a21d5c](https://linux-hardware.org/?probe=e6a4a21d5c) | Jan 02, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [209e15690e](https://linux-hardware.org/?probe=209e15690e) | Dec 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [00696e3398](https://linux-hardware.org/?probe=00696e3398) | Dec 28, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [7280895518](https://linux-hardware.org/?probe=7280895518) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [56d5bb8659](https://linux-hardware.org/?probe=56d5bb8659) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [6ab6a89db8](https://linux-hardware.org/?probe=6ab6a89db8) | Dec 12, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3cd505591d](https://linux-hardware.org/?probe=3cd505591d) | Dec 11, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| ASUSTek       | P453UJ                      | Notebook    | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [aa0a0e67b3](https://linux-hardware.org/?probe=aa0a0e67b3) | Nov 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [9bffff74e0](https://linux-hardware.org/?probe=9bffff74e0) | Nov 26, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [09b0e5058d](https://linux-hardware.org/?probe=09b0e5058d) | Nov 23, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [623b2b0ba9](https://linux-hardware.org/?probe=623b2b0ba9) | Nov 19, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [47d816d00f](https://linux-hardware.org/?probe=47d816d00f) | Nov 12, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [6d2cade66c](https://linux-hardware.org/?probe=6d2cade66c) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [312e04d7f9](https://linux-hardware.org/?probe=312e04d7f9) | Nov 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f1f7ca30e5](https://linux-hardware.org/?probe=f1f7ca30e5) | Nov 05, 2021 |
| ASUSTek       | X442UAR                     | Notebook    | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| OEM           | Intel H81                   | Desktop     | [a4e298caf1](https://linux-hardware.org/?probe=a4e298caf1) | Nov 02, 2021 |
| OEM           | Intel H81                   | Desktop     | [50758cfaf3](https://linux-hardware.org/?probe=50758cfaf3) | Oct 26, 2021 |
| OEM           | Intel H81                   | Desktop     | [e997f638bc](https://linux-hardware.org/?probe=e997f638bc) | Oct 26, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [356632b328](https://linux-hardware.org/?probe=356632b328) | Oct 19, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [d377aa2b23](https://linux-hardware.org/?probe=d377aa2b23) | Oct 17, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [7447071c00](https://linux-hardware.org/?probe=7447071c00) | Oct 16, 2021 |
| MSI           | Boston                      | Desktop     | [77d385bc09](https://linux-hardware.org/?probe=77d385bc09) | Oct 13, 2021 |
| MSI           | Boston                      | Desktop     | [14528f628a](https://linux-hardware.org/?probe=14528f628a) | Oct 13, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [0bf0387391](https://linux-hardware.org/?probe=0bf0387391) | Oct 07, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Dell          | Latitude E7250              | Notebook    | [275b9204f5](https://linux-hardware.org/?probe=275b9204f5) | Sep 13, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [752964e357](https://linux-hardware.org/?probe=752964e357) | Sep 05, 2021 |
| ASUSTek       | X456UQ                      | Notebook    | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7a654e5473](https://linux-hardware.org/?probe=7a654e5473) | Aug 28, 2021 |
| Acer          | Aspire 4349                 | Notebook    | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| Gigabyte      | B250M-Gaming5-CF            | Desktop     | [c34514576a](https://linux-hardware.org/?probe=c34514576a) | Aug 17, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [460fc8dfd4](https://linux-hardware.org/?probe=460fc8dfd4) | Aug 08, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [48853e253b](https://linux-hardware.org/?probe=48853e253b) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [c22e4ce5b4](https://linux-hardware.org/?probe=c22e4ce5b4) | Jul 29, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| ASUSTek       | X550JK                      | Notebook    | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6dea4c88d](https://linux-hardware.org/?probe=c6dea4c88d) | Jul 19, 2021 |
| Biostar       | TZ68K+                      | Desktop     | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [406cb898f1](https://linux-hardware.org/?probe=406cb898f1) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [1927d0abfe](https://linux-hardware.org/?probe=1927d0abfe) | Jun 13, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [23e735bb8f](https://linux-hardware.org/?probe=23e735bb8f) | Jun 08, 2021 |
| Dell          | 0VHWTR A02                  | Desktop     | [ec7174828a](https://linux-hardware.org/?probe=ec7174828a) | Jun 04, 2021 |
| ASUSTek       | UX310UAK                    | Notebook    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0226c84811](https://linux-hardware.org/?probe=0226c84811) | May 25, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [b2c4e6f3a5](https://linux-hardware.org/?probe=b2c4e6f3a5) | May 25, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [b34d6d63d9](https://linux-hardware.org/?probe=b34d6d63d9) | May 22, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [4d2529b647](https://linux-hardware.org/?probe=4d2529b647) | May 22, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [aba051d387](https://linux-hardware.org/?probe=aba051d387) | May 15, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fa9f8b7f7e](https://linux-hardware.org/?probe=fa9f8b7f7e) | May 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db1a234412](https://linux-hardware.org/?probe=db1a234412) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [1254eab2b7](https://linux-hardware.org/?probe=1254eab2b7) | May 04, 2021 |
| HP            | 15                          | Notebook    | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| MSI           | Summit B14 A11MOT           | Notebook    | [9bdd91f198](https://linux-hardware.org/?probe=9bdd91f198) | May 02, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [dbcbb68258](https://linux-hardware.org/?probe=dbcbb68258) | Apr 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [b2600d2372](https://linux-hardware.org/?probe=b2600d2372) | Apr 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [2ccfcf6a1b](https://linux-hardware.org/?probe=2ccfcf6a1b) | Mar 22, 2021 |
| HP            | 15                          | Notebook    | [860412bddc](https://linux-hardware.org/?probe=860412bddc) | Mar 20, 2021 |
| HP            | 15                          | Notebook    | [62447250f9](https://linux-hardware.org/?probe=62447250f9) | Mar 17, 2021 |
| ASUSTek       | H110M-CS                    | Desktop     | [ac52c3630c](https://linux-hardware.org/?probe=ac52c3630c) | Mar 12, 2021 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [4ee1271923](https://linux-hardware.org/?probe=4ee1271923) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [6343267ab7](https://linux-hardware.org/?probe=6343267ab7) | Mar 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [a8091a8c28](https://linux-hardware.org/?probe=a8091a8c28) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8f8fe2c911](https://linux-hardware.org/?probe=8f8fe2c911) | Mar 06, 2021 |
| ASUSTek       | X411UNV                     | Notebook    | [009f3bb5e5](https://linux-hardware.org/?probe=009f3bb5e5) | Feb 27, 2021 |
| HP            | 15                          | Notebook    | [e74fa488e9](https://linux-hardware.org/?probe=e74fa488e9) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [8efc8caada](https://linux-hardware.org/?probe=8efc8caada) | Feb 27, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [b414109f66](https://linux-hardware.org/?probe=b414109f66) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [08a1160725](https://linux-hardware.org/?probe=08a1160725) | Feb 07, 2021 |
| HP            | Notebook                    | Notebook    | [df39c8aaf8](https://linux-hardware.org/?probe=df39c8aaf8) | Feb 02, 2021 |
| ASUSTek       | X45C                        | Notebook    | [349beec2d5](https://linux-hardware.org/?probe=349beec2d5) | Jan 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [474d61d1a7](https://linux-hardware.org/?probe=474d61d1a7) | Jan 27, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450 20BUS2021M    | Notebook    | [60929bb3d1](https://linux-hardware.org/?probe=60929bb3d1) | Jan 21, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [32878b3dae](https://linux-hardware.org/?probe=32878b3dae) | Jan 20, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [03b73f8223](https://linux-hardware.org/?probe=03b73f8223) | Jan 20, 2021 |
| HP            | Notebook                    | Notebook    | [d14d8fe5db](https://linux-hardware.org/?probe=d14d8fe5db) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [e053ef39b6](https://linux-hardware.org/?probe=e053ef39b6) | Jan 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5ee0809420](https://linux-hardware.org/?probe=5ee0809420) | Jan 16, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4c2ddc3c14](https://linux-hardware.org/?probe=4c2ddc3c14) | Jan 10, 2021 |
| HP            | 15                          | Notebook    | [1b3597829c](https://linux-hardware.org/?probe=1b3597829c) | Jan 05, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [150aed5937](https://linux-hardware.org/?probe=150aed5937) | Dec 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [f3aaccf16d](https://linux-hardware.org/?probe=f3aaccf16d) | Dec 19, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [eff007611b](https://linux-hardware.org/?probe=eff007611b) | Dec 16, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [1eec63b277](https://linux-hardware.org/?probe=1eec63b277) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| MSI           | GS63 7RD                    | Notebook    | [51929f5d16](https://linux-hardware.org/?probe=51929f5d16) | Dec 05, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [983f59c8ba](https://linux-hardware.org/?probe=983f59c8ba) | Nov 17, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [4d0297d500](https://linux-hardware.org/?probe=4d0297d500) | Nov 15, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [2898db77af](https://linux-hardware.org/?probe=2898db77af) | Nov 14, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [399693b152](https://linux-hardware.org/?probe=399693b152) | Nov 04, 2020 |
| HP            | 15                          | Notebook    | [751dbba280](https://linux-hardware.org/?probe=751dbba280) | Nov 04, 2020 |
| Unknown       | Unknown                     | Desktop     | [49351fb74d](https://linux-hardware.org/?probe=49351fb74d) | Nov 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [a5450c668e](https://linux-hardware.org/?probe=a5450c668e) | Oct 30, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e48c5dac7](https://linux-hardware.org/?probe=7e48c5dac7) | Oct 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [20da8831d7](https://linux-hardware.org/?probe=20da8831d7) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [6abbe0be7c](https://linux-hardware.org/?probe=6abbe0be7c) | Oct 29, 2020 |
| Notebook      | DCL C483                    | Notebook    | [ed2bb10c86](https://linux-hardware.org/?probe=ed2bb10c86) | Oct 29, 2020 |
| ASUSTek       | H110M-CS                    | Desktop     | [4bc7a25c4b](https://linux-hardware.org/?probe=4bc7a25c4b) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [7a6ee90819](https://linux-hardware.org/?probe=7a6ee90819) | Oct 29, 2020 |
| HP            | ENVY Sleekbook 4            | Notebook    | [b2377a6388](https://linux-hardware.org/?probe=b2377a6388) | Oct 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [1f7d96b34a](https://linux-hardware.org/?probe=1f7d96b34a) | Oct 27, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [76e61701fa](https://linux-hardware.org/?probe=76e61701fa) | Oct 24, 2020 |
| ASUSTek       | P453UA                      | Notebook    | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [218b3ce742](https://linux-hardware.org/?probe=218b3ce742) | Oct 12, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [da1765fe36](https://linux-hardware.org/?probe=da1765fe36) | Oct 11, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [a9c53146fc](https://linux-hardware.org/?probe=a9c53146fc) | Oct 10, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [be8091856c](https://linux-hardware.org/?probe=be8091856c) | Oct 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [a6f1865423](https://linux-hardware.org/?probe=a6f1865423) | Oct 07, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [ae7fe5907d](https://linux-hardware.org/?probe=ae7fe5907d) | Sep 27, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [ed0ef70a05](https://linux-hardware.org/?probe=ed0ef70a05) | Sep 19, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [871d27c2e8](https://linux-hardware.org/?probe=871d27c2e8) | Sep 18, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [3f442c236c](https://linux-hardware.org/?probe=3f442c236c) | Sep 18, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [d7b1ce1a01](https://linux-hardware.org/?probe=d7b1ce1a01) | Sep 15, 2020 |
| Notebook      | N2x0LU                      | Notebook    | [86354a1c26](https://linux-hardware.org/?probe=86354a1c26) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| ASRock        | Z77 Pro3                    | Desktop     | [8d6db6e2d3](https://linux-hardware.org/?probe=8d6db6e2d3) | Sep 09, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [22629ba9b2](https://linux-hardware.org/?probe=22629ba9b2) | Sep 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [43ddcf3c95](https://linux-hardware.org/?probe=43ddcf3c95) | Sep 06, 2020 |
| Unknown       | Unknown                     | Phone       | [d4a5776865](https://linux-hardware.org/?probe=d4a5776865) | Sep 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [38548d7877](https://linux-hardware.org/?probe=38548d7877) | Sep 01, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [3edf866f94](https://linux-hardware.org/?probe=3edf866f94) | Aug 22, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [3a9beeb9f4](https://linux-hardware.org/?probe=3a9beeb9f4) | Aug 16, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [3c3b21f81b](https://linux-hardware.org/?probe=3c3b21f81b) | Aug 15, 2020 |
| HP            | 14                          | Notebook    | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| SYS           | H310CH5-TI2                 | Desktop     | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| HP            | EliteBook 850 G2            | Notebook    | [1c81c3c24d](https://linux-hardware.org/?probe=1c81c3c24d) | Jul 30, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [27a9cd08a6](https://linux-hardware.org/?probe=27a9cd08a6) | Jul 26, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f1ef1518c4](https://linux-hardware.org/?probe=f1ef1518c4) | Jul 25, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [bf80f266b6](https://linux-hardware.org/?probe=bf80f266b6) | Jul 25, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [9c3656a710](https://linux-hardware.org/?probe=9c3656a710) | Jul 24, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3c50b289eb](https://linux-hardware.org/?probe=3c50b289eb) | Jul 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e800855127](https://linux-hardware.org/?probe=e800855127) | Jul 21, 2020 |
| Dell          | Latitude E7470              | Notebook    | [74e59971a2](https://linux-hardware.org/?probe=74e59971a2) | Jul 09, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [eb79a1863c](https://linux-hardware.org/?probe=eb79a1863c) | Jul 08, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [374493e07f](https://linux-hardware.org/?probe=374493e07f) | Jul 08, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [04f260c99a](https://linux-hardware.org/?probe=04f260c99a) | Jul 06, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [aa5a987949](https://linux-hardware.org/?probe=aa5a987949) | Jul 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [e8be3d4a45](https://linux-hardware.org/?probe=e8be3d4a45) | Jul 02, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [d59cf3e39f](https://linux-hardware.org/?probe=d59cf3e39f) | Jun 21, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [bedb334316](https://linux-hardware.org/?probe=bedb334316) | Jun 11, 2020 |
| Gigabyte      | B75MS                       | Desktop     | [116d7e4473](https://linux-hardware.org/?probe=116d7e4473) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [0690307575](https://linux-hardware.org/?probe=0690307575) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [2d68573dcb](https://linux-hardware.org/?probe=2d68573dcb) | Jun 04, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ebee7f8d](https://linux-hardware.org/?probe=24ebee7f8d) | Jun 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e10a133997](https://linux-hardware.org/?probe=e10a133997) | Jun 02, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [7b57cf3668](https://linux-hardware.org/?probe=7b57cf3668) | May 30, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [821df8e348](https://linux-hardware.org/?probe=821df8e348) | May 25, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [6118e39327](https://linux-hardware.org/?probe=6118e39327) | May 25, 2020 |
| HP            | Notebook                    | Notebook    | [024a28eb0b](https://linux-hardware.org/?probe=024a28eb0b) | May 23, 2020 |
| Dell          | Latitude E7450              | Notebook    | [f3e9ca7a40](https://linux-hardware.org/?probe=f3e9ca7a40) | May 21, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | Notebook    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e6818ffd7d](https://linux-hardware.org/?probe=e6818ffd7d) | May 21, 2020 |
| Notebook      | W9x0LU                      | Notebook    | [c7455fcb18](https://linux-hardware.org/?probe=c7455fcb18) | May 17, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [5d81beb457](https://linux-hardware.org/?probe=5d81beb457) | May 17, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [7b1a18ebf9](https://linux-hardware.org/?probe=7b1a18ebf9) | May 09, 2020 |
| ASUSTek       | X556URK                     | Notebook    | [63c6b5a357](https://linux-hardware.org/?probe=63c6b5a357) | May 08, 2020 |
| Foxconn       | 17A0                        | Desktop     | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Notebook      | N750BU                      | Notebook    | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [de6fa960ad](https://linux-hardware.org/?probe=de6fa960ad) | Apr 23, 2020 |
| I-Life Dig... | ZED_AIR_PLUS                | Convertible | [b1a911e13e](https://linux-hardware.org/?probe=b1a911e13e) | Mar 27, 2020 |
| MSI           | H61M-P31/W8                 | Desktop     | [26d8323c91](https://linux-hardware.org/?probe=26d8323c91) | Mar 25, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [baa90e0762](https://linux-hardware.org/?probe=baa90e0762) | Mar 22, 2020 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [34ced022e3](https://linux-hardware.org/?probe=34ced022e3) | Feb 29, 2020 |
| HP            | Mini 210-4000               | Notebook    | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [729f8e494d](https://linux-hardware.org/?probe=729f8e494d) | Feb 14, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [357823f120](https://linux-hardware.org/?probe=357823f120) | Feb 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e9a4da7f1c](https://linux-hardware.org/?probe=e9a4da7f1c) | Jan 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [4fad937155](https://linux-hardware.org/?probe=4fad937155) | Jan 10, 2020 |
| Lenovo        | ThinkPad L380 20M6S22500    | Notebook    | [15c43def70](https://linux-hardware.org/?probe=15c43def70) | Jan 09, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [9d4e0d1911](https://linux-hardware.org/?probe=9d4e0d1911) | Jan 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [2d0bca85ea](https://linux-hardware.org/?probe=2d0bca85ea) | Dec 29, 2019 |
| Gigabyte      | B85M-D3H                    | Desktop     | [753205d5df](https://linux-hardware.org/?probe=753205d5df) | Dec 27, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [d85b25cd22](https://linux-hardware.org/?probe=d85b25cd22) | Dec 24, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [30c00cb837](https://linux-hardware.org/?probe=30c00cb837) | Dec 14, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [e004d9f500](https://linux-hardware.org/?probe=e004d9f500) | Dec 14, 2019 |
| ASUSTek       | E202SA                      | Notebook    | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [44d09b2105](https://linux-hardware.org/?probe=44d09b2105) | Nov 19, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [3fc910f23c](https://linux-hardware.org/?probe=3fc910f23c) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| MSI           | PH67A-C43                   | Desktop     | [b472118c5a](https://linux-hardware.org/?probe=b472118c5a) | Oct 29, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [73a0de63c0](https://linux-hardware.org/?probe=73a0de63c0) | Sep 27, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4299e1c036](https://linux-hardware.org/?probe=4299e1c036) | Sep 27, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [671ea53b31](https://linux-hardware.org/?probe=671ea53b31) | Sep 22, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [53b4bf1914](https://linux-hardware.org/?probe=53b4bf1914) | Sep 22, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [6022620aee](https://linux-hardware.org/?probe=6022620aee) | Sep 17, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [d0632368ab](https://linux-hardware.org/?probe=d0632368ab) | Sep 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [ede7f2c199](https://linux-hardware.org/?probe=ede7f2c199) | Aug 30, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e3c13fc2d8](https://linux-hardware.org/?probe=e3c13fc2d8) | Aug 20, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d0d6cd20b1](https://linux-hardware.org/?probe=d0d6cd20b1) | Jul 26, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [f9b65f1415](https://linux-hardware.org/?probe=f9b65f1415) | Jul 14, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a6f5bc1b0f](https://linux-hardware.org/?probe=a6f5bc1b0f) | Jul 13, 2019 |
| HP            | Notebook                    | Notebook    | [2ce0b2ff35](https://linux-hardware.org/?probe=2ce0b2ff35) | Jul 04, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [298e510c05](https://linux-hardware.org/?probe=298e510c05) | Jun 22, 2019 |
| Lenovo        | ThinkPad X230 2324F51       | Notebook    | [9291e8f5f3](https://linux-hardware.org/?probe=9291e8f5f3) | Jun 22, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [ee5c9fcc02](https://linux-hardware.org/?probe=ee5c9fcc02) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [424ee39d57](https://linux-hardware.org/?probe=424ee39d57) | Jun 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [37a334e523](https://linux-hardware.org/?probe=37a334e523) | Jun 02, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [cb301afe49](https://linux-hardware.org/?probe=cb301afe49) | Jun 02, 2019 |
| Lenovo        | S10-3                       | Notebook    | [09f132c2fa](https://linux-hardware.org/?probe=09f132c2fa) | May 27, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [24c1251a9a](https://linux-hardware.org/?probe=24c1251a9a) | May 09, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [0f42a3ea73](https://linux-hardware.org/?probe=0f42a3ea73) | May 09, 2019 |
| Daffodil C... | DCL S4                      | Notebook    | [291cd2445c](https://linux-hardware.org/?probe=291cd2445c) | May 08, 2019 |
| HP            | ProBook 4540s               | Notebook    | [a8b0fbe3a8](https://linux-hardware.org/?probe=a8b0fbe3a8) | Apr 22, 2019 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [83303ad448](https://linux-hardware.org/?probe=83303ad448) | Apr 07, 2019 |
| Intel         | Unknown                     | Desktop     | [6abdeb3169](https://linux-hardware.org/?probe=6abdeb3169) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [d27842b77f](https://linux-hardware.org/?probe=d27842b77f) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [1c484063a6](https://linux-hardware.org/?probe=1c484063a6) | Mar 09, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| MSI           | P55A-G55                    | Desktop     | [8bc6ce2174](https://linux-hardware.org/?probe=8bc6ce2174) | Dec 08, 2018 |
| MSI           | P55A-G55                    | Desktop     | [24654f4990](https://linux-hardware.org/?probe=24654f4990) | Dec 07, 2018 |
| Gigabyte      | P55-USB3                    | Desktop     | [3cf949c024](https://linux-hardware.org/?probe=3cf949c024) | Jul 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 47        | 16.15%  |
| Ubuntu 22.04                 | 13        | 4.47%   |
| Arch                         | 12        | 4.12%   |
| Ubuntu 18.04                 | 11        | 3.78%   |
| ArcoLinux Rolling            | 10        | 3.44%   |
| Manjaro                      | 9         | 3.09%   |
| Ubuntu 19.10                 | 8         | 2.75%   |
| KDE neon 20.04               | 7         | 2.41%   |
| Zorin 16                     | 6         | 2.06%   |
| Pop!_OS 22.04                | 6         | 2.06%   |
| Debian 11                    | 6         | 2.06%   |
| Arch Rolling                 | 6         | 2.06%   |
| OpenMandriva 4.2             | 5         | 1.72%   |
| Fedora 33                    | 5         | 1.72%   |
| Zorin 15                     | 4         | 1.37%   |
| Manjaro 20.0.1               | 4         | 1.37%   |
| Linux Mint 20.2              | 4         | 1.37%   |
| Ubuntu 22.10                 | 3         | 1.03%   |
| Ubuntu 19.04                 | 3         | 1.03%   |
| Pop!_OS 21.10                | 3         | 1.03%   |
| Pop!_OS 21.04                | 3         | 1.03%   |
| Manjaro 20.1.2               | 3         | 1.03%   |
| Linux Mint 20.1              | 3         | 1.03%   |
| Linux Mint 20                | 3         | 1.03%   |
| Kubuntu 20.04                | 3         | 1.03%   |
| EndeavourOS Rolling          | 3         | 1.03%   |
| Ubuntu 21.04                 | 2         | 0.69%   |
| Ubuntu 20.10                 | 2         | 0.69%   |
| Ubuntu 18.10                 | 2         | 0.69%   |
| Pop!_OS 20.10                | 2         | 0.69%   |
| Parrot 5.1                   | 2         | 0.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.69%   |
| OpenMandriva 4.90            | 2         | 0.69%   |
| OpenMandriva 4.3             | 2         | 0.69%   |
| MX 21                        | 2         | 0.69%   |
| Manjaro 21.2.6               | 2         | 0.69%   |
| Manjaro 21.0.3               | 2         | 0.69%   |
| Manjaro 18.0.4               | 2         | 0.69%   |
| LMDE 4                       | 2         | 0.69%   |
| Linux Mint 21                | 2         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 91        | 33.83%  |
| Manjaro      | 27        | 10.04%  |
| Arch         | 17        | 6.32%   |
| Linux Mint   | 15        | 5.58%   |
| Pop!_OS      | 13        | 4.83%   |
| Fedora       | 12        | 4.46%   |
| Zorin        | 10        | 3.72%   |
| ArcoLinux    | 10        | 3.72%   |
| OpenMandriva | 9         | 3.35%   |
| Kubuntu      | 8         | 2.97%   |
| KDE neon     | 8         | 2.97%   |
| Debian       | 7         | 2.6%    |
| Endless      | 6         | 2.23%   |
| Parrot       | 5         | 1.86%   |
| Kali         | 4         | 1.49%   |
| EndeavourOS  | 4         | 1.49%   |
| openSUSE     | 2         | 0.74%   |
| MX           | 2         | 0.74%   |
| LMDE         | 2         | 0.74%   |
| Deepin       | 2         | 0.74%   |
| CentOS       | 2         | 0.74%   |
| BlackPanther | 2         | 0.74%   |
| Void Linux   | 1         | 0.37%   |
| Ubuntu Unity | 1         | 0.37%   |
| Ubuntu MATE  | 1         | 0.37%   |
| ROSA         | 1         | 0.37%   |
| Pragma       | 1         | 0.37%   |
| Gentoo       | 1         | 0.37%   |
| Garuda Linux | 1         | 0.37%   |
| Elementary   | 1         | 0.37%   |
| Clear Linux  | 1         | 0.37%   |
| Artix        | 1         | 0.37%   |
| Android      | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 8         | 2.52%   |
| 5.4.0-52-generic         | 6         | 1.89%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.57%   |
| 5.13.0-28-generic        | 4         | 1.26%   |
| 5.9.16-1-MANJARO         | 3         | 0.94%   |
| 5.8.0-55-generic         | 3         | 0.94%   |
| 5.8.0-41-generic         | 3         | 0.94%   |
| 5.6.11-1-MANJARO         | 3         | 0.94%   |
| 5.4.0-53-generic         | 3         | 0.94%   |
| 5.4.0-40-generic         | 3         | 0.94%   |
| 5.4.0-29-generic         | 3         | 0.94%   |
| 5.15.0-57-generic        | 3         | 0.94%   |
| 5.15.0-56-generic        | 3         | 0.94%   |
| 5.15.0-48-generic        | 3         | 0.94%   |
| 5.11.0-37-generic        | 3         | 0.94%   |
| 5.11.0-16-generic        | 3         | 0.94%   |
| 6.1.12-arch1-1           | 2         | 0.63%   |
| 6.0.9-zen1-1-zen         | 2         | 0.63%   |
| 6.0.0-kali6-amd64        | 2         | 0.63%   |
| 5.8.16-2-MANJARO         | 2         | 0.63%   |
| 5.8.0-50-generic         | 2         | 0.63%   |
| 5.8.0-44-generic         | 2         | 0.63%   |
| 5.8.0-38-generic         | 2         | 0.63%   |
| 5.8.0-14-generic         | 2         | 0.63%   |
| 5.7.19-2-MANJARO         | 2         | 0.63%   |
| 5.4.8-arch1-1            | 2         | 0.63%   |
| 5.4.0-90-generic         | 2         | 0.63%   |
| 5.4.0-73-generic         | 2         | 0.63%   |
| 5.4.0-47-generic         | 2         | 0.63%   |
| 5.4.0-26-generic         | 2         | 0.63%   |
| 5.4.0-19-generic         | 2         | 0.63%   |
| 5.3.0-40-generic         | 2         | 0.63%   |
| 5.3.0-24-generic         | 2         | 0.63%   |
| 5.3.0-23-generic         | 2         | 0.63%   |
| 5.3.0-18-generic         | 2         | 0.63%   |
| 5.19.0-kali2-amd64       | 2         | 0.63%   |
| 5.19.0-76051900-generic  | 2         | 0.63%   |
| 5.19.0-29-generic        | 2         | 0.63%   |
| 5.18.12-desktop-3omv4090 | 2         | 0.63%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 40        | 13.25%  |
| 5.15.0  | 21        | 6.95%   |
| 5.11.0  | 19        | 6.29%   |
| 5.8.0   | 18        | 5.96%   |
| 5.13.0  | 17        | 5.63%   |
| 5.3.0   | 13        | 4.3%    |
| 5.10.0  | 9         | 2.98%   |
| 5.19.0  | 8         | 2.65%   |
| 5.0.0   | 7         | 2.32%   |
| 4.18.0  | 7         | 2.32%   |
| 4.15.0  | 7         | 2.32%   |
| 6.0.0   | 5         | 1.66%   |
| 5.10.14 | 5         | 1.66%   |
| 5.9.16  | 4         | 1.32%   |
| 5.8.16  | 4         | 1.32%   |
| 4.19.0  | 4         | 1.32%   |
| 6.0.12  | 3         | 0.99%   |
| 5.6.11  | 3         | 0.99%   |
| 5.18.12 | 3         | 0.99%   |
| 6.1.8   | 2         | 0.66%   |
| 6.1.12  | 2         | 0.66%   |
| 6.0.9   | 2         | 0.66%   |
| 5.7.19  | 2         | 0.66%   |
| 5.4.8   | 2         | 0.66%   |
| 5.17.0  | 2         | 0.66%   |
| 5.16.7  | 2         | 0.66%   |
| 5.16.15 | 2         | 0.66%   |
| 5.16.11 | 2         | 0.66%   |
| 5.15.7  | 2         | 0.66%   |
| 5.15.5  | 2         | 0.66%   |
| 5.15.13 | 2         | 0.66%   |
| 5.11.6  | 2         | 0.66%   |
| 5.10.52 | 2         | 0.66%   |
| 6.1.9   | 1         | 0.33%   |
| 6.1.7   | 1         | 0.33%   |
| 6.0.6   | 1         | 0.33%   |
| 6.0.2   | 1         | 0.33%   |
| 6.0.10  | 1         | 0.33%   |
| 5.9.11  | 1         | 0.33%   |
| 5.8.6   | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 16.1%   |
| 5.15    | 38        | 13.01%  |
| 5.8     | 25        | 8.56%   |
| 5.11    | 24        | 8.22%   |
| 5.10    | 22        | 7.53%   |
| 5.13    | 19        | 6.51%   |
| 5.3     | 13        | 4.45%   |
| 6.0     | 12        | 4.11%   |
| 5.16    | 11        | 3.77%   |
| 5.19    | 10        | 3.42%   |
| 4.18    | 8         | 2.74%   |
| 5.18    | 7         | 2.4%    |
| 5.0     | 7         | 2.4%    |
| 4.15    | 7         | 2.4%    |
| 6.1     | 6         | 2.05%   |
| 5.9     | 5         | 1.71%   |
| 5.7     | 5         | 1.71%   |
| 5.6     | 5         | 1.71%   |
| 5.17    | 5         | 1.71%   |
| 4.19    | 5         | 1.71%   |
| 5.14    | 3         | 1.03%   |
| 5.12    | 2         | 0.68%   |
| 5.1     | 2         | 0.68%   |
| 4.9     | 1         | 0.34%   |
| 4.4     | 1         | 0.34%   |
| 4.13    | 1         | 0.34%   |
| 3.18    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 251       | 97.29%  |
| i686    | 4         | 1.55%   |
| aarch64 | 3         | 1.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 130       | 47.97%  |
| KDE5            | 55        | 20.3%   |
| Unknown         | 30        | 11.07%  |
| X-Cinnamon      | 15        | 5.54%   |
| XFCE            | 14        | 5.17%   |
| MATE            | 6         | 2.21%   |
| awesome         | 5         | 1.85%   |
| KDE             | 4         | 1.48%   |
| i3-with-shmlog  | 2         | 0.74%   |
| Deepin          | 2         | 0.74%   |
| Unity           | 1         | 0.37%   |
| Pantheon        | 1         | 0.37%   |
| LXDE            | 1         | 0.37%   |
| i3              | 1         | 0.37%   |
| GNOME Flashback | 1         | 0.37%   |
| DWM             | 1         | 0.37%   |
| Cinnamon        | 1         | 0.37%   |
| bspwm           | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 215       | 79.34%  |
| Wayland | 35        | 12.92%  |
| Unknown | 17        | 6.27%   |
| Tty     | 4         | 1.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 135       | 50%     |
| GDM     | 40        | 14.81%  |
| SDDM    | 38        | 14.07%  |
| GDM3    | 26        | 9.63%   |
| LightDM | 22        | 8.15%   |
| TDM     | 9         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 213       | 81.3%   |
| Unknown | 30        | 11.45%  |
| en_GB   | 8         | 3.05%   |
| C       | 6         | 2.29%   |
| en_IE   | 1         | 0.38%   |
| en_EN   | 1         | 0.38%   |
| en_CA   | 1         | 0.38%   |
| en_AG   | 1         | 0.38%   |
| Default | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 135       | 50%     |
| EFI  | 135       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 212       | 79.7%   |
| Overlay | 23        | 8.65%   |
| Btrfs   | 22        | 8.27%   |
| Unknown | 5         | 1.88%   |
| Xfs     | 3         | 1.13%   |
| Zfs     | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 145       | 53.9%   |
| GPT     | 98        | 36.43%  |
| MBR     | 26        | 9.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 220       | 83.33%  |
| Yes       | 44        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 56.98%  |
| Yes       | 114       | 43.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 58        | 22.48%  |
| Hewlett-Packard             | 47        | 18.22%  |
| MSI                         | 25        | 9.69%   |
| Dell                        | 24        | 9.3%    |
| Gigabyte Technology         | 23        | 8.91%   |
| Lenovo                      | 21        | 8.14%   |
| Acer                        | 18        | 6.98%   |
| Unknown                     | 7         | 2.71%   |
| ASRock                      | 6         | 2.33%   |
| Intel                       | 5         | 1.94%   |
| Notebook                    | 4         | 1.55%   |
| OEM                         | 3         | 1.16%   |
| Foxconn                     | 3         | 1.16%   |
| Biostar                     | 3         | 1.16%   |
| Toshiba                     | 2         | 0.78%   |
| Raspberry Pi Foundation     | 2         | 0.78%   |
| Timi                        | 1         | 0.39%   |
| SYS                         | 1         | 0.39%   |
| Samsung Electronics         | 1         | 0.39%   |
| I-Life Digital Technologies | 1         | 0.39%   |
| Fujitsu                     | 1         | 0.39%   |
| Daffodil Computers          | 1         | 0.39%   |
| Apple                       | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 9         | 3.49%   |
| MSI MS-7C52                                           | 6         | 2.33%   |
| HP ProBook 450 G4                                     | 5         | 1.94%   |
| HP Notebook                                           | 3         | 1.16%   |
| ASUS All Series                                       | 3         | 1.16%   |
| OEM Intel H81                                         | 2         | 0.78%   |
| MSI MS-7B89                                           | 2         | 0.78%   |
| MSI MS-7788                                           | 2         | 0.78%   |
| MSI MS-7668                                           | 2         | 0.78%   |
| Intel DG41RQ AAE54511-203                             | 2         | 0.78%   |
| HP ProBook 450 G2                                     | 2         | 0.78%   |
| HP ProBook 440 G8 Notebook PC                         | 2         | 0.78%   |
| HP EliteBook 840 G3                                   | 2         | 0.78%   |
| HP 15                                                 | 2         | 0.78%   |
| HP 14                                                 | 2         | 0.78%   |
| Gigabyte B250M-HD3                                    | 2         | 0.78%   |
| Dell Inspiron 3442                                    | 2         | 0.78%   |
| ASUS X510UQ                                           | 2         | 0.78%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 0.78%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 2         | 0.78%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 0.78%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 0.78%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 0.78%   |
| ASUS P453UA                                           | 2         | 0.78%   |
| Acer Nitro AN515-43                                   | 2         | 0.78%   |
| Toshiba Satellite Pro L510                            | 1         | 0.39%   |
| Toshiba Satellite L645                                | 1         | 0.39%   |
| Timi Mi NoteBook Pro                                  | 1         | 0.39%   |
| SYS H310CH5-TI2                                       | 1         | 0.39%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.39%   |
| RPi Raspberry Pi 4 Model B Rev 1.5                    | 1         | 0.39%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 1         | 0.39%   |
| Notebook W9x0LU                                       | 1         | 0.39%   |
| Notebook N750BU                                       | 1         | 0.39%   |
| Notebook N2x0LU                                       | 1         | 0.39%   |
| Notebook DCL C483                                     | 1         | 0.39%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.39%   |
| MSI MS-7C91                                           | 1         | 0.39%   |
| MSI MS-7C88                                           | 1         | 0.39%   |
| MSI MS-7C08                                           | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 21        | 8.14%   |
| HP ProBook         | 17        | 6.59%   |
| Acer Aspire        | 14        | 5.43%   |
| Dell Inspiron      | 11        | 4.26%   |
| Lenovo IdeaPad     | 10        | 3.88%   |
| Unknown            | 9         | 3.49%   |
| Dell Latitude      | 8         | 3.1%    |
| Lenovo ThinkPad    | 7         | 2.71%   |
| HP EliteBook       | 7         | 2.71%   |
| MSI MS-7C52        | 6         | 2.33%   |
| ASUS TUF           | 4         | 1.55%   |
| HP Pavilion        | 3         | 1.16%   |
| HP Notebook        | 3         | 1.16%   |
| HP ENVY            | 3         | 1.16%   |
| HP 15              | 3         | 1.16%   |
| ASUS All           | 3         | 1.16%   |
| Acer Nitro         | 3         | 1.16%   |
| Toshiba Satellite  | 2         | 0.78%   |
| RPi Raspberry      | 2         | 0.78%   |
| OEM Intel          | 2         | 0.78%   |
| MSI MS-7B89        | 2         | 0.78%   |
| MSI MS-7788        | 2         | 0.78%   |
| MSI MS-7668        | 2         | 0.78%   |
| MSI Modern         | 2         | 0.78%   |
| Intel DG41RQ       | 2         | 0.78%   |
| HP Laptop          | 2         | 0.78%   |
| HP Compaq          | 2         | 0.78%   |
| HP 14              | 2         | 0.78%   |
| Gigabyte B250M-HD3 | 2         | 0.78%   |
| Dell XPS           | 2         | 0.78%   |
| ASUS ZenBook       | 2         | 0.78%   |
| ASUS X510UQ        | 2         | 0.78%   |
| ASUS P453UA        | 2         | 0.78%   |
| Timi Mi            | 1         | 0.39%   |
| SYS H310CH5-TI2    | 1         | 0.39%   |
| Samsung 300E5EV    | 1         | 0.39%   |
| Notebook W9x0LU    | 1         | 0.39%   |
| Notebook N750BU    | 1         | 0.39%   |
| Notebook N2x0LU    | 1         | 0.39%   |
| Notebook DCL       | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2016    | 33        | 12.79%  |
| 2019    | 31        | 12.02%  |
| 2018    | 30        | 11.63%  |
| 2017    | 26        | 10.08%  |
| 2015    | 20        | 7.75%   |
| 2012    | 20        | 7.75%   |
| 2021    | 17        | 6.59%   |
| 2013    | 17        | 6.59%   |
| 2020    | 15        | 5.81%   |
| 2014    | 15        | 5.81%   |
| 2011    | 10        | 3.88%   |
| 2010    | 10        | 3.88%   |
| 2009    | 7         | 2.71%   |
| 2008    | 3         | 1.16%   |
| Unknown | 3         | 1.16%   |
| 2022    | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 165       | 63.95%  |
| Desktop        | 84        | 32.56%  |
| Convertible    | 4         | 1.55%   |
| System on chip | 2         | 0.78%   |
| Phone          | 1         | 0.39%   |
| Tablet         | 1         | 0.39%   |
| Mini pc        | 1         | 0.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 242       | 92.02%  |
| Enabled  | 21        | 7.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 258       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 95        | 35.98%  |
| 3.01-4.0   | 69        | 26.14%  |
| 8.01-16.0  | 48        | 18.18%  |
| 16.01-24.0 | 30        | 11.36%  |
| 1.01-2.0   | 12        | 4.55%   |
| 32.01-64.0 | 6         | 2.27%   |
| 2.01-3.0   | 3         | 1.14%   |
| 0.51-1.0   | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 103       | 35.4%   |
| 2.01-3.0   | 96        | 32.99%  |
| 3.01-4.0   | 42        | 14.43%  |
| 4.01-8.0   | 28        | 9.62%   |
| 0.51-1.0   | 13        | 4.47%   |
| 8.01-16.0  | 4         | 1.37%   |
| 0.01-0.5   | 4         | 1.37%   |
| 16.01-24.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 164       | 62.36%  |
| 2      | 84        | 31.94%  |
| 3      | 12        | 4.56%   |
| 5      | 1         | 0.38%   |
| 4      | 1         | 0.38%   |
| 0      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 68.97%  |
| Yes       | 81        | 31.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 82.63%  |
| No        | 45        | 17.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 76.43%  |
| No        | 62        | 23.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 59.92%  |
| No        | 105       | 40.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Bangladesh | 258       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Dhaka             | 162       | 59.34%  |
| Chittagong        | 17        | 6.23%   |
| Rajshahi          | 9         | 3.3%    |
| Tongi             | 8         | 2.93%   |
| Jessore           | 8         | 2.93%   |
| Khulna            | 5         | 1.83%   |
| Comilla           | 5         | 1.83%   |
| Azimpur           | 4         | 1.47%   |
| Wari              | 3         | 1.1%    |
| Pabna             | 3         | 1.1%    |
| Narayanganj       | 3         | 1.1%    |
| Mirpur            | 3         | 1.1%    |
| Bogra             | 3         | 1.1%    |
| Sherpur           | 2         | 0.73%   |
| Savar Upazila     | 2         | 0.73%   |
| Nilphamari        | 2         | 0.73%   |
| Feni              | 2         | 0.73%   |
| Uttara            | 1         | 0.37%   |
| Sylhet            | 1         | 0.37%   |
| Srimangal         | 1         | 0.37%   |
| Sirajganj         | 1         | 0.37%   |
| Senbag            | 1         | 0.37%   |
| Rangpur City      | 1         | 0.37%   |
| Pirganj           | 1         | 0.37%   |
| Patnitala         | 1         | 0.37%   |
| Paltan            | 1         | 0.37%   |
| Pabna Sadar       | 1         | 0.37%   |
| NДЃrДЃyanganj | 1         | 0.37%   |
| Natore            | 1         | 0.37%   |
| Narsingdi         | 1         | 0.37%   |
| Narail            | 1         | 0.37%   |
| Nalitabari        | 1         | 0.37%   |
| Nalchiti          | 1         | 0.37%   |
| Nāgarpur         | 1         | 0.37%   |
| Mymensingh        | 1         | 0.37%   |
| LДЃkshДЃm     | 1         | 0.37%   |
| Khilgaon          | 1         | 0.37%   |
| Jamalpur          | 1         | 0.37%   |
| Hurua             | 1         | 0.37%   |
| Gulshan           | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 69        | 97     | 19.49%  |
| Seagate                        | 61        | 76     | 17.23%  |
| Toshiba                        | 53        | 66     | 14.97%  |
| Samsung Electronics            | 26        | 40     | 7.34%   |
| Transcend                      | 19        | 20     | 5.37%   |
| Hitachi                        | 14        | 18     | 3.95%   |
| HGST                           | 12        | 12     | 3.39%   |
| Intel                          | 10        | 12     | 2.82%   |
| SanDisk                        | 9         | 9      | 2.54%   |
| A-DATA Technology              | 7         | 8      | 1.98%   |
| Micron Technology              | 6         | 6      | 1.69%   |
| Kingston                       | 5         | 7      | 1.41%   |
| Teutons                        | 4         | 8      | 1.13%   |
| Silicon Motion                 | 4         | 10     | 1.13%   |
| Hewlett-Packard                | 4         | 4      | 1.13%   |
| Corsair                        | 4         | 6      | 1.13%   |
| Unknown                        | 3         | 4      | 0.85%   |
| SK hynix                       | 3         | 3      | 0.85%   |
| Phison                         | 3         | 3      | 0.85%   |
| Apacer                         | 3         | 4      | 0.85%   |
| TwinMOS                        | 2         | 2      | 0.56%   |
| Ramsta                         | 2         | 2      | 0.56%   |
| PNY                            | 2         | 2      | 0.56%   |
| Phison Electronics             | 2         | 3      | 0.56%   |
| KingSpec                       | 2         | 2      | 0.56%   |
| HS-SSD-E100                    | 2         | 3      | 0.56%   |
| Gigabyte Technology            | 2         | 3      | 0.56%   |
| China                          | 2         | 2      | 0.56%   |
| WDC WDS4                       | 1         | 1      | 0.28%   |
| WALTON                         | 1         | 2      | 0.28%   |
| Team                           | 1         | 1      | 0.28%   |
| Solid State Storage Technology | 1         | 1      | 0.28%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.28%   |
| Realtek                        | 1         | 1      | 0.28%   |
| Patriot                        | 1         | 1      | 0.28%   |
| OCZ                            | 1         | 1      | 0.28%   |
| Lexar                          | 1         | 2      | 0.28%   |
| KIOXIA                         | 1         | 1      | 0.28%   |
| Kingsand                       | 1         | 1      | 0.28%   |
| KingFast                       | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 18        | 4.86%   |
| Toshiba MQ04ABF100 1TB               | 15        | 4.05%   |
| Toshiba DT01ACA100 1TB               | 10        | 2.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 8         | 2.16%   |
| Seagate ST500DM002-1BD142 500GB      | 7         | 1.89%   |
| Seagate ST1000DM010-2EP102 1TB       | 7         | 1.89%   |
| Toshiba HDWD110 1TB                  | 6         | 1.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 1.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 5         | 1.35%   |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 1.35%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 1.35%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.08%   |
| SanDisk NVMe SSD Drive 512GB         | 4         | 1.08%   |
| Intel NVMe SSD Drive 512GB           | 4         | 1.08%   |
| HGST HTS541010A9E680 1TB             | 4         | 1.08%   |
| A-DATA SU650 240GB SSD               | 4         | 1.08%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 3         | 0.81%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 3         | 0.81%   |
| WDC WD10SPZX-60Z10T0 1TB             | 3         | 0.81%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 0.81%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 0.81%   |
| Transcend TS256GSSD230S 256GB        | 3         | 0.81%   |
| Transcend TS128GSSD370S 128GB        | 3         | 0.81%   |
| Transcend TS120GMTS420S 120GB SSD    | 3         | 0.81%   |
| Toshiba DT01ACA200 2TB               | 3         | 0.81%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.81%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.81%   |
| Samsung HD502HJ 500GB                | 3         | 0.81%   |
| Intel SSD 660P Series 1024GB         | 3         | 0.81%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.81%   |
| Corsair Force MP510 240GB            | 3         | 0.81%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 0.54%   |
| WDC WD40PURX-64N96Y0 4TB             | 2         | 0.54%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.54%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 0.54%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 0.54%   |
| WDC WD SSD 120GB                     | 2         | 0.54%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 2         | 0.54%   |
| Transcend TS240GSSD220S 240GB        | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 76     | 31.94%  |
| Toshiba             | 47        | 59     | 24.61%  |
| WDC                 | 45        | 61     | 23.56%  |
| Hitachi             | 14        | 18     | 7.33%   |
| Samsung Electronics | 12        | 20     | 6.28%   |
| HGST                | 12        | 12     | 6.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 27     | 20.75%  |
| Transcend           | 18        | 19     | 16.98%  |
| Samsung Electronics | 8         | 10     | 7.55%   |
| A-DATA Technology   | 7         | 8      | 6.6%    |
| SanDisk             | 5         | 5      | 4.72%   |
| Micron Technology   | 5         | 5      | 4.72%   |
| Teutons             | 4         | 8      | 3.77%   |
| Hewlett-Packard     | 4         | 4      | 3.77%   |
| Toshiba             | 3         | 4      | 2.83%   |
| Apacer              | 3         | 4      | 2.83%   |
| TwinMOS             | 2         | 2      | 1.89%   |
| Ramsta              | 2         | 2      | 1.89%   |
| PNY                 | 2         | 2      | 1.89%   |
| KingSpec            | 2         | 2      | 1.89%   |
| HS-SSD-E100         | 2         | 2      | 1.89%   |
| Gigabyte Technology | 2         | 3      | 1.89%   |
| China               | 2         | 2      | 1.89%   |
| WDC WDS4            | 1         | 1      | 0.94%   |
| WALTON              | 1         | 2      | 0.94%   |
| Team                | 1         | 1      | 0.94%   |
| SK hynix            | 1         | 1      | 0.94%   |
| Patriot             | 1         | 1      | 0.94%   |
| OCZ                 | 1         | 1      | 0.94%   |
| Kingston            | 1         | 1      | 0.94%   |
| Intel               | 1         | 1      | 0.94%   |
| GeIL                | 1         | 1      | 0.94%   |
| GAMER               | 1         | 1      | 0.94%   |
| Crucial             | 1         | 2      | 0.94%   |
| Corsair             | 1         | 2      | 0.94%   |
| ASMT                | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 182       | 246    | 52.91%  |
| SSD     | 103       | 125    | 29.94%  |
| NVMe    | 50        | 73     | 14.53%  |
| Unknown | 6         | 6      | 1.74%   |
| MMC     | 3         | 4      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 224       | 375    | 80%     |
| NVMe | 50        | 72     | 17.86%  |
| SAS  | 3         | 3      | 1.07%   |
| MMC  | 3         | 4      | 1.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 148       | 207    | 54.01%  |
| 0.51-1.0   | 113       | 147    | 41.24%  |
| 1.01-2.0   | 9         | 9      | 3.28%   |
| 3.01-4.0   | 2         | 3      | 0.73%   |
| 2.01-3.0   | 1         | 4      | 0.36%   |
| 4.01-10.0  | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 29.86%  |
| 251-500        | 56        | 20.14%  |
| 501-1000       | 54        | 19.42%  |
| 1001-2000      | 25        | 8.99%   |
| 51-100         | 23        | 8.27%   |
| 21-50          | 16        | 5.76%   |
| 1-20           | 13        | 4.68%   |
| Unknown        | 5         | 1.8%    |
| More than 3000 | 3         | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 100       | 35.21%  |
| 21-50          | 58        | 20.42%  |
| 101-250        | 44        | 15.49%  |
| 51-100         | 42        | 14.79%  |
| 251-500        | 17        | 5.99%   |
| 501-1000       | 13        | 4.58%   |
| Unknown        | 5         | 1.76%   |
| 1001-2000      | 4         | 1.41%   |
| More than 3000 | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 4      | 5.26%   |
| Toshiba DT01ACA100 1TB                         | 2         | 2      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB                | 2         | 2      | 5.26%   |
| HGST HTS545050A7E680 500GB                     | 2         | 2      | 5.26%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 5.26%   |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 1      | 2.63%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 2.63%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 2.63%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 2      | 2.63%   |
| WDC WD10JPVT-00MS8T0 1TB                       | 1         | 1      | 2.63%   |
| WDC WD10EZEX-60WN4A0 1TB                       | 1         | 1      | 2.63%   |
| WDC WD10EZEX-22MFCA0 1TB                       | 1         | 1      | 2.63%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 2.63%   |
| Toshiba HDWD110 1TB                            | 1         | 1      | 2.63%   |
| Toshiba DT01ACA200 2TB                         | 1         | 1      | 2.63%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD          | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 2.63%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 2.63%   |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 2.63%   |
| Samsung Electronics HD161HJ 160GB              | 1         | 2      | 2.63%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.63%   |
| Intel SSDSCKKW240H6 240GB                      | 1         | 1      | 2.63%   |
| HS-SSD-E100 SSD 128G                           | 1         | 1      | 2.63%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 2.63%   |
| Hitachi HDT725050VLA380 500GB                  | 1         | 1      | 2.63%   |
| Hitachi HDT721032SLA360 320GB                  | 1         | 2      | 2.63%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 2.63%   |
| Hewlett-Packard SSD S600 240GB                 | 1         | 1      | 2.63%   |
| A-DATA Technology SU650 240GB SSD              | 1         | 2      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 21.05%  |
| Toshiba             | 7         | 9      | 18.42%  |
| Seagate             | 7         | 7      | 18.42%  |
| HGST                | 5         | 5      | 13.16%  |
| Hitachi             | 3         | 4      | 7.89%   |
| Samsung Electronics | 2         | 3      | 5.26%   |
| SK hynix            | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| HS-SSD-E100         | 1         | 1      | 2.63%   |
| Hewlett-Packard     | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 2      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 25%     |
| Toshiba             | 7         | 9      | 21.88%  |
| Seagate             | 7         | 7      | 21.88%  |
| HGST                | 5         | 5      | 15.63%  |
| Hitachi             | 3         | 4      | 9.38%   |
| Samsung Electronics | 2         | 3      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 37     | 83.78%  |
| SSD  | 6         | 7      | 16.22%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 157       | 258    | 55.09%  |
| Works    | 90        | 151    | 31.58%  |
| Malfunc  | 37        | 44     | 12.98%  |
| Failed   | 1         | 1      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 212       | 71.62%  |
| AMD                            | 34        | 11.49%  |
| SanDisk                        | 9         | 3.04%   |
| Phison Electronics             | 8         | 2.7%    |
| Samsung Electronics            | 7         | 2.36%   |
| Silicon Motion                 | 4         | 1.35%   |
| Kingston Technology Company    | 4         | 1.35%   |
| Marvell Technology Group       | 3         | 1.01%   |
| Toshiba America Info Systems   | 2         | 0.68%   |
| SK hynix                       | 2         | 0.68%   |
| Shenzhen Longsys Electronics   | 2         | 0.68%   |
| KIOXIA                         | 2         | 0.68%   |
| ASMedia Technology             | 2         | 0.68%   |
| VIA Technologies               | 1         | 0.34%   |
| Transcend                      | 1         | 0.34%   |
| Solid State Storage Technology | 1         | 0.34%   |
| Micron Technology              | 1         | 0.34%   |
| Biwin Storage Technology       | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 52        | 14.94%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 26        | 7.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 14        | 4.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 3.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 3.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 3.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 3.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 2.87%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 2.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 2.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 9         | 2.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9         | 2.59%   |
| Intel SSD 660P Series                                                                   | 7         | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 2.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 2.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 1.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.15%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 1.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 1.15%   |
| Phison PS5013 E13 NVMe Controller                                                       | 4         | 1.15%   |
| Phison E12 NVMe Controller                                                              | 4         | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.15%   |
| AMD FCH SATA Controller D                                                               | 4         | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.86%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.57%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 2         | 0.57%   |
| Marvell Group 88SE912x IDE Controller                                                   | 2         | 0.57%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 0.57%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 193       | 63.91%  |
| NVMe | 51        | 16.89%  |
| IDE  | 30        | 9.93%   |
| RAID | 28        | 9.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 218       | 84.5%   |
| AMD    | 37        | 14.34%  |
| ARM    | 3         | 1.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 4.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 3.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 3.09%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 2.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 2.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4         | 1.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 1.54%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 1.54%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 1.54%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.54%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 1.54%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 1.54%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.16%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 3         | 1.16%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.16%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.16%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3         | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.16%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.16%   |
| Intel Xeon CPU X3440 @ 2.53GHz                | 2         | 0.77%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 2         | 0.77%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 0.77%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2         | 0.77%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2         | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.77%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.77%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 0.77%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.77%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.77%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 93        | 36.05%  |
| Intel Core i3           | 53        | 20.54%  |
| Intel Core i7           | 19        | 7.36%   |
| AMD Ryzen 5             | 19        | 7.36%   |
| Other                   | 17        | 6.59%   |
| Intel Pentium           | 12        | 4.65%   |
| Intel Core 2 Duo        | 9         | 3.49%   |
| Intel Celeron           | 6         | 2.33%   |
| AMD Ryzen 3             | 6         | 2.33%   |
| Intel Pentium Dual-Core | 5         | 1.94%   |
| AMD Ryzen 7             | 5         | 1.94%   |
| Intel Xeon              | 3         | 1.16%   |
| Intel Atom              | 2         | 0.78%   |
| AMD A8                  | 2         | 0.78%   |
| Intel Core 2 Quad       | 1         | 0.39%   |
| ARM AArch64             | 1         | 0.39%   |
| AMD Ryzen 9             | 1         | 0.39%   |
| AMD FX                  | 1         | 0.39%   |
| AMD E2                  | 1         | 0.39%   |
| AMD E                   | 1         | 0.39%   |
| AMD A4                  | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 144       | 55.6%   |
| 4       | 86        | 33.2%   |
| 6       | 18        | 6.95%   |
| 8       | 5         | 1.93%   |
| 10      | 2         | 0.77%   |
| 1       | 2         | 0.77%   |
| 12      | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 257       | 99.61%  |
| Unknown | 1         | 0.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 188       | 72.87%  |
| 1       | 69        | 26.74%  |
| Unknown | 1         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 257       | 99.61%  |
| Unknown        | 1         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 24.63%  |
| 0x806e9    | 23        | 8.46%   |
| 0x806ea    | 15        | 5.51%   |
| 0x306a9    | 15        | 5.51%   |
| 0x406e3    | 12        | 4.41%   |
| 0x206a7    | 11        | 4.04%   |
| 0x40651    | 10        | 3.68%   |
| 0x306d4    | 9         | 3.31%   |
| 0x306c3    | 9         | 3.31%   |
| 0x806c1    | 8         | 2.94%   |
| 0x1067a    | 8         | 2.94%   |
| 0x08108109 | 8         | 2.94%   |
| 0x806ec    | 7         | 2.57%   |
| 0x806eb    | 7         | 2.57%   |
| 0x906e9    | 6         | 2.21%   |
| 0x706e5    | 4         | 1.47%   |
| 0x406c4    | 4         | 1.47%   |
| 0x08701021 | 4         | 1.47%   |
| 0x506e3    | 3         | 1.1%    |
| 0x20655    | 3         | 1.1%    |
| 0x106e5    | 3         | 1.1%    |
| 0x10676    | 3         | 1.1%    |
| 0x08108102 | 3         | 1.1%    |
| 0xa0652    | 2         | 0.74%   |
| 0x906eb    | 2         | 0.74%   |
| 0x906ea    | 2         | 0.74%   |
| 0x90672    | 2         | 0.74%   |
| 0x6fb      | 2         | 0.74%   |
| 0x20652    | 2         | 0.74%   |
| 0x0a50000c | 2         | 0.74%   |
| 0x0810100b | 2         | 0.74%   |
| 0x806d1    | 1         | 0.37%   |
| 0x506c9    | 1         | 0.37%   |
| 0x50654    | 1         | 0.37%   |
| 0x406c3    | 1         | 0.37%   |
| 0x30678    | 1         | 0.37%   |
| 0x30661    | 1         | 0.37%   |
| 0x106ca    | 1         | 0.37%   |
| 0x10661    | 1         | 0.37%   |
| 0x08701013 | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 72        | 27.8%   |
| Haswell          | 25        | 9.65%   |
| Skylake          | 20        | 7.72%   |
| IvyBridge        | 19        | 7.34%   |
| Zen+             | 14        | 5.41%   |
| SandyBridge      | 14        | 5.41%   |
| Penryn           | 13        | 5.02%   |
| TigerLake        | 12        | 4.63%   |
| Broadwell        | 12        | 4.63%   |
| Zen 2            | 8         | 3.09%   |
| Silvermont       | 6         | 2.32%   |
| Zen 3            | 5         | 1.93%   |
| Westmere         | 5         | 1.93%   |
| IceLake          | 5         | 1.93%   |
| Core             | 4         | 1.54%   |
| CometLake        | 4         | 1.54%   |
| Unknown          | 4         | 1.54%   |
| Zen              | 3         | 1.16%   |
| Nehalem          | 3         | 1.16%   |
| Piledriver       | 2         | 0.77%   |
| Excavator        | 2         | 0.77%   |
| Bonnell          | 2         | 0.77%   |
| Alderlake Hybrid | 2         | 0.77%   |
| Puma             | 1         | 0.39%   |
| Goldmont         | 1         | 0.39%   |
| Bobcat           | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 202       | 66.23%  |
| Nvidia | 59        | 19.34%  |
| AMD    | 44        | 14.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 27        | 8.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 5.16%   |
| Intel UHD Graphics 620                                                                   | 15        | 4.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 4.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 4.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 3.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.55%   |
| Intel HD Graphics 5500                                                                   | 11        | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 2.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 2.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 2.26%   |
| Intel HD Graphics 630                                                                    | 6         | 1.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.94%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.61%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.29%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.29%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.29%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.29%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.97%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.65%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 0.65%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 159       | 60.92%  |
| Intel + Nvidia | 35        | 13.41%  |
| 1 x AMD        | 31        | 11.88%  |
| 1 x Nvidia     | 20        | 7.66%   |
| Intel + AMD    | 5         | 1.92%   |
| 2 x AMD        | 4         | 1.53%   |
| AMD + Nvidia   | 4         | 1.53%   |
| Other          | 3         | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 221       | 82.46%  |
| Proprietary | 36        | 13.43%  |
| Unknown     | 11        | 4.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 194       | 73.21%  |
| 1.01-2.0   | 34        | 12.83%  |
| 3.01-4.0   | 15        | 5.66%   |
| 0.51-1.0   | 8         | 3.02%   |
| 0.01-0.5   | 8         | 3.02%   |
| 7.01-8.0   | 4         | 1.51%   |
| 5.01-6.0   | 2         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 46        | 17.42%  |
| AU Optronics            | 42        | 15.91%  |
| Chimei Innolux          | 35        | 13.26%  |
| LG Display              | 31        | 11.74%  |
| Samsung Electronics     | 26        | 9.85%   |
| Dell                    | 21        | 7.95%   |
| Goldstar                | 14        | 5.3%    |
| Hewlett-Packard         | 13        | 4.92%   |
| ViewSonic               | 4         | 1.52%   |
| PANDA                   | 4         | 1.52%   |
| Philips                 | 3         | 1.14%   |
| ASUSTek Computer        | 3         | 1.14%   |
| Ancor Communications    | 3         | 1.14%   |
| Sony                    | 2         | 0.76%   |
| MSI                     | 2         | 0.76%   |
| Chi Mei Optoelectronics | 2         | 0.76%   |
| ___                     | 1         | 0.38%   |
| UTV                     | 1         | 0.38%   |
| Unknown                 | 1         | 0.38%   |
| Sharp                   | 1         | 0.38%   |
| QXS                     | 1         | 0.38%   |
| LLL                     | 1         | 0.38%   |
| HUYINIUDA               | 1         | 0.38%   |
| HUAWEI                  | 1         | 0.38%   |
| FSR                     | 1         | 0.38%   |
| CND                     | 1         | 0.38%   |
| CHR                     | 1         | 0.38%   |
| Apple                   | 1         | 0.38%   |
| AOC                     | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch    | 9         | 3.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 7         | 2.58%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch    | 4         | 1.48%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch          | 4         | 1.48%   |
| Dell SE2219HX DELF10F 1920x1080 476x268mm 21.5-inch                 | 4         | 1.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch      | 4         | 1.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch      | 4         | 1.48%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch        | 3         | 1.11%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch           | 3         | 1.11%   |
| Dell S2240L DELD054 1920x1080 476x267mm 21.5-inch                   | 3         | 1.11%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                   | 3         | 1.11%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch               | 3         | 1.11%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                | 3         | 1.11%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                | 3         | 1.11%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch | 2         | 0.74%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch   | 2         | 0.74%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch        | 2         | 0.74%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch         | 2         | 0.74%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch         | 2         | 0.74%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch        | 2         | 0.74%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch         | 2         | 0.74%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch         | 2         | 0.74%   |
| Hewlett-Packard v185w HWP2820 1366x768 410x230mm 18.5-inch          | 2         | 0.74%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch           | 2         | 0.74%   |
| Dell S2218H DELD0B8 1920x1080 480x270mm 21.7-inch                   | 2         | 0.74%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                    | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch     | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch     | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch    | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch     | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch     | 2         | 0.74%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch      | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch      | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch      | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch       | 2         | 0.74%   |
| ___ AAA ___1062 1440x900 410x260mm 19.1-inch                        | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 111       | 44.05%  |
| 1920x1080 (FHD)   | 105       | 41.67%  |
| 3840x2160 (4K)    | 9         | 3.57%   |
| 1440x900 (WXGA+)  | 6         | 2.38%   |
| 1600x900 (HD+)    | 5         | 1.98%   |
| 1280x1024 (SXGA)  | 3         | 1.19%   |
| 1280x800 (WXGA)   | 2         | 0.79%   |
| 1024x600          | 2         | 0.79%   |
| 3440x1440         | 1         | 0.4%    |
| 3360x1080         | 1         | 0.4%    |
| 2736x1824         | 1         | 0.4%    |
| 2560x1600         | 1         | 0.4%    |
| 2560x1440 (QHD)   | 1         | 0.4%    |
| 2240x1400         | 1         | 0.4%    |
| 1920x1200 (WUXGA) | 1         | 0.4%    |
| 1024x768 (XGA)    | 1         | 0.4%    |
| Unknown           | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 82        | 30.94%  |
| 13      | 45        | 16.98%  |
| 21      | 35        | 13.21%  |
| 14      | 34        | 12.83%  |
| 18      | 25        | 9.43%   |
| 23      | 8         | 3.02%   |
| 12      | 6         | 2.26%   |
| 17      | 5         | 1.89%   |
| 19      | 4         | 1.51%   |
| Unknown | 4         | 1.51%   |
| 24      | 3         | 1.13%   |
| 72      | 2         | 0.75%   |
| 16      | 2         | 0.75%   |
| 11      | 2         | 0.75%   |
| 10      | 2         | 0.75%   |
| 84      | 1         | 0.38%   |
| 39      | 1         | 0.38%   |
| 34      | 1         | 0.38%   |
| 27      | 1         | 0.38%   |
| 26      | 1         | 0.38%   |
| 20      | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 149       | 56.87%  |
| 401-500     | 67        | 25.57%  |
| 201-300     | 22        | 8.4%    |
| 501-600     | 9         | 3.44%   |
| 351-400     | 6         | 2.29%   |
| Unknown     | 4         | 1.53%   |
| 1501-2000   | 3         | 1.15%   |
| 801-900     | 1         | 0.38%   |
| 701-800     | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 220       | 90.53%  |
| 16/10   | 12        | 4.94%   |
| 4/3     | 4         | 1.65%   |
| Unknown | 4         | 1.65%   |
| 5/4     | 1         | 0.41%   |
| 3/2     | 1         | 0.41%   |
| 21/9    | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 82        | 31.06%  |
| 81-90          | 68        | 25.76%  |
| 201-250        | 35        | 13.26%  |
| 141-150        | 26        | 9.85%   |
| 151-200        | 13        | 4.92%   |
| 71-80          | 9         | 3.41%   |
| 61-70          | 6         | 2.27%   |
| 131-140        | 4         | 1.52%   |
| Unknown        | 4         | 1.52%   |
| More than 1000 | 3         | 1.14%   |
| 251-300        | 3         | 1.14%   |
| 51-60          | 2         | 0.76%   |
| 41-50          | 2         | 0.76%   |
| 111-120        | 2         | 0.76%   |
| 351-500        | 1         | 0.38%   |
| 301-350        | 1         | 0.38%   |
| 121-130        | 1         | 0.38%   |
| 501-1000       | 1         | 0.38%   |
| 91-100         | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 120       | 46.33%  |
| 121-160       | 75        | 28.96%  |
| 51-100        | 50        | 19.31%  |
| 161-240       | 6         | 2.32%   |
| Unknown       | 4         | 1.54%   |
| More than 240 | 2         | 0.77%   |
| 1-50          | 2         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 225       | 85.55%  |
| 2     | 25        | 9.51%   |
| 0     | 11        | 4.18%   |
| 3     | 2         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 184       | 47.42%  |
| Intel                             | 96        | 24.74%  |
| Qualcomm Atheros                  | 51        | 13.14%  |
| Ralink Technology                 | 14        | 3.61%   |
| Xiaomi                            | 9         | 2.32%   |
| TP-Link                           | 8         | 2.06%   |
| Broadcom                          | 6         | 1.55%   |
| MediaTek                          | 4         | 1.03%   |
| Ralink                            | 2         | 0.52%   |
| Qualcomm                          | 2         | 0.52%   |
| HMD Global                        | 2         | 0.52%   |
| D-Link                            | 2         | 0.52%   |
| ASIX Electronics                  | 2         | 0.52%   |
| Sundance Technology Inc / IC Plus | 1         | 0.26%   |
| Samsung Electronics               | 1         | 0.26%   |
| NetGear                           | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| Arduino SA                        | 1         | 0.26%   |
| AboCom Systems                    | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127       | 29%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 8.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 4.34%   |
| Intel Wireless 8265 / 8275                                        | 15        | 3.42%   |
| Ralink MT7601U Wireless Adapter                                   | 12        | 2.74%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 2.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 2.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 2.05%   |
| Intel Wireless 3165                                               | 8         | 1.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.14%   |
| Intel Wireless 8260                                               | 5         | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.91%   |
| Intel Wireless 7265                                               | 4         | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.91%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                 | 3         | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.68%   |
| Intel Wireless 7260                                               | 3         | 0.68%   |
| Intel Wireless 3160                                               | 3         | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.46%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.46%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 2         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.46%   |
| Qualcomm Redmi 9T                                                 | 2         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 40.38%  |
| Qualcomm Atheros      | 48        | 23.08%  |
| Realtek Semiconductor | 39        | 18.75%  |
| Ralink Technology     | 14        | 6.73%   |
| TP-Link               | 7         | 3.37%   |
| Broadcom              | 4         | 1.92%   |
| Xiaomi                | 3         | 1.44%   |
| Ralink                | 2         | 0.96%   |
| MediaTek              | 2         | 0.96%   |
| D-Link                | 2         | 0.96%   |
| NetGear               | 1         | 0.48%   |
| Dell                  | 1         | 0.48%   |
| AboCom Systems        | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 9.13%   |
| Intel Wireless 8265 / 8275                                     | 15        | 7.21%   |
| Ralink MT7601U Wireless Adapter                                | 12        | 5.77%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 5.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 5.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 5.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 4.33%   |
| Intel Wireless 3165                                            | 8         | 3.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 3.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.4%    |
| Intel Wireless 8260                                            | 5         | 2.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.92%   |
| Intel Wireless 7265                                            | 4         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.92%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 3         | 1.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3         | 1.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.44%   |
| Intel Wireless 7260                                            | 3         | 1.44%   |
| Intel Wireless 3160                                            | 3         | 1.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.96%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 2         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.96%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 0.96%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.48%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.48%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.48%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 170       | 74.89%  |
| Intel                             | 30        | 13.22%  |
| Qualcomm Atheros                  | 7         | 3.08%   |
| Xiaomi                            | 6         | 2.64%   |
| Broadcom                          | 3         | 1.32%   |
| Qualcomm                          | 2         | 0.88%   |
| MediaTek                          | 2         | 0.88%   |
| HMD Global                        | 2         | 0.88%   |
| ASIX Electronics                  | 2         | 0.88%   |
| TP-Link                           | 1         | 0.44%   |
| Sundance Technology Inc / IC Plus | 1         | 0.44%   |
| Samsung Electronics               | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127       | 55.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 15.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.06%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.31%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.87%   |
| Qualcomm Redmi 9T                                                 | 2         | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.87%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.87%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.87%   |
| HMD Global Android                                                | 2         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.87%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.44%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet             | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.44%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.44%   |
| MediaTek moto e(6) plus                                           | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.44%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 214       | 51.57%  |
| WiFi     | 200       | 48.19%  |
| Modem    | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 164       | 63.32%  |
| Ethernet | 95        | 36.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 127       | 49.22%  |
| 2     | 126       | 48.84%  |
| 0     | 5         | 1.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 256       | 99.22%  |
| Yes  | 2         | 0.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 44.03%  |
| IMC Networks                    | 21        | 13.21%  |
| Realtek Semiconductor           | 16        | 10.06%  |
| Qualcomm Atheros Communications | 13        | 8.18%   |
| Cambridge Silicon Radio         | 13        | 8.18%   |
| Lite-On Technology              | 10        | 6.29%   |
| Broadcom                        | 7         | 4.4%    |
| Foxconn / Hon Hai               | 4         | 2.52%   |
| Toshiba                         | 1         | 0.63%   |
| Ralink                          | 1         | 0.63%   |
| Hewlett-Packard                 | 1         | 0.63%   |
| Dell                            | 1         | 0.63%   |
| Unknown                         | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 23.9%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 8.18%   |
| Intel AX201 Bluetooth                               | 12        | 7.55%   |
| IMC Networks Bluetooth Device                       | 12        | 7.55%   |
| Realtek Bluetooth Radio                             | 10        | 6.29%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 6.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 4.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 4.4%    |
| IMC Networks Bluetooth Radio                        | 7         | 4.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 3.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.89%   |
| Lite-On Bluetooth Device                            | 3         | 1.89%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.26%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.26%   |
| Intel AX200 Bluetooth                               | 2         | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.26%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.26%   |
| Toshiba Bluetooth Radio                             | 1         | 0.63%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.63%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.63%   |
| IMC Networks Wireless_Device                        | 1         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.63%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.63%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.63%   |
| Unknown                                             | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 217       | 71.62%  |
| AMD                    | 45        | 14.85%  |
| Nvidia                 | 27        | 8.91%   |
| Generalplus Technology | 7         | 2.31%   |
| Logitech               | 2         | 0.66%   |
| C-Media Electronics    | 2         | 0.66%   |
| JMTek                  | 1         | 0.33%   |
| iCreate Technologies   | 1         | 0.33%   |
| Creative Labs          | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 58        | 15.8%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 6.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 4.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 3.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 3.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 3.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 3.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 3.27%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 3.27%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.18%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 2.18%   |
| Generalplus Technology USB Audio Device                                                           | 7         | 1.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.91%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.09%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.82%   |
| Intel USB PnP Sound Device                                                                        | 3         | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.54%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 0.54%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.54%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.54%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.54%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.54%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 22.78%  |
| SK hynix            | 30        | 18.99%  |
| Micron Technology   | 18        | 11.39%  |
| G.Skill             | 10        | 6.33%   |
| Kingston            | 9         | 5.7%    |
| Unknown             | 7         | 4.43%   |
| Transcend           | 7         | 4.43%   |
| Corsair             | 7         | 4.43%   |
| A-DATA Technology   | 7         | 4.43%   |
| Team                | 6         | 3.8%    |
| Ramaxel Technology  | 4         | 2.53%   |
| SemsoTai            | 2         | 1.27%   |
| Nanya Technology    | 2         | 1.27%   |
| Unknown (C509)      | 1         | 0.63%   |
| Unknown (768A)      | 1         | 0.63%   |
| TwinMOS             | 1         | 0.63%   |
| Ramos Technology    | 1         | 0.63%   |
| Qumo                | 1         | 0.63%   |
| Patriot             | 1         | 0.63%   |
| Hewlett-Packard     | 1         | 0.63%   |
| GeIL                | 1         | 0.63%   |
| Elpida              | 1         | 0.63%   |
| Crucial             | 1         | 0.63%   |
| ASint Technology    | 1         | 0.63%   |
| Apacer              | 1         | 0.63%   |
| Unknown             | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 5         | 3.07%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 4         | 2.45%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 3         | 1.84%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s   | 3         | 1.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.84%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s     | 3         | 1.84%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 2         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.23%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 1.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 1.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 1.23%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 1.23%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s   | 2         | 1.23%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s    | 2         | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s    | 2         | 1.23%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s     | 2         | 1.23%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 2         | 1.23%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s    | 2         | 1.23%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s | 2         | 1.23%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s   | 2         | 1.23%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 2         | 1.23%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                | 1         | 0.61%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s              | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                  | 1         | 0.61%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s       | 1         | 0.61%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s    | 1         | 0.61%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s      | 1         | 0.61%   |
| Transcend RAM TX2133KLN-8GK 4096MB DIMM DDR3 2000MT/s    | 1         | 0.61%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s      | 1         | 0.61%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s      | 1         | 0.61%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s      | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 77        | 62.6%   |
| DDR3    | 35        | 28.46%  |
| LPDDR3  | 4         | 3.25%   |
| LPDDR4  | 3         | 2.44%   |
| Unknown | 2         | 1.63%   |
| SDRAM   | 1         | 0.81%   |
| DDR2    | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 84        | 70%     |
| DIMM         | 31        | 25.83%  |
| Row Of Chips | 5         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 56        | 40.29%  |
| 8192  | 53        | 38.13%  |
| 16384 | 14        | 10.07%  |
| 2048  | 12        | 8.63%   |
| 32768 | 3         | 2.16%   |
| 1024  | 1         | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 31        | 22.63%  |
| 1600  | 26        | 18.98%  |
| 3200  | 21        | 15.33%  |
| 2400  | 17        | 12.41%  |
| 2133  | 11        | 8.03%   |
| 1333  | 5         | 3.65%   |
| 1067  | 4         | 2.92%   |
| 2800  | 3         | 2.19%   |
| 1867  | 3         | 2.19%   |
| 1334  | 3         | 2.19%   |
| 3800  | 2         | 1.46%   |
| 3266  | 2         | 1.46%   |
| 8400  | 1         | 0.73%   |
| 4199  | 1         | 0.73%   |
| 3666  | 1         | 0.73%   |
| 3333  | 1         | 0.73%   |
| 3151  | 1         | 0.73%   |
| 2933  | 1         | 0.73%   |
| 2000  | 1         | 0.73%   |
| 1066  | 1         | 0.73%   |
| 800   | 1         | 0.73%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Pantum      | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L132 Series | 2         | 66.67%  |
| Pantum PMF22 series     | 1         | 33.33%  |

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
| Chicony Electronics                    | 37        | 22.02%  |
| IMC Networks                           | 30        | 17.86%  |
| Cheng Uei Precision Industry (Foxlink) | 15        | 8.93%   |
| Realtek Semiconductor                  | 13        | 7.74%   |
| Sunplus Innovation Technology          | 10        | 5.95%   |
| Quanta                                 | 10        | 5.95%   |
| Microdia                               | 9         | 5.36%   |
| Acer                                   | 8         | 4.76%   |
| Lite-On Technology                     | 7         | 4.17%   |
| Suyin                                  | 5         | 2.98%   |
| Luxvisions Innotech Limited            | 4         | 2.38%   |
| Z-Star Microelectronics                | 2         | 1.19%   |
| Syntek                                 | 2         | 1.19%   |
| Silicon Motion                         | 2         | 1.19%   |
| Primax Electronics                     | 2         | 1.19%   |
| Logitech                               | 2         | 1.19%   |
| Alcor Micro                            | 2         | 1.19%   |
| WCM_USB                                | 1         | 0.6%    |
| Sonix Technology                       | 1         | 0.6%    |
| SiGma Micro                            | 1         | 0.6%    |
| Importek                               | 1         | 0.6%    |
| DLEQNA19IFK6G2                         | 1         | 0.6%    |
| Bison Electronics                      | 1         | 0.6%    |
| Apple                                  | 1         | 0.6%    |
| ANYKA                                  | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 10        | 5.95%   |
| Chicony USB2.0 VGA UVC WebCam                           | 10        | 5.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 9         | 5.36%   |
| IMC Networks VGA UVC WebCam                             | 5         | 2.98%   |
| Microdia Integrated_Webcam_HD                           | 4         | 2.38%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 2.38%   |
| Lite-On HP HD Camera                                    | 4         | 2.38%   |
| Chicony HD WebCam                                       | 4         | 2.38%   |
| Suyin Integrated_Webcam_HD                              | 3         | 1.79%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.79%   |
| Quanta HD Webcam                                        | 3         | 1.79%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 1.79%   |
| IMC Networks Integrated Camera                          | 3         | 1.79%   |
| Chicony EasyCamera                                      | 3         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 3         | 1.79%   |
| Acer HD Webcam                                          | 3         | 1.79%   |
| Z-Star A4 TECH USB2.0 PC Camera J                       | 2         | 1.19%   |
| Suyin HP Truevision HD                                  | 2         | 1.19%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.19%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.19%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.19%   |
| Quanta HD User Facing                                   | 2         | 1.19%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.19%   |
| Logitech Webcam C270                                    | 2         | 1.19%   |
| Lite-On Integrated Camera                               | 2         | 1.19%   |
| Chicony USB2.0 Camera                                   | 2         | 1.19%   |
| Chicony Integrated Camera                               | 2         | 1.19%   |
| Chicony HP Truevision HD camera                         | 2         | 1.19%   |
| Chicony HP HD Webcam                                    | 2         | 1.19%   |
| Chicony HP HD Camera                                    | 2         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.19%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.19%   |
| Acer EasyCamera                                         | 2         | 1.19%   |
| WCM_USB WEB CAM                                         | 1         | 0.6%    |
| Syntek Integrated Camera                                | 1         | 0.6%    |
| Syntek EasyCamera                                       | 1         | 0.6%    |
| Sunplus XiaoMi USB 2.0 Webcam                           | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 81.25%  |
| Synaptics                  | 3         | 9.38%   |
| Elan Microelectronics      | 2         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 43.75%  |
| Validity Sensors VFS491                                                    | 3         | 9.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 9.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 3.13%   |
| Synaptics  WBDI                                                            | 1         | 3.13%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 6         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 33.33%  |
| Broadcom 5880                                                                | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 191       | 70.74%  |
| 1     | 70        | 25.93%  |
| 2     | 7         | 2.59%   |
| 3     | 2         | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 32        | 38.1%   |
| Graphics card            | 24        | 28.57%  |
| Net/wireless             | 11        | 13.1%   |
| Chipcard                 | 6         | 7.14%   |
| Camera                   | 4         | 4.76%   |
| Communication controller | 3         | 3.57%   |
| Multimedia controller    | 2         | 2.38%   |
| Card reader              | 1         | 1.19%   |
| Bluetooth                | 1         | 1.19%   |

