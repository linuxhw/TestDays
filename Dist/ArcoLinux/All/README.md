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

Total: 2171

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Gigabyte      | AERO 15-SA                  | Notebook    | [5ec761c633](https://linux-hardware.org/?probe=5ec761c633) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [80a2ececa9](https://linux-hardware.org/?probe=80a2ececa9) | Sep 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| System76      | Oryx Pro                    | Notebook    | [66f701b53f](https://linux-hardware.org/?probe=66f701b53f) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a677e67805](https://linux-hardware.org/?probe=a677e67805) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| System76      | Oryx Pro                    | Notebook    | [78adcc218f](https://linux-hardware.org/?probe=78adcc218f) | Sep 04, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0113a2a928](https://linux-hardware.org/?probe=0113a2a928) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [43835631c2](https://linux-hardware.org/?probe=43835631c2) | Sep 01, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Acer          | Predator G3-710             | Desktop     | [b14bf667d5](https://linux-hardware.org/?probe=b14bf667d5) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [777f18537c](https://linux-hardware.org/?probe=777f18537c) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Shuttle       | DS437                       | Notebook    | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [da48ed6b65](https://linux-hardware.org/?probe=da48ed6b65) | Aug 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [86a305b6e7](https://linux-hardware.org/?probe=86a305b6e7) | Aug 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [21157a31fe](https://linux-hardware.org/?probe=21157a31fe) | Aug 26, 2022 |
| Samsung       | 550XDA                      | Notebook    | [505f5100d0](https://linux-hardware.org/?probe=505f5100d0) | Aug 25, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [05a337504b](https://linux-hardware.org/?probe=05a337504b) | Aug 25, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a6d3642195](https://linux-hardware.org/?probe=a6d3642195) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| HP            | 212B                        | Desktop     | [ba5bf87e58](https://linux-hardware.org/?probe=ba5bf87e58) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| HP            | 83EF                        | Desktop     | [6f964c19c3](https://linux-hardware.org/?probe=6f964c19c3) | Aug 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [472eb48ecc](https://linux-hardware.org/?probe=472eb48ecc) | Aug 21, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2a32a11841](https://linux-hardware.org/?probe=2a32a11841) | Aug 20, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [3b7d550ab9](https://linux-hardware.org/?probe=3b7d550ab9) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [9b438d4bbf](https://linux-hardware.org/?probe=9b438d4bbf) | Aug 19, 2022 |
| Toshiba       | Satellite P55t-C            | Notebook    | [deac60d261](https://linux-hardware.org/?probe=deac60d261) | Aug 18, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Dell          | G7 7588                     | Notebook    | [246c96a8ae](https://linux-hardware.org/?probe=246c96a8ae) | Aug 16, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [ea53a9b42b](https://linux-hardware.org/?probe=ea53a9b42b) | Aug 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d193a200da](https://linux-hardware.org/?probe=d193a200da) | Aug 16, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [d6e920456d](https://linux-hardware.org/?probe=d6e920456d) | Aug 16, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [a16dfdfe7b](https://linux-hardware.org/?probe=a16dfdfe7b) | Aug 15, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [abf9c78bdd](https://linux-hardware.org/?probe=abf9c78bdd) | Aug 15, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [e2799ec7f9](https://linux-hardware.org/?probe=e2799ec7f9) | Aug 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [dcf4a63c1e](https://linux-hardware.org/?probe=dcf4a63c1e) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00BNRT    | Notebook    | [72139648d3](https://linux-hardware.org/?probe=72139648d3) | Aug 10, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cba8c9f4ac](https://linux-hardware.org/?probe=cba8c9f4ac) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [55430614f9](https://linux-hardware.org/?probe=55430614f9) | Aug 10, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [93bd067b5d](https://linux-hardware.org/?probe=93bd067b5d) | Aug 09, 2022 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | Notebook    | [490109686e](https://linux-hardware.org/?probe=490109686e) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [cd51b4a39c](https://linux-hardware.org/?probe=cd51b4a39c) | Aug 06, 2022 |
| Xplore        | iX104C5                     | Notebook    | [6ef6194939](https://linux-hardware.org/?probe=6ef6194939) | Aug 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [2f96d2d61a](https://linux-hardware.org/?probe=2f96d2d61a) | Aug 06, 2022 |
| Dell          | 0M9KCM A00                  | Desktop     | [b303a37caf](https://linux-hardware.org/?probe=b303a37caf) | Aug 05, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [afc72e5375](https://linux-hardware.org/?probe=afc72e5375) | Aug 04, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [3225b48633](https://linux-hardware.org/?probe=3225b48633) | Aug 03, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [76a5116e6f](https://linux-hardware.org/?probe=76a5116e6f) | Aug 03, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [d5d6bd6478](https://linux-hardware.org/?probe=d5d6bd6478) | Aug 03, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Sony          | VPCF120FL                   | Notebook    | [75bd2bb218](https://linux-hardware.org/?probe=75bd2bb218) | Aug 02, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [5f41623898](https://linux-hardware.org/?probe=5f41623898) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | Notebook    | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a31407c67](https://linux-hardware.org/?probe=5a31407c67) | Jul 31, 2022 |
| Biostar       | J3060NH                     | Desktop     | [64ac6dadf2](https://linux-hardware.org/?probe=64ac6dadf2) | Jul 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [7c72a6289c](https://linux-hardware.org/?probe=7c72a6289c) | Jul 27, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b55d1a9fe5](https://linux-hardware.org/?probe=b55d1a9fe5) | Jul 25, 2022 |
| System76      | Oryx Pro                    | Notebook    | [3b91037c6f](https://linux-hardware.org/?probe=3b91037c6f) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [987aa33ced](https://linux-hardware.org/?probe=987aa33ced) | Jul 25, 2022 |
| Biostar       | J3060NH                     | Desktop     | [37eb1606ef](https://linux-hardware.org/?probe=37eb1606ef) | Jul 25, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| HP            | 3397                        | Desktop     | [017afa048c](https://linux-hardware.org/?probe=017afa048c) | Jul 20, 2022 |
| Biostar       | J3060NH                     | Desktop     | [ba16aba804](https://linux-hardware.org/?probe=ba16aba804) | Jul 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f5aba6ba0f](https://linux-hardware.org/?probe=f5aba6ba0f) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d8852d71bf](https://linux-hardware.org/?probe=d8852d71bf) | Jul 18, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [04affeedf7](https://linux-hardware.org/?probe=04affeedf7) | Jul 18, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [bafb527de8](https://linux-hardware.org/?probe=bafb527de8) | Jul 17, 2022 |
| HP            | Unknown                     | Notebook    | [01622a24ef](https://linux-hardware.org/?probe=01622a24ef) | Jul 17, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [3cc4a578df](https://linux-hardware.org/?probe=3cc4a578df) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | Desktop     | [f8585ad958](https://linux-hardware.org/?probe=f8585ad958) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | Desktop     | [f2372286e0](https://linux-hardware.org/?probe=f2372286e0) | Jul 17, 2022 |
| HP            | Notebook                    | Notebook    | [e5a1df8ba8](https://linux-hardware.org/?probe=e5a1df8ba8) | Jul 17, 2022 |
| System76      | Oryx Pro                    | Notebook    | [5cac9c78e6](https://linux-hardware.org/?probe=5cac9c78e6) | Jul 16, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [27741b20dd](https://linux-hardware.org/?probe=27741b20dd) | Jul 16, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7cb7b3fd6a](https://linux-hardware.org/?probe=7cb7b3fd6a) | Jul 14, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [a6c59d3803](https://linux-hardware.org/?probe=a6c59d3803) | Jul 14, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [2438f42e95](https://linux-hardware.org/?probe=2438f42e95) | Jul 13, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [a1bf65c2d7](https://linux-hardware.org/?probe=a1bf65c2d7) | Jul 12, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [8002a8ec0f](https://linux-hardware.org/?probe=8002a8ec0f) | Jul 10, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [f3a1f552c8](https://linux-hardware.org/?probe=f3a1f552c8) | Jul 09, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [fb5a2ac873](https://linux-hardware.org/?probe=fb5a2ac873) | Jul 09, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [019c2b1194](https://linux-hardware.org/?probe=019c2b1194) | Jul 07, 2022 |
| HP            | 3397                        | Desktop     | [5f251b624d](https://linux-hardware.org/?probe=5f251b624d) | Jul 07, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [532bbca1f1](https://linux-hardware.org/?probe=532bbca1f1) | Jul 06, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [1f47ada680](https://linux-hardware.org/?probe=1f47ada680) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [8476e2e1c3](https://linux-hardware.org/?probe=8476e2e1c3) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [add34d1f6a](https://linux-hardware.org/?probe=add34d1f6a) | Jul 05, 2022 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | Notebook    | [1773a0941f](https://linux-hardware.org/?probe=1773a0941f) | Jul 05, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [74f6e010da](https://linux-hardware.org/?probe=74f6e010da) | Jul 04, 2022 |
| Biostar       | J3060NH                     | Desktop     | [313e87f523](https://linux-hardware.org/?probe=313e87f523) | Jul 02, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [63da8fa3b9](https://linux-hardware.org/?probe=63da8fa3b9) | Jul 02, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | Desktop     | [f8d0b19c1e](https://linux-hardware.org/?probe=f8d0b19c1e) | Jul 01, 2022 |
| MSI           | GL65 Leopard 10SEK          | Notebook    | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7fa7a1ca82](https://linux-hardware.org/?probe=7fa7a1ca82) | Jun 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0fbd5ca967](https://linux-hardware.org/?probe=0fbd5ca967) | Jun 29, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [cf7b4fb7e1](https://linux-hardware.org/?probe=cf7b4fb7e1) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | Notebook    | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Biostar       | J3060NH                     | Desktop     | [6cefe763b7](https://linux-hardware.org/?probe=6cefe763b7) | Jun 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [af267c59cd](https://linux-hardware.org/?probe=af267c59cd) | Jun 28, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [23b355d820](https://linux-hardware.org/?probe=23b355d820) | Jun 27, 2022 |
| Toshiba       | Satellite Pro S300          | Notebook    | [09f9ef25cd](https://linux-hardware.org/?probe=09f9ef25cd) | Jun 27, 2022 |
| MSI           | B250 GAMING M3              | Desktop     | [b294a7b0b1](https://linux-hardware.org/?probe=b294a7b0b1) | Jun 26, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [0d16a3f2ce](https://linux-hardware.org/?probe=0d16a3f2ce) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [11d7e1ecc7](https://linux-hardware.org/?probe=11d7e1ecc7) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [6452ae1060](https://linux-hardware.org/?probe=6452ae1060) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [e3fcc67ecc](https://linux-hardware.org/?probe=e3fcc67ecc) | Jun 26, 2022 |
| ASUSTek       | All Series                  | Notebook    | [19dde83002](https://linux-hardware.org/?probe=19dde83002) | Jun 26, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [c2fceb2c81](https://linux-hardware.org/?probe=c2fceb2c81) | Jun 24, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Lenovo        | ThinkPad T420 4236EF4       | Notebook    | [1894bb8853](https://linux-hardware.org/?probe=1894bb8853) | Jun 21, 2022 |
| ASRock        | X299 Taichi CLX             | Desktop     | [ee5ad45d8b](https://linux-hardware.org/?probe=ee5ad45d8b) | Jun 21, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1D00... | Notebook    | [eacaed715b](https://linux-hardware.org/?probe=eacaed715b) | Jun 21, 2022 |
| Dell          | 0F896N A02                  | Desktop     | [223cbe95f4](https://linux-hardware.org/?probe=223cbe95f4) | Jun 20, 2022 |
| System76      | Oryx Pro                    | Notebook    | [c623d50d29](https://linux-hardware.org/?probe=c623d50d29) | Jun 20, 2022 |
| ASRock        | Z370 Extreme4               | Desktop     | [c971857c53](https://linux-hardware.org/?probe=c971857c53) | Jun 20, 2022 |
| MSI           | A320M PRO-M2                | Desktop     | [8ffdebb12e](https://linux-hardware.org/?probe=8ffdebb12e) | Jun 20, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [bf292ae80a](https://linux-hardware.org/?probe=bf292ae80a) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1cf9eae6e5](https://linux-hardware.org/?probe=1cf9eae6e5) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [3ac49a6b54](https://linux-hardware.org/?probe=3ac49a6b54) | Jun 19, 2022 |
| PLEXHD        | X79 Turbo                   | Desktop     | [b93749f5e0](https://linux-hardware.org/?probe=b93749f5e0) | Jun 19, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [17e0b3e4c0](https://linux-hardware.org/?probe=17e0b3e4c0) | Jun 19, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Notebook      | PA70ES                      | Notebook    | [7024a9dc03](https://linux-hardware.org/?probe=7024a9dc03) | Jun 16, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [b018aaf572](https://linux-hardware.org/?probe=b018aaf572) | Jun 15, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [3074e50dff](https://linux-hardware.org/?probe=3074e50dff) | Jun 15, 2022 |
| ASRock        | X299 Taichi CLX             | Desktop     | [d349f8b0f5](https://linux-hardware.org/?probe=d349f8b0f5) | Jun 15, 2022 |
| HP            | ZBook Studio G3             | Notebook    | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [8488dcacf9](https://linux-hardware.org/?probe=8488dcacf9) | Jun 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [5d49ce7763](https://linux-hardware.org/?probe=5d49ce7763) | Jun 10, 2022 |
| Razer         | Blade                       | Notebook    | [2d8524dc81](https://linux-hardware.org/?probe=2d8524dc81) | Jun 10, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [f895a113f9](https://linux-hardware.org/?probe=f895a113f9) | Jun 09, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [e29eb57530](https://linux-hardware.org/?probe=e29eb57530) | Jun 09, 2022 |
| Dell          | Latitude 5421               | Notebook    | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [ee0fb46764](https://linux-hardware.org/?probe=ee0fb46764) | Jun 08, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [23191e0c1d](https://linux-hardware.org/?probe=23191e0c1d) | Jun 07, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8f5dae3cd7](https://linux-hardware.org/?probe=8f5dae3cd7) | Jun 06, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b3a7546aa9](https://linux-hardware.org/?probe=b3a7546aa9) | Jun 06, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b48f5d554f](https://linux-hardware.org/?probe=b48f5d554f) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [dc7a83708a](https://linux-hardware.org/?probe=dc7a83708a) | Jun 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [3a9d836e5e](https://linux-hardware.org/?probe=3a9d836e5e) | Jun 03, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [531d7297d9](https://linux-hardware.org/?probe=531d7297d9) | Jun 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [dca80e1df5](https://linux-hardware.org/?probe=dca80e1df5) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| Biostar       | J3060NH                     | Desktop     | [e2d33f6c66](https://linux-hardware.org/?probe=e2d33f6c66) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| Gigabyte      | H110N-CF                    | Desktop     | [3a0b00c45d](https://linux-hardware.org/?probe=3a0b00c45d) | May 30, 2022 |
| System76      | Oryx Pro                    | Notebook    | [5f84134f5d](https://linux-hardware.org/?probe=5f84134f5d) | May 29, 2022 |
| Toshiba       | Satellite C675              | Notebook    | [72daf96a34](https://linux-hardware.org/?probe=72daf96a34) | May 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [7ca69b6206](https://linux-hardware.org/?probe=7ca69b6206) | May 28, 2022 |
| Biostar       | J3060NH                     | Desktop     | [2c67e6fc81](https://linux-hardware.org/?probe=2c67e6fc81) | May 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c025e27a90](https://linux-hardware.org/?probe=c025e27a90) | May 27, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [509fc21647](https://linux-hardware.org/?probe=509fc21647) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| Dell          | 0RY007                      | Desktop     | [2d0a227175](https://linux-hardware.org/?probe=2d0a227175) | May 26, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [4976553dfc](https://linux-hardware.org/?probe=4976553dfc) | May 25, 2022 |
| System76      | Oryx Pro                    | Notebook    | [2652ac64a4](https://linux-hardware.org/?probe=2652ac64a4) | May 25, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f4afc8ed1d](https://linux-hardware.org/?probe=f4afc8ed1d) | May 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6e5dd6f76f](https://linux-hardware.org/?probe=6e5dd6f76f) | May 25, 2022 |
| Lenovo        | ThinkPad L540 20AV0031GE    | Notebook    | [13f326fc7d](https://linux-hardware.org/?probe=13f326fc7d) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| HP            | 86EE                        | All in one  | [0870a9cf1a](https://linux-hardware.org/?probe=0870a9cf1a) | May 24, 2022 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [0c5e493177](https://linux-hardware.org/?probe=0c5e493177) | May 24, 2022 |
| LG Electro... | C500                        | Notebook    | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5c9c033d2f](https://linux-hardware.org/?probe=5c9c033d2f) | May 24, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [f451e1b307](https://linux-hardware.org/?probe=f451e1b307) | May 22, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1ca28a2fb](https://linux-hardware.org/?probe=d1ca28a2fb) | May 21, 2022 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [2fdd079ebc](https://linux-hardware.org/?probe=2fdd079ebc) | May 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Supermicro    | X12SPO-F                    | Server      | [1cdd61e1cc](https://linux-hardware.org/?probe=1cdd61e1cc) | May 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [1609781085](https://linux-hardware.org/?probe=1609781085) | May 20, 2022 |
| Supermicro    | X12SPO-F                    | Server      | [5b5ab34565](https://linux-hardware.org/?probe=5b5ab34565) | May 20, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [9410df7433](https://linux-hardware.org/?probe=9410df7433) | May 20, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [2f1ec161d1](https://linux-hardware.org/?probe=2f1ec161d1) | May 20, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [371eb0d1b7](https://linux-hardware.org/?probe=371eb0d1b7) | May 19, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [c3438d922b](https://linux-hardware.org/?probe=c3438d922b) | May 19, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Desktop     | [d29a88fa1f](https://linux-hardware.org/?probe=d29a88fa1f) | May 18, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Desktop     | [d87dcc4dff](https://linux-hardware.org/?probe=d87dcc4dff) | May 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [75ec4a948b](https://linux-hardware.org/?probe=75ec4a948b) | May 18, 2022 |
| HP            | 2B36                        | Desktop     | [390784f8e5](https://linux-hardware.org/?probe=390784f8e5) | May 15, 2022 |
| Lenovo        | ThinkPad T400 276521G       | Notebook    | [9a2f5118c5](https://linux-hardware.org/?probe=9a2f5118c5) | May 15, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [459e7e3586](https://linux-hardware.org/?probe=459e7e3586) | May 15, 2022 |
| HP            | Folio 13                    | Notebook    | [9c9cd2aa91](https://linux-hardware.org/?probe=9c9cd2aa91) | May 15, 2022 |
| Biostar       | J3060NH                     | Desktop     | [09900d1cf6](https://linux-hardware.org/?probe=09900d1cf6) | May 14, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d740686b5e](https://linux-hardware.org/?probe=d740686b5e) | May 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2342a9d519](https://linux-hardware.org/?probe=2342a9d519) | May 12, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2484d9989f](https://linux-hardware.org/?probe=2484d9989f) | May 12, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | Notebook    | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [d3088d7665](https://linux-hardware.org/?probe=d3088d7665) | May 11, 2022 |
| Acer          | Predator G3-605             | Desktop     | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [6a69aab6ee](https://linux-hardware.org/?probe=6a69aab6ee) | May 11, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [08deba5f5f](https://linux-hardware.org/?probe=08deba5f5f) | May 11, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [3780dc0fe5](https://linux-hardware.org/?probe=3780dc0fe5) | May 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [09d0c5a57c](https://linux-hardware.org/?probe=09d0c5a57c) | May 10, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [34a59f46c4](https://linux-hardware.org/?probe=34a59f46c4) | May 10, 2022 |
| Samsung       | 550XDA                      | Notebook    | [d3d7a64817](https://linux-hardware.org/?probe=d3d7a64817) | May 08, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [29c0818bcd](https://linux-hardware.org/?probe=29c0818bcd) | May 08, 2022 |
| Acer          | WMCP78M                     | Desktop     | [bb0d37a6b8](https://linux-hardware.org/?probe=bb0d37a6b8) | May 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [837a74d32f](https://linux-hardware.org/?probe=837a74d32f) | May 08, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a21e01fec5](https://linux-hardware.org/?probe=a21e01fec5) | May 07, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [eab46c9089](https://linux-hardware.org/?probe=eab46c9089) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [feaa2cb9fb](https://linux-hardware.org/?probe=feaa2cb9fb) | May 06, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [43b827546c](https://linux-hardware.org/?probe=43b827546c) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | Notebook    | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| Gigabyte      | GA-M55PLUS-S3G              | Desktop     | [ff948aad6c](https://linux-hardware.org/?probe=ff948aad6c) | May 05, 2022 |
| ASRock        | FM2A78M Pro4+               | Desktop     | [7a00557ba5](https://linux-hardware.org/?probe=7a00557ba5) | May 05, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [b007cf4ed2](https://linux-hardware.org/?probe=b007cf4ed2) | May 04, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [404c22feca](https://linux-hardware.org/?probe=404c22feca) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [744b50ab3b](https://linux-hardware.org/?probe=744b50ab3b) | May 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1f33fda19d](https://linux-hardware.org/?probe=1f33fda19d) | May 03, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [90aa5187ab](https://linux-hardware.org/?probe=90aa5187ab) | May 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [297dca51b9](https://linux-hardware.org/?probe=297dca51b9) | Apr 30, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3a7104d6b4](https://linux-hardware.org/?probe=3a7104d6b4) | Apr 29, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [6755ed2aa6](https://linux-hardware.org/?probe=6755ed2aa6) | Apr 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2514409f18](https://linux-hardware.org/?probe=2514409f18) | Apr 28, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [3b25bc9d0d](https://linux-hardware.org/?probe=3b25bc9d0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [833d1610d5](https://linux-hardware.org/?probe=833d1610d5) | Apr 25, 2022 |
| HP            | 2B47                        | Desktop     | [3805de3dc4](https://linux-hardware.org/?probe=3805de3dc4) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [cdc3ddaa2d](https://linux-hardware.org/?probe=cdc3ddaa2d) | Apr 22, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [aa1df63f27](https://linux-hardware.org/?probe=aa1df63f27) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4a4df2dc70](https://linux-hardware.org/?probe=4a4df2dc70) | Apr 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [0579e465d1](https://linux-hardware.org/?probe=0579e465d1) | Apr 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [e44ad7d84e](https://linux-hardware.org/?probe=e44ad7d84e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [9ba73648b1](https://linux-hardware.org/?probe=9ba73648b1) | Apr 16, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| Dell          | Latitude E7250              | Notebook    | [532fb04297](https://linux-hardware.org/?probe=532fb04297) | Apr 15, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [499a00bcf8](https://linux-hardware.org/?probe=499a00bcf8) | Apr 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [afe37cb756](https://linux-hardware.org/?probe=afe37cb756) | Apr 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a1e63550ab](https://linux-hardware.org/?probe=a1e63550ab) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | Notebook    | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b5375b9ffb](https://linux-hardware.org/?probe=b5375b9ffb) | Apr 13, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [7ce5e071a2](https://linux-hardware.org/?probe=7ce5e071a2) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4c52c99ee9](https://linux-hardware.org/?probe=4c52c99ee9) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [162850d6b3](https://linux-hardware.org/?probe=162850d6b3) | Apr 12, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [542c9c6703](https://linux-hardware.org/?probe=542c9c6703) | Apr 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [36b98241e2](https://linux-hardware.org/?probe=36b98241e2) | Apr 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [67750bdf0f](https://linux-hardware.org/?probe=67750bdf0f) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d03632cea9](https://linux-hardware.org/?probe=d03632cea9) | Apr 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [db52ca23d3](https://linux-hardware.org/?probe=db52ca23d3) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [7d87907153](https://linux-hardware.org/?probe=7d87907153) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [41fc926d28](https://linux-hardware.org/?probe=41fc926d28) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [586edef1b9](https://linux-hardware.org/?probe=586edef1b9) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [bb881ed0ee](https://linux-hardware.org/?probe=bb881ed0ee) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5370b9e906](https://linux-hardware.org/?probe=5370b9e906) | Apr 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4e232c446f](https://linux-hardware.org/?probe=4e232c446f) | Apr 06, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [30591629c3](https://linux-hardware.org/?probe=30591629c3) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [8181b0cd19](https://linux-hardware.org/?probe=8181b0cd19) | Apr 05, 2022 |
| Dell          | Latitude E6430              | Notebook    | [c974a805b2](https://linux-hardware.org/?probe=c974a805b2) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [dd1fef9175](https://linux-hardware.org/?probe=dd1fef9175) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [fe7fdad91b](https://linux-hardware.org/?probe=fe7fdad91b) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [a26b03795a](https://linux-hardware.org/?probe=a26b03795a) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [d467a8e89f](https://linux-hardware.org/?probe=d467a8e89f) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [5cfb35fb9e](https://linux-hardware.org/?probe=5cfb35fb9e) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [989843d8cf](https://linux-hardware.org/?probe=989843d8cf) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [2c39a577ac](https://linux-hardware.org/?probe=2c39a577ac) | Apr 04, 2022 |
| Dell          | Latitude 5421               | Notebook    | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Lenovo        | ThinkPad T480s 20L7001SG... | Notebook    | [440bfc13d9](https://linux-hardware.org/?probe=440bfc13d9) | Apr 03, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [5e530d1a32](https://linux-hardware.org/?probe=5e530d1a32) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Acer          | WMCP78M                     | Desktop     | [7c9d2a802f](https://linux-hardware.org/?probe=7c9d2a802f) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [35057588b4](https://linux-hardware.org/?probe=35057588b4) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [9050980874](https://linux-hardware.org/?probe=9050980874) | Apr 02, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a4228141cb](https://linux-hardware.org/?probe=a4228141cb) | Apr 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ea14bf201](https://linux-hardware.org/?probe=9ea14bf201) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| HPE           | ProLiant DL380 Gen10        | Server      | [5cdc7436c0](https://linux-hardware.org/?probe=5cdc7436c0) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | Desktop     | [f74de3797f](https://linux-hardware.org/?probe=f74de3797f) | Mar 31, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [44eafd5b02](https://linux-hardware.org/?probe=44eafd5b02) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8e7fc0aef9](https://linux-hardware.org/?probe=8e7fc0aef9) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [9a18c2ac1c](https://linux-hardware.org/?probe=9a18c2ac1c) | Mar 31, 2022 |
| Intel         | Unknown                     | Desktop     | [4689fbf7e1](https://linux-hardware.org/?probe=4689fbf7e1) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceae86aef1](https://linux-hardware.org/?probe=ceae86aef1) | Mar 30, 2022 |
| Acer          | Predator G3-710             | Desktop     | [d8d0331e9e](https://linux-hardware.org/?probe=d8d0331e9e) | Mar 30, 2022 |
| Lenovo        | B550 20053                  | Notebook    | [e3c65a5e44](https://linux-hardware.org/?probe=e3c65a5e44) | Mar 30, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [99de1a9e9d](https://linux-hardware.org/?probe=99de1a9e9d) | Mar 30, 2022 |
| Kanji         | Tamura MAX DUO              | Convertible | [1434c90e55](https://linux-hardware.org/?probe=1434c90e55) | Mar 30, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [e33537863b](https://linux-hardware.org/?probe=e33537863b) | Mar 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d72468b304](https://linux-hardware.org/?probe=d72468b304) | Mar 27, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [1f36f7eada](https://linux-hardware.org/?probe=1f36f7eada) | Mar 27, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a2bd44d0a4](https://linux-hardware.org/?probe=a2bd44d0a4) | Mar 25, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [170657280c](https://linux-hardware.org/?probe=170657280c) | Mar 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [98b597334b](https://linux-hardware.org/?probe=98b597334b) | Mar 25, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b128755fa4](https://linux-hardware.org/?probe=b128755fa4) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | Notebook    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [40f5402f5a](https://linux-hardware.org/?probe=40f5402f5a) | Mar 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [672496577e](https://linux-hardware.org/?probe=672496577e) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [92c8ac9161](https://linux-hardware.org/?probe=92c8ac9161) | Mar 21, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [2692e4dfd1](https://linux-hardware.org/?probe=2692e4dfd1) | Mar 18, 2022 |
| Unknown       | Intel X79                   | Desktop     | [1b92468c15](https://linux-hardware.org/?probe=1b92468c15) | Mar 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | Notebook    | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [fb8d2216a5](https://linux-hardware.org/?probe=fb8d2216a5) | Mar 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d0a87aedef](https://linux-hardware.org/?probe=d0a87aedef) | Mar 16, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [908e3fe366](https://linux-hardware.org/?probe=908e3fe366) | Mar 16, 2022 |
| ASRock        | Z87 Professional            | Desktop     | [e75eb7a802](https://linux-hardware.org/?probe=e75eb7a802) | Mar 15, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [13775d028d](https://linux-hardware.org/?probe=13775d028d) | Mar 15, 2022 |
| Dell          | Precision 7540              | Notebook    | [9d4662756c](https://linux-hardware.org/?probe=9d4662756c) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ed3d7239af](https://linux-hardware.org/?probe=ed3d7239af) | Mar 09, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d36e30fa5b](https://linux-hardware.org/?probe=d36e30fa5b) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Sony          | VPCEH25FM                   | Notebook    | [5a60a14cf4](https://linux-hardware.org/?probe=5a60a14cf4) | Mar 07, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [531e740b37](https://linux-hardware.org/?probe=531e740b37) | Mar 05, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d5ab693301](https://linux-hardware.org/?probe=d5ab693301) | Mar 05, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [2383184762](https://linux-hardware.org/?probe=2383184762) | Mar 05, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [1b45a09429](https://linux-hardware.org/?probe=1b45a09429) | Mar 03, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [45c8e5fea2](https://linux-hardware.org/?probe=45c8e5fea2) | Mar 01, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | Notebook    | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| Unknown       | Intel X79                   | Desktop     | [6a9245acd2](https://linux-hardware.org/?probe=6a9245acd2) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [759958a4b0](https://linux-hardware.org/?probe=759958a4b0) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a9bcae50d2](https://linux-hardware.org/?probe=a9bcae50d2) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [270aaf59b6](https://linux-hardware.org/?probe=270aaf59b6) | Feb 25, 2022 |
| Lenovo        | ThinkPad S430 68852BU       | Notebook    | [7d7bb498fe](https://linux-hardware.org/?probe=7d7bb498fe) | Feb 25, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [52bbb8515e](https://linux-hardware.org/?probe=52bbb8515e) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| Medion        | MS-7707                     | Desktop     | [2e4723aea4](https://linux-hardware.org/?probe=2e4723aea4) | Feb 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e24c41d802](https://linux-hardware.org/?probe=e24c41d802) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | K54L                        | Notebook    | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [3beffcfd3e](https://linux-hardware.org/?probe=3beffcfd3e) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [732c7ad77e](https://linux-hardware.org/?probe=732c7ad77e) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1982ff9621](https://linux-hardware.org/?probe=1982ff9621) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [35ac77d812](https://linux-hardware.org/?probe=35ac77d812) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1e8c363a67](https://linux-hardware.org/?probe=1e8c363a67) | Feb 16, 2022 |
| ASUSTek       | K53E                        | Notebook    | [929e5d8462](https://linux-hardware.org/?probe=929e5d8462) | Feb 15, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [046f5cdbd7](https://linux-hardware.org/?probe=046f5cdbd7) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [0ee015dd8e](https://linux-hardware.org/?probe=0ee015dd8e) | Feb 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| Lenovo        | ThinkPad R61/R61i 8934A7... | Notebook    | [e60d5e52f2](https://linux-hardware.org/?probe=e60d5e52f2) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [ca5c3f80ae](https://linux-hardware.org/?probe=ca5c3f80ae) | Feb 11, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [cb0abbfe2d](https://linux-hardware.org/?probe=cb0abbfe2d) | Feb 10, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [c50b098929](https://linux-hardware.org/?probe=c50b098929) | Feb 10, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [dbfb51d331](https://linux-hardware.org/?probe=dbfb51d331) | Feb 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [aa66dba98f](https://linux-hardware.org/?probe=aa66dba98f) | Feb 09, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | Notebook    | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| Compal        | PBL21                       | Notebook    | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [e6bc24c5b9](https://linux-hardware.org/?probe=e6bc24c5b9) | Feb 08, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [de476d2b5a](https://linux-hardware.org/?probe=de476d2b5a) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8a7cf7aca4](https://linux-hardware.org/?probe=8a7cf7aca4) | Feb 07, 2022 |
| Biostar       | J3060NH                     | Desktop     | [b34126597c](https://linux-hardware.org/?probe=b34126597c) | Feb 07, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [587efdf773](https://linux-hardware.org/?probe=587efdf773) | Feb 06, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [0785fcc2af](https://linux-hardware.org/?probe=0785fcc2af) | Feb 06, 2022 |
| Supermicro    | X11SAE-M                    | Server      | [ecb9ec0d34](https://linux-hardware.org/?probe=ecb9ec0d34) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6c3ac00f6a](https://linux-hardware.org/?probe=6c3ac00f6a) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b8aa657ab7](https://linux-hardware.org/?probe=b8aa657ab7) | Feb 05, 2022 |
| Dell          | Precision 5550              | Notebook    | [2853896d4c](https://linux-hardware.org/?probe=2853896d4c) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [f4a6341837](https://linux-hardware.org/?probe=f4a6341837) | Feb 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [655eea9ee5](https://linux-hardware.org/?probe=655eea9ee5) | Feb 02, 2022 |
| Notebook      | PA70ES                      | Notebook    | [794ffc9a83](https://linux-hardware.org/?probe=794ffc9a83) | Feb 02, 2022 |
| ASUSTek       | X750LN                      | Notebook    | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [1c3c43b4ce](https://linux-hardware.org/?probe=1c3c43b4ce) | Feb 02, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [f755eb7a78](https://linux-hardware.org/?probe=f755eb7a78) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [ccbf2ec4f5](https://linux-hardware.org/?probe=ccbf2ec4f5) | Jan 29, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d2ebf4698b](https://linux-hardware.org/?probe=d2ebf4698b) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [9a1fb4d53e](https://linux-hardware.org/?probe=9a1fb4d53e) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [1db87d66c6](https://linux-hardware.org/?probe=1db87d66c6) | Jan 28, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [1f9df11a59](https://linux-hardware.org/?probe=1f9df11a59) | Jan 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| HP            | 1998                        | Desktop     | [4ee1e4fcee](https://linux-hardware.org/?probe=4ee1e4fcee) | Jan 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS0QQ00    | Notebook    | [470cd66ae6](https://linux-hardware.org/?probe=470cd66ae6) | Jan 27, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [efe16c5921](https://linux-hardware.org/?probe=efe16c5921) | Jan 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [599ea5acd6](https://linux-hardware.org/?probe=599ea5acd6) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [0b57afd8bf](https://linux-hardware.org/?probe=0b57afd8bf) | Jan 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d8e76e70e8](https://linux-hardware.org/?probe=d8e76e70e8) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [a4172550fa](https://linux-hardware.org/?probe=a4172550fa) | Jan 26, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [dfe4dda46b](https://linux-hardware.org/?probe=dfe4dda46b) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| ASRock        | P75 Pro3                    | Desktop     | [76bb99305c](https://linux-hardware.org/?probe=76bb99305c) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [269d1509c2](https://linux-hardware.org/?probe=269d1509c2) | Jan 24, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [2dbb65e1bc](https://linux-hardware.org/?probe=2dbb65e1bc) | Jan 24, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a2ed61ffcd](https://linux-hardware.org/?probe=a2ed61ffcd) | Jan 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [22757e0dd9](https://linux-hardware.org/?probe=22757e0dd9) | Jan 23, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [2ce129a03e](https://linux-hardware.org/?probe=2ce129a03e) | Jan 23, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [0d9f79bb17](https://linux-hardware.org/?probe=0d9f79bb17) | Jan 23, 2022 |
| Unknown       | Intel X79                   | Desktop     | [7d1ab99839](https://linux-hardware.org/?probe=7d1ab99839) | Jan 23, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [299f1c8cca](https://linux-hardware.org/?probe=299f1c8cca) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | Notebook    | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Standard      | MB50II                      | Notebook    | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | Notebook    | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [09347426df](https://linux-hardware.org/?probe=09347426df) | Jan 20, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [3bc52b8340](https://linux-hardware.org/?probe=3bc52b8340) | Jan 19, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [2a4100e03c](https://linux-hardware.org/?probe=2a4100e03c) | Jan 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0287de904c](https://linux-hardware.org/?probe=0287de904c) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [03aa6d19c1](https://linux-hardware.org/?probe=03aa6d19c1) | Jan 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [30edae47a1](https://linux-hardware.org/?probe=30edae47a1) | Jan 17, 2022 |
| Dell          | Latitude 7480               | Notebook    | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [b123404920](https://linux-hardware.org/?probe=b123404920) | Jan 17, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [5343777492](https://linux-hardware.org/?probe=5343777492) | Jan 16, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9324cf10f9](https://linux-hardware.org/?probe=9324cf10f9) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f87a30cc1b](https://linux-hardware.org/?probe=f87a30cc1b) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7e3aee849](https://linux-hardware.org/?probe=a7e3aee849) | Jan 15, 2022 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| HP            | 83E0                        | Desktop     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [968c8c3b82](https://linux-hardware.org/?probe=968c8c3b82) | Jan 11, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [3ac159be99](https://linux-hardware.org/?probe=3ac159be99) | Jan 10, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [f8400f7913](https://linux-hardware.org/?probe=f8400f7913) | Jan 09, 2022 |
| Dell          | 05CNYF A01                  | Desktop     | [c197ba435d](https://linux-hardware.org/?probe=c197ba435d) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [37d39e8efe](https://linux-hardware.org/?probe=37d39e8efe) | Jan 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [ad8e8b92cb](https://linux-hardware.org/?probe=ad8e8b92cb) | Jan 08, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [4026f1e18c](https://linux-hardware.org/?probe=4026f1e18c) | Jan 08, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [2e21ca6670](https://linux-hardware.org/?probe=2e21ca6670) | Jan 08, 2022 |
| Acer          | Extensa 5620                | Notebook    | [a10369e225](https://linux-hardware.org/?probe=a10369e225) | Jan 08, 2022 |
| Sony          | VPCEB2B4E                   | Notebook    | [4d3b6ede0c](https://linux-hardware.org/?probe=4d3b6ede0c) | Jan 08, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [c56817a778](https://linux-hardware.org/?probe=c56817a778) | Jan 08, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5cec5778a0](https://linux-hardware.org/?probe=5cec5778a0) | Jan 06, 2022 |
| Lenovo        | ThinkPad T420 4180AJ3       | Notebook    | [d744cfb251](https://linux-hardware.org/?probe=d744cfb251) | Jan 06, 2022 |
| HP            | 82F2 A01                    | Desktop     | [416ee28a87](https://linux-hardware.org/?probe=416ee28a87) | Jan 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e2753ebd08](https://linux-hardware.org/?probe=e2753ebd08) | Jan 04, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [e913dca33e](https://linux-hardware.org/?probe=e913dca33e) | Jan 04, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [fe5ca696c8](https://linux-hardware.org/?probe=fe5ca696c8) | Jan 04, 2022 |
| Monster       | ABRA A5 V11.1               | Notebook    | [0cc6ec8af7](https://linux-hardware.org/?probe=0cc6ec8af7) | Jan 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3383929020](https://linux-hardware.org/?probe=3383929020) | Jan 03, 2022 |
| VS Company    | MCP61M                      | Desktop     | [8009a6fbdf](https://linux-hardware.org/?probe=8009a6fbdf) | Jan 02, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [14ca887c8f](https://linux-hardware.org/?probe=14ca887c8f) | Jan 02, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [23110f625c](https://linux-hardware.org/?probe=23110f625c) | Dec 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [98ed791fc8](https://linux-hardware.org/?probe=98ed791fc8) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3e3a3df7ce](https://linux-hardware.org/?probe=3e3a3df7ce) | Dec 31, 2021 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [46c8424272](https://linux-hardware.org/?probe=46c8424272) | Dec 31, 2021 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [0cf80c2ee3](https://linux-hardware.org/?probe=0cf80c2ee3) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [1bd919981a](https://linux-hardware.org/?probe=1bd919981a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS80M0C    | Notebook    | [dfdcb1f759](https://linux-hardware.org/?probe=dfdcb1f759) | Dec 29, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7376dd6793](https://linux-hardware.org/?probe=7376dd6793) | Dec 29, 2021 |
| Acer          | Nitro AN715-51              | Notebook    | [c3caffed3c](https://linux-hardware.org/?probe=c3caffed3c) | Dec 29, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [4a1c70f95f](https://linux-hardware.org/?probe=4a1c70f95f) | Dec 28, 2021 |
| Dell          | Latitude E4310              | Notebook    | [8b6976bdd2](https://linux-hardware.org/?probe=8b6976bdd2) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34c9874e50](https://linux-hardware.org/?probe=34c9874e50) | Dec 27, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | Notebook    | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [54774d551c](https://linux-hardware.org/?probe=54774d551c) | Dec 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [9cb5033472](https://linux-hardware.org/?probe=9cb5033472) | Dec 26, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [685afb1399](https://linux-hardware.org/?probe=685afb1399) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [00b9630631](https://linux-hardware.org/?probe=00b9630631) | Dec 24, 2021 |
| MSI           | MS-AA1511                   | All in one  | [ef477f6784](https://linux-hardware.org/?probe=ef477f6784) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d971e22ea1](https://linux-hardware.org/?probe=d971e22ea1) | Dec 24, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Dell          | Latitude E4310              | Notebook    | [e5b46c1542](https://linux-hardware.org/?probe=e5b46c1542) | Dec 24, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [b5cd12bc15](https://linux-hardware.org/?probe=b5cd12bc15) | Dec 24, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [ed79d730cd](https://linux-hardware.org/?probe=ed79d730cd) | Dec 24, 2021 |
| ASUSTek       | X450LD                      | Notebook    | [b5e36a24f9](https://linux-hardware.org/?probe=b5e36a24f9) | Dec 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [0c879745b1](https://linux-hardware.org/?probe=0c879745b1) | Dec 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [82a81d9287](https://linux-hardware.org/?probe=82a81d9287) | Dec 24, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [3b01d877ce](https://linux-hardware.org/?probe=3b01d877ce) | Dec 24, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [af10afb79b](https://linux-hardware.org/?probe=af10afb79b) | Dec 23, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [9bd5592765](https://linux-hardware.org/?probe=9bd5592765) | Dec 23, 2021 |
| Medion        | E4213 MD99329               | Notebook    | [8801cfdb2a](https://linux-hardware.org/?probe=8801cfdb2a) | Dec 23, 2021 |
| Teclast       | F15S                        | Notebook    | [8be33fb7e2](https://linux-hardware.org/?probe=8be33fb7e2) | Dec 23, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [9bcfc1e034](https://linux-hardware.org/?probe=9bcfc1e034) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a54f9967ef](https://linux-hardware.org/?probe=a54f9967ef) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2ca39a2067](https://linux-hardware.org/?probe=2ca39a2067) | Dec 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b73f1f9cb1](https://linux-hardware.org/?probe=b73f1f9cb1) | Dec 23, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [870a0913ee](https://linux-hardware.org/?probe=870a0913ee) | Dec 23, 2021 |
| Dell          | Latitude 3410               | Notebook    | [a0b79031ae](https://linux-hardware.org/?probe=a0b79031ae) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d00c0b2ded](https://linux-hardware.org/?probe=d00c0b2ded) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | Notebook    | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| SYWZ          | S210H Series                | Desktop     | [df3edf9f7b](https://linux-hardware.org/?probe=df3edf9f7b) | Dec 21, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8b33da2ce4](https://linux-hardware.org/?probe=8b33da2ce4) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [c349552561](https://linux-hardware.org/?probe=c349552561) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [de9ccde374](https://linux-hardware.org/?probe=de9ccde374) | Dec 18, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [55e4486324](https://linux-hardware.org/?probe=55e4486324) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bee0b80356](https://linux-hardware.org/?probe=bee0b80356) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bc4e465833](https://linux-hardware.org/?probe=bc4e465833) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [9bd0a6e07d](https://linux-hardware.org/?probe=9bd0a6e07d) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [702be0b615](https://linux-hardware.org/?probe=702be0b615) | Dec 17, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [60d68b4c13](https://linux-hardware.org/?probe=60d68b4c13) | Dec 17, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [14ffa86838](https://linux-hardware.org/?probe=14ffa86838) | Dec 17, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [082bd4283a](https://linux-hardware.org/?probe=082bd4283a) | Dec 16, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8b9e71b388](https://linux-hardware.org/?probe=8b9e71b388) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [f9f891f9b2](https://linux-hardware.org/?probe=f9f891f9b2) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2633be8cd](https://linux-hardware.org/?probe=e2633be8cd) | Dec 16, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [9cb226408e](https://linux-hardware.org/?probe=9cb226408e) | Dec 15, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | Notebook    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |

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
| ArcoLinux Rolling     | 1350      | 89.05%  |
| ArcoLinux             | 118       | 7.78%   |
| ArcoLinux 20.6.5      | 11        | 0.73%   |
| ArcoLinux 20.7.5      | 8         | 0.53%   |
| ArcoLinux 20.3.4      | 4         | 0.26%   |
| ArcoLinux 20.3.3      | 3         | 0.2%    |
| ArcoLinux 20.2.12     | 3         | 0.2%    |
| ArcoLinux 19.12.15    | 3         | 0.2%    |
| ArcoLinux 19.07.11    | 3         | 0.2%    |
| ArcoLinux 20.1.4      | 2         | 0.13%   |
| ArcoLinux 19.02.4     | 2         | 0.13%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.07%   |
| ArcoLinux 6.9.2       | 1         | 0.07%   |
| ArcoLinux 6.9.1       | 1         | 0.07%   |
| ArcoLinux 20.5.7      | 1         | 0.07%   |
| ArcoLinux 20.5.2      | 1         | 0.07%   |
| ArcoLinux 20.4.11     | 1         | 0.07%   |
| ArcoLinux 20.2.9      | 1         | 0.07%   |
| ArcoLinux 19.11.3     | 1         | 0.07%   |
| ArcoLinux 19.03.3     | 1         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 1506      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.7-arch1-1    | 48        | 2.68%   |
| 5.15.10-arch1-1   | 39        | 2.17%   |
| 5.13.13-arch1-1   | 38        | 2.12%   |
| 5.14.14-arch1-1   | 26        | 1.45%   |
| 5.16.11-arch1-1   | 25        | 1.39%   |
| 5.13.12-arch1-1   | 22        | 1.23%   |
| 5.14.12-arch1-1   | 21        | 1.17%   |
| 5.17.1-arch1-1    | 18        | 1%      |
| 5.8.14-arch1-1    | 16        | 0.89%   |
| 5.12.13-arch1-2   | 16        | 0.89%   |
| 5.9.14-arch1-1    | 15        | 0.84%   |
| 5.19.13-arch1-1   | 15        | 0.84%   |
| 5.16.2-arch1-1    | 15        | 0.84%   |
| 5.12.15-arch1-1   | 15        | 0.84%   |
| 6.0.8-arch1-1     | 14        | 0.78%   |
| 5.15.5-arch1-1    | 14        | 0.78%   |
| 5.15.11-arch2-1   | 14        | 0.78%   |
| 5.9.8-arch1-1     | 13        | 0.72%   |
| 5.15.4-arch1-1    | 13        | 0.72%   |
| 5.12.12-arch1-1   | 13        | 0.72%   |
| 6.0.2-arch1-1     | 12        | 0.67%   |
| 6.0.12-arch1-1    | 12        | 0.67%   |
| 5.9.1-arch1-1     | 12        | 0.67%   |
| 5.17.9-arch1-1    | 12        | 0.67%   |
| 5.17.5-arch1-1    | 12        | 0.67%   |
| 5.15.2-arch1-1    | 12        | 0.67%   |
| 5.12.10-arch1-1   | 12        | 0.67%   |
| 5.10.84-1-lts     | 12        | 0.67%   |
| 6.0.10-arch2-1    | 11        | 0.61%   |
| 5.9.6-arch1-1     | 11        | 0.61%   |
| 5.17.4-arch1-1    | 11        | 0.61%   |
| 5.16.16-arch1-1   | 11        | 0.61%   |
| 5.16.10-arch1-1   | 11        | 0.61%   |
| 5.14.6-arch1-1    | 11        | 0.61%   |
| 5.12.14-arch1-1   | 11        | 0.61%   |
| 5.9.10-arch1-1    | 10        | 0.56%   |
| 5.18.3-arch1-1    | 10        | 0.56%   |
| 5.18.16-arch1-1   | 10        | 0.56%   |
| 5.15.7-zen1-1-zen | 10        | 0.56%   |
| 5.15.6-arch2-1    | 10        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.7  | 59        | 3.29%   |
| 5.15.10 | 41        | 2.29%   |
| 5.13.13 | 38        | 2.12%   |
| 5.16.11 | 28        | 1.56%   |
| 5.14.14 | 26        | 1.45%   |
| 5.17.1  | 25        | 1.39%   |
| 6.0.2   | 24        | 1.34%   |
| 5.14.12 | 24        | 1.34%   |
| 5.13.12 | 24        | 1.34%   |
| 6.0.8   | 19        | 1.06%   |
| 5.9.14  | 19        | 1.06%   |
| 5.16.2  | 19        | 1.06%   |
| 5.9.8   | 18        | 1%      |
| 5.17.5  | 18        | 1%      |
| 5.15.4  | 18        | 1%      |
| 5.12.15 | 18        | 1%      |
| 5.12.13 | 18        | 1%      |
| 5.8.14  | 17        | 0.95%   |
| 5.9.6   | 16        | 0.89%   |
| 5.15.5  | 16        | 0.89%   |
| 6.1.1   | 15        | 0.84%   |
| 5.9.1   | 15        | 0.84%   |
| 5.19.13 | 15        | 0.84%   |
| 5.15.11 | 15        | 0.84%   |
| 6.0.12  | 14        | 0.78%   |
| 5.15.2  | 14        | 0.78%   |
| 5.12.12 | 14        | 0.78%   |
| 6.0.10  | 13        | 0.72%   |
| 5.17.9  | 13        | 0.72%   |
| 5.16.16 | 13        | 0.72%   |
| 5.15.6  | 13        | 0.72%   |
| 5.14.9  | 13        | 0.72%   |
| 6.0.1   | 12        | 0.67%   |
| 5.9.10  | 12        | 0.67%   |
| 5.16.10 | 12        | 0.67%   |
| 5.15.12 | 12        | 0.67%   |
| 5.14.6  | 12        | 0.67%   |
| 5.12.10 | 12        | 0.67%   |
| 5.10.84 | 12        | 0.67%   |
| 5.10.16 | 12        | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 294       | 17.01%  |
| 5.10    | 213       | 12.33%  |
| 5.16    | 132       | 7.64%   |
| 5.14    | 131       | 7.58%   |
| 6.0     | 117       | 6.77%   |
| 5.13    | 110       | 6.37%   |
| 5.9     | 109       | 6.31%   |
| 5.12    | 107       | 6.19%   |
| 5.17    | 92        | 5.32%   |
| 5.18    | 87        | 5.03%   |
| 5.11    | 77        | 4.46%   |
| 5.19    | 72        | 4.17%   |
| 6.1     | 63        | 3.65%   |
| 5.4     | 60        | 3.47%   |
| 5.8     | 34        | 1.97%   |
| 5.6     | 7         | 0.41%   |
| 5.7     | 6         | 0.35%   |
| 5.5     | 5         | 0.29%   |
| 5.3     | 3         | 0.17%   |
| 5.0     | 3         | 0.17%   |
| 4.19    | 2         | 0.12%   |
| 5.2     | 1         | 0.06%   |
| 4.20    | 1         | 0.06%   |
| 4.18    | 1         | 0.06%   |
| 4.17    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1506      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 524       | 32.89%  |
| KDE5           | 291       | 18.27%  |
| i3             | 112       | 7.03%   |
| GNOME          | 99        | 6.21%   |
| awesome        | 99        | 6.21%   |
| qtile          | 67        | 4.21%   |
| X-Cinnamon     | 55        | 3.45%   |
| bspwm          | 53        | 3.33%   |
| xmonad         | 48        | 3.01%   |
| dwm            | 42        | 2.64%   |
| LeftWM         | 27        | 1.69%   |
| KDE            | 25        | 1.57%   |
| Unknown        | 25        | 1.57%   |
| Deepin         | 19        | 1.19%   |
| LXQt           | 15        | 0.94%   |
| Cinnamon       | 14        | 0.88%   |
| MATE           | 13        | 0.82%   |
| Budgie         | 12        | 0.75%   |
| herbstluftwm   | 10        | 0.63%   |
| i3-with-shmlog | 9         | 0.56%   |
| Hyprland       | 4         | 0.25%   |
| Cutefish       | 4         | 0.25%   |
| chadwm         | 4         | 0.25%   |
| Unity          | 3         | 0.19%   |
| sway           | 3         | 0.19%   |
| spectrwm       | 3         | 0.19%   |
| ICEWM          | 3         | 0.19%   |
| cwm            | 3         | 0.19%   |
| openbox        | 2         | 0.13%   |
| dusk           | 2         | 0.13%   |
| jwm            | 1         | 0.06%   |
| GNOME Classic  | 1         | 0.06%   |
| dwm-sc         | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1382      | 91.04%  |
| Tty     | 86        | 5.67%   |
| Wayland | 39        | 2.57%   |
| Unknown | 11        | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 833       | 52.26%  |
| TDM     | 295       | 18.51%  |
| LightDM | 270       | 16.94%  |
| Unknown | 158       | 9.91%   |
| GDM     | 29        | 1.82%   |
| Ly      | 6         | 0.38%   |
| XDM     | 1         | 0.06%   |
| SLiM    | 1         | 0.06%   |
| LXDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 882       | 57.72%  |
| en_GB   | 130       | 8.51%   |
| de_DE   | 74        | 4.84%   |
| en_CA   | 50        | 3.27%   |
| en_IN   | 37        | 2.42%   |
| fr_FR   | 31        | 2.03%   |
| en_AU   | 31        | 2.03%   |
| ru_RU   | 24        | 1.57%   |
| es_ES   | 22        | 1.44%   |
| pt_BR   | 18        | 1.18%   |
| pl_PL   | 16        | 1.05%   |
| Unknown | 14        | 0.92%   |
| es_AR   | 12        | 0.79%   |
| hu_HU   | 11        | 0.72%   |
| en_ZA   | 11        | 0.72%   |
| it_IT   | 10        | 0.65%   |
| sv_SE   | 9         | 0.59%   |
| C       | 9         | 0.59%   |
| tr_TR   | 8         | 0.52%   |
| nl_NL   | 7         | 0.46%   |
| es_MX   | 7         | 0.46%   |
| pt_PT   | 6         | 0.39%   |
| fi_FI   | 6         | 0.39%   |
| en_IL   | 6         | 0.39%   |
| en_IE   | 6         | 0.39%   |
| ru_UA   | 5         | 0.33%   |
| nl_BE   | 5         | 0.33%   |
| fr_CA   | 5         | 0.33%   |
| en_SG   | 5         | 0.33%   |
| en_DK   | 5         | 0.33%   |
| de_CH   | 5         | 0.33%   |
| ja_JP   | 4         | 0.26%   |
| es_CO   | 4         | 0.26%   |
| en_PH   | 4         | 0.26%   |
| de_AT   | 4         | 0.26%   |
| zh_CN   | 3         | 0.2%    |
| es_CL   | 3         | 0.2%    |
| en_NZ   | 3         | 0.2%    |
| en_AG   | 3         | 0.2%    |
| el_GR   | 3         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1081      | 71.12%  |
| BIOS | 439       | 28.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1143      | 74.32%  |
| Btrfs    | 283       | 18.4%   |
| Overlay  | 70        | 4.55%   |
| Xfs      | 20        | 1.3%    |
| F2fs     | 10        | 0.65%   |
| Unknown  | 8         | 0.52%   |
| Jfs      | 2         | 0.13%   |
| Tmpfs    | 1         | 0.07%   |
| Reiserfs | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1145      | 75.08%  |
| MBR     | 232       | 15.21%  |
| Unknown | 148       | 9.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1151      | 74.26%  |
| Yes       | 399       | 25.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 904       | 59.43%  |
| Yes       | 617       | 40.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 294       | 19.52%  |
| Lenovo              | 260       | 17.26%  |
| Dell                | 167       | 11.09%  |
| Hewlett-Packard     | 160       | 10.62%  |
| Gigabyte Technology | 125       | 8.3%    |
| MSI                 | 118       | 7.84%   |
| Acer                | 63        | 4.18%   |
| ASRock              | 60        | 3.98%   |
| Apple               | 43        | 2.86%   |
| Supermicro          | 18        | 1.2%    |
| Toshiba             | 17        | 1.13%   |
| Intel               | 12        | 0.8%    |
| Unknown             | 12        | 0.8%    |
| Sony                | 10        | 0.66%   |
| Samsung Electronics | 10        | 0.66%   |
| System76            | 9         | 0.6%    |
| Medion              | 9         | 0.6%    |
| HUAWEI              | 9         | 0.6%    |
| Alienware           | 9         | 0.6%    |
| Fujitsu             | 8         | 0.53%   |
| Timi                | 7         | 0.46%   |
| Razer               | 7         | 0.46%   |
| Notebook            | 6         | 0.4%    |
| TUXEDO              | 5         | 0.33%   |
| Pegatron            | 4         | 0.27%   |
| Chuwi               | 4         | 0.27%   |
| Schenker            | 3         | 0.2%    |
| Packard Bell        | 3         | 0.2%    |
| Foxconn             | 3         | 0.2%    |
| Casper              | 3         | 0.2%    |
| AZW                 | 3         | 0.2%    |
| ZOTAC               | 2         | 0.13%   |
| Teclast             | 2         | 0.13%   |
| Shuttle             | 2         | 0.13%   |
| Microsoft           | 2         | 0.13%   |
| LG Electronics      | 2         | 0.13%   |
| Biostar             | 2         | 0.13%   |
| Xplore              | 1         | 0.07%   |
| VS Company          | 1         | 0.07%   |
| UNITCOM             | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 16        | 1.06%   |
| ASUS TUF Gaming X570-PLUS        | 15        | 1%      |
| ASUS All Series                  | 13        | 0.86%   |
| Supermicro SYS-5019A-FTN4        | 10        | 0.66%   |
| ASUS ROG STRIX B550-F GAMING     | 10        | 0.66%   |
| MSI MS-7C37                      | 8         | 0.53%   |
| MSI MS-7C91                      | 7         | 0.46%   |
| ASUS PRIME X570-P                | 7         | 0.46%   |
| ASUS PRIME X470-PRO              | 7         | 0.46%   |
| MSI MS-7B89                      | 6         | 0.4%    |
| MSI MS-7B79                      | 6         | 0.4%    |
| HP Pavilion Notebook             | 6         | 0.4%    |
| MSI MS-7971                      | 5         | 0.33%   |
| HP Notebook                      | 5         | 0.33%   |
| Gigabyte X570 AORUS PRO WIFI     | 5         | 0.33%   |
| Gigabyte X570 AORUS MASTER       | 5         | 0.33%   |
| ASUS PRIME B450M-A               | 5         | 0.33%   |
| ASUS PRIME A320M-K               | 5         | 0.33%   |
| Razer Blade                      | 4         | 0.27%   |
| MSI MS-7C95                      | 4         | 0.27%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ | 4         | 0.27%   |
| HP EliteBook 840 G3              | 4         | 0.27%   |
| Dell XPS 15 9570                 | 4         | 0.27%   |
| Dell OptiPlex 7010               | 4         | 0.27%   |
| ASUS Z170 PRO GAMING             | 4         | 0.27%   |
| ASUS STRIX Z270H GAMING          | 4         | 0.27%   |
| ASUS ROG CROSSHAIR VIII HERO     | 4         | 0.27%   |
| ASRock B450M Pro4                | 4         | 0.27%   |
| Timi TM1607                      | 3         | 0.2%    |
| MSI MS-7B98                      | 3         | 0.2%    |
| MSI MS-7B86                      | 3         | 0.2%    |
| MSI MS-7B85                      | 3         | 0.2%    |
| MSI MS-7A38                      | 3         | 0.2%    |
| MSI MS-7817                      | 3         | 0.2%    |
| Lenovo Legion Y540-15IRH 81SX    | 3         | 0.2%    |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 0.2%    |
| Lenovo IdeaPad 5 14ARE05 81YM    | 3         | 0.2%    |
| Lenovo IdeaPad 320-15ISK 80XH    | 3         | 0.2%    |
| HUAWEI KLVL-WXX9                 | 3         | 0.2%    |
| HP ProDesk 600 G1 SFF            | 3         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 127       | 8.43%   |
| Lenovo IdeaPad            | 50        | 3.32%   |
| Dell Inspiron             | 49        | 3.25%   |
| ASUS ROG                  | 49        | 3.25%   |
| ASUS PRIME                | 49        | 3.25%   |
| Dell Latitude             | 42        | 2.79%   |
| Acer Aspire               | 41        | 2.72%   |
| ASUS TUF                  | 38        | 2.52%   |
| Dell XPS                  | 26        | 1.73%   |
| HP Pavilion               | 25        | 1.66%   |
| HP EliteBook              | 22        | 1.46%   |
| ASUS VivoBook             | 22        | 1.46%   |
| Lenovo Legion             | 21        | 1.39%   |
| HP Laptop                 | 21        | 1.39%   |
| Dell OptiPlex             | 21        | 1.39%   |
| Gigabyte X570             | 17        | 1.13%   |
| HP ENVY                   | 16        | 1.06%   |
| Unknown                   | 16        | 1.06%   |
| Toshiba Satellite         | 14        | 0.93%   |
| Lenovo Yoga               | 14        | 0.93%   |
| Dell Precision            | 14        | 0.93%   |
| ASUS All                  | 13        | 0.86%   |
| Lenovo ThinkCentre        | 11        | 0.73%   |
| Dell Vostro               | 11        | 0.73%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.66%   |
| Gigabyte B450             | 9         | 0.6%    |
| MSI MS-7C37               | 8         | 0.53%   |
| HP EliteDesk              | 8         | 0.53%   |
| Gigabyte B450M            | 8         | 0.53%   |
| ASUS P8Z77-V              | 8         | 0.53%   |
| Apple MacBookPro11        | 8         | 0.53%   |
| Acer Nitro                | 8         | 0.53%   |
| Razer Blade               | 7         | 0.46%   |
| MSI MS-7C91               | 7         | 0.46%   |
| HP ProBook                | 7         | 0.46%   |
| HP Compaq                 | 7         | 0.46%   |
| Fujitsu LIFEBOOK          | 7         | 0.46%   |
| ASUS STRIX                | 7         | 0.46%   |
| ASRock B450M              | 7         | 0.46%   |
| MSI MS-7B89               | 6         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 215       | 14.28%  |
| 2020    | 195       | 12.95%  |
| 2018    | 192       | 12.75%  |
| 2017    | 140       | 9.3%    |
| 2021    | 105       | 6.97%   |
| 2013    | 100       | 6.64%   |
| 2016    | 94        | 6.24%   |
| 2015    | 90        | 5.98%   |
| 2011    | 90        | 5.98%   |
| 2012    | 84        | 5.58%   |
| 2014    | 66        | 4.38%   |
| 2010    | 61        | 4.05%   |
| 2009    | 26        | 1.73%   |
| 2008    | 18        | 1.2%    |
| 2022    | 14        | 0.93%   |
| 2007    | 9         | 0.6%    |
| 2006    | 5         | 0.33%   |
| 2005    | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 785       | 52.12%  |
| Desktop     | 648       | 43.03%  |
| Convertible | 34        | 2.26%   |
| All in one  | 16        | 1.06%   |
| Mini pc     | 13        | 0.86%   |
| Server      | 5         | 0.33%   |
| Tablet      | 4         | 0.27%   |
| Stick pc    | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1506      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1501      | 99.67%  |
| Yes  | 5         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 411       | 26.99%  |
| 4.01-8.0    | 347       | 22.78%  |
| 8.01-16.0   | 270       | 17.73%  |
| 32.01-64.0  | 235       | 15.43%  |
| 3.01-4.0    | 147       | 9.65%   |
| 64.01-256.0 | 53        | 3.48%   |
| 24.01-32.0  | 35        | 2.3%    |
| 1.01-2.0    | 17        | 1.12%   |
| 2.01-3.0    | 7         | 0.46%   |
| Unknown     | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 499       | 29.76%  |
| 2.01-3.0   | 417       | 24.87%  |
| 4.01-8.0   | 262       | 15.62%  |
| 3.01-4.0   | 233       | 13.89%  |
| 0.51-1.0   | 155       | 9.24%   |
| 8.01-16.0  | 74        | 4.41%   |
| 0.01-0.5   | 27        | 1.61%   |
| 16.01-24.0 | 8         | 0.48%   |
| 24.01-32.0 | 1         | 0.06%   |
| Unknown    | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 714       | 45.89%  |
| 2      | 451       | 28.98%  |
| 3      | 186       | 11.95%  |
| 4      | 108       | 6.94%   |
| 5      | 54        | 3.47%   |
| 6      | 19        | 1.22%   |
| 7      | 9         | 0.58%   |
| 0      | 6         | 0.39%   |
| 9      | 4         | 0.26%   |
| 8      | 3         | 0.19%   |
| 11     | 1         | 0.06%   |
| 10     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1083      | 71.44%  |
| Yes       | 433       | 28.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1334      | 88.34%  |
| No        | 176       | 11.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1140      | 75.55%  |
| No        | 369       | 24.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1017      | 66.56%  |
| No        | 511       | 33.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 338       | 22.34%  |
| Germany      | 114       | 7.53%   |
| UK           | 88        | 5.82%   |
| Canada       | 67        | 4.43%   |
| India        | 59        | 3.9%    |
| France       | 45        | 2.97%   |
| Brazil       | 40        | 2.64%   |
| Belgium      | 36        | 2.38%   |
| Russia       | 35        | 2.31%   |
| Spain        | 34        | 2.25%   |
| Netherlands  | 34        | 2.25%   |
| Australia    | 33        | 2.18%   |
| Italy        | 29        | 1.92%   |
| Poland       | 28        | 1.85%   |
| Sweden       | 25        | 1.65%   |
| Turkey       | 24        | 1.59%   |
| Switzerland  | 23        | 1.52%   |
| Hungary      | 21        | 1.39%   |
| Argentina    | 20        | 1.32%   |
| Romania      | 19        | 1.26%   |
| Mexico       | 17        | 1.12%   |
| Ukraine      | 16        | 1.06%   |
| Norway       | 16        | 1.06%   |
| Portugal     | 15        | 0.99%   |
| Finland      | 15        | 0.99%   |
| Indonesia    | 14        | 0.93%   |
| Greece       | 14        | 0.93%   |
| Bulgaria     | 13        | 0.86%   |
| South Africa | 12        | 0.79%   |
| Colombia     | 12        | 0.79%   |
| Ireland      | 11        | 0.73%   |
| Austria      | 11        | 0.73%   |
| Bangladesh   | 10        | 0.66%   |
| Egypt        | 9         | 0.59%   |
| Czechia      | 9         | 0.59%   |
| Malaysia     | 8         | 0.53%   |
| Japan        | 8         | 0.53%   |
| Denmark      | 8         | 0.53%   |
| Slovenia     | 7         | 0.46%   |
| Serbia       | 7         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sydney            | 17        | 1.07%   |
| Durham            | 17        | 1.07%   |
| Berlin            | 15        | 0.95%   |
| Moscow            | 11        | 0.7%    |
| Madrid            | 11        | 0.7%    |
| Lier              | 10        | 0.63%   |
| Paris             | 9         | 0.57%   |
| Houston           | 9         | 0.57%   |
| Warsaw            | 8         | 0.51%   |
| Vienna            | 8         | 0.51%   |
| Pune              | 8         | 0.51%   |
| London            | 8         | 0.51%   |
| Budapest          | 8         | 0.51%   |
| Amsterdam         | 8         | 0.51%   |
| Zurich            | 7         | 0.44%   |
| Toronto           | 7         | 0.44%   |
| Sofia             | 7         | 0.44%   |
| Sao Paulo         | 7         | 0.44%   |
| Portland          | 7         | 0.44%   |
| Helsinki          | 7         | 0.44%   |
| Frankfurt am Main | 7         | 0.44%   |
| Athens            | 7         | 0.44%   |
| Wilrijk           | 6         | 0.38%   |
| Tallinn           | 6         | 0.38%   |
| Milan             | 6         | 0.38%   |
| Istanbul          | 6         | 0.38%   |
| Dublin            | 6         | 0.38%   |
| Chicago           | 6         | 0.38%   |
| Central           | 6         | 0.38%   |
| Bucharest         | 6         | 0.38%   |
| Brooklyn          | 6         | 0.38%   |
| Brisbane          | 6         | 0.38%   |
| Bogotá           | 6         | 0.38%   |
| Bengaluru         | 6         | 0.38%   |
| Ankara            | 6         | 0.38%   |
| Stockholm         | 5         | 0.32%   |
| Seville           | 5         | 0.32%   |
| Rio de Janeiro    | 5         | 0.32%   |
| Oslo              | 5         | 0.32%   |
| New York          | 5         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 479       | 794    | 18.54%  |
| WDC                         | 418       | 669    | 16.18%  |
| Seagate                     | 352       | 518    | 13.63%  |
| Toshiba                     | 165       | 209    | 6.39%   |
| Kingston                    | 135       | 178    | 5.23%   |
| SanDisk                     | 120       | 142    | 4.65%   |
| Crucial                     | 111       | 156    | 4.3%    |
| SK hynix                    | 68        | 82     | 2.63%   |
| Intel                       | 65        | 93     | 2.52%   |
| Hitachi                     | 50        | 59     | 1.94%   |
| A-DATA Technology           | 48        | 59     | 1.86%   |
| Unknown                     | 44        | 65     | 1.7%    |
| HGST                        | 37        | 48     | 1.43%   |
| Micron Technology           | 31        | 32     | 1.2%    |
| Phison                      | 27        | 44     | 1.05%   |
| Apple                       | 27        | 37     | 1.05%   |
| PNY                         | 25        | 36     | 0.97%   |
| SPCC                        | 20        | 24     | 0.77%   |
| Phison Electronics          | 18        | 20     | 0.7%    |
| Corsair                     | 18        | 31     | 0.7%    |
| KIOXIA                      | 17        | 20     | 0.66%   |
| JMicron Technology          | 17        | 20     | 0.66%   |
| Silicon Motion              | 15        | 16     | 0.58%   |
| LITEON                      | 15        | 16     | 0.58%   |
| China                       | 15        | 30     | 0.58%   |
| Micron/Crucial Technology   | 11        | 12     | 0.43%   |
| Gigabyte Technology         | 11        | 14     | 0.43%   |
| XPG                         | 10        | 13     | 0.39%   |
| Transcend                   | 10        | 14     | 0.39%   |
| Patriot                     | 10        | 19     | 0.39%   |
| LITEONIT                    | 10        | 10     | 0.39%   |
| Hewlett-Packard             | 10        | 11     | 0.39%   |
| OCZ                         | 9         | 10     | 0.35%   |
| Kingston Technology Company | 7         | 8      | 0.27%   |
| Intenso                     | 7         | 8      | 0.27%   |
| Plextor                     | 6         | 6      | 0.23%   |
| Mushkin                     | 6         | 9      | 0.23%   |
| ASMT                        | 6         | 6      | 0.23%   |
| ADATA Technology            | 6         | 6      | 0.23%   |
| Team                        | 5         | 5      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                            | 46        | 1.55%   |
| Kingston SA400S37240G 240GB SSD                      | 34        | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB                       | 33        | 1.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 31        | 1.05%   |
| Samsung SSD 850 EVO 250GB                            | 26        | 0.88%   |
| Samsung SSD 850 EVO 500GB                            | 24        | 0.81%   |
| Samsung SSD 970 EVO Plus 500GB                       | 23        | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB                         | 23        | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB                       | 22        | 0.74%   |
| Samsung SSD 860 EVO 1TB                              | 22        | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 20        | 0.68%   |
| Toshiba MQ01ABD100 1TB                               | 20        | 0.68%   |
| Toshiba MQ04ABF100 1TB                               | 19        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                       | 19        | 0.64%   |
| Samsung SSD 860 EVO 250GB                            | 19        | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                          | 19        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 16        | 0.54%   |
| Kingston SA400S37120G 120GB SSD                      | 16        | 0.54%   |
| Samsung SSD 970 EVO 1TB                              | 15        | 0.51%   |
| Crucial CT500MX500SSD1 500GB                         | 15        | 0.51%   |
| Unknown SD/MMC/MS PRO 2GB                            | 14        | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 14        | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 13        | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB                       | 13        | 0.44%   |
| Kingston SA400S37480G 480GB SSD                      | 13        | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 12        | 0.41%   |
| Seagate Expansion 240GB                              | 12        | 0.41%   |
| Samsung SSD 840 EVO 250GB                            | 12        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                         | 12        | 0.41%   |
| Toshiba HDWD110 1TB                                  | 11        | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB                       | 11        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB                       | 11        | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 11        | 0.37%   |
| JMicron Generic 500GB                                | 11        | 0.37%   |
| Crucial CT1000P1SSD8 1TB                             | 11        | 0.37%   |
| Toshiba KXG60ZNV1T02 1TB                             | 10        | 0.34%   |
| Toshiba DT01ACA100 1TB                               | 10        | 0.34%   |
| Seagate ST4000DM004-2CV104 4TB                       | 10        | 0.34%   |
| Samsung SSD 870 EVO 1TB                              | 10        | 0.34%   |
| HGST HTS721010A9E630 1TB                             | 10        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 341       | 496    | 36.9%   |
| WDC                 | 284       | 465    | 30.74%  |
| Toshiba             | 119       | 151    | 12.88%  |
| Hitachi             | 50        | 59     | 5.41%   |
| HGST                | 37        | 48     | 4%      |
| Samsung Electronics | 34        | 43     | 3.68%   |
| Unknown             | 15        | 22     | 1.62%   |
| Apple               | 9         | 11     | 0.97%   |
| ASMT                | 6         | 6      | 0.65%   |
| Maxtor              | 4         | 6      | 0.43%   |
| SABRENT             | 3         | 4      | 0.32%   |
| Hewlett-Packard     | 3         | 4      | 0.32%   |
| USB3.0              | 2         | 3      | 0.22%   |
| Intenso             | 2         | 2      | 0.22%   |
| Fantom              | 2         | 5      | 0.22%   |
| WD MediaMax         | 1         | 1      | 0.11%   |
| RSH-319             | 1         | 1      | 0.11%   |
| PHD 3.0             | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| KESU                | 1         | 1      | 0.11%   |
| JMicron Technology  | 1         | 3      | 0.11%   |
| HPE                 | 1         | 1      | 0.11%   |
| HGST HUS            | 1         | 1      | 0.11%   |
| HGST HTS            | 1         | 1      | 0.11%   |
| Fujitsu             | 1         | 1      | 0.11%   |
| ExcelStor           | 1         | 2      | 0.11%   |
| ASMedia             | 1         | 2      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 272       | 423    | 27.67%  |
| Kingston            | 109       | 136    | 11.09%  |
| Crucial             | 94        | 125    | 9.56%   |
| SanDisk             | 87        | 98     | 8.85%   |
| WDC                 | 85        | 110    | 8.65%   |
| A-DATA Technology   | 31        | 40     | 3.15%   |
| PNY                 | 24        | 32     | 2.44%   |
| SK hynix            | 23        | 30     | 2.34%   |
| Intel               | 17        | 21     | 1.73%   |
| SPCC                | 16        | 18     | 1.63%   |
| Micron Technology   | 16        | 17     | 1.63%   |
| Apple               | 16        | 18     | 1.63%   |
| Toshiba             | 15        | 22     | 1.53%   |
| China               | 15        | 30     | 1.53%   |
| LITEON              | 12        | 13     | 1.22%   |
| JMicron Technology  | 11        | 11     | 1.12%   |
| Patriot             | 10        | 19     | 1.02%   |
| LITEONIT            | 10        | 10     | 1.02%   |
| Transcend           | 9         | 13     | 0.92%   |
| OCZ                 | 9         | 10     | 0.92%   |
| Corsair             | 7         | 12     | 0.71%   |
| Team                | 5         | 5      | 0.51%   |
| KingSpec            | 5         | 5      | 0.51%   |
| Intenso             | 5         | 6      | 0.51%   |
| Hewlett-Packard     | 5         | 5      | 0.51%   |
| Gigabyte Technology | 5         | 5      | 0.51%   |
| Plextor             | 4         | 4      | 0.41%   |
| Mushkin             | 4         | 7      | 0.41%   |
| GOODRAM             | 4         | 6      | 0.41%   |
| Unknown             | 3         | 3      | 0.31%   |
| TO Exter            | 3         | 3      | 0.31%   |
| Seagate             | 3         | 5      | 0.31%   |
| Lexar               | 3         | 3      | 0.31%   |
| Vaseky              | 2         | 4      | 0.2%    |
| Netac               | 2         | 2      | 0.2%    |
| Leven               | 2         | 2      | 0.2%    |
| KingFast            | 2         | 2      | 0.2%    |
| HS-SSD-C100         | 2         | 3      | 0.2%    |
| Hoodisk             | 2         | 2      | 0.2%    |
| Drevo               | 2         | 2      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 805       | 1318   | 35.51%  |
| HDD     | 772       | 1342   | 34.05%  |
| NVMe    | 641       | 968    | 28.28%  |
| MMC     | 28        | 41     | 1.24%   |
| Unknown | 21        | 29     | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1174      | 2485   | 59.26%  |
| NVMe | 640       | 959    | 32.31%  |
| SAS  | 139       | 213    | 7.02%   |
| MMC  | 28        | 41     | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 836       | 1399   | 49.06%  |
| 0.51-1.0   | 569       | 777    | 33.39%  |
| 1.01-2.0   | 174       | 283    | 10.21%  |
| 3.01-4.0   | 53        | 78     | 3.11%   |
| 4.01-10.0  | 38        | 65     | 2.23%   |
| 2.01-3.0   | 31        | 51     | 1.82%   |
| 10.01-20.0 | 3         | 7      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 356       | 22.25%  |
| 251-500        | 314       | 19.63%  |
| 501-1000       | 259       | 16.19%  |
| 1001-2000      | 207       | 12.94%  |
| More than 3000 | 172       | 10.75%  |
| Unknown        | 70        | 4.38%   |
| 2001-3000      | 69        | 4.31%   |
| 1-20           | 69        | 4.31%   |
| 51-100         | 59        | 3.69%   |
| 21-50          | 25        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 412       | 24.8%   |
| 21-50          | 299       | 18%     |
| 101-250        | 249       | 14.99%  |
| 51-100         | 189       | 11.38%  |
| 251-500        | 154       | 9.27%   |
| 501-1000       | 136       | 8.19%   |
| 1001-2000      | 74        | 4.46%   |
| Unknown        | 70        | 4.21%   |
| More than 3000 | 46        | 2.77%   |
| 2001-3000      | 31        | 1.87%   |
| 0              | 1         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB             | 8         | 8      | 2.61%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 1.95%   |
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 1.95%   |
| Seagate ST9320325AS 320GB                      | 5         | 6      | 1.63%   |
| Seagate ST31000528AS 1TB                       | 5         | 5      | 1.63%   |
| Seagate ST1000DM003-9YN162 1TB                 | 4         | 4      | 1.3%    |
| Toshiba MQ01ABF050 500GB                       | 3         | 3      | 0.98%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 3      | 0.98%   |
| Seagate ST3500312CS 500GB                      | 3         | 5      | 0.98%   |
| Seagate ST2000DM001-1ER164 2TB                 | 3         | 5      | 0.98%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 3      | 0.98%   |
| SanDisk SSD PLUS 1000GB                        | 3         | 3      | 0.98%   |
| Samsung Electronics SSD 870 EVO 1TB            | 3         | 3      | 0.98%   |
| Hitachi HTS547575A9E384 752GB                  | 3         | 3      | 0.98%   |
| WDC WDS500G1X0E-00AFY0 500GB                   | 2         | 2      | 0.65%   |
| WDC WD5000AAKX-603CA0 500GB                    | 2         | 6      | 0.65%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 2         | 2      | 0.65%   |
| WDC WD5000AAKX-001CA0 500GB                    | 2         | 3      | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB                       | 2         | 6      | 0.65%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 2         | 3      | 0.65%   |
| WDC WD3200AAJS-00L7A0 320GB                    | 2         | 2      | 0.65%   |
| WDC WD20EFRX-68EUZN0 2TB                       | 2         | 2      | 0.65%   |
| WDC WD20EARX-00PASB0 2TB                       | 2         | 2      | 0.65%   |
| WDC WD10EARS-00Y5B1 1TB                        | 2         | 4      | 0.65%   |
| WDC WD1003FZEX-00K3CA0 1TB                     | 2         | 2      | 0.65%   |
| Toshiba DT01ACA100 1TB                         | 2         | 2      | 0.65%   |
| Seagate ST9500325AS 500GB                      | 2         | 2      | 0.65%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.65%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.65%   |
| Seagate ST500LT012-1DG142 500GB                | 2         | 2      | 0.65%   |
| Seagate ST3500413AS 500GB                      | 2         | 2      | 0.65%   |
| Seagate ST31000524AS 1TB                       | 2         | 2      | 0.65%   |
| Seagate ST3000DM001-1ER166 3TB                 | 2         | 3      | 0.65%   |
| Seagate ST1000LX015-1U7172 1TB                 | 2         | 2      | 0.65%   |
| Seagate ST1000LM049-2GH172 1TB                 | 2         | 2      | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                 | 2         | 2      | 0.65%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 2         | 2      | 0.65%   |
| Maxtor STM3250310AS 250GB                      | 2         | 3      | 0.65%   |
| Hitachi HDS723020BLA642 2TB                    | 2         | 2      | 0.65%   |
| Hitachi HDS721010CLA332 1TB                    | 2         | 3      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 80        | 95     | 27.3%   |
| WDC                       | 73        | 114    | 24.91%  |
| Toshiba                   | 23        | 25     | 7.85%   |
| Samsung Electronics       | 22        | 24     | 7.51%   |
| Hitachi                   | 13        | 16     | 4.44%   |
| HGST                      | 12        | 15     | 4.1%    |
| SanDisk                   | 7         | 7      | 2.39%   |
| Intel                     | 7         | 11     | 2.39%   |
| SK hynix                  | 6         | 6      | 2.05%   |
| Kingston                  | 6         | 8      | 2.05%   |
| Corsair                   | 4         | 9      | 1.37%   |
| Transcend                 | 3         | 3      | 1.02%   |
| Micron Technology         | 3         | 3      | 1.02%   |
| Maxtor                    | 3         | 5      | 1.02%   |
| Crucial                   | 3         | 3      | 1.02%   |
| A-DATA Technology         | 3         | 3      | 1.02%   |
| Micron/Crucial Technology | 2         | 2      | 0.68%   |
| LITEONIT                  | 2         | 2      | 0.68%   |
| Hewlett-Packard           | 2         | 2      | 0.68%   |
| Drevo                     | 2         | 2      | 0.68%   |
| China                     | 2         | 3      | 0.68%   |
| Apple                     | 2         | 2      | 0.68%   |
| XPG                       | 1         | 1      | 0.34%   |
| USB3.0                    | 1         | 2      | 0.34%   |
| SSSTC                     | 1         | 1      | 0.34%   |
| SPCC                      | 1         | 1      | 0.34%   |
| Plextor                   | 1         | 1      | 0.34%   |
| Patriot                   | 1         | 1      | 0.34%   |
| Mushkin                   | 1         | 1      | 0.34%   |
| Lenovo                    | 1         | 1      | 0.34%   |
| LaCie                     | 1         | 1      | 0.34%   |
| Inateck                   | 1         | 1      | 0.34%   |
| HGST HTS                  | 1         | 1      | 0.34%   |
| ASMedia                   | 1         | 2      | 0.34%   |
| Unknown                   | 1         | 1      | 0.34%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 95     | 37.56%  |
| WDC                 | 70        | 109    | 32.86%  |
| Toshiba             | 21        | 23     | 9.86%   |
| Hitachi             | 13        | 16     | 6.1%    |
| HGST                | 12        | 15     | 5.63%   |
| Samsung Electronics | 6         | 6      | 2.82%   |
| Maxtor              | 3         | 5      | 1.41%   |
| Apple               | 2         | 2      | 0.94%   |
| USB3.0              | 1         | 2      | 0.47%   |
| LaCie               | 1         | 1      | 0.47%   |
| HGST HTS            | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 1      | 0.47%   |
| ASMedia             | 1         | 2      | 0.47%   |
| Unknown             | 1         | 1      | 0.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 201       | 279    | 71.53%  |
| SSD  | 63        | 75     | 22.42%  |
| NVMe | 17        | 21     | 6.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 12.5%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 12.5%   |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 12.5%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 12.5%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 12.5%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 12.5%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 37.5%   |
| Samsung Electronics | 2         | 2      | 25%     |
| HGST                | 2         | 2      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1222      | 2751   | 67.51%  |
| Detected | 306       | 563    | 16.91%  |
| Malfunc  | 274       | 375    | 15.14%  |
| Failed   | 8         | 9      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 967       | 45.25%  |
| AMD                            | 387       | 18.11%  |
| Samsung Electronics            | 253       | 11.84%  |
| SanDisk                        | 103       | 4.82%   |
| Phison Electronics             | 63        | 2.95%   |
| SK hynix                       | 46        | 2.15%   |
| ASMedia Technology             | 42        | 1.97%   |
| Kingston Technology Company    | 37        | 1.73%   |
| Micron/Crucial Technology      | 30        | 1.4%    |
| Toshiba America Info Systems   | 28        | 1.31%   |
| Marvell Technology Group       | 26        | 1.22%   |
| ADATA Technology               | 24        | 1.12%   |
| KIOXIA                         | 22        | 1.03%   |
| Silicon Motion                 | 21        | 0.98%   |
| Micron Technology              | 16        | 0.75%   |
| Nvidia                         | 14        | 0.66%   |
| Realtek Semiconductor          | 12        | 0.56%   |
| Seagate Technology             | 7         | 0.33%   |
| JMicron Technology             | 7         | 0.33%   |
| Lite-On Technology             | 6         | 0.28%   |
| Union Memory (Shenzhen)        | 4         | 0.19%   |
| Lenovo                         | 3         | 0.14%   |
| Apple                          | 3         | 0.14%   |
| VIA Technologies               | 2         | 0.09%   |
| Shenzhen Longsys Electronics   | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.09%   |
| LSI Logic / Symbios Logic      | 2         | 0.09%   |
| Broadcom / LSI                 | 2         | 0.09%   |
| Solid State Storage Technology | 1         | 0.05%   |
| Silicon Image                  | 1         | 0.05%   |
| Netac Technology               | 1         | 0.05%   |
| INNOGRIT                       | 1         | 0.05%   |
| Biwin Storage Technology       | 1         | 0.05%   |
| Adaptec                        | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 281       | 11.78%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 147       | 6.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 97        | 4.07%   |
| AMD 400 Series Chipset SATA Controller                                         | 89        | 3.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 74        | 3.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 62        | 2.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 59        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 50        | 2.1%    |
| AMD 500 Series Chipset SATA Controller                                         | 50        | 2.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 48        | 2.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 45        | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 41        | 1.72%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 40        | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 37        | 1.55%   |
| Phison E12 NVMe Controller                                                     | 36        | 1.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 35        | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 35        | 1.47%   |
| Samsung NVMe SSD Controller 980                                                | 31        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 29        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 29        | 1.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 28        | 1.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 27        | 1.13%   |
| Intel SSD 660P Series                                                          | 27        | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 24        | 1.01%   |
| Intel SATA Controller [RAID mode]                                              | 23        | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.96%   |
| Phison E16 PCIe4 NVMe Controller                                               | 22        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 22        | 0.92%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 22        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 21        | 0.88%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 20        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 0.84%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 19        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 19        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 0.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 17        | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 17        | 0.71%   |
| Micron Non-Volatile memory controller                                          | 16        | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 16        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 15        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1209      | 58.83%  |
| NVMe | 641       | 31.19%  |
| RAID | 105       | 5.11%   |
| IDE  | 95        | 4.62%   |
| SAS  | 3         | 0.15%   |
| SCSI | 2         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1061      | 70.45%  |
| AMD     | 444       | 29.48%  |
| Unknown | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 29        | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 21        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 1.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 1.26%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 19        | 1.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.06%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 16        | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 14        | 0.93%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 14        | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 14        | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 13        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.79%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 12        | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 0.73%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 11        | 0.73%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 11        | 0.73%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 10        | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.66%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 10        | 0.66%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 10        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.66%   |
| Intel Atom CPU C3758 @ 2.20GHz                | 10        | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.66%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 10        | 0.66%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 9         | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz              | 9         | 0.6%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 9         | 0.6%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.6%    |
| Intel Core i7-3770K CPU @ 3.50GHz             | 8         | 0.53%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 8         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 376       | 24.92%  |
| Intel Core i7           | 363       | 24.06%  |
| AMD Ryzen 5             | 142       | 9.41%   |
| AMD Ryzen 7             | 126       | 8.35%   |
| Intel Core i3           | 78        | 5.17%   |
| Other                   | 56        | 3.71%   |
| AMD Ryzen 9             | 47        | 3.11%   |
| Intel Xeon              | 36        | 2.39%   |
| Intel Pentium           | 36        | 2.39%   |
| Intel Celeron           | 33        | 2.19%   |
| AMD Ryzen 3             | 33        | 2.19%   |
| Intel Core 2 Duo        | 25        | 1.66%   |
| Intel Atom              | 19        | 1.26%   |
| Intel Core i9           | 15        | 0.99%   |
| AMD FX                  | 15        | 0.99%   |
| AMD A6                  | 11        | 0.73%   |
| AMD A10                 | 10        | 0.66%   |
| AMD Ryzen 7 PRO         | 9         | 0.6%    |
| Intel Pentium Dual-Core | 7         | 0.46%   |
| AMD A8                  | 7         | 0.46%   |
| AMD A4                  | 7         | 0.46%   |
| AMD Phenom II X4        | 6         | 0.4%    |
| AMD A12                 | 6         | 0.4%    |
| Intel Pentium Dual      | 5         | 0.33%   |
| AMD Ryzen Threadripper  | 5         | 0.33%   |
| Intel Xeon Silver       | 3         | 0.2%    |
| Intel Pentium Silver    | 3         | 0.2%    |
| Intel Core m3           | 3         | 0.2%    |
| AMD Athlon 64 X2        | 3         | 0.2%    |
| Intel Core 2 Quad       | 2         | 0.13%   |
| Intel Core 2            | 2         | 0.13%   |
| AMD Ryzen 5 PRO         | 2         | 0.13%   |
| AMD Phenom II X6        | 2         | 0.13%   |
| AMD E2                  | 2         | 0.13%   |
| AMD Athlon II X2        | 2         | 0.13%   |
| AMD Athlon              | 2         | 0.13%   |
| Intel Pentium Gold      | 1         | 0.07%   |
| Intel Pentium 4         | 1         | 0.07%   |
| Intel Genuine           | 1         | 0.07%   |
| Intel Core m7           | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 553       | 36.62%  |
| 2       | 462       | 30.6%   |
| 6       | 231       | 15.3%   |
| 8       | 176       | 11.66%  |
| 12      | 38        | 2.52%   |
| 16      | 17        | 1.13%   |
| 1       | 10        | 0.66%   |
| 3       | 9         | 0.6%    |
| 10      | 7         | 0.46%   |
| 14      | 3         | 0.2%    |
| 32      | 1         | 0.07%   |
| 24      | 1         | 0.07%   |
| 18      | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1503      | 99.73%  |
| 2       | 3         | 0.2%    |
| Unknown | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1174      | 77.9%   |
| 1       | 332       | 22.03%  |
| Unknown | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1499      | 99.54%  |
| Unknown        | 7         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 184       | 11.96%  |
| 0x306c3    | 84        | 5.46%   |
| 0x906ea    | 82        | 5.33%   |
| 0x306a9    | 80        | 5.2%    |
| 0x206a7    | 75        | 4.88%   |
| 0x08701021 | 63        | 4.1%    |
| 0x906e9    | 59        | 3.84%   |
| 0x806ea    | 46        | 2.99%   |
| 0x506e3    | 46        | 2.99%   |
| 0x806e9    | 42        | 2.73%   |
| 0x406e3    | 42        | 2.73%   |
| 0x0800820d | 35        | 2.28%   |
| 0x40651    | 31        | 2.02%   |
| 0x806ec    | 30        | 1.95%   |
| 0x0a201016 | 30        | 1.95%   |
| 0x806c1    | 26        | 1.69%   |
| 0x306d4    | 25        | 1.63%   |
| 0x08108109 | 24        | 1.56%   |
| 0x20655    | 23        | 1.5%    |
| 0x08600106 | 22        | 1.43%   |
| 0x1067a    | 21        | 1.37%   |
| 0x0a201009 | 21        | 1.37%   |
| 0xa0652    | 20        | 1.3%    |
| 0x08108102 | 20        | 1.3%    |
| 0x0a50000c | 19        | 1.24%   |
| 0x08701013 | 17        | 1.11%   |
| 0x706e5    | 14        | 0.91%   |
| 0x806eb    | 12        | 0.78%   |
| 0x106e5    | 12        | 0.78%   |
| 0x30678    | 11        | 0.72%   |
| 0x08101016 | 11        | 0.72%   |
| 0x0810100b | 11        | 0.72%   |
| 0x906ed    | 10        | 0.65%   |
| 0x506f1    | 10        | 0.65%   |
| 0x08600104 | 10        | 0.65%   |
| 0xa0655    | 9         | 0.59%   |
| 0xa0653    | 9         | 0.59%   |
| 0x906ec    | 9         | 0.59%   |
| 0x08608103 | 9         | 0.59%   |
| 0x08600103 | 9         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 330       | 21.87%  |
| Haswell          | 141       | 9.34%   |
| Zen 2            | 132       | 8.75%   |
| Skylake          | 102       | 6.76%   |
| IvyBridge        | 102       | 6.76%   |
| Zen 3            | 90        | 5.96%   |
| Zen+             | 88        | 5.83%   |
| SandyBridge      | 88        | 5.83%   |
| CometLake        | 42        | 2.78%   |
| Zen              | 40        | 2.65%   |
| Westmere         | 40        | 2.65%   |
| Penryn           | 32        | 2.12%   |
| Broadwell        | 30        | 1.99%   |
| TigerLake        | 28        | 1.86%   |
| Excavator        | 26        | 1.72%   |
| Icelake          | 25        | 1.66%   |
| Silvermont       | 24        | 1.59%   |
| Piledriver       | 21        | 1.39%   |
| Goldmont         | 18        | 1.19%   |
| Unknown          | 17        | 1.13%   |
| Nehalem          | 16        | 1.06%   |
| K10              | 14        | 0.93%   |
| Goldmont plus    | 14        | 0.93%   |
| Core             | 11        | 0.73%   |
| Alderlake Hybrid | 11        | 0.73%   |
| Steamroller      | 7         | 0.46%   |
| K8 Hammer        | 4         | 0.27%   |
| Jaguar           | 4         | 0.27%   |
| Puma             | 3         | 0.2%    |
| Bonnell          | 3         | 0.2%    |
| Tremont          | 2         | 0.13%   |
| Bulldozer        | 2         | 0.13%   |
| NetBurst         | 1         | 0.07%   |
| K10 Llano        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 793       | 43.1%   |
| Nvidia                     | 620       | 33.7%   |
| AMD                        | 411       | 22.34%  |
| ASPEED Technology          | 14        | 0.76%   |
| Matrox Electronics Systems | 1         | 0.05%   |
| ATI Technologies           | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 66        | 3.51%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 58        | 3.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 51        | 2.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 2.55%   |
| Intel UHD Graphics 620                                                                   | 47        | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 2.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 42        | 2.24%   |
| Intel HD Graphics 620                                                                    | 42        | 2.24%   |
| Intel HD Graphics 630                                                                    | 41        | 2.18%   |
| AMD Renoir                                                                               | 40        | 2.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 35        | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 34        | 1.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29        | 1.54%   |
| Intel HD Graphics 530                                                                    | 27        | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 26        | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 26        | 1.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24        | 1.28%   |
| Intel HD Graphics 5500                                                                   | 24        | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 23        | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 0.96%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 16        | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 15        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 15        | 0.8%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 15        | 0.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 0.8%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 15        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 14        | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14        | 0.75%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 14        | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.69%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 13        | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 12        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 489       | 32.15%  |
| 1 x Nvidia     | 354       | 23.27%  |
| 1 x AMD        | 326       | 21.43%  |
| Intel + Nvidia | 241       | 15.84%  |
| Intel + AMD    | 38        | 2.5%    |
| AMD + Nvidia   | 27        | 1.78%   |
| 2 x AMD        | 23        | 1.51%   |
| 1 x ASPEED     | 14        | 0.92%   |
| Other          | 3         | 0.2%    |
| 2 x Intel      | 3         | 0.2%    |
| 2 x Nvidia     | 2         | 0.13%   |
| 1 x Matrox     | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1077      | 70.72%  |
| Proprietary | 399       | 26.2%   |
| Unknown     | 47        | 3.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 799       | 51.85%  |
| 1.01-2.0   | 155       | 10.06%  |
| 7.01-8.0   | 135       | 8.76%   |
| 3.01-4.0   | 123       | 7.98%   |
| 0.01-0.5   | 120       | 7.79%   |
| 0.51-1.0   | 76        | 4.93%   |
| 5.01-6.0   | 60        | 3.89%   |
| 8.01-16.0  | 56        | 3.63%   |
| 2.01-3.0   | 15        | 0.97%   |
| 16.01-24.0 | 2         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 197       | 11.16%  |
| AU Optronics            | 175       | 9.92%   |
| LG Display              | 168       | 9.52%   |
| BOE                     | 137       | 7.76%   |
| Chimei Innolux          | 132       | 7.48%   |
| Dell                    | 128       | 7.25%   |
| Goldstar                | 126       | 7.14%   |
| Acer                    | 69        | 3.91%   |
| BenQ                    | 57        | 3.23%   |
| AOC                     | 56        | 3.17%   |
| Ancor Communications    | 53        | 3%      |
| Hewlett-Packard         | 46        | 2.61%   |
| Sharp                   | 35        | 1.98%   |
| Apple                   | 34        | 1.93%   |
| Philips                 | 30        | 1.7%    |
| Lenovo                  | 29        | 1.64%   |
| ASUSTek Computer        | 27        | 1.53%   |
| ViewSonic               | 19        | 1.08%   |
| Sony                    | 17        | 0.96%   |
| PANDA                   | 16        | 0.91%   |
| Iiyama                  | 14        | 0.79%   |
| Chi Mei Optoelectronics | 13        | 0.74%   |
| MSI                     | 12        | 0.68%   |
| Eizo                    | 11        | 0.62%   |
| Panasonic               | 10        | 0.57%   |
| Vizio                   | 9         | 0.51%   |
| Unknown                 | 9         | 0.51%   |
| Sceptre Tech            | 9         | 0.51%   |
| InfoVision              | 8         | 0.45%   |
| CSO                     | 8         | 0.45%   |
| Toshiba                 | 6         | 0.34%   |
| Gigabyte Technology     | 6         | 0.34%   |
| Vestel Elektronik       | 4         | 0.23%   |
| HannStar                | 4         | 0.23%   |
| VIE                     | 3         | 0.17%   |
| MStar                   | 3         | 0.17%   |
| MiTAC                   | 3         | 0.17%   |
| Medion                  | 3         | 0.17%   |
| Denver                  | 3         | 0.17%   |
| Compal                  | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 11        | 0.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 11        | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 10        | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 9         | 0.49%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                     | 9         | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 9         | 0.49%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 8         | 0.44%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                | 7         | 0.38%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 7         | 0.38%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 7         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 6         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 6         | 0.33%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                  | 6         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 5         | 0.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 5         | 0.27%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch           | 5         | 0.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 5         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 5         | 0.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                   | 5         | 0.27%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                      | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch          | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 5         | 0.27%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                   | 5         | 0.27%   |
| Acer V193W ACR0053 1440x900 408x255mm 18.9-inch                        | 5         | 0.27%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch  | 4         | 0.22%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 4         | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 4         | 0.22%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch      | 4         | 0.22%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch | 4         | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 4         | 0.22%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 4         | 0.22%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 4         | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 4         | 0.22%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 4         | 0.22%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 4         | 0.22%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 4         | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 4         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 816       | 49.6%   |
| 1366x768 (WXGA)    | 234       | 14.22%  |
| 2560x1440 (QHD)    | 130       | 7.9%    |
| 3840x2160 (4K)     | 119       | 7.23%   |
| 1600x900 (HD+)     | 55        | 3.34%   |
| 1280x1024 (SXGA)   | 35        | 2.13%   |
| 1920x1200 (WUXGA)  | 31        | 1.88%   |
| 1680x1050 (WSXGA+) | 30        | 1.82%   |
| 2560x1080          | 28        | 1.7%    |
| 1440x900 (WXGA+)   | 28        | 1.7%    |
| 1280x800 (WXGA)    | 23        | 1.4%    |
| 3440x1440          | 20        | 1.22%   |
| 1360x768           | 13        | 0.79%   |
| 3840x1080          | 10        | 0.61%   |
| 2880x1800          | 10        | 0.61%   |
| 1920x540           | 10        | 0.61%   |
| 2160x1440          | 9         | 0.55%   |
| 2560x1600          | 8         | 0.49%   |
| 3200x1800 (QHD+)   | 6         | 0.36%   |
| Unknown            | 5         | 0.3%    |
| 3840x2400          | 4         | 0.24%   |
| 3840x1600          | 3         | 0.18%   |
| 2288x1287          | 2         | 0.12%   |
| 2160x1350          | 2         | 0.12%   |
| 1600x1200          | 2         | 0.12%   |
| 1024x600           | 2         | 0.12%   |
| 5760x2160          | 1         | 0.06%   |
| 480x1920           | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3240x2160          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2944x1080          | 1         | 0.06%   |
| 2048x1152          | 1         | 0.06%   |
| 1400x1050          | 1         | 0.06%   |
| 1024x768 (XGA)     | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 410       | 23.39%  |
| 27      | 189       | 10.78%  |
| 24      | 160       | 9.13%   |
| 13      | 129       | 7.36%   |
| 14      | 125       | 7.13%   |
| 23      | 121       | 6.9%    |
| 21      | 105       | 5.99%   |
| 17      | 98        | 5.59%   |
| 31      | 55        | 3.14%   |
| Unknown | 42        | 2.4%    |
| 34      | 40        | 2.28%   |
| 19      | 35        | 2%      |
| 12      | 33        | 1.88%   |
| 18      | 25        | 1.43%   |
| 22      | 23        | 1.31%   |
| 84      | 15        | 0.86%   |
| 20      | 15        | 0.86%   |
| 72      | 14        | 0.8%    |
| 54      | 11        | 0.63%   |
| 40      | 11        | 0.63%   |
| 32      | 9         | 0.51%   |
| 25      | 9         | 0.51%   |
| 16      | 9         | 0.51%   |
| 11      | 8         | 0.46%   |
| 28      | 7         | 0.4%    |
| 26      | 6         | 0.34%   |
| 48      | 5         | 0.29%   |
| 39      | 5         | 0.29%   |
| 52      | 4         | 0.23%   |
| 10      | 4         | 0.23%   |
| 49      | 3         | 0.17%   |
| 46      | 3         | 0.17%   |
| 43      | 3         | 0.17%   |
| 42      | 3         | 0.17%   |
| 35      | 3         | 0.17%   |
| 29      | 3         | 0.17%   |
| 65      | 2         | 0.11%   |
| 55      | 2         | 0.11%   |
| 37      | 2         | 0.11%   |
| 33      | 2         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 605       | 35.5%   |
| 501-600        | 422       | 24.77%  |
| 401-500        | 183       | 10.74%  |
| 201-300        | 121       | 7.1%    |
| 351-400        | 102       | 5.99%   |
| 601-700        | 88        | 5.16%   |
| 701-800        | 52        | 3.05%   |
| Unknown        | 42        | 2.46%   |
| 1001-1500      | 31        | 1.82%   |
| 1501-2000      | 29        | 1.7%    |
| 801-900        | 22        | 1.29%   |
| 901-1000       | 6         | 0.35%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1242      | 80.6%   |
| 16/10   | 147       | 9.54%   |
| 21/9    | 53        | 3.44%   |
| 5/4     | 32        | 2.08%   |
| Unknown | 29        | 1.88%   |
| 3/2     | 17        | 1.1%    |
| 4/3     | 10        | 0.65%   |
| 32/9    | 6         | 0.39%   |
| 6/5     | 3         | 0.19%   |
| 1.00    | 1         | 0.06%   |
| 0.25    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 407       | 23.51%  |
| 201-250        | 340       | 19.64%  |
| 81-90          | 194       | 11.21%  |
| 301-350        | 193       | 11.15%  |
| 351-500        | 111       | 6.41%   |
| 121-130        | 75        | 4.33%   |
| 151-200        | 65        | 3.76%   |
| 71-80          | 60        | 3.47%   |
| 251-300        | 57        | 3.29%   |
| More than 1000 | 51        | 2.95%   |
| 141-150        | 42        | 2.43%   |
| Unknown        | 42        | 2.43%   |
| 501-1000       | 34        | 1.96%   |
| 61-70          | 29        | 1.68%   |
| 51-60          | 9         | 0.52%   |
| 91-100         | 8         | 0.46%   |
| 131-140        | 7         | 0.4%    |
| 111-120        | 4         | 0.23%   |
| 41-50          | 3         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 552       | 33.13%  |
| 121-160       | 483       | 28.99%  |
| 101-120       | 415       | 24.91%  |
| 161-240       | 96        | 5.76%   |
| 1-50          | 44        | 2.64%   |
| Unknown       | 42        | 2.52%   |
| More than 240 | 34        | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1122      | 73.05%  |
| 2     | 318       | 20.7%   |
| 0     | 57        | 3.71%   |
| 3     | 37        | 2.41%   |
| 4     | 2         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 843       | 38.18%  |
| Intel                                  | 834       | 37.77%  |
| Qualcomm Atheros                       | 228       | 10.33%  |
| Broadcom                               | 97        | 4.39%   |
| Ralink Technology                      | 22        | 1%      |
| TP-Link                                | 19        | 0.86%   |
| Broadcom Limited                       | 18        | 0.82%   |
| Marvell Technology Group               | 12        | 0.54%   |
| Nvidia                                 | 11        | 0.5%    |
| MediaTek                               | 10        | 0.45%   |
| ASIX Electronics                       | 9         | 0.41%   |
| Microsoft                              | 8         | 0.36%   |
| Dell                                   | 8         | 0.36%   |
| Sierra Wireless                        | 7         | 0.32%   |
| Ralink                                 | 5         | 0.23%   |
| Ericsson Business Mobile Networks      | 5         | 0.23%   |
| Samsung Electronics                    | 4         | 0.18%   |
| Qualcomm Atheros Communications        | 4         | 0.18%   |
| NetGear                                | 4         | 0.18%   |
| Lenovo                                 | 4         | 0.18%   |
| Insyde Software                        | 4         | 0.18%   |
| Huawei Technologies                    | 4         | 0.18%   |
| Hewlett-Packard                        | 4         | 0.18%   |
| D-Link System                          | 4         | 0.18%   |
| Aquantia                               | 4         | 0.18%   |
| DisplayLink                            | 3         | 0.14%   |
| D-Link                                 | 3         | 0.14%   |
| Qualcomm                               | 2         | 0.09%   |
| Oculus VR                              | 2         | 0.09%   |
| JMicron Technology                     | 2         | 0.09%   |
| ASUSTek Computer                       | 2         | 0.09%   |
| Xiaomi                                 | 1         | 0.05%   |
| vivo                                   | 1         | 0.05%   |
| U-Blox                                 | 1         | 0.05%   |
| Tenda                                  | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Solarflare Communications              | 1         | 0.05%   |
| Seeed Technology                       | 1         | 0.05%   |
| Novatel Wireless                       | 1         | 0.05%   |
| Motorola PCS                           | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 638       | 24%     |
| Intel Wi-Fi 6 AX200                                               | 124       | 4.67%   |
| Intel I211 Gigabit Network Connection                             | 77        | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 64        | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 61        | 2.29%   |
| Intel Wireless 8265 / 8275                                        | 56        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 1.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 45        | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 44        | 1.66%   |
| Intel Ethernet Connection (2) I219-V                              | 43        | 1.62%   |
| Intel Wireless 7260                                               | 42        | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 41        | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 35        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 35        | 1.32%   |
| Intel Wireless-AC 9260                                            | 33        | 1.24%   |
| Intel Wireless 8260                                               | 31        | 1.17%   |
| Intel Wireless 7265                                               | 31        | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 29        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 28        | 1.05%   |
| Intel Wireless 3165                                               | 25        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 24        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 24        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 23        | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 22        | 0.83%   |
| Intel Wi-Fi 6 AX201                                               | 22        | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 0.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 17        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 15        | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                    | 15        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 14        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 12        | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 637       | 53.57%  |
| Realtek Semiconductor             | 191       | 16.06%  |
| Qualcomm Atheros                  | 180       | 15.14%  |
| Broadcom                          | 70        | 5.89%   |
| Ralink Technology                 | 22        | 1.85%   |
| TP-Link                           | 16        | 1.35%   |
| Broadcom Limited                  | 13        | 1.09%   |
| MediaTek                          | 10        | 0.84%   |
| Microsoft                         | 8         | 0.67%   |
| Sierra Wireless                   | 7         | 0.59%   |
| Ralink                            | 5         | 0.42%   |
| Qualcomm Atheros Communications   | 4         | 0.34%   |
| NetGear                           | 4         | 0.34%   |
| Dell                              | 4         | 0.34%   |
| D-Link                            | 3         | 0.25%   |
| Marvell Technology Group          | 2         | 0.17%   |
| Hewlett-Packard                   | 2         | 0.17%   |
| Ericsson Business Mobile Networks | 2         | 0.17%   |
| D-Link System                     | 2         | 0.17%   |
| ASUSTek Computer                  | 2         | 0.17%   |
| Tenda                             | 1         | 0.08%   |
| IMC Networks                      | 1         | 0.08%   |
| Fibocom                           | 1         | 0.08%   |
| Edimax Technology                 | 1         | 0.08%   |
| CyberTAN Technology               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 124       | 10.36%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 61        | 5.1%    |
| Intel Wireless 8265 / 8275                                     | 56        | 4.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 44        | 3.68%   |
| Intel Wireless 7260                                            | 42        | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 41        | 3.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 35        | 2.92%   |
| Intel Wireless-AC 9260                                         | 33        | 2.76%   |
| Intel Wireless 8260                                            | 31        | 2.59%   |
| Intel Wireless 7265                                            | 31        | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 29        | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 29        | 2.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 28        | 2.34%   |
| Intel Wireless 3165                                            | 25        | 2.09%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 24        | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 23        | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 22        | 1.84%   |
| Intel Wi-Fi 6 AX201                                            | 22        | 1.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 1.42%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 17        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 15        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 14        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 1%      |
| Intel Centrino Advanced-N 6200                                 | 12        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11        | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 10        | 0.84%   |
| Ralink MT7601U Wireless Adapter                                | 10        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 10        | 0.84%   |
| Intel Centrino Advanced-N 6235                                 | 10        | 0.84%   |
| Intel Wireless 3160                                            | 9         | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 8         | 0.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 8         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 779       | 55.76%  |
| Intel                                  | 429       | 30.71%  |
| Qualcomm Atheros                       | 69        | 4.94%   |
| Broadcom                               | 44        | 3.15%   |
| Nvidia                                 | 11        | 0.79%   |
| Marvell Technology Group               | 10        | 0.72%   |
| ASIX Electronics                       | 9         | 0.64%   |
| Broadcom Limited                       | 5         | 0.36%   |
| Samsung Electronics                    | 4         | 0.29%   |
| Lenovo                                 | 4         | 0.29%   |
| Insyde Software                        | 4         | 0.29%   |
| Aquantia                               | 4         | 0.29%   |
| TP-Link                                | 3         | 0.21%   |
| DisplayLink                            | 3         | 0.21%   |
| Qualcomm                               | 2         | 0.14%   |
| JMicron Technology                     | 2         | 0.14%   |
| Huawei Technologies                    | 2         | 0.14%   |
| D-Link System                          | 2         | 0.14%   |
| Xiaomi                                 | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Solarflare Communications              | 1         | 0.07%   |
| Novatel Wireless                       | 1         | 0.07%   |
| Motorola PCS                           | 1         | 0.07%   |
| MediaTek                               | 1         | 0.07%   |
| ICS Advent                             | 1         | 0.07%   |
| Google                                 | 1         | 0.07%   |
| Emulex                                 | 1         | 0.07%   |
| Apple                                  | 1         | 0.07%   |
| 3Com                                   | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 638       | 44.27%  |
| Intel I211 Gigabit Network Connection                             | 77        | 5.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 64        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 3.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 45        | 3.12%   |
| Intel Ethernet Connection (2) I219-V                              | 43        | 2.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 35        | 2.43%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 2.15%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 1.73%   |
| Intel Ethernet Controller I225-V                                  | 24        | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 12        | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 0.69%   |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 8         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 8         | 0.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.49%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 6         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.42%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 5         | 0.35%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.35%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1331      | 53.43%  |
| WiFi     | 1140      | 45.76%  |
| Modem    | 19        | 0.76%   |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 862       | 54.28%  |
| Ethernet | 726       | 45.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 856       | 56.65%  |
| 1     | 585       | 38.72%  |
| 3     | 44        | 2.91%   |
| 4     | 18        | 1.19%   |
| 0     | 7         | 0.46%   |
| 9     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1192      | 77.65%  |
| Yes  | 343       | 22.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 535       | 51.94%  |
| Realtek Semiconductor           | 104       | 10.1%   |
| Qualcomm Atheros Communications | 79        | 7.67%   |
| Cambridge Silicon Radio         | 61        | 5.92%   |
| Broadcom                        | 43        | 4.17%   |
| Apple                           | 43        | 4.17%   |
| IMC Networks                    | 41        | 3.98%   |
| Lite-On Technology              | 32        | 3.11%   |
| ASUSTek Computer                | 30        | 2.91%   |
| Foxconn / Hon Hai               | 21        | 2.04%   |
| Dell                            | 9         | 0.87%   |
| Toshiba                         | 4         | 0.39%   |
| Realtek                         | 4         | 0.39%   |
| Belkin Components               | 4         | 0.39%   |
| MediaTek                        | 3         | 0.29%   |
| Edimax Technology               | 3         | 0.29%   |
| Dynex                           | 3         | 0.29%   |
| HTC (High Tech Computer)        | 2         | 0.19%   |
| Hewlett-Packard                 | 2         | 0.19%   |
| TP-Link                         | 1         | 0.1%    |
| SIN                             | 1         | 0.1%    |
| Ralink Technology               | 1         | 0.1%    |
| Ralink                          | 1         | 0.1%    |
| Opticis                         | 1         | 0.1%    |
| Marvell Semiconductor           | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 188       | 18.23%  |
| Intel AX200 Bluetooth                                 | 119       | 11.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 75        | 7.27%   |
| Intel Bluetooth Device                                | 67        | 6.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 61        | 5.92%   |
| Qualcomm Atheros  Bluetooth Device                    | 56        | 5.43%   |
| Realtek Bluetooth Radio                               | 55        | 5.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 34        | 3.3%    |
| Realtek  Bluetooth 4.2 Adapter                        | 32        | 3.1%    |
| Intel Wireless-AC 3168 Bluetooth                      | 26        | 2.52%   |
| Lite-On Bluetooth Device                              | 25        | 2.42%   |
| Apple Bluetooth Host Controller                       | 19        | 1.84%   |
| Apple Bluetooth USB Host Controller                   | 18        | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                           | 17        | 1.65%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 16        | 1.55%   |
| IMC Networks Bluetooth Device                         | 15        | 1.45%   |
| IMC Networks Bluetooth Radio                          | 14        | 1.36%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 11        | 1.07%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 9         | 0.87%   |
| Realtek RTL8821A Bluetooth                            | 8         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 8         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                    | 8         | 0.78%   |
| ASUS ASUS USB-BT500                                   | 7         | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 6         | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 6         | 0.58%   |
| Dell BCM20702A0 Bluetooth Module                      | 6         | 0.58%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 6         | 0.58%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 4         | 0.39%   |
| Realtek RTL8723B Bluetooth                            | 4         | 0.39%   |
| Realtek Bluetooth Radio                               | 4         | 0.39%   |
| Intel AX210 Bluetooth                                 | 4         | 0.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 4         | 0.39%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 4         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 3         | 0.29%   |
| MediaTek Wireless_Device                              | 3         | 0.29%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 3         | 0.29%   |
| Lite-On Atheros AR3012 Bluetooth                      | 3         | 0.29%   |
| IMC Networks Wireless_Device                          | 3         | 0.29%   |
| IMC Networks Bluetooth USB Host Controller            | 3         | 0.29%   |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1025      | 43.41%  |
| AMD                                  | 520       | 22.02%  |
| Nvidia                               | 493       | 20.88%  |
| C-Media Electronics                  | 48        | 2.03%   |
| Logitech                             | 33        | 1.4%    |
| Kingston Technology                  | 20        | 0.85%   |
| Texas Instruments                    | 15        | 0.64%   |
| Focusrite-Novation                   | 15        | 0.64%   |
| JMTek                                | 13        | 0.55%   |
| Creative Technology                  | 11        | 0.47%   |
| Corsair                              | 10        | 0.42%   |
| Realtek Semiconductor                | 9         | 0.38%   |
| SteelSeries ApS                      | 8         | 0.34%   |
| Razer USA                            | 8         | 0.34%   |
| Creative Labs                        | 8         | 0.34%   |
| RODE Microphones                     | 6         | 0.25%   |
| SAVITECH                             | 5         | 0.21%   |
| Samson Technologies                  | 5         | 0.21%   |
| Generalplus Technology               | 5         | 0.21%   |
| Blue Microphones                     | 5         | 0.21%   |
| BEHRINGER International              | 5         | 0.21%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.17%   |
| Plantronics                          | 4         | 0.17%   |
| GN Netcom                            | 4         | 0.17%   |
| DSEA A/S                             | 4         | 0.17%   |
| Yamaha                               | 3         | 0.13%   |
| VIA Technologies                     | 3         | 0.13%   |
| Sony                                 | 3         | 0.13%   |
| PreSonus Audio Electronics           | 3         | 0.13%   |
| Native Instruments                   | 3         | 0.13%   |
| Lenovo                               | 3         | 0.13%   |
| ASUSTek Computer                     | 3         | 0.13%   |
| XMOS                                 | 2         | 0.08%   |
| Sennheiser Communications            | 2         | 0.08%   |
| Project                              | 2         | 0.08%   |
| Mark of the Unicorn                  | 2         | 0.08%   |
| Jieli Technology                     | 2         | 0.08%   |
| FIFINE Microphones                   | 2         | 0.08%   |
| Dell                                 | 2         | 0.08%   |
| Cambridge Silicon Radio              | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 164       | 5.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 143       | 5.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 141       | 5.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 97        | 3.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 95        | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 87        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 87        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 71        | 2.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 62        | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 61        | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 57        | 2.05%   |
| Intel 200 Series PCH HD Audio                                              | 50        | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 46        | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 44        | 1.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 40        | 1.44%   |
| Nvidia GP106 High Definition Audio Controller                              | 40        | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 39        | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 39        | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 35        | 1.26%   |
| Intel 8 Series HD Audio Controller                                         | 35        | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 33        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 32        | 1.15%   |
| Intel Comet Lake PCH cAVS                                                  | 30        | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 29        | 1.04%   |
| Intel Broadwell-U Audio Controller                                         | 29        | 1.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29        | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 1.01%   |
| Intel CM238 HD Audio Controller                                            | 27        | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 26        | 0.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 25        | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 25        | 0.9%    |
| AMD FCH Azalia Controller                                                  | 22        | 0.79%   |
| AMD Navi 10 HDMI Audio                                                     | 21        | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 20        | 0.72%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 20        | 0.72%   |
| Nvidia TU104 HD Audio Controller                                           | 19        | 0.68%   |
| Nvidia GM204 High Definition Audio Controller                              | 19        | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 19        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 333       | 20.77%  |
| SK hynix            | 279       | 17.4%   |
| Kingston            | 163       | 10.17%  |
| Corsair             | 153       | 9.54%   |
| Micron Technology   | 151       | 9.42%   |
| Crucial             | 124       | 7.74%   |
| Unknown             | 93        | 5.8%    |
| G.Skill             | 90        | 5.61%   |
| A-DATA Technology   | 31        | 1.93%   |
| Team                | 27        | 1.68%   |
| Ramaxel Technology  | 21        | 1.31%   |
| Nanya Technology    | 19        | 1.19%   |
| Elpida              | 17        | 1.06%   |
| Patriot             | 13        | 0.81%   |
| Unknown (ABCD)      | 8         | 0.5%    |
| Unknown             | 7         | 0.44%   |
| Silicon Power       | 6         | 0.37%   |
| Avant               | 6         | 0.37%   |
| Apacer              | 6         | 0.37%   |
| Transcend           | 5         | 0.31%   |
| Goldkey             | 5         | 0.31%   |
| Neo Forza           | 4         | 0.25%   |
| GOODRAM             | 4         | 0.25%   |
| ASint Technology    | 4         | 0.25%   |
| PNY                 | 3         | 0.19%   |
| CSX                 | 3         | 0.19%   |
| AMD                 | 3         | 0.19%   |
| Lexar               | 2         | 0.12%   |
| Kingmax             | 2         | 0.12%   |
| GeIL                | 2         | 0.12%   |
| Unknown (898F)      | 1         | 0.06%   |
| Unknown (0x8634)    | 1         | 0.06%   |
| Unknown (0x8319)    | 1         | 0.06%   |
| Unknown (09D5)      | 1         | 0.06%   |
| Unifosa             | 1         | 0.06%   |
| Timetec             | 1         | 0.06%   |
| Smart               | 1         | 0.06%   |
| Sesame              | 1         | 0.06%   |
| Saikano             | 1         | 0.06%   |
| S                   | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 19        | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 0.99%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.81%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16384MB DIMM DDR4 3200MT/s         | 12        | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 12        | 0.7%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 11        | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 11        | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.46%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 8         | 0.46%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 7         | 0.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s        | 7         | 0.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.41%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 7         | 0.41%   |
| Unknown                                                          | 7         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.35%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 6         | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.35%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 6         | 0.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.35%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 6         | 0.35%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 6         | 0.35%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 5         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 804       | 58.73%  |
| DDR3    | 425       | 31.04%  |
| LPDDR3  | 34        | 2.48%   |
| LPDDR4  | 29        | 2.12%   |
| Unknown | 26        | 1.9%    |
| SDRAM   | 19        | 1.39%   |
| DDR2    | 17        | 1.24%   |
| DDR5    | 10        | 0.73%   |
| DDR     | 3         | 0.22%   |
| LPDDR5  | 2         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 716       | 52.42%  |
| DIMM         | 574       | 42.02%  |
| Row Of Chips | 67        | 4.9%    |
| Chip         | 8         | 0.59%   |
| RIMM         | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 656       | 43.91%  |
| 4096  | 415       | 27.78%  |
| 16384 | 248       | 16.6%   |
| 2048  | 106       | 7.1%    |
| 32768 | 52        | 3.48%   |
| 1024  | 15        | 1%      |
| 64    | 1         | 0.07%   |
| 16    | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 305       | 20.05%  |
| 2667    | 249       | 16.37%  |
| 3200    | 234       | 15.38%  |
| 2400    | 143       | 9.4%    |
| 1333    | 78        | 5.13%   |
| 2133    | 73        | 4.8%    |
| 3600    | 68        | 4.47%   |
| 1334    | 33        | 2.17%   |
| 1867    | 29        | 1.91%   |
| 3400    | 24        | 1.58%   |
| 3000    | 23        | 1.51%   |
| 3733    | 22        | 1.45%   |
| 3266    | 21        | 1.38%   |
| 1067    | 21        | 1.38%   |
| 3466    | 19        | 1.25%   |
| Unknown | 13        | 0.85%   |
| 800     | 12        | 0.79%   |
| 667     | 12        | 0.79%   |
| 4267    | 11        | 0.72%   |
| 2933    | 11        | 0.72%   |
| 2800    | 11        | 0.72%   |
| 3866    | 8         | 0.53%   |
| 3800    | 8         | 0.53%   |
| 2666    | 8         | 0.53%   |
| 1866    | 8         | 0.53%   |
| 4199    | 6         | 0.39%   |
| 4800    | 5         | 0.33%   |
| 1800    | 5         | 0.33%   |
| 8400    | 4         | 0.26%   |
| 3334    | 4         | 0.26%   |
| 2048    | 4         | 0.26%   |
| 1648    | 4         | 0.26%   |
| 5200    | 3         | 0.2%    |
| 3333    | 3         | 0.2%    |
| 2465    | 3         | 0.2%    |
| 1066    | 3         | 0.2%    |
| 975     | 3         | 0.2%    |
| 533     | 3         | 0.2%    |
| 6400    | 2         | 0.13%   |
| 3666    | 2         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 15        | 37.5%   |
| Hewlett-Packard     | 14        | 35%     |
| Canon               | 4         | 10%     |
| Seiko Epson         | 3         | 7.5%    |
| Samsung Electronics | 1         | 2.5%    |
| MIIIW               | 1         | 2.5%    |
| Gprinter            | 1         | 2.5%    |
| Dymo-CoStar         | 1         | 2.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson ET-4700 Series             | 2         | 5%      |
| HP DeskJet 2600 series                 | 2         | 5%      |
| Brother Printer                        | 2         | 5%      |
| Brother DCP-7055 scanner/printer       | 2         | 5%      |
| Seiko Epson ET-2710 Series             | 1         | 2.5%    |
| Samsung SCX-3400 Series                | 1         | 2.5%    |
| MIIIW MW Keyboard Air Mini             | 1         | 2.5%    |
| HP OfficeJet Pro 8020 series           | 1         | 2.5%    |
| HP OfficeJet Pro 6960                  | 1         | 2.5%    |
| HP OfficeJet 5200 series               | 1         | 2.5%    |
| HP OfficeJet 4650 series               | 1         | 2.5%    |
| HP LaserJet Professional P1102w        | 1         | 2.5%    |
| HP LaserJet P1005                      | 1         | 2.5%    |
| HP LaserJet M203-M206                  | 1         | 2.5%    |
| HP ENVY 4500 series                    | 1         | 2.5%    |
| HP Deskjet 4640 series                 | 1         | 2.5%    |
| HP DeskJet 3700 series                 | 1         | 2.5%    |
| HP DeskJet 2700 series                 | 1         | 2.5%    |
| HP Deskjet 1050 J410                   | 1         | 2.5%    |
| Gprinter GP-58                         | 1         | 2.5%    |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 2.5%    |
| Canon TS5100 series                    | 1         | 2.5%    |
| Canon PIXMA MG3600 Series              | 1         | 2.5%    |
| Canon G2000 series                     | 1         | 2.5%    |
| Canon CanoScan LiDE 300                | 1         | 2.5%    |
| Brother MFC-L3770CDW series            | 1         | 2.5%    |
| Brother MFC-L3750CDW                   | 1         | 2.5%    |
| Brother MFC-J6545DW                    | 1         | 2.5%    |
| Brother MFC-J497DW                     | 1         | 2.5%    |
| Brother MFC-J485DW                     | 1         | 2.5%    |
| Brother MFC-J450DW                     | 1         | 2.5%    |
| Brother MFC-7460DN                     | 1         | 2.5%    |
| Brother HL-L2300D series               | 1         | 2.5%    |
| Brother HL-3140CW series               | 1         | 2.5%    |
| Brother DCP-L3550CDW series            | 1         | 2.5%    |
| Brother DCP-1610W                      | 1         | 2.5%    |

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


| Vendor                                            | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Electronics                               | 209       | 22.82%  |
| IMC Networks                                      | 99        | 10.81%  |
| Acer                                              | 80        | 8.73%   |
| Logitech                                          | 79        | 8.62%   |
| Realtek Semiconductor                             | 73        | 7.97%   |
| Microdia                                          | 72        | 7.86%   |
| Sunplus Innovation Technology                     | 46        | 5.02%   |
| Apple                                             | 34        | 3.71%   |
| Cheng Uei Precision Industry (Foxlink)            | 31        | 3.38%   |
| Quanta                                            | 29        | 3.17%   |
| Syntek                                            | 22        | 2.4%    |
| Lite-On Technology                                | 19        | 2.07%   |
| Suyin                                             | 16        | 1.75%   |
| Lenovo                                            | 10        | 1.09%   |
| Microsoft                                         | 9         | 0.98%   |
| Silicon Motion                                    | 8         | 0.87%   |
| Samsung Electronics                               | 7         | 0.76%   |
| Primax Electronics                                | 5         | 0.55%   |
| Luxvisions Innotech Limited                       | 5         | 0.55%   |
| KYE Systems (Mouse Systems)                       | 5         | 0.55%   |
| Creative Technology                               | 5         | 0.55%   |
| Razer USA                                         | 4         | 0.44%   |
| Hewlett-Packard                                   | 4         | 0.44%   |
| Generalplus Technology                            | 4         | 0.44%   |
| Alcor Micro                                       | 4         | 0.44%   |
| Ricoh                                             | 3         | 0.33%   |
| Importek                                          | 3         | 0.33%   |
| GEMBIRD                                           | 3         | 0.33%   |
| WaveRider Communications                          | 2         | 0.22%   |
| Unknown                                           | 2         | 0.22%   |
| Sunplus Technology                                | 2         | 0.22%   |
| Sonix Technology                                  | 2         | 0.22%   |
| Ruision                                           | 2         | 0.22%   |
| AVerMedia Technologies                            | 2         | 0.22%   |
| ARC International                                 | 2         | 0.22%   |
| Z-Star Microelectronics                           | 1         | 0.11%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1         | 0.11%   |
| OPPO Electronics                                  | 1         | 0.11%   |
| OmniVision Technologies                           | 1         | 0.11%   |
| Mimaki Engineering                                | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 55        | 5.97%   |
| Realtek Integrated_Webcam_HD         | 30        | 3.26%   |
| Microdia Integrated_Webcam_HD        | 29        | 3.15%   |
| IMC Networks Integrated Camera       | 26        | 2.82%   |
| Acer Integrated Camera               | 26        | 2.82%   |
| Chicony HD WebCam                    | 24        | 2.61%   |
| Logitech HD Pro Webcam C920          | 22        | 2.39%   |
| IMC Networks USB2.0 HD UVC WebCam    | 22        | 2.39%   |
| Logitech Webcam C270                 | 18        | 1.95%   |
| Syntek Integrated Camera             | 15        | 1.63%   |
| Lite-On Integrated Camera            | 14        | 1.52%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 14        | 1.52%   |
| Sunplus Integrated_Webcam_HD         | 13        | 1.41%   |
| Acer EasyCamera                      | 12        | 1.3%    |
| Chicony USB2.0 Camera                | 11        | 1.19%   |
| Chicony HP Wide Vision HD Camera     | 10        | 1.09%   |
| Apple Built-in iSight                | 10        | 1.09%   |
| Chicony HP TrueVision HD             | 9         | 0.98%   |
| Apple iPhone 5/5C/5S/6/SE            | 9         | 0.98%   |
| Microdia Integrated Webcam           | 8         | 0.87%   |
| Logitech C922 Pro Stream Webcam      | 8         | 0.87%   |
| Apple FaceTime HD Camera (Built-in)  | 8         | 0.87%   |
| Acer BisonCam,NB Pro                 | 8         | 0.87%   |
| Samsung Galaxy A5 (MTP)              | 7         | 0.76%   |
| Quanta HD Webcam                     | 7         | 0.76%   |
| Microdia USB 2.0 Camera              | 7         | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam        | 7         | 0.76%   |
| Lenovo Integrated Webcam [R5U877]    | 6         | 0.65%   |
| IMC Networks Lenovo EasyCamera       | 6         | 0.65%   |
| Chicony HP TrueVision HD Camera      | 6         | 0.65%   |
| Chicony HP HD Webcam                 | 6         | 0.65%   |
| Chicony HP HD Camera                 | 6         | 0.65%   |
| Chicony EasyCamera                   | 6         | 0.65%   |
| Apple FaceTime HD Camera             | 6         | 0.65%   |
| Acer HD Webcam                       | 6         | 0.65%   |
| Realtek Integrated Webcam HD         | 5         | 0.54%   |
| Quanta HD User Facing                | 5         | 0.54%   |
| Microsoft LifeCam HD-3000            | 5         | 0.54%   |
| Microdia Laptop_Integrated_Webcam_HD | 5         | 0.54%   |
| IMC Networks VGA UVC WebCam          | 5         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 65        | 39.88%  |
| Synaptics                  | 35        | 21.47%  |
| Shenzhen Goodix Technology | 26        | 15.95%  |
| Upek                       | 11        | 6.75%   |
| Elan Microelectronics      | 11        | 6.75%   |
| LighTuning Technology      | 7         | 4.29%   |
| AuthenTec                  | 6         | 3.68%   |
| STMicroelectronics         | 1         | 0.61%   |
| DigitalPersona             | 1         | 0.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 10.43%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 6.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 6.75%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 6.75%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 6.13%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 5.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 5.52%   |
| Unknown                                                                    | 9         | 5.52%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 4.29%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 3.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.68%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 3.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.07%   |
| Synaptics  WBDI                                                            | 5         | 3.07%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.07%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.84%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.84%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.23%   |
| Synaptics WBDI Device                                                      | 2         | 1.23%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 1.23%   |
| AuthenTec AES1600                                                          | 2         | 1.23%   |
| Validity Sensors VFS491                                                    | 1         | 0.61%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.61%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.61%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.61%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.61%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.61%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.61%   |
| AuthenTec AES2810                                                          | 1         | 0.61%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.61%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 29        | 40.28%  |
| Alcor Micro           | 26        | 36.11%  |
| O2 Micro              | 5         | 6.94%   |
| Lenovo                | 4         | 5.56%   |
| Upek                  | 2         | 2.78%   |
| Gemalto (was Gemplus) | 2         | 2.78%   |
| Yubico.com            | 1         | 1.39%   |
| SCM Microsystems      | 1         | 1.39%   |
| Clay Logic            | 1         | 1.39%   |
| Cherry                | 1         | 1.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 36.11%  |
| Broadcom 5880                                                                | 8         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 9.72%   |
| Broadcom 58200                                                               | 7         | 9.72%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 2.78%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 2.78%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 1.39%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.39%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.39%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.39%   |
| Cherry Smart Card Reader USB                                                 | 1         | 1.39%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1097      | 71.28%  |
| 1     | 350       | 22.74%  |
| 2     | 84        | 5.46%   |
| 3     | 5         | 0.32%   |
| 4     | 3         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 162       | 30.98%  |
| Graphics card            | 143       | 27.34%  |
| Chipcard                 | 69        | 13.19%  |
| Net/wireless             | 51        | 9.75%   |
| Camera                   | 25        | 4.78%   |
| Multimedia controller    | 22        | 4.21%   |
| Communication controller | 15        | 2.87%   |
| Unassigned class         | 11        | 2.1%    |
| Bluetooth                | 7         | 1.34%   |
| Network                  | 4         | 0.76%   |
| Net/ethernet             | 3         | 0.57%   |
| Card reader              | 3         | 0.57%   |
| Storage/nvme             | 2         | 0.38%   |
| Modem                    | 2         | 0.38%   |
| Dvb card                 | 2         | 0.38%   |
| Wireless                 | 1         | 0.19%   |
| Storage                  | 1         | 0.19%   |

