Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

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

Total: 130

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | X540LA                      | Notebook    | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion        | P6816                       | Notebook    | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo        | ThinkPad L450 20DT0000GE    | Notebook    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [a11de13c4f](https://linux-hardware.org/?probe=a11de13c4f) | Oct 04, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [6de76ddb0e](https://linux-hardware.org/?probe=6de76ddb0e) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Lenovo        | ThinkPad T430s 2356FG9      | Notebook    | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius      | NS585                       | Notebook    | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | Desktop     | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Dell          | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell          | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell          | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Dell          | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP            | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI           | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP            | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | Desktop     | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell          | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP            | 2179                        | Desktop     | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron      | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI           | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell          | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 86        | 86.87%  |
| Xero         | 13        | 13.13%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 98        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.16.15-arch1-1    | 6         | 5.61%   |
| 5.18.16-arch1-1    | 4         | 3.74%   |
| 5.17.9-arch1-1     | 3         | 2.8%    |
| 5.16.2-arch1-1     | 3         | 2.8%    |
| 5.16.1-arch1-1     | 3         | 2.8%    |
| 5.15.33-1-lts      | 3         | 2.8%    |
| 5.14.14-arch1-1    | 3         | 2.8%    |
| 6.1.1-arch1-1      | 2         | 1.87%   |
| 6.0.7-arch1-1      | 2         | 1.87%   |
| 6.0.12-arch1-1     | 2         | 1.87%   |
| 5.19.13-arch1-1    | 2         | 1.87%   |
| 5.19.12-arch1-1    | 2         | 1.87%   |
| 5.18.3-arch1-1     | 2         | 1.87%   |
| 5.18.11-arch1-1    | 2         | 1.87%   |
| 5.17.5-arch1-1     | 2         | 1.87%   |
| 5.17.1-arch1-1     | 2         | 1.87%   |
| 5.16.8-arch1-1     | 2         | 1.87%   |
| 5.16.16-arch1-1    | 2         | 1.87%   |
| 5.16.13-arch1-1    | 2         | 1.87%   |
| 5.16.12-arch1-1    | 2         | 1.87%   |
| 5.15.10-arch1-1    | 2         | 1.87%   |
| 5.14.8-zen1-1-zen  | 2         | 1.87%   |
| 6.0.9-arch1-1      | 1         | 0.93%   |
| 6.0.8-zen1-1-zen   | 1         | 0.93%   |
| 6.0.8-arch1-1      | 1         | 0.93%   |
| 6.0.6-zen1-1-zen   | 1         | 0.93%   |
| 6.0.6-arch1-1      | 1         | 0.93%   |
| 6.0.2-zen1-1-zen   | 1         | 0.93%   |
| 6.0.2-arch1-1      | 1         | 0.93%   |
| 6.0.11-arch1-1     | 1         | 0.93%   |
| 6.0.1-arch2-1      | 1         | 0.93%   |
| 5.19.9-arch1-1     | 1         | 0.93%   |
| 5.19.3-arch1-1     | 1         | 0.93%   |
| 5.19.2-zen1-1-zen  | 1         | 0.93%   |
| 5.19.13-zen1-1-zen | 1         | 0.93%   |
| 5.19.10-arch1-1    | 1         | 0.93%   |
| 5.19.1-arch2-1     | 1         | 0.93%   |
| 5.18.9-arch1-1     | 1         | 0.93%   |
| 5.18.6-arch1-1     | 1         | 0.93%   |
| 5.18.0-arch1-1     | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 5.61%   |
| 5.18.16 | 4         | 3.74%   |
| 5.14.14 | 4         | 3.74%   |
| 5.19.13 | 3         | 2.8%    |
| 5.17.9  | 3         | 2.8%    |
| 5.16.2  | 3         | 2.8%    |
| 5.16.16 | 3         | 2.8%    |
| 5.16.1  | 3         | 2.8%    |
| 5.15.33 | 3         | 2.8%    |
| 5.15.12 | 3         | 2.8%    |
| 5.14.8  | 3         | 2.8%    |
| 5.14.16 | 3         | 2.8%    |
| 6.1.1   | 2         | 1.87%   |
| 6.0.8   | 2         | 1.87%   |
| 6.0.7   | 2         | 1.87%   |
| 6.0.6   | 2         | 1.87%   |
| 6.0.2   | 2         | 1.87%   |
| 6.0.12  | 2         | 1.87%   |
| 5.19.12 | 2         | 1.87%   |
| 5.18.3  | 2         | 1.87%   |
| 5.18.11 | 2         | 1.87%   |
| 5.17.5  | 2         | 1.87%   |
| 5.17.1  | 2         | 1.87%   |
| 5.16.8  | 2         | 1.87%   |
| 5.16.13 | 2         | 1.87%   |
| 5.16.12 | 2         | 1.87%   |
| 5.15.13 | 2         | 1.87%   |
| 5.15.11 | 2         | 1.87%   |
| 5.15.10 | 2         | 1.87%   |
| 6.0.9   | 1         | 0.93%   |
| 6.0.11  | 1         | 0.93%   |
| 6.0.1   | 1         | 0.93%   |
| 5.19.9  | 1         | 0.93%   |
| 5.19.3  | 1         | 0.93%   |
| 5.19.2  | 1         | 0.93%   |
| 5.19.10 | 1         | 0.93%   |
| 5.19.1  | 1         | 0.93%   |
| 5.18.9  | 1         | 0.93%   |
| 5.18.6  | 1         | 0.93%   |
| 5.18.0  | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 21.9%   |
| 5.15    | 18        | 17.14%  |
| 6.0     | 13        | 12.38%  |
| 5.14    | 13        | 12.38%  |
| 5.18    | 11        | 10.48%  |
| 5.19    | 10        | 9.52%   |
| 5.17    | 8         | 7.62%   |
| 5.10    | 3         | 2.86%   |
| 6.1     | 2         | 1.9%    |
| 5.13    | 2         | 1.9%    |
| 5.12    | 1         | 0.95%   |
| 5.11    | 1         | 0.95%   |

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


| Name   | Computers | Percent |
|--------|-----------|---------|
| KDE5   | 91        | 91%     |
| XFCE   | 4         | 4%      |
| GNOME  | 3         | 3%      |
| LeftWM | 1         | 1%      |
| KDE    | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 85        | 86.73%  |
| Wayland | 11        | 11.22%  |
| Tty     | 2         | 2.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 66        | 64.71%  |
| Unknown | 18        | 17.65%  |
| LightDM | 15        | 14.71%  |
| GDM     | 2         | 1.96%   |
| TDM     | 1         | 0.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 52        | 52.53%  |
| en_IN | 7         | 7.07%   |
| en_GB | 6         | 6.06%   |
| de_DE | 5         | 5.05%   |
| C     | 5         | 5.05%   |
| pl_PL | 4         | 4.04%   |
| ru_RU | 3         | 3.03%   |
| it_IT | 3         | 3.03%   |
| en_AU | 3         | 3.03%   |
| fr_FR | 2         | 2.02%   |
| es_MX | 2         | 2.02%   |
| vi_VN | 1         | 1.01%   |
| en_IL | 1         | 1.01%   |
| en_DK | 1         | 1.01%   |
| en_CA | 1         | 1.01%   |
| en_AG | 1         | 1.01%   |
| de_AT | 1         | 1.01%   |
| ba_RU | 1         | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 65        | 65.66%  |
| BIOS | 34        | 34.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 57        | 57%     |
| Xfs     | 21        | 21%     |
| Ext4    | 16        | 16%     |
| Overlay | 6         | 6%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 68        | 68.69%  |
| Unknown | 18        | 18.18%  |
| MBR     | 13        | 13.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 76.47%  |
| Yes       | 24        | 23.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 63        | 64.29%  |
| Yes       | 35        | 35.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 29        | 29.59%  |
| Lenovo              | 18        | 18.37%  |
| Dell                | 13        | 13.27%  |
| Hewlett-Packard     | 11        | 11.22%  |
| MSI                 | 6         | 6.12%   |
| Gigabyte Technology | 4         | 4.08%   |
| Acer                | 4         | 4.08%   |
| ASRock              | 3         | 3.06%   |
| Pegatron            | 2         | 2.04%   |
| HUAWEI              | 2         | 2.04%   |
| Toshiba             | 1         | 1.02%   |
| Medion              | 1         | 1.02%   |
| BESSTAR Tech        | 1         | 1.02%   |
| Aquarius            | 1         | 1.02%   |
| Apple               | 1         | 1.02%   |
| Unknown             | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 3.06%   |
| MSI MS-7971                                | 2         | 2.04%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 2.04%   |
| Toshiba TECRA A11                          | 1         | 1.02%   |
| Pegatron p6-2026                           | 1         | 1.02%   |
| Pegatron D15K                              | 1         | 1.02%   |
| MSI MS-7B61                                | 1         | 1.02%   |
| MSI Katana GF66 11UE                       | 1         | 1.02%   |
| MSI GP73 Leopard 8RD                       | 1         | 1.02%   |
| MSI GF63 Thin 9SCX                         | 1         | 1.02%   |
| Medion P6816                               | 1         | 1.02%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 1.02%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 1.02%   |
| Lenovo ThinkPad Yoga 370 20JJS0SB00        | 1         | 1.02%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 1.02%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 1.02%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 1.02%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 1.02%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 1.02%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 1.02%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 1.02%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 1.02%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.02%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.02%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 1.02%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 1.02%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 1.02%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 1.02%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 1.02%   |
| HUAWEI WRT-WX9                             | 1         | 1.02%   |
| HUAWEI BOM-WXX9                            | 1         | 1.02%   |
| HP ZBook 15 G4                             | 1         | 1.02%   |
| HP Z230 SFF Workstation                    | 1         | 1.02%   |
| HP ProOne 400 G1 AiO                       | 1         | 1.02%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 1         | 1.02%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 1.02%   |
| HP Notebook                                | 1         | 1.02%   |
| HP Laptop 15s-fq2xxx                       | 1         | 1.02%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.02%   |
| HP Laptop 15-da0xxx                        | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 8         | 8.16%   |
| ASUS ROG             | 7         | 7.14%   |
| Lenovo IdeaPad       | 5         | 5.1%    |
| ASUS TUF             | 5         | 5.1%    |
| Dell Precision       | 4         | 4.08%   |
| Dell Latitude        | 4         | 4.08%   |
| ASUS VivoBook        | 4         | 4.08%   |
| Acer Aspire          | 4         | 4.08%   |
| Lenovo Legion        | 3         | 3.06%   |
| HP Laptop            | 3         | 3.06%   |
| MSI MS-7971          | 2         | 2.04%   |
| HP Pavilion          | 2         | 2.04%   |
| Dell Inspiron        | 2         | 2.04%   |
| ASUS PRIME           | 2         | 2.04%   |
| ASUS ASUS            | 2         | 2.04%   |
| Toshiba TECRA        | 1         | 1.02%   |
| Pegatron p6-2026     | 1         | 1.02%   |
| Pegatron D15K        | 1         | 1.02%   |
| MSI MS-7B61          | 1         | 1.02%   |
| MSI Katana           | 1         | 1.02%   |
| MSI GP73             | 1         | 1.02%   |
| MSI GF63             | 1         | 1.02%   |
| Medion P6816         | 1         | 1.02%   |
| Lenovo Yoga          | 1         | 1.02%   |
| Lenovo Y520-15IKBN   | 1         | 1.02%   |
| HUAWEI WRT-WX9       | 1         | 1.02%   |
| HUAWEI BOM-WXX9      | 1         | 1.02%   |
| HP ZBook             | 1         | 1.02%   |
| HP Z230              | 1         | 1.02%   |
| HP ProOne            | 1         | 1.02%   |
| HP Notebook          | 1         | 1.02%   |
| HP ENVY              | 1         | 1.02%   |
| HP Compaq            | 1         | 1.02%   |
| Gigabyte Z170X-UD3   | 1         | 1.02%   |
| Gigabyte X570        | 1         | 1.02%   |
| Gigabyte B460MDS3HV2 | 1         | 1.02%   |
| Gigabyte A320M-S2H   | 1         | 1.02%   |
| Dell Vostro          | 1         | 1.02%   |
| Dell Venue           | 1         | 1.02%   |
| Dell OptiPlex        | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 19        | 19.39%  |
| 2020 | 13        | 13.27%  |
| 2018 | 11        | 11.22%  |
| 2017 | 10        | 10.2%   |
| 2021 | 9         | 9.18%   |
| 2012 | 8         | 8.16%   |
| 2015 | 6         | 6.12%   |
| 2013 | 6         | 6.12%   |
| 2016 | 3         | 3.06%   |
| 2014 | 3         | 3.06%   |
| 2011 | 3         | 3.06%   |
| 2010 | 3         | 3.06%   |
| 2009 | 2         | 2.04%   |
| 2022 | 1         | 1.02%   |
| 2008 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 59        | 60.2%   |
| Desktop     | 35        | 35.71%  |
| Convertible | 3         | 3.06%   |
| Server      | 1         | 1.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 98        | 100%    |

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
| 4.01-8.0    | 28        | 28.57%  |
| 16.01-24.0  | 24        | 24.49%  |
| 8.01-16.0   | 19        | 19.39%  |
| 32.01-64.0  | 12        | 12.24%  |
| 3.01-4.0    | 10        | 10.2%   |
| 24.01-32.0  | 3         | 3.06%   |
| 64.01-256.0 | 2         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 36        | 33.64%  |
| 1.01-2.0   | 25        | 23.36%  |
| 4.01-8.0   | 20        | 18.69%  |
| 3.01-4.0   | 13        | 12.15%  |
| 8.01-16.0  | 5         | 4.67%   |
| 16.01-24.0 | 4         | 3.74%   |
| 0.51-1.0   | 2         | 1.87%   |
| 0.01-0.5   | 2         | 1.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 55.1%   |
| 2      | 25        | 25.51%  |
| 3      | 9         | 9.18%   |
| 4      | 5         | 5.1%    |
| 6      | 2         | 2.04%   |
| 5      | 2         | 2.04%   |
| 7      | 1         | 1.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 77.55%  |
| Yes       | 22        | 22.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 80.61%  |
| No        | 19        | 19.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 81.63%  |
| No        | 18        | 18.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 74.75%  |
| No        | 25        | 25.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 21        | 21.43%  |
| India                  | 9         | 9.18%   |
| Germany                | 7         | 7.14%   |
| Poland                 | 5         | 5.1%    |
| Russia                 | 4         | 4.08%   |
| Italy                  | 4         | 4.08%   |
| France                 | 4         | 4.08%   |
| UK                     | 3         | 3.06%   |
| Greece                 | 3         | 3.06%   |
| Australia              | 3         | 3.06%   |
| Turkey                 | 2         | 2.04%   |
| Sweden                 | 2         | 2.04%   |
| Norway                 | 2         | 2.04%   |
| Netherlands            | 2         | 2.04%   |
| Mexico                 | 2         | 2.04%   |
| Lebanon                | 2         | 2.04%   |
| Canada                 | 2         | 2.04%   |
| Zambia                 | 1         | 1.02%   |
| Vietnam                | 1         | 1.02%   |
| Togo                   | 1         | 1.02%   |
| Spain                  | 1         | 1.02%   |
| Romania                | 1         | 1.02%   |
| Portugal               | 1         | 1.02%   |
| Palestinian Territory  | 1         | 1.02%   |
| Pakistan               | 1         | 1.02%   |
| Morocco                | 1         | 1.02%   |
| Mongolia               | 1         | 1.02%   |
| Malaysia               | 1         | 1.02%   |
| Israel                 | 1         | 1.02%   |
| Hungary                | 1         | 1.02%   |
| Denmark                | 1         | 1.02%   |
| Cyprus                 | 1         | 1.02%   |
| Colombia               | 1         | 1.02%   |
| Chile                  | 1         | 1.02%   |
| Brazil                 | 1         | 1.02%   |
| Bosnia and Herzegovina | 1         | 1.02%   |
| Austria                | 1         | 1.02%   |
| Argentina              | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Longmont       | 3         | 3.06%   |
| Madurai        | 2         | 2.04%   |
| Istanbul       | 2         | 2.04%   |
| Bremen         | 2         | 2.04%   |
| Beirut         | 2         | 2.04%   |
| Zenica         | 1         | 1.02%   |
| Zell am See    | 1         | 1.02%   |
| Wroclaw        | 1         | 1.02%   |
| Wrexham        | 1         | 1.02%   |
| Wells          | 1         | 1.02%   |
| Warsaw         | 1         | 1.02%   |
| Ulan Bator     | 1         | 1.02%   |
| Ufa            | 1         | 1.02%   |
| Toronto        | 1         | 1.02%   |
| Tel Aviv       | 1         | 1.02%   |
| Taranto        | 1         | 1.02%   |
| Stuttgart      | 1         | 1.02%   |
| Stockholm      | 1         | 1.02%   |
| Stavropol      | 1         | 1.02%   |
| Springfield    | 1         | 1.02%   |
| Silkeborg      | 1         | 1.02%   |
| Shadrinsk      | 1         | 1.02%   |
| Seattle        | 1         | 1.02%   |
| Santa Cruz     | 1         | 1.02%   |
| Salt Lake City | 1         | 1.02%   |
| Ramallah       | 1         | 1.02%   |
| Pune           | 1         | 1.02%   |
| Poznan         | 1         | 1.02%   |
| Portland       | 1         | 1.02%   |
| Porcia         | 1         | 1.02%   |
| Pirmasens      | 1         | 1.02%   |
| Phoenix        | 1         | 1.02%   |
| Perth          | 1         | 1.02%   |
| Pavia          | 1         | 1.02%   |
| Passos         | 1         | 1.02%   |
| Paris          | 1         | 1.02%   |
| Oslo           | 1         | 1.02%   |
| Oberursel      | 1         | 1.02%   |
| Nicosia        | 1         | 1.02%   |
| New Haven      | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 30        | 44     | 18.52%  |
| Samsung Electronics         | 28        | 39     | 17.28%  |
| WDC                         | 22        | 31     | 13.58%  |
| Kingston                    | 12        | 16     | 7.41%   |
| Toshiba                     | 9         | 11     | 5.56%   |
| Intel                       | 7         | 9      | 4.32%   |
| HGST                        | 6         | 6      | 3.7%    |
| Sandisk                     | 5         | 7      | 3.09%   |
| Micron Technology           | 4         | 6      | 2.47%   |
| China                       | 4         | 4      | 2.47%   |
| Unknown                     | 3         | 4      | 1.85%   |
| Phison                      | 3         | 3      | 1.85%   |
| Hitachi                     | 3         | 3      | 1.85%   |
| Transcend                   | 2         | 2      | 1.23%   |
| LITEON                      | 2         | 2      | 1.23%   |
| KIOXIA                      | 2         | 2      | 1.23%   |
| Crucial                     | 2         | 2      | 1.23%   |
| XPG                         | 1         | 1      | 0.62%   |
| SK hynix                    | 1         | 1      | 0.62%   |
| Silicon Motion              | 1         | 1      | 0.62%   |
| Realtek Semiconductor       | 1         | 1      | 0.62%   |
| PNY                         | 1         | 1      | 0.62%   |
| Plextor                     | 1         | 1      | 0.62%   |
| OSCOO                       | 1         | 1      | 0.62%   |
| Micron/Crucial Technology   | 1         | 1      | 0.62%   |
| LITEONIT                    | 1         | 1      | 0.62%   |
| Kingston Technology Company | 1         | 1      | 0.62%   |
| Intenso                     | 1         | 1      | 0.62%   |
| Inateck                     | 1         | 1      | 0.62%   |
| GOODRAM                     | 1         | 1      | 0.62%   |
| Biostar                     | 1         | 1      | 0.62%   |
| Apple                       | 1         | 1      | 0.62%   |
| Apacer                      | 1         | 1      | 0.62%   |
| A-DATA Technology           | 1         | 1      | 0.62%   |
| 2-Power                     | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.63%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.63%   |
| Seagate One Touch HDD 5TB                           | 3         | 1.63%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.63%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.09%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 1.09%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 1.09%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 1.09%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 1.09%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 1.09%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 1.09%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 1.09%   |
| HGST HTS545050A7E680 500GB                          | 2         | 1.09%   |
| China SSD 1TB                                       | 2         | 1.09%   |
| XPG GAMMIX S50 1TB                                  | 1         | 0.54%   |
| WDC WDS512G1X0C-00ENX0 512GB                        | 1         | 0.54%   |
| WDC WDS500G3XHC-00SJG0 500GB                        | 1         | 0.54%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.54%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.54%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.54%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.54%   |
| WDC WD800JD-00MSA1 80GB                             | 1         | 0.54%   |
| WDC WD7500BPKT-75PK4T0 752GB                        | 1         | 0.54%   |
| WDC WD6400AAKS-22A7B2 640GB                         | 1         | 0.54%   |
| WDC WD5000AAVS-00ZTB0 500GB                         | 1         | 0.54%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 0.54%   |
| WDC WD40EZRZ-22GXCB0 4TB                            | 1         | 0.54%   |
| WDC WD2500BEVT-60ZCT1 250GB                         | 1         | 0.54%   |
| WDC WD20EZRZ-60Z5HB0 2TB                            | 1         | 0.54%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 1         | 0.54%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 1         | 0.54%   |
| WDC WD15EADS-11R6B1 1TB                             | 1         | 0.54%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1         | 0.54%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 1         | 0.54%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1         | 0.54%   |
| WDC WD10EAVS-00D7B1 1TB                             | 1         | 0.54%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 43     | 50%     |
| WDC                 | 13        | 19     | 21.67%  |
| Toshiba             | 6         | 8      | 10%     |
| HGST                | 6         | 6      | 10%     |
| Hitachi             | 3         | 3      | 5%      |
| Samsung Electronics | 2         | 2      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 27.66%  |
| Kingston            | 8         | 11     | 17.02%  |
| China               | 4         | 4      | 8.51%   |
| WDC                 | 3         | 3      | 6.38%   |
| Transcend           | 2         | 2      | 4.26%   |
| LITEON              | 2         | 2      | 4.26%   |
| Crucial             | 2         | 2      | 4.26%   |
| SanDisk             | 1         | 1      | 2.13%   |
| PNY                 | 1         | 1      | 2.13%   |
| Plextor             | 1         | 1      | 2.13%   |
| OSCOO               | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| LITEONIT            | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| GOODRAM             | 1         | 1      | 2.13%   |
| Biostar             | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |
| Apacer              | 1         | 1      | 2.13%   |
| 2-Power             | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 50        | 71     | 34.97%  |
| HDD  | 50        | 81     | 34.97%  |
| SSD  | 40        | 53     | 27.97%  |
| MMC  | 3         | 4      | 2.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 68        | 126    | 52.71%  |
| NVMe | 50        | 70     | 38.76%  |
| SAS  | 8         | 9      | 6.2%    |
| MMC  | 3         | 4      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 61     | 43.3%   |
| 0.51-1.0   | 35        | 46     | 36.08%  |
| 1.01-2.0   | 9         | 13     | 9.28%   |
| 4.01-10.0  | 8         | 11     | 8.25%   |
| 3.01-4.0   | 2         | 2      | 2.06%   |
| 2.01-3.0   | 1         | 1      | 1.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 27        | 26.21%  |
| 1001-2000      | 20        | 19.42%  |
| 251-500        | 14        | 13.59%  |
| 501-1000       | 12        | 11.65%  |
| 101-250        | 8         | 7.77%   |
| Unknown        | 8         | 7.77%   |
| 51-100         | 6         | 5.83%   |
| 1-20           | 4         | 3.88%   |
| 21-50          | 2         | 1.94%   |
| 2001-3000      | 2         | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 23.3%   |
| 1-20           | 18        | 17.48%  |
| 51-100         | 17        | 16.5%   |
| 251-500        | 9         | 8.74%   |
| 21-50          | 9         | 8.74%   |
| Unknown        | 8         | 7.77%   |
| 501-1000       | 7         | 6.8%    |
| 2001-3000      | 5         | 4.85%   |
| More than 3000 | 3         | 2.91%   |
| 1001-2000      | 3         | 2.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 4.76%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 1         | 2      | 4.76%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 4.76%   |
| Toshiba MK4058GSX 400GB                                         | 1         | 1      | 4.76%   |
| Seagate ST9500420AS 500GB                                       | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 4.76%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 4.76%   |
| Seagate ST31000524AS 1TB                                        | 1         | 1      | 4.76%   |
| Seagate ST2000VX000-1CU164 2TB                                  | 1         | 1      | 4.76%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 1         | 1      | 4.76%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 4.76%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 4.76%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 4.76%   |
| Kingston SV300S37A120G 120GB SSD                                | 1         | 1      | 4.76%   |
| Kingston SUV400S37240G 240GB SSD                                | 1         | 1      | 4.76%   |
| Hitachi HTS725050A9A364 500GB                                   | 1         | 1      | 4.76%   |
| Hitachi HCP725050GLA380 500GB                                   | 1         | 1      | 4.76%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 4.76%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 4.76%   |
| China SATA3 240GB SSD                                           | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 40%     |
| WDC                 | 2         | 3      | 10%     |
| Toshiba             | 2         | 3      | 10%     |
| Kingston            | 2         | 2      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| HGST                | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |
| China               | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 50%     |
| WDC     | 2         | 3      | 12.5%   |
| Toshiba | 2         | 3      | 12.5%   |
| Hitachi | 2         | 2      | 12.5%   |
| HGST    | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 78.95%  |
| SSD  | 3         | 3      | 15.79%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Works    | 74        | 132    | 64.35%  |
| Detected | 23        | 55     | 20%     |
| Malfunc  | 18        | 22     | 15.65%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 73        | 51.77%  |
| AMD                          | 17        | 12.06%  |
| Samsung Electronics          | 15        | 10.64%  |
| SanDisk                      | 11        | 7.8%    |
| Kingston Technology Company  | 5         | 3.55%   |
| Micron Technology            | 4         | 2.84%   |
| Toshiba America Info Systems | 3         | 2.13%   |
| Phison Electronics           | 3         | 2.13%   |
| Realtek Semiconductor        | 2         | 1.42%   |
| KIOXIA                       | 2         | 1.42%   |
| SK hynix                     | 1         | 0.71%   |
| Silicon Motion               | 1         | 0.71%   |
| Seagate Technology           | 1         | 0.71%   |
| Micron/Crucial Technology    | 1         | 0.71%   |
| ASMedia Technology           | 1         | 0.71%   |
| ADATA Technology             | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 10.46%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 3.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.27%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 3.27%   |
| Micron Non-Volatile memory controller                                          | 4         | 2.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.61%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.96%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.96%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.96%   |
| Intel SSD 660P Series                                                          | 3         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.96%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.31%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.31%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.31%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.31%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.31%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.31%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.31%   |
| AMD FCH SATA Controller D                                                      | 2         | 1.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.65%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.65%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.65%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 75        | 53.57%  |
| NVMe | 50        | 35.71%  |
| RAID | 15        | 10.71%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 77        | 78.57%  |
| AMD    | 21        | 21.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 4.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 3.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 3.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 3.03%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 3.03%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 2.02%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 2.02%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 2.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 2.02%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 2         | 2.02%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 2         | 2.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 2.02%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 2.02%   |
| Intel Genuine CPU 0000 @ 2.10GHz        | 1         | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.01%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.01%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 1.01%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.01%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.01%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 1.01%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.01%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 1.01%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.01%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.01%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.01%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.01%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.01%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 1         | 1.01%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 1         | 1.01%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1         | 1.01%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 1.01%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1         | 1.01%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.01%   |
| Intel Core i5-6600 CPU @ 3.30GHz        | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 30        | 30.3%   |
| Intel Core i7     | 27        | 27.27%  |
| AMD Ryzen 5       | 9         | 9.09%   |
| Other             | 8         | 8.08%   |
| AMD Ryzen 7       | 8         | 8.08%   |
| Intel Core i3     | 7         | 7.07%   |
| Intel Celeron     | 2         | 2.02%   |
| Intel Genuine     | 1         | 1.01%   |
| Intel Core 2 Quad | 1         | 1.01%   |
| Intel Core 2 Duo  | 1         | 1.01%   |
| AMD Ryzen 9       | 1         | 1.01%   |
| AMD Ryzen 3       | 1         | 1.01%   |
| AMD Athlon        | 1         | 1.01%   |
| AMD A8            | 1         | 1.01%   |
| AMD A6            | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 43        | 43.43%  |
| 2      | 29        | 29.29%  |
| 6      | 16        | 16.16%  |
| 8      | 10        | 10.1%   |
| 12     | 1         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 81        | 81.82%  |
| 1      | 18        | 18.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 20.79%  |
| 0x806c1    | 7         | 6.93%   |
| 0x906ea    | 6         | 5.94%   |
| 0x306a9    | 6         | 5.94%   |
| 0x806ec    | 5         | 4.95%   |
| 0x806e9    | 5         | 4.95%   |
| 0x506e3    | 4         | 3.96%   |
| 0x08701021 | 4         | 3.96%   |
| 0x906e9    | 3         | 2.97%   |
| 0x806eb    | 3         | 2.97%   |
| 0x306c3    | 3         | 2.97%   |
| 0x206a7    | 3         | 2.97%   |
| 0x0a201016 | 3         | 2.97%   |
| 0x906ed    | 2         | 1.98%   |
| 0x906eb    | 2         | 1.98%   |
| 0x40651    | 2         | 1.98%   |
| 0x1067a    | 2         | 1.98%   |
| 0x08108109 | 2         | 1.98%   |
| 0xa0653    | 1         | 0.99%   |
| 0xa0652    | 1         | 0.99%   |
| 0x806d1    | 1         | 0.99%   |
| 0x706e5    | 1         | 0.99%   |
| 0x706a8    | 1         | 0.99%   |
| 0x406e3    | 1         | 0.99%   |
| 0x306d4    | 1         | 0.99%   |
| 0x20655    | 1         | 0.99%   |
| 0x20652    | 1         | 0.99%   |
| 0x106e5    | 1         | 0.99%   |
| 0x0a50000b | 1         | 0.99%   |
| 0x0a20120a | 1         | 0.99%   |
| 0x08701013 | 1         | 0.99%   |
| 0x08608103 | 1         | 0.99%   |
| 0x08600106 | 1         | 0.99%   |
| 0x0810100b | 1         | 0.99%   |
| 0x06006705 | 1         | 0.99%   |
| 0x0600611a | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 30.3%   |
| Zen 2         | 9         | 9.09%   |
| Haswell       | 9         | 9.09%   |
| IvyBridge     | 8         | 8.08%   |
| TigerLake     | 7         | 7.07%   |
| Zen 3         | 5         | 5.05%   |
| Skylake       | 5         | 5.05%   |
| Zen+          | 4         | 4.04%   |
| SandyBridge   | 4         | 4.04%   |
| Westmere      | 2         | 2.02%   |
| Penryn        | 2         | 2.02%   |
| Nehalem       | 2         | 2.02%   |
| IceLake       | 2         | 2.02%   |
| Goldmont plus | 2         | 2.02%   |
| Excavator     | 2         | 2.02%   |
| CometLake     | 2         | 2.02%   |
| Broadwell     | 2         | 2.02%   |
| Zen           | 1         | 1.01%   |
| Unknown       | 1         | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 61        | 45.86%  |
| Nvidia | 50        | 37.59%  |
| AMD    | 22        | 16.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 4.48%   |
| Intel HD Graphics 620                                                     | 5         | 3.73%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 3.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.99%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 2.24%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 3         | 2.24%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 2.24%   |
| Intel UHD Graphics 620                                                    | 3         | 2.24%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 2.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.24%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 3         | 2.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.49%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 2         | 1.49%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2         | 1.49%   |
| Nvidia GM108M [GeForce 940MX]                                             | 2         | 1.49%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.49%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.49%   |
| Intel HD Graphics 630                                                     | 2         | 1.49%   |
| Intel HD Graphics 5500                                                    | 2         | 1.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.49%   |
| AMD Renoir                                                                | 2         | 1.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.49%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 2         | 1.49%   |
| Nvidia TU117M                                                             | 1         | 0.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.75%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 28        | 28.57%  |
| 1 x Intel      | 28        | 28.57%  |
| 1 x Nvidia     | 18        | 18.37%  |
| 1 x AMD        | 16        | 16.33%  |
| Intel + AMD    | 3         | 3.06%   |
| AMD + Nvidia   | 3         | 3.06%   |
| 2 x Nvidia     | 1         | 1.02%   |
| 2 x Intel      | 1         | 1.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 61        | 61.62%  |
| Proprietary | 36        | 36.36%  |
| Unknown     | 2         | 2.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 59.6%   |
| 1.01-2.0   | 15        | 15.15%  |
| 7.01-8.0   | 6         | 6.06%   |
| 5.01-6.0   | 6         | 6.06%   |
| 0.01-0.5   | 5         | 5.05%   |
| 3.01-4.0   | 4         | 4.04%   |
| 8.01-16.0  | 3         | 3.03%   |
| 0.51-1.0   | 1         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 18        | 15.79%  |
| AU Optronics         | 16        | 14.04%  |
| BOE                  | 12        | 10.53%  |
| Chimei Innolux       | 11        | 9.65%   |
| LG Display           | 10        | 8.77%   |
| Goldstar             | 5         | 4.39%   |
| Ancor Communications | 5         | 4.39%   |
| Acer                 | 5         | 4.39%   |
| Dell                 | 4         | 3.51%   |
| Sharp                | 3         | 2.63%   |
| AOC                  | 3         | 2.63%   |
| PANDA                | 2         | 1.75%   |
| Iiyama               | 2         | 1.75%   |
| Hewlett-Packard      | 2         | 1.75%   |
| Apple                | 2         | 1.75%   |
| Sceptre Tech         | 1         | 0.88%   |
| MSI                  | 1         | 0.88%   |
| LGD                  | 1         | 0.88%   |
| Lenovo               | 1         | 0.88%   |
| Kogan                | 1         | 0.88%   |
| KOC                  | 1         | 0.88%   |
| JRY                  | 1         | 0.88%   |
| Idek Iiyama          | 1         | 0.88%   |
| Hitachi              | 1         | 0.88%   |
| Gigabyte Technology  | 1         | 0.88%   |
| FOX                  | 1         | 0.88%   |
| CSO                  | 1         | 0.88%   |
| BenQ                 | 1         | 0.88%   |
| ASUSTek Computer     | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 2.56%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 1.71%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 950x540mm 43.0-inch   | 2         | 1.71%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.71%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 0.85%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.85%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.85%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.85%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1         | 0.85%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.85%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1         | 0.85%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 0.85%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 0.85%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch       | 1         | 0.85%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.85%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.85%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                         | 1         | 0.85%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.85%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD0561 1920x1080 294x165mm 13.3-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.85%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD03D7 1366x768 309x174mm 14.0-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 0.85%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 0.85%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 0.85%   |
| Kogan HDMI1 KGN3400 3440x1440 796x334mm 34.0-inch                       | 1         | 0.85%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch                 | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 61        | 56.48%  |
| 1366x768 (WXGA)    | 13        | 12.04%  |
| 3840x2160 (4K)     | 8         | 7.41%   |
| 2560x1440 (QHD)    | 6         | 5.56%   |
| 3440x1440          | 5         | 4.63%   |
| 2560x1080          | 3         | 2.78%   |
| 1600x900 (HD+)     | 3         | 2.78%   |
| 3840x2400          | 1         | 0.93%   |
| 3840x1080          | 1         | 0.93%   |
| 3200x1800 (QHD+)   | 1         | 0.93%   |
| 2160x1440          | 1         | 0.93%   |
| 1920x540           | 1         | 0.93%   |
| 1920x1200 (WUXGA)  | 1         | 0.93%   |
| 1680x1050 (WSXGA+) | 1         | 0.93%   |
| 1440x900 (WXGA+)   | 1         | 0.93%   |
| 1280x1024 (SXGA)   | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 33.33%  |
| 27      | 10        | 8.77%   |
| 23      | 10        | 8.77%   |
| 14      | 10        | 8.77%   |
| 21      | 7         | 6.14%   |
| 13      | 7         | 6.14%   |
| 34      | 6         | 5.26%   |
| 84      | 4         | 3.51%   |
| 31      | 4         | 3.51%   |
| 24      | 4         | 3.51%   |
| 17      | 3         | 2.63%   |
| Unknown | 3         | 2.63%   |
| 28      | 2         | 1.75%   |
| 18      | 2         | 1.75%   |
| 54      | 1         | 0.88%   |
| 48      | 1         | 0.88%   |
| 20      | 1         | 0.88%   |
| 12      | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 44.74%  |
| 501-600     | 23        | 20.18%  |
| 401-500     | 10        | 8.77%   |
| 701-800     | 6         | 5.26%   |
| 601-700     | 6         | 5.26%   |
| 201-300     | 5         | 4.39%   |
| 351-400     | 4         | 3.51%   |
| 1501-2000   | 4         | 3.51%   |
| Unknown     | 3         | 2.63%   |
| 1001-1500   | 2         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 83.17%  |
| 21/9    | 8         | 7.92%   |
| 16/10   | 4         | 3.96%   |
| Unknown | 2         | 1.98%   |
| 5/4     | 1         | 0.99%   |
| 32/9    | 1         | 0.99%   |
| 3/2     | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 33.63%  |
| 201-250        | 20        | 17.7%   |
| 81-90          | 14        | 12.39%  |
| 351-500        | 10        | 8.85%   |
| 301-350        | 10        | 8.85%   |
| More than 1000 | 5         | 4.42%   |
| 71-80          | 3         | 2.65%   |
| 121-130        | 3         | 2.65%   |
| Unknown        | 3         | 2.65%   |
| 251-300        | 2         | 1.77%   |
| 151-200        | 2         | 1.77%   |
| 61-70          | 1         | 0.88%   |
| 141-150        | 1         | 0.88%   |
| 501-1000       | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 41        | 37.61%  |
| 51-100        | 29        | 26.61%  |
| 101-120       | 26        | 23.85%  |
| 161-240       | 5         | 4.59%   |
| More than 240 | 3         | 2.75%   |
| Unknown       | 3         | 2.75%   |
| 1-50          | 2         | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 76        | 76.77%  |
| 2     | 20        | 20.2%   |
| 0     | 2         | 2.02%   |
| 3     | 1         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 63        | 44.37%  |
| Realtek Semiconductor             | 51        | 35.92%  |
| Qualcomm Atheros                  | 6         | 4.23%   |
| MediaTek                          | 3         | 2.11%   |
| Broadcom Limited                  | 3         | 2.11%   |
| ASIX Electronics                  | 3         | 2.11%   |
| Samsung Electronics               | 2         | 1.41%   |
| Ericsson Business Mobile Networks | 2         | 1.41%   |
| Broadcom                          | 2         | 1.41%   |
| TP-Link                           | 1         | 0.7%    |
| Ralink Technology                 | 1         | 0.7%    |
| Ralink                            | 1         | 0.7%    |
| Qualcomm                          | 1         | 0.7%    |
| NetGear                           | 1         | 0.7%    |
| Microsoft                         | 1         | 0.7%    |
| Marvell Technology Group          | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 37        | 21.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8         | 4.71%   |
| Intel Wi-Fi 6 AX200                                                | 7         | 4.12%   |
| Intel I211 Gigabit Network Connection                              | 6         | 3.53%   |
| Intel Wi-Fi 6 AX201                                                | 5         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 5         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 4         | 2.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 4         | 2.35%   |
| Realtek RTL8125 2.5GbE Controller                                  | 4         | 2.35%   |
| Intel Wireless 8265 / 8275                                         | 4         | 2.35%   |
| Intel Wireless 7260                                                | 4         | 2.35%   |
| Intel Ethernet Connection (2) I219-V                               | 4         | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.35%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 2         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.18%   |
| Intel Wireless-AC 9260                                             | 2         | 1.18%   |
| Intel Wireless 7265                                                | 2         | 1.18%   |
| Intel Ethernet Connection (7) I219-V                               | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.18%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.18%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.18%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 1.18%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 1         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.59%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.59%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 1         | 0.59%   |
| Ralink RT2501/RT2573 Wireless Adapter                              | 1         | 0.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.59%   |
| Qualcomm MegaFon M150-4                                            | 1         | 0.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1         | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 1         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 62.96%  |
| Realtek Semiconductor | 12        | 14.81%  |
| Qualcomm Atheros      | 5         | 6.17%   |
| MediaTek              | 3         | 3.7%    |
| Broadcom Limited      | 3         | 3.7%    |
| Broadcom              | 2         | 2.47%   |
| TP-Link               | 1         | 1.23%   |
| Ralink Technology     | 1         | 1.23%   |
| Ralink                | 1         | 1.23%   |
| NetGear               | 1         | 1.23%   |
| Microsoft             | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 7         | 8.64%   |
| Intel Wi-Fi 6 AX201                                                       | 5         | 6.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 5         | 6.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 6.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 4         | 4.94%   |
| Intel Wireless 8265 / 8275                                                | 4         | 4.94%   |
| Intel Wireless 7260                                                       | 4         | 4.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 4.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 2.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 2.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 2.47%   |
| Intel Wireless-AC 9260                                                    | 2         | 2.47%   |
| Intel Wireless 7265                                                       | 2         | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 2.47%   |
| Intel Centrino Wireless-N 2230                                            | 2         | 2.47%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 2.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 1.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 1.23%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1         | 1.23%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1         | 1.23%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.23%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 1.23%   |
| Intel Wireless 8260                                                       | 1         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 1.23%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 1.23%   |
| Intel Centrino Wireless-N 100                                             | 1         | 1.23%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.23%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 46        | 53.49%  |
| Intel                    | 30        | 34.88%  |
| ASIX Electronics         | 3         | 3.49%   |
| Samsung Electronics      | 2         | 2.33%   |
| Qualcomm Atheros         | 2         | 2.33%   |
| Qualcomm                 | 1         | 1.16%   |
| Marvell Technology Group | 1         | 1.16%   |
| Broadcom                 | 1         | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 42.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 9.2%    |
| Intel I211 Gigabit Network Connection                             | 6         | 6.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 4.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 4.6%    |
| Intel Ethernet Connection (2) I219-V                              | 4         | 4.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.3%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.3%    |
| Qualcomm MegaFon M150-4                                           | 1         | 1.15%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.15%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.15%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.15%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.15%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.15%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.15%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.15%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 49.69%  |
| Ethernet | 79        | 49.07%  |
| Modem    | 2         | 1.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 60.4%   |
| Ethernet | 40        | 39.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 48        | 48.98%  |
| 1     | 45        | 45.92%  |
| 3     | 4         | 4.08%   |
| 0     | 1         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 71.72%  |
| Yes  | 28        | 28.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 55.41%  |
| Broadcom                        | 7         | 9.46%   |
| Realtek Semiconductor           | 6         | 8.11%   |
| Cambridge Silicon Radio         | 6         | 8.11%   |
| IMC Networks                    | 4         | 5.41%   |
| Qualcomm Atheros Communications | 2         | 2.7%    |
| ASUSTek Computer                | 2         | 2.7%    |
| Toshiba                         | 1         | 1.35%   |
| Realtek                         | 1         | 1.35%   |
| MediaTek                        | 1         | 1.35%   |
| Lite-On Technology              | 1         | 1.35%   |
| Dell                            | 1         | 1.35%   |
| Apple                           | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 18.92%  |
| Intel Bluetooth wireless interface                  | 9         | 12.16%  |
| Intel AX200 Bluetooth                               | 7         | 9.46%   |
| Intel AX201 Bluetooth                               | 6         | 8.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 8.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.05%   |
| Realtek Bluetooth Radio                             | 3         | 4.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.7%    |
| IMC Networks Wireless_Device                        | 2         | 2.7%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.7%    |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 2.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.7%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.35%   |
| Realtek Bluetooth Radio                             | 1         | 1.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.35%   |
| MediaTek Wireless_Device                            | 1         | 1.35%   |
| Lite-On Bluetooth Device                            | 1         | 1.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.35%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.35%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.35%   |
| Broadcom BCM2045A0                                  | 1         | 1.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.35%   |
| ASUS Bluetooth Radio                                | 1         | 1.35%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 77        | 51.33%  |
| Nvidia                     | 30        | 20%     |
| AMD                        | 23        | 15.33%  |
| Corsair                    | 3         | 2%      |
| C-Media Electronics        | 3         | 2%      |
| Razer USA                  | 2         | 1.33%   |
| Kingston Technology        | 2         | 1.33%   |
| Tenx Technology            | 1         | 0.67%   |
| Samsung Electronics        | 1         | 0.67%   |
| Realtek Semiconductor      | 1         | 0.67%   |
| PreSonus Audio Electronics | 1         | 0.67%   |
| Plantronics                | 1         | 0.67%   |
| Logitech                   | 1         | 0.67%   |
| Hewlett-Packard            | 1         | 0.67%   |
| Generalplus Technology     | 1         | 0.67%   |
| Barco Display Systems      | 1         | 0.67%   |
| Astro Gaming               | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 9         | 5.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 4.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8         | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 3.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 3.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.84%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 2.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 2.27%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.7%    |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.7%    |
| AMD Navi 10 HDMI Audio                                                     | 3         | 1.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.14%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.14%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.57%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.57%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.57%   |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1         | 0.57%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 24        | 24.24%  |
| Samsung Electronics | 24        | 24.24%  |
| Corsair             | 10        | 10.1%   |
| Micron Technology   | 9         | 9.09%   |
| Crucial             | 8         | 8.08%   |
| Kingston            | 6         | 6.06%   |
| G.Skill             | 6         | 6.06%   |
| Unknown             | 4         | 4.04%   |
| Team                | 2         | 2.02%   |
| Ramaxel Technology  | 2         | 2.02%   |
| Unifosa             | 1         | 1.01%   |
| PNY                 | 1         | 1.01%   |
| Elpida              | 1         | 1.01%   |
| A-DATA Technology   | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 2.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 2.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.89%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 1.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.89%   |
| Kingston RAM KHX2133C14/16G 16384MB DIMM DDR4 2176MT/s              | 2         | 1.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 2         | 1.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                           | 1         | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                            | 1         | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.94%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s                | 1         | 0.94%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                  | 1         | 0.94%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                  | 1         | 0.94%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                       | 1         | 0.94%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.94%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.94%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.94%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 1         | 0.94%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s                  | 1         | 0.94%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.94%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 0.94%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.94%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.94%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.94%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.94%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.94%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.94%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.94%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                           | 1         | 0.94%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                           | 1         | 0.94%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.94%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.94%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 55        | 66.27%  |
| DDR3   | 20        | 24.1%   |
| LPDDR4 | 2         | 2.41%   |
| LPDDR3 | 2         | 2.41%   |
| DDR    | 2         | 2.41%   |
| SDRAM  | 1         | 1.2%    |
| DDR2   | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 57.14%  |
| DIMM         | 28        | 33.33%  |
| Row Of Chips | 8         | 9.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 42        | 46.15%  |
| 4096  | 29        | 31.87%  |
| 16384 | 16        | 17.58%  |
| 2048  | 4         | 4.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 21        | 22.11%  |
| 3200  | 17        | 17.89%  |
| 1600  | 14        | 14.74%  |
| 2400  | 5         | 5.26%   |
| 2133  | 4         | 4.21%   |
| 1333  | 4         | 4.21%   |
| 3600  | 3         | 3.16%   |
| 3266  | 3         | 3.16%   |
| 2933  | 3         | 3.16%   |
| 4267  | 2         | 2.11%   |
| 3400  | 2         | 2.11%   |
| 2666  | 2         | 2.11%   |
| 2176  | 2         | 2.11%   |
| 1800  | 2         | 2.11%   |
| 800   | 2         | 2.11%   |
| 4400  | 1         | 1.05%   |
| 4199  | 1         | 1.05%   |
| 4133  | 1         | 1.05%   |
| 3800  | 1         | 1.05%   |
| 3467  | 1         | 1.05%   |
| 2747  | 1         | 1.05%   |
| 1450  | 1         | 1.05%   |
| 1334  | 1         | 1.05%   |
| 1067  | 1         | 1.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 16        | 24.62%  |
| Chicony Electronics                    | 10        | 15.38%  |
| Acer                                   | 8         | 12.31%  |
| Realtek Semiconductor                  | 7         | 10.77%  |
| Quanta                                 | 4         | 6.15%   |
| Microdia                               | 4         | 6.15%   |
| Syntek                                 | 3         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.62%   |
| Sunplus Innovation Technology          | 2         | 3.08%   |
| Generalplus Technology                 | 2         | 3.08%   |
| Suyin                                  | 1         | 1.54%   |
| Ricoh                                  | 1         | 1.54%   |
| Luxvisions Innotech Limited            | 1         | 1.54%   |
| Logitech                               | 1         | 1.54%   |
| Lite-On Technology                     | 1         | 1.54%   |
| Alpha Imaging Technology               | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 4         | 6.15%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 6.15%   |
| Syntek Integrated Camera                            | 3         | 4.62%   |
| Quanta HP TrueVision HD Camera                      | 3         | 4.62%   |
| IMC Networks Integrated Camera                      | 3         | 4.62%   |
| Acer Integrated Camera                              | 3         | 4.62%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 3.08%   |
| Chicony Integrated Camera                           | 2         | 3.08%   |
| Chicony EasyCamera                                  | 2         | 3.08%   |
| Acer HD Webcam                                      | 2         | 3.08%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.54%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.54%   |
| Sunplus HP Truevision HD                            | 1         | 1.54%   |
| Ricoh Integrated Webcam                             | 1         | 1.54%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.54%   |
| Realtek Integrated Webcam                           | 1         | 1.54%   |
| Realtek Built-In Video Camera                       | 1         | 1.54%   |
| Quanta HD User Facing                               | 1         | 1.54%   |
| Microdia Webcam Vitade AF                           | 1         | 1.54%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 1.54%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.54%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.54%   |
| Logitech Webcam C600                                | 1         | 1.54%   |
| Lite-On Integrated Camera                           | 1         | 1.54%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.54%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.54%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.54%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 1         | 1.54%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.54%   |
| IMC Networks HD Camera                              | 1         | 1.54%   |
| IMC Networks EasyCamera                             | 1         | 1.54%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.54%   |
| Generalplus campark PC04                            | 1         | 1.54%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.54%   |
| Chicony USB2.0 UVC WebCam                           | 1         | 1.54%   |
| Chicony USB 2.0 Camera                              | 1         | 1.54%   |
| Chicony HP Webcam                                   | 1         | 1.54%   |
| Chicony HP High Definition 1MP Webcam               | 1         | 1.54%   |
| Chicony HD User Facing                              | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Shenzhen Goodix Technology | 3         | 27.27%  |
| Elan Microelectronics      | 2         | 18.18%  |
| Synaptics                  | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 2         | 18.18%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 9.09%   |
| Elan fingerprint sensor [FeinTech FPS00200]       | 1         | 9.09%   |
| Elan ELAN:Fingerprint                             | 1         | 9.09%   |
| AuthenTec Fingerprint Sensor                      | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 2         | 28.57%  |
| Broadcom    | 2         | 28.57%  |
| Yubico.com  | 1         | 14.29%  |
| Clay Logic  | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 28.57%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 14.29%  |
| Clay Logic Nitrokey Pro                                    | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 70        | 70.71%  |
| 1     | 25        | 25.25%  |
| 2     | 4         | 4.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 33.33%  |
| Graphics card         | 7         | 21.21%  |
| Chipcard              | 5         | 15.15%  |
| Net/wireless          | 2         | 6.06%   |
| Multimedia controller | 2         | 6.06%   |
| Camera                | 2         | 6.06%   |
| Bluetooth             | 2         | 6.06%   |
| Storage               | 1         | 3.03%   |
| Network               | 1         | 3.03%   |

